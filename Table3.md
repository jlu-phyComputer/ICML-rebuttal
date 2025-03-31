Table 3: MSE changes after adding EGNI/ESNI (Δ%) corresponding to Figures 1(c) and 1(d). The look-back and prediction lengths are set to 96. 

| Model                  | ETTH2  | ECL    | Traffic | Weather | Solar-Energy | PEMS03  |
| ---------------------- | ------ | ------ | ------- | ------- | ------------ | ------- |
| Transformer            | 0.567  | 0.274  | 0.672   | 0.402   | 0.314        | 0.298   |
| Transformer with EGNI  | 0.589  | 0.251  | 0.695   | 0.391   | 0.334        | 0.282   |
| → Δ% with EGNI         | +3.88% | -8.39% | +3.42%  | -2.74%  | +6.37%       | -5.37%  |
| Transformer with ESNI  | 0.599  | 0.289  | 0.650   | 0.422   | 0.301        | 0.286   |
| → Δ% with ESNI         | +5.64% | +5.47% | -3.27%  | +4.98%  | -4.14%       | -4.03%  |
| iTransformer           | 0.321  | 0.151  | 0.422   | 0.173   | 0.213        | 0.069   |
| iTransformer with EGNI | 0.310  | 0.142  | 0.435   | 0.165   | 0.202        | 0.075   |
| → Δ% with EGNI         | -3.43% | -5.96% | +3.08%  | -4.62%  | -5.16%       | +8.70%  |
| iTransformer with ESNI | 0.296  | 0.158  | 0.410   | 0.167   | 0.200        | 0.075   |
| → Δ% with ESNI         | -7.79% | +4.64% | -2.84%  | -3.47%  | -6.10%       | +8.70%  |
| PatchTST               | 0.313  | 0.201  | 0.567   | 0.187   | 0.239        | 0.107   |
| PatchTST with EGNI     | 0.301  | 0.215  | 0.554   | 0.175   | 0.231        | 0.095   |
| → Δ% with EGNI         | -3.83% | +6.97% | -2.29%  | -6.42%  | -3.35%       | -11.21% |
| PatchTST with ESNI     | 0.304  | 0.213  | 0.589   | 0.176   | 0.234        | 0.120   |
| → Δ% with ESNI         | -2.88% | +5.97% | +3.88%  | -5.88%  | -2.09%       | +12.15% |