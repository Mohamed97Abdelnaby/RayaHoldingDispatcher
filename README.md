# 📄 **Adding a Document to a UiPath Document Understanding Process** 🛠️

This guide provides a detailed step-by-step process to add a new document type to your UiPath Document Understanding (DU) workflow. Ensure accurate document classification and data extraction with these instructions.

---

## 1. 🗂️ **Create an Object in Data Service**

Start by creating an object in UiPath Data Service that matches the structure of your new document.

### 📝 **Steps:**
1. Navigate to **Data Service** in UiPath.
2. Create a new object.
3. Define the fields required for your document type.

🎨 *Visual Placeholder: ![Data Service Object Creation](#)*

---

## 2. 🗃️ **Add the Object to Taxonomy**

Integrate the newly created object into the taxonomy used in your DU process.

### 📝 **Steps:**
1. Open **UiPath Studio**.
2. Go to the **Taxonomy Manager**.
3. Add the new object under the relevant taxonomy category.

🎨 *Visual Placeholder: ![Taxonomy Manager](#)*

---

## 3. 🔧 **Initialize the Object in DUProcessing**

Next, initialize the new object within your DUProcessing workflow.

### 📝 **Steps:**
1. Open your **DUProcessing workflow**.
2. Initialize the new object.
3. Ensure it matches the type created in Data Service.

🎨 *Visual Placeholder: ![Object Initialization](#)*

---

## 4. 🔍 **Add Unique Keywords to Classifier**

To help the classifier correctly identify the new document type, add unique keywords.

### 📝 **Steps:**
1. Open the **Classification** activity in UiPath Studio.
2. Add specific keywords related to your document.

🎨 *Visual Placeholder: ![Keywords Addition](#)*

---

## 5. 📑 **Add the Document to Classification**

Include your document in the classification setup for proper recognition.

### 📝 **Steps:**
1. Go to the **Classification** section.
2. Add the document type you've defined.

🎨 *Visual Placeholder: ![Document Classification](#)*

---

## 6. 🔄 **Retrain the Classifier with the New Document**

Retrain the classifier to improve its accuracy with the new document.

### 📝 **Steps:**
1. Navigate to the **Classification Retrain** part.
2. Add the new document for retraining.

🎨 *Visual Placeholder: ![Retraining Classifier](#)*

---

## 7. 🎓 **Train the Extractor on the New Document**

Finally, train the extractor to accurately extract data from the new document type.

### 📝 **Steps:**
1. Open the **Extraction** activity.
2. Train the extractor with the new document.

🎨 *Visual Placeholder: ![Extractor Training](#)*

---

## 🎉 **Conclusion**

By following these steps, your UiPath Document Understanding process will be fully equipped to recognize and process the new document type with precision and accuracy.
