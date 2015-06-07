# ORC club certificate scoring

Van http://orc.org/index.asp?id=44 zijn lijsten te downloaden met daarin gegevens over de zeilboten met een geldig ORC-certificaat.

Omdat de VPP ook wel zinnig is voor anderen, heb ik dit tooltje gemaakt.



## Header names:

for `<wind>`:  [6, 8, 10, 12, 14, 16, 20]
for `<angle>`:  [52, 60, 75, 90, 110, 120, 135, 150]

- `WL6` Windward / Leeward @ 6kts
- `OL6` ??
- `CR6`(`CR<wind>`) Circular random @6kts
- `NSP6` (`NSP<wind>`) Non spinnaker @6kts
- `OC6` (`OC<wind>`) Ocean for PCS

### VPP:
 - `UA6` (`UA<wind>`) Beat angles
 - `UP6` Beat VMG
 - `DA6` Gybe angles
 - `D6` Run VMG
 - `R526` (`R<angle><wind>`) time allowance voor 52deg @6kts wind.
   `3600 / R526` = De te verwachten bootsnelheid bij 52deg twa 6kts tws.


### Triple number ratings:
 - `GPH`: General purpose handicap
 - `OTNLOW`, `OTNMED`, `OTNHIG`: Offshore triple number (low, mid, high)
 - `ITNLOW`, `ITNMED`, `ITNHIG`: Inshore triple number (low, mid, high)

## Links
 - [Uitleg over certificaat op orc.org](http://orc.org/index.asp?id=23)
 - OpenCPN book: [weather routing plugin](http://opencpn.org/ocpn/book/export/html/267)
 - Collapse sidebar (http://www.bootply.com/mL7j0aOINa)
 - Bootstrap toggle switch (interpolation on/off) http://www.bootstraptoggle.com/
