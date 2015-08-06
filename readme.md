Indonesian Postal Code Database 
===================

Tools
-------------------
* DB - MySql

Query
--------------------
``` sql
SELECT
	kelurahan,
	kecamatan,
	kabupaten,
	provinsi
FROM
	kodepos
WHERE
	kodepos = ?
```

Appreciations
--------------------
List of postalcodes are provided from Satrio's Website in XLSX format (http://satrio.me/2015/03/06/download-kode-pos-indonesia-2015-format-excel-xlsx-paling-lengkap/)