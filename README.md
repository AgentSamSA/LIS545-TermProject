# LIS545-TermProject
## About
This repository stores the 2022 Ukraine Russia War Equipment Losses Oryx dataset, sourced from [Kaggle](https://www.kaggle.com/datasets/piterfm/2022-ukraine-russia-war-equipment-losses-oryx). This comprehensive dataset contains thousands of rows of visually confirmed equipment and vehicle loss data from Ukraine. Each of these datarows was visually confirmed, and the original source includes an image as the ground source of truth.  
As information and intelligence play increasing public-facing roles in modern warfare, it becomes important to preserve and maintain ground sources of truth whenever possible.
## Data Files
This repository contains the following files:

- img_russia/Tanks: a sample of image source files in both .png and .jpg, showing visually confirmed Tank losses on the Russian side
- img_ukraine/Infantry_Fighting_Vehicles: a sample of image source files in both .png and .jpg, showing visually confirmed Infantry Fighting Vehicles (IFV) losses on the Ukrainian side
- img_losses_metadata_russia.csv: a CSV file detailing the metadata for the losses_russia.csv file. Links each source image to a data row
- img_losses_metadata_ukraine.csv: a CSV file detailing the metadata for the losses_ukraine.csv file. Links each source image to a data row
- losses_russia.csv: a CSV file with data rows related to Russia's vehicle losses in the 2022 Russia-Ukraine war. Headers include the equipment type, model, total number destroyed, and various statuses (destroyed, abandoned, damaged, captured, etc.)
- Final Report (DOCX): a PDF detailing the chosen dataset, as well as a possible canditate repository to host the data
- Metadata file (XML): an XML file containing the metadata record for the dataset, in accordance with the [DataCite Metadata Schema - Version 4.6](https://datacite-metadata-schema.readthedocs.io/en/4.6/#)

Due to the size of the original dataset (over 10GB and over 30,000 individual image files), only a sample of the source images are provided here.
The rest may be accessed at the source: [Kaggle](https://www.kaggle.com/datasets/piterfm/2022-ukraine-russia-war-equipment-losses-oryx)
