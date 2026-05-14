# Technical Writing & API Documentation Portfolio: Food Map SaaS

## Overview

This repository features a comprehensive documentation suite for **Food Map**, a hyper-local SaaS platform designed to connect small-to-medium retail providers (supermarkets and hypermarkets) with regional residents. As a Senior English Editor and Technical Content Developer, I have designed this documentation to bridge the gap between complex engineering requirements and user-centric business logic.

## Developer Documentation (API Reference)

### **1. Inventory Management API**

`POST /v1/inventory/items`

Allows registered providers to programmatically add new food or beverage items to their digital storefront.

**Request Example (JSON):**

```json
{
  "provider_id": "STORE-One",
  "item_name": "Doha Rice (1kg)",
  "category": "items",
  "price": 50,
  "stock_count": 50,
  "is_available": true,
  "phone": "+2011###",
  "address": {
    "street": "90 North Road",
    "city": "New Cairo",
    "country": "Egypt"
}
}

```

**Field Definitions:**

* **`provider_id`**: Unique vendor identifier for the SaaS platform.
* **`price`**: Selling price in local currency (e.g., EGP).
* **`is_available`**: A boolean flag indicating if the item is ready for local search.

### **2. Resident Request API**

`POST /v1/requests`

Enables residents to notify nearby providers of high-demand items not currently in stock, facilitating better inventory planning for vendors.

**Request Example (JSON):**

```json
{
  "resident_id": "RES-5521",
  "requested_item": "Gluten-Free Flour",
  "preferred_brand": "Any",
  "urgency_level": "High",
  "location_radius_km": 5
}

```


##  User Documentation (Bilingual Guides)

### **Provider Onboarding: Setting Up Your Shop**

This tutorial demonstrates the ability to translate technical workflows into accessible, attractive content for business users in both English and Arabic.

| Step | English Instructions | (النسخة العربية) التعليمات |
| --- | --- | --- |
| **1** | Download the Food Map Provider app and tap "Register." | قم بتحميل تطبيق "فود ماب" واضغط على "تسجيل". |
| **2** | Upload a photo of your commercial license for verification. | قم بتحميل صورة من سجلك التجاري لتوثيق الحساب. |
| **3** | Pin your exact location on the map so neighbors can find you. | حدد موقعك بدقة على الخريطة ليتمكن جيرانك من العثور عليك. |

---

## Strategic Skills Demonstrated

* **API Literacy**: Mastery of RESTful verbs (POST, GET, PUT), JSON syntax, and status codes.
* **Bilingual Proficiency**: High-quality technical translation between English and Arabic tailored for the MENA market.
* **Docs-as-Code Workflow**: Utilizing GitHub, Markdown, and VS Code to align with modern software development lifecycles.
* **Business Understanding**: Deep understanding of SaaS ecosystems, including provider-client relationships and inventory logistics.

---

## Contact & Links

* **Professional Background**: English Technical Editor & Frontend Developer.
* **Location**: Based in Cairo, Egypt.
