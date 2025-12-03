# GoLang Concurrency Mastery

**15 Real-World Problems & Patterns**

Learn Go concurrency through practical, production-level examples. This repository contains all the code from the Udemy course "GoLang Concurrency Mastery."

## 🎯 What You'll Learn

- Goroutines & Channels
- Mutex & RWMutex
- Worker Pools & Job Queues
- Graceful Shutdowns & Context Cancellation
- Deadlock Detection & Prevention
- Distributed Rate Limiting with Redis
- Priority-Based Task Scheduling

## 📚 Course Structure

### Phase 1: Core Patterns (Basics)
1. **Alternate Printing** - Using channels for synchronization
2. **Worker Pool** - Concurrent task processing
3. **Safe Counter** - Protecting shared state with Mutex
4. **Context Cancellation** - Timeout and cancellation patterns
5. **Rate Limiter** - Token bucket implementation

### Phase 2: Real-World Engineering Scenarios
6. **Concurrent File Downloader** - Parallel downloads with coordination
7. **Graceful HTTP Server Shutdown** - Clean service termination
8. **Producer-Consumer System** - Classic concurrency pattern
9. **Bounded Buffer** - Backpressure handling
10. **Retry with Exponential Backoff** - Resilient service calls

### Phase 3: Advanced & System-Level Patterns
11. **Concurrent Map with RWMutex** - Thread-safe data structures
12. **Job Queue** - Multiple producers and consumers
13. **Deadlock Detection & Prevention** - Safe concurrent design
14. **Distributed Rate Limiter** - Redis-based rate limiting
15. **Priority-Based Task Scheduler** - Heap + goroutine scheduling

## 🚀 Getting Started

### Prerequisites
- Go 1.21 or higher
- Basic Go knowledge (functions, structs, interfaces)
- Git installed

### Installation
```bash
# Clone the repository
git clone https://github.com/YOUR_USERNAME/golang-concurrency-mastery.git

# Navigate to the project
cd golang-concurrency-mastery

# Initialize Go module (if needed)
go mod init github.com/YOUR_USERNAME/golang-concurrency-mastery
```

## 📖 How to Use This Repository

Each problem is in its own folder with:
- `README.md` - Problem description and requirements
- `main.go` - Starter template (try solving it yourself first!)
- `solution/main.go` - Complete working solution

### Recommended Approach:
1. Read the problem README
2. Try implementing it yourself using the starter template
3. Compare with the solution
4. Run and experiment with the code

## 🎓 Course Link

**Enroll in the full course:** [Udemy Course Link - Add after publishing]

## 📝 Topics Covered

- Goroutines
- Channels (buffered & unbuffered)
- Select statements
- Mutex & RWMutex
- WaitGroups
- Context package
- Race condition prevention
- Deadlock prevention
- Concurrent patterns
- Production-ready concurrency

## 🤝 Contributing

Found a bug or have a suggestion? Feel free to open an issue or submit a pull request!

## 📧 Contact

Questions about the course? Reach out:
- **Instructor:** Hari
- **Email:** [Your email - optional]
- **Udemy Q&A:** [Link to course Q&A]

## ⭐ Show Your Support

If you find this repository helpful, please give it a star! ⭐

---

**Happy Coding! 🚀**
