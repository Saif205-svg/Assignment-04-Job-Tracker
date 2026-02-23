
## Answers to Questions

### 1. What is the difference between getElementById, getElementsByClassName, and querySelector / querySelectorAll?
নির্দিষ্ট কোন IDName কে ধরার জন্য JavaScript এ আমরা getElementByID() মেথডটি ব্যাবহার করা হয়ে থাকে। আবার একই নামে ডিফাইন করা ক্লাস কে javascript এ ধরার জন্য getElementsByClassName() মেথডটি ব্যাবহার করাতে পারি। এই মেথড এর সাহায্যে একাধিক ক্লাস কে ধরা যায়। querySelector() মেথড রিটার্ন করে CSS সিলেক্টরে match হওয়া প্রথম element কে। আর querySelectorAll() method রিটার্ন করে CSS সিলেক্টরে match হওয়া সকল ক্লাস এবং আইডি কে। উদাহরনঃ querySelectorAll('.className','#IdName');

### 2. How do you create and insert a new element into the DOM?
DOM এ আমরা নতুন কোন element create করতে চাইলে createElement() method ব্যাবহা করব, আর সেই element এ কোন ডাটা বা element insert করতে চাইলে innerHTML অথবা create করা element অনুসারে innerText মেথড ও ব্যাবহার করতে পারি।

### 3. What is Event Bubbling? And how does it work?
Event Bubbling হল যখন আমরা কোন বাটনে ক্লিক করি তখন সেটা শুধুমাত্র সে বাটনে থেমে না থেকে ক্রমান্বয়ে তার parent এর দিকে যায় এবং সেটা ব্রাউজারে console করে। এটি target element থেকে শুরু করে html document পর্যন্ত চলতে থাকে।

### 4. What is Event Delegation in JavaScript? Why is it useful?
Event Delegation হচ্ছে এমন একটি মেথড যার সাহায্যে আমরা যে element এ ক্লিক করব সেটি ডিলিট হয়ে যাবে। এটি ব্যাবহারের ৩ টি মূল কারন রয়েছেঃ (i) Dynamically কাজ করে, (ii) performance ভালো থাকে যেমন ১০০ টি element এর জন্য ১০০ টি addEventListener না বসিয়ে delegation করে কাজ সম্পাদন করা যায়। (iii) কোড ক্লিন রাখা যায়।

### 5. What is the difference between preventDefault() and stopPropagation() methods?
preventDefault() method ওয়েবসাইটের ডিফল্ট ব্যাবহারে বাধা সৃষ্টি করে, অর্থাৎ এই মেথড ব্যাবহার করলে ব্রাউজার যেটা নরমালি করত সেটা করতে পারেনা।

stopPropagation() method মুলত event bubbling

