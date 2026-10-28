<div align="center">
  <h1>🏢 DARY | منصة داري لإدارة العقارات</h1>
  <p>Advanced Real Estate Business Analysis Dashboard | لوحة تحليل أعمال عقارية متقدمة</p>

  <p>
    <a href="#english">🇬🇧 English</a> • <a href="#arabic">🇸🇦 العربية</a>
  </p>

  ![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
  ![DAX](https://img.shields.io/badge/DAX-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
  ![Data Analysis](https://img.shields.io/badge/Data%20Analysis-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)
</div>

---

<a id="english"></a>
## 🇬🇧 English Documentation

### 📌 About the Project
**DARY – Real Estate Management Platform** is a comprehensive business intelligence dashboard built using **Power BI**, designed to provide real estate companies and property managers with a full analytical view of their operations. The report covers all aspects of property management — from building occupancy and tenant contracts to invoice collection, utility meter readings, and maintenance service tracking — all in one centralized, interactive platform. The goal is to replace fragmented data with clear KPIs and actionable insights that drive smarter decisions.

### 🌟 Report Pages & Features

- **🏠 Home Page (Navigation Hub):** A visually rich landing page with quick-access navigation buttons to all report sections, displaying top-level KPIs at a glance (total contracts, invoices, collection rate, maintenance requests, and overdue amounts).
- **📊 Executive Summary:** A high-level overview combining all critical metrics: total payments (5.84M SAR), collection rate (0.55), overdue amounts (1.22M SAR), total invoices (7,419), total contracts (212), and a live operations log.
- **🏗️ Properties & Units:** Detailed breakdown of 20 buildings with 226 units across multiple cities. Includes unit type distribution (Studio, Duplex, Penthouse, Apartment, Roof), occupancy status chart, and average monthly rent (6.50K SAR).
- **📝 Contracts & Tenants:** Full contract management view for 212 contracts and 152 tenants. Tracks contract start date trends (2023–2026), contract status breakdown (Active, Renewed, Expired, Cancelled, Suspended), and unit-level details.
- **💰 Invoices & Collection:** Financial tracking dashboard with total invoices, collection rate (0.52), overdue amounts (41.60K), invoice status distribution (Paid, Overdue, Suspended, Cancelled), monthly payment trends, and payment method breakdown (Cheque, Cash, Credit Card, E-Wallet, Bank Transfer).
- **🛠️ Maintenance & Services:** Operational dashboard for 709 total maintenance requests with priority levels, request status (Open: 93 | Closed: 401 | In Progress | Cancelled), average repair time (33 hours), and repair cost trends over time.
- **⚡ Meter Readings:** Utility consumption tracking for 190 units with 1,989 reading records. Includes previous vs. current reading comparison, total consumption (395K), and monthly consumption trends per unit.
- **✅ Data Quality:** Cross-validation dashboard covering all data sources — units (226), readings (1,989), payments (4,277), invoices (780), and operations (3,200) — with invoice and meter reading verification panels for data integrity checks.

### 📐 Data Model
The report is built on a **Star Schema** data model consisting of:
- **Fact Tables:** `Fact_Operations`, `Fact_Invoice`, `Fact_Payments`, `Fact_Maintenance`, `Fact_MonthlyReading`
- **Dimension Tables:** `Dim_Building`, `Dim_Unit`, `Dim_Tenant`, `Dim_Contract`, `Dim_Date`
- **Supporting:** `Parameters` table for dynamic field switching

### 📏 DAX Measures
The report leverages a rich set of **DAX measures** covering:
- **Basic KPIs:** Total contracts, total invoices, collection rate, total paid, overdue amounts, occupancy rate, active contract rate
- **Advanced Time Intelligence:** Month-to-date payments, year-to-date invoices, previous month total payments, monthly change in payments, average unit consumption

### 🗂️ Repository Contents

| File | Description |
|------|-------------|
| `مشروع ادارة المباني - تحليل الاعمال .pbix` | Main Power BI report file |
| `صور المشروع/1-الرئيسية.jpg` | Home / Navigation page screenshot |
| `صور المشروع/مقاييس DAX 2-المتقدمه.jpg` | Advanced DAX measures screenshot |
| `صور المشروع/مقاييس DAX 3-الأساسية.jpg` | Basic DAX measures screenshot |
| `صور المشروع/4-modeling.jpg` | Data model diagram screenshot |
| `صور المشروع/الملخص 5-التنفيذي.jpg` | Executive Summary page screenshot |
| `صور المشروع/العقارات 6-والوحدات.jpg` | Properties & Units page screenshot |
| `صور المشروع/العقود 7-والمستأجرون.jpg` | Contracts & Tenants page screenshot |
| `صور المشروع/الفواتير 8-والتحصيل.jpg` | Invoices & Collection page screenshot |
| `صور المشروع/الصيانة -9والخدمات.jpg` | Maintenance & Services page screenshot |
| `صور المشروع/قراءات -10العدادات.jpg` | Meter Readings page screenshot |
| `صور المشروع/جودة البيانات-11.jpg` | Data Quality page screenshot |
| `صور المشروع/الجداول و ربط العلاقات .jpg` | Tables & Relationships screenshot |

### ⚙️ How to Open

1. **Prerequisites:**
   - Install **Microsoft Power BI Desktop** (latest version recommended).
2. **Open the Report:**
   - Download or clone this repository.
   - Open `مشروع ادارة المباني - تحليل الاعمال .pbix` using Power BI Desktop.
3. **Explore:**
   - Navigate between report pages using the home navigation buttons or the page tabs at the bottom.
   - Use slicers (building, year, unit, invoice status) to filter and drill into the data.

### 📸 Dashboard Preview

| Page | Screenshot |
|------|------------|
| 🏠 Home | ![Home](صور%20المشروع/1-الرئيسية.jpg) |
| 📊 Executive Summary | ![Summary](صور%20المشروع/الملخص%205-التنفيذي.jpg) |
| 🏗️ Properties & Units | ![Properties](صور%20المشروع/العقارات%206-والوحدات.jpg) |
| 📝 Contracts & Tenants | ![Contracts](صور%20المشروع/العقود%207-والمستأجرون.jpg) |
| 💰 Invoices & Collection | ![Invoices](صور%20المشروع/الفواتير%208-والتحصيل.jpg) |
| 🛠️ Maintenance & Services | ![Maintenance](صور%20المشروع/الصيانة%20-9والخدمات.jpg) |
| ⚡ Meter Readings | ![Meters](صور%20المشروع/قراءات%20-10العدادات.jpg) |
| ✅ Data Quality | ![Quality](صور%20المشروع/جودة%20البيانات-11.jpg) |

<br>

---

<a id="arabic"></a>
## 🇸🇦 دليل الاستخدام (العربية)

### 📌 عن المشروع
**منصة داري لإدارة العقارات** هي لوحة تحليل أعمال شاملة مبنية باستخدام **Power BI**، صُممت لتمنح شركات العقارات ومديري المباني رؤية تحليلية متكاملة لكافة عملياتهم. يغطي التقرير جميع جوانب إدارة العقارات — من إشغال المباني وعقود المستأجرين إلى تحصيل الفواتير وقراءات عدادات الخدمات وتتبع طلبات الصيانة — كل ذلك في منصة تفاعلية مركزية واحدة. الهدف هو تحويل البيانات المتفرقة إلى مؤشرات أداء واضحة ورؤى قابلة للتنفيذ تدعم اتخاذ قرارات أذكى.

### 🌟 صفحات التقرير والمميزات

- **🏠 الصفحة الرئيسية (مركز التنقل):** صفحة بصرية جذابة توفر أزرار تنقل سريع لجميع أقسام التقرير، مع عرض أبرز مؤشرات الأداء (إجمالي العقود، الفواتير، نسبة التحصيل، طلبات الصيانة، والمتأخرات).
- **📊 الملخص التنفيذي:** نظرة شاملة عالية المستوى تجمع كافة المقاييس الحرجة: إجمالي المدفوعات (5.84M ريال)، نسبة التحصيل (0.55)، إجمالي المتأخرات (1.22M ريال)، إجمالي الفواتير (7,419)، وسجل العمليات الحي.
- **🏗️ العقارات والوحدات:** تحليل تفصيلي لـ 20 مبنى و226 وحدة في مدن متعددة. يشمل توزيع أنواع الوحدات (استوديو، دوبلكس، بنتهاوس، شقة، روف)، ومخطط حالة الإشغال، ومتوسط الإيجار الشهري (6,500 ريال).
- **📝 العقود والمستأجرون:** إدارة شاملة لـ 212 عقدًا و152 مستأجرًا. يتتبع اتجاهات إنشاء العقود (2023-2026)، وتوزيع حالات العقود (ساري، مجدد، منتهي، ملغى، معلق).
- **💰 الفواتير والتحصيل:** لوحة متابعة مالية تشمل إجمالي الفواتير، نسبة التحصيل (0.52)، المتأخرات (41.60K)، توزيع حالات الفواتير، اتجاهات الدفع الشهرية، وتوزيع طرق الدفع (شيك، نقدي، بطاقة ائتمان، محفظة إلكترونية، تحويل بنكي).
- **🛠️ الصيانة والخدمات:** لوحة تشغيلية لـ 709 طلب صيانة مع مستويات الأولوية وحالات الطلبات (مفتوحة: 93 | مغلقة: 401 | قيد التنفيذ | ملغاة)، ومتوسط وقت الإصلاح (33 ساعة)، واتجاهات تكاليف الإصلاح.
- **⚡ قراءات العدادات:** تتبع استهلاك الخدمات لـ 190 وحدة بـ 1,989 سجل قراءة. يشمل مقارنة القراءة السابقة والحالية، وإجمالي الاستهلاك (395K)، واتجاهات الاستهلاك الشهري.
- **✅ جودة البيانات:** لوحة تحقق شاملة تغطي جميع مصادر البيانات — الوحدات (226)، القراءات (1,989)، الدفعات (4,277)، الفواتير (780)، والعمليات (3,200) — مع لوحات تحقق من الفواتير وقراءات العدادات.

### 📐 نموذج البيانات
يعتمد التقرير على نموذج بيانات **Star Schema** يتكون من:
- **جداول الحقائق:** `Fact_Operations` ، `Fact_Invoice` ، `Fact_Payments` ، `Fact_Maintenance` ، `Fact_MonthlyReading`
- **جداول الأبعاد:** `Dim_Building` ، `Dim_Unit` ، `Dim_Tenant` ، `Dim_Contract` ، `Dim_Date`
- **داعم:** جدول `Parameters` للتبديل الديناميكي بين الحقول

### 📏 مقاييس DAX
يستخدم التقرير مجموعة غنية من **مقاييس DAX** تشمل:
- **المؤشرات الأساسية:** إجمالي العقود، إجمالي الفواتير، نسبة التحصيل، إجمالي المدفوعات، المتأخرات، نسبة الإشغال، نسبة العقود النشطة
- **ذكاء الوقت المتقدم:** المدفوعات منذ بداية الشهر، الفواتير منذ بداية السنة، إجمالي مدفوعات الشهر السابق، التغير الشهري في المدفوعات، متوسط استهلاك الوحدة

### 🗂️ محتويات المستودع

| الملف | الوصف |
|-------|--------|
| `مشروع ادارة المباني - تحليل الاعمال .pbix` | ملف تقرير Power BI الرئيسي |
| `صور المشروع/1-الرئيسية.jpg` | لقطة شاشة صفحة التنقل الرئيسية |
| `صور المشروع/مقاييس DAX 2-المتقدمه.jpg` | لقطة شاشة مقاييس DAX المتقدمة |
| `صور المشروع/مقاييس DAX 3-الأساسية.jpg` | لقطة شاشة مقاييس DAX الأساسية |
| `صور المشروع/4-modeling.jpg` | لقطة شاشة مخطط نموذج البيانات |
| `صور المشروع/الملخص 5-التنفيذي.jpg` | لقطة شاشة صفحة الملخص التنفيذي |
| `صور المشروع/العقارات 6-والوحدات.jpg` | لقطة شاشة صفحة العقارات والوحدات |
| `صور المشروع/العقود 7-والمستأجرون.jpg` | لقطة شاشة صفحة العقود والمستأجرين |
| `صور المشروع/الفواتير 8-والتحصيل.jpg` | لقطة شاشة صفحة الفواتير والتحصيل |
| `صور المشروع/الصيانة -9والخدمات.jpg` | لقطة شاشة صفحة الصيانة والخدمات |
| `صور المشروع/قراءات -10العدادات.jpg` | لقطة شاشة صفحة قراءات العدادات |
| `صور المشروع/جودة البيانات-11.jpg` | لقطة شاشة صفحة جودة البيانات |
| `صور المشروع/الجداول و ربط العلاقات .jpg` | لقطة شاشة الجداول والعلاقات |

### ⚙️ خطوات الفتح والاستخدام

1. **المتطلبات الأساسية:**
   - تثبيت **Microsoft Power BI Desktop** (يُنصح بأحدث إصدار).
2. **فتح التقرير:**
   - قم بتنزيل أو استنساخ هذا المستودع.
   - افتح الملف `مشروع ادارة المباني - تحليل الاعمال .pbix` باستخدام Power BI Desktop.
3. **الاستكشاف:**
   - تنقل بين صفحات التقرير عبر أزرار التنقل في الصفحة الرئيسية أو تبويبات الصفحات في الأسفل.
   - استخدم أدوات التصفية (المبنى، السنة، الوحدة، حالة الفاتورة) للتعمق في البيانات.

### 📸 معاينة لوحة التحكم

| الصفحة | لقطة الشاشة |
|---------|-------------|
| 🏠 الرئيسية | ![الرئيسية](صور%20المشروع/1-الرئيسية.jpg) |
| 📊 الملخص التنفيذي | ![الملخص](صور%20المشروع/الملخص%205-التنفيذي.jpg) |
| 🏗️ العقارات والوحدات | ![العقارات](صور%20المشروع/العقارات%206-والوحدات.jpg) |
| 📝 العقود والمستأجرون | ![العقود](صور%20المشروع/العقود%207-والمستأجرون.jpg) |
| 💰 الفواتير والتحصيل | ![الفواتير](صور%20المشروع/الفواتير%208-والتحصيل.jpg) |
| 🛠️ الصيانة والخدمات | ![الصيانة](صور%20المشروع/الصيانة%20-9والخدمات.jpg) |
| ⚡ قراءات العدادات | ![القراءات](صور%20المشروع/قراءات%20-10العدادات.jpg) |
| ✅ جودة البيانات | ![الجودة](صور%20المشروع/جودة%20البيانات-11.jpg) |

<br>

---

<div align="center">
  <p>Built by <b>Eng. Waleed Mohsen Al-Ansi</b></p>
  <p><b>برمجة وتطوير م. وليد محسن الآنسي</b></p>
  <p>📞 +967 773 157 823</p>
  <p>© 2026 DARY – Real Estate Management Platform. All Rights Reserved.</p>
  <p>© ٢٠٢٦ منصة داري لإدارة العقارات. جميع الحقوق محفوظة.</p>
</div>