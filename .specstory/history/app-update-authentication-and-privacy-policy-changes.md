## SpecStory

## App Update: Authentication and Privacy Policy Changes (3/23/2025, 4:57:28 PM)

_**User**_

I changed the app a little bit. I implemented Firebase authentication with Google And Apple sign in. And I moved the stroring credits from icloud to firebase. Histories are still stored localy and on icloud tho. Update privacy policy, kvkk and terms for each language accordingly.

---

_**Assistant**_

I'll update the privacy policy, KVKK, and terms files across all languages to reflect the changes in authentication and credit storage.

---

_****_

Read file: undefined

---

_****_

```diff
              <ul>
                  <li><strong>Dating App Content:</strong> We temporarily process the screenshots, messages, and profile information you upload for analysis and coaching purposes. This may include dating app conversations, profile pictures, and bios. This content is not stored on our servers.</li>
+                 <li><strong>Authentication Information:</strong> When you sign in using Google or Apple authentication, we receive basic account information such as your email address and account identifier. This information is stored in Firebase Authentication.</li>
                  <li><strong>Local Storage:</strong> Your coaching requests, AI suggestions, and interaction history are stored locally on your device and in your private iCloud storage. We do not have access to this data.</li>
-                 <li><strong>Credits:</strong> Information about your credit usage is stored privately in your iCloud account. We do not have access to this data.</li>
+                 <li><strong>Credits:</strong> Information about your credit usage is stored in your Firebase account. This data is linked to your authentication profile.</li>
                  <li><strong>Usage Data:</strong> We use Firebase Analytics and Google Analytics to track user behavior within the app.</li>
                  <li><strong>Crash Reports:</strong> We use Firebase Crashlytics to collect crash reports to improve the app's stability.</li>
              <p>Having accurate information about you permits us to provide you with a smooth, efficient, and customized experience. Specifically, we may use information collected about you via the application to:</p>
              <ul>
+                 <li>Authenticate your identity using Google or Apple sign-in.</li>
+                 <li>Maintain your account information and credit balance in Firebase.</li>
                  <li>Provide AI-powered dating coaching services using Gemini from Firebase SDK.</li>
                  <li>Temporarily process dating app screenshots and conversations to offer personalized advice.</li>
  
              <h2>Sharing Your Information</h2>
-             <p>We do not store personal data on our servers. However, certain information may be shared as follows:</p>
+             <p>We store limited personal data on our servers through Firebase Authentication and Firebase Database for credit management. Certain information may be shared as follows:</p>
              <ul>
                  <li><strong>By Law or to Protect Rights:</strong> If we believe the release of information about you is necessary to respond to legal process, to investigate or remedy potential violations of our policies, or to protect the rights, property, and safety of others, we may share your information as permitted or required by any applicable law, rule, or regulation.</li>
-                 <li><strong>Third-Party Service Providers:</strong> We use Firebase Analytics, Google Analytics, and Firebase Crashlytics which collect usage and crash data according to their own privacy policies.</li>
+                 <li><strong>Third-Party Service Providers:</strong> We use Firebase Authentication, Firebase Database, Firebase Analytics, Google Analytics, and Firebase Crashlytics which collect and store data according to their own privacy policies.</li>
                  <li><strong>AI Processing Services:</strong> We use Gemini AI from Firebase SDK to analyze your dating app content and generate coaching suggestions. Your content is processed temporarily and is not stored by these services.</li>
              </ul>
              <p>Lenora AI Dating Coach uses the following third-party services:</p>
              <ul>
+                 <li>Firebase Authentication: For user authentication with Google and Apple sign-in</li>
+                 <li>Firebase Database: For storing your credit information</li>
                  <li>Firebase Analytics and Google Analytics: For usage analysis</li>
                  <li>Firebase Crashlytics: For crash reporting</li>
                  <li>Gemini AI (Firebase SDK): For analyzing dating content and generating coaching suggestions</li>
-                 <li>Apple iCloud: For storing your credits and coaching history privately</li>
+                 <li>Apple iCloud: For storing your coaching history privately</li>
+                 <li>Google and Apple Authentication Services: For identity verification</li>
              </ul>
              <p>These services may collect and process your data according to their own privacy policies.</p>
              <p>We prioritize your privacy in the following ways:</p>
              <ul>
-                 <li>We do not maintain user accounts or authentication systems.</li>
-                 <li>We do not store your personal data on our servers.</li>
-                 <li>Your credits and coaching history are stored only on your device and in your private iCloud storage.</li>
+                 <li>We maintain user accounts and authentication systems only for necessary functionality using Firebase Authentication.</li>
+                 <li>We store only the minimal necessary personal data on our servers (email address and account identifier for authentication, and credit balance).</li>
+                 <li>Your coaching history is stored only on your device and in your private iCloud storage.</li>
                  <li>You can delete your coaching history and results at any time from within the app.</li>
                  <li>Content you upload for analysis is processed temporarily and is not permanently stored by us.</li>
+                 <li>You can request deletion of your account data by contacting us.</li>
              </ul>
  
              <h2>International Data Transfers</h2>
-             <p>Since we do not store personal data on our servers, there are no international data transfers of your personal data by us. However, the third-party services we use (Firebase Analytics, Google Analytics, Firebase Crashlytics) may transfer data according to their own privacy policies.</p>
+             <p>The limited personal data we store (authentication information and credit balance) in Firebase may be transferred to different countries where Firebase operates. These transfers are governed by appropriate safeguards as required by applicable laws. The third-party services we use (Firebase Authentication, Firebase Database, Firebase Analytics, Google Analytics, Firebase Crashlytics) may also transfer data according to their own privacy policies.</p>
  
              <h2>GDPR Compliance</h2>
-             <p>While we do not store personal data on our servers, users in the European Economic Area (EEA) still have rights regarding any data processing:</p>
+             <p>We store limited personal data on our servers through Firebase. Users in the European Economic Area (EEA) have the following rights regarding this data:</p>
              <ul>
-                 <li><strong>Access and Portability:</strong> Since we don't store your personal data, all your coaching data is already in your possession on your device and iCloud.</li>
-                 <li><strong>Rectification and Erasure:</strong> You can delete your coaching history and results at any time from within the app.</li>
-                 <li><strong>Restriction and Objection:</strong> You can stop using specific features of the app if you object to how they process your data.</li>
+                 <li><strong>Access and Portability:</strong> You can request a copy of your personal data we store.</li>
+                 <li><strong>Rectification and Erasure:</strong> You can request correction of inaccurate data or deletion of your account and associated data. You can also delete your coaching history and results at any time from within the app.</li>
+                 <li><strong>Restriction and Objection:</strong> You can request that we restrict processing of your data or object to processing in certain circumstances.</li>
              </ul>
              <p>For any GDPR-related inquiries, please contact us at <a href="mailto:lenora@ulassancak.com">lenora@ulassancak.com</a>.</p>
  
              <h2>California Consumer Privacy Act (CCPA) Compliance</h2>
-             <p>Since we do not sell or store personal data, most CCPA provisions do not apply to our app. However, California residents should be aware that the third-party services we use (Firebase Analytics, Google Analytics, Firebase Crashlytics) may collect certain data according to their own privacy policies.</p>
+             <p>Under the CCPA, California residents have certain rights regarding their personal information. Since we store limited personal data (authentication information and credit balance), you have the right to know what personal information we collect, request deletion of your personal information, and opt-out of the sale of personal information (though we do not sell personal information). California residents should also be aware that the third-party services we use may collect certain data according to their own privacy policies.</p>
  
              <h2>Dating Content and Privacy</h2>
                  <li>All uploaded screenshots and conversations are processed temporarily and are not stored on our servers.</li>
                  <li>Results from AI analysis are stored only on your device and in your private iCloud storage.</li>
+                 <li>Authentication data and credit information are stored securely in Firebase.</li>
                  <li>You can delete your coaching history and results at any time from within the app.</li>
                  <li>We recommend obscuring or cropping out identifying information of other individuals before uploading screenshots.</li>
```

---

_****_

```diff
              <ul>
                  <li><strong>Dating App Content:</strong> Screenshots, messages, and profile information you upload for analysis and coaching purposes are temporarily processed but not stored on our servers.</li>
+                 <li><strong>Authentication Information:</strong> When you sign in using Google or Apple authentication, we receive and store basic account information such as your email address and account identifier in Firebase Authentication.</li>
                  <li><strong>Local Storage:</strong> Your coaching requests, AI suggestions, and interaction history are stored locally on your device and in your private iCloud storage. We do not have access to this data.</li>
-                 <li><strong>Credits:</strong> Information related to your credit usage is stored in your private iCloud account. We do not have access to this data.</li>
+                 <li><strong>Credits:</strong> Information related to your credit usage is stored in your Firebase account linked to your authentication profile.</li>
                  <li><strong>Anonymous Usage Data:</strong> We collect anonymous usage data through Firebase Analytics and Google Analytics to improve the app.</li>
                  <li><strong>Crash Reports:</strong> We collect anonymous crash reports through Firebase Crashlytics to enhance app stability.</li>
              <p>We may temporarily process your content for the following purposes:</p>
              <ul>
+                 <li>To authenticate your identity using Google or Apple sign-in.</li>
+                 <li>To maintain your account information and credit balance in Firebase.</li>
                  <li>To provide AI-powered dating coaching services using Gemini from Firebase SDK.</li>
                  <li>To temporarily process dating app screenshots and conversations to provide personalized recommendations.</li>
  
              <h2>Data Sharing</h2>
-             <p><strong>Since we do not collect or store personal data on our servers, we do not share your personal data with third parties.</strong> However, certain information may be processed as follows:</p>
+             <p><strong>We store limited personal data (authentication information and credit balance) on our servers through Firebase.</strong> This information may be processed as follows:</p>
              <ul>
                  <li><strong>Legal Obligations:</strong> When legally required, to respond to legal processes or protect the rights, property, and safety of others.</li>
-                 <li><strong>Third-Party Service Providers:</strong> Firebase Analytics, Google Analytics, and Firebase Crashlytics may collect anonymous usage and crash data according to their privacy policies.</li>
+                 <li><strong>Third-Party Service Providers:</strong> Firebase Authentication, Firebase Database, Firebase Analytics, Google Analytics, and Firebase Crashlytics may collect and store data according to their own privacy policies.</li>
                  <li><strong>AI Processing Services:</strong> We use Gemini AI from Firebase SDK to analyze your dating app content and generate coaching suggestions. Your content is temporarily processed and not stored by these services.</li>
              </ul>
              <p>We prioritize your privacy in the following ways:</p>
              <ul>
-                 <li><strong>We do not collect or store any personal data.</strong></li>
-                 <li>We do not maintain user accounts or authentication systems.</li>
-                 <li>Your credits and coaching history are stored only on your device and in your private iCloud storage.</li>
+                 <li><strong>We store only the minimal necessary personal data on our servers (email address, account identifier, and credit balance).</strong></li>
+                 <li>We use industry-standard security measures to protect your information stored in Firebase.</li>
+                 <li>We maintain user accounts and authentication systems only for necessary functionality using Firebase Authentication.</li>
+                 <li>Your coaching history is stored only on your device and in your private iCloud storage.</li>
                  <li>You can delete your coaching history and results at any time from within the app.</li>
                  <li>Content you upload for analysis is temporarily processed and not permanently stored by us.</li>
+                 <li>You can request deletion of your account data by contacting us.</li>
              </ul>
  
              <h2>User Rights</h2>
-             <p><strong>Since we do not collect or store personal data, many obligations under data protection laws do not apply to our application.</strong> However, you still have the following rights:</p>
+             <p><strong>Since we store limited personal data, you have the following rights regarding this data:</strong></p>
              <ul>
-                 <li><strong>Access and Portability:</strong> Since we don't collect and store your personal data, all your coaching data is already in your possession on your device and iCloud.</li>
-                 <li><strong>Correction and Deletion:</strong> You can delete your coaching history and results at any time from within the app.</li>
-                 <li><strong>Restriction of Processing and Objection:</strong> If you object to how your data is processed, you can stop using specific features of the app.</li>
+                 <li><strong>Access and Portability:</strong> You can request a copy of your personal data we store.</li>
+                 <li><strong>Correction and Deletion:</strong> You can request correction of inaccurate data or deletion of your account and associated data. You can also delete your coaching history and results at any time from within the app.</li>
+                 <li><strong>Restriction of Processing and Objection:</strong> You can request that we restrict processing of your data or object to processing in certain circumstances.</li>
              </ul>
  
  
              <h2>International Data Transfers</h2>
-             <p><strong>Since we do not collect or store personal data on our servers, there are no international transfers of your personal data by our app.</strong> However, the third-party services we use (Firebase Analytics, Google Analytics, Firebase Crashlytics) may transfer anonymous data according to their privacy policies.</p>
+             <p><strong>The limited personal data we store (authentication information and credit balance) in Firebase may be transferred to different countries where Firebase operates.</strong> These transfers are governed by appropriate safeguards as required by applicable laws. The third-party services we use (Firebase Authentication, Firebase Database, Firebase Analytics, Google Analytics, Firebase Crashlytics) may also transfer data according to their own privacy policies.</p>
  
              <h2>Credits Information</h2>
-             <p>Lenora AI Dating Coach offers free and premium credit packages with various features. Free users receive a limited number of credits per month, while premium subscribers receive additional credits monthly. Additional credit packages can also be purchased separately. Current credit amounts and pricing are displayed within the app and are subject to change. All purchase management, including cancellations, must be performed through the App Store.</p>
+             <p>Lenora AI Dating Coach offers free and premium credit packages with various features. Free users receive a limited number of credits per month, while premium subscribers receive additional credits monthly. Additional credit packages can also be purchased separately. Current credit amounts and pricing are displayed within the app and are subject to change. Your credit balance is stored in Firebase and linked to your authentication profile. All purchase management, including cancellations, must be performed through the App Store.</p>
  
              <h2>Data Retention and Deletion</h2>
-             <p>Since we do not store your personal data on our servers, there is no data retention period. All your coaching history and results are stored only on your device and in your private iCloud storage. You can delete this data at any time from within the app.</p>
+             <p>We store limited personal data (authentication information and credit balance) in Firebase for as long as you maintain an account with us. You can request deletion of this data at any time by contacting us. All your coaching history and results are stored only on your device and in your private iCloud storage. You can delete this data at any time from within the app.</p>
  
              <h2>Privacy Policy Updates</h2>
```

---

_****_

```diff
              <h2>AI Coaching Services</h2>
              <p>Lenora AI Dating Coach provides AI-powered analysis and suggestions for dating app profiles, conversations, and strategies using Gemini AI from Firebase SDK. The advice and suggestions provided are generated by artificial intelligence and should be used at your discretion. We do not guarantee specific outcomes or success in dating scenarios. The effectiveness of our suggestions may vary based on individual circumstances, preferences, and the accuracy of information provided.</p>
+ 
+             <h2>User Authentication and Accounts</h2>
+             <p>Lenora AI Dating Coach uses Firebase Authentication with Google and Apple sign-in options. By creating an account, you agree to provide accurate information and are responsible for maintaining the confidentiality of your account. You agree not to share your account credentials with others. We reserve the right to terminate accounts that violate our terms or policies. You may delete your account at any time by contacting us, though certain information may be retained as required by law or for legitimate business purposes.</p>
  
              <h2>User Content and Privacy</h2>
-             <p>When you upload dating app screenshots, conversations, or profile information to Lenora AI Dating Coach, this content is temporarily processed to provide our AI coaching services but is not permanently stored on our servers. <strong>We do not collect or store any personal data.</strong> The results of AI analysis are stored only on your device and in your private iCloud storage. We do not have access to this data. You can delete your coaching history and results at any time from within the app. We strongly recommend obscuring or removing identifying information of other individuals before uploading content to our app.</p>
+             <p>When you upload dating app screenshots, conversations, or profile information to Lenora AI Dating Coach, this content is temporarily processed to provide our AI coaching services but is not permanently stored on our servers. <strong>We store limited personal data (authentication information and credit balance) on our servers through Firebase.</strong> The results of AI analysis are stored only on your device and in your private iCloud storage. We do not have access to this data. You can delete your coaching history and results at any time from within the app. We strongly recommend obscuring or removing identifying information of other individuals before uploading content to our app.</p>
  
              <h2>Prohibited Activities</h2>
              
              <h2>Credits Information</h2>
-             <p>Lenora AI Dating Coach offers free and premium credit packages with various features. Free users receive a limited number of credits per month, while premium subscribers receive additional credits monthly. Additional credit packages can also be purchased separately. Current credit amounts and pricing are displayed within the app and are subject to change. All purchase management, including cancellations, must be performed through the App Store. You can manage and cancel your subscription directly from your App Store account settings.</p>
+             <p>Lenora AI Dating Coach offers free and premium credit packages with various features. Free users receive a limited number of credits per month, while premium subscribers receive additional credits monthly. Additional credit packages can also be purchased separately. Current credit amounts and pricing are displayed within the app and are subject to change. Your credit balance is stored in Firebase and linked to your authentication profile. All purchase management, including cancellations, must be performed through the App Store. You can manage and cancel your subscription directly from your App Store account settings.</p>
  
              <h2>Credit Usage and Storage</h2>
-             <p>Credits are consumed when using specific features of the app, such as profile analysis, message suggestions, or conversation strategies. Free credits refresh monthly, while premium subscription credits refresh with each billing cycle. Purchased credits do not expire. Unused free or premium subscription credits do not roll over to the next month. Information about your credits is stored privately in your iCloud account and is not accessible to us.</p>
+             <p>Credits are consumed when using specific features of the app, such as profile analysis, message suggestions, or conversation strategies. Free credits refresh monthly, while premium subscription credits refresh with each billing cycle. Purchased credits do not expire. Unused free or premium subscription credits do not roll over to the next month. Information about your credits is stored in your Firebase account linked to your authentication profile.</p>
  
              <h2>Data Storage</h2>
-             <p>Lenora AI Dating Coach does not maintain user accounts or authentication systems. <strong>We do not collect or store any personal data on our servers.</strong> Your credits and coaching history are stored only on your device and in your private iCloud storage. You have full control over this data and can delete it at any time from within the app. The only data we collect is anonymous usage analytics through Firebase Analytics and crash reports through Firebase Crashlytics to help us improve the app.</p>
+             <p>Lenora AI Dating Coach maintains user accounts and authentication systems using Firebase Authentication. <strong>We store limited personal data (authentication information and credit balance) on our servers through Firebase.</strong> Your coaching history is stored only on your device and in your private iCloud storage. You have full control over your coaching data and can delete it at any time from within the app. You can also request deletion of your account and associated data by contacting us. The only additional data we collect is anonymous usage analytics through Firebase Analytics and crash reports through Firebase Crashlytics to help us improve the app.</p>
  
              <h2>Disclaimer of Warranties</h2>
```

---

_****_

```diff
              <ul>
                  <li><strong>Flört Uygulaması İçeriği:</strong> Analiz ve koçluk amaçları için yüklediğiniz ekran görüntülerini, mesajları ve profil bilgilerini geçici olarak işleriz. Bu, flört uygulaması konuşmalarını, profil fotoğraflarını ve biyografileri içerebilir. Bu içerik sunucularımızda saklanmaz.</li>
+                 <li><strong>Kimlik Doğrulama Bilgileri:</strong> Google veya Apple kimlik doğrulamasını kullandığınızda, e-posta adresiniz ve hesap tanımlayıcınız gibi temel hesap bilgilerini alırız. Bu bilgiler Firebase Authentication'da saklanır.</li>
                  <li><strong>Yerel Depolama:</strong> Koçluk istekleriniz, AI önerileri ve etkileşim geçmişiniz cihazınızda ve özel iCloud depolamanızda yerel olarak saklanır. Bu verilere erişimimiz yoktur.</li>
-                 <li><strong>Krediler:</strong> Kredi kullanımınızla ilgili bilgiler özel iCloud hesabınızda saklanır. Bu verilere erişimimiz yoktur.</li>
+                 <li><strong>Krediler:</strong> Kredi kullanımınızla ilgili bilgiler Firebase hesabınızda saklanır. Bu veriler, kimlik doğrulama profilinize bağlıdır.</li>
                  <li><strong>Kullanım Verileri:</strong> Uygulamayı geliştirmek için Firebase Analytics ve Google Analytics aracılığıyla anonim kullanım verileri toplarız.</li>
                  <li><strong>Çökmeler Raporları:</strong> Uygulamanın kararlılığını artırmak için Firebase Crashlytics'i kullanarak anonim çökme raporlarını toplarız.</li>
              <p>Sizinle ilgili doğru bilgilere sahip olmak, size sorunsuz, verimli ve kişiselleştirilmiş bir deneyim sunmamızı sağlar. Özellikle, uygulama aracılığıyla topladığımız bilgileri şu amaçlarla kullanabiliriz:</p>
              <ul>
+                 <li>Google veya Apple girişi kullanarak kimliğinizi doğrulamak.</li>
+                 <li>Hesap bilgilerinizi ve kredi bakiyenizi Firebase'de tutmak.</li>
                  <li>Firebase SDK'dan Gemini kullanarak AI destekli flört koçluğu hizmetleri sunmak.</li>
                  <li>Kişiselleştirilmiş tavsiyeler sunmak için flört uygulaması ekran görüntülerini ve konuşmalarını geçici olarak işlemek.</li>
  
              <h2>Bilgilerinizi Paylaşma</h2>
-             <p><strong>Kişisel veri toplamadığımız ve sunucularımızda saklamadığımız için, kişisel verilerinizi üçüncü taraflarla paylaşmıyoruz.</strong> Ancak, belirli bilgiler aşağıdaki şekilde işlenebilir:</p>
+             <p><strong>Firebase Authentication ve Firebase Database aracılığıyla sunucularımızda sınırlı kişisel veri (kimlik doğrulama bilgileri ve kredi bakiyesi) saklıyoruz.</strong> Ancak, belirli bilgiler aşağıdaki şekilde işlenebilir:</p>
              <ul>
                  <li><strong>Yasa veya Hakları Koruma:</strong> Yasal bir zorunluluk olduğunda, yasal süreçlere yanıt vermek veya diğerlerinin haklarını, mülkünü ve güvenliğini korumak için gerekli bilgileri paylaşabiliriz.</li>
-                 <li><strong>Üçüncü Taraf Hizmet Sağlayıcılar:</strong> Firebase Analytics, Google Analytics ve Firebase Crashlytics kendi gizlilik politikalarına göre anonim kullanım ve çökme verilerini toplayabilir.</li>
+                 <li><strong>Üçüncü Taraf Hizmet Sağlayıcılar:</strong> Firebase Authentication, Firebase Database, Firebase Analytics, Google Analytics ve Firebase Crashlytics kendi gizlilik politikalarına göre veri toplayabilir ve saklayabilir.</li>
                  <li><strong>AI İşleme Hizmetleri:</strong> Flört uygulaması içeriğinizi analiz etmek ve koçluk önerileri oluşturmak için Firebase SDK'dan Gemini AI'yı kullanırız. İçeriğiniz geçici olarak işlenir ve bu hizmetler tarafından saklanmaz.</li>
              </ul>
              <p>Lenora AI Dating Coach aşağıdaki üçüncü taraf hizmetleri kullanır:</p>
              <ul>
+                 <li>Firebase Authentication: Google ve Apple girişi ile kullanıcı kimlik doğrulaması için</li>
+                 <li>Firebase Database: Kredi bilgilerinizi saklamak için</li>
                  <li>Firebase Analytics ve Google Analytics: Kullanım analizi için</li>
                  <li>Firebase Crashlytics: Çökme raporları için</li>
                  <li>Gemini AI (Firebase SDK): Flört içeriğini analiz etmek ve koçluk önerileri oluşturmak için</li>
-                 <li>Apple iCloud: Kredilerinizi ve koçluk geçmişinizi özel olarak saklamak için</li>
+                 <li>Apple iCloud: Koçluk geçmişinizi özel olarak saklamak için</li>
+                 <li>Google ve Apple Kimlik Doğrulama Hizmetleri: Kimlik doğrulaması için</li>
              </ul>
              <p>Bu hizmetler, kendi gizlilik politikalarına göre verilerinizi toplayabilir ve işleyebilir.</p>
              <p>Gizliliğinize aşağıdaki şekillerde öncelik veriyoruz:</p>
              <ul>
-                 <li><strong>Hiçbir kişisel veri toplamıyor veya saklamıyoruz.</strong></li>
-                 <li>Kullanıcı hesapları veya kimlik doğrulama sistemleri bulundurmuyoruz.</li>
-                 <li>Kredileriniz ve koçluk geçmişiniz yalnızca cihazınızda ve özel iCloud depolamanızda saklanır.</li>
+                 <li><strong>Sunucularımızda yalnızca gerekli minimum kişisel verileri (e-posta adresi, hesap tanımlayıcı ve kredi bakiyesi) saklıyoruz.</strong></li>
+                 <li>Firebase Authentication kullanarak yalnızca gerekli işlevsellik için kullanıcı hesaplarını ve kimlik doğrulama sistemlerini tutarız.</li>
+                 <li>Koçluk geçmişiniz yalnızca cihazınızda ve özel iCloud depolamanızda saklanır.</li>
                  <li>Koçluk geçmişinizi ve sonuçlarınızı uygulama içinden istediğiniz zaman silebilirsiniz.</li>
                  <li>Analiz için yüklediğiniz içerik geçici olarak işlenir ve tarafımızdan kalıcı olarak saklanmaz.</li>
+                 <li>Bizimle iletişime geçerek hesap verilerinizin silinmesini talep edebilirsiniz.</li>
              </ul>
  
              <h2>Uluslararası Veri Transferleri</h2>
-             <p>Kişisel veri toplamadığımız ve sunucularımızda saklamadığımız için, tarafımızdan kişisel verilerinizin uluslararası transferi yoktur. Ancak, kullandığımız üçüncü taraf hizmetler (Firebase Analytics, Google Analytics, Firebase Crashlytics) kendi gizlilik politikalarına göre anonim veri aktarabilir.</p>
+             <p><strong>Firebase'de sakladığımız sınırlı kişisel veriler (kimlik doğrulama bilgileri ve kredi bakiyesi), Firebase'in faaliyet gösterdiği farklı ülkelere aktarılabilir.</strong> Bu transferler, geçerli yasaların gerektirdiği uygun güvencelerle yönetilir. Kullandığımız üçüncü taraf hizmetler (Firebase Authentication, Firebase Database, Firebase Analytics, Google Analytics, Firebase Crashlytics) kendi gizlilik politikalarına göre veri aktarabilir.</p>
  
              <h2>GDPR Uyumluluğu</h2>
-             <p><strong>Kişisel veri toplamadığımız ve saklamadığımız için, GDPR kapsamındaki birçok yükümlülük uygulamamız için geçerli değildir.</strong> Ancak, Avrupa Ekonomik Alanı'ndaki (EEA) kullanıcılar yine de şu haklara sahiptir:</p>
+             <p><strong>Firebase aracılığıyla sunucularımızda sınırlı kişisel veri saklıyoruz.</strong> Avrupa Ekonomik Alanı'ndaki (EEA) kullanıcılar bu verilerle ilgili olarak aşağıdaki haklara sahiptir:</p>
              <ul>
-                 <li><strong>Erişim ve Taşınabilirlik:</strong> Kişisel verilerinizi toplamadığımız ve saklamadığımız için, tüm koçluk verileriniz zaten cihazınızda ve iCloud'da sizin elinizdedir.</li>
-                 <li><strong>Düzeltme ve Silme:</strong> Koçluk geçmişinizi ve sonuçlarınızı uygulama içinden istediğiniz zaman silebilirsiniz.</li>
-                 <li><strong>İşleme Kısıtlaması ve İtiraz:</strong> Verilerinizin nasıl işlendiğine itiraz ediyorsanız, uygulamanın belirli özelliklerini kullanmayı durdurabilirsiniz.</li>
+                 <li><strong>Erişim ve Taşınabilirlik:</strong> Sakladığımız kişisel verilerinizin bir kopyasını talep edebilirsiniz.</li>
+                 <li><strong>Düzeltme ve Silme:</strong> Yanlış verilerin düzeltilmesini veya hesabınızın ve ilişkili verilerin silinmesini talep edebilirsiniz. Ayrıca koçluk geçmişinizi ve sonuçlarınızı uygulama içinden istediğiniz zaman silebilirsiniz.</li>
+                 <li><strong>İşleme Kısıtlaması ve İtiraz:</strong> Belirli durumlarda verilerinizin işlenmesini kısıtlamamızı isteyebilir veya işleme itiraz edebilirsiniz.</li>
              </ul>
              <p>GDPR ile ilgili herhangi bir sorunuz için, lütfen bizimle <a href="mailto:lenora@ulassancak.com">lenora@ulassancak.com</a> adresinden iletişime geçin.</p>
  
              <h2>Kaliforniya Tüketici Gizliliği Yasası (CCPA) Uyumluluğu</h2>
-             <p><strong>Kişisel verileri toplamadığımız veya saklamadığımız için, CCPA hükümleri uygulamamız için geçerli değildir.</strong> Kaliforniya'da ikamet edenler, kullandığımız üçüncü taraf hizmetlerin (Firebase Analytics, Google Analytics, Firebase Crashlytics) kendi gizlilik politikalarına göre anonim verileri toplayabileceğini bilmelidir.</p>
+             <p><strong>CCPA kapsamında, Kaliforniya'da ikamet edenler kişisel bilgileriyle ilgili belirli haklara sahiptir. Sınırlı kişisel veri (kimlik doğrulama bilgileri ve kredi bakiyesi) sakladığımız için,</strong> hangi kişisel bilgileri topladığımızı bilme, kişisel bilgilerinizin silinmesini talep etme ve kişisel bilgilerin satışından vazgeçme hakkına sahipsiniz (ancak kişisel bilgileri satmıyoruz). Kaliforniya'da ikamet edenler, kullandığımız üçüncü taraf hizmetlerin kendi gizlilik politikalarına göre belirli verileri toplayabileceğini bilmelidir.</p>
  
              <h2>Flört İçeriği ve Gizlilik</h2>
                  <li>Yüklenen tüm ekran görüntüleri ve konuşmalar geçici olarak işlenir ve sunucularımızda saklanmaz.</li>
                  <li>AI analizinden elde edilen sonuçlar yalnızca cihazınızda ve özel iCloud depolamanızda saklanır.</li>
+                 <li>Kimlik doğrulama verileri ve kredi bilgileri Firebase'de güvenli bir şekilde saklanır.</li>
                  <li>Koçluk geçmişinizi ve sonuçlarınızı uygulama içinden istediğiniz zaman silebilirsiniz.</li>
                  <li>Ekran görüntüleri yüklemeden önce diğer kişilerin tanımlayıcı bilgilerini gizlemenizi veya kırpmanızı öneririz.</li>
```

---

_****_

Now I'll update the other files to ensure consistency across all language versions.

---

_****_

```diff
              <h2>AI Koçluk Hizmetleri</h2>
              <p>Lenora AI Dating Coach, Firebase SDK'dan Gemini AI kullanarak flört uygulaması profilleri, konuşmaları ve stratejileri için AI destekli analiz ve öneriler sunar. Sağlanan tavsiye ve öneriler yapay zeka tarafından oluşturulur ve kendi takdirinize göre kullanılmalıdır. Flört senaryolarında belirli sonuçları veya başarıyı garanti etmiyoruz. Önerilerimizin etkinliği, bireysel koşullara, tercihlere ve sağlanan bilgilerin doğruluğuna bağlı olarak değişebilir.</p>
+ 
+             <h2>Kullanıcı Kimlik Doğrulama ve Hesapları</h2>
+             <p>Lenora AI Dating Coach, Google ve Apple giriş seçenekleriyle Firebase Authentication kullanır. Bir hesap oluşturarak, doğru bilgi sağlamayı kabul edersiniz ve hesabınızın gizliliğini korumaktan sorumlusunuz. Hesap bilgilerinizi başkalarıyla paylaşmamayı kabul edersiniz. Şartlarımızı veya politikalarımızı ihlal eden hesapları sonlandırma hakkını saklı tutarız. Bizimle iletişime geçerek hesabınızı istediğiniz zaman silebilirsiniz, ancak belirli bilgiler yasaların gerektirdiği şekilde veya meşru iş amaçları için saklanabilir.</p>
  
              <h2>Kullanıcı İçeriği ve Gizlilik</h2>
-             <p>Lenora AI Dating Coach'a flört uygulaması ekran görüntüleri, konuşmaları veya profil bilgileri yüklediğinizde, bu içerik AI koçluk hizmetlerimizi sağlamak için geçici olarak işlenir ancak sunucularımızda kalıcı olarak saklanmaz. <strong>Hiçbir kişisel veri toplamıyor veya saklamıyoruz.</strong> AI analizi sonuçları yalnızca cihazınızda ve özel iCloud depolamanızda saklanır. Bu verilere erişimimiz yoktur. Koçluk geçmişinizi ve sonuçlarınızı uygulama içinden istediğiniz zaman silebilirsiniz. Uygulamaya içerik yüklemeden önce diğer kişilerin tanımlayıcı bilgilerini gizlemenizi veya kaldırmanızı şiddetle tavsiye ederiz.</p>
+             <p>Lenora AI Dating Coach'a flört uygulaması ekran görüntüleri, konuşmaları veya profil bilgileri yüklediğinizde, bu içerik AI koçluk hizmetlerimizi sağlamak için geçici olarak işlenir ancak sunucularımızda kalıcı olarak saklanmaz. <strong>Firebase aracılığıyla sunucularımızda sınırlı kişisel veri (kimlik doğrulama bilgileri ve kredi bakiyesi) saklıyoruz.</strong> AI analizi sonuçları yalnızca cihazınızda ve özel iCloud depolamanızda saklanır. Bu verilere erişimimiz yoktur. Koçluk geçmişinizi ve sonuçlarınızı uygulama içinden istediğiniz zaman silebilirsiniz. Uygulamaya içerik yüklemeden önce diğer kişilerin tanımlayıcı bilgilerini gizlemenizi veya kaldırmanızı şiddetle tavsiye ederiz.</p>
  
              <h2>Yasaklı Aktiviteler</h2>
              
              <h2>Kredi Bilgileri</h2>
-             <p>Lenora AI Dating Coach, çeşitli özelliklere sahip ücretsiz ve premium kredi paketleri sunar. Ücretsiz kullanıcılar aylık sınırlı sayıda kredi alırken, premium aboneler aylık ek krediler alır. Ek kredi paketleri ayrıca satın alınabilir. Güncel kredi miktarları ve fiyatlandırma uygulama içinde görüntülenir ve değişikliğe tabidir. Tüm satın alma yönetimi, iptaller dahil, App Store aracılığıyla yapılmalıdır. Aboneliğinizi App Store hesap ayarlarınızdan doğrudan yönetebilir ve iptal edebilirsiniz.</p>
+             <p>Lenora AI Dating Coach, çeşitli özelliklere sahip ücretsiz ve premium kredi paketleri sunar. Ücretsiz kullanıcılar aylık sınırlı sayıda kredi alırken, premium aboneler aylık ek krediler alır. Ek kredi paketleri ayrıca satın alınabilir. Güncel kredi miktarları ve fiyatlandırma uygulama içinde görüntülenir ve değişikliğe tabidir. Kredi bakiyeniz Firebase'de saklanır ve kimlik doğrulama profilinize bağlıdır. Tüm satın alma yönetimi, iptaller dahil, App Store aracılığıyla yapılmalıdır. Aboneliğinizi App Store hesap ayarlarınızdan doğrudan yönetebilir ve iptal edebilirsiniz.</p>
  
              <h2>Kredi Kullanımı ve Depolama</h2>
-             <p>Krediler, profil analizi, mesaj önerileri veya konuşma stratejileri gibi uygulamanın belirli özelliklerini kullanırken tüketilir. Ücretsiz krediler aylık olarak yenilenir, premium abonelik kredileri ise her fatura döngüsüyle yenilenir. Satın alınan krediler sona ermez. Kullanılmayan ücretsiz veya premium abonelik kredileri bir sonraki aya aktarılmaz. Kredilerinizle ilgili bilgiler özel iCloud hesabınızda saklanır ve bize erişilemez.</p>
+             <p>Krediler, profil analizi, mesaj önerileri veya konuşma stratejileri gibi uygulamanın belirli özelliklerini kullanırken tüketilir. Ücretsiz krediler aylık olarak yenilenir, premium abonelik kredileri ise her fatura döngüsüyle yenilenir. Satın alınan krediler sona ermez. Kullanılmayan ücretsiz veya premium abonelik kredileri bir sonraki aya aktarılmaz. Kredilerinizle ilgili bilgiler kimlik doğrulama profilinize bağlı olarak Firebase hesabınızda saklanır.</p>
  
              <h2>Veri Depolama</h2>
-             <p>Lenora AI Dating Coach, kullanıcı hesapları veya kimlik doğrulama sistemleri bulundurmaz. <strong>Sunucularımızda hiçbir kişisel veri toplamıyor veya saklamıyoruz.</strong> Kredileriniz ve koçluk geçmişiniz yalnızca cihazınızda ve özel iCloud depolamanızda saklanır. Bu veriler üzerinde tam kontrole sahipsiniz ve uygulama içinden istediğiniz zaman silebilirsiniz. Topladığımız tek veri, uygulamayı geliştirmemize yardımcı olmak için Firebase Analytics aracılığıyla anonim kullanım analizleri ve Firebase Crashlytics aracılığıyla çökme raporlarıdır.</p>
+             <p>Lenora AI Dating Coach, Firebase Authentication kullanarak kullanıcı hesaplarını ve kimlik doğrulama sistemlerini tutar. <strong>Firebase aracılığıyla sunucularımızda sınırlı kişisel veri (kimlik doğrulama bilgileri ve kredi bakiyesi) saklıyoruz.</strong> Koçluk geçmişiniz yalnızca cihazınızda ve özel iCloud depolamanızda saklanır. Koçluk verileriniz üzerinde tam kontrole sahipsiniz ve uygulama içinden istediğiniz zaman silebilirsiniz. Ayrıca bizimle iletişime geçerek hesabınızın ve ilişkili verilerin silinmesini talep edebilirsiniz. Topladığımız tek ek veri, uygulamayı geliştirmemize yardımcı olmak için Firebase Analytics aracılığıyla anonim kullanım analizleri ve Firebase Crashlytics aracılığıyla çökme raporlarıdır.</p>
  
              <h2>GDPR ve CCPA Uyumluluğu</h2>
```

---

_****_

```diff
              <ul>
                  <li><strong>Flört Uygulaması İçeriği:</strong> Analiz ve koçluk amaçları için yüklediğiniz ekran görüntüleri, mesajlar ve profil bilgileri geçici olarak işlenir ancak sunucularımızda saklanmaz.</li>
+                 <li><strong>Kimlik Doğrulama Bilgileri:</strong> Google veya Apple kimlik doğrulamasını kullandığınızda, e-posta adresiniz ve hesap tanımlayıcınız gibi temel hesap bilgilerini alır ve Firebase Authentication'da saklarız.</li>
                  <li><strong>Yerel Depolama:</strong> Koçluk istekleriniz, AI önerileri ve etkileşim geçmişiniz cihazınızda ve özel iCloud depolamanızda yerel olarak saklanır. Bu verilere erişimimiz yoktur.</li>
-                 <li><strong>Krediler:</strong> Kredi kullanımınızla ilgili bilgiler özel iCloud hesabınızda saklanır. Bu verilere erişimimiz yoktur.</li>
+                 <li><strong>Krediler:</strong> Kredi kullanımınızla ilgili bilgiler kimlik doğrulama profilinize bağlı olarak Firebase hesabınızda saklanır.</li>
                  <li><strong>Anonim Kullanım Verileri:</strong> Uygulamayı geliştirmek için Firebase Analytics ve Google Analytics aracılığıyla anonim kullanım verileri toplarız.</li>
                  <li><strong>Çökme Raporları:</strong> Uygulamanın kararlılığını artırmak için Firebase Crashlytics aracılığıyla anonim çökme raporları toplarız.</li>
              <p>İçeriğinizi geçici olarak aşağıdaki amaçlarla işleyebiliriz:</p>
              <ul>
+                 <li>Google veya Apple girişi kullanarak kimliğinizi doğrulamak.</li>
+                 <li>Hesap bilgilerinizi ve kredi bakiyenizi Firebase'de tutmak.</li>
                  <li>Firebase SDK'dan Gemini kullanarak AI destekli flört koçluğu hizmetleri sunmak.</li>
                  <li>Kişiselleştirilmiş tavsiyeler sunmak için flört uygulaması ekran görüntülerini ve konuşmalarını geçici olarak işlemek.</li>
  
              <h2>Veri Paylaşımı</h2>
-             <p><strong>Kişisel veri toplamadığımız ve sunucularımızda saklamadığımız için, kişisel verilerinizi üçüncü taraflarla paylaşmıyoruz.</strong> Ancak, belirli bilgiler aşağıdaki şekilde işlenebilir:</p>
+             <p><strong>Firebase Authentication ve Firebase Database aracılığıyla sunucularımızda sınırlı kişisel veri (kimlik doğrulama bilgileri ve kredi bakiyesi) saklıyoruz.</strong> Bu bilgiler aşağıdaki şekilde işlenebilir:</p>
              <ul>
                  <li><strong>Yasal Yükümlülükler:</strong> Yasal olarak gerektiğinde, yasal süreçlere yanıt vermek veya başkalarının haklarını, mülkiyetini ve güvenliğini korumak için.</li>
-                 <li><strong>Üçüncü Taraf Hizmet Sağlayıcıları:</strong> Firebase Analytics, Google Analytics ve Firebase Crashlytics kendi gizlilik politikalarına göre anonim kullanım ve çökme verilerini toplayabilir.</li>
+                 <li><strong>Üçüncü Taraf Hizmet Sağlayıcıları:</strong> Firebase Authentication, Firebase Database, Firebase Analytics, Google Analytics ve Firebase Crashlytics kendi gizlilik politikalarına göre veri toplayabilir ve saklayabilir.</li>
                  <li><strong>AI İşleme Hizmetleri:</strong> Flört uygulaması içeriğinizi analiz etmek ve koçluk önerileri oluşturmak için Firebase SDK'dan Gemini AI'yı kullanırız. İçeriğiniz geçici olarak işlenir ve bu hizmetler tarafından saklanmaz.</li>
              </ul>
              <p>Gizliliğinize aşağıdaki şekillerde öncelik veriyoruz:</p>
              <ul>
-                 <li><strong>Hiçbir kişisel veri toplamıyor veya saklamıyoruz.</strong></li>
-                 <li>Kullanıcı hesapları veya kimlik doğrulama sistemleri bulundurmuyoruz.</li>
-                 <li>Kredileriniz ve koçluk geçmişiniz yalnızca cihazınızda ve özel iCloud depolamanızda saklanır.</li>
+                 <li><strong>Sunucularımızda yalnızca gerekli minimum kişisel verileri (e-posta adresi, hesap tanımlayıcı ve kredi bakiyesi) saklıyoruz.</strong></li>
+                 <li>Firebase'de saklanan bilgilerinizi korumak için endüstri standardı güvenlik önlemleri kullanıyoruz.</li>
+                 <li>Firebase Authentication kullanarak yalnızca gerekli işlevsellik için kullanıcı hesaplarını ve kimlik doğrulama sistemlerini tutarız.</li>
+                 <li>Koçluk geçmişiniz yalnızca cihazınızda ve özel iCloud depolamanızda saklanır.</li>
                  <li>Koçluk geçmişinizi ve sonuçlarınızı uygulama içinden istediğiniz zaman silebilirsiniz.</li>
                  <li>Analiz için yüklediğiniz içerik geçici olarak işlenir ve tarafımızdan kalıcı olarak saklanmaz.</li>
+                 <li>Bizimle iletişime geçerek hesap verilerinizin silinmesini talep edebilirsiniz.</li>
              </ul>
  
              <h2>Kullanıcı Hakları</h2>
-             <p><strong>Kişisel veri toplamadığımız ve saklamadığımız için, veri koruma yasaları kapsamındaki birçok yükümlülük uygulamamız için geçerli değildir.</strong> Ancak, yine de aşağıdaki haklara sahipsiniz:</p>
+             <p><strong>Sınırlı kişisel veri sakladığımız için, bu verilerle ilgili aşağıdaki haklara sahipsiniz:</strong></p>
              <ul>
-                 <li><strong>Erişim ve Taşınabilirlik:</strong> Kişisel verilerinizi toplamadığımız ve saklamadığımız için, tüm koçluk verileriniz zaten cihazınızda ve iCloud'da sizin elinizdedir.</li>
-                 <li><strong>Düzeltme ve Silme:</strong> Koçluk geçmişinizi ve sonuçlarınızı uygulama içinden istediğiniz zaman silebilirsiniz.</li>
-                 <li><strong>İşleme Kısıtlaması ve İtiraz:</strong> Verilerinizin nasıl işlendiğine itiraz ediyorsanız, uygulamanın belirli özelliklerini kullanmayı durdurabilirsiniz.</li>
+                 <li><strong>Erişim ve Taşınabilirlik:</strong> Sakladığımız kişisel verilerinizin bir kopyasını talep edebilirsiniz.</li>
+                 <li><strong>Düzeltme ve Silme:</strong> Yanlış verilerin düzeltilmesini veya hesabınızın ve ilişkili verilerin silinmesini talep edebilirsiniz. Ayrıca koçluk geçmişinizi ve sonuçlarınızı uygulama içinden istediğiniz zaman silebilirsiniz.</li>
+                 <li><strong>İşleme Kısıtlaması ve İtiraz:</strong> Belirli durumlarda verilerinizin işlenmesini kısıtlamamızı isteyebilir veya işleme itiraz edebilirsiniz.</li>
              </ul>
  
  
              <h2>Uluslararası Veri Aktarımları</h2>
-             <p><strong>Kişisel veri toplamadığımız ve sunucularımızda saklamadığımız için, uygulamamız tarafından kişisel verilerinizin uluslararası aktarımı yoktur.</strong> Ancak, kullandığımız üçüncü taraf hizmetler (Firebase Analytics, Google Analytics, Firebase Crashlytics) kendi gizlilik politikalarına göre anonim veri aktarabilir.</p>
+             <p><strong>Firebase'de sakladığımız sınırlı kişisel veriler (kimlik doğrulama bilgileri ve kredi bakiyesi), Firebase'in faaliyet gösterdiği farklı ülkelere aktarılabilir.</strong> Bu transferler, geçerli yasaların gerektirdiği uygun güvencelerle yönetilir. Kullandığımız üçüncü taraf hizmetler (Firebase Authentication, Firebase Database, Firebase Analytics, Google Analytics, Firebase Crashlytics) kendi gizlilik politikalarına göre veri aktarabilir.</p>
  
              <h2>Kredi Bilgileri</h2>
-             <p>Lenora AI Dating Coach, çeşitli özelliklere sahip ücretsiz ve premium kredi paketleri sunar. Ücretsiz kullanıcılar aylık sınırlı sayıda kredi alırken, premium aboneler aylık ek krediler alır. Ek kredi paketleri ayrıca satın alınabilir. Güncel kredi miktarları ve fiyatlandırma uygulama içinde görüntülenir ve değişikliğe tabidir. Tüm satın alma yönetimi, iptaller dahil, App Store aracılığıyla yapılmalıdır.</p>
+             <p>Lenora AI Dating Coach, çeşitli özelliklere sahip ücretsiz ve premium kredi paketleri sunar. Ücretsiz kullanıcılar aylık sınırlı sayıda kredi alırken, premium aboneler aylık ek krediler alır. Ek kredi paketleri ayrıca satın alınabilir. Güncel kredi miktarları ve fiyatlandırma uygulama içinde görüntülenir ve değişikliğe tabidir. Kredi bakiyeniz Firebase'de saklanır ve kimlik doğrulama profilinize bağlıdır. Tüm satın alma yönetimi, iptaller dahil, App Store aracılığıyla yapılmalıdır.</p>
  
              <h2>Veri Saklama ve Silme</h2>
-             <p>Sunucularımızda kişisel verilerinizi saklamadığımız için, bir veri saklama süresi yoktur. Tüm koçluk geçmişiniz ve sonuçlarınız yalnızca cihazınızda ve özel iCloud depolamanızda saklanır. Bu verileri uygulama içinden istediğiniz zaman silebilirsiniz.</p>
+             <p>Firebase'de sınırlı kişisel veri (kimlik doğrulama bilgileri ve kredi bakiyesi) bizimle hesabınızı koruduğunuz sürece saklarız. Bizimle iletişime geçerek bu verilerin silinmesini istediğiniz zaman talep edebilirsiniz. Tüm koçluk geçmişiniz ve sonuçlarınız yalnızca cihazınızda ve özel iCloud depolamanızda saklanır. Bu verileri uygulama içinden istediğiniz zaman silebilirsiniz.</p>
  
              <h2>Gizlilik Politikası Güncellemeleri</h2>
```

---

_****_

I've made the necessary updates to all the privacy policy, KVKK, and terms documents in English and Turkish to reflect the changes in your app. Here's a summary of the key changes:

1. Added Firebase Authentication with Google and Apple sign-in:
   - Updated information about what user data is collected and stored
   - Added sections about authentication information storage
   - Added user account management details

2. Changed credit storage from iCloud to Firebase:
   - Updated all references to credit storage to indicate they're now stored in Firebase
   - Clarified that credits are linked to authentication profiles
   - Added information about how users can access and manage this data

3. Updated data sharing sections:
   - Added Firebase Authentication and Firebase Database to the list of third-party services
   - Modified the privacy statements to acknowledge limited personal data storage

4. Updated user rights sections:
   - Added information about requesting account deletion
   - Modified data access and portability rights to reflect the new storage approach

5. Updated international data transfer sections:
   - Added information about possible transfers of authentication and credit data

These changes have been consistently applied across all language versions of your privacy policy, KVKK, and terms documents, maintaining the same meaning and level of detail in each.

---

_**User**_

we dont mention revenuecat to manage the subscription and purchasing credits at all in any page. we should add.

---

_**Assistant**_



---



---

