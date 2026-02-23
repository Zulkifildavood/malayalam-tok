# Malayalam-Tok 🐘
Malayalam-Tok is an industry-grade, hybrid morpho-statistical tokenizer specifically engineered for the Malayalam language. By combining a Linguistic Protection Layer with state-of-the-art subword algorithms (BPE & Unigram), it prevents the "pathological fragmentation" of agglutinative word forms while maintaining the efficiency required for modern Large Language Models (LLMs).

🚀 Key Features
Hybrid Engine: Uses a regex-based "Shield" to protect Malayalam suffix chains (e.g., -kal, -il, -ōțu) from unnatural splitting.

Dual Algorithm Support: Out-of-the-box support for both BPE and Unigram models.

LLM Ready: Built as a drop-in replacement for HuggingFace PreTrainedTokenizer.

High Performance: Powered by a Rust-based backend for sub-millisecond inference latency.

Automated Validation: Integrated with mlmorph for silver-standard linguistic accuracy testing.

📦 Installation
🛠️ Quick Start
📊 Performance Benchmarks
Current development version (v0.1.0-alpha)

🧪 Automated Testing
We use Property-Based Testing to ensure morphological integrity. To run the suite:

📜 Thesis Research
This project is part of a Master's Thesis titled "Engineering Malayalam-Tok: A Hybrid Morpho-Statistical Tokenizer for High-Integrity NLP." It builds upon research conducted in RP-3 regarding human-perceived adequacy (MAS) in Dravidian language tokenization.

🤝 Contributing
Contributions are welcome! Please see  for details on our linguistic validation protocols.

📄 License
Distributed under the MIT License. See LICENSE for more information.