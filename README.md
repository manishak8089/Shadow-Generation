# Realistic Shadow Generation with GAN

This project demonstrates realistic shadow generation on natural images using a custom-trained GAN model. Given a deshadowed input image, the model learns to cast shadows in appropriate regions, conditioned on the shadow mask and instance segmentation.

---

## Project Structure

- `1_shadow_generation_code.ipynb`: Main Colab notebook for model inference
- `assets/`: Folder containing input, output, and mask visualizations
- `models/`: Generator and discriminator architectures 
- `utils/`: Image preprocessing and visualization functions

---

## ⚙️ How It Works

1. **Input**: A deshadowed RGB image
2. **Preprocessing**: Generates:
   - Shadow mask (binary)
   - Instance mask (semantic segmentation)
3. **GAN-based Generation**: Produces a realistic shadow-cast image
4. **Post-processing**: Visualization and export

---

## Technologies Used

- Python, PyTorch, NumPy, OpenCV
- Google Colab for experimentation
- GANs: U-Net Generator, PatchGAN Discriminator

---

## Notes

- This is a research-oriented prototype for cast shadow synthesis.
- Ideal for use in training data augmentation, simulation, or visual effects.

---

## Acknowledgement

Sample image of zebra sourced from open dataset used for testing.

<img width="635" height="441" alt="Image" src="https://github.com/user-attachments/assets/294ec22e-822e-480b-ba30-801f857c9e83" />



