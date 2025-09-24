# ⚡ Real-Time Data Pipeline

This repository showcases my work on building a **real-time data pipeline** using modern big data frameworks. The project demonstrates how data flows from ingestion to visualization in a distributed environment.

---

## 🚀 Tech Stack

- **Programming Language:** Python  
- **Data Transportation:** Apache Kafka  
- **Coordination Service:** Zookeeper  
- **Distributed Computation:** Apache Spark  
- **Data Storage:** Apache Cassandra  
- **Visualization:** Node.js  

---

## 📊 Workflow

1. **Data Ingestion**  
   - Collected streaming data from a live source.  
   - Transformed the raw data and published it into **Kafka topics**.

2. **Stream Processing**  
   - Consumed Kafka messages using **Apache Spark**.  
   - Performed **distributed computations** such as calculating averages and aggregations over time.  
   - Published processed data back to **Kafka** for downstream consumption.

3. **Data Storage**  
   - Stored processed data in **Apache Cassandra** for scalable and fault-tolerant persistence.

4. **Visualization**  
   - Used **Node.js** to fetch the data and create real-time dashboards for insights.

---

## 🔑 Key Highlights

- Built a **real-time pipeline** from scratch using open-source big data tools.  
- Implemented **streaming analytics** with Spark.  
- Designed a **scalable data store** with Cassandra.  
- Delivered **real-time visualization** with Node.js.  

---

## 📌 Future Enhancements

- Integrate **Grafana/Plotly** for advanced dashboards.  
- Extend to handle **multiple heterogeneous data streams**.  
- Deploy pipeline on **Kubernetes** for scalability.  

---

## ⚡ Getting Started

1. Start **Zookeeper** and **Kafka**.
2. Run the **producer** to fetch and publish data.
3. Launch the **Spark job** to process and aggregate streams.
4. Start the **consumer** to persist results into Cassandra.
5. Run the **Node.js app** to visualize real-time data.

---

## 📜 License

This project is open-source and available under the [MIT License](LICENSE).
