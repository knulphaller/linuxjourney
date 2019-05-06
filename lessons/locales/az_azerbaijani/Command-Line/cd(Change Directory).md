# cd (Change Directory)

## Dərsin Mövzusu

İndi siz harada olduğunuzu bilirsiniz və indi gəlin fayl sistemində necə hərəkət edəcəyimizi öyrənək.Yadınızda saxlayın ki, biz yollardan (path) istifadə edərək qovluqlar arası səyahət edəcəyik.Yolu göstərmək üçün iki fərqli üsuldan istifadə edə bilərik, tam yol və nisbi yol.

<ul>
<li> Tam yol: Bu yol sizin kök (root) qovluqundan indiki dayandığınız mövqeyə qədər olan tam yoldur.Kök sizin baş şefinizdir.Hər zaman, yolunuz hər dəfə / işarəsindən başlandıqda bu, o deməkdir ki, siz kök qovluqundan başlayırsınız, məsələn:  /home/pete/Desktop.</li>

<li>Nisbi yol: Bu yol hal-hazırda fayl sisteminizdə haradasınızsa oranı göstərir.Deyək ki, sizin yolunuz /home/pete/Documents bu şəkildə və siz Documents qovluqunun içində olan taxes qovluğunun içərisinə daxil olmaq istəyiriniz.Ancaq bu yol üsulunda kök qovluqundan başlayaraq bunun kimi /home/pete/Documents/taxes yazmaq əvəzinə taxes/ yaza bilərsiniz.</li>
</ul>

İndi siz yolların (path) necə işlədiyini anladınız, sadəcə olaraq istədiyimiz qovluqa keçməyimizə kömək ola biləcək son bir şey qaldı.Xoşbəxtlikdən bunun üçün cd və ya “Change Directory” (qovluğu dəyişdirmək) komandası var.

<pre>$ cd /home/pete/Pictures</pre> 

Burada isə mən indiki yerimi /home/pete/Pictures-ə dəyişdim.İndi isə bu qovluğun daxilində olan Hawaii qovluğuna keçmək istəyirəm.Bu qovluğa belə keçə bilərik:

<pre>$ cd Hawaii</pre>

Qovluğun adını necə istifadə etdiyimə diqqət yetirdiniz? Çünki mən artıq /home/pete/Pictures qovluğunun daxilindəyəm.Bu yollar, yəni tam və nisbi yollar insanı yora bilər, lakin xoşbəxtlikdən sizə göstərə biləcəyim bəzi qısayollar var.

<ul>
<li>.(cari qovluq) Bu sizin hazırda olduğunuz qovluqdur.</li>
<li>..(əvvəlki qovluq) Bu sizi hazırda olduğunuz mövqedən bir öncəki qovluğa qaytrır.</li>
<li>~ (home(ev) qovluğu) Bu sizi əvəzolunmaz olan “home directory”-ə qaytarır. /home/pete bunun kimi.</li>
<li>-(əvvəlki qovluq) Bu sizi ən əvvəldə olan qovluğa aparır.</li>
</u1>

<pre>$ cd .
$ cd ..
$ cd ~
$ cd -
</pre>
Gəlin yoxlayaq!

## Tapşırıq
<o1>
<li>cd komandasını heç bir parametr olmadan yoxlayın, görün nə baş verəcək?
</o1>

## Sual-Cavab
Siz /home/pete/Pictures qovluqundasınız və /home/pete qovluğuna getmək istəyirsiniz, hansı qısayolu istifadə edərsiniz?

## Cavab
cd ..
