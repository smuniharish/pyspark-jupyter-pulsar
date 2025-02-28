# Pulsar + PySpark + Jupyter Stack 🚀

Easily run an **Apache Pulsar** cluster with **Jupyter PySpark** using Docker Compose. All images are hosted on Docker Hub, so you can spin up the stack without any local builds.

## 📂 **Services Included:**
- **Jupyter Lab** with PySpark
- **Apache Pulsar** (Broker, Bookie, Zookeeper)
- **Cluster metadata initialization**
- **Health checks & service dependencies**

## 🛠 **Requirements:**
- Docker
- Docker Compose

## 🚀 **Quick Start:**

1. **Create a `docker-compose.yml` file:**

Download the file directly or copy the content from your repository.

```sh
curl -O https://raw.githubusercontent.com/your-username/your-repo/main/docker-compose.yml
```

2. **Run the stack:**

```sh
docker-compose up -d
```

3. **Access the services:**
- 📘 **Jupyter Lab:** [http://localhost:8888](http://localhost:8888)
- 🟢 **Pulsar Broker:** `pulsar://localhost:6650`
- ⚡ **Pulsar Admin API:** [http://localhost:8080](http://localhost:8080)

4. **Stop the services:**

```sh
docker-compose down
```

## 🛠 **Using Your Docker Hub Images:**

Your `docker-compose.yml` should reference your public Docker Hub images, for example:

```yaml
image: your-dockerhub-username/pyspark-jupyter:latest
```

This ensures users can directly pull the latest versions without building locally.

## 🏁 **Troubleshooting:**
- Check container logs:

```sh
docker-compose logs -f
```

- Verify running containers:

```sh
docker ps
```

## 📜 **License:**
MIT License

## 🤝 **Contributing:**
Feel free to submit issues or pull requests!

---

Ready to explore data streaming and big data processing? Spin up your environment in seconds and start building! 🚀

---

Let me know if you want me to tweak this further or add more sections! 🚀

