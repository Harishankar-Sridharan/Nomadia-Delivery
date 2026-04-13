# 7.3. Manage Sub Statuses

The Manage Sub Statuses feature allows administrators to create, edit, and assign detailed status labels that reflect the real-time progress or condition of a delivery task. These sub statuses provide a more granular tracking mechanism within the broader status categories such as "Pickup", "Waiting", or "Delivered"

### 1. Create a Sub status <a href="#toc225775670" id="toc225775670"></a>

1. Go to **Configuration**.
2. Click on **Configuration Menu**
3. Under **My Data**, click on **Sub statuses**.

![](<../.gitbook/assets/image_1 (2).png>)

4. Click the **Actions** dropdown menu
5. Click on **Add**

![](<../.gitbook/assets/image_2 (4).png>)

6. Enter the Sub status code
7. Select the Status configuration type

<figure><img src="../.gitbook/assets/image (19).png" alt=""><figcaption></figcaption></figure>

8. Click on Save

<figure><img src="../.gitbook/assets/image (20).png" alt=""><figcaption></figcaption></figure>

9. Sub status has been created successfully

![](<../.gitbook/assets/image_5 (4).png>)

### 2. Delete a Sub status <a href="#toc225775671" id="toc225775671"></a>

1. Go to **Configuration**.
2. Click on **Configuration Menu**
3. Under My Data, click on **Sub statuses**.
4. Select a **Sub statuses**
5. Click the **Actions** dropdown menu
6. Click on **Delete**

<figure><img src="../.gitbook/assets/image (21).png" alt=""><figcaption></figcaption></figure>



You will see a confirmation pop-up message stating: "**Do you want to delete the sub-status?"**

7. Click on Yes

![](<../.gitbook/assets/image_7 (3).png>)

8. Sub status has been deleted successfully

![](<../.gitbook/assets/image_8 (2).png>)



### 3. Coloring a Sub status <a href="#toc225775672" id="toc225775672"></a>

Apply conditions based on zone attributes such as type of mission (Delivery, Pickup), Zone priority, Assigned deliverer, Postal code prefix, etc.

1. Go to **Configuration**.
2. Click on **Configuration Menu**
3. Under **My Data**, click on **Sub statuses**.
4. Select a **Sub statuses**
5. Click the **Actions** dropdown menu
6. Click on **Coloring**

<figure><img src="../.gitbook/assets/image (22).png" alt=""><figcaption></figcaption></figure>

7. Choose a Color
8. Click on Save

<figure><img src="../.gitbook/assets/image (23).png" alt=""><figcaption></figcaption></figure>



9. The selected color has been applied successfully.

<figure><img src="../.gitbook/assets/image (24).png" alt=""><figcaption></figcaption></figure>



### 4. Customize Sub statuses table <a href="#toc225775673" id="toc225775673"></a>

1. Go to **Configuration**.
2. Click on **Configuration Menu**
3. Under **My Data**, click on **Sub statuses**.
4. Select a **Sub statuses**
5. Click the **Actions** dropdown menu
6. Click on **Customize the Limit**

<figure><img src="../.gitbook/assets/image (26).png" alt=""><figcaption></figcaption></figure>



7. Choose which fields you want to display on the table.

&#x20;    Note: Avoid selecting too many fields at once, as it may become difficult to read or navigate

8. Click on **Save**

![](<../.gitbook/assets/image_13 (3).png>)

9. The selected fields have been displayed on the table successfully

![](<../.gitbook/assets/image_14 (2).png>)

### 5. MANAGING SUB-STATUS CONFIGURATION TYPES <a href="#toc225775674" id="toc225775674"></a>

Nomadia Delivery provides three types of sub-status templates that enable users to personalize the delivery workflow according to the customer type or category. These templates are Basic, Intermediate, and Advanced.

* **Basic Configuration types**: Designed for customers who require only a single verification step, such as capturing a photo or collecting a signature. It simplifies the delivery process by including only the essential checks\\.
* **Intermediate Configuration types**: Suitable for customers who need multiple verification steps but do not require the full range of options available on the advanced template.
* **Advanced Configuration types**: Intended for customers who demand comprehensive verification, such as taking photos at every stage of the delivery. It provides maximum flexibility to configure detailed workflows.

**Note**: The Configuration types options are provided solely to help differentiate delivery workflows based on customer categories. However, the complexity of the workflow is entirely at the user’s discretion. For example, a Basic template can still be configured to support a complex delivery process if needed.

To configure and manage sub-status configuration types in Nomadia Delivery, follow these steps:

1. Open the Nomadia Delivery application and go to the **Configuration module**.

![](<../.gitbook/assets/image_15 (3).png>)

2. Click on the **Actions** button, then choose **Add** to create a new sub-status.

![](<../.gitbook/assets/image_16 (2).png>)

3. Assign the created sub-status to one or more templates.

![](<../.gitbook/assets/image_17 (2).png>)

4. Define the required actions for each sub-status, such as making signature mandatory, requiring a photo, etc.

![](<../.gitbook/assets/image_18 (1).png>)

5. Repeat the process to create additional sub-statuses and link them to the desired templates.

![](<../.gitbook/assets/image_19 (2).png>)

6. Once all templates are configured, navigate to the **Missions** tab.
7. Click on the **Mission Editor** button to attach a sub-status template to a mission.

![](<../.gitbook/assets/image_20 (3).png>)

8. Select the appropriate sub-status configuration template for the chosen mission

![](<../.gitbook/assets/image_21 (2).png>)

9. Alternatively, configure templates in bulk during mission import by mapping the Excel field to the Status configuration type with values like **BASIC**, **INTERMEDIATE**, or **ADVANCED**.

![](<../.gitbook/assets/image_22 (3).png>)

### 6. Trigger Notifications for Sub Status Changes <a href="#id-6.3.3.6._trigger_notifications" id="id-6.3.3.6._trigger_notifications"></a>

The Trigger Notifications for Sub-Status Changes feature enables accurate, real-time communication with all stakeholders involved in parcel movement. It improves transparency, coordination, and overall service quality across first-mile, mid-mile, and last-mile operations.

To configure notifications for sub-status changes, follow the steps below:

1. Open the Nomadia Delivery application and go to the Configuration tab.

![](<../.gitbook/assets/image_23 (2).png>)

2. Select Sub-statuses from the list.

![](<../.gitbook/assets/image_24 (2).png>)

3. Click the Pencil icon next to the existing sub-status to edit it.

![](<../.gitbook/assets/image_25 (3).png>)

4. The Custom Messages Configuration section is displayed at the bottom of the page.

![](<../.gitbook/assets/image_26 (2).png>)

5. Click the + button to add the notification configuration to the sub status.

![](<../.gitbook/assets/image_27 (1).png>)

6. Notifications can be made for the following recipients:

* **Sender** – The original sender of the mission. Notifications are sent to the contractor’s email address or mobile number stored in the mission details.
* **Consignee** – The original recipient of the mission (customer). Notifications are sent to the delivery email address or mobile number stored in the mission details.
* **Other Recipients** – Any internal stakeholders who need to be informed about the mission’s transit, such as the dispatch or logistics teams. This field accepts multiple email addresses or phone numbers, separated by commas.

![](<../.gitbook/assets/image_28 (2).png>)

7. Notifications can be sent via Email or SMS.

* To create a notification configuration, select a recipient, message type, and message template. Please note that only custom message templates are supported for this case.

![](../.gitbook/assets/image_29.png)

8. The Other Recipients field allows you to enter multiple email addresses or phone numbers, separated by commas.

* Please note that the Other Recipients field is enabled only when Other Recipients is selected in the Recipient column.

![](<../.gitbook/assets/image_30 (1).png>)

9. After completing the configuration, click Save to apply and store the changes.

![](<../.gitbook/assets/image_31 (1).png>)

When the mobile user triggers a sub-status, all configured recipients automatically receive the update via Email or SMS at the same time, providing real-time information on the mission’s movement.

![](<../.gitbook/assets/image_32 (1).png>)
