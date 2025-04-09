HTML পূর্ণাঙ্গ গাইড (বাংলা)

এই গাইডটি HTML শেখার জন্য একদম শুরু থেকে শেষ পর্যন্ত গুরুত্বপূর্ণ বিষয়গুলোকে বিস্তারিতভাবে ব্যাখ্যা করবে।


---

অধ্যায় ১: HTML পরিচিতি

HTML (HyperText Markup Language) হলো ওয়েব পেজ তৈরি করার প্রধান ভাষা। এটি একটি মার্কআপ ভাষা যা বিভিন্ন ট্যাগের মাধ্যমে ওয়েব কনটেন্ট সাজাতে ব্যবহৃত হয়। প্রতিটি ট্যাগের আলাদা আলাদা কাজ আছে। HTML এর মাধ্যমে আমরা টেক্সট, ছবি, ভিডিও, লিংক, টেবিল ইত্যাদি যুক্ত করতে পারি।


---

অধ্যায় ২: HTML এর গঠন

HTML ডকুমেন্ট সাধারণত নিচের মত গঠিত হয়:

<!DOCTYPE html> <!-- এইটি HTML5 ডকুমেন্ট বোঝায় -->
<html>
  <head>
    <title>শিরোনাম</title> <!-- ব্রাউজারের ট্যাবে যেটা দেখা যাবে -->
  </head>
  <body>
    <!-- মূল কনটেন্ট এখানে থাকবে -->
    <h1>স্বাগতম!</h1>
    <p>এটি একটি উদাহরণ পৃষ্ঠা।</p>
  </body>
</html>


---

অধ্যায় ৩: হেডিং ও প্যারাগ্রাফ

হেডিং ট্যাগ:

HTML-এ মোট ৬টি হেডিং ট্যাগ আছে:

<h1>সবচেয়ে বড় হেডিং</h1>
<h2>...</h2>
...
<h6>সবচেয়ে ছোট হেডিং</h6>

প্যারাগ্রাফ:

<p>এটি একটি সাধারণ প্যারাগ্রাফ।</p>


---

অধ্যায় ৪: লিস্ট

HTML-এ দুই ধরনের লিস্ট থাকে:

1. Unordered List (<ul>) → বিন্দু দিয়ে তালিকা


2. Ordered List (<ol>) → সংখ্যা/বর্ণ দিয়ে তালিকা



<ul>
  <li>আপেল</li>
  <li>কমলা</li>
</ul>

<ol>
  <li>প্রথম</li>
  <li>দ্বিতীয়</li>
</ol>


---

অধ্যায় ৫: টেবিল

HTML টেবিল তৈরির জন্য ব্যবহার হয়:

<table>: পুরো টেবিল

<tr>: সারি (row)

<th>: হেডার কলাম

<td>: সাধারণ কলাম


<table border="1">
  <tr>
    <th>নাম</th>
    <th>বয়স</th>
  </tr>
  <tr>
    <td>রাহুল</td>
    <td>২৫</td>
  </tr>
</table>


---

অধ্যায় ৬: লিংক ও ছবি

লিংক:

<a href="https://example.com">এই লিংকে যাও</a>

ছবি:

<img src="image.jpg" alt="ছবির বর্ণনা" width="200">


---

অধ্যায় ৭: ফর্ম

HTML ফর্ম ব্যবহার করে ইউজারের ইনপুট নেওয়া হয়:

<form action="submit.php" method="post">
  <label>নাম:</label>
  <input type="text" name="username">
  <br>
  <label>বার্তা:</label>
  <textarea name="message"></textarea>
  <br>
  <button type="submit">জমা দিন</button>
</form>


---

অধ্যায় ৮: মিডিয়া ট্যাগ

অডিও:

<audio controls>
  <source src="sound.mp3" type="audio/mpeg">
  আপনার ব্রাউজার অডিও প্লে করতে পারছে না।
</audio>

ভিডিও:

<video controls width="300">
  <source src="video.mp4" type="video/mp4">
  আপনার ব্রাউজার ভিডিও প্লে করতে পারছে না।
</video>


---

অধ্যায় ৯: সেমান্টিক এলিমেন্ট

এই ট্যাগগুলো ডকুমেন্টকে অর্থপূর্ণ করে তোলে:

<header>ওয়েবসাইটের উপরের অংশ</header>
<nav>নেভিগেশন লিংক</nav>
<main>মূল কনটেন্ট</main>
<section>বিভাগ</section>
<article>স্বতন্ত্র কনটেন্ট</article>
<aside>সাইড ইনফো</aside>
<footer>পাদটীকা</footer>


---

অধ্যায় ১০: HTML5 ফিচার

নতুন ইনপুট টাইপ: email, date, range, color

মিডিয়া এলিমেন্ট: <video>, <audio>

ক্যানভাস: <canvas> গ্রাফিক্স আঁকার জন্য

ওয়েব স্টোরেজ: localStorage ও sessionStorage

নতুন API সমূহ: Drag & Drop, GeoLocation, Web Workers



---

অধ্যায় ১১: HTML Entities & Symbols

HTML-এ কিছু বিশেষ ক্যারেক্টার সরাসরি ব্যবহার করা যায় না। যেমন: <, >, & ইত্যাদি।

<p>কম চিহ্ন: &lt;</p>
<p>বেশি চিহ্ন: &gt;</p>
<p>অ্যান্ড চিহ্ন: &amp;</p>
<p>কপিরাইট: &copy;</p>
<p>নন-ব্রেকিং স্পেস: &nbsp;</p>


---

অধ্যায় ১২: IFrame ও Embed

<iframe src="https://example.com" width="600" height="400"></iframe>

<embed src="file.pdf" width="300" height="400">


---

অধ্যায় ১৩: Meta Tags ও SEO

<meta charset="UTF-8">
<meta name="description" content="HTML শেখার বাংলা বই">
<meta name="keywords" content="HTML, শেখা, বাংলা">
<meta name="author" content="আপনার নাম">
<meta name="viewport" content="width=device-width, initial-scale=1.0">


---

অধ্যায় ১৪: Accessibility (a11y)

alt ট্যাগ ছবি বোঝায় স্ক্রিন রিডারের জন্য

label ও for অ্যাট্রিবিউট ইনপুটের জন্য

aria-* অ্যাট্রিবিউট সহায়ক টুলের জন্য



---

অধ্যায় ১৫: Responsive Design

<meta name="viewport" content="width=device-width, initial-scale=1.0">
<picture>
  <source media="(max-width: 600px)" srcset="small.jpg">
  <img src="large.jpg" alt="ছবি">
</picture>


---

অধ্যায় ১৬: HTML Boilerplate

<!DOCTYPE html>
<html lang="bn">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>আমার ওয়েবসাইট</title>
</head>
<body>
  <!-- কনটেন্ট -->
</body>
</html>


---

অধ্যায় ১৭: প্র্যাকটিক্যাল প্রজেক্ট

1. পোর্টফোলিও ওয়েবসাইট


2. ব্যক্তিগত ব্লগ


3. কনট্যাক্ট ফর্ম


4. ছবি গ্যালারি




---

অধ্যায় ১৮: HTML + CSS + JS সংযোগ

<link rel="stylesheet" href="style.css">
<script src="script.js"></script>


---

অধ্যায় ১৯: কোডিং কনভেনশন ও Best Practices

ইন্ডেন্টেশন ঠিক রাখা (2 বা 4 space)

ট্যাগ ক্লোজ করা

মিনিমাল কমেন্ট ব্যবহার করা

অর্থবোধক নাম ব্যবহার করা



---

অধ্যায় ২০: HTML Validation ও Debugging

W3C Validator ব্যবহার করা

DevTools দিয়ে এলিমেন্ট ইন্সপেক্ট করা



---

শেষ কথা: HTML শেখা হলো ওয়েব ডেভেলপমেন্টের প্রথম ধাপ। এই গাইডটির মাধ্যমে আপনি শুরু থেকে অনেক কিছু শিখতে পারবেন। CSS ও JavaScript এর সাথে ব্যবহার করলে আপনি সম্পূর্ণ ওয়েবসাইট তৈরি করতে পারবেন।

পরবর্তী টপিক: CSS গাইড (বাংলা) — চাইলে সেটাও তৈরি করে দেব।

