# Firefox-Quantum-Sprint

I have done a backward compatibility:
- browser version detection that tells to user if version doesn't support 'let' and 'class';
- - works with Firefox only;
- 'let map;' was replaced by 'var map;'
- 'const' are saved, but 36+ version are needed;
- reworked map.js by Babel;
- add script in HTML to provide variety, include alert about old browser version.

Was tested also in 45.9 ESR and 58 Nightly.
