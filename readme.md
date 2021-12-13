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

History
--------------------
**Aug 2015 -** List of postalcodes are provided from PT Pos Indonesia (http://www.posindonesia.co.id/), with 81.248 kodepos data. File name = `tbl_kodepos.sql`

**Dec 2021 -** Grabbing kodepos data from BPS website (https://sig.bps.go.id/bridging-kode/index), resulting in 69.498 kodepos data. File name = `tbl_kodepos_bps.sql`


Q&A
--------------------
**Q :** Why number of `kodepos` data from PT Pos and BPS is different?

**A :** I dont know.

##

**Q :** Which data is the correct one?

**A :** I also dont know.

##


**Q :** Why some `kelurahan` can have more than one `kodepos` in BPS data?

**A :** I dont know why.



Disclaimer
--------------------
```
This data is provided "as is" without any guarantee whatsoever. 
Feel free to fork, tinker, add, remove, change, or do whatever you want to it. 
```