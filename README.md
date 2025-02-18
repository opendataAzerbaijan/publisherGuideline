# Açıq məlumatlar" portalının iştirakçı təlimatı

Bu təlimat [**CKAN 2.10.7 Overview**](https://docs.ckan.org/en/2.10/) sənədinə əsaslanaraq hazırlanmış və “Açıq Məlumatlar” portalının məlumat idarəetmə sistemindən istifadə edən iştirakçılar üçün nəzərdə tutulmuşdur. Təlimatda iştirakçıların yerinə yetirəcəyi bütün əməliyyatlar ətraflı izah edilmişdir. Bu, onların məlumatların paylaşılması və idarə olunması prosesini effektiv və düzgün şəkildə icra etməsinə kömək edəcək.

# "Açıq Məlumatlar" portalı nədir

**"Açıq Məlumatlar" portalı** ictimaiyyət üçün açıq olan məlumatların toplanması, idarə olunması və paylaşılması üçün rəqəmsal platformadır. Portal şəffaflığı artırır, məlumatlardan istifadəyə şərait yaradır və innovasiyalara dəstək verir. Adətən Məlumat idarəetmə sistemi (CKAN) əsasında işləyir və müxtəlif formatlarda məlumat təqdim edir.

# Əsas anlayışlar

Aşağıdakı cədvəl sizə portalda yer alan Anlayışlar və biznes terminləri haqqında ümumi məlumat verir.

<table border="1" cellpadding="10" cellspacing="0" style="border-collapse: collapse; width: 100%;">
    <thead>
        <tr style="background-color: #f2f2f2;">
            <th>Əsas anlayışlar</th>
            <th>Açıqlama</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Open Data (Açıq məlumat)</td>
            <td>Açıq şəkildə paylaşılan və hər kəsin istifadə edə biləcəyi məlumatlardır.</td>
        </tr>
        <tr>
            <td>Metadata (Metaməlumatlar)</td>
            <td>Məlumat dəstləri haqqında məlumatları təsvir edən məlumatlar.</td>
        </tr>
        <tr>
            <td>Dataset (Məlumat Dəsti)</td>
            <td>Müəyyən bir mövzuya aid məlumatların toplusu. Məsələn, bir bölgənin cinayət statistikası və ya hökumət departamentinin xərcləri haqqında məlumatlar.</td>
        </tr>
        <tr>
            <td>Source (Mənbə)</td>
            <td>İdarəetmə sistemində məlumat dəstinin mənşəyini və ya məlumatın haradan alındığını göstərmək üçün nəzərdə tutulub.</td>
        </tr>
        <tr>
            <td>Resource (Resurs)</td>
            <td>Məlumat dəstindəki faktiki məlumat faylları və ya məlumat mənbələri. Bu fayllar CSV, Excel formatları (XLS, XLSX), XML, PDF və ya digər formalarda ola bilər.</td>
        </tr>
        <tr>
            <td>Activity Stream (Fəaliyyət Axını)</td>
            <td>Məlumat dəstləri və təşkilatlar üzərində aparılan son fəaliyyətlərin xronoloji siyahısı.</td>
        </tr>
        <tr>
            <td>Member (Üzv)</td>
            <td>Təşkilatın private (yalnızca məlumat idarəetmə sistemindən əlçatan olan) məlumat dəstlərini görə bilər.</td>
        </tr>
        <tr>
            <td>Editor (Məlumat redaktoru)</td>
            <td>
                <ul>
                    <li>Member-in bütün funksiyalarını yerinə yetirə bilər.</li>
                    <li>Əlavə olaraq:
                        <ul>
                            <li>Təşkilata yeni Məlumat dəstləri əlavə edə bilər.</li>
                            <li>Təşkilatdakı istənilən Məlumat dəstini redaktə və ya silə bilər.</li>
                            <li>Məlumat dəstləri public və ya private edə bilər.</li>
                        </ul>
                    </li>
                </ul>
            </td>
        </tr>
        <tr>
            <td>Admin (İdarəçi)</td>
            <td>
                <ul>
                    <li>Editor-un bütün funksiyalarını yerinə yetirə bilər.</li>
                    <li>Əlavə olaraq:
                        <ul>
                            <li>Təşkilata yeni iştirakçılar əlavə edə bilər və həmin iştirakçıları Member, Editor və ya Admin olmasını seçə bilər.</li>
                            <li>Təşkilatdakı istənilən iştirakçının rolunu dəyişdirə bilər (digər Admin-lər də daxil olmaqla).</li>
                            <li>Member, Editor və ya digər Admin-ləri təşkilatdan silə bilər.</li>
                            <li>Təşkilat haqqında məlumatları redaktə edə bilər (ad, təsvir, şəkil və s.).</li>
                            <li>Təşkilatı tamamilə silə bilər.</li>
                        </ul>
                    </li>
                </ul>
            </td>
        </tr>
    </tbody>
</table>


# Bölmələr
Məlumat idarəetmə sistemində aşağıdakı əsas bölmələr yer alır.

<table border="1" cellpadding="10" cellspacing="0" style="border-collapse: collapse; width: 100%;">
    <thead>
        <tr style="background-color: #d9e1f2; text-align: left;">
            <th>Bölmə</th>
            <th>Açıqlaması</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Datasets – Məlumat dəstləri</td>
            <td>Datasets bölməsində məlumat idarəetmə sistemində yer alan bütün Məlumat dəstləri görmək, aid olduğu quruma Məlumat dəsti əlavə etmək, onları dəyişdirmək, silmək və digər əməliyyatları həyata keçirmək mümkündür.</td>
        </tr>
        <tr>
            <td>Organizations - Təşkilatlar</td>
            <td>Hər bir Məlumat dəsti bir organization-a aiddir və onu həmin təşkilat idarə edir. Hər bir təşkilatda aşağıda yer alan İştirakçı rolları mövcuddur: Admin, Editor və Member.</td>
        </tr>
        <tr>
            <td>Groups - Kateqoriyalar</td>
            <td>Bu bölmə idarə etmə sistemində olan məlumat dəstlərinin kolleksiyalarını (kateqoriyalarını) yaratmaq və idarə etmək üçün istifadə olunur.</td>
        </tr>
        <tr>
            <td>Data Requests - Məlumat Sorğuları</td>
            <td>Məlumat sorğusu (data request) bir təşkilatdan müəyyən məlumatın açıqlanması yönündə olan müraciətlərin toplandığı bölmədir.</td>
        </tr>
        <tr>
            <td>Showcase - İstifadə Nümunələri</td>
            <td>Bu bölmə, məlumat dəstlərinin tətbiq olunma nümunələrini təqdim edir.</td>
        </tr>
    </tbody>
</table>

# 1\. Məlumat idarəetmə sisteminin istifadəsi

## 1.1. Qeydiyyatdan keçmək

1. İştirakçıya göndərilən dəvət mesajında verilən linkə daxil olun.
2. İştirakçı adı **(Username)** olaraq İştirakçının adı və soyadı qeyd olunmalıdır.
3. Şifrənizi **(Password)** təyin edin və Şifrəni təsdiq edin **(Confirm)**.
4. Şifrəni yeniləyin **(Update Password)** butonuna klikləyərək hesabı aktivləşdirin.

## 1.2. Məlumat idarəetmə sisteminə daxil olmaq

1. Açıq məlumatlar portalının Məlumat idarəetmə sistemində Daxil ol **(Log in)** butonuna klikləyin.
2. Istifadəçi adı **(Username)** və ya elektron poçt **(e-mail)** və şifrə **(password)** daxil edin.
3. Daxil olun **(Login)** butonuna klikləyib daxil olun.

## 1.3. İştirakçı hesabının idarə edilməsi

“Açıq məlumatlar” portalında Məlumat dəstinə daxil olduğumuz zaman fəaliyyət axını bölməsi mövcuddur, bu bölmədə məlumat dəsti üzəridə edilən yeniləmələri dair xronoloji ardıcıllıq və həmçinində yeniləməni edən **İştirakçının adı** portal istifadəçilərinə görünür. Bu səbəblə **İştirakçı adı və digər məlumatlar düzgün** qeyd olunmalıdır.

#### 1.3.1. İştirakçı Profilinin məlumatlarının redaktə edilməsi.

1. Açıq məlumatlar portalının Məlumat idarəetmə sisteminə giriş edin.
2. Profil parametrləri **(Profile Settings)** bölməsinə keçid edin.
3. Aşağıda verdiyim cədvəldəki məlumatları əlavə edə və ya dəyişdirə bilərsiniz.

<table border="1" cellpadding="10" cellspacing="0" style="border-collapse: collapse; width: 100%;">
    <thead>
        <tr style="background-color: #f2f2f2;">
            <th>Data</th>
            <th>Məlumat</th>
            <th>Açıqlaması</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Full name</td>
            <td>Ad, Soyad</td>
            <td>İştirakçının tam adı yazılmalıdır.</td>
        </tr>
        <tr>
            <td>Email</td>
            <td>E-poçt</td>
            <td>İştirakçının Elektron poçt ünvanı yerləşir.</td>
        </tr>
        <tr>
            <td>About</td>
            <td>Haqqında</td>
            <td>İştirakçının təmsil etdiyi qurumdakı struktur bölməsi və vəzifəsi və.s haqqında məlumat verilsin.</td>
        </tr>
        <tr>
            <td>Profile picture</td>
            <td>Profil şəkli</td>
            <td>İştirakçı öz şəkilini bura yerləşdirə bilər.</td>
        </tr>
    </tbody>
</table>

###### Cədvəl 1

4. Profili yeniləyin **(Update Profile)** hissəsinə klik edərək İştirakçı profilinin redaktəsini tamamlaya bilərik.

#### 1.3.2. İştirakçı Profilinin şifrəsinin dəyişdirilməsi

1. Açıq məlumatlar portalının Məlumat idarəetmə sisteminə giriş edin.
2. Profil parametrləri **(Profile Settings)** bölməsinə keçid edin.
3. **Old Password** hissəsinə cari şifrənizi yazın.
4. **Pasword** və **Confirm Password** hissəsinə yeni şifrənizi yazın.
5. Profili yeniləyin **(Update Profile)** hissəsinə klik edərək İştirakçı profilinin şifrə yeniləmə prosesini tamamlayın.

## 1.4. Məlumat dəstlərinin idarə edilməsi

Məlumat dəstləri həmin məlumat dəstini əlavə edən Təşkilat tərəfindən idarə olunur. Sadəcə Kateqoriyalara əlavə edilməsi İRİA tərəfindən idarə edilir. Bu səbəblə iştirakçılar bu Kateqoriyalar bölməsində hər hansı bir **əməliyyat aparmamalıdır.**

### 1.4.1 Məlumat dəstinin əlavə edilməsi

1. Açıq məlumatlar portalının Məlumat idarəetmə sisteminə giriş edin.
2. Əsas naviqasiya panelində Məlumat dəstləri **(Datasets)** bölməsinə klikləyin.
3. Yeni Məlumat dəsti əlavə edin.
4. Məlumat dəsti əlavə et **(Add Dataset)** düyməsini seçin.
5. Aşağıda verilmiş cədvəl əsasında Məlumat dəsti məlumatlarını daxil edin.

<table border="1" cellpadding="10" cellspacing="0" style="border-collapse: collapse; width: 100%;">
    <thead>
        <tr style="background-color: #f2f2f2;">
            <th>Metaməlumat (ingiliscə)</th>
            <th>Metaməlumat (Azərbaycanca)</th>
            <th>Açıqlaması</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Title</td>
            <td>Məlumat dəstinin adı</td>
            <td>Məlumat dəstinə aid təsviri bir başlıq.</td>
        </tr>
        <tr>
            <td>Description</td>
            <td>Məlumat dəstinin açıqlaması</td>
            <td>
                Məlumat dəsti haqqında faydalı qeydlər.<br>
                bu hissəsində məlumatın <strong>*yenilənmə tezliyi(Update Frequency)</strong> haqqında məlumat vermək vacibdir. Yenilənmə tezliyi məlumat dəstinin nə qədər zamandan bir yeniləndiyini bizə göstərir. <br>Nümunə: yenilənmə tezliyi = 1 ay, yenilənmə tezliyi = 3 saat.
            </td>
        </tr>
        <tr>
            <td>Tags</td>
            <td>Etiketlər</td>
            <td>
                Tag, məlumat dəstini təsvir etmək və axtarışı asanlaşdırmaq üçün istifadə olunan açar sözlərdir.<br>
                (məsələn, təhsil, xərclər).
            </td>
        </tr>
        <tr>
            <td>License</td>
            <td>Lisenziya</td>
            <td>
                Lisenziya iştirakçılara həmin məlumat dəstinin istifadəsi, paylaşılması və yenidən işlənməsi ilə bağlı hüququ və məhdudiyyətləri bildirir. <br>
                Lisenziyalar və onların növləri barəsində 1.4.1.3 bölməsindən daha çox məlumat əldə edə bilərsiniz.
            </td>
        </tr>
        <tr>
            <td>Organization</td>
            <td>Təşkilat</td>
            <td>Məlumat dəstini idarə edən təşkilat.</td>
        </tr>
        <tr>
            <td>Visibility</td>
            <td>Görünürlük</td>
            <td>
                Görünürlük hissəsində iki seçim vardır.<br>
                <strong>Private:</strong> yalnız məlumat idarəetmə sistemində məlumat dəsti əlçatan olur.<br>
                <strong>Public:</strong> Məlumat dəsti həmçinin “Açıq məlumatlar” portalında iştirakçılar tərəfindən də əlçatan olur.
            </td>
        </tr>
        <tr>
            <td>Source</td>
            <td>Mənbə</td>
            <td>
                Əgər paylaşılan məlumat dəsti Məlumatı açıqlayan Təşkilatdan başqa yerə aiddirsə, burada həmin link yerləşdirilə bilər.
            </td>
        </tr>
        <tr>
            <td>Version</td>
            <td>Versiya</td>
            <td>
                Məlumat dəstinin cari versiyası. Versiyalandırma haqqında əlavə məlumatı 1.3.1.2. bölməsindən tanış ola bilərsiniz.
            </td>
        </tr>
        <tr>
            <td>Author</td>
            <td>Müəllifin Adı</td>
            <td>Məlumatlardan cavabdeh olan şəxs və ya təşkilatın adı.</td>
        </tr>
        <tr>
            <td>Author Email</td>
            <td>Müəllifin e-poçtu</td>
            <td>Məlumatlardan cavabdeh olan şəxsin və ya təşkilatın elektron poçt ünvanı.</td>
        </tr>
        <tr>
            <td>Maintainer</td>
            <td>Maintainerin adı</td>
            <td>Məlumatlara cavabdeh olan ikinci şəxs.</td>
        </tr>
        <tr>
            <td>Maintainer Email</td>
            <td>Maintainerin e-poçtu</td>
            <td>Məlumat dəstinə cavabdeh ikinci şəxslə əlaqə üçün e-poçt ünvanı.</td>
        </tr>
    </tbody>
</table>

###### Cədvəl 2

6. Məlumat əlavə et **(Add Data)** düyməsinə klikləyərək resurs yükləmə səhifəsinə keçin.
7. Aşağıda verilmiş cədvəl əsasında məlumatlarınızı daxil edin.

<table border="1" cellpadding="10" cellspacing="0" style="border-collapse: collapse; width: 100%;">
    <thead>
        <tr style="background-color: #f2f2f2;">
            <th>Metaməlumat<br>(İngiliscə)</th>
            <th>Metaməlumat<br>(Azərbaycanca)</th>
            <th>Açıqlaması</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Data</td>
            <td>Məlumat</td>
            <td>
                Siz məlumat dəstinin resurslarını (mənbələrini) təyin edirsiniz. <br>
                <strong>Upload</strong> və <strong>Link</strong> şəkilində iki seçim verilir.<br><br>
                <strong>Upload:</strong> Komputerdə yer alan fayllarınız arasında seçim edirsiniz.<br><br>
                <strong>Link:</strong> API linki şəkilində saxladığınız məlumatların linkini daxil edə bilərsiniz. Açıq məlumat dəstinin formatının seçimi haqqında 1.4.3.1. bölməsindən daha ətraflı məlumat ala bilərsiniz.
            </td>
        </tr>
        <tr>
            <td>Name</td>
            <td> Resursun adı</td>
            <td>Resursun təsviri adı</td>
        </tr>
        <tr>
            <td>Description</td>
            <td>Resursun açıqlamaı</td>
            <td>Resurs haqqında fərqləndirici məlumatlar.</td>
        </tr>
        <tr>
            <td>Format</td>
            <td>Format</td>
            <td>Əlavə edilən mənbənin formatı qeyd olunur. Nümunə olaraq: məlumatları strukturludursa, CSV, yarı strukturlu və struktursuzdursa, JSON və ya XML kimi formatlardan istifadə edilə bilər.</td>
        </tr>
    </tbody>
</table>

###### Cədvəl 3

8. Məlumatları yenidən nəzərdən keçirin və bitir **(Finish)** və ya yadda saxla və yenisini əlavə et **(Save & add another)**düyməsini basaraq əməliyyatı tamamlayın.
##### Qeyd: bəzi bölmələrdə 3 dildə (Az, Ru, Eng) məlumat daxil olunası tələb olunur. Hər üç dildə məlumatların daxil edilməsi zəruridir.

#### 1.4.1.1. Yeni Məlumat dəsti əlavə edərkən Create Dataset və Add Data bölmələrində yer alan Title/Description fərqi

_Create Dataset bölməsində olan title və description, Məlumat dəstinin ümumi adını və təsvirini əhatə edir._

_Add Data bölməsində isə hər bir əlavə edilən data file üçün ayrıca title və description təyin edilir. Bu, fərqli data fayllarının bir Məlumat dəsti daxilində ayırd edilməsini təmin edir. Bunun əsas səbəbi, bir Məlumat dəsti daxilində bir neçə data faylının ola bilməsidir. Hər bir fayl fərqli məlumatları əhatə edə bilər._

#### 1.4.1.2. Məlumat idarəetmə sistemində yer alan məlumat dəstlərinin versiyalandırması məntiqi

İştiakçılar təqdim etdikləri Məlumat dəstlərdə baş verən hər bir dəyişiklik növünü Məlumat dəstinin məzmununa və təsirinə görə **Xırda(PATCH)**, **Kiçik(MINOR)**, və ya **Böyük(MAJOR)** versiyalandırma altında təsnif edilir.

<table border="1" cellpadding="10" cellspacing="0" style="border-collapse: collapse; width: 100%;">
    <thead>
        <tr style="background-color: #d9e1f2; text-align: left;">
            <th>Dəyişiklik Növü</th>
            <th>Açıqlama və Nümunələr</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td><strong>PATCH</strong></td>
            <td>
                Dəyişikliklər Məlumat dəstində və ya Meta məlumatda <strong>kiçik səhvlərin düzəldilməsi</strong> üçün istifadə olunur. 
                Məlumat dəstinin strukturu və əsas məzmunu dəyişməz qalır, bu da iştirakçıların Məlumat dəstindən istifadə alışqanlıqlarına təsir etmir.
                <br><br>
                <strong>Nümunə:</strong>
                <ul>
                    <li>"Yaş" sütununda 25-ci sətirdəki məlumat düzəldilir: <strong>28 → 27</strong>. Versiya: <strong>2.0.0 → 2.0.1</strong></li>
                </ul>
            </td>
        </tr>
        <tr>
            <td><strong>MINOR</strong></td>
            <td>
                Dəyişikliklər Məlumat dəstinə <strong>yeni məlumat sütunu, mənbəsi əlavə etmək</strong> və ya <strong>böyük həcmdə məlumat sətirlərinin silinməsi, dəyişdirilməsi, əlavə edilməsi</strong> zamanı istifadə olunur. 
                Bu dəyişikliklər mövcud strukturu pozmur, yəni uyğunluq qorunur.
                <br><br>
                <strong>Nümunə:</strong>
                <ul>
                    <li>"Ünvan" sütunu əlavə edilir. Versiya: <strong>2.0.0 → 2.1.0</strong></li>
                    <li>Təhsil xərcləri Məlumat dəstinə 2024-cü il üzrə olan məlumatlar əlavə edilir. Versiya: <strong>2.1.0 → 2.2.0</strong></li>
                </ul>
            </td>
        </tr>
        <tr>
            <td><strong>MAJOR</strong></td>
            <td>
                Dəyişikliklər Məlumat dəstinin <strong>strukturuna təsir edən dəyişiklikləri</strong> ifadə edir. 
                Bu dəyişikliklərə Məlumat dəstinin bir sütunun silinməsi, formatının dəyişdirilməsi aid edilir ki, bu da iştirakçıların Məlumat dəstindən istifadə alışqanlıqlarına ciddi təsir göstərə bilər.
                <br><br>
                <strong>Nümunə:</strong>
                <ul>
                    <li>"Şəhər" sütunu silinir, yerinə "Bölgə" sütunu əlavə edilir. Versiya: <strong>2.0.0 → 3.0.0</strong></li>
                    <li>Telefon nömrələri tam olaraq "+994" kodu ilə təqdim edilir. Versiya: <strong>3.0.0 → 4.0.0</strong></li>
                </ul>
            </td>
        </tr>
    </tbody>
</table>

###### Cədvəl 4

#### 1.4.1.3. Məlumat idarəetmə sistemində yer alan məlumat dəstlərinə tətbiq oluna biləcək lisenziyalar

**1\. Creative Commons Attribution 4.0 İnternational (CC BY 4.0) License - Kreativ Kommons Beynəlxalq Atributlaşdırma Lisenziyası**

Bu lisenziya müəllif hüquqları ilə qorunan məzmunların, o cümlədən məlumat dəstlərinin sərbəst istifadəsinə imkan yaradır və aşağıdakı şərtləri müəyyən edir:

- **İstinad mütləqdir** – Məlumatdan istifadə edərkən müəllif(lər)ə istinad verilməlidir. Lisenziya mətninə və ya ona keçid göstərilməlidir.
- **Dəyişikliklər qeydə alınmalıdır** – Əgər məlumat dəstinə əlavə, çıxarış və ya başqa dəyişikliklər edilərsə, bu, açıq şəkildə bildirilməlidir. Müəllifin rəsmi təsdiqi kimi təqdim etmək olmaz.
- **Sərbəst istifadə və paylaşım** – Məlumatı kommersiya məqsədilə də daxil olmaqla, istənilən məqsədlə istifadə və paylaşmaq olar.
- **Uyğunlaşdırma və modifikasiya mümkündür** – Məlumat dəsti redaktə edilə, başqa mənbələrlə birləşdirilə və yeni məlumat dəsti yaradıla bilər, amma müəllifə istinad şərtdir.
- **Texniki dəyişikliklərə icazə verilir** – Məlumat istənilən formata çevrilə bilər (CSV, SQL, JSON və s.), eləcə də müxtəlif proqramlarda istifadəsi mümkündür.
- **Digər şərtləri ilə burden tanış ola bilərsiniz**: [Legal Code - Attribution 4.0 International - Creative Commons](https://creativecommons.org/licenses/by/4.0/legalcode)

**2\. Creative Commons Zero (CC0) License - Kreativ Kommons Sıfır Lisenziyası**

- Məzmuna dair bütün hüquqlardan imtina edildiyini və onun ictimai mülkiyyətə verildiyini ifadə edir. Məzmundan istənilən məqsədlə, məhdudiyyətsiz və istinadsız istifadə etmək mümkündür.

### 1.4.2. Mövcud Məlumat dəstinə düzəliş edilməsi

#### 1.4.2.1. Mövcud Məlumat dəstinin metaməlumatlarına düzəliş edilməsi

1. Açıq məlumatlar portalının Məlumat idarəetmə sisteminə giriş edin.
2. Əsas naviqasiya panelində Məlumat dəsti **(Datasets)** bölməsinə klikləyin.
3. Məlumat dəstinin idarəetmə interfeysinə keçmək üçün İdarə et **(Manage)** düyməsinə klikləyin.
4. Metaməlumatları redaktə et **(Edit Metadata)** bölməsini seçin.
5. Dəyişmək istədiyiniz məlumatları **cədvəl 2** əsasında yeniləyin.
6. Bütün yenilikləri nəzərdən keçirin və dəyişiklikləri tətbiq etmək üçün Yadda saxla **(Save)** düyməsini basın.

#### 1.4.2.2. Mövcud Məlumat dəstini silmək

1. Açıq məlumatlar portalının Məlumat idarəetmə sisteminə giriş edin.
2. Əsas naviqasiya panelində Məlumat dəsti **(Datasets)** bölməsinə klikləyin.
3. Məlumat dəstiin idarəetmə interfeysinə keçmək üçün İdarə et **(Manage)** düyməsinə klikləyin.
4. Silmək **(Delete)** düyməsini seçin: Təsdiq dialoq pəncərəsini göstərəcək.
5. Təsdiq et **(Confirm)** düyməsini basaraq Məlumat dəstii silmə prosesini tamamlayın.

### 1.4.3. Mövcud məlumat dəstinin resurslarının idarə olunması

#### 1.4.3.1. Mövcud Məlumat dəstinə resursunun formatının təyin edilməsi.
  Müxtəlif məlumat strukturları üçün fərqli fayl formatları nəzərə alınmalıdır. Əsas üç məlumat strukturu mövcuddur: cədvəl (tabular), iyerarxik (hierarchical) və şəbəkə (network).
  <table border="1" cellpadding="10" cellspacing="0" style="border-collapse: collapse; width: 100%;">
    <thead>
        <tr style="background-color: #d9e1f2; text-align: left;">
            <th>Məlumat Strukturu</th>
            <th>Açıqlama</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td><strong>Cədvəl (Tabular)</strong></td>
            <td>
                Məlumatların ən geniş yayılmış strukturu <strong>cədvəl formatıdır</strong>. Bu tip məlumatlar <strong>sətirlər və sütunlar</strong> şəklində təşkil edilir və ardıcıl dəyərləri ehtiva edir (məsələn, xərclər siyahısı).<br><br>
                Əgər məlumatlar <strong>bir-biri ilə əlaqəli deyilsə</strong> və <strong>ayrı-ayrı qeydlərdən ibarətdirsə</strong>, <strong>CSV (Comma-Separated Values)</strong> kimi cədvəl formatı ən uyğun seçimdir.
            </td>
        </tr>
        <tr>
            <td><strong>İyerarxik (Hierarchical)</strong></td>
            <td>
                İyerarxik məlumat strukturu <strong>məlumat nöqtələri arasındakı əlaqələri</strong> göstərir. Buna <strong>ailə ağacı, ölkələrdəki bələdiyyələr və ya təşkilati strukturlar</strong> misal ola bilər.<br><br>
                Əgər məlumatlar <strong>valideyn-övlad münasibəti əsasında</strong> qurulub və <strong>ağacvari (tree-like) bir quruluşa malikdirsə</strong>, <strong>JSON və ya XML formatı</strong> ideal seçimdir.
            </td>
        </tr>
        <tr>
            <td><strong>Şəbəkə (Network)</strong></td>
            <td>
                Şəbəkə əsaslı məlumat strukturu <strong>istənilən elementlər arasında çoxsəviyyəli əlaqələrin</strong> mövcud olmasına imkan verir.<br><br>
                Sosial şəbəkələr bu struktura yaxşı nümunədir. <strong>Facebook dostlarınızı və onların dostlarını düşünün</strong> – burada əlaqələr <strong>müxtəlif istiqamətlərdə</strong> mövcuddur. <strong>LinkedIn</strong>-də birinci, ikinci və üçüncü səviyyəli əlaqələri bu şəkildə təsvir etmək olar.<br><br>
                İnternet də bir <strong>şəbəkə strukturlu məlumat sistemidir</strong>, çünki veb səhifələr bir çox digər səhifələrlə əlaqəlidir və bu əlaqələr müxtəlif istiqamətlərdə qurula bilər. Uyğun format olaraq <strong>RDF</strong> istifadə edilə bilər.<br><br>
                <strong>Nümunə:</strong>
                <ul>
                    <li>Facebook və LinkedIn dostluq əlaqələri</li>
                    <li>Veb-saytların hiperlinklərlə bir-birinə bağlanması</li>
                </ul>
            </td>
        </tr>
    </tbody>
</table>

###### Cədvəl 5

#### 1.4.3.2. Mövcud Məlumat dəstinə yeni resurs əlavə etmək

1. Açıq məlumatlar portalının Məlumat idarəetmə sisteminə giriş edin.
2. Əsas naviqasiya panelində Məlumat dəsti **(Datasets)** bölməsinə klikləyin.
3. Məlumat dəstinin idarəetmə interfeysinə keçmək üçün İdarə et **(Manage)** düyməsinə klikləyin.
4. Resurlar **(Resources)** bölməsinə keçin.
5. Yeni resurs əlavə et **(Add new resource)** düyməsini basın.
6. Yeni resursun məlumatlarını **cədvəl 3** əsasında əlavə edin.
7. Məlumatları yenidən nəzərdən keçirin və Əlavə et **(Add)** və ya Yadda saxla və yenisini əlavə et **(Save & add another)** düyməsini basaraq yayımlayın.

#### 1.4.3.3. Mövcud Məlumat dəstinin resurs məlumatlarına düzəliş edilməsi

1. Açıq məlumatlar portalının Məlumat idarəetmə sisteminə giriş edin.
2. Əsas naviqasiya panelində Məlumat dəsti **(Datasets)** bölməsinə klikləyin.
3. Məlumat dəstinin idarəetmə interfeysinə keçmək üçün İdarə et **(Manage)** düyməsinə klikləyin.
4. Resurslar **(Resources)** bölməsini seçin.
5. Redaktə etmək istədiyiniz mövcud resursları **cədvəl 3** əsasında dəyişdirin.
6. Yenilənmələri nəzərdən keçirin və tətbiq etmək üçün Resursları yenilə **(Update Resources)** düyməsini basın.

#### 1.4.3.4. Məlumat dəstində mövcud resurs (məlumat faylını) silmək

1. Açıq məlumatlar portalının Məlumat idarəetmə sisteminə giriş edin.
2. Əsas naviqasiya panelində Məlumat dəsti **(Datasets)** bölməsinə klikləyin.
3. Məlumat dəstinin idarəetmə interfeysinə keçmək üçün İdarə et **(Manage)** düyməsinə klikləyin.
4. Resurslar **(Resources)** bölməsini seçin.
5. Silmək istədiyiniz mövcud resursu seçin.
6. Silmək **(Delete)** düyməsini seçin: dialoq pəncərəsini göstərəcək.
7. Təsdiq et **(Confirm)** düyməsini basaraq Məlumat dəstini silmə prosesini tamamlayın.

### 1.4.4. Mövcud Məlumat dəstinin əməkdaşların (Collaborators) idarə olunması

Bu funksiyaya Məlumat dəsti səviyyəsində icazələrin idarə edilməsi təmin edilir. Bu zaman uyğun icazəsi olan əməkdaşlar, istənilən fərdi Məlumat dəsti üzərində verilən rola uyğun əməliyyatları icra edə bilirlər.

#### 1.4.4.1. Mövcud Məlumat dəstinin əməkdaşların əlavə edilməsi

1. Açıq məlumatlar portalının Məlumat idarəetmə sisteminə giriş edin.
2. Əsas naviqasiya panelində Məlumat dəsti **(Datasets)** bölməsinə klikləyin.
3. Məlumat dəstinin idarəetmə interfeysinə keçmək üçün İdarət et **(Manage)** düyməsinə klikləyin.
4. Əməkdaşlar **(Collaborators)** bölməsini seçin.
5. Əməkdaşlar əlavə et **(Add Collaborators)** butonuna klikləyin.
6. Axtarış hissəsinə iştirakçı adını daxil edərək əməkdaş kimi təyin etmək istədiyiniz iştirakçını seçin.
7. Role bölməsindən member, editor və admin arasından uyğun rolu seçin (anlayışlar bölməsindən rollar haqqında məlumt əldə edə bilərsiniz).
8. Əməkdaş əlavə et **(Add Collaborator)** butonuna klikləyərək yeni əməkdaşınızı əlavə edin.

#### 1.4.4.2. Mövcud Məlumat dəstinin əməkdaşların rollarının dəyişdirilməsi

1. Açıq məlumatlar portalının Məlumat idarəetmə sisteminə giriş edin.
2. Əsas naviqasiya panelində Məlumat dəsti **(Datasets)** bölməsinə klikləyin.
3. Məlumat dəstinin idarəetmə interfeysinə keçmək üçün İdarət et **(Manage)** düyməsinə klikləyin.
4. Əməkdaşlar **(Collaborators)** bölməsini seçin.
5. Rolunu dəyişmək istədiyiniz iştirakçının açar butonuna klikləyin.
6. Rolunu uyğun olaraq Admin, Editor, Member’ə dəyişdirdikdən sonra əməkdaşı yeniləyin **(Update Collaborator)** butonuna klikləyərək prosesi tamamlayaq.

#### 1.4.4.3. Mövcud Məlumat dəstinin əməkdaşların silinməsi

1. Açıq məlumatlar portalının Məlumat idarəetmə sisteminə giriş edin.
2. Əsas naviqasiya panelində Məlumat dəsti **(Datasets)** bölməsinə klikləyin.
3. Məlumat dəstinin idarəetmə interfeysinə keçmək üçün İdarət et **(Manage)** düyməsinə klikləyin.
4. Əməkdaşlar **(Collaborators)** bölməsini seçin.
5. Silmək istədiyiniz iştirakçının qarşısındakı **X** butonuna klikləyin.
6. Açılan dialoq qutusunda Təsdiq et **(Confirm)** butonuna klikləyərək prosesi tamamlayın.

## 1.5. Mövcud Təşkilatı (Oganization) idarə edilməsi

#### 1.5.1. Təşkilat məlumatlarının redaktə edilməsi

1. Açıq məlumatlar portalının Məlumat idarəetmə sisteminə giriş edin.
2. Əsas naviqasiya panelində Təşkilatlar **(Organizations)** bölməsinə klikləyin.
3. Məlumat dəstinin idarəetmə interfeysinə keçmək üçün İdarə et **(Manage)** düyməsinə klikləyin.
4. Lazım olan sahələri aşağıdakı cədvək əsasında dəyişdirin.

<table border="1" cellpadding="10" cellspacing="0" style="border-collapse: collapse; width: 100%;">
    <thead>
        <tr style="background-color: #d9e1f2; text-align: left;">
            <th>Metaməlumat (İngiliscə)</th>
            <th>Metaməlumat (Azərbaycanca)</th>
            <th>Açıqlaması</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Title</td>
            <td>Başlıq</td>
            <td>Təşkilatın adı</td>
        </tr>
        <tr>
            <td>Description</td>
            <td>Açıqlama</td>
            <td>Təşkilat haqqında məlumat</td>
        </tr>
        <tr>
            <td>Image</td>
            <td>Şəkil</td>
            <td>Təşkilatın şəkil və ya <a href="#">logosu</a>. 43 x 43 piksel ölçüsündə olması məqsədə uyğundur.</td>
        </tr>
    </tbody>
</table>

###### Cədvəl 6

5. Yeniləmələrinizi nəzərdən keçirin və dəyişiklikləri saxlamaq üçün Təşkilatı yeniləyin **(Update Organization)** düyməsinə klikləyin.

#### 1.5.2. Mövcud Təşkilatdakı memberləri (üzvləri) rollarını dəyişmək.

##### Üsul 1

1. Açıq məlumatlar portalının Məlumat idarəetmə sisteminə giriş edin.
2. Əsas naviqasiya panelində Təşkilatlar **(Organizations)** bölməsinə klikləyin.  
3. Məlumat dəstinin idarəetmə interfeysinə keçmək üçün İdarə et **(Manage)** düyməsinə klikləyin.  
4. Üzvlər **(Members)** bölməsini seçin.
5. Rolunu dəyişmək istədiyiniz iştirakçının qarşısında olan açar butonuna klikləyin.
6. Rolunu uyğun olaraq Admin, Editor, Member’ə dəyişdirdikdən sonra Üzvü yeniləyin **(Update Member)** butonuna klikləyək prosesi tamamlayın.

##### Üsul 2

1. Açıq məlumatlar portalının Məlumat idarəetmə sisteminə giriş edin.
2. Əsas naviqasiya panelində Təşkilatlar **(Organizations)** bölməsinə klikləyin.  
3. Məlumat dəstinin idarəetmə interfeysinə keçmək üçün İdarə et **(Manage)** düyməsinə klikləyin.  
4. Üzvlər **(Members)** bölməsini seçin.
5. Üzv əlavə et **(Add Member)** butonuna klikləyin.
6. Mövcud iştirakçı **(Existing user)** hissəsindən iştirakçı adını tapıb rolunu (Admin, Editor, Member) olaraq dəyişdirin.olaraq dəyişdirin.
7. Üzv əlavə et **(Add Member)** butonuna klikləyərək iştirakçının rolunu dəyişin.

#### 1.5.3. Mövcud Təşkilatdakı memberləri (üzvləri) silmək.

1. Açıq məlumatlar portalının Məlumat idarəetmə sisteminə giriş edin.
2. İdarəetmə sisteminə girişƏsas naviqasiya panelində Təşkilatlar **(Organizations)** bölməsinə klikləyin.  
3. Məlumat dəstinin idarəetmə interfeysinə keçmək üçün İdarə et **(Manage)** düyməsinə klikləyin.  
4. Üzvlər **(Members)** bölməsini seçin.
5. Silmək istədiyiniz iştirakçının sağ tərəfində olan **X** butonuna klikləyin.
6. Açılan Dialoq pəncərəsində Təsdiq et **(Confirm)** butonuna klikləyərək silmə prosesini tamamlayın.

## 1.6. Portalın API vasitəsilə istifadəsi

### 1.6.1 API açarının yaradılması

1. Açıq məlumatlar portalının Məlumat idarəetmə sisteminə giriş edin.
2. Profilinizə (İştirakçı adınızın yazıldığı hissə) klikləyin.
3. API açarlar **(API Tokens)** bölməsinə keçid edin.
4. Ad **(Name)** hissəsində API açarınızın adını yazın.
5. API açarı yarat **(Create API Token)** butonuna basaraq API açarınızı yaratma prosesini tamamlayın.

Bu API açarından istifadə edərək məlumat dəstlərini yükləmək üçün aşağıdakı fayllardan istifadə edə bilərsiniz.

<https://docs.ckan.org/en/2.10/maintaining/filestore.html?highlight=resource_create#filestore-api>

[API guide — CKAN 2.10.7 documentation](https://docs.ckan.org/en/2.10/api/index.html)

### 1.6.2. API açarının silinməsi

1. Açıq məlumatlar portalının Məlumat idarəetmə sisteminə giriş edin.
2. Profilinizə (İştirakçı adınızın yazıldığı hissə) klikləyin.
3. API açarlar **(API Tokens)** bölməsinə keçid edin.
4. Silmək istədiyiniz tokeni **X** butonuna basaraq silə bilərsiniz.
   
&nbsp;

### 1.6.3 API vasitəsi ilə məlumat dəstlərinin əlavə edilməsi

**1\. Məlumat idarəetmə sistemində API-ə qoşulma və faylları ehtiva edən mənbə qovluq.**


\# CKAN instance main URL
ckan_url = "<http://opendata-api.idda.az/api/3/action>"

\# Package create – for creating dataset itself (without files, which later can contain any number of # files):
resource_create_url = ckan_url + "/resource_create"

\# Resource create – for adding specific file with data into already created CKAN dataset:
package_create_url = ckan_url + "/package_create"

\# Title translations are optional
trns_en = GoogleTranslator(source='az', target='en')
trns_ru = GoogleTranslator(source='az', target='ru')

\# API key is unique for each publisher organization and generated/shared by CKAN Admin. Below is just an example
api_key = ("eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJqdGkiOiJmN2ExYmMyY2QzZTRlNWY2YTZiN2M4ZDllMGYxYTIiLCJpYXQiOjE3MzM5MTI0MDF9.jgbfdY76kkk")

\# Defining that authorisation is made by API key
headers = {"Authorization": api_key}

\# Your directory where required dataset files are located:
dir_path = '&lt;/your_directory_where_files_located&gt;'

&nbsp;


**2\. Məlumat dəstində Metaməlumatların doldurulması üçün element adları.**


&nbsp;       package_data = {

&nbsp;       "\_csrf_token": "IjA1ODU0MmU2MGZjYmI4MmFjOTIxOTI0YzAxYzE3NGExYzBmYzU1ZDIi.Z1lN-A.t9BcCBwgWm1hSubcD_4SVO182uo",

&nbsp;       "name": dataset_name,

&nbsp;       "title_translated-az": dataset_title, # title in Azerbaijani

&nbsp;       "title_translated-en": title_en, # title in English

&nbsp;       "title_translated-ru": title_ru, # title in Russian

&nbsp;       "url": dataset_name,  # Easy practice to generate URL is using dataset name

&nbsp;       "owner_org": '9b44b52f-2116-48c8-9565-d9dc026dca8f',   # This ID is unique for each publisher  

&nbsp;       # organization and share by CKAN admin

&nbsp;       "license_id": 'notspecified',

&nbsp;       "private": False, # if set False, it will be publicly available in portal

&nbsp;       "tag_string": directory_name  # Easy practice to generate TAG is using directory name

    }

**3**. **Məlumat dəstində konkret faylın metaməlumatlarının doldurulması üçün element adları**.

&nbsp;       # Get the package ID from the response. Package is created code above, before resource.

&nbsp;       package_id = package_response.json()\["result"\]\["id"\]

&nbsp;       # Parameters for the resource

&nbsp;       resource_data = {

&nbsp;           "package_id": package_id,

&nbsp;           "name": resource_name, # name of the file

&nbsp;           "format": 'CSV', # as your file extensions (csv, json,etc)

&nbsp;           "name_translated-az": resource_name,

&nbsp;           "name_translated-en":title_en, # name of the file in English

&nbsp;           "name_translated-ru":title_ru # name of the file in Russian

&nbsp;

&nbsp;       }  

&nbsp;

