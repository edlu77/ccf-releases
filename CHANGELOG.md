# Changelog

Changelog for the HuBMAP ccf-release Release Notes

## 1.3 - 2022-12-15

### Added in 1.3
**The following reference organs were added with ccf-release v1.3:** 
* left/right female mammary glands
* update to skin to accommodate addition of mammary glands and future skeletal muscle additions in legs
* landmark organs added for mammary gland registration user interface (RUI) support: sternum, manubrium, xiphoid process, axillary tail of breast, lower outer quadrant of breast, lower inner quadrant of breast, upper outer quadrant of breast, lower inner quadrant of breast

* **13 ASCT+B tables were revised:** blood; blood vasculature; bone marrow; brain; eye; heart; large intestine; lymph vasculature; ovary; pancreas; small intestine, spleen; thymus
* **19 2D functional tissue unit (FTU) reference illustrations were added** to support Functional Tissue Unit (FTU) Explorer.
  - **kidney:** nephron, renal corpuscle, cortical collecting duct, outer medullary collecting duct, inner medullary collecting duct, thick ascending loop of Henle, thin ascending loop of Henle, thin descending loop of Henle
  - **large intestine:** crypt of Lieberkuhn
  - **liver:** liver lobule
  - **lung:** alveoli, bronchial submucosal gland
  - **pancreas:** acinus, islets of Langerhans, intercalated duct
  - **prostate:** prostate glandular acinus
  - **skin:** epidermal ridge, dermal papilla
  - **thymus:** thymus lobule


## 1.2 - 2022-06-15

### Added in 1.2
The following reference organs were added with ccf-release v1.2:

* spinal cord, placenta, small intestine measurements

Changes to ccf-release v1.0 models include: 
* Adjustments were made to the skin to account for the verterbral column and eventual addition of female breasts and gatrocnemius muscles. 
* The renal pelvis, major and minor calyxes, were added to the ureter model to better reflect the ontology distinction between kidney and ureter. 
* The nerves, ducts, muscles, some ligaments, and vasculature for organs are split according to 3D Reference Objects. Since these splittings were for UI/back-end reasons, while certain vessels are associated with many organs as general pathways, any one vessel is only ever in one blood vasculature “group”.

* **8 2D functional tissue unit (FTU) reference illustrations were added** to support Functional Tissue Unit (FTU) Explorer.
  - **kidney:** nephron, renal corpuscle
  - **large intestine:** crypt of Lieberkuhn
  - **liver:** liver lobule
  - **lung:** alveolus
  - **pancreas:** islets of Langerhans
  - **prostate:** prostate glandular acinus
  - **thymus:** thymus lobule

## 1.1 - 2021-12-01

### Added in 1.1

* **11 revised ASCT+B tables:** blood/bone marrow; brain; heart; kidney; large intestine; lung; lymph node; skin; spleen; thymus; vasculature
* **13 3D reference objects from female visible human project:** pelvic bone (blood/bone marrow); brain; heart; left/right kidney; large intestine; lung; left/right lymph node (popliteal); skin, spleen; thymus; vasculature
* **13 3D reference objects from male visible human project:** pelvic bone (blood/bone marrow); brain; heart; left/right kidney; large intestine; lung; left/right lymph node (popliteal); skin, spleen; thymus; vasculature

* **11 new reference organs;  26 3D reference objects:** were added as follows: eye; fallopian tube; knee; liver; ovary; pancreas; prostate; small intestine; ureter; urinary bladder; uterus

**Changes to ccf-release v1.0 models include:**

* All female models (with exception to the Allen Brain) were stretched in the Z-axis to accommodate for an error introduced by a derivative visible human dataset for v1.0. The original visible human data was used to rescale v1.1 models.
* The male and female Allen Brains were scaled, repositioned, and rotated to better fit the skin and align with the new eye models
* Vasculature for the uterus, eye, and liver was added to the vasculature model
* The optic chiasm was added to the Allen Brain models
* The nerves, ducts, muscles, some ligaments, and vasculature for organs are split according to 3D Reference Objects. Since these splittings were for UI/back-end reasons, while certain vessels are associated with many organs as general pathways, any one vessel is only ever in one blood vasculature “group”.
* The partial ureters were removed from the v1.0 kidney models as a complete ureter organ is now available
* The heart models now include complete aortas and no longer include the left common carotid, brachiocephalic trunk, or left subclavian. These vessels are also included in the complete blood vasculature model.
*  Minor adjustments were made to several vessels, the skin, and the large intestine to accommodate the new organs.




## 1.0 - 2021-03-12

### Added in 1.0
* **11 ASCT+B tables:** blood/bone marrow; brain; heart; kidney; large intestine; lung; lymph node; skin; spleen; thymus; vasculature
* **13 3D reference objects from female visible human project:** pelvic bone (blood/bone marrow); brain; heart; left/right kidney; large intestine; lung; left/right lymph node (popliteal); skin, spleen; thymus; vasculature
* **13 3D reference objects from male visible human project:** pelvic bone (blood/bone marrow); brain; heart; left/right kidney; large intestine; lung; left/right lymph node (popliteal); skin, spleen; thymus; vasculature

