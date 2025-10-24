# 🧩 Rapid Mold with Digital Fabrication

![Rapid Mold Example](./images/fin_ray_use_case.jpg)

This project demonstrates a rapid prototyping workflow for creating silicone molds using **digital fabrication** and **SLA 3D printing**. The process allows for fast and precise mold creation suitable for small-scale or experimental manufacturing.

---

## 🧱 3D Modeling Workflow

1. **Create or import** the target 3D model.  
2. **Create a solid block** that completely encloses the target model.  
3. **Use the `COMBINE` tool** with the **Cut** operation to subtract the target model from the block, forming a **negative mold**.  
4. **3D print** the resulting negative mold.
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
