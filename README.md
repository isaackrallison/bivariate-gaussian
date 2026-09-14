# Reading the Bivariate Gaussian

An interactive visualization of the multivariate normal distribution, built alongside
§3.2 of Kevin P. Murphy, *Probabilistic Machine Learning: An Introduction*.

**Live:** https://isaackrallison.github.io/bivariate-gaussian/

- Reshape Σ with μ₁, μ₂, σ₁, σ₂, ρ and watch the Mahalanobis contours, eigenvectors,
  and sample cloud respond.
- Drag the plot to slice the joint at Y₂ = y₂ and compare the conditional p(y₁|y₂)
  against the marginal p(y₁).
- Presets for the full / diagonal / spherical covariance shapes of Figure 3.6.
- A seven-question quiz that can set the plot to the scenario each question describes.

Single self-contained `index.html` — no build step, no dependencies beyond Google Fonts.
