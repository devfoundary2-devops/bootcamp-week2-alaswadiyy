### **Verify my deployment**

---

- `kubectl get pods -n shopmicro`

- `kubectl get svc -n shopmicro`

- `kubectl get deploy -n shopmicro`

![All pod running](./images/kebectl-three.png)

### **Open Grafana:**

- Grafana: <http://localhost:3000>
 (login: admin / admin)

**Grafana dashboard**

![grafana dashboard](./images/grafana-dash.png)

**Metrics on grafana**

![metrics on grafana](./images/Grafana-metrics.png)

**logs on grafana**

![logs on grafana](./images/Grafana-logs.png)

### **Open Prometheus UI:**

 `http://localhost:9090`

**Prometheus**

(./images/prometheus.png)

### **Test Service Connectivity:**

- **Test backend health:**

  `curl http://localhost:3001/health`

  ![backend health](./images/3001-healthy.png)

- **Test frontend health:**

`curl http://localhost:8080`

![frontend health](./images/8080-healthy.png)
