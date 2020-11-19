# Audiobooks (Audible) metadata agent
Forked from: https://github.com/macr0dev/Audiobooks.bundle

## Changes
* Don't write Narrators and Series to *Genres*
* Do write Narrators to *Styles*
  * Exclude contributors (full cast, …)
* Do write Series to *Collections*
  * **NOTE:** Plex currently fails to present this info
* Write Authors to Moods
  * Excludes contributors (translators, foreword, …)
* Write "Series, Book # - Title" to *Sort Album*
* Correct some audible title formatting quirks (strip superfluous title appends such as " Series, Book X", "A LitRPG Saga", …)
* Added option to prefer copyright year instead of datePublished
  * When no copyright year is found use Jan 1 of datePublished
