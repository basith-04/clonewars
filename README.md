# Airbnb UI Clone — µLearn Clone Wars 

A responsive and interactive **Airbnb-inspired frontend clone**, vibe coded as part of the **µLearn Clone Wars** program conducted at our college.

**1st Prize — µLearn Clone Wars**

### Built by
- **Ashin Chacko**
- **Abdul Basith P V**

---

## About the Challenge

The challenge was simple: **recreate the UI/UX of a real-world application using AI coding agents within a very limited amount of time.**

We chose **Airbnb**.

But instead of building only a visually similar landing page, our goal was to make as much of the interface **actually functional** as possible using mock data.

The complete project was built in approximately **30 minutes**.

---

## Challenge Constraints

The competition had some interesting limitations:

- No reference images or screenshots could be given to the coding agent.
- No `design.md` or pre-written design specification could be provided.
- The application had to be built primarily by **prompting AI coding agents**.
- The final application had to be deployable through **GitHub Pages**.
- We had only around **30 minutes** to build the project.

This meant we had to rely on prompting, iteration and the coding agents' understanding of the product rather than feeding them a prepared design.

---

## What We Built

Our main focus was making the clone **functional rather than just visually similar**.

The application includes:

- Airbnb-inspired responsive UI
- Homes
- Experiences
- Services
- Destination search
- Date selection
- Guest selection
- Listing cards and carousels
- Listing detail views
- Wishlist / saved properties
- Mock booking interactions
- Search and filtering
- Responsive mobile interface
- Mobile search experience
- Destination and inspiration sections
- Responsive navigation and footer

All data and interactions are handled entirely on the frontend using **mock/local data**.

---

## Extra Features

Once the core Airbnb experience was working, we used the remaining time to add some features beyond a basic clone.

###  AI Travel Assistant

We added a mock AI travel assistant that can help users discover content within the application.

It can demonstrate interactions such as:

- Finding stays within a budget
- Recommending properties
- Suggesting experiences
- Answering travel-related questions
- Helping users explore the available mock listings

The assistant uses local predefined logic and existing mock data.

**No external AI API is used.**

---

###  AI Trip Planner

Users can generate a mock travel itinerary based on inputs such as:

- Destination
- Number of days
- Number of travellers
- Interests

The planner combines existing **Homes, Experiences and Services** to create a simple itinerary.

Everything is generated locally from mock data.

---

###  Surprise Me

The **Surprise Me** feature provides a quick travel suggestion by selecting a combination of:

- Destination
- Stay
- Experience
- Service

It uses the existing dataset to create a simple mock getaway recommendation.

---

###  Compare Stays

Users can select properties and compare them side by side.

The comparison includes information such as:

- Price
- Rating
- Location
- Guest capacity
- Bedrooms
- Beds
- Amenities

The interface can also provide a simple mock AI-style recommendation based on the compared properties.

---

###  Map Mode

We created an Airbnb-inspired map browsing experience without using:

- Google Maps
- Mapbox
- External map APIs

Instead, the map is a lightweight frontend simulation using HTML and CSS.

It includes:

- Property price markers
- Selected marker states
- Property preview cards
- List / Map switching
- Responsive mobile map view

The goal was to recreate the **interaction and feel of map-based property discovery**, rather than provide geographically accurate mapping.

---

## Why a Single HTML File?

One noticeable thing about this repository is that almost the entire application lives inside:

```text
index.html
```

This was **intentional**.

One of the requirements was that the final project had to be deployed through **GitHub Pages**, and we had only around **30 minutes** to build everything.

Instead of spending valuable competition time setting up:

- Frameworks
- Build pipelines
- Routing
- Package management
- Backend services
- Deployment configurations
- Environment variables

we decided to keep the architecture as simple as possible.

The single `index.html` contains most of the:

- HTML structure
- CSS styling
- Responsive design
- JavaScript interactions
- Mock listing data
- Search logic
- Filtering
- Wishlist logic
- AI assistant logic
- Trip planner
- Compare functionality
- Mock map
- Other UI interactions

Images are loaded through cloud-hosted URLs, so we also avoided maintaining a local image asset pipeline.

### Why this worked well for the challenge

Using a single HTML file meant:

- **Instant GitHub Pages deployment**
- No `npm install`
- No build step
- No framework configuration
- No routing configuration
- No backend deployment
- No dependency problems
- Faster debugging
- Faster AI-generated edits
- More time for visible UI and functionality

Our strategy was essentially:

> **One HTML file. Mock data. Zero backend. Zero build process. Maximum functional UI within 30 minutes.**

This was a deliberate trade-off between **production architecture and development speed**.

For a production application, the code would obviously benefit from being separated into components, modules and services with a proper backend where required.

For a **30-minute vibe-coding competition**, however, keeping everything simple gave us more time to focus on what actually mattered for the challenge.

---

## Vibe Coding

This project was primarily built through **vibe coding**.

Rather than manually writing every component from scratch, we described the required:

- UI
- Layout
- Interactions
- Responsive behavior
- Features
- Improvements

through prompts and worked with coding agents to generate and modify the implementation.

We primarily used tools such as:

- **Codex**
- **Antigravity**

The challenge became less about manually typing every line of code and more about **communicating the desired result clearly, evaluating the generated output and quickly iterating on it.**

---

## Internet Issues During the Build

One unexpected challenge was the **internet connection during the competition**.

Both Codex and Antigravity occasionally took significantly longer than expected to complete operations because of connectivity issues.

With only around 30 minutes available, waiting several minutes for an agent operation was expensive.

Because of this, we adapted our prompting strategy:

- Keep tasks small
- Ask for direct edits
- Avoid unnecessary research
- Avoid installing additional packages
- Avoid unnecessary architectural changes
- Prioritize visible functionality
- Iterate feature-by-feature

This was another reason why the **single-file approach** worked well for us.

---

## Tech Stack

The project intentionally uses a minimal stack:

```text
HTML
CSS
JavaScript
Local / Mock Data
Cloud-hosted Image Assets
localStorage
GitHub Pages
```

There is:

-  No backend
-  No database
-  No real authentication
-  No real payment processing
-  No external AI API
-  No mapping API
-  No build system required

The goal was not production infrastructure.

The goal was to build the **most complete and interactive frontend experience possible within the available time.**

---

## Our Approach

With only around **30 minutes**, our priorities were:

1. Recreate the recognizable Airbnb visual language.
2. Implement the major navigation and browsing flows.
3. Make UI elements functional instead of decorative.
4. Make the application responsive.
5. Use mock data instead of spending time building infrastructure.
6. Add additional features once the core clone was functional.
7. Keep deployment as simple as possible.
8. Get the final application running on GitHub Pages.

Rather than trying to build a production Airbnb architecture, we optimized everything around one constraint:

**time.**

---

## Running Locally

There is no build process.

Clone the repository:

```bash
git clone <repository-url>
cd <repository-name>
```

Then simply open:

```text
index.html
```

in your browser.

Alternatively, serve the directory using any basic static development server.

---

## Deployment

The application was designed specifically to work as a static website.

It can be deployed directly using **GitHub Pages** without requiring:

- Server infrastructure
- Environment variables
- API keys
- Database configuration
- Build commands

---

## Result

 **1st Prize — µLearn Clone Wars**

Built in approximately **20 minutes** through prompt-driven development.

### Team

**Ashin Chacko**  
**Abdul Basith P V**

---

## Disclaimer

This project was created for an **educational college competition** and is intended as a UI/UX cloning and AI-assisted development experiment.

It is not affiliated with, endorsed by, sponsored by, or connected to Airbnb, Inc.

Airbnb and its associated names, trademarks and branding belong to their respective owners.