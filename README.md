# cuda-neurotransmitter

**Chemical signals that modulate agent cognition -- dopamine IS confidence.**

> These aren't metaphors. They're the same mathematical structures.

## The Mapping

| Neurotransmitter | Agent Concept | Half-life |
|-----------------|--------------|-----------|
| **Dopamine** | Confidence (reward signal) | 20 ticks |
| **Serotonin** | Trust (sustained social bond) | 50 ticks |
| **Norepinephrine** | Alertness (immediate threat) | 10 ticks |
| **Endorphin** | Relief (tension release) | 30 ticks |
| **Melatonin** | Calm (reduction of arousal) | 40 ticks |
| **Acetylcholine** | Focus (attention sharpening) | 15 ticks |
| **GABA** | Inhibition (deliberation suppression) | 25 ticks |
| **Glutamate** | Activation (deliberation amplification) | 12 ticks |

## Key Mechanics

### Receptor Down-Regulation
After 5+ activations, receptor sensitivity decreases with a floor at 20%. This prevents overstimulation. An agent that constantly receives dopamine (high confidence signals) becomes less sensitive to them, requiring stronger signals for the same effect.

### Hebbian Synapses
"Neurons that fire together wire together." Pre-synaptic + post-synaptic firing strengthens the connection (LTP). Pre-synaptic only firing weakens it (LTD). This is the fleet's simplest form of credit assignment.

### Cascades
Reward -> dopamine -> endorphin -> serotonin (positive feedback). Stress -> norepinephrine -> melatonin (calming feedback). Cascades chain multiple neurotransmitter responses into complex behavioral modulations.

## Ecosystem Integration

- [cuda-genepool](https://github.com/Lucineer/cuda-genepool) -- Instincts modulated by neurotransmitter levels
- [cuda-biology](https://github.com/Lucineer/cuda-biology) -- BiologicalAgent uses neurotransmitters
- [cuda-emotion](https://github.com/Lucineer/cuda-emotion) -- Emotional states built on neurotransmitter foundation
- [cuda-confidence](https://github.com/Lucineer/cuda-confidence) -- Mathematical confidence = dopamine signal
- [cuda-trust](https://github.com/Lucineer/cuda-trust) -- Mathematical trust = serotonin signal

## The Insight

Dopamine IS confidence. Not a metaphor -- the same mathematical structure (exponential decay, accumulation, threshold gating). Serotonin IS trust. Norepinephrine IS alertness. By mapping neurotransmitters to agent cognitive primitives, we get the full power of neurochemistry as engineering parameters.

## License

MIT OR Apache-2.0