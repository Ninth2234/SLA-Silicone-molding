# 🧩 Rapid Silicone Mold with Digital Fabrication

![Rapid Silicone Mold Example](./images/fin_ray_use_case.jpg)

This project showcases a rapid digital fabrication workflow for producing silicone molds using SLA 3D printing and computer-aided design. The workflow demonstrates how high-resolution photopolymer printing can be combined with silicone casting to enable fast, accurate, and repeatable mold production without the need for traditional tooling. By starting from a CAD model and applying streamlined design principles—such as parting-line planning, draft angle integration, and cavity generation—the process allows users to transition from digital design to physical mold within hours. The use of Anycubic ABS-Like Pro 2 resin provides strong, dimensionally stable masters that capture fine geometric details while maintaining compatibility with standard RTV silicones. This method is ideal for small-scale manufacturing, product prototyping, and research applications where rapid iteration, material testing, or educational demonstration is required. The repository includes practical design guidelines, safety precautions, and recommended print and curing parameters, forming a reproducible framework for engineers, makers, and educators exploring the intersection of additive manufacturing and mold-based fabrication.

---

## 🧱 3D Modeling Workflow

1. **Create or import** the desired 3D model into your CAD workspace**.  
2. **Generate a solid block that fully encloses the model, ensuring sufficient wall thickness around all sides**.  
3. **Apply the Combine tool with the Cut operation to subtract the model from the block, creating a negative mold cavity**.
4. Export and 3D print the resulting negative mold using your SLA printer**.
🎥 **Reference Video:** [Rapid Mold 3D Modeling Workflow](https://youtu.be/Q1Thdrt40MA?si=13iyadsBUq4JawJu)
---

### Materials Used

- **Mold Material:** [Anycubic ABS-Like Resin Pro 2 (Clear)](https://store.anycubic.com/products/abs-like-resin-pro-2?variant=43847439351970)  
  A high-strength, clear SLA resin with ABS-like mechanical properties. Suitable for durable mold creation, but can cause silicone inhibition if not properly post-processed.

- **Casting Silicone:** [RungArt Silicone 40AB (Platinum-Cure)](https://www.resinrungart.com/shop/1402225205854-yaangchiliokhn-ra-40ab-chud-1-kk-110012)  
  A room-temperature, **platinum-cured** silicone rubber with 40A shore hardness, ideal for flexible and detailed parts.

---

## 🧪 Material & Compatibility Notes

### SLA Printing

SLA (Stereolithography) printing offers **high resolution** and **smooth surface quality**, ideal for rapid silicone molding prototypes with **fine details**.  

However, SLA resin contains chemicals that can **inhibit platinum-cured silicone**, causing **partial or incomplete curing**. Inhibited silicone remains **sticky or soft** on the surface.

### Silicone Used

The silicone used in this process is a **room-temperature curing** type with a **platinum-cure mechanism** (Silicone AB).

---

## 🔧 Post-Processing Procedure

![Mold example](./images/testing_results.jpg)

To minimize silicone inhibition and prepare the mold for casting:

1. **Wash** the printed mold twice in **99% Isopropyl Alcohol (IPA)**.  
2. **Immerse** the mold in **99% IPA** for **30 minutes**.  
3. **Air dry** the mold completely.  
4. **Expose** the mold under **UV light for 1 hour**.  
5. **Bake** the mold at **60 °C for 2 hours**.  
6. **Leave** the mold in open air for **3 days** before casting.

---

## ⚠️ Troubleshooting Inhibition

If silicone curing is **partially inhibited** (sticky or tacky surface):

- Clean the mold again following the same post-process steps.  
- Allow both the **mold** and **part** to remain in **open air** for additional time.  
- It has also been observed that **waiting several days before casting** — rather than pouring silicone immediately after printing — **significantly reduces inhibition**.


## 📚 Reference

Venzac, B., Deng, S., Mahmoud, Z., Lenferink, A., Costa, A., Bray, F., Otto, C., Rolando, C., & Le Gac, S. (2021).  
*PDMS Curing Inhibition on 3D-Printed Molds: Why? Also, How to Avoid It?*  
**Analytical Chemistry, 93**(19), 7180–7187.  
https://doi.org/10.1021/acs.analchem.0c04944
