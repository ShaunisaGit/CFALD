# **CFALD — CFA-Domain Luminance Drizzle for OSC Astrophotography**

**CFALD is a method for extracting true monochrome luminance directly from the CFA mosaic of OSC cameras *before* any demosaicing.**  
This provides:

- ✔ **Higher SNR** (≈2× vs. RGB luminance)
- ✔ **Cleaner signal** due to zero interpolation
- ✔ **Sharper micro-detail** after drizzle reconstruction
- ✔ **Compatibility** with Siril, DSS, and Python
- ✔ Works with **any Bayer-pattern OSC camera**

CFALD has demonstrated significant improvements on real targets including **M81**, the **North America Nebula**, and **Orion**.

---

## **Status**

- 🔬 **CFALD v1.3 (Public Research Release)**
- 📄 Whitepaper included  
- 📁 Example data included  
- ⚙ Python reference implementation pending review  
- 💡 Community testing requested  

---

## **What CFALD Is**

- A **true luminance extraction** from the raw RGGB data  
- A **2×2 native bin** of the CFA mosaic  
- A **drizzle-reconstructed** mono channel  
- A **drop-in luminance layer** for OSC workflows  

---

## **What CFALD Is Not**

- Not a debayer algorithm  
- Not a sharpening trick  
- Not a fake resolution upscaler  
- Not tied to any specific sensor or brand  

---

## **Repository Contents**

(Example structure to fill in soon)


---

## **How to Use CFALD**

1. **Calibrate lights in Siril *without debayering***  
2. **Export CFA FITS**  
3. **Run the CFALD Python script** (coming soon)  
4. **Stack luminance frames**  
5. **Apply drizzle reconstruction**  
6. **Combine CFALD-L with RGB** in your processing workflow  

---

## **Contributing**

Pull requests and testing are welcome.  
We especially need:

- Cameras **beyond Canon DSLR**  
- **ASI / QHY / PlayerOne** CFA FITS for verification  
- High-quality datasets (nebulae and galaxies)  

Please open an Issue if you'd like to collaborate or test CFALD with new hardware.

---

## **License**

MIT License (recommended for community use and research adoption)

---

## **Acknowledgements**

Method developed by **Shaun Slade (shaunisagit)** with AI-assisted technical support for documentation and formulation.



