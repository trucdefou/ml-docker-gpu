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

<a href="https://github.com/othneildrew/Best-README-Template/graphs/contributors">
  * [![Vue][Vue.js]][Vue-url]
</a>
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
[contributors-shield]: https://img.shields.io/github/contributors/othneildrew/Best-README-Template.svg?style=for-the-badge
[contributors-url]: https://github.com/othneildrew/Best-README-Template/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/othneildrew/Best-README-Template.svg?style=for-the-badge
[forks-url]: https://github.com/othneildrew/Best-README-Template/network/members
[stars-shield]: https://img.shields.io/github/stars/othneildrew/Best-README-Template.svg?style=for-the-badge
[stars-url]: https://github.com/othneildrew/Best-README-Template/stargazers
[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=for-the-badge
[issues-url]: https://github.com/othneildrew/Best-README-Template/issues
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=for-the-badge
[license-url]: https://github.com/othneildrew/Best-README-Template/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/othneildrew
[product-screenshot]: images/screenshot.png
[Next.js]: https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white
[Next-url]: https://nextjs.org/
[React.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[React-url]: https://reactjs.org/
[Vue.js]: https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D
[Vue-url]: https://vuejs.org/
[Angular.io]: https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white
[Angular-url]: https://angular.io/
[Svelte.dev]: https://img.shields.io/badge/Svelte-4A4A55?style=for-the-badge&logo=svelte&logoColor=FF3E00
[Svelte-url]: https://svelte.dev/
[Laravel.com]: https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white
[Laravel-url]: https://laravel.com
[Bootstrap.com]: https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white
[Bootstrap-url]: https://getbootstrap.com
[JQuery.com]: https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white
[JQuery-url]: https://jquery.com 
