🧩 Rapid Silicone Mold with Digital Fabrication

This project presents a rapid digital fabrication workflow for creating silicone molds using SLA 3D printing and computer-aided design (CAD). The workflow demonstrates how high-resolution photopolymer printing can be combined with silicone casting to achieve fast, accurate, and repeatable mold production without the need for traditional machining or tooling.

By starting from a digital CAD model and applying essential mold design principles—such as parting-line planning, draft-angle integration, and cavity generation—users can transition from digital design to a functional mold within hours. Using Anycubic ABS-Like Pro 2 resin as the mold master ensures high dimensional stability and fine surface fidelity while maintaining compatibility with standard RTV platinum-cured silicones when properly post-processed.

This approach is ideal for small-scale manufacturing, product prototyping, research experiments, and educational demonstrations, offering a reproducible and cost-effective framework that bridges additive manufacturing and mold-based fabrication.

🧱 3D Modeling Workflow

Create or import the desired 3D model into your CAD workspace.

Generate a solid block that fully encloses the model, leaving adequate wall thickness on all sides.

Use the Combine tool with the Cut operation to subtract the model from the block, forming a negative mold cavity.

Export and 3D print the resulting mold using your SLA printer.

🎥 Reference Video: Rapid Mold 3D Modeling Workflow

🧰 Materials Used

Mold Master Material: Anycubic ABS-Like Resin Pro 2 (Clear)

A clear, high-strength SLA resin with ABS-like mechanical properties. Suitable for durable mold masters but may inhibit silicone curing if not properly post-processed.

Casting Silicone: RungArt Silicone 40AB (Platinum-Cure)

A room-temperature, platinum-cured RTV silicone with Shore A hardness of 40, ideal for flexible molds that capture fine geometric details.

🧪 Material Compatibility Notes
SLA Resin

SLA (stereolithography) printing provides high precision and smooth surface finishes, making it ideal for mold masters. However, uncured resin residues can chemically inhibit platinum-cure silicones, resulting in tacky or incompletely cured surfaces. To prevent inhibition, ensure the printed part is fully cleaned, UV-cured, and heat-treated before casting.

Silicone

The silicone used in this workflow is a room-temperature-vulcanizing (RTV) type that cures via a platinum-catalyzed addition reaction. This curing mechanism is sensitive to contamination from uncured resin, sulfur, amines, or tin compounds, so proper mold preparation is essential.

🔧 Post-Processing Workflow

To ensure full curing and surface compatibility between SLA resin and silicone:

Wash the printed part twice in 99% isopropyl alcohol (IPA) to remove uncured resin.

Soak the part in fresh IPA for 30 minutes to dissolve trapped residues.

Air-dry thoroughly to remove all solvent traces.

UV-cure the part under 405 nm light for 1 hour, rotating for even exposure.

Bake the cured part at 60 °C for 2 hours to complete crosslinking.

Rest the mold in open air for at least 3 days before casting silicone.

⚠️ Caution, Best Practices, and Troubleshooting for SLA–Silicone Molding
1. Incomplete SLA Curing May Inhibit Silicone

Issue: Residual uncured resin can chemically inhibit platinum-cure silicones, resulting in tacky or partially cured surfaces.
Prevention:

Wash prints thoroughly in ≥ 90 % IPA or the manufacturer’s cleaning solution.

Allow full solvent evaporation before UV curing.

Post-cure under 405 nm UV light for at least one hour, rotating for uniform exposure.

If inhibition persists, apply a barrier coat (clear acrylic or thin epoxy) before pouring silicone.

2. Mold Design Guidelines

Draft Angles: 2–3° minimum; 5°+ for deep cavities.

Wall Thickness: Maintain 5–10 mm silicone thickness for structural rigidity.

Alignment Keys: Use 6–12 mm hemispherical or diamond-shaped keys for precise alignment.

Sprues & Vents:

Sprues: Ø 3–6 mm at the lowest point.

Vents: Ø 0.3–1 mm at the highest points.

Fillets: 0.5–1 mm internal radii reduce stress and improve silicone flow.

Surface Finish: Smooth or seal printed masters; matte textures trap bubbles.

3. Controlled Heat Use

Guideline: Gentle heating (30–45 °C) can shorten silicone cure time, but excessive heat can damage the resin or alter curing behavior.
Risks:

Resin deformation (ABS-Like Pro 2 softens above ≈ 60 °C).

Silicone shrinkage or bubble formation due to accelerated exotherm.
Best Practice:

Use a drying oven or enclosure below 45 °C.

Maintain even temperature; avoid direct heat guns or spot heating.

4. Handling and Storage

Store cured molds in a cool, dry, dust-free environment.

Lightly dust silicone molds with talcum powder to prevent surface tack.

Label molds with date, silicone type, and curing parameters for traceability.

Avoid stacking or compressing molds, as silicone may deform over time.

5. Troubleshooting Silicone Inhibition

If silicone curing is incomplete or tacky after demolding:

Rewash and re-cure the SLA mold following the full post-processing protocol.

Allow additional air exposure (24–72 hours) before re-casting.

Extended resting significantly reduces inhibition by allowing residual volatiles to dissipate.

When persistent issues occur, test a small patch of silicone before full casting.

📚 Reference

Venzac, B., Deng, S., Mahmoud, Z., Lenferink, A., Costa, A., Bray, F., Otto, C., Rolando, C., & Le Gac, S. (2021). PDMS Curing Inhibition on 3D-Printed Molds: Why? Also, How to Avoid It? Analytical Chemistry, 93(19), 7180–7187.
https://doi.org/10.1021/acs.analchem.0c04944
