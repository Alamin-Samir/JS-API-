# My JavaScript & API Notes

আজকে আমরা শিখেছি কীভাবে JavaScript দিয়ে API থেকে ডাটা আনতে হয়।

### কোড স্নিপেট:
```javascript
async function loadData() {
    let response = await fetch('[https://jsonplaceholder.typicode.com/todos/1](https://jsonplaceholder.typicode.com/todos/1)');
    let data = await response.json();
    console.log(data.title);
}
loadData();






*(লেখা শেষ হলে `Ctrl + S` চেপে ফাইলটি সেভ করে নাও।)*

---

### ধাপ ৪: গিটহাবে একটি প্রাইভেট রিপোজিটরি (খালি ঘর) তৈরি করা




এবার এই নোটগুলো ইন্টারনেটে অনলাইনে সুরক্ষিত রাখার পালা।


১. ব্রাউজারে গিয়ে [GitHub](https://github.com/) এ লগইন করো।
২. ওপরের ডানপাশের কোণায় থাকা **`+`** আইকনে ক্লিক করে **`New repository`** সিলেক্ট করো।
৩. রিপোজিটরির একটি নাম দাও (যেমন: `my-coding-notes`)।

৪. এটিকে অবশ্যই **`Private`** সিলেক্ট করবে (যাতে অন্য কেউ দেখতে না পায়)।
৫. নিচের **`Create repository`** বাটনে ক্লিক করো। (ক্লিক করার পর গিটহাব তোমাকে কিছু কোড বা লিংক দেখাবে, ওগুলো আমরা পরের ধাপে ব্যবহার করব)।

---

### ধাপ ৫: ভিএস কোডের সাথে গিটহাব কানেক্ট করা (টার্মিনাল কমান্ড)
এখন তোমার কম্পিউটারের ভিএস কোডের টার্মিনালে গিটহাবের সাথে লিংক করিয়ে দেবো।
১. ভিএস কোডের ওপরের মেনু থেকে **Terminal** > **New Terminal** এ ক্লিক করে টার্মিনাল ওপেন করো।
২. এবার নিচের কমান্ডগুলো **একটা একটা করে** লিখে কিবোর্ডের `Enter` প্রেস করবে:

* **কমান্ড ১ (গিট চালু করা):**
  ```bash
  git init



  vs code a gie ftrch  korte hobe 