# LG_SLTRANS

Lot / Serial Transactions

## Alanlar ve Açıklamaları

| Level | Product ID | Field Name | Field Type | Field Size | Field Offset | Türkçe Açıklama | Expression |
| ----- | ---------- | ---------- | ---------- | ---------- | ------------ | --------------- | ---------- |
| 2 | 3 | LOGICALREF | Longint | 4 | 0 | Lot / Seri Hareketi Log. Ref. | Lot / Serial Transaction Logical Reference |
| 2 | 3 | STFICHEREF | Longint | 4 | 4 | Malzeme Fişi Ref. | Material Voucher Reference |
| 2 | 3 | STTRANSREF | Longint | 4 | 8 | Malzeme Hareketi Ref. | Item Transaction Reference |
| 2 | 3 | INTRANSREF | Longint | 4 | 12 | Giriş Malzeme Hareket Ref. | Input Item Transaction Reference |
| 2 | 3 | INSLTRANSREF | Longint | 4 | 16 | Giriş Lot / Seri / Stok Yeri Hareket Ref. | Input Lot / Serial / Location Transaction Reference |
| 2 | 3 | INSLAMOUNT | Double | 8 | 20 | Miktar (Giriş hareket birimi) | Quantity From Input Transaction Unit |
| 2 | 3 | LINENR | Integer | 2 | 28 | Satır Numarası | Line Number |
| 2 | 3 | ITEMREF | Longint | 4 | 30 | Malzeme Kartı Referansı | Item Card Reference |
| 2 | 3 | DATE_ | Longint | 4 | 34 | Tarih | Date |
| 2 | 3 | IOCODE | Integer | 2 | 38 | Girdi / Çıktı kodu ;1 : Girdi;2 : Ambardan giriş;3 : Ambardan çıkış;4 : Çıktı | Input / Output Code ;1 : Input;2 : Input From Warehouse;3 : Output From Warehouse;4 : Output |
| 2 | 3 | INVENNO | Integer | 2 | 40 | Ambar Numarası | Warehouse Number |
| 2 | 3 | FICHETYPE | Integer | 2 | 42 | Bağlı fiş türü | Voucher Type that Connected |
| 2 | 3 | SLTYPE | Integer | 2 | 44 | Lot / Seri Türü; 1 Lot; 2 Seri | Lot / Serial Type ;1 Lot;2 Serial |
| 2 | 3 | SLREF | Longint | 4 | 46 | Lot / Seri Kayıt Ref. | Lot / Serial Record Reference |
| 2 | 3 | LOCREF | Longint | 4 | 50 | Stok Yeri Kaydı Ref. | Location Record Reference |
| 2 | 3 | MAINAMOUNT | Double | 8 | 54 | Miktar (ana birim) | Quantity In Main Unit |
| 2 | 3 | UOMREF | Longint | 4 | 62 | Birim referansı | Unit Reference |
| 2 | 3 | AMOUNT | Double | 8 | 66 | Miktar (satır birimi) | Quantity In Line Unit |
| 2 | 3 | REMAMOUNT | Double | 8 | 74 | Ana birim kalan miktar | Remaining Quantity In Main Unit |
| 2 | 3 | REMLNUNITAMNT | Double | 8 | 82 | Satır birimi kalan miktar | Remaining Quantity In Line Unit |
| 2 | 3 | UINFO1 | Double | 8 | 90 | Çevrim Katsayısı | Conversion Factor |
| 2 | 3 | UINFO2 | Double | 8 | 98 | Çevrim Katsayısı | Conversion Factor |
| 2 | 3 | UINFO3 | Double | 8 | 106 | Boyut Katsayısı | Dimension Factor |
| 2 | 3 | UINFO4 | Double | 8 | 114 | Boyut Katsayısı | Dimension Factor |
| 2 | 3 | UINFO5 | Double | 8 | 122 | Boyut Katsayısı | Dimension Factor |
| 2 | 3 | UINFO6 | Double | 8 | 130 | Boyut Katsayısı | Dimension Factor |
| 2 | 3 | UINFO7 | Double | 8 | 138 | Boyut Katsayısı | Dimension Factor |
| 2 | 3 | UINFO8 | Double | 8 | 146 | Boyut Katsayısı | Dimension Factor |
| 2 | 3 | EXPDATE | Longint | 4 | 154 | Son Kul.T. | Expiry Date |
| 2 | 3 | RATESCORE | Integer | 2 | 158 | Not | Note |
| 2 | 3 | CANCELLED | Byte | 1 | 160 | İptal Edilmiş | Cancelled |
| 2 | 3 | OUTCOST | Double | 8 | 161 | Çıkış fişi maliyeti | Output Vouchers Output Cost |
| 2 | 3 | OUTCOSTCURR | Double | 8 | 169 | Çıkış fişi dövizli maliyeti | Output Vouchers Output Cost In F. Currency |
| 2 | 3 | DIFFPRCOST | Double | 8 | 177 | Fiyat Farkı Maliyeti | Cost Because Of Price Difference |
| 2 | 3 | DIFFPRCOSTCURR | Double | 8 | 185 | Fiyat farkından oluşan maliyet (dövizli) | Cost In F. Currency Because Of Price Difference |
| 2 | 3 | SERIQCOK | Byte | 1 | 193 | Kalite Kontrol Uygunluğu | Conformity Of Inspection |
| 2 | 3 | LPRODSTAT | Integer | 2 | 194 | Durumu | Status |
| 2 | 3 | SOURCETYPE | Byte | 1 | 196 | Kaynak Tipi | Resource Type |
| 2 | 3 | SOURCEWSREF | Longint | 4 | 197 | Kaynak İş İstasyonu Referansı | Resource Workstation Reference |
| 2 | 3 | SITEID | Integer | 2 | 201 | Veri Merkezi | Data Processing Site |
| 2 | 3 | RECSTATUS | Integer | 2 | 203 | Kayıt Durumu | Record Status |
| 2 | 3 | ORGLOGICREF | Longint | 4 | 205 | Orijinal Kayıt Log. Ref. | Original Record Logical Reference |
| 2 | 3 | WFSTATUS | Longint | 4 | 209 | Kullanımda Değil | Not In Use |
| 2 | 3 | DISTORDREF | Longint | 4 | 213 | Dağıtım Emri Referansı | Distribution Order Reference |
| 2 | 3 | DISTORDLNREF | Longint | 4 | 217 | Dağıtım Emri Satırı Ref. | Distribution Order Line Reference |
| 2 | 3 | INDORDSLTRNREF | Longint | 4 | 221 | Dağıtımda Lot / Seri Hareketi Ref. | Lot / Serial Transaction Reference in Distribution |
| 2 | 3 | GROSSUINFO1 | Double | 8 | 225 | Bürüt Çevrim Katsayısı 1 | Gross Conversion Factor1 |
| 2 | 3 | GROSSUINFO2 | Double | 8 | 233 | Bürüt Çevrim Katsayısı 2 | Gross Conversion Factor2 |
| 2 | 3 | ATAXPRCOST | Double | 8 | 241 | Ek Vergi Maliyeti | Additional Tax Cost |
| 2 | 3 | ATAXPRCOSTCURR | Double | 8 | 249 | Ek Vergi Maliyeti (Raporlama Dövizi) | Additional Tax Cost (Reporting Currency) |
| 2 | 3 | INFIDX | Double | 8 | 257 | Enflasyon Endeksi | Inflation Index |
| 2 | 3 | ORGLOGOID | ZString | 25 | 265 | Veri Merkezi | Data Processing Site |
| 2 | 3 | LINEEXP | ZString | 31 | 290 | Satır Açıklaması | Line Description |
| 2 | 3 | EXIMFCTYPE | Integer | 2 | 321 | İthalat / İhracat Fiş Türü | Foreign Trade Slip Type |
| 2 | 3 | EXIMFILEREF | Longint | 4 | 323 | INVEXIMINFO Reference | INVEXIMINFO Reference |
| 2 | 3 | EXIMPROCNR | Integer | 2 | 327 | İthalat / İhracat Hareket Emri | Foreign Trade Transaction Order |
| 2 | 3 | MAINSLLNREF | Longint | 4 | 329 | Lot / Seri Hareketleri | Lot / Serial Transactions |
| 2 | 3 | MADEOFSHRED | Byte | 1 | 333 | Parçalama Yoluyla Oluşmuş ; 0: Hayır; 1: Evet | Generated by Parting ;0: No;1: Yes |

## İlişkiler - Relations

| Level | Product ID | Source Field | Destination Table | Destination Field | Relation Type | Extra Condition |
| ----- | ---------- | ------------ | ---------------- | ---------------- | ------------- | --------------- |
| 2 | 3 | STFICHEREF | L_STFICHE | LOGICALREF | one-to-one |  |
| 2 | 3 | STTRANSREF | L_STLINE | LOGICALREF | one-to-one |  |
| 2 | 3 | INTRANSREF | L_STLINE | LOGICALREF | one-to-one |  |
| 2 | 3 | INSLTRANSREF | L_SLTRANS | LOGICALREF | one-to-one |  |
| 2 | 3 | ITEMREF | L_ITEMS | LOGICALREF | one-to-one |  |
| 2 | 3 | SLREF | L_SERILOTN | LOGICALREF | one-to-one |  |
| 2 | 3 | LOCREF | L_LOCATION | LOGICALREF | one-to-one |  |
| 2 | 3 | UOMREF | L_UNITSETL | LOGICALREF | one-to-one |  |
| 2 | 3 | SOURCEWSREF | L_WORKSTAT | LOGICALREF | one-to-one |  |
| 2 | 3 | DISTORDREF | L_DISTORD | LOGICALREF | one-to-one |  |
| 2 | 3 | DISTORDLNREF | L_DISTORDLINE | LOGICALREF | one-to-one |  |

## Indexler

| Level | Product ID | Index Name | Attributes | Segment No | Segment Field | Sense |
| ----- | ---------- | ---------- | ---------- | ---------- | ------------- | ----- |
| 2 | 3 | Index1 | Unique + Not Null | 1 | LOGICALREF | Ascending |
| 2 | 3 | Index2 | Duplicate + Not Null | 1 | STTRANSREF | Ascending |
| 2 | 3 | Index2 | Duplicate + Not Null | 2 | LINENR | Ascending |
| 2 | 3 | Index3 | Duplicate + Not Null | 1 | SLREF | Ascending |
| 2 | 3 | Index4 | Duplicate + Not Null | 1 | ITEMREF | Ascending |
| 2 | 3 | Index4 | Duplicate + Not Null | 2 | INVENNO | Ascending |
| 2 | 3 | Index4 | Duplicate + Not Null | 3 | IOCODE | Ascending |
| 2 | 3 | Index4 | Duplicate + Not Null | 4 | DATE_ | Ascending |
| 2 | 3 | Index5 | Duplicate + Not Null | 1 | INSLTRANSREF | Ascending |
| 2 | 3 | Index6 | Duplicate + Not Null | 1 | DISTORDLNREF | Ascending |
| 2 | 3 | Index6 | Duplicate + Not Null | 2 | LINENR | Ascending |
