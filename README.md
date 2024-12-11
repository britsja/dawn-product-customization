# Product Grouping Feature for Shopify Dawn Theme

This guide explains how to use the modified Shopify Dawn theme to group products by their metafield and collection to display them on a product page as if they belong to the same product. 

## Key Features
- **Group Products by Color:** Use a custom metafield to group products so they appear as color variants of each other on the product page.
- **Color Swatches:** Display color swatches for all products in the group, linking to their respective product pages.
- **Image-Based Swatches:** Use product images as swatches instead of color names for a more visually appealing design.

---

## How to Use the Product Grouping Feature

### 1. **Add Products to a Group**
To group products, follow these steps:

1. **Set the Collection**:
   - Ensure all products in the group are part of the same collection.
   - The first collection assigned to each product must be identical for grouping to work. For example, if grouping shirts, all products should have "Shirts" as their first collection.

2. **Set the Product Grouping Metafield**:
   - Navigate to the Shopify Admin panel.
   - Open the product you want to group.
   - Locate the `Product Grouping` metafield.
   - Assign the same `Product Grouping` value to all products you want in the same group.
     - Example: Use "darkshirts" for all shirts in the same group.

### 2. **Customize the Product Template**
To enable and configure the product grouping features:

1. Go to your Shopify Admin panel.
2. Open the **Customize** view for your Shopify store.
3. On the product page, locate the **Template** area in the left panel.
4. Select **Variant Picker** under the Template area.
5. Configure the following options:

   - **Show color swatches from different products in Product Group:**
     - Enable this option to display color swatches for all products in the group.

   - **Use the product image as the swatch instead of color name:**
     - Enable this option to display product images as swatches instead of text-based color names.

### 3. **How It Works**
- When viewing a product page, swatches for other products in the group will appear.
- Clicking a swatch opens the product page for the corresponding color.
- Each product is treated as a single-color product but displays the full range of colors available in the group.

---

## Summary of Steps
1. Add products to the same **collection** (first collection must match).
2. Assign the same `Product Grouping` metafield value to all products in the group.
3. Customize the **Variant Picker** settings in the product template.

---

## Example Scenario
**Objective:** Group Black, Red, and Blue T-shirts together.

### Steps:
1. **Set the Collection:** Ensure all T-shirts are part of the "Shirts" collection.
2. **Set the Metafield:** Assign the `Product Grouping` metafield with the value "T-Shirts" to all three products.
3. **Customize Template:** Enable the options for color swatches and image-based swatches in the **Variant Picker** settings.

**Result:** On the product page for the Black T-shirt, you will see swatches for Red and Blue T-shirts. Clicking these swatches will navigate to their respective product pages.

---

## Notes and Best Practices
- **Consistency is Key:** Ensure the first collection and `Product Grouping` metafield values match across all products in the group.
- **Check Metafields:** Access and edit metafields directly in the product admin page.

---

## Demonstration
- **Light Shirts Grouped Together:** https://jan-funky-shirts.myshopify.com/products/t-shirt-pink with color text being used.
- **Dark Shirts Grouped Together:** https://jan-funky-shirts.myshopify.com/products/t-shirt-black with product image swatches used.
- **Collection Showing Individual Products:** https://jan-funky-shirts.myshopify.com/collections/all 

---

## Questions or Feedback?
If you have any questions or need further assistance, feel free to reach out.



