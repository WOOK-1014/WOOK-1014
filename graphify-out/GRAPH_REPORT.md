# Graph Report - WOOK-1014  (2026-11-19)

## Corpus Check
- Corpus is ~356 words - fits in a single context window. You may not need a graph.

## Summary
- 20 nodes · 21 edges · 4 communities (3 shown, 1 thin omitted)
- Extraction: 86% EXTRACTED · 14% INFERRED · 0% AMBIGUOUS · INFERRED: 3 edges (avg confidence: 0.88)
- Token cost: 83,906 input · 0 output

## Community Hubs (Navigation)
- Security Learner Profile
- Graph Outputs & Maintenance
- Graph Lookup Commands
- Graphify Skill Registration

## God Nodes (most connected - your core abstractions)
1. `graphify usage rules` - 6 edges
2. `Security learner profile` - 6 edges
3. `Query graph before grep/source read` - 5 edges
4. `graphify-out knowledge graph (graph.json)` - 3 edges
5. `SK Shieldus Rookies (35th) Cloud Security Program` - 3 edges
6. `graphify skill (/graphify trigger)` - 2 edges
7. `graphify update (AST-only refresh)` - 2 edges
8. `sk-shieldus-rookies repository` - 2 edges
9. `Focus: web/infra vuln assessment, cloud security, network security` - 2 edges
10. `.claude/skills/graphify/SKILL.md` - 1 edges

## Surprising Connections (you probably didn't know these)
- `graphify skill (/graphify trigger)` --conceptually_related_to--> `graphify usage rules`  [INFERRED]
  .claude/CLAUDE.md → CLAUDE.md

## Hyperedges (group relationships)
- **graphify scoped lookup commands** — claude_graphify_query, claude_graphify_path, claude_graphify_explain, claude_graphify_section [EXTRACTED 1.00]

## Communities (4 total, 1 thin omitted)

### Community 0 - "Security Learner Profile"
Cohesion: 0.38
Nodes (7): Certifications (Network Administrator L2; planned Engineer Information Processing, SQLD, AWS SAA), B.S. in Computer Engineering, Focus: web/infra vuln assessment, cloud security, network security, Security learner profile, Toolset (Python, Kali Linux, Burp Suite, nmap, AWS, Linux, Cisco IOS), SK Shieldus Rookies (35th) Cloud Security Program, sk-shieldus-rookies repository

### Community 1 - "Graph Outputs & Maintenance"
Cohesion: 0.40
Nodes (5): GRAPH_REPORT.md, graphify-out knowledge graph (graph.json), graphify usage rules, graphify update (AST-only refresh), graphify-out/wiki/index.md

### Community 2 - "Graph Lookup Commands"
Cohesion: 0.40
Nodes (4): graphify explain, graphify path, graphify query, graphify section

## Knowledge Gaps
- **10 isolated node(s):** `.claude/skills/graphify/SKILL.md`, `graphify query`, `graphify path`, `graphify explain`, `graphify section` (+5 more)
  These have ≤1 connection - possible missing edges or undocumented components. (Counts symbols only; 11 node(s) total have ≤1 connection when file, concept and rationale nodes are included.)
- **1 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `graphify usage rules` connect `Graph Outputs & Maintenance` to `Graph Lookup Commands`, `Graphify Skill Registration`?**
  _High betweenness centrality (0.304) - this node is a cross-community bridge._
- **What connects `.claude/skills/graphify/SKILL.md`, `graphify query`, `graphify path` to the rest of the system?**
  _10 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Why does `Query graph before grep/source read` connect `Graph Lookup Commands` to `Graph Outputs & Maintenance`?**
  _High betweenness centrality (0.222) - this node is a cross-community bridge._