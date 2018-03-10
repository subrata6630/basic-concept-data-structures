# basic-concept-data-structures

কম্পিউটার সায়েন্স, প্রোগ্রামিং ইত্যাদির ফান্ডামেন্টাল বিষয় এর অন্যতম একটা হলো ডাটা স্ট্রাকচার, সাথে এলগরিদম।

ডাটা স্ট্রাকচার যেভাবে শুরু হয়
একদম ফান্ডামেন্টাল ডাটা টাইপ দিয়ে, যেমনঃ ইন্টিজার, ফ্লোট, স্ট্রিং ইত্যাদি। এরপর আছে সিক্যুয়েন্সিয়াল/লিনিয়ার ডাটা স্ট্রাকচারঃ এরে বা লিস্ট। এরপর আছে গ্রাফ বেসড ডাটা স্ট্রাকচার, যেমনঃ ট্রি, বাইনারি ট্রি, গ্রাফ ইত্যাদি।

ডাটা স্ট্রাকচার ৩ ক্যাটাগরিরঃ

১. প্রিমিটিভ ডাটা — ইন্টিজার, ফ্লোট, স্ট্রিং ইত্যাদি </br>

২. নন প্রিমিটিভ ডাটা — এরে  </br>

৩. এবস্ট্রাক্ট ডাটা — স্ট্যাক, কুই, হ্যাশ টেবল, ট্রি, গ্রাফ, হিপ </br>

আপনি যদি ডাটা স্ট্রাকচার ও এলগরিদম সম্পর্কে ধারণা রাখেন তাহলে নিশ্চয় Tree, B-Tree সম্পর্কেও ধারণা রাখেন। এবং এটাও জানেন O(n) এর চেয়ে O(log n) সার্চিং এর জন্য অবশ্যই ইফিসিয়েন্ট টাইম কমপ্লেক্সিটি।

বাইনারি সার্চের বিগ ওহ! O(log n), মানে লগারিদমিক টাইম কমপ্লেক্সিটি। লিনিয়ার সার্চের O(n), মানে লিনিয়ার টাইম কমপ্লেক্সিটি।

টাইম কমপ্লেক্সিটি এলগরিদম এর ব্যাপার। আমি যখন এলগরিদম নিয়ে আলোচনা করবো তখন টাইম কমপ্লেক্সিটি, এসিম্পটোটিক এনালাইসিস, বিভিন্ন নোটেশন (যেমনঃ Big O, small o, Omega, theta etc) নিয়ে আলোচনা করবো।

আপনি যদি ট্রি সম্পর্কে ধারণা রাখেন তাহলে অন্তত নিচের এই ৩ টা জিনিস খুব ভালো বুঝবেনঃ

১. পার্সিং ও পার্সার — সিন্টেক্স এনালাইসিস

২. রিলেশনাল ডাটাবেইজ এ ট্রি(বিশেষ করে বাইনারি সার্চ ট্রি) এর ব্যবহার

৩. ডাটাবেজ সার্চিং এ ট্রি এর ব্যবহার এবং যেভাবে ডাটাবেজ কাজ করে

ট্রি কি?
ট্রি একটি নন সিক্যুয়েন্সিয়াল ডাটা স্ট্রাকচার। কেনো নন সিক্যুয়েন্সিয়াল? কারণ এতে ডাটা গুলি সিক্যুয়েন্স আকারে সাজানো থাকে না, যেমনটা থাকে এরে তে।

ট্রি ডাটা স্ট্রাকচার যতটা না গাছের মত দেখে, তার চেয়ে বেশি দেখতে হায়রারকিকাল স্ট্রাকচারের মতো। আবার অনেকটা দাদা, বাবা, পুত্রের সম্পর্কের মতও ভাবা যায়।<

<img src="https://cdn-images-1.medium.com/max/800/0*VIBSrFALP1wx6sQj.png" alt="Smiley face" height="42" width="42">


