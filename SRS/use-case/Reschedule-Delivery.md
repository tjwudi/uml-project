# Use Cases: Reschedule Delivery

### Diagram


### Brief Introduction
If the customer is not at home and no agent for him/her,the delivery must be rescheduled upon the agreement with the customer.


### Initial Step-by-Step Description
Before this use case can be initialized, the customer should sign in the Midway system(via SSO in taobao.com), then the customer has already ordered a product and the customer is not at home and no agent for him/her.

1. The customer chooses to reschedule the delivery.
2. The order management sub-system displays the form of rescheduling.
3. The customer fills out the information required and submit it.
4. The order management sub-system receives the request, confirms it and sends the information of rescheduling to the logistics company.
5. The logisics company's employee takes the package to the customer on reschedular day.
