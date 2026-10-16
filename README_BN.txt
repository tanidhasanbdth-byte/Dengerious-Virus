Tanid Personal AI — Android PWA MVP
বাংলা নির্দেশনা:
1) ZIP extract করুন।
2) index.html, manifest.json, sw.js, icon-192.png, icon-512.png ফাইলগুলো GitHub repository-এর root-এ upload করুন (ZIP নিজে upload করবেন না)।
3) Repository Settings > Pages > Deploy from a branch > main > /(root) > Save।
4) প্রকাশিত https://USERNAME.github.io/REPO/ লিংক Chrome-এ খুলুন > ⋮ > Install app / Add to Home screen।
5) Notes/Tasks এই ডিভাইসের browser localStorage-এ থাকে। Browser data clear করলে হারাতে পারে; ব্যক্তিগত/গোপন তথ্য রাখবেন না।
সীমাবদ্ধতা:
- এটি প্রকৃত AI model embed করে না। ChatGPT/Gemini buttons অনলাইন সাইট খোলে।
- অফলাইন AI-এর জন্য Google AI Edge Gallery আলাদাভাবে ইনস্টল করে মডেল ডাউনলোড করুন।
- Voice typing browser-এর Speech Recognition support এবং internet-এর ওপর নির্ভর করতে পারে। Text-to-speech device/browser support অনুযায়ী কাজ করবে।
- এটি MVP/prototype; কোনো backend, cloud sync, secure database, বা guaranteed reminders নেই।
