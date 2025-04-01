# Topic: Image Formation

## 📝 Questions

**1. Consider that we are working with a pinhole camera and an object is present at a distance of z₀ in front of the camera. How would the magnification be affected if we moved the object away from the camera?**

- The magnification would decrease
- The magnification would increase
- The magnification would remain the same
- None of the above

**2. Consider two blurry images captured from two cameras A and B. A has diameter less than ideal size and B has diameter more than ideal size. Is it possible to tell which camera captured which image?**

- Yes
- No
- Yes, if the diameter and focal length are given

**3. Given a pinhole camera whose focal length is 2mm. Calculate the coordinates of the vanishing point of all the parallel lines in the real world which are parallel to the line passing through the point (0.1m, 0.3m, 0.1m) and the pinhole.**

- 2mm, 6mm
- 2m, 6m
- 1mm, 0.66mm
- 1m, 0.66m

**4. An image can only be formed on the focal point.**

- True
- False

**5. Lenses perform perspective projection.**

- True
- False

**6. Why do we use lenses when we have pinhole camera?**

- Cameras with lenses are easier to manufacture than pinhole cameras
- Lenses gather more light than pinhole cameras, reducing exposure time
- Lenses can be stacked to produce a clear image of the scene
- Lenses keep parallel lines from the scene, parallel in the image

**7. How many planes of focus does a fixed lens have?**

- 1
- This depends on the object’s distance from the lens in the scene
- There are multiple; however, an exact number cannot be defined
- Infinite

**8. If a point in 3D space produces a blur circle with radius greater than pixel size, then it is in focus.**

- True
- False

**9. An object at a distance 20mm and an object at a distance 60mm produces a blur circle with a radius less than pixel size. If you move these objects any further the blur circle might be greater than the pixel size. Calculate the depth of field (DoF) for the system.**

- 80mm
- 0.8m
- 40mm
- 60mm

**10. An object R at 50mm from a convex lens produces an image on an image plane. There are two other objects - Object 1 is at a distance of 5mm behind R and Object 2 is 5mm in front of R. What can you say about the amount of blur produced by Objects 1 and 2?**

- Both objects produce same amount of blur
- Object 2 produced more blur than object 1
- Object 1 produces more blur than object 2
- Cannot determine from the information given

**11. What is the _main reason_ to use a series of lenses, rather than use one lens, in real cameras?**

- To gather more light
- To capture images at different distances from the camera
- To capture high quality image over all part of the image

**12. Distortion matrix represents the distortion caused by a lens. Is it possible to correct Radial distortion if we know the distortion matrix?**

- Yes
- No

**13. What is image formation?**

- Projection of points from 2D plane to 3D scene
- Projection of points from 3D scene to 2D plane

---

## ✅ Answers

**1. Answer:** The magnification would decrease  
**Explanation:** Magnification is inversely proportional to the distance of objects in the real world.

**2. Answer:** No  
**Explanation:** Due to diffraction, both smaller and larger than ideal diameters produce similar blur.

**3. Answer:** 2mm, 6mm  
**Formula:** \( (x, y) = (f \cdot x_z/z_s, f \cdot y_z/z_s) \)

**4. Answer:** False  
**Explanation:** An image forms at the focal point only if the object is infinitely far away and on the optical axis.

**5. Answer:** True  
**Explanation:** Lenses follow the same principles of perspective projection.

**6. Answer:** Lenses gather more light than pinhole cameras, reducing exposure time  
**Explanation:** Lenses collect more light and focus it to a point, enabling quicker image capture.

**7. Answer:** 1  
**Explanation:** A fixed lens has only one plane of focus.

**8. Answer:** False  
**Explanation:** A point is in focus only if its blur circle is within one pixel size.

**9. Answer:** 40mm  
**Explanation:** DoF = 60mm - 20mm = 40mm

**10. Answer:** Object 2 produced more blur than object 1  
**Explanation:** Closer to lens = more rapid defocus.

**11. Answer:** To capture high quality image over all part of the image  
**Explanation:** A series of lenses ensures consistent image quality across the frame.

**12. Answer:** Yes  
**Explanation:** Radial distortion can be corrected using the distortion matrix.

**13. Answer:** Projection of points from 3D scene to 2D plane

---

# Topic: Image Sensing

## 📝 Questions


**1. What is the main purpose of image sensors?**

- Converting digital images to optical images.
- Converting optical images to digital images.

**2. Which property of Silicon atoms is leveraged in sensors?**

- Releases electron flux greater than incoming photon flux
- Releases electron flux equal to incoming photon flux
- Releases electron flux lesser than incoming photon flux

**3. What occurs during bucket brigading in CCD sensors?**

- Photons are transferred from one row to the next row.
- Electrons are transferred from one row to the next row.
- Each pixel has its own circuit to convert electrons to voltage.

**4. CMOS sensors have a higher frame rate than CCD sensors.**

- True
- False

**5. Why is the exposed light-sensitive area smaller in CMOS sensors than in CCD sensors?**

- The additional circuitry takes up space.
- They require more power.
- CCD has better circuitry for electron to voltage conversion.

**6. Which of the following inventions catalyzed the development of digital cameras?**

- Pinhole Camera
- Lenses
- Film
- Silicon Image Detectors

**7. In what range of wavelengths is the quantum efficiency of silicon close to 1?**

- Below 400 nm
- Between 400 nm and 1100 nm
- Above 1100 nm

**8. Spectral responses of cones in our eyes are essentially \_\_\_\_ of Silicon atoms.**

- Spectral efficiency
- Quantum efficiency
- Photoelectric effect

**9. The measured brightness is linearly related to incoming photon flux.**

- True
- False

**10. Why would cameras introduce non-linearity to measured brightness?**

- To increase the dynamic range.
- To make images more or less bright
- To compress some brightness ranges more than other brightness ranges

**11. What is the main issue with enhancing the dynamic range of a scene using multiple images with different exposures?**

- The highest brightness value crosses 255
- The images are not clear
- Does not work well for moving images as it essentially adds up multiple images

**12. Which of the following types of noise in image sensors is not scene independent?**

- Photon Shot Noise
- Readout Noise
- Dark Current Noise
- Fixed Pattern Noise

**13. Photon shot noise can always be approximated to a Gaussian Distribution.**

- True
- False

**14. Which of the following is the main cause of fixed pattern noise?**

- Photons arrive at the image sensors at a random rate due to the quantum nature of light.
- Due to errors in converting the number of electrons at the image sensor into voltage.
- Silicon electrons get released not because of the energy of incoming photons but due to heat energy around the camera
- Slight differences between the characteristics of different pixels, introduced during the manufacturing of the image sensor.

**15. Which of the following has the highest dynamic range?**

- Digital Video
- Digital Camera
- Human Eye
- HDR Display

---

## ✅ Answers

**1. Answer:** Converting optical images to digital images  
**Explanation:** Image sensors convert optical signals into electrical signals to be digitally processed or stored.

**2. Answer:** Releases electron flux equal to incoming photon flux  
**Explanation:** Silicon's quantum efficiency ensures one-to-one correspondence between incoming photons and released electrons.

**3. Answer:** Electrons are transferred from one row to the next row  
**Explanation:** In CCDs, charges are moved row by row like passing buckets in a fire brigade.

**4. Answer:** True  
**Explanation:** CMOS sensors allow random access and parallel readout, enabling higher frame rates.

**5. Answer:** The additional circuitry takes up space  
**Explanation:** CMOS pixels include transistors for amplification and readout, reducing the area available for light capture.

**6. Answer:** Silicon Image Detectors  
**Explanation:** These enabled the development of compact, electronic image-capturing devices.

**7. Answer:** Above 1100 nm  
**Explanation:** Silicon detectors approach 100% quantum efficiency at wavelengths above 1100 nm.

**8. Answer:** Quantum efficiency  
**Explanation:** Quantum efficiency refers to how well light (photons) is converted to electric signal—similar to cones in human eyes.

**9. Answer:** False  
**Explanation:** Non-linear tone mapping and gamma correction are applied to adjust brightness perception.

**10. Answer:** To compress some brightness ranges more than other brightness ranges  
**Explanation:** This improves image visibility, especially in shadows and highlights.

**11. Answer:** Does not work well for moving images as it essentially adds up multiple images  
**Explanation:** HDR image blending assumes static scenes; motion causes ghosting artifacts.

**12. Answer:** Photon Shot Noise  
**Explanation:** It depends on the brightness of the scene (i.e., number of incident photons), so it is scene dependent.

**13. Answer:** False  
**Explanation:** Photon shot noise is Poisson-distributed; Gaussian approximation holds only when photon count is high.

**14. Answer:** Slight differences between the characteristics of different pixels, introduced during the manufacturing of the image sensor  
**Explanation:** These variations cause consistent pixel-level brightness inconsistencies — i.e., fixed pattern noise.

**15. Answer:** Human Eye  
**Explanation:** With a dynamic range of around 120 dB, the human eye surpasses digital sensors and even HDR displays.

---

# Topic: Binary Images

## 📝 Questions

---

## ✅ Answers

---

# Topic: Image Processing I

## 📝 Questions

---

## ✅ Answers

---

# Topic: Image Processing II

## 📝 Questions

---

## ✅ Answers

---
