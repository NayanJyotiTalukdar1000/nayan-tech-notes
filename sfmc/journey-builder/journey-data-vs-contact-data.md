

# Journey Data vs Contact Data

## Simple Explanation

**Journey Data** is the data captured when the customer enters the journey. 
It works like a **snapshot** and normally does not change during that journey instance.

**Contact Data** is the customer's **latest/current data** available from Contact Builder. 
It can change while the customer is already inside the journey.

---

## Example

A customer enters the journey with:

> **Loyalty Status = Silver**

Later, the customer's loyalty status changes to:

> **Loyalty Status = Gold**

Therefore:

| Data Type | Value |
|---|---|
| Journey Data | Silver |
| Contact Data | Gold |

---

## Interview Answer

> **Journey Data is the snapshot of customer data at the time of journey entry, while Contact Data gives the latest customer information during the journey. If I need the original value, I use Journey Data. If I need the current value, I use Contact Data.**

---

## Easy Trick to Remember

**Journey Data = Past / Entry-time data**

**Contact Data = Present / Latest data**
