# WORKSHEET 2
## Identify Objects, Classes, and Relationships

**Instructions:** Use the process and proposed system from Worksheet 1 to complete this worksheet.

---

## Part 1. Identify the Objects

Identify the important people, things, records, transactions, or concepts that your proposed system needs to represent.

**Guide Question:**

If you were going to create a program for this process, what things would the program need to represent?

| No. | Object | Description |
|:---:|---|---|
| 1 | Student | Files and requests the OTC form |
| 2 | Management_Committee | Reviews and approves the submitted OTC form by the student |
| 3 | OTC_Form | File containing the request by the student representative to the MANCOM |
| 4 | Email | System message sent to the involved students and teachers regarding the approval status of the OTC form |
| 5 | Teacher | Receives the email regarding the OTC form's approval status |

### Object Evaluation

For each identified object, ask:

- Does it play an important role in the process?
- Does it contain information?
- Does it perform an action?
- Does it interact with another object?
- Does the proposed system need to keep track of it?

**Reminder:** Remove objects that are not necessary for your proposed system.

---

## Part 2. Analyze Object Interactions

Determine how your identified objects interact with one another.

**Example:** `Student → submits → Request`

| No. | Object 1 | Interacts | Object 2 |
|:---:|---|---|---|
| 1 | Student | Files / Requests | OTC_Form |
| 2 | Management_Committee | Reviews / Approves | OTC_Form |
| 3 | OTC_Form | Emailed to | Student / Teachers |

---

## Part 3. Identify Possible Classes

Determine which objects can become classes in your proposed system.

Not every object needs to become a class. Choose only the objects that are important to your proposed system.

| No. | Class | What does it represent? |
|:---:|---|---|
| 1 |Student |The primary users of this system |
| 2 |Management_Committee |The ones receiving the requests submitted by the students |
| 3 |OTC_Form |The object being interacted with by the students and MANCOM |

---

## Part 4. Class Analysis

Analyze the attributes and methods of each identified class.

### Class No. 1

**Class Name:** Student

**Purpose:**  
Represents the student requesting an OTC approval

#### Attributes

| Attribute | Description |
|---|---|
| | |
| | |
| | |
| | |

#### Methods

| Method Name | What does it do? |
|---|---|
| | |
| | |
| | |
| | |

---

### Class No. 2

**Class Name:** __________________________________

**Purpose:**  
__________________________________________________

#### Attributes

| Attribute | Description |
|---|---|
| | |
| | |
| | |
| | |

#### Methods

| Method Name | What does it do? |
|---|---|
| | |
| | |
| | |
| | |

---

**Additional Classes:** Add another copy of the Class Analysis section for each additional class you identify.

**Reminder:** Keep your project simple. Avoid creating unnecessary classes.

---

## Part 5. Identify Class Relationships

Determine how your identified classes are related to one another.

| No. | Class 1 | Relationship | Class 2 | Why are they related? |
|:---:|---|---|---|---|
| 1 | | | | |
| 2 | | | | |
| 3 | | | | |
| 4 | | | | |
| 5 | | | | |
| 6 | | | | |

### Relationship Types

| Relationship | Description |
|---|---|
| **Association** | Two classes interact with one another. |
| **Aggregation** | One class groups or contains objects that can exist independently. |
| **Composition** | One class strongly owns another object. |
| **Inheritance** | One class is a specialized version of another class. |

**Reminder:** Use only the relationship types that make sense for your proposed system. Not all relationship types are required.
