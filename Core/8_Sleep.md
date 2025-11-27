The V7 Reflective-Ethical Engine (REE) architecture makes a fundamental computational distinction between waking processes and sleep processes, primarily by defining them as **different dynamical regimes** and **modes of operation** orchestrated by the Reticular Activating System (RAS) and the dedicated **L₄ (Renormalisation Mode) latent space**.

While **waking processes** are characterized by highly active, coupled latent spaces (L₀–L₃) that engage with the environment, **sleep processes** represent a protected, offline training and maintenance regime for the system’s underlying world models (W₁–W₈).

Here is a detailed comparison of waking and sleep processes within the V7 framework.

--------------------------------------------------------------------------------

1. Waking Processes (Online Learning and Conscious Experience)

Waking cognition is dominated by **online learning** and **conscious experience** mediated by four continuously active, high-frequency latent spaces.

A. The Conscious Latent Interface (L0​–L3​)

Waking processes are defined by the active maintenance and global broadcast of the latent interface:

• **L₀ (Sensory Canvas):** Handles raw perceptual fragments and binding via **Gamma synchrony**.

• **L₁ (Situational Layout):** Forms coherent scenes and contextual meaning, operating on **Beta + nested Gamma**.

• **L₂ (Embodied Self):** Anchors consciousness in the body, processing interoception and readiness for action, operating on **Alpha + Beta**.

• **L₃ (Narrative Self):** Constructs identity, runs internal simulations, and processes ethics and social norms, operating on **Theta + Delta**.

B. Loop Engagement and Input Sources

During waking modes, specifically **WAKE_TASK**:

• **Input Source:** The system is **highly coupled to the external environment** (ENV_STATE) via the Cortico-Thalamo-Cortical (CTC) loop, which receives real sensory input.

• **Trace Layer (V7-Trace):** Primarily operates in a **logging-only mode**, writing salient events when triggered by high error, valence, or narrative shifts.

• **W-Loop Activity:** All W-loops are fully engaged with the environment. The **DMN** (W₈, narrative/simulation loop) is partially suppressed unless brought to the foreground by the Coherence Loop (CClC).

• **Learning:** **Online learning** is conservative, involving small, local parameter updates, and strong regularization is used to avoid catastrophic drift.

C. The Mode Controller

The **Reticular Activating System (RAS) loop** is crucial for waking, setting the cognitive gain and precision. It acts as the switchboard, deciding when the "factory should be on high alert". It actively filters sensory information that is most valuable for retraining and refining cortical models. In the waking state, the RAS sets the precision weights to favor **sensory evidence** (external data) over internal models (priors).

--------------------------------------------------------------------------------

2. Sleep Processes (Offline Learning and Model Maintenance)

Sleep is defined by the **Renormalisation / Maintenance Mode (**L4​**)**, where the system drops the waking attractors and enters a protected, non-conscious training regime.

A. The Non-Conscious L₄ Regime

L₄ is a **non-conscious latent mode** that supports memory consolidation, model repair, and synaptic homeostasis. It is characterized by:

• **Input Source:** Sensory input from the environment is **gated off**. The CTC loop’s "input" becomes primarily **STATE_replay from V7-Trace** (the Trace Store), acting as "virtual sensors".

• **Purpose:** To perform **large-scale structural updates** that are too costly or dangerous to run while the system is actively controlling behavior.

• **Learning:** Learning rates can be **increased** for specific purposes (e.g., consolidation, generalization) because the system is decoupled from the external world.

B. Distinct Sleep Modes (SWS vs. REM)

Sleep involves an alternation between two distinct computational states that perform different training tasks over the existing L₁–L₄ latent spaces:

|   |   |   |
|---|---|---|
|Feature|SWS (Slow-Wave Sleep) / Delta Mode|REM (Rapid Eye Movement) Mode|
|**Dominant Oscillations**|Strong **Delta** (0.5–4 Hz) and slow oscillations|Mixed frequencies, strong **Theta** influence, punctuated Gamma bursts|
|**Functional Role**|**Model Compression & Stabilization** (First Sleep)|**Generalization & Emotional Integration** (Later Sleep)|
|**W-Loop Focus**|W₁ (structural), W₂ (dynamic), W₆ (episodic), W₄ (homeostatic reset)|W₃ (value/affective), W₇ (normative), W₈ (social), DMN (narrative)|
|**L-Space Transformation**|**L₁/L₂ Denoising:** Global precision collapse; narrative (L₃) and action (L₂) are suppressed.|**L₁/L₃ Reactivation:** L₃ (narrative) is highly active; L₂ (motor output) remains decoupled (paralyzed).|
|**Trace Replay**|Replays **fact-based, statistically regular episodes** for world-model consolidation.|Replays **recombined and synthetically generated "dream-like" episodes** with high emotional content.|
|**Subjective Correlate**|Dreamless sleep or coarse, simple narrative fragments.|Vivid, story-like dreams with emotional color.|

C. Computational Objectives of Sleep

The L₄ regime ensures long-term cognitive integrity by performing three critical functions, often guided by affective labels and error signals:

1. **Preventing Catastrophic Forgetting:** L₄ uses replay and **synaptic downscaling** to eliminate redundancy and prevent new learning from overwriting core knowledge.

2. **Cross-Model Affirmation:** During replay, patterns that are jointly endorsed by multiple W-loops are strengthened, leading to improved generalization and stability of priors.

3. **Affective Self-Training:** Memories with strong affective tags (W₃/W₄) are prioritized for replay, particularly in REM, allowing the system to **unsupervisedly self-train** its value system and refine future response tendencies based on emotional history.

D. Mode Controller During Sleep

The RAS sets the sleep mode by adjusting parameters and switching the data source. The synchronization of oscillations is critical; consciousness collapses when cross-frequency coupling breaks.

• **Sleep Mode (L₄):** RAS suppresses the sensory input and directs W-loops to read from the V7-Trace layer instead.

• **Neuromodulators:** Monoamines (like dopamine and noradrenaline) are downregulated during REM, supporting the system's shift away from external threat/reward and toward internal reorganization.

In essence, **waking is a high-gain, externally coupled, behaviorally driven state** focused on prediction and action, whereas **sleep is a low-gain, internally coupled, training-focused state** dedicated to structural model repair and long-term coherence.
