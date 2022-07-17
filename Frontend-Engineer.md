# Frontend Engineer

# Uraian Kerja


1. **Melakukan perancangan spesifikasi teknis, membuat kode program, serta peer code review.**

   
   1. Membuat kode program *frontend*.
   2. Memasang *coding tools* standar, seperti *code linter* (Eslint plugin), *error logging* (Sentry), dan *code metric* (SonarQube).
   3. Membuat dan menjalankan tes, berupa *unit testing* (Jest + Mocha/Chai) terhadap kode program yang telah dibuat.
   4. Melakukan *performance measurement* menggunakan Lighthouse, Pagespeed Insight, New Relic (Web Vital).
   5. Mengikuti standar penggunaan Git dan strategi *branching (Git Flow or Trunk Based)*.
   6. Mengikuti standar prosedur Merge Request (MR) atau Pull Request (PR).
   7. Mengimplementasikan *pre-integration test* seperti *unit testing*, *code linter,* dan *deploy preview* pada proses MR atau PR.

      
2. **Melakukan instalasi/deploy aplikasi ke server.**

   
   1. Menentukan strategi *deployment* per *environment* per projek, antara *managed service* (Netlify) atau *self-managed* sesuai environments yang sesuai 
   2. Melakukan konfigurasi *deployment* sesuai strategi yang digunakan, antara lain:

      1. Membuat *docker image* sesuai standar dan menyimpan *image* tersebut pada *private* atau *public registry*, untuk dideploy pada environment yang sesuai.
      2. Membuat CI/CD *script* sesuai standar.
      3. Konfigurasi Github Webhook untuk CapRover/Pipeline.
   
   3. Bersama DevOps melakukan *pointing* terhadap *domain* dan *setup* SSL *certificates*.

      
3. **Membuat dokumentasi teknis mengenai aplikasi yang dikembangkan.**

   
   1. Membuat README.md pada *root folder* kode program.
   2. Membuat dokumentasi berisikan penjelasan *variable/function/module* kode program (JSDoc).
   3. Membuat [Quick Start Development](/doc/technical-documentation-Nhkc36EFII) di Wiki produk/projek masing-masing.
   4. Mendokumentasikan hasil *performance measurement* *report*.

      
4. **Melakukan riset dan meningkatkan kapasitas serta pengetahuan kepada organisasi.**

   a. Mengoptimasi kode program berdasarkan hasil *performance measurement* (Web Vital).

   b. Meningkatkan *code maintainability*, *code coverage*, *reliability,* mengurangi *technical debt* berdasarkan hasil analisis SonarQube.

   c. Membuat *reusable code* dalam bentuk *module, library, package, template,* dan/atau *boilerplate*.

   d. Sharing session (artikel, video, webinar, tech-talk, mentoring).

# Kompetensi / Technical Expertise


 1. **Menguasai bahasa pemrograman serta development tools yang dibutuhkan.**

    
     1. Cara kerja internet (HTTP, DNS, *browser, hosting, domain*)
     2. Dasar-dasar HTML, antara lain semantik HTML, pembuatan form dan validasi, *accesibility*, dan SEO (Search Engine Optimization).
     3. Cara kerja dan basic backend knowledge (routing, model, request-response cycle).
     4. Stateful vs Stateless services.
     5. Dasar-dasar CSS dalam pembuatan *layout*, meliputi desain responsif.
     6. Dasar-dasar penggunaan Javascript dalam *browser*, meliputi manipulasi DOM, AJAX, *handling event*, *cookies, local storage,* dan *session storage*.
     7. Dasar-dasar penggunaan Javascript secara umum, seperti *hoisting, scope,* dan *prototype.*
     8. *Source code editor* (IDE), misalnya Visual Studio Code.
     9. Tools dokumentasi API Postman.
    10. Source code version control (Git) untuk sehari-hari dan secara *advanced*.

        
 2. **Menguasai teknik perancangan sistem, implementasi, dan evaluasi, berdasarkan *business/user requirements*.**

    
    1. Implementasi UI design.
    2. Memilih arsitektur dan teknologi stack yang sesuai kebutuhan.

       
 3. **Menguasai teknik manajemen *package* dalam pengembangan aplikasi.**

    
    1. Memiliki pemahaman perbedaan / use case NPM dan Yarn.
    2. Mampu membuat packages eksternal di NPM Library.

       
 4. **Menguasai teknik penggunaan Javascript secara mendalam, meliputi front-end development framework berikut build tools yang diperlukan.**

    
     1. NodeJS.
     2. *Front-end development framework* (VueJS, NuxtJS, ReactJS).
     3. CSS *framework* (Bootstrap, TailwindCSS).
     4. Prinsip/konvensi arsitektur CSS, misalnya BEM (Block-Element-Modifier).
     5. Penggunaan CSS Preprocessors and Postprocessors, misalnya SASS dan PostCSS.
     6. UI *library* (seperti Vuetify).
     7. Merancang dan membangun komponen antarmuka berdasarkan prinsip *modularity* dan *reusability*.
     8. *Route management* (VueRouter).
     9. *State management* (Vuex).
    10. HTTP *request* (fetch, axios).
    11. API *documentation tools* (Postman).
    12. *Authentication, authorization*, SSO, dan *Access management.*
    13. *Web security knowledge*.
    14. *Server-side rendering (SSR)*.
    15. Client-side rendering (CSR).
    16. Static site generator (SSG)
    17. *Code linter* (ESLint, Prettier, .editorconfig)
    18. *Task runner* (NPM *scripts*).
    19. *Module bundlers* (Webpack).
    20. Mampu mengimplementasikan teknologi Progressive Web Apps (PWA)

        
 5. **Menguasai teknik perancangan dan melakukan pengujian dengan berbagai metode aplikasi testing.**

    
    1. Membuat dan menjalankan *unit test* (Jest, Mocha, Chai).
    2. Membuat dan menjalankan *end-to-end* (E2E) *test* (Cypress, Nightwatch).

       
 6. **Menguasai teknik membuat dokumentasi teknis pada fitur/aplikasi yang dibangun secara jelas dan detail.**

    
    1. Code doc-blocks.
    2. Markdown format.
    3. Technical documentation, README.md

       
 7. **Menguasai teknik instalasi dan pemeliharaan aplikasi pada *server*.**

    
    1. Konfigurasi *multi-environment* *(development*, *staging, production*).
    2. Membuat dan menjalankan CI/CD *script*.
    3. Membuat Dockerfile.
    4. Penggunaan *managed-service* (Netlify).
    5. Penggunaan (semi) *self-managed service* (CapRover).
    6. Setup Sentry error logging.
    7. Setup performance monitor (New Relic)

       
 8. **Menguasai teknik evaluasi dan meningkatkan metric software standards.**

    
    1. Memahami metrik-metrik standar aplikasi, seperti *Time to First Byte*, *Time to* *First Contentful Paint*, Load Time, dsb.
    2. Pengukuran performansi aplikasi menggunakan *tools* seperti Lighthouse, Pagespeed Insights.

       
 9. **Menguasai teknik *troubleshooting* dan *debugging* aplikasi, serta memperbaiki *error.***

    
    1. *Debugging tools,* antara lain *logger*/*console* pada *browser*, *terminal/shell*, dan IDE.
    2. Instalasi *tools* untuk *error logging* (Sentry).

    
10. **Menguasai teknik *peer code review*.**

    
    1. Melakukan code review 

# Roadmap & Learning Path

Source: <https://roadmap.sh/frontend>




