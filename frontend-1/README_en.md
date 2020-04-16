# Assignment for Candidates of XMind Front-end Developer

## Get Started

1. The assignment gets us to know you better, including but not limited to your current capability and potential. Please finish reading this document before completing the task.
2. There will be no limit of tech stack, and you can finish the assignment with any stack and present it on a web page.
3. You need to attach a document with description of how to use, run and test your code, including the required operating system, and environment, etc.
4. We will save your code and other content for comparison and identification. You retain ownership for your assignment and we will ensure there will be no misappropriation happened. It would be great that if you share it with others. 

## A Simple Account Book

The basic requirement of this assignment is to build a simple application called account book.

### Data Structure

We will provide dataset in CSV format where contains fictitious billing data, including the following information:


| Field name | Field label | Column Type | Description | Required |
| :-: | :---------: | :------------: | :---------------------------------| :---------------------: |
| Bill Time | `time` | `Date` | The created time of the bill, formatted as ISO8601: `2019-09-08T08:02:17+08:00` | Yes |
| Bill Type | `type` | `Integer` | The type of the bill. This field is limited to two values: `1` is the income and `0` is the expenditure. | Yes |
| Bill Category | `category` | `String` |A detailed category of bills. | No |
| Bill Amount  | `amount` | `Float` | The amount of the bill is in RMB (￥),  accurate to two decimal places. | Yes |

In addition to the dataset above, we also provide another dataset including field information below:

| Column name | Column label | Column Type | Description | Required |
| :---: | :----: | :-------: | :--------------------------------------------- | :--: |
| Category ID | `id`   | `String`  | The unique identifier of the category, corresponding to the `category` field in the billing data. | Yes |
| Category Name | `name` | `String`  | Category display name              | Yes |
| Category    Column | `type` | `Integer` | The type of category is the same as the `type` field in the billing data:`1` represents income and `0` represents expenditure | Yes |

### Basic Requirement

You need to read the data we provided to meet the following requirements:

1. Load the provided data;
2. Display the bill in the form of column, and filter the months via drop-down box. The column displays the data bill of the filter months;
3. Users can add bills;
4. The application supports simple statistics collection and display the total amount of income and expenses of the selected months. 

The basic requirements for the assignment is as above. If you are applying for a senior front-end engineer or above, please complete additional requirements as below: 

1. A secondary filter based on current bill category;
2. Calculate and sort the expenditure amount of the general bills in the selected month according to the bill category.

If you are applying for a remote job, please complete the following additional requirements:

1. Write a brief document that includes your thinking process for this assignment, and describe the encountered problems along with solutions.

> Additional requirements above is bonus.

## Make sure it runs

1. Please archive the assignment (code and all the other content), and send to hr@xmind.net by cloud disk or github link.
2. Please attach your resume with the information below:
   - Email Address
   - Phone Number
3. Please do not include any dependent libraries or executable file in your code, such as the `node_modules` folder.
