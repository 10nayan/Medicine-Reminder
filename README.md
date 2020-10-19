# Medicine-Reminder
This application can be developed using Django with following steps
1. Creating a form that takes users name, medicine name, repetion count data and stores in below mentioned two table .
2.  Creating two models (Patient and Medicines), Patient model with Patient Name,No of medicine, desease field  , age and Medicine model with medicine name,repetiton count, selectfield(monthly/daily/weekly) and a foreign field that linked to patient field.
3. Both Patient model and Medicine model should be linked with one to many relation.
4. By querrying medicine table filter by every patient table ID to get one's all medicines and then get every medicines repetition count and scheduled them accoridingly.
5.For every patients each medicines taking time can be added to an event to calender.
