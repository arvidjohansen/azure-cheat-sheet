# azure-cheat-sheet

## Links
1) Azure for students registration - https://aka.ms/a4s
2) Account balance - https://www.microsoftazuresponsorships.com/Balance
3) Disk costs - https://azure.microsoft.com/nb-no/pricing/details/managed-disks/

## Prices - North Europe
### LRS - Locally Redundant Storage
#### Premium SSD
|Navn|Diskstørrelser|Pris per måned|1-årig reservert|Maks. IOPS (maks. IOPS med bursting)|Maks. gjennomstrømming (maks. gjennomstrømming med bursting)|Pris per innsetting per måned (Delt disk)
|---|---|---|---|---|---|---|
|P1|4 GiB|kr6,35|I/T|120 (3 500)|25 MB/sekund (170 MB/sekund)|I/T
|P2|8 GiB|kr12,70|I/T|120 (3 500)|25 MB/sekund (170 MB/sekund)|I/T
|P3|16 GiB|kr25,39|I/T|120 (3 500)|25 MB/sekund (170 MB/sekund)|I/T
|P4|32 GiB|kr46,55|I/T|120 (3 500)|25 MB/sekund (170 MB/sekund)|I/T
|P6|64 GiB|kr89,98|I/T|240 (3 500)|50 MB/sekund (170 MB/sekund)|I/T
|P10|128 GiB|kr173,75|I/T|500 (3 500)|100 MB/sekund (170 MB/sekund)|I/T
|P15|256 GiB|kr335,09|I/T|1 100 (3 500)|125 MB/sekund (170 MB/sekund)|kr19,31
|P20|512 GiB|kr645,46|I/T|2 300 (3 500)|150 MB/sekund (170 MB/sekund)|kr34,75
|P30|1 TiB|kr1 191,56|kr1 132,0225|5 000 (30 000)|200 MB/sekund (1,000 MB/sekund)|kr69,50
|P40|2 TiB|kr2 283,55|kr2 169,2812|7 500 (30 000)|250 MB/sekund (1,000 MB/sekund)|kr139,00
|P50|4 TiB|kr4 368,53|kr4 150,5041|7 500 (30 000)|250 MB/sekund (1,000 MB/sekund)|kr270,28
|P60|8 TiB|kr8 339,92|kr7 922,6880|16 000 (30 000)|500 MB/sekund (1,000 MB/sekund)|kr540,55
|P70|16 TiB|kr15 885,58|kr15 091,6738|18 000 (30 000)|750 MB/sekund (1,000 MB/sekund)|kr1 158,33
|P80|32 TiB (32767 GiB)|kr31 771,06|kr30 182,6130|20 000 (30 000)|900 MB/sekund (1,000 MB/sekund)|kr2 316,65

### Standard SSD
|Navn|Diskstørrelser|Pris per måned|Maks. IOPS per disk|Maks. gjennomstrømming per disk
|---|---|---|---|---|
E1|4 GiB|kr2,65|500|60 MB/sekund
E2|8 GiB|kr5,29|500|60 MB/sekund
E3|16 GiB|kr10,58|500|60 MB/sekund
E4|32 GiB|kr21,16|500|60 MB/sekund
E6|64 GiB|kr42,32|500|60 MB/sekund
E10|128 GiB|kr84,63|500|60 MB/sekund
E15|256 GiB|kr169,26|500|60 MB/sekund
E20|512 GiB|kr338,51|500|60 MB/sekund
E30|1 TiB|kr677,01|500|60 MB/sekund
E40|2 TiB|kr1 354,02|500|60 MB/sekund
E50|4 TiB|kr2 708,04|500|60 MB/sekund
E60|8 TiB|kr5 416,08|2 000|400 MB/sekund
E70|16 TiB|kr10 832,16|4 000|600 MB/sekund
E80|32 TiB (32767 GiB)|kr21 664,31|6 000|750 MB/sekund

#### HDDs - cheap but slow:  
|Navn|Diskstørrelser|Pris per måned|IOP-er per disk|Gjennomstrømning per stasjon
|---|---|---|---|---|
|S4|32 GiB|kr13,55|Opp til 500|Opptil 60 MB/sekund
|S6|64 GiB|kr26,52|Opp til 500|Opptil 60 MB/sekund
|S10|128 GiB|kr51,91|Opp til 500|Opptil 60 MB/sekund
|S15|256 GiB|kr99,86|Opp til 500|Opptil 60 MB/sekund
|S20|512 GiB|kr191,82|Opp til 500|Opptil 60 MB/sekund
|S30|1 TiB|kr361,08|Opp til 500|Opptil 60 MB/sekund
|S40|2 TiB|kr722,15|Opp til 500|Opptil 60 MB/sekund
|S50|4 TiB|kr1 444,29|Opp til 500|Opptil 60 MB/sekund
|S60|8 TiB|kr2 888,58|Opp til 1 300|Opptil 300 MB/sekund
|S70|16 TiB|kr5 777,15|Opp til 2 000|Opptil 500 MB/sekund
|S80|32 TiB (32767 GiB)|kr11 554,30|Opp til 2 000|Opptil 500 MB/sekund

### ZRS - Zone Redundant Storage
#### Premium SSD
|Navn|Diskstørrelser|Pris per måned|1-årig reservert Pris per måned|Maks. IOPS (maks. IOPS med bursting)|Maks. gjennomstrømming (maks. gjennomstrømming med bursting)|Pris per innsetting per måned (Delt disk)
|---|---|---|---|---|---|---|
P1|4 GiB|kr9,53|I/T|120 (3 500)|25 MB/sekund (170 MB/sekund)|I/T
P2|8 GiB|kr19,05|I/T|120 (3 500)|25 MB/sekund (170 MB/sekund)|I/T
P3|16 GiB|kr38,09|I/T|120 (3 500)|25 MB/sekund (170 MB/sekund)|I/T
P4|32 GiB|kr69,81|I/T|120 (3 500)|25 MB/sekund (170 MB/sekund)|I/T
P6|64 GiB|kr134,97|I/T|240 (3 500)|50 MB/sekund (170 MB/sekund)|I/T
P10|128 GiB|kr260,63|I/T|500 (3 500)|100 MB/sekund (170 MB/sekund)|I/T
P15|256 GiB|kr502,64|I/T|1 100 (3 500)|125 MB/sekund (170 MB/sekund)|kr19,31
P20|512 GiB|kr968,01|I/T|2 300 (3 500)|150 MB/sekund (170 MB/sekund)|kr34,75
P30|1 TiB|kr1 787,12|I/T|5 000 (30 000)|200 MB/sekund (1,000 MB/sekund)|kr69,50
P40|2 TiB|kr3 425,34|I/T|7 500 (30 000)|250 MB/sekund (1,000 MB/sekund)|kr139,00
P50|4 TiB|kr6 552,89|I/T|7 500 (30 000)|250 MB/sekund (1,000 MB/sekund)|kr270,28
P60|8 TiB|kr12 509,96|I/T|16 000 (30 000)|500 MB/sekund (1,000 MB/sekund)|kr540,55
P70|16 TiB|kr23 828,54|I/T|18 000 (30 000)|750 MB/sekund (1,000 MB/sekund)|kr1 158,33
P80|32 TiB (32767 GiB)|kr47 657,17|I/T|20 000 (30 000)|900 MB/sekund (1,000 MB/sekund)|kr2 316,65
#### Standard SSD
|Navn|Diskstørrelser|Pris per måned|Maks. IOPS per disk|Maks. gjennomstrømming per disk
|---|---|---|---|---|
E1|4 GiB|kr3,97|120|25 MB/sekund
E2|8 GiB|kr7,94|120|25 MB/sekund
E3|16 GiB|kr15,87|120|25 MB/sekund
E4|32 GiB|kr31,74|120|25 MB/sekund
E6|64 GiB|kr63,47|240|50 MB/sekund
E10|128 GiB|kr126,94|500|60 MB/sekund
E15|256 GiB|kr253,88|500|60 MB/sekund
E20|512 GiB|kr507,76|500|60 MB/sekund
E30|1 TiB|kr1 015,52|500|60 MB/sekund
E40|2 TiB|kr2 031,03|500|60 MB/sekund
E50|4 TiB|kr4 062,06|500|60 MB/sekund
E60|8 TiB|kr8 124,12|2 000|400 MB/sekund
E70|16 TiB|kr16 248,24|4 000|600 MB/sekund
E80|32 TiB (32767 GiB)|kr32 496,47|6 000|750 MB/sekund
