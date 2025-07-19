# realistic-sketches-pix2pix
Sketch-to-Real Image Translation using Pix2Pix GAN on Facades dataset implemented in TensorFlow with visualization and evaluation.
# 🎨 Realistic Sketches: Sketch-to-Photo Translation using Pix2Pix GAN

This project uses a **Pix2Pix GAN** implemented in TensorFlow to **translate architectural sketches into realistic images** using the Facades dataset.

---

## 🚀 Features

✅ Converts architectural sketches into realistic images using GANs.  
✅ Built with **TensorFlow 2.x and Google Colab** for ease of experimentation.  
✅ **Checkpointing** support to resume training without losing progress.  
✅ **Visualization pipeline** for test images and qualitative evaluation.  
✅ Modular and clean notebook for learning and extension.

---



## 📂 Dataset

We use the **Facades dataset** from TensorFlow Datasets:
- `trainA`: real facade images
- `trainB`: corresponding architectural sketches
- `testA` and `testB` for evaluation

The dataset is automatically downloaded and prepared inside the notebook.


## 🛠️ Usage

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/nidhibajaj213/realistic-sketches-pix2pix.git
cd realistic-sketches-pix2pix
```` 

### 2️⃣ Install requirements

```bash
pip install -r requirements.txt
````
### 3️⃣ Run the Notebook

Open the notebook (`realistic_sketches.ipynb`) in Jupyter Notebook locally:

```bash
jupyter notebook
````
### 💾 Checkpoints

During training, model checkpoints are automatically saved every 5 epochs in the `checkpoints/` folder inside the project root.

To resume training, place your `checkpoints/` folder in the project directory before running the notebook — it will automatically load the latest checkpoint.

You can also upload checkpoints to **Google Drive** and mount it to Colab for persistent storage and sharing.

👉 You can access the shared checkpoints here:  
[Google Drive Checkpoints Folder](https://drive.google.com/drive/folders/1bLEZkv3kldQ7ArUwxiJcyRHUj41-J5fJ?usp=drive_link)

###📊 Results
After training, expect the Generator Loss to decrease progressively (e.g., ~11.6 after 50 epochs).

You can visualize generated images side-by-side with sketches and real photos inside the notebook.

The notebook includes code for evaluating on test images with loss calculation and visualization.
### 📝 License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.



### ✨ Author

Built  by **Nidhi Bajaj**

- [LinkedIn](https://www.linkedin.com/in/nidhibajaj/)  
- [GitHub](https://github.com/nidhibajaj213)

---

### 🙌 Acknowledgements

- Original Pix2Pix Paper by Isola et al.  
- TensorFlow framework  
- TensorFlow Datasets  
- Google Colab for free GPU resources

