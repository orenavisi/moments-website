<!DOCTYPE html>
<html lang="he">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>רגעים מתוקים - מגשי אירוח חלביים</title>
<style>
  body {
    margin: 0; padding: 0;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    direction: rtl;
    background: #fff7f9;
    color: #5a3b4d;
  }
  header {
    background: #f3d4d8;
    padding: 20px 40px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    box-shadow: 0 3px 10px rgba(90,59,77,0.2);
  }
  header h1 {
    font-family: 'Georgia', serif;
    font-weight: 700;
    font-size: 2rem;
    color: #7e5160;
    margin: 0;
  }
  nav a {
    text-decoration: none;
    color: #7e5160;
    margin-left: 30px;
    font-weight: 600;
    transition: color 0.3s ease;
  }
  nav a:hover {
    color: #c97a8e;
  }
  .hero {
    background: url('https://images.unsplash.com/photo-1505253210344-6c43a3b8e49d?auto=format&fit=crop&w=1350&q=80') no-repeat center center/cover;
    height: 450px;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    color: #fff;
    text-shadow: 0 2px 8px rgba(0,0,0,0.5);
    padding: 0 20px;
    text-align: center;
  }
  .hero h2 {
    font-size: 3rem;
    margin: 0 0 15px 0;
    font-family: 'Georgia', serif;
  }
  .hero p {
    font-size: 1.2rem;
    max-width: 600px;
  }
  .btn-order {
    margin-top: 25px;
    padding: 14px 35px;
    background: #c97a8e;
    border: none;
    color: white;
    font-weight: 700;
    font-size: 1.2rem;
    border-radius: 25px;
    cursor: pointer;
    box-shadow: 0 5px 15px rgba(201,122,142,0.5);
    transition: background 0.3s ease;
  }
  .btn-order:hover {
    background: #a95a69;
  }
  section {
    max-width: 960px;
    margin: 50px auto;
    padding: 0 20px;
  }
  h3 {
    font-family: 'Georgia', serif;
    font-size: 2rem;
    color: #7e5160;
    margin-bottom: 25px;
    text-align: center;
  }
  .categories {
    display: flex;
    justify-content: space-around;
    flex-wrap: wrap;
    gap: 25px;
  }
  .category-card {
    background: #f9e6eb;
    border-radius: 15px;
    width: 250px;
    padding: 20px;
    box-shadow: 0 3px 12px rgba(125,80,97,0.15);
    text-align: center;
    transition: transform 0.3s ease;
    cursor: pointer;
  }
  .category-card:hover {
    transform: translateY(-8px);
    box-shadow: 0 10px 25px rgba(125,80,97,0.3);
  }
  .category-icon {
    font-size: 3.5rem;
    margin-bottom: 12px;
  }
  .category-title {
    font-weight: 700;
    font-size: 1.3rem;
    color: #7e5160;
  }
  footer {
    background: #f3d4d8;
    padding: 20px;
    text-align: center;
    color: #7e5160;
    font-weight: 600;
    font-size: 0.9rem;
    box-shadow: 0 -3px 10px rgba(90,59,77,0.2);
  }
  footer a {
    color: #7e5160;
    text-decoration: none;
    margin: 0 8px;
  }
  footer a:hover {
    color: #c97a8e;
  }
  /* טופס יצירת קשר */
  form {
    display:flex; 
    flex-direction: column; 
    gap: 15px;
  }
  form label {
    font-weight: 600;
    color: #7e5160;
  }
  form input, form textarea {
    padding:10px; 
    border-radius: 5px; 
    border: 1px solid #c97a8e; 
    font-size: 1rem;
    font-family: inherit;
  }
</style>
</head>
<body>

<header>
  <h1>רגעים מתוקים</h1>
  <nav>
    <a href="#">בית</a>
    <a href="#">תפריט</a>
    <a href="#">חבילות</a>
    <a href="#">צור קשר</a>
    <a href="#" class="btn-order">הזמן עכשיו</a>
  </nav>
</header>

<section class="hero">
  <h2>חוויה מתוקה ברגעים הכי יקרים</h2>
  <p>מגשי אירוח חלביים, קינוחים בעיצוב מוקפד, שירות אישי ושמחה בכל ביס.</p>
  <button class="btn-order">הזמן עכשיו</button>
</section>

<section>
  <h3>הקטגוריות שלנו</h3>
  <div class="categories">
    <div class="category-card">
      <div class="category-icon">🥐</div>
      <div class="category-title">מאפים מלוחים</div>
    </div>
    <div class="category-card">
      <div class="category-icon">🍰</div>
      <div class="category-title">קינוחים</div>
    </div>
    <div class="category-card">
      <div class="category-icon">🥗</div>
      <div class="category-title">סלטים</div>
    </div>
    <div class="category-card">
      <div class="category-icon">🍓</div>
      <div class="category-title">מגשי פירות</div>
    </div>
    <div class="category-card">
      <div class="category-icon">🌱</div>
      <div class="category-title">טבעוני</div>
    </div>
    <div class="category-card">
      <div class="category-icon">🎁</div>
      <div class="category-title">חבילות אירוח</div>
    </div>
  </div>
</section>

<section>
  <h3>מי אנחנו?</h3>
  <p style="max-width:700px; margin:0 auto; text-align:center; color:#6f4a59;">
    רגעים מתוקים – יוצרים עבורכם חווית אירוח אלגנטית ומתוקה, עם מגשים שמותאמים במיוחד לאירועים שלכם.  
    כל מנה מוגשת באהבה, באיכות ובסטייל שלא תשכחו.
  </p>
</section>

<section style="max-width:700px; margin: 50px auto; padding: 0 20px;">
  <h3>צור קשר</h3>
  <form action="mailto:Ravitazia@gmail.com" method="post" enctype="text/plain">
    <label for="name">שם מלא:</label>
    <input type="text" id="name" name="שם" required />

    <label for="phone">טלפון:</label>
    <input type="tel" id="phone" name="טלפון" required />

    <label for="email">אימייל:</label>
    <input type="email" id="email" name="אימייל" required />

    <label for="message">הודעה / פרטים נוספים:</label>
    <textarea id="message" name="הודעה" rows="4"></textarea>

    <button type="submit" class="btn-order">שלח</button>
  </form>
</section>

<footer>
  © 2025 רגעים מתוקים | 053-2297-505 |  
  <a href="#">אינסטגרם</a> | <a href="#">פייסבוק</a>
</footer>

</body>
</html>

