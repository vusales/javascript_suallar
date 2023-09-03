# javascript_suallar

Sual-1 ---- Javascript nədir ? 
Cavab-1 ----

***Compilation - yüksək səviyyəli proqram dili ilə yazılmış (high-level programming language ) kodların kompüter tərəfindən başa düşülə bilən maşın-kodlarına və ya byte-kodlarına çevirilməsi prosesidir. 
***Compiler- Yüksək səviyyəli kodlarla yazılan kodları proqram işləməmişdən qabaq maşın-kodlarına çevirir.
***interpreter - Yüksək səviyyəli kodlarla yazılan kodları proqram işləyərkən sətir-sətir (line-by-line) maşın-kodlarına çevirir.

Compilerlər daha sürətlidir , İnterpreterlərlə kod üzərində dəyişiklik etdikdə bütün proqramı yenidən compile etməyə gərək olmur.

Javascript mühərrikləri compiler və interpreterlərin ən yaxşı xüsusiyyətlərini götürüb və JİT(just-in-time) compilation model yaradıblar. Buna görə Javascript nədir sualına cavab olaraq aşağıdakı ifadəni deyə bilərik: 

-Javascript  lightweight (yaddaşda az yer tutan, minimalistik xüsusiyyət və sintaksı olan, asan icra olunan), interpreter və ya JİT(Just-in-time) compiler proqramlama dilidir.


Sual-2 ---- Java və Javascript arasında olan fərq nədir ? 

Cavab-2 ---- 
Javascript - client-side skriptləmə dilidir. Bəzən Javascriptə brauzer dili də deyilir. Çünki Javascriptlə interaktiv səhifələr yaza bilərik.
Java - obyekt yönümlü proqramlama dilidir və özünün virtual maşın platformu var.Bu virtual maşın platformu demək olar ki, bütün platformalarda işləyə bilən compile olunmuş proqramlar yarada bilir.


sual-3 ---- Javascript data tipləri hansılardır ?
cavab-3 ---- 
Javascriptdə data tipləri 3 yerə bölünür primitiv (primitive), trivial(bilmədim necə tərcümə edim ki, düzgün olsun :) və mürəkkəb (composite).

primitive:
 -number
 -string
 -boolean
 -symbol 

trivial
 -undefined
 -null

composite
 -object
 -function
 -array

Sual-4 ---- isNaN funksiyasını nə zaman istifadə edərdin? 
Cavab-4 ----

isNaN funksiyası daxil edilən dəyərin rəqəm olub-olmadığını müəyyən edir. Müqayisə apararkən ilk öncə dəyəri rəqəm tipinə çevirir. Nəticə olaraq boolean qaytarır.

isNaN ilə Number.isNaN funksiyaları bir-birindən fərqlənir. 
Belə ki, isNaN daxil edilən dəyəri rəqəmə çevirir və alınan nəticənin NaN olub-olmadığını yoxlayır.
Number.isNaN funksiyasında true cavabı almaq üçün daxil edilən dəyər number tip olmalıdır və eyni zamanda NaN olmalıdır.

NaN - not a number. 

Sual-5 ---- undeclared və undefined dəyişənləri haqqında.

Cavab-5 ----

Undefined - bu (error deyim) error əsasən dəyişən təyin olunub amma heç bir dəyər mənimsədilmədiyi zaman yaranır. Undefined keyüord deyil. 

Undeclared - bu error biz yaradılmamış və ya təyin edilməmiş dəyişəni istifadə etmək istəyəndə yaranır. Undeclared dəyişəninin tipi undefined-dir. Global dəyişəndir.

# javascript_suallar
### to be continued :) 
