# pwd (Print Working Directory)

## Dərsin Mövzusu

Linux-da hər şey fayldır.Siz bu səyahətin dərinliklərində bunu daha yaxşı başa düşəcəksiniz, amma hələlik bunu yadınızda saxlayın.Hər bir fayl leararxik ağacda (tree) təşkil olunur.Fayl sistemindəki ilk qovluq kök (root) qovluğudur, buna misal olaraq:
<pre>/
|-- bin
|   |-- file1
|   |-- file2
|-- etc
|   |-- file3
|   `-- directory1
|       |-- file4
|       `-- file5
|-- home
|-- var
</pre>

Hər bir faylın və ya qovluğun yeri yol (path) olaraq adlandırılır.Əgər evinizin içində pete qovluğu və o qovluqun da içində Filmlər adlandırılmış qovluq varsa, bu yol belə görünər: /home/pete/Filmlər, sizcə də çox asan deyil?

Fayl sistemlərinin naviqasiyası, harada olduğunuzu və haraya gedəcəyinizi tam olaraq bilsəniz, bu komanda sizə çox yardımçı ola bilər.Əgər siz harada olduğunuzu bilmək istəsəniz, pwd komandasını istifadə etməlisiniz və bu qısaltmanın mənası “print working directory” (faylların çap işi)-dir.Bu komanda tam olaraq kök(root) faylından başlayarq indi dayandığınız mövqeyə qədər yolunuzu göstərir.

<pre>$ pwd</pre>

Sən haradasan, mən haradayam? Gəlin yoxlayaq.

## Tapşırıq
Bu mövzu ilə əlavə tapşırıq yoxdur.

## Sual-Cavab
Hal-hazırda hansı faylda olduğumuzu necə öyrənə bilərik?

## Cavab
pwd
