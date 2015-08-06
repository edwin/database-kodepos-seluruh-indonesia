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
	tbl_kodepos
WHERE
	kodepos = ?
```

Appreciations
--------------------
List of postalcodes are provided from PT POs Indonesia (http://www.posindonesia.co.id/)