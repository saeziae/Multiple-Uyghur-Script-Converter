# Multiple-Uyghur-Script-Converter

Forked from original work, refactored for Python 3 and Qt 5, enjoy it!

`python umsc.py`

This converter converts multiple Uyghur scripts such as ULS(Uyghur Latin Script), UAS(Uyghur Arabic Script), CTS(Common Turkish Script).

## Scripts

- Uyghur Ereb Yëziqi (UEY) - arabic script
- Uyghur Latin Yëziqi (ULY) - latin script since 2001
- Common Turkic (Ortaq Türkche Alfabet)
- Uyghur Siril Yëziqi (USY) - cyrillic script
- Uyghur Yëngi Yëziqi (UYY) - latin script used between 1965 and 1982
- Toponymy Transcription [SASM/GNC/SRC transcriptions](https://en.wikipedia.org/wiki/SASM/GNC_romanization) - a modification of UYY, currently used in place names

| Arabic(UEY) | Common Turkic | Latin(ULY) | Cyrillic(USY) | UYY | Toponymy Transcription  |
| ----------- | ------------- | ---------- | ------------- | --- | ----------------------- |
| ا           | a             | a          | а             | a   | a                       |
| ە           | e             | e          | ә             | ə   | a                       |
| ب           | b             | b          | б             | b   | b                       |
| پ           | p             | p          | п             | p   | p                       |
| ت           | t             | t          | т             | t   | t                       |
| ج           | c             | j          | җ             | j   | j                       |
| چ           | ç             | ch         | ч             | q   | q                       |
| خ           | x             | x          | х             | h   | h                       |
| د           | d             | d          | д             | d   | d                       |
| ر           | r             | r          | р             | r   | r                       |
| ز           | z             | z          | з             | z   | z                       |
| ژ           | j             | zh         | ж             | ⱬ   | y, j(final of syllable) |
| س           | s             | s          | с             | s   | s                       |
| ش           | ş             | sh         | ш             | x   | x                       |
| ف           | f             | f          | ф             | f   | f                       |
| ڭ           | ñ             | ng         | ң             | ng  | ng                      |
| ل           | l             | l          | л             | l   | l                       |
| م           | m             | m          | м             | m   | m                       |
| ھ           | h             | h          | һ             | h   | h                       |
| و           | o             | o          | о             | o   | o                       |
| ۇ           | u             | u          | у             | u   | u                       |
| ۆ           | ö             | ö          | ө             | ɵ   | ö                       |
| ۈ           | ü             | ü          | ү             | ü   | ü                       |
| ۋ           | v             | w          | в             | w   | w                       |
| ې           | é             | ë, é       | е             | e   | e                       |
| ى           | i             | i          | и             | i   | i                       |
| ي           | y             | y          | й             | y   | y                       |
| ق           | q             | q          | қ             | ⱪ   | k                       |
| ك           | k             | k          | к             | k   | k                       |
| گ           | g             | g          | г             | g   | g                       |
| ن           | n             | n          | н             | n   | n                       |
| غ           | ğ             | gh         | ғ             | ƣ   | g                       |
| ئ           |               |            |               |     |                         |
| يا          | ya            | ya         | я             | ya  | ya                      |
| يۇ          | yu            | yu         | ю             | yu  | yu                      |

## Examples

- UEY: ھەممە ئادەم تۇغۇلۇشىدىنلا ئەركىن، ئىززەت۔ھۆرمەت ۋە ھوقۇقتا باب۔باراۋەر بولۇپ تۇغۇلغان. ئۇلار ئەقىلگە ۋە ۋىجدانغا ئىگە ھەمدە بىر۔بىرىگە قېرىنداشلىق مۇناسىۋىتىگە خاس روھ بىلەن مۇئامىلە قىلىشى كېرەك.\
  ئەقىللىق كېلىشىم بىر خىل قانۇنلۇق كۈچكە ئىگە بولغان، ئالدىنئالا قوشۇلغان كېلىشم ياكى توختامنىڭ ماددىلىرىغان ئاساسەن ئاپتوماتىك ھالدا ئىجىرا قىلىندىغان كومپيوتېر پىروگراممىسى ياكى ئېلىكترونلۇق ئېلىم۔بېرىم نىزامى.
- ULY: hemme adem tughulushidinla erkin, izzet-hörmet we hoquqta bab-barawer bolup tughulghan. ular eqilge we wijdan'gha ige hemde bir-birige qërindashliq munasiwitige xas roh bilen muamile qilishi kërek.\
  eqilliq këlishim bir xil qanunluq küchke ige bolghan, aldin'ala qoshulghan këlishm yaki toxtamning maddilirighan asasen aptomatik halda ijira qilindighan kompyotër pirogrammisi yaki ëliktronluq ëlim-bërim nizami.
- Common Turkic: hemme adem tuğuluşidinla erkin, izzet-hörmet ve hoquqta bab-baraver bolup tuğulğan. ular eqilge ve vicdanğa ige hemde bir-birige qérindaşliq munasivitige xas roh bilen muamile qilişi kérek.\
  eqilliq kélişim bir xil qanunluq küçke ige bolğan, aldin'ala qoşulğan kélişm yaki toxtamniñ maddiliriğan asasen aptomatik halda icira qilindiğan kompyotér pirogrammisi yaki éliktronluq élim-bérim nizami.
- USY: һәммә адәм туғулушидинла әркин, иззәт-һөрмәт вә һоқуқта баб-баравәр болуп туғулған. улар әқилгә вә виҗданға игә һәмдә бир-биригә қериндашлиқ мунасивитигә хас роһ билән муамилә қилиши керәк.\
  әқиллиқ келишим бир хил қанунлуқ күчкә игә болған, алдин'ала қошулған келишм яки тохтамниң маддилириған асасән аптоматик һалда иҗира қилиндиған компйотер пирограммиси яки еликтронлуқ елим-берим низами.
- UYY: ⱨəmmə adəm tuƣuluxidinla ərkin, izzət-ⱨɵrmət və ⱨoⱪuⱪta bab-baravər bolup tuƣulƣan. ular əⱪilgə və vijdanƣa igə ⱨəmdə bir-birigə ⱪerindaxliⱪ munasivitigə has roⱨ bilən muamilə ⱪilixi kerək.\
  əⱪilliⱪ kelixim bir hil ⱪanunluⱪ küqkə igə bolƣan, aldin'ala ⱪoxulƣan kelixm yaki tohtamning maddiliriƣan asasən aptomatik ⱨalda ijira ⱪilindiƣan kompyoter pirogrammisi yaki eliktronluⱪ elim-berim nizami.
- Toponymy Transcription：saybag rayoni ürümqi xahiri ga karaxlik xahar rayoni bolup (سايباغ رايونى ئۈرۈمچى شەھىرى گە قاراشلىق شەھەر رايونى بولۇپ )
