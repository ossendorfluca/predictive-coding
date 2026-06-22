## Bidirectional Models and Predictive Coding

The brain is constantly betting on what comes next, so the "leakage" we engineer out of temporal models might be the feature we should be studying, not the bug we should be fixing.

If perception is fundamentally predictive, bidirectional architectures with explicit error signals may match the brain better than causal ones — especially in regions that track surprise.

In many temporal deep learning models, "future leakage" (where the model uses information from t+1 to predict t) is considered a flaw (Eren et al., 2025). However, the brain is fundamentally a predictive organ that constantly generates "top-down" anticipations of incoming "bottom-up" sensory data. This framework, known as **Predictive Coding**, suggests that neural activity reflects the difference between what we expect and what we actually perceive (Oliviers et al., 2025; Salvatori et al., 2023). This direction explores **bidirectional architectures** to model these feedback loops, treating "future leakage" not as a bug, but as a potential proxy for the brain's anticipatory mechanisms.

Synthetic: Train a PredNet on simulated video sequences, demonstrate the prediction-error mechanism, show how it differs from a feedforward baseline. The whole point can be made on toy data.
