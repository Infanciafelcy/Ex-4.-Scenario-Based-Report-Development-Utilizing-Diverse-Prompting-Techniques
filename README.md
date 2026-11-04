# EX-04: Scenario-Based Report Development Utilizing Diverse Prompting Techniques
## NAME : INFANCIA FELCY P
## REG NO : 212223040067
## 🎯 AIM

To design an AI-powered chatbot for a retail environment using different prompt engineering techniques to handle customer inquiries, provide instant support, and improve customer experience.

## ⚙️ ALGORITHM

**Step 1: Identify the Scenario**

- Select a retail store as the application area.
- Identify common customer queries such as product availability, order tracking, returns, and refunds.

**Step 2: Define Chatbot Requirements**

- Understand customer questions.
- Provide relevant responses.
- Assist with product information.
- Handle complaints and support requests.

**Step 3: Apply Prompt Engineering Techniques**

- Use role-based prompting to define the chatbot's role.
- Use straightforward prompting for simple customer queries.
- Use contextual prompting to handle detailed inquiries.
- Use tabular prompting to organize product information.

**Step 4: Generate Responses**

- Submit customer queries to an AI platform.
- Generate responses using the designed prompts.
- Observe the chatbot's performance.

**Step 5: Evaluate the Output**

- Check response accuracy, clarity, relevance, and response time.
- Identify areas for improvement.

## 💬 PROMPT

**Scenario:** AI-powered Retail Customer Support Chatbot.

**Prompt 1 – Role-Based Prompting**

> Act as a friendly retail customer support assistant. Help customers with product inquiries, order tracking, returns, and refunds. Provide polite and clear responses.

**Prompt 2 – Straightforward Prompting**

> Explain the return policy for a product purchased from an online retail store.

**Prompt 3 – Contextual Prompting**

> A customer ordered a laptop online, but the product arrived damaged. Suggest the steps the customer should follow to request a replacement.

**Prompt 4 – Tabular Format Prompting**

> Create a table showing five common retail customer inquiries, their descriptions, and suitable chatbot responses.

## 📤 OUTPUT

### Sample Chatbot Responses

| Customer Query              | Chatbot Response                                                                                |
| --------------------------- | ----------------------------------------------------------------------------------------------- |
| Where is my order?          | Please provide your order ID to check the delivery status.                                      |
| Can I return a product?     | Yes, eligible products can be returned according to the store's return policy.                  |
| Is this product available?  | Please provide the product name so I can help check availability.                               |
| My product arrived damaged. | Sorry for the inconvenience. Please contact support with your order details and product images. |
| How can I get a refund?     | Refunds are processed according to the store's refund policy after the return is approved.      |

### Chatbot Workflow

```
flowchart TD
 A["Customer Query"] --> B["AI Chatbot"]
 B --> C["Understand Query"]
 C --> D["Generate Response"]
 D --> E{"Query Resolved?"}
 E -->|Yes| F["Provide Solution"]
 E -->|No| G["Escalate to Human Support"]
```

## 📊 RESULT

Successfully designed an AI-powered retail customer support chatbot using different prompting techniques. The chatbot generated responses for common customer inquiries, including product availability, order tracking, returns, and refunds.

The experiment demonstrates how prompt engineering improves chatbot communication, response relevance, and customer support efficienc
