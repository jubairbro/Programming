HTML পূর্ণাঙ্গ গাইড (বাংলা)

এই গাইডটি HTML শেখার জন্য একদম শুরু থেকে শেষ পর্যন্ত গুরুত্বপূর্ণ বিষয়গুলোকে বিস্তারিতভাবে ব্যাখ্যা করবে।


---

অধ্যায় ১: HTML পরিচিতি

HTML (HyperText Markup Language) হলো ওয়েব পেজ তৈরি করার প্রধান ভাষা। এটি একটি মার্কআপ ভাষা যা বিভিন্ন ট্যাগের মাধ্যমে ওয়েব কনটেন্ট সাজাতে ব্যবহৃত হয়। প্রতিটি ট্যাগের আলাদা আলাদা কাজ আছে। HTML এর মাধ্যমে আমরা টেক্সট, ছবি, ভিডিও, লিংক, টেবিল ইত্যাদি যুক্ত করতে পারি।


---

অধ্যায় ২: HTML এর গঠন

HTML ডকুমেন্ট সাধারণত নিচের মত গঠিত হয়:

&lt;!DOCTYPE html&gt;
&lt;html&gt;
  &lt;head&gt;
    &lt;title&gt;শিরোনাম&lt;/title&gt;
  &lt;/head&gt;
  &lt;body&gt;
    &lt;h1&gt;স্বাগতম!&lt;/h1&gt;
    &lt;p&gt;এটি একটি উদাহরণ পৃষ্ঠা।&lt;/p&gt;
  &lt;/body&gt;
&lt;/html&gt;


---

অধ্যায় ৩: হেডিং ও প্যারাগ্রাফ

হেডিং ট্যাগ:

&lt;h1&gt;সবচেয়ে বড় হেডিং&lt;/h1&gt;
&lt;h2&gt;...&lt;/h2&gt;
...
&lt;h6&gt;সবচেয়ে ছোট হেডিং&lt;/h6&gt;

প্যারাগ্রাফ:

&lt;p&gt;এটি একটি সাধারণ প্যারাগ্রাফ।&lt;/p&gt;


---

অধ্যায় ৪: লিস্ট

&lt;ul&gt;
  &lt;li&gt;আপেল&lt;/li&gt;
  &lt;li&gt;কমলা&lt;/li&gt;
&lt;/ul&gt;

&lt;ol&gt;
  &lt;li&gt;প্রথম&lt;/li&gt;
  &lt;li&gt;দ্বিতীয়&lt;/li&gt;
&lt;/ol&gt;


---

অধ্যায় ৫: টেবিল

&lt;table border=&quot;1&quot;&gt;
  &lt;tr&gt;
    &lt;th&gt;নাম&lt;/th&gt;
    &lt;th&gt;বয়স&lt;/th&gt;
  &lt;/tr&gt;
  &lt;tr&gt;
    &lt;td&gt;রাহুল&lt;/td&gt;
    &lt;td&gt;২৫&lt;/td&gt;
  &lt;/tr&gt;
&lt;/table&gt;


---

অধ্যায় ৬: লিংক ও ছবি

লিংক:

&lt;a href=&quot;https://example.com&quot;&gt;এই লিংকে যাও&lt;/a&gt;

ছবি:

&lt;img src=&quot;image.jpg&quot; alt=&quot;ছবির বর্ণনা&quot; width=&quot;200&quot;&gt;


---

অধ্যায় ৭: ফর্ম

&lt;form action=&quot;submit.php&quot; method=&quot;post&quot;&gt;
  &lt;label&gt;নাম:&lt;/label&gt;
  &lt;input type=&quot;text&quot; name=&quot;username&quot;&gt;
  &lt;br&gt;
  &lt;label&gt;বার্তা:&lt;/label&gt;
  &lt;textarea name=&quot;message&quot;&gt;&lt;/textarea&gt;
  &lt;br&gt;
  &lt;button type=&quot;submit&quot;&gt;জমা দিন&lt;/button&gt;
&lt;/form&gt;


---

অধ্যায় ৮: মিডিয়া ট্যাগ

অডিও:

&lt;audio controls&gt;
  &lt;source src=&quot;sound.mp3&quot; type=&quot;audio/mpeg&quot;&gt;
  আপনার ব্রাউজার অডিও প্লে করতে পারছে না।
&lt;/audio&gt;

ভিডিও:

&lt;video controls width=&quot;300&quot;&gt;
  &lt;source src=&quot;video.mp4&quot; type=&quot;video/mp4&quot;&gt;
  আপনার ব্রাউজার ভিডিও প্লে করতে পারছে না।
&lt;/video&gt;


---

অধ্যায় ৯: সেমান্টিক এলিমেন্ট

&lt;header&gt;ওয়েবসাইটের উপরের অংশ&lt;/header&gt;
&lt;nav&gt;নেভিগেশন লিংক&lt;/nav&gt;
&lt;main&gt;মূল কনটেন্ট&lt;/main&gt;
&lt;section&gt;বিভাগ&lt;/section&gt;
&lt;article&gt;স্বতন্ত্র কনটেন্ট&lt;/article&gt;
&lt;aside&gt;সাইড ইনফো&lt;/aside&gt;
&lt;footer&gt;পাদটীকা&lt;/footer&gt;


---

অধ্যায় ১০: HTML5 ফিচার

নতুন ইনপুট টাইপ: email, date, range, color

মিডিয়া এলিমেন্ট: <video>, <audio>

ক্যানভাস: <canvas> গ্রাফিক্স আঁকার জন্য

ওয়েব স্টোরেজ: localStorage ও sessionStorage

নতুন API সমূহ: Drag & Drop, GeoLocation, Web Workers



---

অধ্যায় ১১: HTML Entities & Symbols

&lt;p&gt;কম চিহ্ন: &amp;lt;&lt;/p&gt;
&lt;p&gt;বেশি চিহ্ন: &amp;gt;&lt;/p&gt;
&lt;p&gt;অ্যান্ড চিহ্ন: &amp;amp;&lt;/p&gt;
&lt;p&gt;কপিরাইট: &amp;copy;&lt;/p&gt;
&lt;p&gt;নন-ব্রেকিং স্পেস: &amp;nbsp;&lt;/p&gt;


---

অধ্যায় ১২: IFrame ও Embed

&lt;iframe src=&quot;https://example.com&quot; width=&quot;600&quot; height=&quot;400&quot;&gt;&lt;/iframe&gt;
&lt;embed src=&quot;file.pdf&quot; width=&quot;300&quot; height=&quot;400&quot;&gt;


---

অধ্যায় ১৩: Meta Tags ও SEO

&lt;meta charset=&quot;UTF-8&quot;&gt;
&lt;meta name=&quot;description&quot; content=&quot;HTML শেখার বাংলা বই&quot;&gt;
&lt;meta name=&quot;keywords&quot; content=&quot;HTML, শেখা, বাংলা&quot;&gt;
&lt;meta name=&quot;author&quot; content=&quot;আপনার নাম&quot;&gt;
&lt;meta name=&quot;viewport&quot; content=&quot;width=device-width, initial-scale=1.0&quot;&gt;


---

অধ্যায় ১৪: Accessibility (a11y)

alt ট্যাগ ছবি বোঝায় স্ক্রিন রিডারের জন্য

label ও for অ্যাট্রিবিউট ইনপুটের জন্য

aria-* অ্যাট্রিবিউট সহায়ক টুলের জন্য



---

অধ্যায় ১৫: Responsive Design

&lt;meta name=&quot;viewport&quot; content=&quot;width=device-width, initial-scale=1.0&quot;&gt;
&lt;picture&gt;
  &lt;source media=&quot;(max-width: 600px)&quot; srcset=&quot;small.jpg&quot;&gt;
  &lt;img src=&quot;large.jpg&quot; alt=&quot;ছবি&quot;&gt;
&lt;/picture&gt;


---

অধ্যায় ১৬: HTML Boilerplate

&lt;!DOCTYPE html&gt;
&lt;html lang=&quot;bn&quot;&gt;
&lt;head&gt;
  &lt;meta charset=&quot;UTF-8&quot;&gt;
  &lt;meta name=&quot;viewport&quot; content=&quot;width=device-width, initial-scale=1.0&quot;&gt;
  &lt;title&gt;আমার ওয়েবসাইট&lt;/title&gt;
&lt;/head&gt;
&lt;body&gt;
  &lt;!-- কনটেন্ট --&gt;
&lt;/body&gt;
&lt;/html&gt;


---

অধ্যায় ১৭: প্র্যাকটিক্যাল প্রজেক্ট

1. পোর্টফোলিও ওয়েবসাইট


2. ব্যক্তিগত ব্লগ


3. কনট্যাক্ট ফর্ম


4. ছবি গ্যালারি




---

অধ্যায় ১৮: HTML + CSS + JS সংযোগ

&lt;link rel=&quot;stylesheet&quot; href=&quot;style.css&quot;&gt;
&lt;script src=&quot;script.js&quot;&gt;&lt;/script&gt;


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

