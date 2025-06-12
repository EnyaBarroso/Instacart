# Instacart

Instacart is a grocery delivery platform where customers can register an order and have it delivered, similar to Uber Eats and DoorDash. This particular dataset was publicly released by Instacart in 2017 for a Kaggle competition. The actual data can be downloaded directly from the Kaggle competition page.

Data cleaning was performed, and a report was prepared that provides insight into the shopping habits of Instacart customers' shopping habits to inform decisions on inventory and product preferences.
## Data Dictionary:

• **instacart_orders.csv:** Each row corresponds to an order in the Instacart app.

  ○ **'order_id':** ID number that uniquely identifies each order.
  
  ○ **'user_id':** ID number that uniquely identifies each customer's account.
  
  ○ **'order_number':** The number of times this customer has placed an order.
  
  ○ **'order_dow':** Day of the week an order was placed (0 if Sunday).
  
  ○ **'order_hour_of_day':** Time of day the order was placed.
  
  ○ **'days_since_prior_order':** Number of days since this customer placed their previous order.
  
• **products.csv:** Each row corresponds to a unique product that customers can purchase.

  ○ **'product_id':** ID number that uniquely identifies each product.
  
  ○ **'product_name':** Name of the product.
  
  ○ **'aisle_id':** ID number that uniquely identifies each grocery aisle category.
  
  ○ **'department_id':** ID number that uniquely identifies each grocery department.
  
• **order_products.csv:** Each row corresponds to an item ordered in an order.

  ○ **'order_id':** ID number that uniquely identifies each order.
  
  ○ **'product_id':** ID number that uniquely identifies each product.
  
  ○ **'add_to_cart_order':** The sequential order in which each item was added to the cart.
  
  ○ **'reordered':** 0 if the customer has never ordered this product before, 1 if they have.
  
• **aisles.csv**

  ○ **'aisle_id':** ID number that uniquely identifies each grocery aisle category.

  ○ **'aisle':** Aisle name.
  
• **departments.csv**

  ○ **'department_id':** ID number that uniquely identifies each grocery department.
  
  ○ **'department':** Department name.

## Results

The results obtained were:

• **Most frequently added to the top of the cart:**

  ○ Banana (top position).

  ○ Organic whole milk.

  ○ Organic strawberries.

  ○ Organic Hass avocado.

• **Observed patterns:**

  ○ Fresh staples: Fruits (banana, strawberries, avocado), dairy (milk, half & half), and vegetables (spinach, onion) dominate the list.

  ○ Organic products: 8 of the 15 items are organic, suggesting a preference for healthy/natural products.

  ○ Beverages: Spring water and sparkling water are also prioritized.

🔍 **Psychological/Behavioral Interpretation:**

• Focus on essentials: Customers begin their shopping with basic, perishable, or high-needs products (e.g., milk, fruit), leaving non-essentials for later.

• Health and Convenience: The high presence of organic products reflects a trend toward healthy choices.

• Shopping list habits: Many shoppers follow a mental order (e.g., fresh first, then canned).

📊 **Actionable Insights:**

• Physical store placement:

  ○ Place these products at the back of the store to increase exposure to other items ("must-visit" strategy).
  
• Digital Marketing:

  ○ Highlight them on the front page of the e-commerce site or with "frequently purchased" banners.

  ○ Promotional bundles (e.g., "Healthy Breakfast Kit" with banana + milk + strawberries).
  
• Inventory Management:

  ○ Ensure sufficient stock of these products, especially during peak times (mornings/weekends).
  
• Cross-recommendations:

  ○ If a customer adds banana first, suggest additional options (e.g., cereal or honey).

## Final Conclusions

People tend to buy more frequently, products with short shelf lives, such as:

🍌 Fruits 🥬 Vegetables

Since these are items consumed daily, and due to their short shelf life, they need to be consumed within a maximum of one week of purchase, they are therefore added first to customers' carts.

🥫 Products with expiration dates (and therefore a longer shelf life) are products that customers can see being purchased once or twice a month, since if they make a purchase, they are unlikely to finish the product in less than one week, as there is no concern that the product will expire.

🧼 On the other hand, personal hygiene products are not food products, so their shelf life is much longer than any other product, so they are purchased less frequently.

Therefore, the products that should be stocked in the store are fresh ones, such as fruits and vegetables, as they generate the most profit and the most traffic in the store. Therefore, proper care must be taken to maintain or improve their quality and preservation.
