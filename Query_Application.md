# SQL Query Insurance Agent Use Explanation

### 1.) Discount Plan Enrollment
_Use low accident frequency data to prompt agents to recommend Intellidrive, boosting savings_

![image](https://github.com/user-attachments/assets/6827bbac-79a4-4578-b02a-b31072b6877f)

### 2.) Registration Lapse and Safety Feature Identifier:
_Search by VIN number to find clients with lapsed registrations who may be eligible for vehicle safety feature discounts._

![image](https://github.com/user-attachments/assets/00a9c68b-d4ee-4294-abff-423da1d760a0)

### 3.) Initial Plan Setup Query
_Intended for automating suggestions for initial plan setup for new clients
Queries for accident frequeny and income bracket to suggest deductibles and premiums_

**a.) High accident frequency and high income:** Higher liability and premiums.

**b.) High accident frequency and medium income:** Lower deductibles, medium premiums.

**c.) Low accident frequency:** Low deductibles and premiums.

![image](https://github.com/user-attachments/assets/03230252-26ce-491c-ad35-e3e5a392846c)

### 4.) Plan Adjustment Query
_"Living" Plan: Adjust Plan as Accidents Occur_

_Intended for use periodically to suggest changes to client plans as accidents occur_

__a.) Under-coverage:__ Discuss higher liability if accident damages exceed current limit.

__b.) Over-coverage:__ Recommend lower premiums if damages are below the deductible.

__c.) Payment Issues:__ Address frequent missed payments with potential premium reductions

![image](https://github.com/user-attachments/assets/bd0209c5-d3a3-4a00-847a-620a4807a16c)



