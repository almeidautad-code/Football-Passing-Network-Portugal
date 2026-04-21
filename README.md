# 🇵🇹 Portugal National Team — Passing Network Analysis

## 📌 Overview
This project visualizes the **passing network** of the Portugal national team using **Cytoscape**, a powerful network analysis tool. Each player is represented as a node, and the connections between them represent passes, with the thickness and color of the edges indicating the frequency and direction of passes between players.

> 📄 [**View Full Analysis Report (PDF)**](https://github.com/almeidautad-code/Football-Passing-Network-Portugal/blob/624bafae607b51e400f25927b151e5ca2c13c245/Network%20github.pdf)

<img width="3235" height="3090" alt="Network Portugal" src="https://github.com/user-attachments/assets/adaf8c1d-9c41-4fd6-a200-1a3da6722b55" />

---

## 🔍 Key Features
- 🔵 Player nodes sized by **passing involvement**
- 🟢 Edge thickness represents **passing frequency**
- 📍 Players positioned according to their **pitch position**
- 🇵🇹 Covers **Portugal vs Chéquia (2024)** passing patterns
- 🔄 Interactive network — zoom, filter and explore connections

---

## 🧠 Key Findings

**1. Efficient Build-Up and Left-Side Construction**
- The team uses a short, supported build-up with frequent passes between nearby players
- Construction heavily concentrated on the **left side**, with **Nuno Mendes** having the highest number of interactions

**2. Vitinha & Bruno Fernandes — Central Playmakers**
- Both players are crucial connectors due to their **high betweenness centrality**
- **Vitinha** links up with full-backs and center-backs in the initial build-up phase
- **Bruno Fernandes** operates in the creative phase, connecting with wingers and forwards

**3. Ronaldo & Leão — Low Involvement**
- Smaller nodes and fewer connections suggest **limited involvement**
- **Leão** stayed wide and was isolated, reflecting a direct, less associative style
- **Bernardo** was more mobile, played inside, and freed **Dalot** to overlap

**4. Playing System — 3-4-3**
- Portugal is structurally organized in a **3-4-3**, characterized by a high level of mobility
- Four players — **Vitinha, Bruno, Cancelo, and Bernardo** — display notable positional fluidity

---

## 📊 SWOT Analysis

| | |
|---|---|
| 💪 **Strengths** | Short and secure circulation; Strong left-side build-up |
| ⚠️ **Weaknesses** | Offensive isolation of Leão and Ronaldo; Right side underused |
| 🚀 **Opportunities** | Improve connections with forwards; Use Bernardo as interior playmaker |
| 🔴 **Threats** | Potential pressure on the left side; Overcrowding in central areas |

---

## 📁 Project Structure
```
📦 Football-Passing-Network-Portugal
├── Network Passe.cys        → Cytoscape network file
├── Network github.pdf       → Full analysis report
└── README.md                → Project documentation
```

---

## 🚀 How to Use
1. Download and install **Cytoscape** from [cytoscape.org](https://cytoscape.org)
2. Download the `Network Passe.cys` file from this repository
3. Open Cytoscape and go to **File → Open**
4. Select the `.cys` file
5. Explore the passing network interactively
6. Read the full analysis in the **PDF report**

---

## 🛠️ Tools & Technologies
- Cytoscape (network visualization)
- Network Analysis (betweenness centrality, node degree)
- Data sourced from **Wyscout** (professional football database)

---

## 📌 Future Improvements
- [ ] Add more matches and competitions
- [ ] Include passing direction analysis
- [ ] Compare passing networks across different games
- [ ] Add opponent team networks for comparison
- [ ] Animate passing sequences

---

## 👤 Author
**João Almeida** — Data Analytics Portfolio
[LinkedIn](https://www.linkedin.com/in/joaoalmeida96/) • [GitHub](https://github.com/almeidautad-code)
