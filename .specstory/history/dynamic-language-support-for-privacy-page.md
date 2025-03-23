## SpecStory

## Dynamic Language Support for Privacy Page (3/23/2025, 7:39:25 PM)

_**User**_

can you fix this page(privacy.html) it was designed for only two languages which are tr and en but i have fr too. can we make it dynamic and fall back to en?

---

_**Assistant**_

I'll update the privacy.html page to handle French and use English as a fallback for other languages. Let me modify the code:

---

_****_

```diff
              var redirectUrl;
              if (langParam) {
-                 // Redirect based on the query parameter
-                 redirectUrl = langParam === 'tr' ? 'privacy_tr.html' : 'privacy_en.html';
+                 // Handle the three supported languages: tr, fr, and en (default)
+                 if (langParam === 'tr') {
+                     redirectUrl = 'privacy_tr.html';
+                 } else if (langParam === 'fr') {
+                     redirectUrl = 'privacy_fr.html';
+                 } else {
+                     redirectUrl = 'privacy_en.html'; // Default/fallback to English
+                 }
              } else {
-                 // Default to language detection if no query parameter is present
+                 // No query parameter, detect browser language
                  var userLang = navigator.language || navigator.userLanguage;
-                 redirectUrl = userLang.startsWith('tr') ? 'privacy_tr.html' : 'privacy_en.html';
+                 userLang = userLang.substring(0, 2).toLowerCase(); // Get the language code part only
+                 
+                 if (userLang === 'tr') {
+                     redirectUrl = 'privacy_tr.html';
+                 } else if (userLang === 'fr') {
+                     redirectUrl = 'privacy_fr.html';
+                 } else {
+                     redirectUrl = 'privacy_en.html'; // Default/fallback to English
+                 }
              }
  
```

---

_****_

The privacy.html page has been updated to support French language and use English as a fallback. The changes include:

1. Added support for 'fr' in the query parameter handling
2. Improved the browser language detection to work with standard language codes
3. Set English as the default fallback for any language that isn't Turkish or French

The code now extracts just the first two characters of the language code and converts them to lowercase, ensuring proper language detection for all browser formats.

---

_**User**_

do the same for terms.html and kvkk.html

---

_**Assistant**_

I'll need to check if terms.html and kvkk.html exist first, and then update them with the same language handling logic.

---

_****_



---

_****_



---

_****_

Read file: undefined

---

_****_

Read file: undefined

---

_****_

Now I'll update both files with the same language handling logic as privacy.html:

---

_****_

```diff
              var redirectUrl;
              if (langParam) {
-                 // Redirect based on the query parameter
-                 redirectUrl = langParam === 'tr' ? 'terms_tr.html' : 'terms_en.html';
+                 // Handle the three supported languages: tr, fr, and en (default)
+                 if (langParam === 'tr') {
+                     redirectUrl = 'terms_tr.html';
+                 } else if (langParam === 'fr') {
+                     redirectUrl = 'terms_fr.html';
+                 } else {
+                     redirectUrl = 'terms_en.html'; // Default/fallback to English
+                 }
              } else {
-                 // Default to language detection if no query parameter is present
+                 // No query parameter, detect browser language
                  var userLang = navigator.language || navigator.userLanguage;
-                 redirectUrl = userLang.startsWith('tr') ? 'terms_tr.html' : 'terms_en.html';
+                 userLang = userLang.substring(0, 2).toLowerCase(); // Get the language code part only
+                 
+                 if (userLang === 'tr') {
+                     redirectUrl = 'terms_tr.html';
+                 } else if (userLang === 'fr') {
+                     redirectUrl = 'terms_fr.html';
+                 } else {
+                     redirectUrl = 'terms_en.html'; // Default/fallback to English
+                 }
              }
  
```

---

_****_

```diff
              var redirectUrl;
              if (langParam) {
-                 // Redirect based on the query parameter
-                 redirectUrl = langParam === 'tr' ? 'kvkk_tr.html' : 'kvkk_en.html';
+                 // Handle the three supported languages: tr, fr, and en (default)
+                 if (langParam === 'tr') {
+                     redirectUrl = 'kvkk_tr.html';
+                 } else if (langParam === 'fr') {
+                     redirectUrl = 'kvkk_fr.html';
+                 } else {
+                     redirectUrl = 'kvkk_en.html'; // Default/fallback to English
+                 }
              } else {
-                 // Default to language detection if no query parameter is present
+                 // No query parameter, detect browser language
                  var userLang = navigator.language || navigator.userLanguage;
-                 redirectUrl = userLang.startsWith('tr') ? 'kvkk_tr.html' : 'kvkk_en.html';
+                 userLang = userLang.substring(0, 2).toLowerCase(); // Get the language code part only
+                 
+                 if (userLang === 'tr') {
+                     redirectUrl = 'kvkk_tr.html';
+                 } else if (userLang === 'fr') {
+                     redirectUrl = 'kvkk_fr.html';
+                 } else {
+                     redirectUrl = 'kvkk_en.html'; // Default/fallback to English
+                 }
              }
  
```

---

_****_

Both files have been successfully updated to:

1. Support three languages: Turkish (tr), French (fr), and English (en)
2. Use English as the fallback for any language that's not Turkish or French
3. Extract just the first two characters of the browser language code and convert to lowercase
4. Match the same language handling implementation as privacy.html

All three pages (privacy.html, terms.html, and kvkk.html) now have consistent language handling.

---



---

