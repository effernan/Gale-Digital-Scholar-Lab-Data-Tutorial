# Gale-Digital-Scholar-Lab-Data-Tutorial
This is a tutorial to transform the text and metadata provided by Gale Digital Scholar Lab into a user friendly CSV dataframe that can be used to implement Text Data Mining methodologies.

The dataset used is **"The Times Digital Archive"** (https://www.gale.com/intl/c/the-times-digital-archive)

The Digital Scholar Lab provides the option of downloading in separate CSV files:
- **Metadata** (Document Title, Content Type, Document Type, Publication Title, Publication Date, Publisher, Place of Publication, Author, Source Library, Gale Primary Source, Gale Document Number, Subject, Language).
- **Content Set** (title and text of the articles).

Both dataframes share an ID identifier that can be used to merge them. Here goes a step-by-step set of Jupyter Notebooks showing how to do that:

* **1. Gale Metadata.** It contains code to parse the ID identfier found in the Metadata Gale Dataframe
* **2. Importing Text Data Gale.** It contains code to import the Content Set (title + text of the articles) 
* **3. Headers**. It contains code to clean the title of the Content Set and to parse the ID identifier that we need
* **4. Merging Dataframes**. It contains code to merge the Gale Metadata CSV and the Content Set CSV by the now cleaned ID identifier column
* **5. Body**. It contains code to clean and pre-process the text of the articles in the Content Set. 

The output is a CSV dataframe with clean article text and corresponding metadata.

(c) Elena Fernández Fernández 2024
