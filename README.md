[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]
# ML Docker GPU  

## **About The Project**  
This project provides a Docker container preconfigured with Lambda Stack and additional configurations to simplify machine learning workflows on GPU-enabled systems. It integrates essential tools and frameworks to streamline the setup for deep learning and machine learning development.

---

### **Built With**  
- **Docker**: For containerization and easy environment management.  
- **Lambda Stack**: Preconfigured stack with TensorFlow, PyTorch, CUDA, and cuDNN for ML workloads.  
- **NVIDIA Container Toolkit**: Enables GPU acceleration in Docker containers.  

---

## **Getting Started**  
Follow these steps to build and run the container locally.  

### **Prerequisites**  
Ensure you have the following installed:  
- Docker (20.10 or later)  
- NVIDIA Docker Toolkit  
- NVIDIA drivers compatible with your GPU  

### **Installation**  

1. Clone the repository:  
   ```sh  
   git clone https://github.com/trucdefou/ml-docker-gpu.git  
   cd ml-docker-gpu  
   ```  

2. Build the Docker image:  
   ```sh  
   docker build -t ml-docker-gpu:latest .  
   ```  

3. Run the container:  
   ```sh  
   docker run --gpus all -it --rm -v $(pwd):/workspace ml-docker-gpu:latest  
   ```  

---

## **Usage**  
- **TensorFlow & PyTorch**: Preinstalled frameworks ready for use with GPU acceleration.  
- **Custom ML Workflows**: Develop, train, and deploy models directly within the container.  
- **Mounted Volumes**: Share files between your local system and the container using the `-v` flag.  

---

## **Roadmap**  
- Add Jupyter Notebook support.  
- Include additional ML libraries like XGBoost and Scikit-learn.  
- Automate environment setup with Docker Compose.  

### Top contributors:
* [![dmnunez1993][github]][dmnunez-url]
* [![trucdefou][dmnunez]][trucdefou-url]
* [![Next][Next.js]][Next-url]
---

## **Contributing**  

1. Fork the repository.  
2. Create a new branch:  
   ```sh  
   git checkout -b feature/YourFeature  
   ```  
3. Commit your changes:  
   ```sh  
   git commit -m "Add YourFeature"  
   ```  
4. Push to the branch:  
   ```sh  
   git push origin feature/YourFeature  
   ```  
5. Open a pull request.  

---

## **License**  
Distributed under the MIT License. See `LICENSE` for more information.  

---

## **Contact**  
**Luciano Recalde**  
[lucianorecalde92@gmail.com](mailto:lucianorecalde92@gmail.com)  
[GitHub Profile](https://github.com/trucdefou)  

---

## **Acknowledgments**  
- [Lambda Stack Documentation](https://lambdalabs.com/lambda-stack-deep-learning-software)  
- [NVIDIA Container Toolkit](https://github.com/NVIDIA/nvidia-docker)  
- [Docker Official Documentation](https://docs.docker.com/)


<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[Next.js]: https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white
[Next-url]: https://nextjs.org/
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/othneildrew
[github]: [https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white](https://img.shields.io/github/:metric/:user/:repo
[Next-url]: https://nextjs.org/
[Bootstrap.com]: https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white
[Bootstrap-url]: https://getbootstrap.com
[JQuery.com]: https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white
[JQuery-url]: https://jquery.com 
