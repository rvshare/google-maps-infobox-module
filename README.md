# Google Maps InfoBox

---

A browserify optimized module of google maps infobox.

~This repository and npm module only encapsulates the original script into a broserify friendly module, and doesn't modify it's source.~

### RVshare updates

Updated the original source to be able to be pass through a server side renderer. Previously, any SSR would error out due to the global `google` object that was not present.
