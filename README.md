# job-offer-app
 
 ![](RackMultipart20210108-4-7h7m8j_html_bf7a8150c7f47d5.gif) ![](RackMultipart20210108-4-7h7m8j_html_f4f932da868f76e3.gif) ![](RackMultipart20210108-4-7h7m8j_html_f2810dafc58624ee.jpg) ![](RackMultipart20210108-4-7h7m8j_html_6b5c26ba7d13495d.gif) ![](RackMultipart20210108-4-7h7m8j_html_9c4665690f28a2ab.gif)

## TECH-PIRATES (ASPIRING MINDS)

![](RackMultipart20210108-4-7h7m8j_html_2486201f6768e004.gif) ![](RackMultipart20210108-4-7h7m8j_html_f7dd6db61a97ec94.gif)

# **ROUND 2**

![](RackMultipart20210108-4-7h7m8j_html_cff7a4a00288097a.jpg)

**PARTICIPANTS**

- **Ajay Kumar R**
- **Suriyan S**

![](RackMultipart20210108-4-7h7m8j_html_84594bee41abcd1.gif)


_ **Source Code GIT Repository:** _

**Web Browser Link:**

[**https://github.com/Tech-Pirates-Aspiring-Minds/job-offer-generator**](https://github.com/Tech-Pirates-Aspiring-Minds/job-offer-generator)

**https://github.com/Tech-Pirates-Aspiring-Minds/license-api-test-component**

**GIT Clone Link:**

[**https://github.com/Tech-Pirates-Aspiring-Minds/job-offer-generator.git**](https://github.com/Tech-Pirates-Aspiring-Minds/job-offer-generator.git)

_ **Frameworks:** _

![](RackMultipart20210108-4-7h7m8j_html_bfe3d5ca22040eab.png) ![](RackMultipart20210108-4-7h7m8j_html_9c524934b3049083.png) ![](RackMultipart20210108-4-7h7m8j_html_9fab57606c10be32.jpg) ![](RackMultipart20210108-4-7h7m8j_html_de86df2cf469e7e6.png)

![](RackMultipart20210108-4-7h7m8j_html_5aa02d49d1a956ee.png) ![](RackMultipart20210108-4-7h7m8j_html_22bbfab8440786c4.png) ![](RackMultipart20210108-4-7h7m8j_html_4105c1f06802661c.png) ![](RackMultipart20210108-4-7h7m8j_html_29c16b233e72182e.png)

**Job Offer Letter Geneartor**

The Job offer letter generator is based on java based application. This application allows users to create pre-defined templates (Ex: job offer letter, Bill., etc.) With dynamic fields. We should provide data for dynamic fields via excel at the time of report/letter generation. This application reduce manual efforts and consumes times.

**Spring Boot Architecture**

![](RackMultipart20210108-4-7h7m8j_html_971efb812d9f3d21.png)

![](RackMultipart20210108-4-7h7m8j_html_6444162be571fe74.jpg)

**Job Offer Letter Generator Flow Diagram**

![](RackMultipart20210108-4-7h7m8j_html_fd01d1317ec9df9b.png)

**Application Process Flow:**

Application runs at port 4200

[http://localhost:4200/#/create-template](http://localhost:4200/#/create-template)

**Template Creation:**

Create Template with basic details required for a template with dynamic fields and template content.

![](RackMultipart20210108-4-7h7m8j_html_d3a09df89eb46acf.png)

![](RackMultipart20210108-4-7h7m8j_html_c0fd027cddc1eca.png)

![](RackMultipart20210108-4-7h7m8j_html_cf7d482cfeb95ebd.png)

![](RackMultipart20210108-4-7h7m8j_html_b2718794ce2c9724.png)

![](RackMultipart20210108-4-7h7m8j_html_b1e10e54f9d39a8e.png)

![](RackMultipart20210108-4-7h7m8j_html_44625636c4514784.png)

**Content Prepration:**

Create Content as below enclosed with flower brackets to get dynamically replace it when template generation Ex: {Employee Name}. Note : the mentioned name should be matched with dynamic fields as above in previous image.

![](RackMultipart20210108-4-7h7m8j_html_87b8524c9e138ba7.png)

**Save the Template:**

Save the template will confirm with success message as shown below.

![](RackMultipart20210108-4-7h7m8j_html_54ea57d5c7a6dff6.png)

**View Template:**

View the created templates as below. User can preview/generate the template and can also delete if no need.

![](RackMultipart20210108-4-7h7m8j_html_90e2e34f1e114dfa.png)

**Preview Template:**

User can preview the template before generate. It only contains the original content while created.

It is downloadable and also it has some additional features as shown below.

![](RackMultipart20210108-4-7h7m8j_html_eceabeea2ffd3ac3.png)

**Template Generation:**

Step 1: Upload data file with data to generated in excel. Only excel files allowed. Excel file can contains multiple data to be generated.

![](RackMultipart20210108-4-7h7m8j_html_7c436765b359b86e.png)

The excel data should be as follows. The column name should be matched with dynamic fields in template. If fields mismatched the only matched fields will be replaced , remaining still present with flower brackets as we created in template.

![](RackMultipart20210108-4-7h7m8j_html_66de48dca307f15c.png)

![](RackMultipart20210108-4-7h7m8j_html_5c56dfcc76a47d23.png)

![](RackMultipart20210108-4-7h7m8j_html_1ed47811f3feb082.png)

Step 2 : Select the required excel sheet as below.

![](RackMultipart20210108-4-7h7m8j_html_338fe9f427e692c7.png)

Step 3: Click next to proceed

![](RackMultipart20210108-4-7h7m8j_html_25dea09ad65c1693.png)

Step 4: Document generation – User should provide the file format and file name. These two fileds are mandatory. Field name prefix can be optional. Prefix can be excel data field names.

![](RackMultipart20210108-4-7h7m8j_html_45ce8797e63fa391.png)

![](RackMultipart20210108-4-7h7m8j_html_9d68d4480b156ee5.png)

![](RackMultipart20210108-4-7h7m8j_html_7f31294f05580fbd.png)

Step 5: Generate the template – Once all done then proceed with Generate button to generate the bundle of templates as Zip. The below images shows thet bundle of offer letter generated as zip with dynamic fields.

![](RackMultipart20210108-4-7h7m8j_html_79dd6e22eb533c88.png)

Step 6: View the generated files

![](RackMultipart20210108-4-7h7m8j_html_ad2d2730f101a472.png)

![](RackMultipart20210108-4-7h7m8j_html_44a7f0c067d01aab.png)

![](RackMultipart20210108-4-7h7m8j_html_c51573f11d0d04ce.png)

_ **Swagger UI** _

Swagger UI has been included in this project for Rest API documentation

![](RackMultipart20210108-4-7h7m8j_html_3401ee2d0ea139bd.png)

![](RackMultipart20210108-4-7h7m8j_html_d4f2f1954fc1cb5a.gif) ![](RackMultipart20210108-4-7h7m8j_html_9abe6c367f314a66.gif) ![](RackMultipart20210108-4-7h7m8j_html_186daa70e97628a4.gif)


