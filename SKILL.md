Here’s a strong SKILL.md file you can place in the root of the repo.

DIY Surprise Builder

Overview

DIY Surprise Builder is an AI-powered discovery skill designed for Google AI Edge Gallery.

The skill helps customers discover fun, creative, seasonal, and unexpected DIY projects using ordinary products commonly found at Lowe’s.

Instead of traditional home improvement assistance, this experience focuses on inspiration, exploration, and project creativity powered by recommendation intelligence and lightweight on-device AI.

Examples:

* Tomato cage → DIY Christmas tree
* Pool noodles → Garage wall protector
* Wooden pallets → Vertical garden
* PVC pipes → Backyard sprinkler toy

The skill is designed to work offline after installation using local AI models and embedded project knowledge.

⸻

Core Features

1. Scan & Inspire

Users can:

* Scan a product
* Upload a photo
* Scan a barcode
* Speak a product name

The skill detects the item and suggests fun DIY projects involving that product.

Example:

“What fun things can I build with this tomato cage?”

⸻

2. Surprise Me Mode

Generates random project inspiration based on:

* Seasonality
* Trends
* DIY patterns
* Family-friendly projects
* Holiday themes
* Backyard ideas

Example:

“Build a floating herb garden using gutters.”

⸻

3. Multi-Item Project Detection

Users can scan multiple items together.

Example:

* tomato cage
* string lights
* zip ties

The skill infers:

“Looks like you may want to build a DIY Christmas tree.”

⸻

AI Components

Vision Understanding

Local lightweight vision models detect:

* Products
* Tools
* Seasonal items
* Materials
* DIY objects

⸻

DIY Pattern Discovery Engine

Uses embedded project mappings inspired by:

* Basket building
* Recommendation systems
* Co-purchase relationships
* Seasonal buying behavior
* DIY trends

Example mapping:

{
  "anchor": "tomato cage",
  "project": "DIY Christmas Tree",
  "required_items": [
    "string lights",
    "zip ties",
    "extension cord"
  ]
}

⸻

Lightweight SLM Generation

The skill uses small language models to generate:

* Project instructions
* Creative project names
* Safety notes
* Recommended materials
* Beginner guidance

⸻

Recommendation Ranking

Recommendations are ranked using:

* Essentiality
* Budget friendliness
* Seasonal relevance
* Beginner friendliness
* Creativity score

⸻

Example User Flows

Example 1 — Tomato Cage

Input:

“What can I build with this?”

Output:

* DIY Christmas Tree
* Estimated cost
* Difficulty
* Time required
* Recommended items

⸻

Example 2 — Wooden Pallet

Suggested projects:

* Coffee table
* Vertical garden
* Patio wall decor
* Outdoor movie stand

⸻

Future Enhancements

* Pinterest/TikTok trend integration
* Personalized project recommendations
* In-store discovery mode
* Local vector search
* Offline multimodal embeddings
* Gemma-based reasoning
* Shopping cart export
* Visual project previews

⸻

Target Use Cases

* DIY inspiration
* Seasonal discovery
* Family projects
* Beginner-friendly creativity
* Basket building
* Retail AI demos
* Edge AI demonstrations

⸻

Technical Goals

* Offline-first architecture
* On-device inference
* Lightweight retrieval
* Small language models
* Local recommendation intelligence
* Edge AI experimentation

⸻

Author

Zaid Alibadi
