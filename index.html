<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width,initial-scale=1,viewport-fit=cover">
<title>برا السالفة</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Lalezar&family=Readex+Pro:wght@400;600&display=swap" rel="stylesheet">
<style>
:root{--bg:#160F2B;--card:#241A45;--line:#3a2d68;--ink:#F4EEFF;--mut:#9A8FC2;--hot:#FF5C8A;--mint:#6EF2C0}
*{box-sizing:border-box;margin:0}
body{background:var(--bg);color:var(--ink);font:400 17px/1.6 'Readex Pro',system-ui,sans-serif;min-height:100dvh;padding:env(safe-area-inset-top) 0 env(safe-area-inset-bottom)}
#app{position:relative;max-width:480px;margin:auto;padding:62px 18px 30px;display:flex;flex-direction:column;gap:14px;min-height:100dvh}
h1,h2{font-family:Lalezar,'Readex Pro',sans-serif;font-weight:400;line-height:1.15}
h1{font-size:68px;color:var(--hot)}
h2{font-size:34px}
.m{color:var(--mut);font-size:15px}
.b{font:inherit;font-weight:600;font-size:18px;border:0;border-radius:14px;padding:14px 18px;background:var(--mint);color:#10241d;cursor:pointer;width:100%}
.b.alt{background:var(--card);color:var(--ink);border:1.5px solid var(--line)}
.b:disabled,.chip:disabled{opacity:.45;cursor:default}
.i{width:100%;padding:13px 14px;border-radius:12px;border:1.5px solid var(--line);background:var(--card);color:var(--ink);font:inherit}
.row{display:flex;flex-wrap:wrap;gap:8px}
.chip{font:inherit;font-size:15px;padding:8px 14px;border-radius:99px;background:var(--card);border:1.5px solid var(--line);color:var(--ink)}
button.chip{cursor:pointer}
.chip.on{background:var(--hot);border-color:var(--hot);color:#fff}
.code{font:400 54px/1 Lalezar;letter-spacing:.15em;color:var(--mint);text-align:center;background:var(--card);border-radius:18px;padding:16px;direction:ltr}
.role{border-radius:26px;min-height:46vh;display:grid;place-items:center;text-align:center;padding:24px;background:var(--card);border:2px dashed #4a3b85;cursor:pointer}
.role.in{background:var(--mint);color:#10241d;border:0;animation:fl .45s}
.role.out{background:var(--hot);color:#fff;border:0;animation:fl .45s}
.big{font:400 56px/1.1 Lalezar,sans-serif}
.mid{margin:auto;text-align:center;display:grid;gap:14px}
.pl{display:flex;justify-content:space-between;background:var(--card);padding:10px 14px;border-radius:12px}
.bar{border-radius:14px;padding:10px 14px;text-align:center;display:grid;line-height:1.3}
.bar b{font:400 28px/1.2 Lalezar,sans-serif}.bar small{font-size:14px}
.bar.out{background:#FF3B4E;color:#fff}.bar.in{background:var(--mint);color:#10241d}
.gear{position:absolute;top:calc(env(safe-area-inset-top,0px) + 10px);left:12px;width:42px;height:42px;border-radius:50%;border:1.5px solid var(--line);background:var(--card);color:var(--ink);font-size:20px;cursor:pointer;padding:0}
.made{color:#FFD84A;font-size:15px}
.modal{position:fixed;inset:0;background:#000a;display:grid;place-items:end center;z-index:9}
.sheet{background:var(--bg);border:1.5px solid var(--line);border-radius:22px 22px 0 0;padding:20px 18px 26px;width:100%;max-width:480px;display:grid;gap:12px;max-height:85dvh;overflow:auto}
.gc{display:grid;gap:4px;text-align:center;padding:26px 18px;border-radius:22px;border:0;font:inherit;color:#fff;cursor:pointer}
.gt{font:400 40px/1.1 Lalezar,sans-serif}.gc small{font-size:15px;opacity:.92}
.gear.adm{left:auto;right:12px;background:#2F6BFF;border-color:#2F6BFF;color:#fff}
.b.pk{background:var(--hot);color:#fff}
@keyframes fl{from{transform:scaleX(.05)}}
@media(prefers-reduced-motion:reduce){.role{animation:none!important}}
:focus-visible{outline:3px solid var(--mint);outline-offset:2px}
</style>
</head>
<body>
<main id="app"></main>
<script src="https://cdn.jsdelivr.net/npm/peerjs@1.5.4/dist/peerjs.min.js"></script>
<script>
const $=s=>document.querySelector(s),app=$('#app');
const esc=t=>String(t).replace(/[&<>"]/g,c=>({'&':'&amp;','<':'&lt;','>':'&gt;','"':'&quot;'}[c]));
const pick=a=>a[Math.random()*a.length|0],shuf=a=>a.map(x=>[Math.random(),x]).sort((p,q)=>p[0]-q[0]).map(x=>x[1]);
const C=o=>Object.fromEntries(Object.entries(o).map(([k,v])=>[k,v.split('،')]));
const CATS=C({
'أكلات':'كبسة،شاورما،برجر،بيتزا،مندي،مطبق،سمبوسة،هريس،جريش،مقلقل،فلافل،كنافة،لقيمات،مضغوط،سوشي،كباب',
'مدن':'الرياض،جدة،مكة،المدينة،الدمام،أبها،الدوحة،دبي،الكويت،القاهرة،بيروت،عمّان،إسطنبول،باريس،لندن،طوكيو',
'حيوانات':'جمل،صقر،حصان،أسد،نمر،قطة،بطريق،زرافة،دلفين،ذئب،غزال،ثعلب،فيل،قرد،نعامة،أرنب',
'مشاهير':'رونالدو،ميسي،نيمار،محمد صلاح،مايكل جاكسون،أم كلثوم،محمد عبده،راشد الماجد،إيلون ماسك،شاكيرا،بيل غيتس،بنزيما،ليبرون جيمس،مستر بيست',
'ألعاب':'ماين كرافت،فورتنايت،ببجي،روبلوكس،فيفا،جي تي أي،أمونغ أس،كول أوف ديوتي،ماريو،زيلدا،فالورانت،كلاش رويال،بلاي ستيشن،ليغ أوف ليجندز',
'أنمي':'ناروتو،ون بيس،دراغون بول،ديث نوت،هجوم العمالقة،بليتش،كابتن ماجد،المحقق كونان،ساسكي،لوفي،غوكو،ليفاي،زورو،بوكيمون',
'أماكن':'مطار،مستشفى،مدرسة،مول،مطعم،شاطئ،صحراء،ملعب،مسجد،سينما،محطة بنزين،مخيم،حديقة،فندق،مكتبة،بقالة',
'أغراض':'ثلاجة،سيارة،جوال،مكيف،كرسي،مفتاح،نظارة،ساعة،شنطة،مظلة،مرآة،دلة قهوة،تلفزيون،سرير،مروحة،سماعة',
'ألوان':'أحمر،أزرق،أخضر،أصفر،برتقالي،بنفسجي،وردي،أسود،أبيض،رمادي،بني،ذهبي،فضي،تركوازي،بيج،كحلي',
'عالم البحار':'قرش،دلفين،حوت،أخطبوط،سلحفاة بحرية،قنديل البحر،نجم البحر،سلطعون،جمبري،حصان البحر،فقمة،سمكة المهرج،حبار،سمكة السيف،ثعبان البحر،محار',
'رياضات':'كرة قدم،كرة سلة،تنس،سباحة،بلياردو،كرة طائرة،ملاكمة،جري،سباق خيل،غوص،تزلج،رماية،مصارعة،بادل،ركوب دراجات،شطرنج',
'مشروبات':'شاي،قهوة عربية،قهوة مثلجة،عصير ليمون،كولا،حليب،كرك،لبن،ماء،عصير برتقال،موهيتو،شاي أخضر،نسكافيه،عصير مانجو،ميلك شيك،كابتشينو',
'دول':'السعودية،الإمارات،الكويت،قطر،مصر،الأردن،المغرب،تركيا،اليابان،البرازيل،أمريكا،فرنسا،ألمانيا،إيطاليا،الهند،الصين',
'فواكه وخضار':'مانجو،بطيخ،خيار،رمان،تفاح،موز،طماطم،جزر،فراولة،عنب،بصل،بطاطس،تمر،برتقال،باذنجان،ليمون'
});
const LN={ar:'العربية',en:'English',tr:'Türkçe',fr:'Français',es:'Español',de:'Deutsch',ur:'اردو',id:'Bahasa Indonesia'},RTL=['ar','ur'];
const K='tag made nm cr cd jn lc who min3 pl addp cont back room inv cat go waitH pass iam turn outT outH tap ok wait asks askH asksX tovote whoOut caught guessH wg ow iw theOut theW gs nc vts again endR exit yOut act yIn full busy left set lang outc done outsN eName eLib eConn share copied'.split(' ');
const D={
ar:"الكل يعرف السالفة إلا واحد. اكتشفه قبل لا يكتشفكم.|تم صنع هذه اللعبة بواسطة Kitawore|اسمك|أنشئ غرفة أونلاين|كود الغرفة|انضم|نلعب على جوال واحد|مين اللاعبين؟|نحتاج ٣ لاعبين على الأقل|لاعب|إضافة لاعب|كمّلنا|رجوع|الغرفة|شارك رابط الدعوة|الفئة|ابدأ الجولة|ننتظر المضيف…|مرر الجوال لـ|أنا|هذا دورك تشوف السالفة. لا أحد يشوف جوالك.|برا السالفة|ما تعرف الكلمة. استمع للأجوبة وتظاهر إنك تعرفها.|اضغط عشان تشوف دورك|فهمت، أخفِ|ننتظر البقية|الأسئلة|كل واحد يسأل اللي بعده سؤال عن السالفة بدون ما يقولها صريحة، والكل يجاوب.|يسأل|خلصنا، نصوّت|مين برا السالفة؟|انكشفت!|خمّن الكلمة وتفوز.|انكشف {n}، بس عنده فرصة أخيرة يخمّن الكلمة…|فاز اللي برا السالفة|فازوا اللي داخل السالفة|برا السالفة:|الكلمة:|خمّن:|ما انكشف، الأصوات راحت لغيره.|أصوات|جولة جديدة|إنهاء الجولة|خروج|أنت برا السالفة|سوّي نفسك معهم|أنت جوا السالفة|الغرفة ممتلئة (١٢ لاعب)|اللعبة شغالة، انتظر الجولة الجديدة|انسحب {n}، رجعنا للغرفة|إعدادات الغرفة|اللغة|عدد اللي برا السالفة|تم|عدد اللي برا السالفة: {k}|اكتب اسمك وكود الغرفة|تعذر تحميل مكتبة الاتصال، حدّث الصفحة|تعذر الاتصال بالغرفة|تعال نلعب برا السالفة! كود الغرفة:|اننسخ الرابط",
en:"Everyone knows the secret except one. Find them before they find out.|This game was made by Kitawore|Your name|Create online room|Room code|Join|Play on one phone|Who's playing?|At least 3 players needed|Player|Add player|Continue|Back|Room|Share invite link|Category|Start round|Waiting for the host…|Pass the phone to|I'm|Your turn to see the secret. Keep your screen hidden.|Outside the topic|You don't know the word. Listen to the answers and blend in.|Tap to see your role|Got it, hide|Waiting for the others|Questions|Each player asks the next one a question about the secret without naming it. Everyone answers.|asks|Done, let's vote|Who is outside the topic?|You're caught!|Guess the word to win.|{n} got caught but has one last chance to guess the word…|The outsider wins|The insiders win|Outside the topic:|The word:|guessed:|Not caught, the votes went elsewhere.|votes|New round|End round|Exit|You're outside the topic|Blend in with them|You're inside the topic|Room is full (12 players)|Game in progress, wait for the next round|{n} left, back to the room|Room settings|Language|Number of outsiders|Done|Outsiders: {k}|Enter your name and room code|Couldn't load the connection library, refresh the page|Couldn't connect to the room|Come play Bara Al-Salfa! Room code:|Link copied",
tr:"Herkes sırrı bilir, biri hariç. Seni ele vermeden onu bul.|Bu oyun Kitawore tarafından yapıldı|Adın|Çevrimiçi oda kur|Oda kodu|Katıl|Tek telefonla oyna|Kimler oynuyor?|En az 3 oyuncu gerekli|Oyuncu|Oyuncu ekle|Devam|Geri|Oda|Davet bağlantısını paylaş|Kategori|Turu başlat|Ev sahibi bekleniyor…|Telefonu şuna ver:|Ben|Sırrı görme sırası sende. Ekranını kimseye gösterme.|Konu dışı|Kelimeyi bilmiyorsun. Cevapları dinle ve bilen gibi davran.|Rolünü görmek için dokun|Anladım, gizle|Diğerleri bekleniyor|Sorular|Herkes sıradakine sırrı açıkça söylemeden bir soru sorar. Herkes cevaplar.|soruyor|Bitti, oylayalım|Konu dışı kim?|Yakalandın!|Kelimeyi tahmin et ve kazan.|{n} yakalandı ama kelimeyi tahmin etmek için son bir şansı var…|Konu dışı olan kazandı|Konu içindekiler kazandı|Konu dışı:|Kelime:|tahmin etti:|Yakalanmadı, oylar başkasına gitti.|oy|Yeni tur|Turu bitir|Çıkış|Konu dışısın|Onlar gibi davran|Konunun içindesin|Oda dolu (12 oyuncu)|Oyun devam ediyor, yeni turu bekle|{n} ayrıldı, odaya dönüldü|Oda ayarları|Dil|Konu dışı sayısı|Tamam|Konu dışı: {k}|Adını ve oda kodunu yaz|Bağlantı kütüphanesi yüklenemedi, sayfayı yenile|Odaya bağlanılamadı|Gel Bara Al-Salfa oynayalım! Oda kodu:|Bağlantı kopyalandı",
fr:"Tout le monde connaît le secret sauf un. Trouvez-le avant qu'il ne vous démasque.|Ce jeu a été créé par Kitawore|Ton prénom|Créer une salle en ligne|Code de la salle|Rejoindre|Jouer sur un seul téléphone|Qui joue ?|Il faut au moins 3 joueurs|Joueur|Ajouter un joueur|Continuer|Retour|Salle|Partager le lien d'invitation|Catégorie|Lancer la manche|En attente de l'hôte…|Passe le téléphone à|Je suis|C'est ton tour de voir le secret. Cache ton écran.|Hors sujet|Tu ne connais pas le mot. Écoute les réponses et fais comme si tu savais.|Touche pour voir ton rôle|Compris, masquer|En attente des autres|Questions|Chacun pose au suivant une question sur le secret sans le nommer. Tout le monde répond.|interroge|Terminé, on vote|Qui est hors sujet ?|Tu es démasqué !|Devine le mot pour gagner.|{n} est démasqué mais a une dernière chance de deviner le mot…|Le hors sujet gagne|Les joueurs dans le sujet gagnent|Hors sujet :|Le mot :|a deviné :|Pas démasqué, les votes sont allés ailleurs.|votes|Nouvelle manche|Terminer la manche|Quitter|Tu es hors sujet|Fais comme eux|Tu es dans le sujet|Salle pleine (12 joueurs)|Partie en cours, attends la prochaine manche|{n} est parti, retour à la salle|Paramètres de la salle|Langue|Nombre de hors sujet|OK|Hors sujet : {k}|Entre ton prénom et le code de la salle|Impossible de charger la bibliothèque de connexion, actualise la page|Connexion à la salle impossible|Viens jouer à Bara Al-Salfa ! Code de la salle :|Lien copié",
es:"Todos conocen el secreto menos uno. Descúbrelo antes de que os descubra.|Este juego fue creado por Kitawore|Tu nombre|Crear sala en línea|Código de sala|Unirse|Jugar en un solo móvil|¿Quiénes juegan?|Se necesitan al menos 3 jugadores|Jugador|Añadir jugador|Continuar|Atrás|Sala|Compartir enlace de invitación|Categoría|Empezar ronda|Esperando al anfitrión…|Pasa el móvil a|Soy|Te toca ver el secreto. Que nadie vea tu pantalla.|Fuera del tema|No conoces la palabra. Escucha las respuestas y disimula.|Toca para ver tu rol|Entendido, ocultar|Esperando a los demás|Preguntas|Cada uno hace una pregunta sobre el secreto al siguiente sin nombrarlo. Todos responden.|pregunta a|Listo, a votar|¿Quién está fuera del tema?|¡Te descubrieron!|Adivina la palabra y ganas.|{n} fue descubierto pero tiene una última oportunidad de adivinar la palabra…|Gana el que estaba fuera del tema|Ganan los que estaban dentro del tema|Fuera del tema:|La palabra:|adivinó:|No lo descubrieron, los votos fueron a otro.|votos|Nueva ronda|Terminar ronda|Salir|Estás fuera del tema|Disimula como ellos|Estás dentro del tema|Sala llena (12 jugadores)|Partida en curso, espera la próxima ronda|{n} se fue, volvemos a la sala|Ajustes de la sala|Idioma|Número de jugadores fuera del tema|Listo|Fuera del tema: {k}|Escribe tu nombre y el código de sala|No se pudo cargar la librería de conexión, recarga la página|No se pudo conectar a la sala|¡Ven a jugar Bara Al-Salfa! Código de sala:|Enlace copiado",
de:"Alle kennen das Geheimnis außer einem. Finde ihn, bevor er euch durchschaut.|Dieses Spiel wurde von Kitawore gemacht|Dein Name|Online-Raum erstellen|Raumcode|Beitreten|Auf einem Handy spielen|Wer spielt mit?|Mindestens 3 Spieler nötig|Spieler|Spieler hinzufügen|Weiter|Zurück|Raum|Einladungslink teilen|Kategorie|Runde starten|Warten auf den Gastgeber…|Gib das Handy an|Ich bin|Du bist dran, das Geheimnis zu sehen. Zeig niemandem deinen Bildschirm.|Außerhalb des Themas|Du kennst das Wort nicht. Hör den Antworten zu und tu so, als wüsstest du es.|Tippen, um deine Rolle zu sehen|Verstanden, verbergen|Warten auf die anderen|Fragen|Jeder stellt dem Nächsten eine Frage zum Geheimnis, ohne es zu nennen. Alle antworten.|fragt|Fertig, wir stimmen ab|Wer ist außerhalb des Themas?|Du wurdest erwischt!|Errate das Wort und gewinne.|{n} wurde erwischt, hat aber eine letzte Chance, das Wort zu erraten…|Der Außenstehende gewinnt|Die Eingeweihten gewinnen|Außerhalb des Themas:|Das Wort:|riet:|Nicht erwischt, die Stimmen gingen woandershin.|Stimmen|Neue Runde|Runde beenden|Beenden|Du bist außerhalb des Themas|Tu so wie die anderen|Du bist im Thema|Raum voll (12 Spieler)|Spiel läuft, warte auf die nächste Runde|{n} ist gegangen, zurück im Raum|Raumeinstellungen|Sprache|Anzahl der Außenstehenden|Fertig|Außenstehende: {k}|Gib deinen Namen und den Raumcode ein|Verbindungsbibliothek konnte nicht geladen werden, Seite neu laden|Verbindung zum Raum fehlgeschlagen|Komm spielen: Bara Al-Salfa! Raumcode:|Link kopiert",
ur:"سب کو راز معلوم ہے سوائے ایک کے۔ اسے ڈھونڈیں اس سے پہلے کہ وہ آپ کو پکڑ لے۔|یہ گیم Kitawore نے بنایا ہے|آپ کا نام|آن لائن روم بنائیں|روم کوڈ|شامل ہوں|ایک فون پر کھیلیں|کون کھیل رہا ہے؟|کم از کم 3 کھلاڑی چاہئیں|کھلاڑی|کھلاڑی شامل کریں|جاری رکھیں|واپس|روم|دعوتی لنک شیئر کریں|زمرہ|راؤنڈ شروع کریں|میزبان کا انتظار…|فون دیں اسے:|میں ہوں|آپ کی باری ہے راز دیکھنے کی۔ اپنی اسکرین کسی کو نہ دکھائیں۔|موضوع سے باہر|آپ کو لفظ معلوم نہیں۔ جوابات سنیں اور ایسے ظاہر کریں جیسے آپ کو معلوم ہے۔|اپنا کردار دیکھنے کے لیے ٹیپ کریں|سمجھ گیا، چھپائیں|باقیوں کا انتظار|سوالات|ہر کھلاڑی اگلے سے راز کے بارے میں سوال پوچھتا ہے، بغیر اسے صاف بتائے۔ سب جواب دیتے ہیں۔|پوچھتا ہے|ہو گیا، ووٹ کریں|موضوع سے باہر کون ہے؟|آپ پکڑے گئے!|لفظ کا اندازہ لگائیں اور جیتیں۔|{n} پکڑا گیا مگر لفظ کا اندازہ لگانے کا آخری موقع ہے…|موضوع سے باہر والا جیت گیا|موضوع کے اندر والے جیت گئے|موضوع سے باہر:|لفظ:|اندازہ:|پکڑا نہیں گیا، ووٹ کسی اور کو گئے۔|ووٹ|نیا راؤنڈ|راؤنڈ ختم کریں|باہر نکلیں|آپ موضوع سے باہر ہیں|ان کی طرح ظاہر کریں|آپ موضوع کے اندر ہیں|روم بھر گیا ہے (12 کھلاڑی)|گیم جاری ہے، اگلے راؤنڈ کا انتظار کریں|{n} چلا گیا، روم میں واپس|روم کی ترتیبات|زبان|موضوع سے باہر کھلاڑیوں کی تعداد|ہو گیا|موضوع سے باہر: {k}|اپنا نام اور روم کوڈ لکھیں|کنکشن لائبریری لوڈ نہیں ہوئی، صفحہ ریفریش کریں|روم سے کنکشن نہیں ہو سکا|آئیں برا السالفة کھیلیں! روم کوڈ:|لنک کاپی ہو گیا",
id:"Semua tahu rahasianya kecuali satu orang. Temukan dia sebelum ketahuan.|Game ini dibuat oleh Kitawore|Namamu|Buat ruang online|Kode ruang|Gabung|Main di satu HP|Siapa yang main?|Minimal 3 pemain|Pemain|Tambah pemain|Lanjut|Kembali|Ruang|Bagikan tautan undangan|Kategori|Mulai ronde|Menunggu tuan rumah…|Berikan HP ke|Saya|Giliranmu melihat rahasia. Jangan tunjukkan layarmu.|Di luar topik|Kamu tidak tahu katanya. Dengarkan jawaban lalu pura-pura tahu.|Ketuk untuk melihat perananmu|Mengerti, sembunyikan|Menunggu yang lain|Pertanyaan|Setiap orang bertanya ke orang berikutnya tentang rahasia tanpa menyebutnya. Semua menjawab.|bertanya ke|Selesai, ayo voting|Siapa yang di luar topik?|Kamu ketahuan!|Tebak katanya untuk menang.|{n} ketahuan tapi punya satu kesempatan terakhir menebak katanya…|Yang di luar topik menang|Yang di dalam topik menang|Di luar topik:|Katanya:|menebak:|Tidak ketahuan, suara jatuh ke orang lain.|suara|Ronde baru|Akhiri ronde|Keluar|Kamu di luar topik|Pura-pura seperti mereka|Kamu di dalam topik|Ruang penuh (12 pemain)|Game sedang berjalan, tunggu ronde berikutnya|{n} keluar, kembali ke ruang|Pengaturan ruang|Bahasa|Jumlah yang di luar topik|Selesai|Di luar topik: {k}|Isi namamu dan kode ruang|Pustaka koneksi gagal dimuat, muat ulang halaman|Gagal terhubung ke ruang|Ayo main Bara Al-Salfa! Kode ruang:|Tautan disalin"
};
const T={};for(const l in D){T[l]={};D[l].split('|').forEach((v,i)=>T[l][K[i]]=v);}
const K2='games mafia dBara dMafia mtag min5 r_mafia r_doctor r_detective r_citizen d_mafia d_doctor d_detective d_citizen mates night p_mafia p_doctor p_detective p_cit nightw dead isM notM day died nodie disc whoOut2 vres out2 tie citW mafW mcount adm auto wyr wtag dWyr or res nxt fin thx pts rounds nopts min2'.split(' '),X={ar:"الألعاب|مافيا|الكل يعرف الكلمة إلا واحد|المافيا بين المواطنين|المافيا بينكم. اكتشفوهم قبل لا يقتلونكم.|نحتاج ٥ لاعبين على الأقل|مافيا|طبيب|محقق|مواطن|أنت من المافيا. تقتلون واحد كل ليلة وما تنكشفون.|كل ليلة تنقذ واحد من القتل، وتقدر تنقذ نفسك.|كل ليلة تفحص لاعب وتعرف هو مافيا ولا لا.|ما عندك قدرة. ناقش وصوّت عشان تكشف المافيا.|زملاؤك في المافيا:|الليل|اختر من تقتلون|اختر من تنقذ|اختر من تفحص|الليل… اختر أي لاعب (للتمويه)|ننتظر الليل ينتهي…|طلعت من اللعبة، تابع بصمت|مافيا|مو مافيا|الصباح|{n} مات الليلة|ما مات أحد الليلة|ناقشوا مين المافيا|مين تظنه مافيا؟|نتيجة التصويت|{n} طلع من اللعبة وكان {r}|تعادل، ما طلع أحد|فاز المواطنون|فازت المافيا|عدد المافيا|لوحة الأدمن|عشوائي|لو خيروك|اختر الأخف عليك… وشوف مين يوافقك.|اختيارات صعبة وضحك|أو|النتيجة|التالي|النتيجة النهائية|انتهت اللعبة، نلعب مرة ثانية؟|نقطة|عدد الجولات|بدون نقاط|نحتاج لاعبين اثنين على الأقل",en:"Games|Mafia|Everyone knows the word but one|The mafia among the citizens|The mafia is among you. Find them before they kill you.|At least 5 players needed|Mafia|Doctor|Detective|Citizen|You're mafia. Kill one player each night and don't get caught.|Each night, save one player from being killed. You can save yourself.|Each night, investigate one player to learn if they're mafia.|No special power. Discuss and vote to find the mafia.|Your mafia teammates:|Night|Choose who to kill|Choose who to save|Choose who to investigate|Night… pick anyone (decoy)|Waiting for the night to end…|You're out. Keep watching silently.|Mafia|Not mafia|Morning|{n} died last night|Nobody died last night|Discuss who the mafia is|Who do you think is mafia?|Vote result|{n} was voted out and was {r}|Tie, nobody was voted out|The citizens win|The mafia wins|Number of mafia|Admin panel|Random|Would You Rather|Pick the lesser evil… and see who agrees.|Tough choices and laughs|or|Result|Next|Final results|Game over, play again?|pts|Rounds|No points|At least 2 players needed"};
for(const l in X)X[l].split('|').forEach((v,i)=>T[l][K2[i]]=v);
let ul='ar';try{ul=localStorage.getItem('bs_lang')||'ar';if(!LN[ul])ul='ar';}catch(e){}
const lg=()=>(scr==='game'&&V&&V.S.lang)||ul;
const t=k=>(T[lg()]&&T[lg()][k])||T.en[k]||T.ar[k]||k;
let showSet=false,seq=[],admOn=false,admRole='auto',showAdm=false;try{admOn=sessionStorage.getItem('bs_adm')==='1'}catch(e){}
const MN={bara:3,mafia:5,wyr:2};
const QS='تعيش بدون جوال|تعيش بدون سيارة~تاكل كبسة كل يوم|تاكل شاورما كل يوم~تسافر للماضي|تسافر للمستقبل~تكون غني وما عندك أصحاب|تكون فقير وعندك أصحاب كثير~تعرف كل اللغات|تعزف كل الآلات~تطير|تصير ما تنشاف~تسكن بالصحراء|تسكن جنب البحر~ما تنام أبداً|تنام عشرين ساعة باليوم~تقرأ أفكار الناس|تعرف المستقبل~تاكل بيتزا بس طول عمرك|تاكل برجر بس طول عمرك~تكون أذكى واحد بالعالم|تكون أسعد واحد بالعالم~تسافر كل سنة لبلد جديد|تسكن بمدينة أحلامك~تكون مشهور|تكون غني بس مجهول~تكون دايم جوعان|تكون دايم نعسان~تنسى كل أسماء الناس|تنسى كل الوجوه~تشتغل من البيت|تشتغل من المكتب~تسهر وتصحى متأخر|تنام بدري وتصحى بدري~تحضر فيلم رعب|تحضر فيلم كوميدي~تتكلم مع الحيوانات|تفهم كل لغات البشر~تاكل حلا بس|تاكل مالح بس~صيف طول السنة|شتاء طول السنة~تفقد صوتك أسبوع|تفقد جوالك أسبوع~تعيش على جزيرة وحدك|تعيش بمدينة مزدحمة جداً~تكون أطول بكثير|تكون أقصر بكثير~تقدر توقف الوقت|تقدر ترجع الوقت~تاخذ ألف ريال الحين|تاخذ مليون بعد عشر سنين~تسافر بالطيارة|تسافر بالسيارة~تنام بالخيمة|تنام بالفندق~كل أكلك بارد|كل أكلك حار جداً~تلعب كرة قدم|تتفرج على كرة قدم~تكون لاعب مشهور|تكون مدرب مشهور~يكون عندك كلب|يكون عندك قطة~تركب جمل|تركب حصان~تسوق سيارة سريعة|تركب طيارة خاصة~تعيش بدون موسيقى|تعيش بدون أفلام~تعيش بدون مكيف بالصيف|تعيش بدون دفاية بالشتاء~تتعلم أي شي بسرعة|تتذكر أي شي تقراه~تكون كاتب مشهور|تكون ممثل مشهور~يكون عندك بيت ضخم|يكون عندك قصر بس بعيد~تتغدى مع شخصية مشهورة|تقابل بطلك المفضل~ما تسوي واجبات أبداً|ما تسوي اختبارات أبداً~تدرس بالصباح|تدرس بالمساء~تحضر مباراة بالملعب|تحضر حفلة غنائية~تفتح مطعم|تفتح محل ألعاب~تصير يوتيوبر|تصير مصمم ألعاب~تلعب ماين كرافت|تلعب فورتنايت~تلعب مع أصحابك أونلاين|تلعب وحدك قصة طويلة~تتحكم بالطقس|تتحكم بالحيوانات~تكون تاجر ناجح|تكون طبيب ناجح~تكون مبرمج|تكون مصمم~تتعلم السباحة بسرعة|تتعلم الغوص~تاكل سمك|تاكل لحم~عصير برتقال|عصير مانجو~قهوة عربية|شاي كرك~تشرب ماي بارد بالشتاء|تشرب شاي حار بالصيف~تعيش بدون سكر|تعيش بدون ملح~رحلة بحرية|رحلة برية~تروح مخيم|تقعد بالبيت~جلسة بر مع الأصحاب|جلسة مقهى~تتسوق بالمول|تتسوق أونلاين~تحضر مسلسل كامل بيوم|تحضر فيلم كل يوم~تقرأ كتاب|تسمع بودكاست~تسافر لليابان|تسافر لإيطاليا~تزور باريس|تزور اسطنبول~تعيش بدبي|تعيش بالرياض~تتعلم الطبخ|تتعلم التصوير~تتعلم الرسم|تتعلم العزف~تلبس نفس القميص كل يوم|تلبس ثياب مختلفة بس مو مريحة~تغير لون شعرك|تغير اسمك~يكون صوتك مضحك|تكون مشيتك مضحكة~تضحك بالمواقف الجدية|تسكت بالمواقف المضحكة~تنسى مفاتيحك دايم|تنسى جوالك دايم~تتأخر دايم|تجي بدري دايم~تقول الحقيقة دايم|تكذب كذبة بيضاء وترتاح~تعرف سر أصحابك|يعرفون سرّك~تعيش بدون واي فاي|تعيش بدون بيانات الجوال~شاحن جوالك ينتهي دايم|يتعلق جوالك دايم~تنتظر بالطابور ساعة|تدفع زيادة وتتجاوزه~تركب مصعد دايم|تطلع درج دايم~تسكن بالدور الأول|تسكن بالدور الأخير~تحط منبه واحد|تحط عشر منبهات~تاكل بإيدك|تاكل بالملعقة دايم~تنام على الأرض|تنام على كرسي~تتحمل البرد|تتحمل الحر~تلبس نظارة شمس بالليل|تلبس معطف بالصيف~تخطط لكل شي|تمشي على البديهة~تسافر مع الأصحاب|تسافر مع العائلة~تسوي مفاجأة لغيرك|تنسوي لك مفاجأة~تاخذ هدية غالية|تاخذ هدية من القلب~تحضر حفلة كبيرة|تقعد جلسة صغيرة هادية~تحب الصباح|تحب الليل~تعيش بدون تلفزيون|تعيش بدون سماعات~تلعب شطرنج|تلعب بلوت~تلعب ورق أونو|تلعب دومينو~تحضرها بالملعب|تحضرها بالبيت مرتاح~تكسب الدوري|تكسب كأس العالم~تكون حارس مرمى|تكون مهاجم~تركب دراجة|تمشي مشي~ركض الصبح|ركض بالليل~تعيش بدون كرة قدم|تعيش بدون ألعاب فيديو~تلعب أونلاين دايم|تلعب مع الأصحاب بالبيت~تبني بيت بماين كرافت|تخوض معركة بفورتنايت~تكون أقوى لاعب بالعالم|تكون أذكى مصمم ألعاب~تصنع لعبة مشهورة|تصنع تطبيق مشهور~تشتري سيارة جديدة|تشتري سيارة كلاسيكية~سيارة أوتوماتيك|سيارة يدوي~سيارة كبيرة|سيارة صغيرة~تكسب جائزة كبيرة بالقرعة|تبني ثروتك بنفسك~تعيش بقرية هادية|تعيش بمدينة مليانة حياة~تفتح مزرعة|تفتح مطعم~تفتح مشروعك|تشتغل موظف براتب ثابت~تشتغل أربعة أيام بالأسبوع|تاخذ إجازة ثلاثة أشهر بالسنة~تشتغل بالليل|تشتغل بالنهار~راتب كبير بدوام طويل|راتب متوسط بدوام قصير~تعيش مغامرة بالفضاء|تعيش مغامرة تحت البحر~تصير فنان|تصير عالم~تحضر فيلم بالسينما|تحضر فيلم بالبيت~تتعلم لغة جديدة|تتعلم مهارة جديدة~تعيش بدون مشاكل بس بدون مغامرات|تعيش مغامرات بس معها مشاكل~تاكل بالمطعم|تاكل من البيت~تشتري شي غالي ويدوم|تشتري شي رخيص وتغيره~تعيش بالجبال|تعيش على الشاطئ~تسافر لوحدك|تسافر مع مجموعة كبيرة~تصير مليونير بس تشتغل دايم|تصير موظف بسيط بس وقتك لك'.split('~').map(x=>x.split('|'));
let G='bara',scr='hub',mode=null,host=false,meId=null,peer=null,gconn=null,conns={},S=null,V=null,name='',code='',err='',ln=['','',''],revealed=false,ready=false,lastRound=-1;

/* ---------- game logic (runs on the host / single phone) ---------- */
function pub(id){if(S.game==='mafia')return pubM(id);if(S.game==='wyr'){const s={...S};delete s.pref;return{S:s,card:null};}const s={...S};delete s.pref;if(s.phase!=='result')delete s.word;if(!['result','guess'].includes(s.phase))delete s.outs;
 return{S:s,card:s.phase==='lobby'?null:(S.outs.includes(id)?{out:1}:{word:S.word})};}
function mwin(){const al=S.players.filter(p=>S.alive[p.id]),m=al.filter(p=>S.roles[p.id]==='mafia').length;return!m?'cit':m>=al.length-m?'maf':null;}
function pubM(id){const s={...S};delete s.pref;delete s.act;delete s.invs;if(s.phase!=='result')delete s.roles;const r=S.roles&&S.roles[id],a=S.act;
 return{S:s,card:S.phase==='lobby'?null:{role:r,mates:r==='mafia'?S.players.filter(p=>S.roles[p.id]==='mafia'&&p.id!==id).map(p=>p.id):[],
  done:!!a&&(r==='mafia'?a.m[id]!=null:r==='doctor'?a.d!=null:r==='detective'?a.v!=null:false),inv:(S.invs||[]).filter(x=>x.by===id).pop()}};}
function startM(){const n=S.players.length;S.k=Math.max(1,Math.min(S.k||1,(n-1)>>1));
 const L=[...Array(S.k).fill('mafia'),...(S.doc?['doctor']:[]),...(S.det?['detective']:[])];
 S.roles={};S.alive={};S.invs=[];const pool=[...L,...Array(Math.max(0,n-L.length)).fill('citizen')],P=S.pref||{},ids=shuf(S.players.map(p=>p.id));
 ids.forEach(id=>{const i=pool.indexOf(P[id]);if(P[id]&&i>=0){S.roles[id]=P[id];pool.splice(i,1);}});
 ids.filter(id=>!S.roles[id]).forEach(id=>{S.roles[id]=pool.splice(pool.length*Math.random()|0,1)[0];});ids.forEach(id=>S.alive[id]=1);
 S.phase='card';S.seen={};S.votes={};S.win=null;S.elim=null;S.last=null;S.day=0;S.round++;S.note='';}
function beginNight(){S.phase='night';S.act={m:{},d:null,v:null,p:{}};S.day++;S.last=null;}
function nightDone(){const a=S.act,al=S.players.filter(p=>S.alive[p.id]);
 if(!al.every(p=>{const r=S.roles[p.id];return(r==='mafia'?a.m[p.id]!=null:r==='doctor'?a.d!=null:r==='detective'?a.v!=null:true)&&(!S.local||a.p[p.id]);}))return;
 const c={};Object.values(a.m).forEach(x=>c[x]=(c[x]||0)+1);const mx=Math.max(...Object.values(c)),tg=pick(Object.keys(c).filter(x=>c[x]===mx));
 S.last=tg===a.d?null:tg;if(S.last)S.alive[S.last]=0;
 const w=mwin();if(w){S.win=w;S.phase='result';}else S.phase='day';}
function tallyM(){const c={};Object.values(S.votes).forEach(v=>c[v]=(c[v]||0)+1);const mx=Math.max(...Object.values(c)),tp=Object.keys(c).filter(x=>c[x]===mx);
 S.elim=null;if(tp.length===1){S.elim={id:tp[0],role:S.roles[tp[0]]};S.alive[tp[0]]=0;}
 const w=mwin();if(w){S.win=w;S.phase='result';}else S.phase='vres';}
function startW(){const n=S.rn||10;let pool=QS.map((_,i)=>i).filter(i=>!(S.used||[]).includes(i));if(pool.length<n){pool=QS.map((_,i)=>i);S.used=[];}
 S.qs=shuf(pool).slice(0,n);S.used=[...(S.used||[]),...S.qs];S.qi=0;S.pts={};S.players.forEach(p=>S.pts[p.id]=0);S.votes={};S.cnt=null;S.phase='q';S.round++;S.note='';}
function wTally(){const c=[0,0];Object.values(S.votes).forEach(v=>c[v]++);S.cnt=c;
 if(!S.nopts&&c[0]!==c[1]){const w=c[0]>c[1]?0:1;S.players.forEach(p=>{if(S.votes[p.id]===w)S.pts[p.id]++;});}
 S.phase='qres';}
function start(){S.word=pick(CATS[S.cat]);S.k=Math.max(1,Math.min(S.k||1,S.players.length-2));{const P=S.pref||{},ids=shuf(S.players.map(p=>p.id));S.outs=[...ids.filter(i=>P[i]==='out'),...ids.filter(i=>P[i]!=='out'&&P[i]!=='in'),...ids.filter(i=>P[i]==='in')].slice(0,S.k);}S.order=shuf(S.players.map(p=>p.id));S.phase='card';S.seen={};S.votes={};S.guesses={};S.win=null;S.round++;S.note='';}
function tally(){const c={};Object.values(S.votes).forEach(v=>c[v]=(c[v]||0)+1);
 const r=S.players.map(p=>[p.id,c[p.id]||0]).sort((x,y)=>y[1]-x[1]),k=S.outs.length;
 if(r[k-1][1]>r[k][1]&&r.slice(0,k).every(x=>S.outs.includes(x[0]))){S.opts=shuf([S.word,...shuf(CATS[S.cat].filter(w=>w!==S.word)).slice(0,5)]);S.phase='guess';}
 else{S.win='out';S.phase='result';}}
function handle(m,from){
 if(!S)return;const isH=from===S.hostId;
 switch(m.t){
  case'join':if(S.players.find(p=>p.id===from))break;
   if(S.phase!=='lobby')conns[from]&&conns[from].send({busy:1});
   else if(S.players.length>=12)conns[from]&&conns[from].send({busy:2});
   else{S.players.push({id:from,name:String(m.name||'لاعب').slice(0,14)});if(m.pref&&m.pref!=='auto'){S.pref=S.pref||{};S.pref[from]=String(m.pref).slice(0,12);}}break;
  case'cat':if(isH&&S.phase==='lobby'&&CATS[m.cat])S.cat=m.cat;break;
  case'lang':if(isH&&S.phase==='lobby'&&LN[m.l])S.lang=m.l;break;
  case'outs':if(isH&&S.phase==='lobby')S.k=Math.max(1,Math.min(+m.k||1,S.game==='mafia'?(S.players.length-1)>>1:S.players.length-2));break;
  case'start':if(isH&&S.phase==='lobby'&&S.players.length>=MN[S.game])S.game==='mafia'?startM():S.game==='wyr'?startW():start();break;
  case'seen':if(S.phase==='card'){S.seen[from]=1;if(S.players.every(p=>S.seen[p.id])){S.game==='mafia'?beginNight():(S.phase='ask');}}break;
  case'ask2vote':if(isH&&S.phase==='ask'){S.phase='vote';S.votes={};}break;
  case'vote':if(S.phase==='vote'&&S.votes[from]==null&&m.to!==from&&S.players.find(p=>p.id===m.to)){S.votes[from]=m.to;if(S.players.every(p=>S.votes[p.id]!=null))tally();}break;
  case'guess':if(S.phase==='guess'&&S.outs.includes(from)&&S.guesses[from]==null){S.guesses[from]=m.w;if(S.outs.every(o=>S.guesses[o]!=null)){S.win=Object.values(S.guesses).includes(S.word)?'out':'in';S.phase='result';}}break;
  case'again':if(isH)S.phase='lobby';break;
  case'pref':if(S.phase==='lobby'){S.pref=S.pref||{};if(m.r==='auto')delete S.pref[from];else S.pref[from]=String(m.r).slice(0,12);}break;
  case'rn':if(isH&&S.phase==='lobby'&&[5,10,15,20].includes(+m.n))S.rn=+m.n;break;
  case'wvote':if(S.phase==='q'&&S.votes[from]==null&&(m.c===0||m.c===1)){S.votes[from]=m.c;if(S.players.every(p=>S.votes[p.id]!=null))wTally();}break;
  case'wnext':if(isH&&S.phase==='qres'){S.qi++;if(S.qi>=S.qs.length)S.phase='result';else{S.votes={};S.phase='q';}}break;
  case'opt':if(isH&&S.phase==='lobby'&&(m.o==='doc'||m.o==='det'||m.o==='nopts'))S[m.o]=S[m.o]?0:1;break;
  case'nact':if(S.phase==='night'&&S.alive[from]&&S.alive[m.to]){const r=S.roles[from],a=S.act;
   if(r==='mafia'&&m.k==='m'&&a.m[from]==null&&S.roles[m.to]!=='mafia')a.m[from]=m.to;
   else if(r==='doctor'&&m.k==='d'&&a.d==null)a.d=m.to;
   else if(r==='detective'&&m.k==='v'&&a.v==null&&m.to!==from){a.v=m.to;S.invs.push({by:from,to:m.to,m:S.roles[m.to]==='mafia',day:S.day});}
   if(r!=='detective'||!S.local)a.p[from]=1;nightDone();}break;
  case'ndone':if(S.phase==='night'&&S.roles[from]==='detective'&&S.act.v!=null){S.act.p[from]=1;nightDone();}break;
  case'day2vote':if(isH&&S.phase==='day'){S.phase='vote';S.votes={};}break;
  case'mvote':if(S.phase==='vote'&&S.alive[from]&&S.votes[from]==null&&S.alive[m.to]&&m.to!==from){S.votes[from]=m.to;if(S.players.filter(p=>S.alive[p.id]).every(p=>S.votes[p.id]!=null))tallyM();}break;
  case'next':if(isH&&S.phase==='vres')beginNight();break;
 }
 sync();
}
function sync(){
 if(mode==='online')S.players.forEach(p=>{const c=conns[p.id];if(p.id!==S.hostId&&c&&c.open)c.send(pub(p.id));});
 render();
}
function send(m){if(mode==='online'&&!host)gconn.send(m);else handle(m,meId);}
function lview(){
 const un=(f)=>(S.players.find(f)||{}).id;
 if(S.phase==='card')return un(p=>!S.seen[p.id]);
 if(S.game==='wyr')return S.phase==='q'?un(p=>S.votes[p.id]==null):S.hostId;
 if(S.game==='mafia'){
  if(S.phase==='night')return un(p=>S.alive[p.id]&&!S.act.p[p.id]);
  if(S.phase==='vote')return un(p=>S.alive[p.id]&&S.votes[p.id]==null);
  return S.hostId;}
 if(S.phase==='vote')return un(p=>S.votes[p.id]==null);
 if(S.phase==='guess')return S.outs.find(o=>S.guesses[o]==null);
 return S.hostId;}

/* ---------- online (PeerJS, no server needed) ---------- */
const TURN=[];/* لو احتجت سيرفر TURN خاص: {urls:'turn:host:443',username:'..',credential:'..'} */
const PC=TURN.length?{config:{iceServers:[{urls:'stun:stun.l.google.com:19302'},...TURN]}}:{};
const noLib=()=>{if(typeof Peer!=='undefined')return false;err=t('eLib');render();return true;};
const gen=()=>Array.from({length:5},()=>pick([...'ABCDEFGHJKLMNPQRSTUVWXYZ23456789'])).join('');
function reset(){if(host)code='';try{peer&&peer.destroy()}catch(e){}peer=null;gconn=null;conns={};S=null;V=null;mode=null;host=false;scr='home';render();}
function create(){
 if(peer||noLib())return;name=$('#nm').value.trim()||'المضيف';code=gen();mode='online';host=true;
 peer=new Peer('bara-salfa-'+code,PC);
 peer.on('open',()=>{meId='host';S={hostId:'host',players:[{id:'host',name}],cat:'أكلات',phase:'lobby',round:0,lang:ul,k:1,game:G,doc:1,det:1,rn:10,nopts:0,pref:admOn&&admRole!=='auto'?{host:admRole}:{}};scr='game';render();});
 peer.on('connection',c=>{conns[c.peer]=c;
  c.on('data',m=>handle(m,c.peer));
  c.on('close',()=>{const q=S&&S.players.find(p=>p.id===c.peer);if(!q)return;
   S.players=S.players.filter(p=>p.id!==c.peer);delete conns[c.peer];
   if(S.phase!=='lobby'){S.phase='lobby';S.note=q.name;}sync();});});
 peer.on('disconnected',()=>{try{peer.reconnect()}catch(e){}});
 peer.on('error',e=>{err=t('eConn')+' ('+e.type+')';reset();});
}
function join(){
 if(peer||noLib())return;name=$('#nm').value.trim();code=$('#cd').value.replace(/\s/g,'').toUpperCase();
 if(!name||code.length<4){err=t('eName');render();return;}
 mode='online';host=false;peer=new Peer(undefined,PC);
 const fail=m=>{if(!V){err=m;reset();}};
 peer.on('open',id=>{meId=id;gconn=peer.connect('bara-salfa-'+code,{reliable:true});
  gconn.on('open',()=>gconn.send({t:'join',name,pref:admOn?admRole:'auto'}));
  gconn.on('data',d=>{if(d.busy){err=d.busy===2?t('full'):t('busy');reset();return;}V=d;scr='game';render();});
  gconn.on('close',()=>{err=t('eConn');reset();});
  setTimeout(()=>fail(t('eConn')+' (timeout)'),15000);});
 peer.on('error',e=>fail(t('eConn')+' ('+e.type+')'));
}

/* ---------- screens ---------- */
const wait=x=>`<div class=mid><p class=m>${x}</p></div>`;
const langChips=cur=>Object.keys(LN).map(c=>`<button class="chip ${c===cur?'on':''}" data-a=lang data-v=${c}>${LN[c]}</button>`).join('');
const hubH=()=>`<div><h1 style="font-size:54px">${t('games')}</h1><p class=made>${t('made')}</p></div>
<button class=gc style="background:var(--hot)" data-a=pick data-v=bara><span class=gt>برا السالفة</span><small>${t('dBara')}</small></button>
<button class=gc style="background:#6B4DF0" data-a=pick data-v=mafia><span class=gt>${t('mafia')}</span><small>${t('dMafia')}</small></button>
<button class=gc style="background:#0FA58F" data-a=pick data-v=wyr><span class=gt>${t('wyr')}</span><small>${t('dWyr')}</small></button>`;
const homeH=()=>`<div><h1>${G==='mafia'?t('mafia'):G==='wyr'?t('wyr'):'برا السالفة'}</h1><p class=m>${G==='mafia'?t('mtag'):G==='wyr'?t('wtag'):t('tag')}</p><p class=made>${t('made')}</p></div>
${err?`<p style="color:var(--hot)">${err}</p>`:''}
<input class=i id=nm placeholder="${t('nm')}" maxlength=14 value="${esc(name)}">
<button class=b data-a=create>${t('cr')}</button>
<div style="display:flex;gap:8px"><input class=i id=cd placeholder="${t('cd')}" maxlength=5 value="${esc(code||location.hash.slice(1).toUpperCase().slice(0,5))}" style="direction:ltr;text-transform:uppercase"><button class="b alt" style="width:auto" data-a=join>${t('jn')}</button></div>
<button class="b alt" data-a=local>${t('lc')}</button><button class="b alt" data-a=tohub>${t('back')}</button>`;
const localH=()=>`<h2>${t('who')}</h2><p class=m>${t('min'+MN[G])}</p>${err?`<p style="color:var(--hot)">${err}</p>`:''}
${ln.map((n,i)=>`<input class=i data-i=${i} placeholder="${t('pl')} ${i+1}" maxlength=14 value="${esc(n)}">`).join('')}
<button class="b alt" data-a=addp ${ln.length>=12?'disabled':''}>${t('addp')}</button>
<button class=b data-a=startlocal>${t('cont')}</button><button class="b alt" data-a=back>${t('back')}</button>`;

function mafH(s,card,me,n,loc,isH,nm,gate){
 const ph=s.phase,al=id=>s.alive&&s.alive[id],RN=r=>t('r_'+r),alv=s.players.filter(p=>al(p.id));
 const pk=(a,ids)=>ids.map(id=>`<button class="b alt" data-a=${a} data-v="${esc(id)}">${nm(id)}</button>`).join('');
 const wr=`<p class=m>${t('waitH')}</p>`;
 if(ph==='card'){
  if(s.seen[me])return wait(`${t('wait')} (${Object.keys(s.seen).length}/${n})`);
  if(loc&&!ready)return gate(t('pass'));
  const r=card.role;
  return`<p class=m>${t('turn')}</p><div class="role ${revealed?(r==='mafia'?'out':'in'):''}" data-a=reveal>${revealed
   ?`<div><div class=big>${RN(r)}</div><p>${t('d_'+r)}</p>${card.mates.length?`<p><b>${t('mates')}</b> ${card.mates.map(nm).join(', ')}</p>`:''}</div>`
   :`<div><div class=big>؟</div><p class=m>${t('tap')}</p></div>`}</div>${revealed?`<button class=b data-a=seen>${t('ok')}</button>`:''}`;}
 if(ph==='night'){
  if(!al(me))return wait(t('dead'));
  if(loc&&!ready)return gate(t('pass'));
  const r=card.role,iv=card.inv&&card.inv.day===s.day?card.inv:null;let body;
  if(card.done)body=iv?`<p>${nm(iv.to)}: <b>${iv.m?t('isM'):t('notM')}</b></p>${loc?`<button class=b data-a=ndone>${t('ok')}</button>`:`<p class=m>${t('nightw')}</p>`}`:`<p class=m>${t('nightw')}</p>`;
  else if(r==='citizen'&&!loc)body=`<p class=m>${t('nightw')}</p>`;
  else{const tg=alv.filter(p=>r==='mafia'?p.id!==me&&!card.mates.includes(p.id):r==='detective'?p.id!==me:true).map(p=>p.id);
   body=`<p class=m>${t(r==='mafia'?'p_mafia':r==='doctor'?'p_doctor':r==='detective'?'p_detective':'p_cit')}</p>${pk('nact',tg)}`;}
  return`<h2>🌙 ${t('night')}</h2>${body}`;}
 if(ph==='day')return`<h2>☀️ ${t('day')}</h2><p>${s.last?t('died').replace('{n}',nm(s.last)):t('nodie')}</p>${!loc&&card.inv&&card.inv.day===s.day?`<p class=m>${nm(card.inv.to)}: ${card.inv.m?t('isM'):t('notM')}</p>`:''}<p class=m>${t('disc')}</p>
  <div class=row>${s.players.map(p=>`<span class=chip style="${al(p.id)?'':'opacity:.4;text-decoration:line-through'}">${esc(p.name)}</span>`).join('')}</div>
  ${isH?`<button class=b data-a=day2vote>${t('tovote')}</button>`:wr}`;
 if(ph==='vote'){
  if(!al(me))return wait(t('dead'));
  if(s.votes[me]!=null)return wait(`${t('wait')} (${Object.keys(s.votes).length}/${alv.length})`);
  if(loc&&!ready)return gate(t('pass'));
  return`<h2>${t('whoOut2')}</h2>${pk('mvote',alv.filter(p=>p.id!==me).map(p=>p.id))}`;}
 if(ph==='vres')return`<h2>${t('vres')}</h2><p>${s.elim?t('out2').replace('{n}',nm(s.elim.id)).replace('{r}',RN(s.elim.role)):t('tie')}</p>${isH?`<button class=b data-a=next>${t('night')}</button>`:wr}`;
 const cw=s.win==='cit';
 return`<h2 style="color:${cw?'var(--mint)':'var(--hot)'}">${cw?t('citW'):t('mafW')}</h2>
 <div style="display:grid;gap:6px">${s.players.map(p=>`<div class=pl><span>${esc(p.name)}</span><span class=m>${RN(s.roles[p.id])}</span></div>`).join('')}</div>
 ${isH?`<button class=b data-a=again>${t('again')}</button>`:wr}`;
}

function wyrH(s,me,n,loc,isH,nm,gate){
 const wr=`<p class=m>${t('waitH')}</p>`,tot=s.qs.length;
 if(s.phase==='q'){
  if(s.votes[me]!=null)return wait(`${t('wait')} (${Object.keys(s.votes).length}/${n})`);
  if(loc&&!ready)return gate(t('pass'));
  const q=QS[s.qs[s.qi]];
  return`<p class=m>${s.qi+1}/${tot}</p><h2>${t('wyr')}</h2><button class=b data-a=wvote data-v=0>${q[0]}</button><p class=m style="text-align:center">${t('or')}</p><button class="b pk" data-a=wvote data-v=1>${q[1]}</button>`;}
 if(s.phase==='qres'){
  const q=QS[s.qs[s.qi]],c=s.cnt,tt=Math.max(1,c[0]+c[1]);
  const bar=(i,col)=>`<div class=pl style="display:block"><div style="display:flex;justify-content:space-between"><span>${q[i]}</span><b>${c[i]}</b></div><div style="height:8px;border-radius:99px;background:var(--line);margin-top:6px"><div style="height:8px;border-radius:99px;width:${Math.round(c[i]/tt*100)}%;background:${col}"></div></div></div>`;
  return`<p class=m>${s.qi+1}/${tot}</p><h2>${t('res')}</h2>${bar(0,'var(--mint)')}${bar(1,'var(--hot)')}<p class=m>${s.players.map(p=>nm(p.id)+': '+(s.votes[p.id]===0?'A':'B')).join(' · ')}</p>${isH?`<button class=b data-a=wnext>${s.qi+1>=tot?t('fin'):t('nxt')}</button>`:wr}`;}
 const r=[...s.players].sort((a,b)=>s.pts[b.id]-s.pts[a.id]);
 return`<h2>${t('fin')}</h2>${s.nopts?`<p class=m>${t('thx')}</p>`:r.map((p,i)=>`<div class=pl><span>${i===0?'🏆 ':''}${esc(p.name)}</span><span class=m>${s.pts[p.id]} ${t('pts')}</span></div>`).join('')}${isH?`<button class=b data-a=again>${t('again')}</button>`:wr}`;
}

function gameH(){
 const{S:s,card}=V,me=meId,n=s.players.length,loc=mode==='local',isH=me===s.hostId,mn=MN[s.game]||3;
 const nm=id=>esc((s.players.find(p=>p.id===id)||{}).name||'؟');
 if(s.round!==lastRound){revealed=false;ready=false;lastRound=s.round;}
 const gate=l=>`<div class=mid><p class=m>${l}</p><h2>${nm(me)}</h2><button class=b data-a=ready>${t('iam')} ${nm(me)}</button></div>`;
 const kH=s.k>1?`<p class=m>${t('outsN').replace('{k}',s.k)}</p>`:'';
 if(s.phase==='lobby')return`<h2>${t('room')}</h2>${s.note?`<p style="color:var(--hot)">${t('left').replace('{n}',esc(s.note))}</p>`:''}${loc?'':`<div class=code>${esc(code)}</div><button class="b alt" data-a=share>${t('inv')}</button>`}
 <div class=row>${s.players.map(p=>`<span class=chip>${esc(p.name)}</span>`).join('')}</div>
 ${s.game!=='bara'?'':`<p class=m>${t('cat')}</p><div class=row>${Object.keys(CATS).map(c=>`<button class="chip ${c===s.cat?'on':''}" ${isH?`data-a=cat data-v="${c}"`:'disabled'}>${c}</button>`).join('')}</div>`}
 ${isH?`<button class=b data-a=start ${n<mn?'disabled':''}>${n<mn?t('min'+mn):t('go')}</button>`:`<p class=m>${t('waitH')}</p>`}`;
 if(s.game==='wyr')return wyrH(s,me,n,loc,isH,nm,gate);
 if(s.game==='mafia')return mafH(s,card,me,n,loc,isH,nm,gate);
 if(s.phase==='card'){
  if(s.seen[me])return wait(`${t('wait')} (${Object.keys(s.seen).length}/${n})`);
  if(loc&&!ready)return gate(t('pass'));
  return`<p class=m>${t('turn')}</p>
  <div class="role ${revealed?(card.out?'out':'in'):''}" data-a=reveal>${revealed
   ?(card.out?`<div><div class=big>${t('outT')}</div><p>${t('outH')}</p></div>`
              :`<div><p>${s.cat}</p><div class=big>${esc(card.word)}</div></div>`)
   :`<div><div class=big>؟</div><p class=m>${t('tap')}</p></div>`}</div>
  ${revealed?`<button class=b data-a=seen>${t('ok')}</button>`:''}`;}
 if(s.phase==='ask')return`<h2>${t('asks')}</h2>${kH}<p class=m>${t('askH')}</p>
  <ol style="padding-inline-start:22px;display:grid;gap:8px">${s.order.map((id,i)=>`<li>${nm(id)} ${t('asksX')} ${nm(s.order[(i+1)%n])}</li>`).join('')}</ol>
  ${isH?`<button class=b data-a=ask2vote>${t('tovote')}</button>`:`<p class=m>${t('waitH')}</p>`}`;
 if(s.phase==='vote'){
  if(s.votes[me]!=null)return wait(`${t('wait')} (${Object.keys(s.votes).length}/${n})`);
  if(loc&&!ready)return gate(t('pass'));
  return`<h2>${t('whoOut')}</h2>${kH}${s.players.filter(p=>p.id!==me).map(p=>`<button class="b alt" data-a=vote data-v="${esc(p.id)}">${esc(p.name)}</button>`).join('')}`;}
 if(s.phase==='guess'){
  if(!s.outs.includes(me))return wait(t('wg').replace('{n}',s.outs.map(nm).join(', ')));
  if(s.guesses[me]!=null)return wait(t('wait'));
  if(loc&&!ready)return gate(t('pass'));
  return`<h2>${t('caught')}</h2><p class=m>${t('guessH')}</p>${s.opts.map(w=>`<button class="b alt" data-a=guess data-v="${esc(w)}">${esc(w)}</button>`).join('')}`;}
 const cnt={};Object.values(s.votes).forEach(v=>cnt[v]=(cnt[v]||0)+1);const w=s.win==='out',gs=Object.entries(s.guesses||{});
 return`<h2 style="color:${w?'var(--hot)':'var(--mint)'}">${w?t('ow'):t('iw')}</h2>
 <p>${t('theOut')} <b>${s.outs.map(nm).join(', ')}</b><br>${t('theW')} <b>${esc(s.word)}</b>${gs.length?gs.map(([i,x])=>`<br>${nm(i)} ${t('gs')} ${esc(x)}`).join(''):(w?`<br>${t('nc')}`:'')}</p>
 <div style="display:grid;gap:6px">${s.players.map(p=>`<div class=pl><span>${esc(p.name)}${s.outs.includes(p.id)?' ('+t('outT')+')':''}</span><span class=m>${cnt[p.id]||0} ${t('vts')}</span></div>`).join('')}</div>
 ${isH?`<button class=b data-a=again>${t('again')}</button>`:`<p class=m>${t('waitH')}</p>`}`;
}

function adG(){return admOn?`<button class="gear adm" data-a=adm aria-label="admin">⚙️</button>`:'';}
function adM(){if(!admOn||!showAdm)return'';
 const gm=scr==='game'&&V?V.S.game:G,op=gm==='mafia'?['mafia','doctor','detective','citizen']:gm==='wyr'?[]:['out','in'];
 const lab=o=>o==='auto'?t('auto'):o==='out'?t('outT'):o==='in'?t('yIn'):t('r_'+o);
 return`<div class=modal data-a=adm><div class=sheet data-a=none><h2>${t('adm')}</h2><div class=row>${['auto',...op].map(o=>`<button class="chip ${admRole===o?'on':''}" data-a=apref data-v=${o}>${lab(o)}</button>`).join('')}</div><button class=b data-a=adm>${t('done')}</button></div></div>`;}
function render(){
 if(scr==='game'){
  if(mode==='local'){meId=lview();V=pub(meId);}else if(host)V=pub(meId);
  if(!V)return;
 }
 const L=lg();document.documentElement.lang=L;document.documentElement.dir=RTL.includes(L)?'rtl':'ltr';
 let h='',gear=false,modal='';
 if(scr==='home'||scr==='hub'){h=scr==='hub'?hubH():homeH();gear=true;modal=`<h2>${t('lang')}</h2><div class=row>${langChips(ul)}</div>`;}
 else if(scr==='local')h=localH();
 else{
  const s0=V.S,c0=V.card,isH0=s0.hostId===meId;
  const bar=s0.game==='mafia'?(mode==='online'&&c0&&!['lobby','result'].includes(s0.phase)&&!(s0.phase==='card'&&!s0.seen[meId])?`<div class="bar ${c0.role==='mafia'?'out':'in'}"><b>${t('r_'+c0.role)}</b></div>`:''):mode==='online'&&c0&&(['ask','vote','guess'].includes(s0.phase)||(s0.phase==='card'&&s0.seen[meId]))
   ?(c0.out?`<div class="bar out"><b>${t('yOut')}</b><small>${t('act')}</small></div>`
           :`<div class="bar in"><b>${t('yIn')}</b><small>${t('theW')} ${esc(c0.word)}</small></div>`):'';
  const endB=mode==='online'&&host&&!['lobby','result'].includes(s0.phase)?`<button class="b alt" data-a=again>${t('endR')}</button>`:'';
  h=bar+gameH()+`<div style="margin-top:auto;display:grid;gap:8px">${endB}<button class="b alt" style="font-size:14px;padding:8px" onclick="location.reload()">${t('exit')}</button></div>`;
  if(s0.phase==='lobby'&&isH0){gear=true;const mf=s0.game==='mafia',mx=mf?Math.max(1,(s0.players.length-1)>>1):Math.max(1,s0.players.length-2),kk=Math.min(s0.k||1,mx);
   const tg=(o,r)=>`<button class="chip ${s0[o]?'on':''}" data-a=opt data-v=${o}>${t(r)}</button>`;
   modal=`<h2>${t('set')}</h2><p class=m>${t(mf?'mcount':'outc')}</p><div class=row>${Array.from({length:mx},(_,i)=>`<button class="chip ${kk===i+1?'on':''}" data-a=outc data-v=${i+1}>${i+1}</button>`).join('')}</div>${mf?`<div class=row>${tg('doc','r_doctor')}${tg('det','r_detective')}</div>`:''}<p class=m>${t('lang')}</p><div class=row>${langChips(s0.lang)}</div>`;
   if(s0.game==='wyr')modal=`<h2>${t('set')}</h2><p class=m>${t('rounds')}</p><div class=row>${[5,10,15,20].map(x=>`<button class="chip ${(s0.rn||10)===x?'on':''}" data-a=rn data-v=${x}>${x}</button>`).join('')}</div><div class=row><button class="chip ${s0.nopts?'on':''}" data-a=opt data-v=nopts>${t('nopts')}</button></div><p class=m>${t('lang')}</p><div class=row>${langChips(s0.lang)}</div>`;}
  wake();
 }
 app.innerHTML=adG()+(gear?`<button class=gear data-a=gear aria-label="${t('lang')}">⚙️</button>`:'')+h+(gear&&showSet?`<div class=modal data-a=gear><div class=sheet data-a=none>${modal}<button class=b data-a=gear>${t('done')}</button></div></div>`:'')+adM();
 err='';
}

/* ---------- events ---------- */
const A={
 create,join,
 local(){name=$('#nm').value;scr='local';render();},
 back(){scr='home';render();},
 addp(){ln.push('');render();},
 startlocal(){
  const names=ln.map(x=>x.trim()).filter(Boolean);
  if(names.length<MN[G]){err=t('min'+MN[G]);render();return;}
  mode='local';S={hostId:'p0',players:names.map((x,i)=>({id:'p'+i,name:x})),cat:'أكلات',phase:'lobby',round:0,lang:ul,k:1,game:G,local:1,doc:1,det:1,rn:10,nopts:0,pref:admOn&&admRole!=='auto'?{p0:admRole}:{}};scr='game';render();},
 cat:v=>send({t:'cat',cat:v}),
 start(){showSet=false;send({t:'start'});},
 gear(){showSet=!showSet;render();},
 lang(v){if(scr==='home'||scr==='hub'){ul=v;try{localStorage.setItem('bs_lang',v)}catch(e){}
  seq.push(v);seq=seq.slice(-7);if(seq.join()==='fr,es,tr,en,ar,en,ar'){admOn=true;try{sessionStorage.setItem('bs_adm','1')}catch(e){}}
  render();}else send({t:'lang',l:v});},
 outc(v){send({t:'outs',k:+v});},
 opt:v=>send({t:'opt',o:v}),
 rn:v=>send({t:'rn',n:+v}),
 wvote(v){ready=false;send({t:'wvote',c:+v});},
 wnext:()=>send({t:'wnext'}),
 adm(){showAdm=!showAdm;render();},
 apref(v){admRole=v;if(scr==='game'&&V&&V.S.phase==='lobby')send({t:'pref',r:v});render();},
 pick(v){G=v;scr='home';render();},
 tohub(){scr='hub';render();},
 mvote(v){ready=false;send({t:'mvote',to:v});},
 nact(v){const r=V.card.role;if(!(mode==='local'&&r==='detective'))ready=false;send({t:'nact',k:({mafia:'m',doctor:'d',detective:'v'})[r]||'x',to:v});},
 ndone(){ready=false;send({t:'ndone'});},
 day2vote:()=>send({t:'day2vote'}),
 next:()=>send({t:'next'}),
 reveal(){revealed=true;render();},
 ready(){ready=true;render();},
 seen(){revealed=false;ready=false;send({t:'seen'});},
 ask2vote:()=>send({t:'ask2vote'}),
 vote(v){ready=false;send({t:'vote',to:v});},
 guess(v){ready=false;send({t:'guess',w:v});},
 again:()=>send({t:'again'}),
 async share(){const url=location.href.split('#')[0]+'#'+code,tx=t('share')+' '+code;
  try{if(navigator.share)await navigator.share({text:tx,url});else{await navigator.clipboard.writeText(tx+'\n'+url);alert(t('copied'));}}catch(e){}}
};
app.onclick=e=>{const b=e.target.closest('[data-a]');if(b&&!b.disabled&&A[b.dataset.a])A[b.dataset.a](b.dataset.v);};
app.oninput=e=>{if(e.target.dataset.i!=null)ln[e.target.dataset.i]=e.target.value;};
let wl=null;
async function wake(){try{if(navigator.wakeLock&&!document.hidden&&(!wl||wl.released))wl=await navigator.wakeLock.request('screen');}catch(e){}}
document.addEventListener('visibilitychange',()=>{if(document.hidden)return;
 if(host&&peer&&peer.disconnected&&!peer.destroyed){try{peer.reconnect()}catch(e){}}
 if(scr==='game')wake();});
render();
</script>
</body>
</html>
