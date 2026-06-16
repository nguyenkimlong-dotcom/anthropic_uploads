PRESERVE.

SET DECIMAL DOT.

GET DATA /TYPE=TXT

/FILE="D:\Mac Sync\NCKH\BÉ\SỰ KHÁC BIỆT HÀI LÒNG SINH KẾ CÁC DÂN TỘC SAU
CHƯƠNG TRÌNH CHI TRẢ GIẢM PHÁT THẢI TỪ RỪNG
(ERPA)\Sinh_data\erpa_sem_output_v11\ERPA_v11_SEM_synthetic_N559.csv"

/ENCODING='UTF8'

/DELIMITERS=","

/QUALIFIER='"'

/ARRANGEMENT=DELIMITED

/FIRSTCASE=2

/DATATYPEMIN PERCENTAGE=95.0

/VARIABLES=

A1 AUTO

A2 AUTO

A3 AUTO

A4 AUTO

A5 AUTO

A6 AUTO

A7 AUTO

A8 AUTO

A9 AUTO

A10 AUTO

A11 AUTO

A13 AUTO

DJ1 AUTO

DJ2 AUTO

DJ3 AUTO

DJ4 AUTO

DJ5 AUTO

DJ6 AUTO

PJ1 AUTO

PJ2 AUTO

PJ3 AUTO

PJ4 AUTO

PJ5 AUTO

RJ1 AUTO

RJ2 AUTO

RJ3 AUTO

RJ4 AUTO

RJ5 AUTO

RJ6 AUTO

TRU1 AUTO

TRU2 AUTO

TRU3 AUTO

TRU4 AUTO

TRU5 AUTO

SAT1 AUTO

SAT2 AUTO

SAT3 AUTO

BEN1 AUTO

BEN2 AUTO

BEN3 AUTO

BEN4 AUTO

CST1 AUTO

CST2 AUTO

CST3 AUTO

CST4 AUTO

ENG1 AUTO

ENG2 AUTO

SATc1 AUTO

SATc2 AUTO

SATc3 AUTO

SATc4 AUTO

SATc5 AUTO

/MAP.

RESTORE.

CACHE.

EXECUTE.

Data written to the working file.

52 variables and 559 cases written.

Variable: A1 Type: Number Format : F1

Variable: A2 Type: Number Format : F1

Variable: A3 Type: Number Format : F2

Variable: A4 Type: Number Format : F1

Variable: A5 Type: Number Format : F1

Variable: A6 Type: Number Format : F2

Variable: A7 Type: Number Format : F1

Variable: A8 Type: Number Format : F1

Variable: A9 Type: Number Format : F2

Variable: A10 Type: Number Format : F1

Variable: A11 Type: Number Format : F1

Variable: A13 Type: Number Format : F1

Variable: DJ1 Type: Number Format : F1

Variable: DJ2 Type: Number Format : F1

Variable: DJ3 Type: Number Format : F1

Variable: DJ4 Type: Number Format : F1

Variable: DJ5 Type: Number Format : F1

Variable: DJ6 Type: Number Format : F1

Variable: PJ1 Type: Number Format : F1

Variable: PJ2 Type: Number Format : F1

Variable: PJ3 Type: Number Format : F1

Variable: PJ4 Type: Number Format : F1

Variable: PJ5 Type: Number Format : F1

Variable: RJ1 Type: Number Format : F1

Variable: RJ2 Type: Number Format : F1

Variable: RJ3 Type: Number Format : F1

Variable: RJ4 Type: Number Format : F1

Variable: RJ5 Type: Number Format : F1

Variable: RJ6 Type: Number Format : F1

Variable: TRU1 Type: Number Format : F1

Variable: TRU2 Type: Number Format : F1

Variable: TRU3 Type: Number Format : F1

Variable: TRU4 Type: Number Format : F1

Variable: TRU5 Type: Number Format : F1

Variable: SAT1 Type: Number Format : F1

Variable: SAT2 Type: Number Format : F1

Variable: SAT3 Type: Number Format : F1

Variable: BEN1 Type: Number Format : F1

Variable: BEN2 Type: Number Format : F1

Variable: BEN3 Type: Number Format : F1

Variable: BEN4 Type: Number Format : F1

Variable: CST1 Type: Number Format : F1

Variable: CST2 Type: Number Format : F1

Variable: CST3 Type: Number Format : F1

Variable: CST4 Type: Number Format : F1

Variable: ENG1 Type: Number Format : F1

Variable: ENG2 Type: Number Format : F1

Variable: SATc1 Type: Number Format : F1

Variable: SATc2 Type: Number Format : F1

Variable: SATc3 Type: Number Format : F1

Variable: SATc4 Type: Number Format : F1

Variable: SATc5 Type: Number Format : F1

Substitute the following to build syntax for these data.

/VARIABLES=

A1 F1

A2 F1

A3 F2

A4 F1

A5 F1

A6 F2

A7 F1

A8 F1

A9 F2

A10 F1

A11 F1

A13 F1

DJ1 F1

DJ2 F1

DJ3 F1

DJ4 F1

DJ5 F1

DJ6 F1

PJ1 F1

PJ2 F1

PJ3 F1

PJ4 F1

PJ5 F1

RJ1 F1

RJ2 F1

RJ3 F1

RJ4 F1

RJ5 F1

RJ6 F1

TRU1 F1

TRU2 F1

TRU3 F1

TRU4 F1

TRU5 F1

SAT1 F1

SAT2 F1

SAT3 F1

BEN1 F1

BEN2 F1

BEN3 F1

BEN4 F1

CST1 F1

CST2 F1

CST3 F1

CST4 F1

ENG1 F1

ENG2 F1

SATc1 F1

SATc2 F1

SATc3 F1

SATc4 F1

SATc5 F1

DATASET NAME DataSet1 WINDOW=FRONT.

SAVE OUTFILE='D:\Mac Sync\NCKH\BÉ\SỰ KHÁC BIỆT HÀI LÒNG SINH KẾ CÁC DÂN
TỘC SAU CHƯƠNG TRÌNH CHI '+

'TRẢ GIẢM PHÁT THẢI TỪ RỪNG (ERPA)\Khac_biet_dan_toc.sav'

/COMPRESSED.

DATASET ACTIVATE DataSet1.

SAVE OUTFILE='D:\Mac Sync\NCKH\BÉ\SỰ KHÁC BIỆT HÀI LÒNG SINH KẾ CÁC DÂN
TỘC SAU CHƯƠNG TRÌNH CHI '+

'TRẢ GIẢM PHÁT THẢI TỪ RỪNG (ERPA)\Khac_biet_dan_toc.sav'

/COMPRESSED.

FREQUENCIES VARIABLES=A1 A2 A4 A5 A7 A8 A10 A13

/ORDER=ANALYSIS.

DATASET ACTIVATE DataSet1.

SAVE OUTFILE='D:\Mac Sync\NCKH\BÉ\SỰ KHÁC BIỆT HÀI LÒNG SINH KẾ CÁC DÂN
TỘC SAU CHƯƠNG TRÌNH CHI '+

'TRẢ GIẢM PHÁT THẢI TỪ RỪNG (ERPA)\Khac_biet_dan_toc.sav'

/COMPRESSED.

FREQUENCIES VARIABLES=A1 A2 A4 A5 A7 A8 A10 A13

/ORDER=ANALYSIS.

**Frequencies**

<table style="width:80%;">
<colgroup>
<col style="width: 25%" />
<col style="width: 27%" />
<col style="width: 27%" />
</colgroup>
<tbody>
<tr>
<td colspan="3" style="text-align: center;"><blockquote>
<p><strong>Notes</strong></p>
</blockquote></td>
</tr>
<tr>
<td colspan="2" style="text-align: center;"><blockquote>
<p>Output Created</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>15-JUN-2026 15:50:43</p>
</blockquote></td>
</tr>
<tr>
<td colspan="2" style="text-align: center;"><blockquote>
<p>Comments</p>
</blockquote></td>
<td style="text-align: center;"></td>
</tr>
<tr>
<td rowspan="6" style="text-align: center;"><blockquote>
<p>Input</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>Data</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>D:\Mac Sync\NCKH\BÉ\SỰ KHÁC BIỆT HÀI LÒNG SINH KẾ CÁC DÂN TỘC SAU
CHƯƠNG TRÌNH CHI TRẢ GIẢM PHÁT THẢI TỪ RỪNG
(ERPA)\Khac_biet_dan_toc.sav</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>Active Dataset</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>DataSet1</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>Filter</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>&lt;none&gt;</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>Weight</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>&lt;none&gt;</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>Split File</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>&lt;none&gt;</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>N of Rows in Working Data File</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>559</p>
</blockquote></td>
</tr>
<tr>
<td rowspan="2" style="text-align: center;"><blockquote>
<p>Missing Value Handling</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>Definition of Missing</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>User-defined missing values are treated as missing.</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>Cases Used</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>Statistics are based on all cases with valid data.</p>
</blockquote></td>
</tr>
<tr>
<td colspan="2" style="text-align: center;"><blockquote>
<p>Syntax</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>FREQUENCIES VARIABLES=A1 A2 A4 A5 A7 A8 A10 A13</p>
<p>/ORDER=ANALYSIS.</p>
</blockquote></td>
</tr>
<tr>
<td rowspan="2" style="text-align: center;"><blockquote>
<p>Resources</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>Processor Time</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>00:00:00.00</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>Elapsed Time</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>00:00:00.00</p>
</blockquote></td>
</tr>
</tbody>
</table>

<table style="width:99%;">
<colgroup>
<col style="width: 8%" />
<col style="width: 10%" />
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
</colgroup>
<tbody>
<tr>
<td colspan="9" style="text-align: center;"><blockquote>
<p><strong>Statistics</strong></p>
</blockquote></td>
</tr>
<tr>
<td colspan="2" style="text-align: center;"></td>
<td style="text-align: center;"><blockquote>
<p>A1</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>A2</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>A4</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>A5</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>A7</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>A8</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>A10</p>
</blockquote></td>
</tr>
<tr>
<td rowspan="2" style="text-align: center;"><blockquote>
<p>N</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>Valid</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>559</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>559</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>559</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>559</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>559</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>559</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>559</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>Missing</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>0</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>0</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>0</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>0</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>0</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>0</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>0</p>
</blockquote></td>
</tr>
</tbody>
</table>

<table style="width:100%;">
<colgroup>
<col style="width: 27%" />
<col style="width: 35%" />
<col style="width: 37%" />
</colgroup>
<tbody>
<tr>
<td colspan="3" style="text-align: center;"><blockquote>
<p><strong>Statistics</strong></p>
</blockquote></td>
</tr>
<tr>
<td colspan="2" style="text-align: center;"></td>
<td style="text-align: center;"><blockquote>
<p>A13</p>
</blockquote></td>
</tr>
<tr>
<td rowspan="2" style="text-align: center;"><blockquote>
<p>N</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>Valid</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>559</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>Missing</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>0</p>
</blockquote></td>
</tr>
</tbody>
</table>

**Frequency Table**

<table style="width:76%;">
<colgroup>
<col style="width: 8%" />
<col style="width: 11%" />
<col style="width: 13%" />
<col style="width: 11%" />
<col style="width: 15%" />
<col style="width: 16%" />
</colgroup>
<tbody>
<tr>
<td colspan="6" style="text-align: center;"><blockquote>
<p><strong>A1</strong></p>
</blockquote></td>
</tr>
<tr>
<td colspan="2" style="text-align: center;"></td>
<td style="text-align: center;"><blockquote>
<p>Frequency</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>Percent</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>Valid Percent</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>Cumulative Percent</p>
</blockquote></td>
</tr>
<tr>
<td rowspan="4" style="text-align: center;"><blockquote>
<p>Valid</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>A Lưới 2</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>187</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>33.5</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>33.5</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>33.5</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>A Lưới 3</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>197</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>35.2</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>35.2</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>68.7</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>A Lưới 4</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>175</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>31.3</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>31.3</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>100.0</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>Total</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>559</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>100.0</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>100.0</p>
</blockquote></td>
<td style="text-align: center;"></td>
</tr>
</tbody>
</table>

<table style="width:73%;">
<colgroup>
<col style="width: 8%" />
<col style="width: 8%" />
<col style="width: 13%" />
<col style="width: 11%" />
<col style="width: 15%" />
<col style="width: 16%" />
</colgroup>
<tbody>
<tr>
<td colspan="6" style="text-align: center;"><blockquote>
<p><strong>A2</strong></p>
</blockquote></td>
</tr>
<tr>
<td colspan="2" style="text-align: center;"></td>
<td style="text-align: center;"><blockquote>
<p>Frequency</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>Percent</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>Valid Percent</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>Cumulative Percent</p>
</blockquote></td>
</tr>
<tr>
<td rowspan="3" style="text-align: center;"><blockquote>
<p>Valid</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>Nam</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>402</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>71.9</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>71.9</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>71.9</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>Nữ</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>157</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>28.1</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>28.1</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>100.0</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>Total</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>559</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>100.0</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>100.0</p>
</blockquote></td>
<td style="text-align: center;"></td>
</tr>
</tbody>
</table>

<table style="width:74%;">
<colgroup>
<col style="width: 8%" />
<col style="width: 9%" />
<col style="width: 13%" />
<col style="width: 11%" />
<col style="width: 15%" />
<col style="width: 16%" />
</colgroup>
<tbody>
<tr>
<td colspan="6" style="text-align: center;"><blockquote>
<p><strong>A4</strong></p>
</blockquote></td>
</tr>
<tr>
<td colspan="2" style="text-align: center;"></td>
<td style="text-align: center;"><blockquote>
<p>Frequency</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>Percent</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>Valid Percent</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>Cumulative Percent</p>
</blockquote></td>
</tr>
<tr>
<td rowspan="7" style="text-align: center;"><blockquote>
<p>Valid</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>Kinh</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>91</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>16.3</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>16.3</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>16.3</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>Tà Ôi</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>215</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>38.5</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>38.5</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>54.7</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>Pa Kô</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>165</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>29.5</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>29.5</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>84.3</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>Cơ Tu</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>64</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>11.4</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>11.4</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>95.7</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>Pa Hy</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>17</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>3.0</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>3.0</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>98.7</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>Khác</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>7</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>1.3</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>1.3</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>100.0</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>Total</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>559</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>100.0</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>100.0</p>
</blockquote></td>
<td style="text-align: center;"></td>
</tr>
</tbody>
</table>

<table style="width:80%;">
<colgroup>
<col style="width: 8%" />
<col style="width: 15%" />
<col style="width: 13%" />
<col style="width: 11%" />
<col style="width: 15%" />
<col style="width: 16%" />
</colgroup>
<tbody>
<tr>
<td colspan="6" style="text-align: center;"><blockquote>
<p><strong>A5</strong></p>
</blockquote></td>
</tr>
<tr>
<td colspan="2" style="text-align: center;"></td>
<td style="text-align: center;"><blockquote>
<p>Frequency</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>Percent</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>Valid Percent</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>Cumulative Percent</p>
</blockquote></td>
</tr>
<tr>
<td rowspan="6" style="text-align: center;"><blockquote>
<p>Valid</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>Không đi học</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>28</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>5.0</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>5.0</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>5.0</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>Tiểu học</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>156</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>27.9</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>27.9</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>32.9</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>THCS</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>243</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>43.5</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>43.5</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>76.4</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>THPT</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>112</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>20.0</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>20.0</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>96.4</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>CĐ/ĐH</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>20</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>3.6</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>3.6</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>100.0</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>Total</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>559</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>100.0</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>100.0</p>
</blockquote></td>
<td style="text-align: center;"></td>
</tr>
</tbody>
</table>

<table style="width:84%;">
<colgroup>
<col style="width: 8%" />
<col style="width: 19%" />
<col style="width: 12%" />
<col style="width: 11%" />
<col style="width: 15%" />
<col style="width: 16%" />
</colgroup>
<tbody>
<tr>
<td colspan="6" style="text-align: center;"><blockquote>
<p><strong>A7</strong></p>
</blockquote></td>
</tr>
<tr>
<td colspan="2" style="text-align: center;"></td>
<td style="text-align: center;"><blockquote>
<p>Frequency</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>Percent</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>Valid Percent</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>Cumulative Percent</p>
</blockquote></td>
</tr>
<tr>
<td rowspan="7" style="text-align: center;"><blockquote>
<p>Valid</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>Lâm nghiệp</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>109</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>19.5</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>19.5</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>19.5</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>Trồng trọt</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>88</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>15.7</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>15.7</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>35.2</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>Chăn nuôi</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>85</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>15.2</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>15.2</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>50.4</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>Làm thuê</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>95</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>17.0</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>17.0</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>67.4</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>Buôn bán/ dịch vụ</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>85</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>15.2</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>15.2</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>82.6</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>Khác</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>97</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>17.4</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>17.4</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>100.0</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>Total</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>559</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>100.0</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>100.0</p>
</blockquote></td>
<td style="text-align: center;"></td>
</tr>
</tbody>
</table>

<table style="width:90%;">
<colgroup>
<col style="width: 8%" />
<col style="width: 25%" />
<col style="width: 12%" />
<col style="width: 11%" />
<col style="width: 15%" />
<col style="width: 16%" />
</colgroup>
<tbody>
<tr>
<td colspan="6" style="text-align: center;"><blockquote>
<p><strong>A8</strong></p>
</blockquote></td>
</tr>
<tr>
<td colspan="2" style="text-align: center;"></td>
<td style="text-align: center;"><blockquote>
<p>Frequency</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>Percent</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>Valid Percent</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>Cumulative Percent</p>
</blockquote></td>
</tr>
<tr>
<td rowspan="4" style="text-align: center;"><blockquote>
<p>Valid</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>Hộ nghèo</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>173</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>30.9</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>30.9</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>30.9</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>Hộ cận nghèo</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>134</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>24.0</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>24.0</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>54.9</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>Không thuộc các hộ trên</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>252</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>45.1</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>45.1</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>100.0</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>Total</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>559</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>100.0</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>100.0</p>
</blockquote></td>
<td style="text-align: center;"></td>
</tr>
</tbody>
</table>

<table style="width:79%;">
<colgroup>
<col style="width: 8%" />
<col style="width: 14%" />
<col style="width: 13%" />
<col style="width: 11%" />
<col style="width: 15%" />
<col style="width: 16%" />
</colgroup>
<tbody>
<tr>
<td colspan="6" style="text-align: center;"><blockquote>
<p><strong>A10</strong></p>
</blockquote></td>
</tr>
<tr>
<td colspan="2" style="text-align: center;"></td>
<td style="text-align: center;"><blockquote>
<p>Frequency</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>Percent</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>Valid Percent</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>Cumulative Percent</p>
</blockquote></td>
</tr>
<tr>
<td rowspan="4" style="text-align: center;"><blockquote>
<p>Valid</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>Hộ gia đình</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>29</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>5.2</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>5.2</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>5.2</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>Nhóm hộ</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>435</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>77.8</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>77.8</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>83.0</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>Cộng đồng</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>95</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>17.0</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>17.0</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>100.0</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>Total</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>559</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>100.0</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>100.0</p>
</blockquote></td>
<td style="text-align: center;"></td>
</tr>
</tbody>
</table>

<table style="width:92%;">
<colgroup>
<col style="width: 8%" />
<col style="width: 27%" />
<col style="width: 12%" />
<col style="width: 11%" />
<col style="width: 15%" />
<col style="width: 16%" />
</colgroup>
<tbody>
<tr>
<td colspan="6" style="text-align: center;"><blockquote>
<p><strong>A13</strong></p>
</blockquote></td>
</tr>
<tr>
<td colspan="2" style="text-align: center;"></td>
<td style="text-align: center;"><blockquote>
<p>Frequency</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>Percent</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>Valid Percent</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>Cumulative Percent</p>
</blockquote></td>
</tr>
<tr>
<td rowspan="5" style="text-align: center;"><blockquote>
<p>Valid</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>Có, hiện không còn nhận</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>83</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>14.8</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>14.8</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>14.8</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>Có, hiện vẫn nhận song song với ERPA</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>121</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>21.6</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>21.6</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>36.5</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>Không</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>269</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>48.1</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>48.1</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>84.6</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>Không rõ</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>86</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>15.4</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>15.4</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>100.0</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>Total</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>559</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>100.0</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>100.0</p>
</blockquote></td>
<td style="text-align: center;"></td>
</tr>
</tbody>
</table>

DATASET ACTIVATE DataSet1.

SAVE OUTFILE='D:\Mac Sync\NCKH\BÉ\SỰ KHÁC BIỆT HÀI LÒNG SINH KẾ CÁC DÂN
TỘC SAU CHƯƠNG TRÌNH CHI '+

'TRẢ GIẢM PHÁT THẢI TỪ RỪNG (ERPA)\Khac_biet_dan_toc.sav'

/COMPRESSED.

DESCRIPTIVES VARIABLES=A3 A6 A9 A11

/STATISTICS=MEAN STDDEV MIN MAX.

**Descriptives**

<table style="width:80%;">
<colgroup>
<col style="width: 25%" />
<col style="width: 27%" />
<col style="width: 27%" />
</colgroup>
<tbody>
<tr>
<td colspan="3" style="text-align: center;"><blockquote>
<p><strong>Notes</strong></p>
</blockquote></td>
</tr>
<tr>
<td colspan="2" style="text-align: center;"><blockquote>
<p>Output Created</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>15-JUN-2026 16:46:39</p>
</blockquote></td>
</tr>
<tr>
<td colspan="2" style="text-align: center;"><blockquote>
<p>Comments</p>
</blockquote></td>
<td style="text-align: center;"></td>
</tr>
<tr>
<td rowspan="6" style="text-align: center;"><blockquote>
<p>Input</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>Data</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>D:\Mac Sync\NCKH\BÉ\SỰ KHÁC BIỆT HÀI LÒNG SINH KẾ CÁC DÂN TỘC SAU
CHƯƠNG TRÌNH CHI TRẢ GIẢM PHÁT THẢI TỪ RỪNG
(ERPA)\Khac_biet_dan_toc.sav</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>Active Dataset</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>DataSet1</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>Filter</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>&lt;none&gt;</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>Weight</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>&lt;none&gt;</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>Split File</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>&lt;none&gt;</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>N of Rows in Working Data File</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>559</p>
</blockquote></td>
</tr>
<tr>
<td rowspan="2" style="text-align: center;"><blockquote>
<p>Missing Value Handling</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>Definition of Missing</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>User defined missing values are treated as missing.</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>Cases Used</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>All non-missing data are used.</p>
</blockquote></td>
</tr>
<tr>
<td colspan="2" style="text-align: center;"><blockquote>
<p>Syntax</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>DESCRIPTIVES VARIABLES=A3 A6 A9 A11</p>
<p>/STATISTICS=MEAN STDDEV MIN MAX.</p>
</blockquote></td>
</tr>
<tr>
<td rowspan="2" style="text-align: center;"><blockquote>
<p>Resources</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>Processor Time</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>00:00:00.02</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>Elapsed Time</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>00:00:00.00</p>
</blockquote></td>
</tr>
</tbody>
</table>

<table style="width:82%;">
<colgroup>
<col style="width: 18%" />
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 12%" />
<col style="width: 11%" />
<col style="width: 16%" />
</colgroup>
<tbody>
<tr>
<td colspan="6" style="text-align: center;"><blockquote>
<p><strong>Descriptive Statistics</strong></p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"></td>
<td style="text-align: center;"><blockquote>
<p>N</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>Minimum</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>Maximum</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>Mean</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>Std. Deviation</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>A3</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>559</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>20</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>75</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>46.94</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>12.492</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>A6</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>559</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>1</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>11</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>4.96</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>2.297</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>A9</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>559</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.54</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>27.57</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>4.6766</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>4.33384</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>A11</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>559</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>1</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>3</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>2.18</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.769</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>Valid N (listwise)</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>559</p>
</blockquote></td>
<td style="text-align: center;"></td>
<td style="text-align: center;"></td>
<td style="text-align: center;"></td>
<td style="text-align: center;"></td>
</tr>
</tbody>
</table>

DESCRIPTIVES VARIABLES=DJ1 DJ2 DJ3 DJ4 DJ5 DJ6 PJ1 PJ2 PJ3 PJ4 PJ5 RJ1
RJ2 RJ3 RJ4 RJ5 RJ6 TRU1

TRU2 TRU3 TRU4 TRU5 SAT1 SAT2 SAT3

/STATISTICS=MEAN STDDEV MIN MAX KURTOSIS SKEWNESS.

**Descriptives**

<table style="width:80%;">
<colgroup>
<col style="width: 25%" />
<col style="width: 27%" />
<col style="width: 27%" />
</colgroup>
<tbody>
<tr>
<td colspan="3" style="text-align: center;"><blockquote>
<p><strong>Notes</strong></p>
</blockquote></td>
</tr>
<tr>
<td colspan="2" style="text-align: center;"><blockquote>
<p>Output Created</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>15-JUN-2026 19:21:23</p>
</blockquote></td>
</tr>
<tr>
<td colspan="2" style="text-align: center;"><blockquote>
<p>Comments</p>
</blockquote></td>
<td style="text-align: center;"></td>
</tr>
<tr>
<td rowspan="6" style="text-align: center;"><blockquote>
<p>Input</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>Data</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>D:\Mac Sync\NCKH\BÉ\SỰ KHÁC BIỆT HÀI LÒNG SINH KẾ CÁC DÂN TỘC SAU
CHƯƠNG TRÌNH CHI TRẢ GIẢM PHÁT THẢI TỪ RỪNG
(ERPA)\Khac_biet_dan_toc.sav</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>Active Dataset</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>DataSet1</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>Filter</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>&lt;none&gt;</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>Weight</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>&lt;none&gt;</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>Split File</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>&lt;none&gt;</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>N of Rows in Working Data File</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>559</p>
</blockquote></td>
</tr>
<tr>
<td rowspan="2" style="text-align: center;"><blockquote>
<p>Missing Value Handling</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>Definition of Missing</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>User defined missing values are treated as missing.</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>Cases Used</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>All non-missing data are used.</p>
</blockquote></td>
</tr>
<tr>
<td colspan="2" style="text-align: center;"><blockquote>
<p>Syntax</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>DESCRIPTIVES VARIABLES=DJ1 DJ2 DJ3 DJ4 DJ5 DJ6 PJ1 PJ2 PJ3 PJ4 PJ5
RJ1 RJ2 RJ3 RJ4 RJ5 RJ6 TRU1</p>
<p>TRU2 TRU3 TRU4 TRU5 SAT1 SAT2 SAT3</p>
<p>/STATISTICS=MEAN STDDEV MIN MAX KURTOSIS SKEWNESS.</p>
</blockquote></td>
</tr>
<tr>
<td rowspan="2" style="text-align: center;"><blockquote>
<p>Resources</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>Processor Time</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>00:00:00.00</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>Elapsed Time</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>00:00:00.01</p>
</blockquote></td>
</tr>
</tbody>
</table>

<table style="width:94%;">
<colgroup>
<col style="width: 18%" />
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 12%" />
<col style="width: 11%" />
<col style="width: 16%" />
<col style="width: 11%" />
</colgroup>
<tbody>
<tr>
<td colspan="7" style="text-align: center;"><blockquote>
<p><strong>Descriptive Statistics</strong></p>
</blockquote></td>
</tr>
<tr>
<td rowspan="2" style="text-align: center;"></td>
<td style="text-align: center;"><blockquote>
<p>N</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>Minimum</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>Maximum</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>Mean</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>Std. Deviation</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>Skewness</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>Statistic</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>Statistic</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>Statistic</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>Statistic</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>Statistic</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>Statistic</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>DJ1</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>559</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>1</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>5</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>3.01</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.824</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.041</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>DJ2</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>559</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>1</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>5</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>3.01</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.790</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>-.129</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>DJ3</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>559</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>1</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>5</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>3.04</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.840</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.025</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>DJ4</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>559</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>1</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>5</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>3.06</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.836</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.125</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>DJ5</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>559</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>1</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>5</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>3.04</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.825</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.051</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>DJ6</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>559</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>1</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>5</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>3.10</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.857</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>-.018</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>PJ1</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>559</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>1</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>5</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>3.26</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.788</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.170</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>PJ2</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>559</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>1</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>5</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>3.33</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.799</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.134</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>PJ3</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>559</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>1</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>5</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>3.26</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.777</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.161</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>PJ4</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>559</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>1</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>5</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>3.28</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.783</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>-.051</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>PJ5</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>559</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>1</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>5</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>3.30</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.799</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.117</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>RJ1</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>559</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>1</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>5</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>3.23</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.807</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.127</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>RJ2</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>559</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>1</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>5</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>3.20</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.799</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.012</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>RJ3</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>559</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>1</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>5</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>3.21</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.822</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>-.067</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>RJ4</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>559</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>1</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>5</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>3.21</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.809</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>-.117</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>RJ5</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>559</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>1</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>5</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>3.25</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.805</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>-.033</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>RJ6</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>559</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>1</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>5</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>3.18</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.792</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.094</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>TRU1</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>559</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>1</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>5</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>3.35</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.782</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.160</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>TRU2</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>559</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>1</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>5</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>3.34</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.778</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.073</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>TRU3</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>559</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>1</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>5</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>3.34</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.754</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.027</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>TRU4</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>559</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>1</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>5</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>3.34</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.751</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.098</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>TRU5</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>559</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>1</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>5</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>3.36</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.768</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.121</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>SAT1</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>559</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>1</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>5</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>2.83</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.735</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>-.027</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>SAT2</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>559</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>1</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>5</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>2.84</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.735</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>-.019</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>SAT3</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>559</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>1</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>5</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>2.81</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.720</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.008</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>Valid N (listwise)</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>559</p>
</blockquote></td>
<td style="text-align: center;"></td>
<td style="text-align: center;"></td>
<td style="text-align: center;"></td>
<td style="text-align: center;"></td>
<td style="text-align: center;"></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 34%" />
<col style="width: 22%" />
<col style="width: 21%" />
<col style="width: 22%" />
</colgroup>
<tbody>
<tr>
<td colspan="4" style="text-align: center;"><blockquote>
<p><strong>Descriptive Statistics</strong></p>
</blockquote></td>
</tr>
<tr>
<td rowspan="2" style="text-align: center;"></td>
<td style="text-align: center;"><blockquote>
<p>Skewness</p>
</blockquote></td>
<td colspan="2" style="text-align: center;"><blockquote>
<p>Kurtosis</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>Std. Error</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>Statistic</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>Std. Error</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>DJ1</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.103</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>-.163</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.206</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>DJ2</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.103</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>-.327</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.206</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>DJ3</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.103</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>-.119</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.206</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>DJ4</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.103</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>-.162</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.206</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>DJ5</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.103</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>-.196</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.206</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>DJ6</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.103</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>-.482</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.206</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>PJ1</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.103</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>-.187</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.206</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>PJ2</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.103</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>-.009</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.206</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>PJ3</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.103</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>-.144</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.206</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>PJ4</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.103</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>-.154</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.206</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>PJ5</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.103</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>-.264</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.206</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>RJ1</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.103</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>-.255</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.206</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>RJ2</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.103</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>-.335</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.206</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>RJ3</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.103</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>-.175</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.206</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>RJ4</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.103</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>-.340</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.206</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>RJ5</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.103</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>-.105</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.206</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>RJ6</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.103</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>-.190</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.206</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>TRU1</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.103</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>-.239</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.206</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>TRU2</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.103</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>-.298</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.206</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>TRU3</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.103</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>-.252</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.206</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>TRU4</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.103</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.092</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.206</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>TRU5</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.103</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>-.089</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.206</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>SAT1</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.103</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>-.122</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.206</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>SAT2</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.103</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.138</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.206</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>SAT3</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.103</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>-.210</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.206</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>Valid N (listwise)</p>
</blockquote></td>
<td style="text-align: center;"></td>
<td style="text-align: center;"></td>
<td style="text-align: center;"></td>
</tr>
</tbody>
</table>

COMPUTE DJ_mean=MEAN(DJ1 to DJ6).

EXECUTE.

COMPUTE PJ_mean=MEAN(PJ1 to PJ5).

EXECUTE.

COMPUTE RJ_mean=MEAN(RJ1 to RJ6).

EXECUTE.

COMPUTE TRU_mean=MEAN(TRU1 to TRU5).

EXECUTE.

COMPUTE SAT_mean=MEAN(SAT1 to SAT3).

EXECUTE.

COMPUTE BEN_mean=MEAN(BEN1 to BEN4).

EXECUTE.

COMPUTE CST_mean=MEAN(CST1 to CST4).

EXECUTE.

DESCRIPTIVES VARIABLES=DJ_mean PJ_mean RJ_mean TRU_mean SAT_mean
BEN_mean CST_mean

/STATISTICS=MEAN STDDEV MIN MAX KURTOSIS SKEWNESS.

**Descriptives**

<table style="width:80%;">
<colgroup>
<col style="width: 25%" />
<col style="width: 27%" />
<col style="width: 27%" />
</colgroup>
<tbody>
<tr>
<td colspan="3" style="text-align: center;"><blockquote>
<p><strong>Notes</strong></p>
</blockquote></td>
</tr>
<tr>
<td colspan="2" style="text-align: center;"><blockquote>
<p>Output Created</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>15-JUN-2026 19:25:57</p>
</blockquote></td>
</tr>
<tr>
<td colspan="2" style="text-align: center;"><blockquote>
<p>Comments</p>
</blockquote></td>
<td style="text-align: center;"></td>
</tr>
<tr>
<td rowspan="6" style="text-align: center;"><blockquote>
<p>Input</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>Data</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>D:\Mac Sync\NCKH\BÉ\SỰ KHÁC BIỆT HÀI LÒNG SINH KẾ CÁC DÂN TỘC SAU
CHƯƠNG TRÌNH CHI TRẢ GIẢM PHÁT THẢI TỪ RỪNG
(ERPA)\Khac_biet_dan_toc.sav</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>Active Dataset</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>DataSet1</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>Filter</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>&lt;none&gt;</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>Weight</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>&lt;none&gt;</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>Split File</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>&lt;none&gt;</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>N of Rows in Working Data File</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>559</p>
</blockquote></td>
</tr>
<tr>
<td rowspan="2" style="text-align: center;"><blockquote>
<p>Missing Value Handling</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>Definition of Missing</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>User defined missing values are treated as missing.</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>Cases Used</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>All non-missing data are used.</p>
</blockquote></td>
</tr>
<tr>
<td colspan="2" style="text-align: center;"><blockquote>
<p>Syntax</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>DESCRIPTIVES VARIABLES=DJ_mean PJ_mean RJ_mean TRU_mean SAT_mean
BEN_mean CST_mean</p>
<p>/STATISTICS=MEAN STDDEV MIN MAX KURTOSIS SKEWNESS.</p>
</blockquote></td>
</tr>
<tr>
<td rowspan="2" style="text-align: center;"><blockquote>
<p>Resources</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>Processor Time</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>00:00:00.00</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>Elapsed Time</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>00:00:00.00</p>
</blockquote></td>
</tr>
</tbody>
</table>

<table style="width:94%;">
<colgroup>
<col style="width: 18%" />
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 12%" />
<col style="width: 11%" />
<col style="width: 16%" />
<col style="width: 11%" />
</colgroup>
<tbody>
<tr>
<td colspan="7" style="text-align: center;"><blockquote>
<p><strong>Descriptive Statistics</strong></p>
</blockquote></td>
</tr>
<tr>
<td rowspan="2" style="text-align: center;"></td>
<td style="text-align: center;"><blockquote>
<p>N</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>Minimum</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>Maximum</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>Mean</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>Std. Deviation</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>Skewness</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>Statistic</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>Statistic</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>Statistic</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>Statistic</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>Statistic</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>Statistic</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>DJ_mean</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>559</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>1.33</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>4.83</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>3.0447</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.65726</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>-.022</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>PJ_mean</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>559</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>1.60</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>5.00</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>3.2855</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.64095</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.205</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>RJ_mean</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>559</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>1.33</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>5.00</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>3.2138</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.63482</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.041</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>TRU_mean</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>559</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>1.60</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>5.00</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>3.3456</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.63690</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.233</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>SAT_mean</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>559</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>1.00</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>5.00</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>2.8301</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.64135</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>-.024</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>BEN_mean</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>559</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>2.00</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>5.00</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>3.5894</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.61076</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>-.006</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>CST_mean</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>559</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>1.50</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>5.00</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>3.0559</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.63896</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.054</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>Valid N (listwise)</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>559</p>
</blockquote></td>
<td style="text-align: center;"></td>
<td style="text-align: center;"></td>
<td style="text-align: center;"></td>
<td style="text-align: center;"></td>
<td style="text-align: center;"></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 34%" />
<col style="width: 22%" />
<col style="width: 21%" />
<col style="width: 22%" />
</colgroup>
<tbody>
<tr>
<td colspan="4" style="text-align: center;"><blockquote>
<p><strong>Descriptive Statistics</strong></p>
</blockquote></td>
</tr>
<tr>
<td rowspan="2" style="text-align: center;"></td>
<td style="text-align: center;"><blockquote>
<p>Skewness</p>
</blockquote></td>
<td colspan="2" style="text-align: center;"><blockquote>
<p>Kurtosis</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>Std. Error</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>Statistic</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>Std. Error</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>DJ_mean</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.103</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>-.402</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.206</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>PJ_mean</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.103</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>-.098</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.206</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>RJ_mean</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.103</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>-.276</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.206</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>TRU_mean</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.103</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>-.170</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.206</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>SAT_mean</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.103</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>-.050</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.206</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>BEN_mean</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.103</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>-.535</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.206</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>CST_mean</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.103</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>-.179</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.206</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>Valid N (listwise)</p>
</blockquote></td>
<td style="text-align: center;"></td>
<td style="text-align: center;"></td>
<td style="text-align: center;"></td>
</tr>
</tbody>
</table>

MEANS TABLES=DJ_mean PJ_mean RJ_mean TRU_mean SAT_mean SATc1 SATc2 SATc3
SATc4 SATc5 BY A4

/CELLS=MEAN COUNT STDDEV.

**Means**

<table style="width:80%;">
<colgroup>
<col style="width: 25%" />
<col style="width: 27%" />
<col style="width: 27%" />
</colgroup>
<tbody>
<tr>
<td colspan="3" style="text-align: center;"><blockquote>
<p><strong>Notes</strong></p>
</blockquote></td>
</tr>
<tr>
<td colspan="2" style="text-align: center;"><blockquote>
<p>Output Created</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>15-JUN-2026 19:29:16</p>
</blockquote></td>
</tr>
<tr>
<td colspan="2" style="text-align: center;"><blockquote>
<p>Comments</p>
</blockquote></td>
<td style="text-align: center;"></td>
</tr>
<tr>
<td rowspan="6" style="text-align: center;"><blockquote>
<p>Input</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>Data</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>D:\Mac Sync\NCKH\BÉ\SỰ KHÁC BIỆT HÀI LÒNG SINH KẾ CÁC DÂN TỘC SAU
CHƯƠNG TRÌNH CHI TRẢ GIẢM PHÁT THẢI TỪ RỪNG
(ERPA)\Khac_biet_dan_toc.sav</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>Active Dataset</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>DataSet1</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>Filter</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>&lt;none&gt;</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>Weight</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>&lt;none&gt;</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>Split File</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>&lt;none&gt;</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>N of Rows in Working Data File</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>559</p>
</blockquote></td>
</tr>
<tr>
<td rowspan="2" style="text-align: center;"><blockquote>
<p>Missing Value Handling</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>Definition of Missing</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>For each dependent variable in a table, user-defined missing values
for the dependent and all grouping variables are treated as missing.</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>Cases Used</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>Cases used for each table have no missing values in any independent
variable, and not all dependent variables have missing values.</p>
</blockquote></td>
</tr>
<tr>
<td colspan="2" style="text-align: center;"><blockquote>
<p>Syntax</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>MEANS TABLES=DJ_mean PJ_mean RJ_mean TRU_mean SAT_mean SATc1 SATc2
SATc3 SATc4 SATc5 BY A4</p>
<p>/CELLS=MEAN COUNT STDDEV.</p>
</blockquote></td>
</tr>
<tr>
<td rowspan="2" style="text-align: center;"><blockquote>
<p>Resources</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>Processor Time</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>00:00:00.00</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>Elapsed Time</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>00:00:00.00</p>
</blockquote></td>
</tr>
</tbody>
</table>

<table style="width:88%;">
<colgroup>
<col style="width: 18%" />
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
</colgroup>
<tbody>
<tr>
<td colspan="7" style="text-align: center;"><blockquote>
<p><strong>Case Processing Summary</strong></p>
</blockquote></td>
</tr>
<tr>
<td rowspan="3" style="text-align: center;"></td>
<td colspan="6" style="text-align: center;"><blockquote>
<p>Cases</p>
</blockquote></td>
</tr>
<tr>
<td colspan="2" style="text-align: center;"><blockquote>
<p>Included</p>
</blockquote></td>
<td colspan="2" style="text-align: center;"><blockquote>
<p>Excluded</p>
</blockquote></td>
<td colspan="2" style="text-align: center;"><blockquote>
<p>Total</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>N</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>Percent</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>N</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>Percent</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>N</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>Percent</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>DJ_mean * A4</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>559</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>100.0%</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>0</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>0.0%</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>559</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>100.0%</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>PJ_mean * A4</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>559</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>100.0%</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>0</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>0.0%</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>559</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>100.0%</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>RJ_mean * A4</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>559</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>100.0%</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>0</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>0.0%</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>559</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>100.0%</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>TRU_mean * A4</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>559</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>100.0%</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>0</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>0.0%</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>559</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>100.0%</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>SAT_mean * A4</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>559</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>100.0%</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>0</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>0.0%</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>559</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>100.0%</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>SATc1 * A4</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>559</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>100.0%</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>0</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>0.0%</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>559</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>100.0%</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>SATc2 * A4</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>559</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>100.0%</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>0</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>0.0%</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>559</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>100.0%</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>SATc3 * A4</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>559</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>100.0%</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>0</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>0.0%</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>559</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>100.0%</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>SATc4 * A4</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>559</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>100.0%</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>0</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>0.0%</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>559</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>100.0%</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>SATc5 * A4</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>559</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>100.0%</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>0</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>0.0%</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>559</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>100.0%</p>
</blockquote></td>
</tr>
</tbody>
</table>

<table style="width:100%;">
<colgroup>
<col style="width: 8%" />
<col style="width: 15%" />
<col style="width: 12%" />
<col style="width: 12%" />
<col style="width: 12%" />
<col style="width: 13%" />
<col style="width: 13%" />
<col style="width: 11%" />
</colgroup>
<tbody>
<tr>
<td colspan="8" style="text-align: center;"><blockquote>
<p><strong>Report</strong></p>
</blockquote></td>
</tr>
<tr>
<td colspan="2" style="text-align: center;"><blockquote>
<p>A4</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>DJ_mean</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>PJ_mean</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>RJ_mean</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>TRU_mean</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>SAT_mean</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>SATc1</p>
</blockquote></td>
</tr>
<tr>
<td rowspan="3" style="text-align: center;"><blockquote>
<p>Kinh</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>Mean</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>3.0073</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>3.2791</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>3.2015</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>3.3429</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>2.8278</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>3.09</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>N</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>91</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>91</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>91</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>91</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>91</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>91</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>Std. Deviation</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.66477</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.63587</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.65193</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.61267</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.66176</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.694</p>
</blockquote></td>
</tr>
<tr>
<td rowspan="3" style="text-align: center;"><blockquote>
<p>Tà Ôi</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>Mean</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>3.0426</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>3.2930</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>3.2171</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>3.3451</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>2.8388</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>3.08</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>N</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>215</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>215</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>215</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>215</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>215</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>215</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>Std. Deviation</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.64680</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.67026</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.62934</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.64371</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.64678</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.722</p>
</blockquote></td>
</tr>
<tr>
<td rowspan="3" style="text-align: center;"><blockquote>
<p>Pa Kô</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>Mean</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>3.0535</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>3.2739</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>3.1899</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>3.3358</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>2.8182</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>3.12</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>N</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>165</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>165</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>165</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>165</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>165</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>165</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>Std. Deviation</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.66361</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.61017</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.64495</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.64656</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.62302</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.739</p>
</blockquote></td>
</tr>
<tr>
<td rowspan="3" style="text-align: center;"><blockquote>
<p>Cơ Tu</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>Mean</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>3.0833</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>3.3281</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>3.2344</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>3.3563</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>2.8542</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>3.05</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>N</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>64</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>64</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>64</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>64</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>64</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>64</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>Std. Deviation</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.67521</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.63483</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.60109</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.62485</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.62255</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.575</p>
</blockquote></td>
</tr>
<tr>
<td rowspan="3" style="text-align: center;"><blockquote>
<p>Pa Hy</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>Mean</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>3.0686</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>3.2000</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>3.2549</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>3.3765</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>2.7451</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>3.12</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>N</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>17</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>17</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>17</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>17</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>17</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>17</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>Std. Deviation</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.67201</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.66708</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.59837</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.70669</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.73153</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.781</p>
</blockquote></td>
</tr>
<tr>
<td rowspan="3" style="text-align: center;"><blockquote>
<p>Khác</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>Mean</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>2.9762</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>3.2286</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>3.5476</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>3.4571</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>2.8571</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>3.00</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>N</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>7</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>7</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>7</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>7</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>7</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>7</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>Std. Deviation</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.74180</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.68730</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.83729</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.66045</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.79015</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.577</p>
</blockquote></td>
</tr>
<tr>
<td rowspan="3" style="text-align: center;"><blockquote>
<p>Total</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>Mean</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>3.0447</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>3.2855</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>3.2138</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>3.3456</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>2.8301</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>3.09</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>N</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>559</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>559</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>559</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>559</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>559</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>559</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>Std. Deviation</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.65726</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.64095</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.63482</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.63690</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.64135</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.705</p>
</blockquote></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 12%" />
<col style="width: 22%" />
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
</colgroup>
<tbody>
<tr>
<td colspan="6" style="text-align: center;"><blockquote>
<p><strong>Report</strong></p>
</blockquote></td>
</tr>
<tr>
<td colspan="2" style="text-align: center;"><blockquote>
<p>A4</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>SATc2</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>SATc3</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>SATc4</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>SATc5</p>
</blockquote></td>
</tr>
<tr>
<td rowspan="3" style="text-align: center;"><blockquote>
<p>Kinh</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>Mean</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>3.45</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>3.45</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>3.31</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>3.21</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>N</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>91</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>91</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>91</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>91</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>Std. Deviation</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.778</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.654</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.678</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.796</p>
</blockquote></td>
</tr>
<tr>
<td rowspan="3" style="text-align: center;"><blockquote>
<p>Tà Ôi</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>Mean</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>3.46</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>3.44</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>3.30</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>3.18</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>N</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>215</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>215</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>215</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>215</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>Std. Deviation</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.668</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.659</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.714</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.779</p>
</blockquote></td>
</tr>
<tr>
<td rowspan="3" style="text-align: center;"><blockquote>
<p>Pa Kô</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>Mean</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>3.39</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>3.46</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>3.42</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>3.24</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>N</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>165</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>165</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>165</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>165</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>Std. Deviation</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.755</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.737</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.655</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.725</p>
</blockquote></td>
</tr>
<tr>
<td rowspan="3" style="text-align: center;"><blockquote>
<p>Cơ Tu</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>Mean</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>3.41</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>3.50</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>3.31</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>3.33</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>N</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>64</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>64</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>64</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>64</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>Std. Deviation</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.610</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.667</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.753</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.757</p>
</blockquote></td>
</tr>
<tr>
<td rowspan="3" style="text-align: center;"><blockquote>
<p>Pa Hy</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>Mean</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>3.53</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>3.65</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>3.35</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>2.94</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>N</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>17</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>17</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>17</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>17</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>Std. Deviation</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.874</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.606</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.702</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.966</p>
</blockquote></td>
</tr>
<tr>
<td rowspan="3" style="text-align: center;"><blockquote>
<p>Khác</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>Mean</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>3.71</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>3.43</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>4.00</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>3.29</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>N</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>7</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>7</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>7</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>7</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>Std. Deviation</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.951</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.787</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.577</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.756</p>
</blockquote></td>
</tr>
<tr>
<td rowspan="3" style="text-align: center;"><blockquote>
<p>Total</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>Mean</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>3.44</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>3.46</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>3.35</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>3.21</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>N</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>559</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>559</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>559</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>559</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>Std. Deviation</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.715</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.681</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.697</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.769</p>
</blockquote></td>
</tr>
</tbody>
</table>

FACTOR

/VARIABLES DJ1 DJ2 DJ3 DJ4 DJ5 DJ6 PJ1 PJ2 PJ3 PJ4 PJ5 RJ1 RJ2 RJ3 RJ4
RJ5 RJ6 TRU1 TRU2 TRU3

TRU4 TRU5 SAT1 SAT2 SAT3

/MISSING LISTWISE

/ANALYSIS DJ1 DJ2 DJ3 DJ4 DJ5 DJ6 PJ1 PJ2 PJ3 PJ4 PJ5 RJ1 RJ2 RJ3 RJ4
RJ5 RJ6 TRU1 TRU2 TRU3 TRU4

TRU5 SAT1 SAT2 SAT3

/PRINT INITIAL KMO EXTRACTION

/PLOT EIGEN

/CRITERIA FACTORS(1) ITERATE(25)

/EXTRACTION PC

/ROTATION NOROTATE

/METHOD=CORRELATION.

**Factor Analysis**

<table style="width:80%;">
<colgroup>
<col style="width: 25%" />
<col style="width: 27%" />
<col style="width: 27%" />
</colgroup>
<tbody>
<tr>
<td colspan="3" style="text-align: center;"><blockquote>
<p><strong>Notes</strong></p>
</blockquote></td>
</tr>
<tr>
<td colspan="2" style="text-align: center;"><blockquote>
<p>Output Created</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>15-JUN-2026 19:44:12</p>
</blockquote></td>
</tr>
<tr>
<td colspan="2" style="text-align: center;"><blockquote>
<p>Comments</p>
</blockquote></td>
<td style="text-align: center;"></td>
</tr>
<tr>
<td rowspan="6" style="text-align: center;"><blockquote>
<p>Input</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>Data</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>D:\Mac Sync\NCKH\BÉ\SỰ KHÁC BIỆT HÀI LÒNG SINH KẾ CÁC DÂN TỘC SAU
CHƯƠNG TRÌNH CHI TRẢ GIẢM PHÁT THẢI TỪ RỪNG
(ERPA)\Khac_biet_dan_toc.sav</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>Active Dataset</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>DataSet1</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>Filter</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>&lt;none&gt;</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>Weight</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>&lt;none&gt;</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>Split File</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>&lt;none&gt;</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>N of Rows in Working Data File</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>559</p>
</blockquote></td>
</tr>
<tr>
<td rowspan="2" style="text-align: center;"><blockquote>
<p>Missing Value Handling</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>Definition of Missing</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>MISSING=EXCLUDE: User-defined missing values are treated as
missing.</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>Cases Used</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>LISTWISE: Statistics are based on cases with no missing values for
any variable used.</p>
</blockquote></td>
</tr>
<tr>
<td colspan="2" style="text-align: center;"><blockquote>
<p>Syntax</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>FACTOR</p>
<p>/VARIABLES DJ1 DJ2 DJ3 DJ4 DJ5 DJ6 PJ1 PJ2 PJ3 PJ4 PJ5 RJ1 RJ2 RJ3
RJ4 RJ5 RJ6 TRU1 TRU2 TRU3</p>
<p>TRU4 TRU5 SAT1 SAT2 SAT3</p>
<p>/MISSING LISTWISE</p>
<p>/ANALYSIS DJ1 DJ2 DJ3 DJ4 DJ5 DJ6 PJ1 PJ2 PJ3 PJ4 PJ5 RJ1 RJ2 RJ3 RJ4
RJ5 RJ6 TRU1 TRU2 TRU3 TRU4</p>
<p>TRU5 SAT1 SAT2 SAT3</p>
<p>/PRINT INITIAL KMO EXTRACTION</p>
<p>/PLOT EIGEN</p>
<p>/CRITERIA FACTORS(1) ITERATE(25)</p>
<p>/EXTRACTION PC</p>
<p>/ROTATION NOROTATE</p>
<p>/METHOD=CORRELATION.</p>
</blockquote></td>
</tr>
<tr>
<td rowspan="3" style="text-align: center;"><blockquote>
<p>Resources</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>Processor Time</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>00:00:00.31</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>Elapsed Time</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>00:00:00.29</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>Maximum Memory Required</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>74408 (72.664K) bytes</p>
</blockquote></td>
</tr>
</tbody>
</table>

<table style="width:65%;">
<colgroup>
<col style="width: 27%" />
<col style="width: 25%" />
<col style="width: 12%" />
</colgroup>
<tbody>
<tr>
<td colspan="3" style="text-align: center;"><blockquote>
<p><strong>KMO and Bartlett's Test</strong></p>
</blockquote></td>
</tr>
<tr>
<td colspan="2" style="text-align: center;"><blockquote>
<p>Kaiser-Meyer-Olkin Measure of Sampling Adequacy.</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.960</p>
</blockquote></td>
</tr>
<tr>
<td rowspan="3" style="text-align: center;"><blockquote>
<p>Bartlett's Test of Sphericity</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>Approx. Chi-Square</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>7779.506</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>df</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>300</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>Sig.</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.000</p>
</blockquote></td>
</tr>
</tbody>
</table>

<table style="width:33%;">
<colgroup>
<col style="width: 8%" />
<col style="width: 11%" />
<col style="width: 12%" />
</colgroup>
<tbody>
<tr>
<td colspan="3" style="text-align: center;"><blockquote>
<p><strong>Communalities</strong></p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"></td>
<td style="text-align: center;"><blockquote>
<p>Initial</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>Extraction</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>DJ1</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>1.000</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.363</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>DJ2</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>1.000</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.349</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>DJ3</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>1.000</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.308</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>DJ4</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>1.000</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.361</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>DJ5</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>1.000</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.299</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>DJ6</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>1.000</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.278</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>PJ1</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>1.000</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.395</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>PJ2</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>1.000</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.393</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>PJ3</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>1.000</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.392</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>PJ4</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>1.000</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.356</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>PJ5</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>1.000</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.351</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>RJ1</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>1.000</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.418</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>RJ2</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>1.000</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.439</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>RJ3</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>1.000</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.375</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>RJ4</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>1.000</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.410</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>RJ5</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>1.000</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.381</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>RJ6</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>1.000</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.381</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>TRU1</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>1.000</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.555</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>TRU2</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>1.000</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.531</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>TRU3</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>1.000</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.561</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>TRU4</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>1.000</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.549</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>TRU5</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>1.000</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.541</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>SAT1</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>1.000</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.520</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>SAT2</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>1.000</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.507</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>SAT3</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>1.000</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.498</p>
</blockquote></td>
</tr>
</tbody>
</table>

<table style="width:33%;">
<colgroup>
<col style="width: 32%" />
</colgroup>
<tbody>
<tr>
<td><blockquote>
<p>Extraction Method: Principal Component Analysis.</p>
</blockquote></td>
</tr>
</tbody>
</table>

<table style="width:87%;">
<colgroup>
<col style="width: 14%" />
<col style="width: 11%" />
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 12%" />
<col style="width: 16%" />
</colgroup>
<tbody>
<tr>
<td colspan="6" style="text-align: center;"><blockquote>
<p><strong>Total Variance Explained</strong></p>
</blockquote></td>
</tr>
<tr>
<td rowspan="2" style="text-align: center;"><blockquote>
<p>Component</p>
</blockquote></td>
<td colspan="3" style="text-align: center;"><blockquote>
<p>Initial Eigenvalues</p>
</blockquote></td>
<td colspan="2" style="text-align: center;"><blockquote>
<p>Extraction Sums of Squared Loadings</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>Total</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>% of Variance</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>Cumulative %</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>Total</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>% of Variance</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>1</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>10.511</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>42.045</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>42.045</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>10.511</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>42.045</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>2</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>2.280</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>9.118</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>51.163</p>
</blockquote></td>
<td style="text-align: center;"></td>
<td style="text-align: center;"></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>3</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>2.008</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>8.033</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>59.196</p>
</blockquote></td>
<td style="text-align: center;"></td>
<td style="text-align: center;"></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>4</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.941</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>3.765</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>62.961</p>
</blockquote></td>
<td style="text-align: center;"></td>
<td style="text-align: center;"></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>5</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.905</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>3.621</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>66.582</p>
</blockquote></td>
<td style="text-align: center;"></td>
<td style="text-align: center;"></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>6</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.588</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>2.352</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>68.934</p>
</blockquote></td>
<td style="text-align: center;"></td>
<td style="text-align: center;"></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>7</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.544</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>2.176</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>71.110</p>
</blockquote></td>
<td style="text-align: center;"></td>
<td style="text-align: center;"></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>8</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.534</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>2.136</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>73.245</p>
</blockquote></td>
<td style="text-align: center;"></td>
<td style="text-align: center;"></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>9</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.501</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>2.002</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>75.248</p>
</blockquote></td>
<td style="text-align: center;"></td>
<td style="text-align: center;"></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>10</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.494</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>1.976</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>77.223</p>
</blockquote></td>
<td style="text-align: center;"></td>
<td style="text-align: center;"></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>11</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.488</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>1.951</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>79.174</p>
</blockquote></td>
<td style="text-align: center;"></td>
<td style="text-align: center;"></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>12</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.466</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>1.866</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>81.040</p>
</blockquote></td>
<td style="text-align: center;"></td>
<td style="text-align: center;"></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>13</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.458</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>1.831</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>82.871</p>
</blockquote></td>
<td style="text-align: center;"></td>
<td style="text-align: center;"></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>14</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.430</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>1.720</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>84.590</p>
</blockquote></td>
<td style="text-align: center;"></td>
<td style="text-align: center;"></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>15</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.413</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>1.652</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>86.242</p>
</blockquote></td>
<td style="text-align: center;"></td>
<td style="text-align: center;"></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>16</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.408</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>1.631</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>87.873</p>
</blockquote></td>
<td style="text-align: center;"></td>
<td style="text-align: center;"></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>17</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.381</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>1.525</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>89.398</p>
</blockquote></td>
<td style="text-align: center;"></td>
<td style="text-align: center;"></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>18</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.375</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>1.502</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>90.899</p>
</blockquote></td>
<td style="text-align: center;"></td>
<td style="text-align: center;"></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>19</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.364</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>1.457</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>92.357</p>
</blockquote></td>
<td style="text-align: center;"></td>
<td style="text-align: center;"></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>20</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.345</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>1.380</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>93.736</p>
</blockquote></td>
<td style="text-align: center;"></td>
<td style="text-align: center;"></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>21</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.343</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>1.374</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>95.110</p>
</blockquote></td>
<td style="text-align: center;"></td>
<td style="text-align: center;"></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>22</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.329</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>1.317</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>96.428</p>
</blockquote></td>
<td style="text-align: center;"></td>
<td style="text-align: center;"></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>23</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.315</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>1.260</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>97.688</p>
</blockquote></td>
<td style="text-align: center;"></td>
<td style="text-align: center;"></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>24</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.291</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>1.163</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>98.851</p>
</blockquote></td>
<td style="text-align: center;"></td>
<td style="text-align: center;"></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>25</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.287</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>1.149</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>100.000</p>
</blockquote></td>
<td style="text-align: center;"></td>
<td style="text-align: center;"></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 46%" />
<col style="width: 53%" />
</colgroup>
<tbody>
<tr>
<td colspan="2" style="text-align: center;"><blockquote>
<p><strong>Total Variance Explained</strong></p>
</blockquote></td>
</tr>
<tr>
<td rowspan="2" style="text-align: center;"><blockquote>
<p>Component</p>
</blockquote></td>
<td style="text-align: center;"><blockquote>
<p>Extraction Sums of Squared Loadings</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>Cumulative %</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>1</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>42.045</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>2</p>
</blockquote></td>
<td style="text-align: center;"></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>3</p>
</blockquote></td>
<td style="text-align: center;"></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>4</p>
</blockquote></td>
<td style="text-align: center;"></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>5</p>
</blockquote></td>
<td style="text-align: center;"></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>6</p>
</blockquote></td>
<td style="text-align: center;"></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>7</p>
</blockquote></td>
<td style="text-align: center;"></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>8</p>
</blockquote></td>
<td style="text-align: center;"></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>9</p>
</blockquote></td>
<td style="text-align: center;"></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>10</p>
</blockquote></td>
<td style="text-align: center;"></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>11</p>
</blockquote></td>
<td style="text-align: center;"></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>12</p>
</blockquote></td>
<td style="text-align: center;"></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>13</p>
</blockquote></td>
<td style="text-align: center;"></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>14</p>
</blockquote></td>
<td style="text-align: center;"></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>15</p>
</blockquote></td>
<td style="text-align: center;"></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>16</p>
</blockquote></td>
<td style="text-align: center;"></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>17</p>
</blockquote></td>
<td style="text-align: center;"></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>18</p>
</blockquote></td>
<td style="text-align: center;"></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>19</p>
</blockquote></td>
<td style="text-align: center;"></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>20</p>
</blockquote></td>
<td style="text-align: center;"></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>21</p>
</blockquote></td>
<td style="text-align: center;"></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>22</p>
</blockquote></td>
<td style="text-align: center;"></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>23</p>
</blockquote></td>
<td style="text-align: center;"></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>24</p>
</blockquote></td>
<td style="text-align: center;"></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>25</p>
</blockquote></td>
<td style="text-align: center;"></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr>
<td><blockquote>
<p>Extraction Method: Principal Component Analysis.</p>
</blockquote></td>
</tr>
</tbody>
</table>

<img
src="D:\Mac Sync\NCKH\BÉ\SỰ KHÁC BIỆT HÀI LÒNG SINH KẾ CÁC DÂN TỘC SAU CHƯƠNG TRÌNH CHI TRẢ GIẢM PHÁT THẢI TỪ RỪNG (ERPA)\Data output\media/media/image1.png"
style="width:6.26389in;height:3.68819in" />

<table style="width:24%;">
<colgroup>
<col style="width: 8%" />
<col style="width: 14%" />
</colgroup>
<tbody>
<tr>
<td colspan="2" style="text-align: center;"><blockquote>
<p><strong>Component Matrix<sup>a</sup></strong></p>
</blockquote></td>
</tr>
<tr>
<td rowspan="2" style="text-align: center;"></td>
<td style="text-align: center;"><blockquote>
<p>Component</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>1</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>DJ1</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.602</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>DJ2</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.591</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>DJ3</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.555</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>DJ4</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.601</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>DJ5</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.547</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>DJ6</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.528</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>PJ1</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.629</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>PJ2</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.627</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>PJ3</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.626</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>PJ4</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.597</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>PJ5</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.592</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>RJ1</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.647</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>RJ2</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.663</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>RJ3</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.612</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>RJ4</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.640</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>RJ5</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.617</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>RJ6</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.617</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>TRU1</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.745</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>TRU2</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.729</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>TRU3</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.749</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>TRU4</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.741</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>TRU5</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.735</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>SAT1</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.721</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>SAT2</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.712</p>
</blockquote></td>
</tr>
<tr>
<td style="text-align: center;"><blockquote>
<p>SAT3</p>
</blockquote></td>
<td style="text-align: right;"><blockquote>
<p>.706</p>
</blockquote></td>
</tr>
</tbody>
</table>

<table style="width:24%;">
<colgroup>
<col style="width: 23%" />
</colgroup>
<tbody>
<tr>
<td><blockquote>
<p>Extraction Method: Principal Component Analysis.<sup>a</sup></p>
</blockquote></td>
</tr>
<tr>
<td><blockquote>
<p>a. 1 components extracted.</p>
</blockquote></td>
</tr>
</tbody>
</table>
