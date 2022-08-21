# Afya Intelligence Interview 2022

## Question 1

Afya Intelligence has created a chatbot that is aimed at supporting help facilities improve their performance. After the launch of the program a number of facilities have been registered and active ones identified. Registration and active data are to be regularly entered by the facility heads as aggregate numbers. The regularity of data entry is being measured by reporting rate metrics and the higher the metrics the better result.

In order to measure the effectiveness of the program over 3 years, data for 3 years as shown in table below have to be compared given some criterions and final results be produced as:

yearOneData

```json
[
  {
    "value": 10,
    "name": "Number of members registered",
    "code": "MEMBER_REGISTERED",
    "reportingRate": "10"
  },
  {
    "value": 9,
    "name": "Number of active members",
    "code": "ACTIVE_MEMBERS",
    "reportingRate": "50"
  }
]

```

yearTwoData

```json
[
  {
    "value": 30,
    "name": "Number of members registered",
    "code": "MEMBER_REGISTERED",
    "reportingRate": "70"
  },
  {
    "value": 25,
    "name": "Number of active members",
    "code": "ACTIVE_MEMBERS",
    "reportingRate": "90"
  }
]

```

yearThreeData

```json
[
  {
    "value": 56,
    "name": "Number of members registered",
    "code": "MEMBER_REGISTERED",
    "reportingRate": "70"
  },
  {
    "value": 43,
    "name": "Number of active members",
    "code": "ACTIVE_MEMBERS",
    "reportingRate": "20"
  }
]
```

## Criterias

1. Data with Reporting rate greater or equal to 50% (>=50) will be taken for final procesing

2. In order to arrive to final output, average of data items that meet reporting date criteria should be taken as shown below;

### Final Results (output)

```json
[
  {
    "value": 43,
    "name": "Number of members registered",
    "code": "MEMBER_REGISTERED"
  },
  {
    "value": 17,
    "name": "Number of active members",
    "code": "ACTIVE_MEMBERS"
  }
]

```

## Assignment

Develop a javascript/typescript script to process the provided inputs (yearOneData, yearTwoData, yearThreeData) and produce the above output. Your script should be test driven .i.e. You must use automated tests to verify your code. We have provided a boilerplate codebase with all necessary tools for this question, find the boilerplate code here

### Running the script

1. clone the script from the repo `git clone https://github.com/Afya-Intelligence/afya-intelligence-lab-interview-2022`

2. Run `npm install` to install all necessary packages to run the script"

3. Run `npm test` to test your script

4. Submit your completed code into your own github account and shared the link as directed

**NOTE:**

1. Be original (Do not copy code from others)
2. Follow coding and testing conventions
3. Write clean and readable codes
4. Have Fun!
