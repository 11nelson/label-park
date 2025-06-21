# **App Name**: NutriCheck Korea

## Core Features:

- Manual Data Entry: Allow direct input, modification, and deletion of nutritional information for in-house products (yogurt and granola).
- Public Data Integration: Connect to the 'Processed Food Nutritional Information DB' API from the Public Data Portal (https://www.data.go.kr/data/15127578/openapi.do) to query data and store relevant information in the Firestore DB.
- Compliance Review: Automatically assess the suitability of 'Nutrient Emphasis Display' according to the 「Standards for Labeling of Foods, etc.」 based on the entered nutritional content of the product.
- AI-Powered Labeling Assistance: AI-powered analysis to determine optimal label placements and font sizes for nutritional information to maximize readability and regulatory compliance. This feature will act as a tool to recommend the most effective layout based on the product's dimensions and regulatory requirements.
- Data Visualization: Display product nutritional data in a clear, structured format within the Firestore Studio UI.
- API Search Interface: Provide a user-friendly interface for searching the public data API, viewing results, and importing selected data into the database.

## Style Guidelines:

- Primary color: Soft, natural green (#8FBC8F) to represent health and natural ingredients.
- Background color: Light beige (#F5F5DC) to provide a clean and calming backdrop.
- Accent color: Muted orange (#D2691E) to highlight key information and calls to action related to the granola or yogurt.
- Body font: 'PT Sans' (sans-serif) for readability and a modern feel.
- Headline font: 'Alegreya ' (serif) paired with 'PT Sans' for body text, providing an elegant but still intellectual feel.
- Use minimalist, easily recognizable icons for each nutrient category, aligning with South Korean standards.
- Employ a clean, tabular layout for nutritional data display to ensure clarity and ease of comparison.