![University of Manchester](https://upload.wikimedia.org/wikipedia/en/5/5a/University_of_Manchester_logo.png)

# 👋 Hi, I'm Anthony Nguyen

### Passionate about systems engineering, ML, software development, and system architecture with a general interest in developing robust solutions.

[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:anthony.nguyen@example.com) [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/anthony-nguyen)

---

## 🛠️ Tech Stack

![**C++**](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) ![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white) ![Assembly](https://img.shields.io/badge/Assembly-654FF0?style=for-the-badge&logo=assemblyscript&logoColor=white) ![Qt](https://img.shields.io/badge/Qt-41CD52?style=for-the-badge&logo=qt&logoColor=white)

---

## 🚀 Featured Projects

### [Order Book with GUI](https://github.com/a38062an/OrderBook)
Building advanced order book infrastructure with focus on low-latency execution and market data processing.

```cpp
// Example: High-performance order matching
class OrderMatcher {
public:
    void matchOrder(const Order& order) {
        // Low-latency matching logic
        processOrder(order);
    }
};
```

### [Branch Predictor](https://github.com/a38062an/Branch_Predictor)
Implemented sophisticated branch prediction algorithms to optimize CPU performance in modern architectures.

```cpp
// Example: Branch prediction implementation
class BranchPredictor {
private:
    std::vector<uint8_t> predictionTable;
public:
    bool predict(uint32_t pc) {
        return predictionTable[pc % table_size] > threshold;
    }
};
```

### [Matrix Optimisation](https://github.com/a38062an/Matrix_Optimisation)
Developed highly optimized matrix operations using assembly language and SIMD instructions for maximum performance.

```assembly
; Example: SIMD matrix multiplication
movaps xmm0, [rsi]      ; Load first vector
mulps  xmm0, [rdi]      ; Multiply with second vector
addps  xmm1, xmm0       ; Add to accumulator
```

### [Atomic Resource Broker](https://github.com/a38062an/Atomic_Resource_Broker)
A resource management system designed for efficient allocation and coordination in distributed environments.

```cpp
// Example: Atomic resource allocation
class ResourceBroker {
public:
    std::atomic<Resource*> allocate() {
        return resources.exchange(nullptr);
    }
};
```

---

<div align="center">
💡 Always learning, always building
</div>
