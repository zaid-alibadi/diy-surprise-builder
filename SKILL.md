---

name: diy-surprise-builder
description: Discover fun DIY projects from everyday products using local AI
metadata:

homepage: https://github.com/zaid-alibadi/diy-surprise-builder

DIY Surprise Builder

An AI-powered DIY inspiration skill that helps users discover fun, seasonal, creative, and unexpected projects from ordinary products.

The experience is inspired by real-world shopping behavior, basket-building intelligence, recommendation systems, and DIY trend discovery.

Examples:

* Tomato cage → DIY Christmas tree
* Pool noodles → Garage wall protector
* Wooden pallets → Vertical garden
* PVC pipes → Backyard sprinkler toy

The skill supports:

* Product scanning
* Image-based inspiration
* Multi-item project detection
* Recommendation ranking
* Seasonal DIY exploration

Designed to work offline after installation using lightweight on-device AI models and embedded project knowledge.

Files

* manifest.json: Skill configuration and metadata
* README.md: Skill overview and setup
* prompts/system_prompt.txt: Core DIY assistant instructions
* workflows/workflow.json: Workflow definition
* data/projects.json: Embedded DIY project mappings
* assets/icon.png: Skill icon
* assets/banner.png: Skill banner

Prompts / Triggers

* “What can I build with this?”
* “Give me a fun DIY project”
* “Surprise me with a DIY idea”
* “What project uses this item?”
* “Scan this product”
* “Show creative ideas for this”
* “What do people build with this?”
* “Find a seasonal DIY project”

Instructions

Use local vision understanding to detect:

* products
* tools
* materials
* seasonal objects

Use embedded DIY project mappings to infer:

* project ideas
* required items
* complementary products
* seasonal relevance

Generate:

* beginner-friendly instructions
* estimated project cost
* project difficulty
* estimated completion time
* optional upgrades

Prioritize:

* creativity
* beginner friendliness
* seasonal inspiration
* basket-building opportunities
* fun discovery experiences

