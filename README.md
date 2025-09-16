# Facebook Social Network Analysis with Apache Spark

An advanced social network analysis project using Apache Spark GraphFrames to analyze Facebook friendship data and uncover network patterns, influence dynamics, and community structures.

## 🎯 Project Overview

This project demonstrates **enterprise-level big data processing** by analyzing real Facebook social network data using Apache Spark. It showcases skills in distributed computing, graph algorithms, and social network analysis.

### Key Features:
- ✅ **Distributed Graph Processing** with Apache Spark
- ✅ **Real Research Dataset** (Stanford SNAP Facebook data)
- ✅ **Multiple Graph Algorithms** (PageRank, Community Detection, Centrality)
- ✅ **Scalable Architecture** (works with millions of connections)

## 📊 Dataset

**Facebook Social Circles Dataset** from Stanford SNAP
- **4,039 users** (anonymized)
- **88,234 friendships**
- **Real social network data** from Facebook
- **Research-quality dataset** used in academic papers

## 🛠️ Technology Stack

### Core Technologies:
- **Apache Spark 3.5.0** - Distributed computing framework
- **GraphFrames 0.8.2** - Graph processing library for Spark
- **Python 3.8+** - Programming language
- **PySpark** - Python API for Spark

### Analysis Libraries:
- **Pandas** - Data manipulation
- **Matplotlib/Seaborn** - Data visualization
- **Jupyter** - Interactive analysis notebooks

### Development Tools:
- **Maven** - Dependency management
- **Git** - Version control
- **Docker** (optional) - Containerization

## 📈 Analysis Capabilities

### Network Statistics
- User and friendship counts
- Degree distributions
- Network density calculations
- Basic graph metrics

### Influence Analysis
- **PageRank Algorithm** - Identify most influential users
- **Centrality Measures** - Degree and betweenness centrality
- **Influence Scoring** - User impact analysis

### Community Detection
- **Label Propagation Algorithm** - Find user communities
- **Community Size Analysis** - Group distribution statistics
- **Network Clustering** - Identify social circles

## 📁 Project Structure

## 🎯 Usage Examples


## 📊 Sample Output

```
🚀 Starting Facebook Social Network Analysis
==================================================

🔄 Loading Facebook friendship data...
📊 Loaded 4,039 users and 88,234 friendships

📈 Calculating basic network statistics...
   👥 Users: 4,039
   🤝 Friendships: 88,234
   📊 Average degree: 43.69
   📊 Max degree: 1,045
   📊 Min degree: 1

🎯 Calculating PageRank (influence scores)...
   🏆 Top 5 influencers:
      User 1912: 0.0012
      User 2266: 0.0011
      User 2206: 0.0010
      User 2006: 0.0009
      User 2142: 0.0009

🏘️ Detecting communities...
   🏘️ Found 12 communities
   📊 Top 5 communities by size:
      Community 1: 1,342 members
      Community 2: 1,098 members
      Community 3: 987 members
```

### Scalability Features:
- ✅ **Distributed Processing** across multiple nodes
- ✅ **Memory Optimization** with adaptive query execution
- ✅ **Fault Tolerance** with Spark's resilience
- ✅ **Horizontal Scaling** by adding more workers
