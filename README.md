# Vue Store Locator App

This project is a **study project** designed to explore and experiment with the functionalities of **Mapbox**. The goal was to understand how Mapbox can be integrated into a Vue 2 / Nuxt 2 application, specifically for implementing map-based features like store locators, which can be seen in the two demo examples.

The app uses **Vuex** to manage a list of airports and demonstrates the interaction between the map and the list of locations via **Mapbox APIs**.

## Features

- Displays a list of airports.
- Interactive map using **Mapbox** to show airport locations.
- **Vuex** for state management across the app.
- Easy navigation through a list of airports and their locations on the map.
- Can add, edit and remove airports.

## Demos

Here are two live demos showcasing similar store locator functionalities:

- **[Credit Agricole Conti Store Locator](https://www.credit-agricole.it/apri-il-conto/scegli-filiale?account_type=ONL)** - Find the nearest branch locations for opening an online account.
- **[Remax Property Search Map](https://www.remax.it/trova/ricerca/vendita?agency_group_id&agency_id&agent_id&bathrooms&collection&commercial&energy_class[]=1&energy_class[]=8&lifestyle&location&location_type&order=sell_price-desc&price&program&rooms&size&unit_type_id=1&yard_id)** - A property search map for listings in the real estate market.

## Tech Stack

- **Nuxt.js 2** (Vue 2) for server-side rendering and routing.
- **Vuex** for state management.
- **Mapbox API** for interactive maps and geolocation.

## Prerequisites

- **Node.js 10** or higher
- **Yarn** as the package manager

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/bluke93/vue-store-locator.git
   cd vue-store-locator
   ```

2. Install dependencies:
   ```bash
   yarn install
   ```

3. Set Node 10 as the version if you're using **nvm**:
   ```bash
   nvm use 10
   ```

## Development

To run the app locally in development mode:

1. Start the development server with hot reloading:
   ```bash
   yarn dev
   ```

2. The app will be available at `http://localhost:3000` in your browser.
