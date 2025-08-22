```mermaid
graph TD
    subgraph "Core Driver"
        A[<b>Resource Rents</b><br/><i>(Windfall Income)</i>]
    end

    subgraph "Inflationary Channels"
        B1(<b>Exchange Rate Channel</b><br/>FX Inflows → Real Appreciation → Non-Tradable Price Increases)
        B2(<b>Fiscal Channel</b><br/>Volatility → Procyclical Spending & Deficits)
        B3(<b>Monetary/Liquidity Channel</b><br/>FX Inflows → Unsterilized Liquidity → Credit Booms)
        B4(<b>Institutional Channel</b><br/>Weak Institutions → Rent Seeking & Misallocation)
    end

    subgraph "Moderating Factor: Financial Development"
        C1[<b>Low Financial Development</b><br/><i>(Amplifies Shocks)</i>]
        C2[<b>High Financial Development</b><br/><i>(Absorbs Shocks)</i>]
    end

    subgraph "Mechanisms & Effects"
        D1("High Exchange Rate Pass-Through")
        D2("Monetary Financing (Seigniorage)")
        D3("Unsterilized Liquidity Injections & Asset Bubbles")
        D4("Fiscal Dominance & Lack of Credibility")

        E1("Hedging Instruments & Anchored Expectations<br/><i>Reduces Pass-Through</i>")
        E2("Deep Bond Markets & Countercyclical Policy<br/><i>Enables Non-Inflationary Financing</i>")
        E3("Sterilization Tools (SWFs, OMOs) & Prudential Oversight<br/><i>Absorbs Liquidity & Tempers Booms</i>")
        E4("Credible Policy Frameworks (e.g., Inflation Targeting)<br/><i>Buffers Shocks</i>")
    end

    subgraph "Final Outcome"
        F_High[<b>High & Volatile Inflation</b>]
        F_Low[<b>Low & Stable Inflation</b>]
    end

    A --> B1
    A --> B2
    A --> B3
    A --> B4

    B1 --> C1
    B2 --> C1
    B3 --> C1
    B4 --> C1

    B1 --> C2
    B2 --> C2
    B3 --> C2
    B4 --> C2
    
    C1 --> D1
    C1 --> D2
    C1 --> D3
    C1 --> D4

    C2 --> E1
    C2 --> E2
    C2 --> E3
    C2 --> E4

    D1 --> F_High
    D2 --> F_High
    D3 --> F_High
    D4 --> F_High

    E1 --> F_Low
    E2 --> F_Low
    E3 --> F_Low
    E4 --> F_Low

    style F_High fill:#ffcccc,stroke:#333,stroke-width:2px
    style F_Low fill:#ccffcc,stroke:#333,stroke-width:2px
    style C1 fill:#f9f9f9,stroke:#666
    style C2 fill:#f9f9f9,stroke:#666
```
