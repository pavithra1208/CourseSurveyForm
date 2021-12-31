# Requirements
## Introduction
This is a frontend project built using HTML, CSS, and JavaScript, which strictly validates the input entered by the user/client, and immediately lets the user know if the entry is invalid.

This is a Course survey form, open the HTML file in your browser you can use this form. It uses the form validation in Javascript, to check if the input entered is a number, the pattern we use is /^[0-9]+$/ and match it with the 'string' we want to check. JS code goes like this: string.match(/^[0-9]+$/);
Also, does not accept input until the requirements are not fulfilled or are not valid.


# Detail requirements
## High Level Requirements:
|ID      | Description                                     | Status            |
|:---:   | :-----------------------------------------------| :----------------:|
|  HLR_1     |  Enter the user input                       |Implemented        |
|  HLR_2     |  Describe the user current role             |Implemented        |
|  HLR_3     |   Most liked part of the course             |Implemented        |
|  HLR_4     |     Features to be improved in future       |Implemented        |
|  HLR_5     |     Submit the survey                       |Implemented        |
## Low Level Requirements:        
|ID          | Description                                                                                      | Status            |
|:--------:  | :---------------------------------------------------------------------------------------:        | :----------------:|
|  HLR_LLR_1a | Username-Must contain atleast three characters, and can't have a number.                        |Implemented        |
|  HLR_LLR_1b | Email- Enter valid email id, should contain (@, mail .com)                                      |Implemented        |
|  HLR_LLR_1c | Age- shouble be number with max of 122                                                          |Implemented        |
|  HLR_LLR_2  | Select dropdown option to describe the role:student, undergraduate, postgraduate                |Implemented        |
|  HLR_LLR_3  |  Select dropdown to choose the liked part of the course: learning objective, assessments, mentor|Implemented        |
|  HLR_LLR_4  | Use checkboxes to describe features to be improved: content, video lecture, interface module    |Implemented        |
|  HLR_LLR_5  | Use input type button to submit the survey                                                      |Implemented        |




