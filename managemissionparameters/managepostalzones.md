# 7.1. Manage Postal Zones

The Manage Postal Zones feature allows administrators and logistics managers to define and manage geographical delivery zones based on postal codes. These zones are essential for organizing deliveries, assigning resources, and optimizing routes within specificareas

### 1. Import Postal Zones <a href="#toc225775647" id="toc225775647"></a>

<table data-header-hidden><thead><tr><th valign="top"></th><th valign="top"></th><th valign="top"></th></tr></thead><tbody><tr><td valign="top">Field name in import file</td><td valign="top">Field name in back-office table</td><td valign="top">Description</td></tr><tr><td valign="top">Id</td><td valign="top">Code</td><td valign="top">Mandatory. It should be unique among the other Zone ids</td></tr><tr><td valign="top">Name</td><td valign="top">Name</td><td valign="top">Mandatory</td></tr><tr><td valign="top">Organization</td><td valign="top">Agency</td><td valign="top">Mandatory</td></tr><tr><td valign="top">Postal Codes</td><td valign="top">Postal Codes</td><td valign="top"> </td></tr><tr><td valign="top">Normalized Size</td><td valign="top">Postal Codes normalized length</td><td valign="top"> </td></tr><tr><td valign="top">Normalize With</td><td valign="top">Prefix</td><td valign="top"> </td></tr><tr><td valign="top">All Skills Required</td><td valign="top">Require all skills to be compatible</td><td valign="top"> </td></tr><tr><td valign="top">Skills</td><td valign="top">N/A</td><td valign="top"> </td></tr><tr><td valign="top">Status Customization Types</td><td valign="top">N/A</td><td valign="top"> </td></tr><tr><td valign="top">Wkt Geometry</td><td valign="top">N/A</td><td valign="top"> </td></tr><tr><td valign="top">Opening Days</td><td valign="top">Opening day x</td><td valign="top">Suffix x is equal from 1 to 10</td></tr><tr><td valign="top">Opening Hours</td><td valign="top">Opening Hours x</td><td valign="top">Suffix x is equal from 1 to 10</td></tr></tbody></table>



1. Click on **Configuration Tab**

<figure><img src="../.gitbook/assets/image (10).png" alt=""><figcaption></figcaption></figure>

2. Click on Configuration Menu
3. Under **My data** section, click on Manage Zones

![](<../.gitbook/assets/image_2 (3).png>)

4. Click the **Actions** dropdown menu.
5. Click on **Import**

<figure><img src="../.gitbook/assets/image (11).png" alt=""><figcaption></figcaption></figure>

6. Click on **Browse File** to upload the file that contains the zone data.

<figure><img src="../.gitbook/assets/image (12).png" alt=""><figcaption></figcaption></figure>

7. Select a valid **Zone file** from your local system.

![](<../.gitbook/assets/image_5 (3).png>)

8. Postal Zones will be imported successfully.

![](<../.gitbook/assets/image_6 (2).png>)

### 2. Add a Postal Zone <a href="#toc199075784" id="toc199075784"></a>

1. Click on **Configuration Tab**
2. Click on **Configuration Menu**
3. Under My data section, click on **Manage Zones**
4. Click the **Actions** dropdown menu.
5. Click on **Add a Postal Zone.**

![](<../.gitbook/assets/image_7 (2).png>)

6. Fill in the required fields: **Code**, **Name**, and **Prefix**.

**Note**: The Prefix is used to standardize postal codes to a fixed length of 6 digits. In regions where postal codes are shorter (e.g., 5 digits in some areas of France), the system automatically adds the defined prefix to reach the required length.

<figure><img src="../.gitbook/assets/image (13).png" alt=""><figcaption></figcaption></figure>

7. Click on **Save**

<figure><img src="../.gitbook/assets/image (14).png" alt=""><figcaption></figcaption></figure>

8. Postal Zones will be added successfully

![](<../.gitbook/assets/image_10 (2).png>)

### 3. Create Postal Zones by Territory Management (Sectorization) <a href="#toc199075785" id="toc199075785"></a>

1. Click on **Configuration Tab**
2. Click on **Configuration Menu**
3. Under My data section, click on **Manage Zones**
4. Select a **Mission**
5. Click the **Actions** dropdown menu.
6. Click on \_\_New Sectorization. \_\_

For detailed information, refer to the Territory Manager Manual available at the following link:

[https://mynomadia.com/doc/tm/docs/en/tm-book/\_districting.html](https://mynomadia.com/doc/tm/docs/en/tm-book/_districting.html)

![](<../.gitbook/assets/image_11 (2).png>)

7. Select the appropriate **Indicators** and define the **Time Period**
8. Click on **Assign Territories**

![](<../.gitbook/assets/image_12 (2).png>)

9. Click on **Automation**

![](<../.gitbook/assets/image_13 (2).png>)

10. In the **Balancing Points** section, click **Start** to prepare the system for automatic balancing.

![](<../.gitbook/assets/image_14 (1).png>)

11. Click **“Let’s go!”** to launch the automated balancing of territories.

![](<../.gitbook/assets/image_15 (2).png>)

12. Sectors are generated according to the balancing rules set by the user.
13. To ensure the sectorization respects postal code boundaries, click on **Administrative Borders** and select **Postal Code** from the dropdown menu.

![](<../.gitbook/assets/image_16 (1).png>)

Sectors are aligned based on postal boundaries

**Disclaimer: Postal code boundary data is unavailable for certain countries.**

### 4. Delete a Postal Zone <a href="#toc199075786" id="toc199075786"></a>

1. Click on **Configuration Tab**
2. Click on **Configuration Menu**
3. Under My data section, click on **Manage Zones**
4. Select a **Zone**

![](<../.gitbook/assets/image_17 (1).png>)

5. Click the **Actions** dropdown menu.
6. Click on **Delete**

<figure><img src="../.gitbook/assets/image (15).png" alt=""><figcaption></figcaption></figure>



7. You will see a confirmation pop-up message stating: "Are you sure you want to delete this zone"?
8. Click on **Yes**

<figure><img src="../.gitbook/assets/image (16).png" alt=""><figcaption></figcaption></figure>

9. Postal Zone will be deleted successfully

![](<../.gitbook/assets/image_20 (2).png>)

### 5. Export a Postal Zone <a href="#toc199075787" id="toc199075787"></a>

1. Click on **Configuration Tab**
2. Click on **Configuration Menu**
3. Under My data section, click on **Manage Zones**
4. Select a **Zone**
5. Click the **Actions** dropdown menu.
6. Click on **Export**

![](<../.gitbook/assets/image_21 (1).png>)

7. Postal Zone will be exported successfully

![](<../.gitbook/assets/image_22 (2).png>)

### 6. Color a Postal Zone <a href="#toc199075788" id="toc199075788"></a>

Apply conditions based on zone attributes such as type of mission (Delivery, Pickup), Zone priority, Assigned deliverer, Postal code prefix, etc.

1. Click on **Configuration Tab**
2. Click on **Configuration Menu**
3. Under My data section, click on **Manage Zones**
4. Select a **Zone**
5. Click the **Actions** dropdown menu.
6. Click on **Coloring**

<figure><img src="../.gitbook/assets/image (17).png" alt=""><figcaption></figcaption></figure>

7. Choose a Color
8. Click on **Save**

![](<../.gitbook/assets/image_24 (1).png>)

9. The selected color has been applied successfully.

![](<../.gitbook/assets/image_25 (2).png>)

### 7. Customize Zones Table <a href="#toc225775653" id="toc225775653"></a>

Refer to [4.3.1.1. Import a Postal Zones](managepostalzones.md#_4.3.1.1._Import_a) to have the complete list of available fields.

1. Click on **Configuration Tab**
2. Click on **Configuration Menu**
3. Under My data section, click on **Manage Zones**
4. Select a **Zone**
5. Click the **Actions** dropdown menu.
6. Click on **Customize Limit**

![](<../.gitbook/assets/image_26 (1).png>)

7. Choose which fields you want to display on the table.

&#x20; Note: Avoid selecting too many fields at once, as it may become difficult to read or navigate.

8. Click on **Save**

![](../.gitbook/assets/image_27.png)

9. The selected fields have been displayed on the table.

![](<../.gitbook/assets/image_28 (1).png>)

