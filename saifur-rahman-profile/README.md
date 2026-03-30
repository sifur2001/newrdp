# সাইফুর রহমান - Personal Profile

একটি আধুনিক এবং সুন্দর ব্যক্তিগত প্রোফাইল ওয়েবসাইট যা সাইফুর রহমানের জন্য তৈরি করা হয়েছে।

## ✨ বৈশিষ্ট্য

- 🎨 **আধুনিক UI ডিজাইন** - গ্রেডিয়েন্ট এবং অ্যানিমেশন সহ সুন্দর ডিজাইন
- 📱 **সম্পূর্ণ রেসপন্সিভ** - সব ডিভাইসে নিখুঁতভাবে কাজ করে
- ⚡ **দ্রুত এবং হালকা** - অপ্টিমাইজড পারফরম্যান্স
- 🎭 **অ্যানিমেশন** - মসৃণ স্ক্রল এবং হোভার ইফেক্ট
- 🌐 **বাংলা ভাষা সমর্থন** - সম্পূর্ণ বাংলায়
- 📧 **যোগাযোগ ফর্ম** - সহজ যোগাযোগের জন্য
- 🎯 **সেকশন**:
  - হোম (Hero Section)
  - সম্পর্কে (About)
  - দক্ষতা (Skills)
  - অভিজ্ঞতা ও শিক্ষা (Experience & Education)
  - যোগাযোগ (Contact)

## 🚀 কিভাবে ব্যবহার করবেন

### সরাসরি ব্যবহার

1. **ফাইল খুলুন**
   - `index.html` ফাইলটি যেকোনো ব্রাউজারে খুলুন

### লাইভ সার্ভার দিয়ে

1. **VS Code এ খুলুন**
   ```bash
   cd saifur-rahman-profile
   ```

2. **Live Server চালু করুন**
   - VS Code এ Live Server এক্সটেনশন ইনস্টল করুন
   - `index.html` ফাইলে রাইট ক্লিক করুন
   - "Open with Live Server" সিলেক্ট করুন

## 📝 কাস্টমাইজেশন

### ব্যক্তিগত তথ্য পরিবর্তন

[`index.html`](index.html) ফাইলে নিম্নলিখিত তথ্য পরিবর্তন করুন:

```html
<!-- নাম -->
<h1 class="hero-title">আমি <span class="gradient-text">সাইফুর রহমান</span></h1>

<!-- ইমেইল -->
<p>saifur.rahman@email.com</p>

<!-- ফোন -->
<p>+৮৮০ ১৭১২-৩৪৫৬৭৮</p>

<!-- ঠিকানা -->
<p>ঢাকা, বাংলাদেশ</p>
```

### প্রোফাইল ছবি পরিবর্তন

প্রোফাইল ছবি পরিবর্তন করতে [`index.html`](index.html) এ:

```html
<!-- বর্তমান (UI Avatars ব্যবহার করে) -->
<img src="https://ui-avatars.com/api/?name=Saifur+Rahman&size=300&background=667eea&color=fff&bold=true" alt="সাইফুর রহমান">

<!-- নিজের ছবি ব্যবহার করতে -->
<img src="images/profile.jpg" alt="সাইফুর রহমান">
```

### রঙ পরিবর্তন

[`css/style.css`](css/style.css) ফাইলে রুট ভেরিয়েবল পরিবর্তন করুন:

```css
:root {
    --primary-color: #667eea;      /* প্রাথমিক রঙ */
    --secondary-color: #764ba2;    /* সেকেন্ডারি রঙ */
    --accent-color: #f093fb;       /* অ্যাকসেন্ট রঙ */
}
```

### দক্ষতা পরিবর্তন

[`index.html`](index.html) এ দক্ষতা সেকশনে:

```html
<div class="skill-bar">
    <div class="skill-info">
        <span>HTML & CSS</span>
        <span class="skill-percentage">95%</span>
    </div>
    <div class="progress">
        <div class="progress-bar" data-progress="95"></div>
    </div>
</div>
```

### সোশ্যাল মিডিয়া লিংক

[`index.html`](index.html) এ সোশ্যাল লিংক আপডেট করুন:

```html
<a href="https://facebook.com/yourprofile" class="social-link" title="Facebook">
    <i class="fab fa-facebook-f"></i>
</a>
<a href="https://twitter.com/yourprofile" class="social-link" title="Twitter">
    <i class="fab fa-twitter"></i>
</a>
<a href="https://linkedin.com/in/yourprofile" class="social-link" title="LinkedIn">
    <i class="fab fa-linkedin-in"></i>
</a>
<a href="https://github.com/yourprofile" class="social-link" title="GitHub">
    <i class="fab fa-github"></i>
</a>
```

### টাইপিং টেক্সট পরিবর্তন

[`js/script.js`](js/script.js) ফাইলে:

```javascript
const typingTexts = [
    'ওয়েব ডেভেলপার',
    'সফটওয়্যার ইঞ্জিনিয়ার',
    'UI/UX ডিজাইনার',
    'সমস্যা সমাধানকারী',
    'প্রযুক্তি উৎসাহী'
];
```

## 📂 ফাইল স্ট্রাকচার

```
saifur-rahman-profile/
│
├── index.html          # মূল HTML ফাইল
├── README.md           # ডকুমেন্টেশন
│
├── css/
│   └── style.css       # সব স্টাইল
│
└── js/
    └── script.js       # সব JavaScript
```

## 🎨 ডিজাইন ফিচার

### গ্রেডিয়েন্ট
- প্রাথমিক: `#667eea` থেকে `#764ba2`
- সেকেন্ডারি: `#f093fb` থেকে `#f5576c`

### অ্যানিমেশন
- টাইপিং ইফেক্ট
- স্ক্রল অ্যানিমেশন
- হোভার ইফেক্ট
- প্রগ্রেস বার অ্যানিমেশন
- সার্কুলার প্রগ্রেস

### রেসপন্সিভ ব্রেকপয়েন্ট
- মোবাইল: `< 576px`
- ট্যাবলেট: `< 968px`
- ডেস্কটপ: `> 968px`

## 🔧 প্রযুক্তি

- **HTML5** - সেমান্টিক মার্কআপ
- **CSS3** - আধুনিক স্টাইলিং
  - Flexbox
  - Grid
  - Animations
  - Gradients
- **JavaScript (ES6+)** - ইন্টারঅ্যাক্টিভিটি
  - Intersection Observer API
  - Smooth Scrolling
  - Form Handling
- **Font Awesome 6** - আইকন
- **Google Fonts** - Hind Siliguri & Poppins

## 📱 ব্রাউজার সাপোর্ট

- ✅ Chrome (সর্বশেষ)
- ✅ Firefox (সর্বশেষ)
- ✅ Safari (সর্বশেষ)
- ✅ Edge (সর্বশেষ)
- ✅ Opera (সর্বশেষ)

## 🚀 পারফরম্যান্স

- ⚡ দ্রুত লোডিং
- 🎯 অপ্টিমাইজড CSS
- 📦 ছোট ফাইল সাইজ
- 🔄 মসৃণ অ্যানিমেশন

## 📧 যোগাযোগ ফর্ম

যোগাযোগ ফর্ম বর্তমানে ডেমো মোডে আছে। প্রোডাকশনে ব্যবহারের জন্য:

1. **Backend API যোগ করুন**
2. **Email Service সংযুক্ত করুন** (যেমন: EmailJS, Formspree)
3. **Database সংযোগ করুন** (ঐচ্ছিক)

## 🎯 ভবিষ্যৎ উন্নতি

- [ ] ব্লগ সেকশন
- [ ] পোর্টফোলিও গ্যালারি
- [ ] ডার্ক মোড
- [ ] মাল্টি-ল্যাঙ্গুয়েজ সাপোর্ট
- [ ] Backend ইন্টিগ্রেশন
- [ ] SEO অপ্টিমাইজেশন

## 📄 লাইসেন্স

এই প্রজেক্টটি ব্যক্তিগত ব্যবহারের জন্য তৈরি করা হয়েছে। আপনি চাইলে এটি কাস্টমাইজ করে ব্যবহার করতে পারেন।

## 👨‍💻 ডেভেলপার

**সাইফুর রহমান**
- 📧 Email: saifur.rahman@email.com
- 📱 Phone: +৮৮০ ১৭১২-৩৪৫৬৭৮
- 📍 Location: ঢাকা, বাংলাদেশ

---

Made with ❤️ by Saifur Rahman
