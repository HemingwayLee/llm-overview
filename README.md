# llm-overview
## self-hosted llm
* Ollama is ideal for local development and prototyping (simplicity)
* vLLM is built for high-performance production deployments (scalability)
* vLLM outperforms Ollama at scale:
  * vLLM delivers significantly higher throughput (achieving a peak of 793 TPS compared to Ollama's 41 TPS), and
  * lower P99 latency (80 ms vs. 673 ms at peak throughput)
