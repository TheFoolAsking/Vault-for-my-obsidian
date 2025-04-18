İntegral türevin tersi gibi ama tam değil.
Yine de çözümünü türevin tersinden yapma. (nolur nolmaz)

integral değerini çözmek için istenilen değişkene göre ;
1.  Değişkenin üssünü bir arttır.
2. Değişkeni üssüne böl (1. adımdan sonraki üssüne)
3. Sabit terimi x ile çarp.
4. Kendin bi sabit terim ekle.

Mesela :
	$\int$$(x^5+4x^2-7x+2)$ $(dx)$ = ?

1. $(x^6+4x^3-7x^2+2)$
2. $(\frac{x^6}{6} + \frac{4x^3}{3} - \frac{7x^2}{2} + 2)$ 
3. $(\frac{x^6}{6} + \frac{4x^3}{3} - \frac{7x^2}{2} + 2x)$ 
4. $(\frac{x^6}{6} + \frac{4x^3}{3} - \frac{7x^2}{2} + 2x + c)$ 

	$\int$$(x^5+4x^2-7x+2)$ $(dx)$ = $(\frac{x^6}{6} + \frac{4x^3}{3} - \frac{7x^2}{2} + 2x + c)$ 

---

### Belirli integral:
Bu integral alan belirtiyo.
Genelde sınavlarda da bunu soruyolar genelde.
$\int_{3}^{4}$  Şeklinde gösterilir.
İntegrale göre tek farkı sabit terim koymazsın.
	Çözümü için:
1. İntegrali çöz
2. Değişken yerine üstteki değeri ver.
3. Değişken yerine alttaki değeri ver.
4. Üstteki değerden alttaki değeri çıkar.

---

>NOT:
>İntegrallere herzaman sabit terim koy bi tane.
>Onu unutmadığın sürece sıkıntı olmayacaktır.

---

#### Bilsen çok iyi olcak şeyler:

- Belirili integralde senden istenen iki değer de aynıysa cevap sıfırdır
	$\int_{a}^{a}$ $f(x)$ = $0$ 

- Belirili integral her zaman reel sayı olarak dışarı çıkar. O yüzden bazı trickler var. Mesela senden belirli bir integralin türevini isterse cevap her zaman 0 çıkar.
	$\frac{d}{dx}$$\int_{d}^{m}$$f(x)$$*dx$  = $0$

- F(x) tek fonksiyon ise ve senden böyle bşi isterse cevap her zaman 0 çıkar.
	$\int_{-a}^{a}$ f(x)*$dx$ = 0 

- Aynısı çift fonksiyonlu integralde varsa:
	$\int_{-a}^{a}$ $f(x)$ * $dx$ = $2$ * $\int_{0}^{a}$ $f(x)$*$dx$  ya da
	$\int_{-a}^{a}$ $f(x)$*$dx$ = $2 * \int_{-a}^{0}$ $f(x)$*$dx$ 

- Bide belirli integralleri ters çevirebiliyon. Ama önüne (-) koymak zorundasın.
	$\int_{a}^{b}$$f(x)*dx$  = - $\int_{b}^{a}$$f(x)*dx$

- En ömelli not olarak : Belirli integralleri doğrayabiliyosun:
	$\int_{1}^{10}$$f(x)dx$  = $\int_{1}^{5}$$f(x)dx$ + $\int_{5}^{10}$$f(x)dx$    Bunu istediğin kadar arttırabilirsin. (Soruya göre şekillendirmeye çalış)

---

Funfact:
Bunu istediğin yerde kullan güzel bişiymiş:
	Türevi fonksiyondaki herkesin üstüne yığabiliyosun:
		$f'(x)$ = $f(x)'$ 
	Ama önemli olan; içinin türevini bölüm olarak yazmak zorundasın:
		$f'(5x)$ = $\frac{f(5x)'}{5}$ 

İntegralle birleştirebiliyosun bide bunu (Türevle integralin birbirini götürmesi için) :
	$\int$$f'(5x)$$*dx$   =   $\int$$\frac{f(5x)}{5}$'$*dx$   =   $\frac{f(5x)}{5}$ 

Havalı özellik bence