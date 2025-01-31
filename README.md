# OneClickBite

The project is composed of three parts: Image Classification using Neural Network models, Web Scraping for gathering recipes, and third-party integration with Zomato, Swiggy, Blinkit, and Zepto. Download "Group_44_Final_Report.pdf" for detailed report.

The main objective of this project is to classify food images with 45 different food categories sourced from the food101 dataset. To achieve this, three CNN models were implemented - TensorFlow's ModelMaker, MobileNetV3, and InceptionV3. Model Maker yielded an accuracy of 78% on training data and 73% on testing data. MobileNetV3 had an accuracy of 60% on training data and 51% on testing data. Meanwhile, InceptionV3, which is the most complex and computationally demanding model, outperformed all other models with a training accuracy of 81% and testing accuracy of 77%. Thus, InceptionV3 was chosen as the final model for image classification. All the 3 models can be found inside "ImageClassificationModels" folder.

"WebScrapingJava" folder has all the code we used to scrape recipes from 8 different websites.

Once an uploaded image is identified, the user may select to prepare/order the food. Ordering will redirect the user to Zomato/Swiggy, and the user may choose between text recipes or video recipes. Video recipes will display YouTube videos in English and Hindi that show how to prepare the dish, while text recipes will be obtained through web scraping and displayed on the screen for the user to follow. Additionally, the user can order any missing ingredients required for the recipe from Blinkit/Zepto.

To get this application, download the OneclickBite.apk file from the "OneClickBite_apk_file.zip" folder, enable the "install from unknown sources" option, and install the APK file. For understanding the flow of app, you can refer to the "Readme OnClickBite.pdf" file.

You can find the project presentation here --> https://www.youtube.com/watch?v=WYh8R2tJQzc

You can find the app demo here --> https://www.youtube.com/watch?v=uxTss2Gtp8w
