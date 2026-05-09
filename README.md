/**
 * SURCHI Presale Configuration
 * Native Ecosystem: Solana
 */

export const SURCHI_TOKEN_METADATA = {
  name: "SURCHI",
  symbol: "SURCHI",
  blockchain: "Solana",
  totalSupply: 19_897_905,
};

export const TOKEN_ALLOCATION = {
  presale: {
    percentage: 0.64,
    tokens: 12_734_659.2,
  },
  liquidityPool: {
    percentage: 0.30,
    tokens: 5_969_371.5,
  },
  reserve: {
    percentage: 0.06,
    tokens: 1_193_874.3,
  },
};

export const PRESALE_STRUCTURE = {
  softCap: 100, // SOL
  hardCap: 600, // SOL
  liquidityRate: 0.70, // 70%
  listingType: "Auto Listing",
  durationDays: 30,
  liquidityLockDays: 365,
  minBuy: 0.05, // SOL
  maxBuy: 10,   // SOL
  unsoldTokens: "Reserved for External Liquidity Addition",
};

export const PRICING_CONSTANTS = {
  ratePerSol: 21_224.43,
  examples: [
    { sol: 0.05, surchi: 1_061.22 },
    { sol: 1.00, surchi: 21_224.43 },
    { sol: 10.0, surchi: 212_244.32 },
  ],
};

export const LAUNCH_HIGHLIGHTS = [
  "Strong liquidity-focused tokenomics",
  "Community-driven distribution structure",
  "Long-term liquidity protection",
  "Scalable AI-powered Web3 ecosystem",
  "Built on the high-speed Solana network",
];
