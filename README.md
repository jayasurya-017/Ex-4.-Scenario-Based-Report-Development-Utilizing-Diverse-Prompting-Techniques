# Experiment No. 4 – Scenario-Based Report Development Utilizing Diverse Prompting Techniques

## Objective

The objective of this experiment is to design and develop an AI-powered chatbot for a retail environment that can handle customer inquiries, provide efficient support, and improve the overall customer experience. Different prompting techniques are used to evaluate the chatbot's response quality, efficiency, and user interaction.

---

# Aim

To design and evaluate an AI-powered retail customer support chatbot using various prompting techniques such as Zero-shot, One-shot, Few-shot, Role-based, and Instruction-based prompting, and compare the quality of the generated responses.

---

# Algorithm

1. Identify the retail customer support use case.
2. Select common customer scenarios such as product inquiry, order tracking, return/refund, and troubleshooting.
3. Choose different prompting techniques:
   - Zero-shot Prompting
   - One-shot Prompting
   - Few-shot Prompting
   - Role-based Prompting
   - Instruction-based Prompting
4. Design suitable prompts for each scenario.
5. Execute the prompts using an AI model.
6. Collect the generated responses.
7. Compare the responses based on clarity, accuracy, usefulness, efficiency, and customer experience.
8. Document the observations and determine the most effective prompting technique.

---

# Prompt

## Scenario 1 – Product Inquiry

### Zero-shot Prompt

Do you have wireless headphones available?

### One-shot Prompt

How can I cancel an order?

### Few-shot Prompt

Do you offer warranty on electronics? How long does delivery usually take?

### Role-based Prompt

You are a professional retail customer support agent. A customer asks about wireless headphones. Respond politely and clearly.

### Instruction-based Prompt

Provide a short and clear answer about the availability of wireless headphones.

---

## Scenario 2 – Return and Refund

### Zero-shot Prompt

What is your return policy?

### One-shot Prompt

How can I cancel an order?

### Few-shot Prompt

Do you offer warranty on electronics? How long does delivery usually take?

### Role-based Prompt

You are a retail customer support agent. Explain the return policy clearly and politely.

### Instruction-based Prompt

Explain the return policy in 2–3 simple sentences.

---

## Scenario 3 – Order Tracking

### Zero-shot Prompt

Where is my order #12345?

### One-shot Prompt

How can I cancel an order?

### Few-shot Prompt

Do you offer warranty on electronics? How long does delivery usually take?

### Role-based Prompt

You are a retail support agent. A customer asks about their order status. Respond professionally.

### Instruction-based Prompt

Provide the order status in 2–3 short sentences.

---

## Scenario 4 – Product Troubleshooting

### Zero-shot Prompt

My blender is not working. What should I do?

### One-shot Prompt

How can I cancel an order?

### Few-shot Prompt

Do you offer warranty on electronics? How long does delivery usually take?

### Role-based Prompt

You are a retail customer support agent. Help the customer troubleshoot a faulty blender politely.

### Instruction-based Prompt

Provide 2–3 simple troubleshooting steps.

---

# Output

## Scenario 1 – Product Inquiry

### Zero-shot

Yes, wireless headphones are available in different models and price ranges.

### One-shot

Orders can be canceled within 24 hours through the **My Orders** section.

### Few-shot

Electronics include a one-year warranty and delivery usually takes 3–5 business days. Wireless headphones are available in multiple models.

### Role-based

Thank you for contacting us. We currently offer a wide range of wireless headphones from different brands. Please let us know your preferred budget so we can recommend the best option.

### Instruction-based

Yes, wireless headphones are available in various models.

---

## Scenario 2 – Return and Refund

### Zero-shot

Products can be returned within 30 days if they are unused.

### One-shot

Orders can be canceled within 24 hours.

### Few-shot

Most products can be returned within 30 days and electronic products include a warranty.

### Role-based

You may return unused products within 30 days in their original packaging. Once approved, your refund will be processed within a few business days.

### Instruction-based

Returns are accepted within 30 days with the original receipt and packaging.

---

## Scenario 3 – Order Tracking

### Zero-shot

Your order is currently in transit.

### One-shot

Orders can be canceled within 24 hours.

### Few-shot

Orders usually arrive within 3–5 business days and can be tracked using the order ID.

### Role-based

Your order has been shipped successfully and is currently on the way. You can monitor its delivery status using your tracking number.

### Instruction-based

Your order is in transit. Track it using your order number.

---

## Scenario 4 – Product Troubleshooting

### Zero-shot

Check whether the blender is properly connected to the power supply.

### One-shot

Orders can be canceled within 24 hours.

### Few-shot

Try reconnecting the power cord, reset the blender, and verify the warranty if the issue continues.

### Role-based

Please ensure the blender is connected properly, the jar is correctly locked, and the power outlet is functioning. If the problem continues, our support team will be happy to assist further.

### Instruction-based

Check the power connection, ensure all parts are assembled correctly, and contact customer support if the problem continues.

---

# Comparative Analysis

| Scenario | Technique | Inquiry Handling | Efficiency | Customer Experience |
|----------|-----------|------------------|------------|---------------------|
| Product Inquiry | Zero-shot | Basic | Fast | Low |
| Product Inquiry | One-shot | Clear | Efficient | Moderate |
| Product Inquiry | Few-shot | Detailed | Moderate | High |
| Product Inquiry | Role-based | Professional | High | Excellent |
| Product Inquiry | Instruction-based | Simple | Very High | Good |
| Return & Refund | Zero-shot | Basic | Fast | Average |
| Return & Refund | One-shot | Clear | Efficient | Good |
| Return & Refund | Few-shot | Detailed | Moderate | High |
| Return & Refund | Role-based | Structured | High | Excellent |
| Return & Refund | Instruction-based | Simple | Very High | Good |
| Order Tracking | Zero-shot | Basic | Fast | Average |
| Order Tracking | One-shot | Clear | Efficient | Good |
| Order Tracking | Few-shot | Detailed | Moderate | Good |
| Order Tracking | Role-based | Professional | High | Excellent |
| Order Tracking | Instruction-based | Simple | Very High | Good |
| Troubleshooting | Zero-shot | Basic | Fast | Average |
| Troubleshooting | One-shot | Structured | Efficient | Good |
| Troubleshooting | Few-shot | Context-rich | Moderate | High |
| Troubleshooting | Role-based | Empathetic | High | Excellent |
| Troubleshooting | Instruction-based | Simple | Very High | Good |

---

# Result

The experiment demonstrated that different prompting techniques produce different styles and qualities of responses.

- **Role-based prompting** produced the most professional, empathetic, and customer-friendly responses, resulting in the best overall customer experience.
- **Instruction-based prompting** generated the quickest and most concise responses, making it suitable for simple customer queries.
- **Few-shot prompting** provided more detailed and context-aware responses but required additional examples and was slightly less efficient.
- **Zero-shot** and **One-shot prompting** generated faster responses but lacked personalization and detailed context compared to the other techniques.

Thus, the AI-powered retail customer support chatbot was successfully evaluated using diverse prompting techniques, and the effectiveness of each technique was analyzed based on response quality, efficiency, and customer experience.
