# ODEN – Open Dynamic External‑memory Network ( ODIA-ENGLISH LLM )
A self adapting Transformer architecture with hierarchical external memory, adaptive multi‑modal attention, Mixture‑of‑Experts feed‑forward, and FP8 quantisation.

ODEN is an advanced language model architecture with cognitive capabilities including hierarchical memory, adaptive multi-modal attention, and expert-based processing.

## Features

- **Hierarchical External Memory**: Multi-level memory system with consolidation between levels
- **Adaptive Multi-Modal Attention**: Specialized attention patterns with learned routing
- **Mixture of Experts**: Dynamic routing of tokens to specialized feed-forward networks
- **Self-Correction Mechanism**: Refinement of attention outputs
- **Advanced Positional Encoding**: Dual-frequency rotary position embeddings
- **Model Parallelism**: Efficient distributed training across multiple GPUs
- **Quantization Support**: FP8/INT8 precision for inference optimization

- **Dynamic Memory Management**: Adaptive memory allocation and deallocation


Model Sizes
Size    Parameters  Hidden Size     Attention Heads   Layers  Memory Slots    
Small   1.3B        1024            8                 16      512
Base    7B          2048            16                32      1024
Large   30B         4096            32                48      2048 
