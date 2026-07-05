---
name: 'Backlog '
about: Add an issue in the product backlog
title: ''
labels: ''
assignees: ''

---
---
name: User Story
about: Template for creating user stories
title: 'Story: Query a Subset of Products'
labels: 'user-story'
assignees: ''
---
As a Customer, I need to query a subset of products in the catalog, so that I can quickly find items that match my specific criteria.

### Details and Assumptions
* The product catalog database contains items with attributes for category, price, and availability.
* The query mechanism must filter items efficiently without loading the entire inventory.

### Acceptance Criteria
```gherkin
Given the product catalog contains items with various categories and price ranges
When a customer queries for products in the "Electronics" category with a price between 10 and 50
Then the system returns a subset containing only the products matching both criteria
And all items from other categories or outside that price range are excluded from the results

