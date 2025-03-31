# ***Coffee Shop Chain Data Insights***:



### 📖 Introduction:

* #### ☕ Project Overview: 
    This project analyzes and provides insights 
    for global coffee shop chain to better      understand customer's *coffee consumption habits* and optimizing *sales strategies*.

    By leveraging data-driven insights, the project *aims* to enhance customer experience, improve product offerings, and drive revenue growth across various international markets.

* #### 📈 Business Objectives:
    * Identify key customer segments and their preferences.
    * Optimize product offerings to maximize sales and profitability.
    * Improve customer retention and engagement strategies.
    * Identify peak sales periods and promotional opportunities.

* #### 🌍 Scope: 
    Analysis across multiple regions and demographics to enhance global sales strategies.

### 🗂️ Data Collection & Preprocessing
#### Data Sources:

* POS (Point of Sale) transaction data.

* Customer demographics and loyalty program data.

* Online reviews and social media interactions.



#### Data Cleaning & Preparation:

* Handling Missing Values:

* Removing Duplicates: Eliminated 19 duplicate IDs from  "Submission ID" column.

* Standardizing Formats:
    * Aligned all values in columns to right.

* Merging Datasets: 



#### 🧹 Data Cleaning - Handiling Missing values:
   * 1️⃣ Get count of Null values in data set:
       * We used pandas *is_null().sum()* to get totll count of Null values as shown in screenshot below:      

        ![Image](https://github.com/user-attachments/assets/9b2373b7-c2f9-4d46-9426-a614b4a3d77f)
    
   
   
   *  2️⃣ Handled Null values in column *"What is your age?"*:  
       * There were totll *31 Null* values in this cloumn. Here we used *mod()* function to get most frequent value -- *"25-34 years old"*. hence Null values in this column have been replaced wuth "25-34 years old". 
   
        ![Image](https://github.com/user-attachments/assets/0fa8ad4e-d2b5-46d7-bf6d-8135a2ff3fbd)

        ![Image](https://github.com/user-attachments/assets/d9d84f04-596f-4a1a-9a1b-c4a7151aef03)

  * 3️⃣ Handled Null values in column *How many cups of coffee do you typically drink per day?*: 
      * There were totll *93 Null* values in this cloumn. Using pandas mod() function we got "2 is the" most frequent value, hence Null values in this column have been replaced with "2".

        ![Image](https://github.com/user-attachments/assets/5c322457-d9f6-497d-8253-5a080fcc079b)
     
        ![Image](https://github.com/user-attachments/assets/10f2a8c4-aafb-40a9-995c-243c8c207afb)

* 4️⃣ Handled Null values in column *'Where do you typically drink coffee?'*:
    * There were totll *70 Null* values in this cloumn. Using pandas mod() function we got "At home" is the most frequent value, hence Null values in this column have been replaced with "At home".
        ![Image](https://github.com/user-attachments/assets/201e8143-8fb1-49f0-a262-3817a04ff615)

        ![Image](https://github.com/user-attachments/assets/e3fa2813-4dc0-4eea-ad21-7d73e62c0d0e)




