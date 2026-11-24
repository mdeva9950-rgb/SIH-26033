
# Smart India Hackathon Workshop

**Date:** 24 November 2026  
**Reference Number:** 26017105 
**Name:** Devandra Prasad M

---

## Problem Title

**SIH 26033: Multiple intermediaries reduce farmers' earnings and increase consumer prices.**

## Problem Creator's Organization

Ministry of Consumer Affairs, Food & Public Distribution

## Theme

Agriculture, FoodTech & Rural Development

---

## Problem Description

In the traditional agricultural supply chain, farmers often depend on several intermediaries to sell their produce. Each intermediary adds a margin, reducing the amount farmers receive while increasing the final price paid by consumers.

The expected solution is a digital marketplace that:

- Connects farmers and Farmer Producer Organizations (FPOs) directly with consumers and bulk buyers.
- Provides logistics support for transporting agricultural products.
- Uses AI for demand forecasting and route optimization.

### Expected Benefits

- Better prices for farmers.
- Lower prices for consumers.
- Reduced supply-chain inefficiencies.

---

## Proposed Solution

We propose **FarmConnect**, a digital marketplace that brings farmers, FPOs, consumers, retailers and bulk buyers onto one platform.

Farmers can register, create product listings, add quantities, set prices and upload product images. Buyers can search for available products, compare prices and place orders directly with farmers.

The platform will also include logistics support to coordinate pickup and delivery. AI-based demand forecasting can estimate which products may be in demand, helping farmers plan their production and sales. Route optimization can help delivery partners select efficient routes.

### How It Addresses the Problem

- Reduces dependence on multiple intermediaries through direct connections.
- Gives farmers more control over product listings and prices.
- Provides consumers with better price transparency.
- Connects farmers, buyers and logistics providers through one platform.
- Helps reduce transportation delays and supply-chain inefficiencies.

### Innovation and Uniqueness

The main innovation is combining direct selling, transparent pricing, logistics coordination and AI-assisted planning in one simple digital platform.

Unlike traditional marketplaces, FarmConnect focuses on connecting farmers directly with consumers and bulk buyers while supporting transportation and demand forecasting.

---

## Technical Approach

### Technologies Used

| Component | Technology |
|---|---|
| Frontend | HTML, CSS, JavaScript, Bootstrap |
| Backend | Python, Django |
| Database | SQLite, PostgreSQL |
| AI/ML | Pandas, Scikit-learn |
| Maps and Routing | Map API |
| Notifications | Email and SMS |

### Implementation Process

1. Create separate registration and login options for farmers, buyers and delivery partners.
2. Build farmer profiles and product-listing pages.
3. Develop product search, price comparison and order placement.
4. Add an order-management dashboard.
5. Implement logistics coordination and delivery tracking.
6. Develop a demand-forecasting model using available sales data.
7. Add route suggestions for delivery planning.
8. Test the prototype using sample farmer, product and order data.

### System Workflow

```text
       FARMER / FPO
             |
             v
      USER REGISTRATION
             |
             v
       PRODUCT LISTING
             |
             v
       DIGITAL MARKETPLACE
             |
       +-----+------+
       |            |
       v            v
   CONSUMERS     BULK BUYERS
       |            |
       +-----+------+
             |
             v
       ORDER PLACEMENT
             |
             v
      FARMER CONFIRMATION
             |
             v
      LOGISTICS MANAGEMENT
             |
             v
       DELIVERY TRACKING
             |
             v
       ORDER COMPLETED
```

### AI Integration

**1. AI-Based Demand Forecasting**

The system analyzes historical sales information and market demand to estimate which agricultural products may be needed in the future. This helps farmers make better decisions about product availability and sales planning.

**2. AI-Based Route Optimization**

The system uses delivery locations and route information to suggest efficient transportation routes, helping reduce unnecessary travel time and delivery costs.

---

## Feasibility and Viability

The proposed solution is feasible as a web-based platform using commonly available technologies and open-source tools.

The initial prototype can focus on farmer registration, product listings, buyer search, ordering and delivery tracking. Advanced AI features can be integrated in later development stages.

### Potential Challenges

- Limited digital knowledge among some farmers.
- Internet connectivity problems in rural areas.
- Maintaining accurate product quality and quantity information.
- Transportation costs and delivery availability.
- Limited historical data for accurate demand forecasting.
- Payment security and order-management issues.

### Strategies to Overcome Challenges

- Provide a simple and mobile-friendly user interface.
- Include regional language support.
- Allow FPOs to help farmers manage their accounts.
- Work with verified logistics partners.
- Improve forecasting accuracy as more sales data becomes available.
- Implement secure payment systems and transparent order policies.

---

## Impact and Benefits

### Benefits for Farmers

- Direct access to consumers and bulk buyers.
- Better control over product prices.
- Reduced dependency on multiple intermediaries.
- Improved visibility of market demand.
- Better opportunities to sell agricultural products.

### Benefits for Consumers

- Access to agricultural products directly from farmers.
- Better price transparency.
- More product choices.
- Convenient online ordering.

### Benefits for the Supply Chain

- Improved coordination between farmers, buyers and delivery partners.
- Reduced unnecessary transportation delays.
- Better matching of supply with demand.
- Potential reduction in unsold agricultural products.
- Improved efficiency in agricultural distribution.

### Social and Economic Impact

FarmConnect aims to improve farmers' earning opportunities while making agricultural products more accessible and affordable for consumers. It also encourages digital adoption in rural agriculture and supports a more transparent agricultural marketplace.

---

## Research and References

1. Smart India Hackathon Problem Statement - SIH 26033.
2. [e-NAM - National Agriculture Market](https://www.enam.gov.in/)
3. [Ministry of Consumer Affairs, Food & Public Distribution](https://consumeraffairs.nic.in/)

---

## Conclusion

FarmConnect provides a digital approach to reducing the gap between farmers and consumers. By combining direct marketplace access, logistics coordination and AI-based demand forecasting, the proposed solution aims to create a more transparent and efficient agricultural supply chain.

**Note:** FarmConnect is a proposed solution. Its performance and benefits will need to be validated through prototype development and pilot testing.
