# livraison settat 

<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="theme-color" content="#111111">
  <meta name="description" content="LIVRAISON SETTAT - خدمة التوصيل داخل مدينة سطات وخارجها">
  <title>LIVRAISON SETTAT | خدمة التوصيل</title>

  <style>
    * { box-sizing: border-box; }
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #111;
      color: white;
      line-height: 1.7;
    }
    header {
      background: #080808;
      text-align: center;
      padding: 24px 15px;
      border-bottom: 3px solid #ffd400;
    }
    .logo {
      color: #ffd400;
      font-size: 30px;
      font-weight: bold;
      letter-spacing: 1px;
    }
    header p { margin: 5px 0; color: #ddd; }
    .hero {
      text-align: center;
      padding: 35px 15px;
      background: linear-gradient(145deg, #242424, #111);
    }
    h1 { font-size: 27px; margin: 5px 0; }
    .yellow { color: #ffd400; }
    .hero p { color: #ddd; }
    .btn {
      display: inline-block;
      background: #ffd400;
      color: #111;
      padding: 12px 22px;
      border-radius: 8px;
      text-decoration: none;
      font-weight: bold;
      border: none;
      cursor: pointer;
      font-size: 16px;
    }
    .section {
      max-width: 650px;
      margin: 20px auto;
      padding: 20px;
    }
    .card {
      background: #202020;
      padding: 18px;
      margin: 12px 0;
      border-radius: 12px;
      border: 1px solid #383838;
    }
    h2 { color: #ffd400; text-align: center; }
    .prices {
      display: flex;
      justify-content: space-around;
      gap: 10px;
      text-align: center;
      flex-wrap: wrap;
    }
    .price {
      background: #292929;
      padding: 15px;
      border-radius: 10px;
      flex: 1;
      min-width: 130px;
    }
    .price strong {
      display: block;
      color: #ffd400;
      font-size: 25px;
    }
    label { display: block; margin: 12px 0 5px; }
    input, select, textarea {
      width: 100%;
      padding: 13px;
      border: 1px solid #555;
      border-radius: 7px;
      background: #303030;
      color: white;
      font-size: 16px;
    }
    textarea { min-height: 85px; resize: vertical; }
    form button { width: 100%; margin-top: 18px; }
    footer {
      text-align: center;
      padding: 25px 10px;
      color: #bbb;
      background: #080808;
      margin-top: 30px;
    }
    .whatsapp {
      position: fixed;
      bottom: 18px;
      left: 15px;
      background: #20c767;
      color: white;
      text-decoration: none;
      padding: 12px 16px;
      border-radius: 30px;
      font-weight: bold;
      z-index: 10;
    }
  </style>
</head>

<body>

<header>
  <div class="logo">LIVRAISON SETTAT</div>
  <p>خدمة التوصيل السريعة داخل مدينة سطات</p>
</header>

<section class="hero">
  <h1>مرحبا بكم في <span class="yellow">LIVRAISON SETTAT</span></h1>
  <p>نوصّلو ليك الطلبات ديالك حتى لباب الدار 🚴</p>
  <p>المطاعم • المشتريات • الطرود • الوثائق</p>
  <a href="#commande" class="btn">اطلب التوصيل الآن</a>
</section>

<section class="section">
  <h2>أثمنة التوصيل</h2>
  <div class="prices">
    <div class="price">
      داخل مدينة سطات
      <strong>15 DH</strong>
    </div>
    <div class="price">
      المناطق البعيدة
      <strong>20 DH</strong>
    </div>
  </div>
  <p style="text-align:center;color:#bbb">
    الثمن النهائي كيتأكد معاك قبل إرسال السائق.
  </p>
</section>

<section class="section">
  <h2>خدماتنا</h2>
  <div class="card">🍔 توصيل طلبات المطاعم والمأكولات</div>
  <div class="card">🛒 شراء وتوصيل المشتريات</div>
  <div class="card">📦 توصيل الطرود والوثائق</div>
  <div class="card">🏪 توصيل طلبات المحلات التجارية</div>
</section>

<section class="section card" id="commande">
  <h2>اطلب خدمة التوصيل</h2>

  <form id="orderForm">
    <label>الاسم الكامل</label>
    <input id="name" type="text" placeholder="أدخل اسمك" required>

    <label>رقم الهاتف</label>
    <input id="phone" type="tel" placeholder="رقم هاتفك" required>

    <label>نوع الخدمة</label>
    <select id="service" required>
      <option value="">اختر الخدمة</option>
      <option>طلب من مطعم</option>
      <option>مشتريات</option>
      <option>طرد أو وثائق</option>
      <option>توصيل من محل تجاري</option>
      <option>خدمة أخرى</option>
    </select>

    <label>مكان أخذ الطلب</label>
    <input id="pickup" type="text" placeholder="الحي أو العنوان" required>

    <label>مكان التوصيل</label>
    <input id="dropoff" type="text" placeholder="الحي أو العنوان" required>

    <label>ملاحظات إضافية</label>
    <textarea id="details" placeholder="اكتب تفاصيل الطلب إن وجدت"></textarea>

    <button class="btn" type="submit">إرسال الطلب عبر واتساب</button>
  </form>
</section>

<section class="section" style="text-align:center">
  <h2>تواصل معنا</h2>
  <p>للطلب أو الاستفسار اتصل بنا عبر واتساب</p>
  <a class="btn" href="https://wa.me/212603681664">تواصل عبر واتساب</a>
</section>

<footer>
  <div class="yellow"><strong>LIVRAISON SETTAT</strong></div>
  <p>خدمتكم راحتنا ❤️</p>
  <p>© 2026 جميع الحقوق محفوظة</p>
</footer>

<a class="whatsapp" href="https://wa.me/212603681664">واتساب</a>

<script>
  document.getElementById("orderForm").addEventListener("submit", function(e) {
    e.preventDefault();

    const name = document.getElementById("name").value.trim();
    const phone = document.getElementById("phone").value.trim();
    const service = document.getElementById("service").value;
    const pickup = document.getElementById("pickup").value.trim();
    const dropoff = document.getElementById("dropoff").value.trim();
    const details = document.getElementById("details").value.trim();

    const message =
      "طلب توصيل جديد - LIVRAISON SETTAT%0A" +
      "الاسم: " + encodeURIComponent(name) + "%0A" +
      "الهاتف: " + encodeURIComponent(phone) + "%0A" +
      "الخدمة: " + encodeURIComponent(service) + "%0A" +
      "مكان الأخذ: " + encodeURIComponent(pickup) + "%0A" +
      "مكان التوصيل: " + encodeURIComponent(dropoff) + "%0A" +
      "ملاحظات: " + encodeURIComponent(details);

    window.open("https://wa.me/212603681664?text=" + message, "_blank");
  });
</script>

</body>
</html>
