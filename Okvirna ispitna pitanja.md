# <p align="center">Okvirna ispitna pitanja</p>

## Uvod

<details>
<summary><strong> 1. Što je operacijski sustav, od čega se sastoji i čemu služi? </strong></summary>

  <br>
  $\large\color{rgb(174, 41, 252)}{\textsf{Operacijski sustav}}$
  <br>
  Program ili skup programa koji upravljaju svim uređajima u sustavu i
  omogućuju prihvatljivo jednostavno i funkcionalno sučelje korisničkim
  programima prema sklopovlju (korisniku korisničko sučelje). 

  <br><br>
  $\large\color{rgb(174, 41, 252)}{\textsf{Računalni sustav sastoji se od:}}$

  ---
</details>



<details>
<summary><strong> 2. Navedite/skicirajte i ukratko objasnite razine između kojih je smješten OS </strong></summary>
  <br>
  $\large\color{rgb(174, 41, 252)}{\text{Fizička razina}}$ - Uređaji (IC-i, sklopovi, PCB, ožičenja, posebne komp.) <br>
  $\large\color{rgb(174, 41, 252)}{\text{Razina mikroarhitekture}}$ - Tu fizički uređaji zajedno formiraju pojedine funkcijske cjeline: registri - ALU – CPU čime je određen tijek podataka) <br>
  $\large\color{rgb(174, 41, 252)}{\text{Razina strojnog jezika}}$ - Mikroprogram u asembleru, upravlja tijekom podataka između registara CPU i registara U/I uređaja s 50 – 300 instr.) <br>
  $\large\color{rgb(174, 41, 252)}{\text{Operacijski sustav}}$ - Sloj programske podrške koji djelomično skriva ovu sklopovsku složenost i programeru omogućuje skup instrukcija kojima će lakše pristupiti do tog sklopovlja <br>
  $\large\color{rgb(174, 41, 252)}{\text{Ostali sustavski programi}}$ (ljuska, kor. sučelje, prevoditelji, editori,ostali). 
Oni zapravo nisu dio OS-a, ali ih se uvijek zajedno isporučuju i razmatraju. OS je izvorno samo onaj dio koji se pokreće u jezgrinom (kernel/ supervisor načinu rada. On je sklopovski zaštićen od korisnika.
Nasuprot tome, prevoditelji i editori pokreću se u tzv. korisničkom načinu rada, ali opet ne dozvoljavaju baš sve.<br>
  $\large\color{rgb(174, 41, 252)}{\text{Korisnički programi}}$ - Kupljeni, “kupljeni” ili pisani od strane korisnika.
  <br> <br>
<img width="983" height="550" alt="image" src="https://github.com/user-attachments/assets/a8591693-f21f-4c6e-9c63-bef2c7bef89e" />
  
 ---
</details>



<details>
<summary><strong> 3. Navedite 5 generacija operacijskih sustava i ukratko opišite njihova osnovna obilježja. </strong></summary>
  <br>
  $\large\color{rgb(174, 41, 252)}{\text{Prva generacija 1945 - 1955}}$<br>
  • Releji, vakuumske cijevi, ploče s ožičenjima, programi u čistom strojnom obliku, kasnije napredak u obliku bušenih kartica
  <br><br>
  $\large\color{rgb(174, 41, 252)}{\text{Druga generacija 1955 - 1965}}$<br>
  • Tranzistori, pouzdanija računala - mainframes, FORTRAN, batch
sustavi (posao ili skup programa: na papir, na bušenu karticu, u
računalo na obradu, pa na pisač. <br>
• Napredak: sve poslove snimiti na magnetsku traku na jeftinom
računalu, traku odnijeti na računalo za obradu i učitati, nakon obradbe
rezultate snimiti na izlaznu traku, a onda s te trake učitati na izlazno
računalo, te ispisati rezultate. <br>
• Daljnji napredak: FMS (Fortran Monitor System) s nizom kartica - $JOB
card (ime i vrijeme izvođenja), $FORTRAN (OS treba učitati
FORTRAN), $LOAD (OS treba učitati prevedeni program, $RUN za
pokrenuti program, $END za kraj posla)
  <br><br>
  
<details>
<summary>Rani slijedni (batch) sustavi</summary>

<img width="1571" height="504" alt="image" src="https://github.com/user-attachments/assets/f743fcad-ad92-443a-bc89-0b0a3cd82242" />

 • Donesi karticu do 1401  
 • Učitaj karticu na traku  
 • Stavi traku u 7094 koji obavlja računanje  
 • Stavi traku s rezultatima na 1401 koji ispisuje rezultati

</details>
  
  $\large\color{rgb(174, 41, 252)}{\text{Treća generacija 1965 – 1980}}$<br>
  • IC-i i multiprogramiranje <br>
  • Programska kompatibilnost strojeva (pa čak da jedan OS pogoni sve strojeve nekog proizvođača - loše) <br>
  • Komercijalne primjene (uz znanstvene)<br>
  • MULTICS, UNIX, MINIX, Linux<br>
  • Multiprogramiranje – memoriju podijeliti u dijelove u koje smjestiti različite poslove. Sprječava problem da CPU stoji dok posao čeka podatke s U/I. (U/I vrijeme čekanja i 80-90% ukupnog vremena). Ako jedan posao čeka na U/I, drugi se može brzo izvesti iz memorije.<br>
  • Spooling (Simultaneous Peripheral Operation On Line). Kada se neki posao završi, OS učitava novi posao s diska.<br>
  • Podjela vremena (Time Sharing). Resurs se dodjeljuje korisniku koji ga trenutno treba.<br>
  <br>
  $\large\color{rgb(174, 41, 252)}{\text{Četvrta generacija 1980 – danas}}$<br>
  • LSI čipovi<br>
  • Osobna računala, mikroračunala (PDP 11, Z80, IBM PC, višejezgreni procesori, paralelni i raspodijeljeni sustavi, snažna računala posebne namjene)<br>
  • CP/M, DOS, MS-DOS, GUI (user friendly): Windows, NT, 98, ME, 2000, XP, Vista, W7, W8, W10...<br>
  • UNIX: X Windows, Motif, Linux: niz distribucija<br>
  • NOS (mrežni) i DOS (raspodijeljeni)<br>
  <br>
  $\large\color{rgb(174, 41, 252)}{\text{Peta generacija 1990 – danas}}$<br>
  • Prvi mobili telefon: 1970-ih<br>
  • Danas 90% svjetske populacije ima mobilni telefon<br>
  • PDA, smartphone<br>
  • Symbian, RIM Blackberry, Windows Phone, Android, iOS<br>
  
 ---
</details>



<details>
<summary><strong> 4. Navedite i ukratko opišite najznačajnije vrste operacijskih sustava prema računalnoj okolini i prema namjeni. </strong></summary>
  $\large\color{rgb(174, 41, 252)}{\text{Operacijski sustavi velikih računala}}$<br>
  • Mainframe, vratili se kao veliki web poslužitelji <br>
  • Slijed poslova, obrada transakcija, podjela vremena, posluga brojnih korisnika<br>

  $\large\color{rgb(174, 41, 252)}{\text{Operacijski sustavi poslužitelja}}$<br>
  • Jači PC-i, radne stanice ili mainframe računala, posluga velikog broja korisnika koji dijele sklopovlje, programe i podatke <br>
  
  $\large\color{rgb(174, 41, 252)}{\text{Višeprocesorski operacijski sustavi}}$<br>
  .
  .
  .


 ---
</details>



<details>
<summary><strong> 5. </strong></summary>


 ---
</details>



<details>
<summary><strong> 6. </strong></summary>


 ---
</details>
