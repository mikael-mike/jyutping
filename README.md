# 粵拼
根據 github.com/rime/rime-cantonese 修改嘅粵拼schema，允許現代嘅廣東話讀音

粵拼方案由　[rime-cantonese](https://github.com/rime/rime-cantonese)　中的jyutping及jyutping_ipa版修改而嚟，主要添加以下規則：
1. 字首`n`/`l`不分，例如`lei`可以輸入「你」
2. 允許字首`ng`/`∅`不分，例如`o`可以輸入「我」
3. `ng`字與`m`字不分，例如`m`可以輸入「唔」及「五」
4. `c`(ipa /t͡sʰ/) 及 `z` (ipa /t͡s/) 及 `s` 可以喺 `oe` `eo` `yu` 前輸入爲 `ch` 及 `zh` 及 `sh`

同時提供ipa嘅strict版本，刪去 `eo` `oe` 不分、 `j` `y` 不分等模糊
再提供ipa嘅customized版本，`q` 不作 /ʔ/ 而作 `aa`

## License & Attribution

This project is licensed under the [Creative Commons Attribution 4.0 International (CC-BY-4.0)](https://creativecommons.org/licenses/by/4.0/) license. 

This work is built upon and contains modified material from **[rime-cantonese](https://github.com/rime/rime-cantonese)**.