💧 Water Filtration Systems Initiative
Super Organization of Science, Inc. (SoS)

Welcome to the water-filtration-systems repository. This is the official open-source blueprint repository for localized, decentralized water security. Operating out of our flagship prototype at the SOS Community Lab (SOSCL) in Newport, Kentucky, our goal is simple: decouple clean drinking water from commercial utility grids using the power of open-source science.

🔬 Core Philosophy & Rules

    The Anti-Patent Mandate: Everything in this repository belongs to the global human collective. These blueprints cannot be patented, locked behind corporate paywalls, or monetized for exclusive private gain.

    Radical Non-Invasiveness: Urban populations and apartment dwellers are frequently restricted by landlords, leases, and zoning codes. Our systems are engineered to be modular, packable, and tenant-friendly—requiring zero permanent plumbing modifications or wall-cutting.

    The Contribution Economy: Build a system, test its metrics, fork the repository, and push your data optimizations back to the main branch. Status is earned through active contribution.

🗂️ Repository Architecture

This repository is structured into modular components so that makers, fabricators, and Raspberry Pi public kiosks can easily parse, download, and replicate the builds:
Plaintext

water-filtration-systems/

│

├── README.md                      <-- Overview, BOM, and core theory

├── LICENSE                        <-- CERN-OHL-S / CC BY-SA 4.0 license files

├── bill-of-materials/             <-- Cost spreadsheets and upcycled parts lists

├── CAD-and-STLs/                  <-- 3D printable brackets, shims, and manifold parts

├── assembly-manuals/              <-- Step-by-step text and visual guides

└── sensor-code/                   <-- IoT telemetry and Raspberry Pi data-logging scripts

🛠️ The Dual-Source Closed-Loop Architecture

To achieve absolute water self-reliance in a municipal environment, our deployment relies on a standardized, modular multi-stage infrastructure:
1. Primary Collection: Urban Rainwater Harvesting

    First-Flush Diverters: A simple, mechanical PVC pipe configuration that intercepts and isolates the initial rooftop runoff containing 90% of atmospheric dust and debris via a floating ball valve, routing only clean subsequent water into storage.

    Modular Storage Matrix: Scalable arrays utilizing interconnected, food-safe Intermediate Bulk Container (IBC) totes rather than heavy, permanent concrete cisterns.

2. The Multi-Stage Purification Train (Potable Output)

Raw collection is pushed through a rigorous, low-maintenance purification stack to guarantee drinkable safety without corporate chemicals:

    Stage 1 (Mechanical Sediment): 5- to 20-micron spun-polypropylene cartridge filters to strip out suspended particulate matter.

    Stage 2 (Activated Carbon Block): 0.5- to 1-micron carbon blocks to adsorb chemical contaminants, chlorine, VOCs, and heavy metals.

    Stage 3 (Sub-Micron Ultrafiltration): 0.02-micron hollow fiber membranes that physically block bacteria (E. coli) and protozoan cysts (Giardia).

    Stage 4 (IoT Sensor & Optional UV): Real-time Total Dissolved Solids (TDS) monitoring via low-power Raspberry Pi microcontrollers paired with a 12V UV sterilization loop.

3. Renter-Friendly "Over-the-Sill" Deployment

To bypass landlord restrictions, purified water is fed indoors through a thin, flexible food-grade silicone tube passing through a custom insulated window-insert panel (mirroring portable AC unit brackets), feeding a dedicated countertop dispenser without leaving structural damage.

🚀 Getting Started & Replication

    Clone or Sync: Pull these repositories locally or sync them to your local Raspberry Pi kiosk node.

    Review the BOM: Open the bill-of-materials folder to source parts via standard local plumbing fixtures or upcycled scrap streams.

    Build at the Lab: If you are in Newport, visit the SOSCL shop floor during our public build brigades to assemble your first stack alongside our community engineers.

“Clarity of logic. Quality of data. Willingness to contribute.”
