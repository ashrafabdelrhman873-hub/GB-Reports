# GB-Reports exports

## Current template — source RGIOEXOEIOD2012_SO_1 1.rdf

- [BI Publisher RTF](RGIOEXOEIOD2012_SO_1_FULL_BIP.rtf)
- [Actual XML local PDF preview](RGIOEXOEIOD2012_SO_1_FULL_PREVIEW.pdf)
- [Source, tests and preview package](RGIOEXOEIOD2012_SO_1_FULL_BIP_package.zip)
- [Arabic usage, parameters and validation notes](FULL_REPORT_README.md)
- [Delivery status](FULL_REPORT_STATUS.json)

All27 recovered sourceFormatTriggers,80field/textobjects and8frames are migrated.79unit tests and10localintegration/rendercases passed. OracleXDO execution remains untested. The actualXMLdoesnotincludeIMAGE, so realQRrequiresupdatedsourcedata; the packagedQRfixtureisclearlysynthetic.

Pass the original global P_ORG_ID parameter; it is not inferred from individual invoice ORG_ID values. Source P_FLAG default is1. Read the full notes before production use.

## Previous template

[RGIOEXOEIOD2012_SO_1_BIP.rtf](RGIOEXOEIOD2012_SO_1_BIP.rtf) is the older export based on the `_test` source. Use the FULL version above for the newly uploaded report.
