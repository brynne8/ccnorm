# ccnorm
Lua Unicode normalization data. It's kind of similar to Skeleton algorithm from Unicode [tr39](http://www.unicode.org/reports/tr39/), while it considers readability and cases.

# Latin letters
Any unicode that looks similar to a latin letter is normalized to latin letters, even if it's a number or a punctuation. Characters are normalized by shape for latin letters, so Greek letter ν (lower case Nu) is normalized to latin letter V.

# Chinese characters
Chinese characters (a.k.a kanji) are normalized to Simplified Chinese as much as possible. The normalized Chinese sentence should be readable by native Chinese people.

# Contributing
The ccnorm.lua is automatically generated, so please report bugs in Issues. Do not send pull requests.
