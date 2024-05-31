# trait_rarity_calculator

This Python script calculates and ranks the rarity of traits within a generative NFT collection using metadata in the Metaplex standard JSON format. The script processes a JSON file containing NFT metadata to determine the frequency of each trait across the collection, computes the rarity percentage for each trait, and evaluates the combined rarity for each NFT. It's designed for flexibility, allowing users to adapt the script to different collection sizes and trait configurations.

Key Features:

JSON Data Handling: Efficiently parses and processes NFT metadata provided in JSON format.
Dynamic Trait Analysis: Automatically counts and calculates rarity for multiple trait types within the NFT metadata.
Rarity Ranking System: Combines individual trait rarities to compute a comprehensive rarity score for each NFT.
CSV Output: Exports the calculated rarity rankings to a CSV file for easy analysis and sharing.
Ideal for NFT creators and collectors looking to quantify and compare the uniqueness of items within a collection.
