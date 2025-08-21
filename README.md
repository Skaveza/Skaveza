<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sifa Kaveza Mwachoni - GitHub Profile</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            background-color: #0d1117;
            color: #c9d1d9;
            line-height: 1.6;
            padding: 2rem;
            max-width: 1200px;
            margin: 0 auto;
        }
        
        .container {
            background-color: #161b22;
            border-radius: 12px;
            padding: 2.5rem;
            box-shadow: 0 8px 24px rgba(0, 0, 0, 0.2);
            border: 1px solid #30363d;
        }
        
        header {
            text-align: center;
            margin-bottom: 2.5rem;
            padding-bottom: 2rem;
            border-bottom: 1px solid #30363d;
        }
        
        h1 {
            font-size: 2.5rem;
            color: #58a6ff;
            margin-bottom: 0.5rem;
            background: linear-gradient(45deg, #58a6ff, #3fb950);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
        
        h2 {
            font-size: 1.5rem;
            color: #c9d1d9;
            margin-bottom: 1.5rem;
            display: flex;
            align-items: center;
            gap: 10px;
        }
        
        h2::before {
            content: "";
            display: inline-block;
            height: 2px;
            width: 30px;
            background: linear-gradient(45deg, #58a6ff, #3fb950);
        }
        
        h3 {
            font-size: 1.2rem;
            color: #58a6ff;
            margin-bottom: 1rem;
        }
        
        .tagline {
            font-size: 1.2rem;
            color: #8b949e;
            margin-bottom: 1rem;
        }
        
        .flag {
            font-size: 1.5rem;
            vertical-align: middle;
            margin-left: 0.5rem;
        }
        
        .section {
            margin-bottom: 2.5rem;
            padding: 1.5rem;
            background-color: #0d1117;
            border-radius: 8px;
            border: 1px solid #21262d;
        }
        
        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 1.5rem;
            margin-bottom: 2rem;
        }
        
        .card {
            background: linear-gradient(145deg, #161b22, #1a2029);
            padding: 1.5rem;
            border-radius: 8px;
            border: 1px solid #30363d;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        
        .card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.3);
            border-color: #58a6ff;
        }
        
        .social-links {
            display: flex;
            flex-wrap: wrap;
            gap: 1rem;
            margin-top: 1rem;
        }
        
        .social-btn {
            display: flex;
            align-items: center;
            gap: 8px;
            padding: 0.6rem 1.2rem;
            background: linear-gradient(45deg, #238636, #2ea043);
            color: white;
            text-decoration: none;
            border-radius: 6px;
            font-weight: 500;
            transition: all 0.3s ease;
        }
        
        .social-btn:hover {
            background: linear-gradient(45deg, #2ea043, #3fb950);
            transform: translateY(-2px);
            box-shadow: 0 4px 12px rgba(46, 160, 67, 0.3);
        }
        
        .social-icon {
            width: 20px;
            height: 20px;
        }
        
        .tools-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(70px, 1fr));
            gap: 1rem;
            margin-top: 1rem;
        }
        
        .tool-item {
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            padding: 0.8rem;
            background-color: #161b22;
            border-radius: 8px;
            border: 1px solid #30363d;
            transition: all 0.3s ease;
        }
        
        .tool-item:hover {
            background-color: #1c2129;
            border-color: #58a6ff;
            transform: scale(1.05);
        }
        
        .tool-icon {
            width: 30px;
            height: 30px;
            margin-bottom: 0.5rem;
        }
        
        .tool-name {
            font-size: 0.7rem;
            text-align: center;
            color: #8b949e;
        }
        
        .highlight {
            color: #58a6ff;
            font-weight: 600;
        }
        
        .email-link {
            color: #58a6ff;
            text-decoration: none;
            font-weight: 500;
            transition: color 0.3s ease;
        }
        
        .email-link:hover {
            color: #79c0ff;
            text-decoration: underline;
        }
        
        .resume-link {
            display: inline-flex;
            align-items: center;
            gap: 8px;
            padding: 0.5rem 1rem;
            background-color: #238636;
            color: white;
            text-decoration: none;
            border-radius: 6px;
            font-weight: 500;
            margin-top: 0.5rem;
            transition: all 0.3s ease;
        }
        
        .resume-link:hover {
            background-color: #2ea043;
            transform: translateY(-2px);
        }
        
        @media (max-width: 768px) {
            body {
                padding: 1rem;
            }
            
            .container {
                padding: 1.5rem;
            }
            
            h1 {
                font-size: 2rem;
            }
            
            .grid {
                grid-template-columns: 1fr;
            }
            
            .tools-grid {
                grid-template-columns: repeat(auto-fill, minmax(60px, 1fr));
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>Hi 👋, I'm Sifa Kaveza Mwachoni</h1>
            <p class="tagline">A passionate Machine Learning Engineer from Kenya <span class="flag">🇰🇪</span> | Building AI for impact</p>
        </header>
        
        <div class="grid">
            <div class="card">
                <h2>About Me</h2>
                <p>I'm a Machine Learning Engineer focused on creating AI solutions that make a real difference in people's lives, especially in underserved regions.</p>
                <p>My current work involves developing AI-powered diagnostic chatbots to improve healthcare accessibility.</p>
            </div>
            
            <div class="card">
                <h2>Current Focus</h2>
                <p>🌱 <span class="highlight">Learning:</span> LLM deployment (LangChain, Ollama), MLOps (MLflow), and NLP optimization (Hugging Face, quantization)</p>
                <p>🔭 <span class="highlight">Working on:</span> AI-powered diagnostic chatbots for underserved regions</p>
                <p>🤝 <span class="highlight">Looking to collaborate on:</span> Open-source ML projects in healthcare/finance (especially NLP/LLMs)</p>
                <p>🙏 <span class="highlight">Looking for help with:</span> Fine-tuning LLMs for multilingual support</p>
            </div>
        </div>
        
        <div class="section">
            <h2>Get In Touch</h2>
            <p>💬 <span class="highlight">Ask me about:</span> Python, ML Classification Models, NLP chatbots</p>
            <p>📫 <span class="highlight">How to reach me:</span> <a href="mailto:sifakaveza@gmail.com" class="email-link">sifakaveza@gmail.com</a></p>
            <p>📄 <span class="highlight">Know about my experiences:</span> 
                <a href="https://docs.google.com/document/d/1a1L2TAVejGe_ys9QgPQiVHD4hmVbOVH4E11X34GCxEM/edit?usp=sharing" class="resume-link" target="_blank">
                    View My Resume
                </a>
            </p>
            
            <h3>Connect with me:</h3>
            <div class="social-links">
                <a href="https://www.linkedin.com/in/sifa-mwachoni/" target="_blank" class="social-btn">
                    <svg class="social-icon" viewBox="0 0 24 24" fill="white">
                        <path d="M20.447 20.452h-3.554v-5.569c0-1.328-.027-3.037-1.852-3.037-1.853 0-2.136 1.445-2.136 2.939v5.667H9.351V9h3.414v1.561h.046c.477-.9 1.637-1.85 3.37-1.85 3.601 0 4.267 2.37 4.267 5.455v6.286zM5.337 7.433c-1.144 0-2.063-.926-2.063-2.065 0-1.138.92-2.063 2.063-2.063 1.14 0 2.064.925 2.064 2.063 0 1.139-.925 2.065-2.064 2.065zm1.782 13.019H3.555V9h3.564v11.452zM22.225 0H1.771C.792 0 0 .774 0 1.729v20.542C0 23.227.792 24 1.771 24h20.451C23.2 24 24 23.227 24 22.271V1.729C24 .774 23.2 0 22.222 0h.003z"/>
                    </svg>
                    LinkedIn
                </a>
                
                <a href="https://kaggle.com/sifamwachoni" target="_blank" class="social-btn">
                    <svg class="social-icon" viewBox="0 0 24 24" fill="white">
                        <path d="M18.825 23.859c-.022.092-.117.141-.281.141h-3.139c-.187 0-.351-.082-.492-.248l-5.178-6.589-1.448 1.374v5.111c0 .235-.117.352-.351.352H5.505c-.236 0-.354-.117-.354-.352V.353c0-.233.118-.353.354-.353h2.431c.234 0 .351.12.351.353v14.343l6.203-6.272c.165-.165.33-.246.495-.246h3.239c.144 0 .236.06.285.18.046.149.034.255-.036.315l-6.555 6.344 6.836 8.507c.095.104.117.208.07.358"/>
                    </svg>
                    Kaggle
                </a>
                
                <a href="https://instagram.com/sifakaveza" target="_blank" class="social-btn">
                    <svg class="social-icon" viewBox="0 0 24 24" fill="white">
                        <path d="M12 2.163c3.204 0 3.584.012 4.85.07 3.252.148 4.771 1.691 4.919 4.919.058 1.265.069 1.645.069 4.849 0 3.205-.012 3.584-.069 4.849-.149 3.225-1.664 4.771-4.919 4.919-1.266.058-1.644.07-4.85.07-3.204 0-3.584-.012-4.849-.07-3.26-.149-4.771-1.699-4.919-4.92-.058-1.265-.07-1.644-.07-4.849 0-3.204.013-3.583.07-4.849.149-3.227 1.664-4.771 4.919-4.919 1.266-.057 1.645-.069 4.849-.069zM12 0C8.741 0 8.333.014 7.053.072 2.695.272.273 2.69.073 7.052.014 8.333 0 8.741 0 12c0 3.259.014 3.668.072 4.948.2 4.358 2.618 6.78 6.98 6.98C8.333 23.986 8.741 24 12 24c3.259 0 3.668-.014 4.948-.072 4.354-.2 6.782-2.618 6.979-6.98.059-1.28.073-1.689.073-4.948 0-3.259-.014-3.667-.072-4.947-.196-4.354-2.617-6.78-6.979-6.98C15.668.014 15.259 0 12 0zm0 5.838a6.162 6.162 0 100 12.324 6.162 6.162 0 000-12.324zM12 16a4 4 0 110-8 4 4 0 010 8zm6.406-11.845a1.44 1.44 0 100 2.881 1.44 1.44 0 000-2.881z"/>
                    </svg>
                    Instagram
                </a>
            </div>
        </div>
        
        <div class="section">
            <h2>Languages and Tools</h2>
            <div class="tools-grid">
                <div class="tool-item">
                    <img src="https://www.vectorlogo.zone/logos/python/python-icon.svg" alt="Python" class="tool-icon">
                    <span class="tool-name">Python</span>
                </div>
                <div class="tool-item">
                    <img src="https://www.vectorlogo.zone/logos/pytorch/pytorch-icon.svg" alt="PyTorch" class="tool-icon">
                    <span class="tool-name">PyTorch</span>
                </div>
                <div class="tool-item">
                    <img src="https://www.vectorlogo.zone/logos/tensorflow/tensorflow-icon.svg" alt="TensorFlow" class="tool-icon">
                    <span class="tool-name">TensorFlow</span>
                </div>
                <div class="tool-item">
                    <img src="https://www.vectorlogo.zone/logos/opencv/opencv-icon.svg" alt="OpenCV" class="tool-icon">
                    <span class="tool-name">OpenCV</span>
                </div>
                <div class="tool-item">
                    <img src="https://www.vectorlogo.zone/logos/docker/docker-icon.svg" alt="Docker" class="tool-icon">
                    <span class="tool-name">Docker</span>
                </div>
                <div class="tool-item">
                    <img src="https://www.vectorlogo.zone/logos/flutterio/flutterio-icon.svg" alt="Flutter" class="tool-icon">
                    <span class="tool-name">Flutter</span>
                </div>
                <div class="tool-item">
                    <img src="https://www.vectorlogo.zone/logos/dartlang/dartlang-icon.svg" alt="Dart" class="tool-icon">
                    <span class="tool-name">Dart</span>
                </div>
                <div class="tool-item">
                    <img src="https://www.vectorlogo.zone/logos/firebase/firebase-icon.svg" alt="Firebase" class="tool-icon">
                    <span class="tool-name">Firebase</span>
                </div>
                <div class="tool-item">
                    <img src="https://www.vectorlogo.zone/logos/nginx/nginx-icon.svg" alt="Nginx" class="tool-icon">
                    <span class="tool-name">Nginx</span>
                </div>
                <div class="tool-item">
                    <img src="https://www.vectorlogo.zone/logos/postgresql/postgresql-icon.svg" alt="PostgreSQL" class="tool-icon">
                    <span class="tool-name">PostgreSQL</span>
                </div>
                <div class="tool-item">
                    <img src="https://www.vectorlogo.zone/logos/getpostman/getpostman-icon.svg" alt="Postman" class="tool-icon">
                    <span class="tool-name">Postman</span>
                </div>
                <div class="tool-item">
                    <img src="https://www.vectorlogo.zone/logos/pocoo_flask/pocoo_flask-icon.svg" alt="Flask" class="tool-icon">
                    <span class="tool-name">Flask</span>
                </div>
                <div class="tool-item">
                    <img src="https://www.vectorlogo.zone/logos/pandas/pandas-icon.svg" alt="Pandas" class="tool-icon">
                    <span class="tool-name">Pandas</span>
                </div>
                <div class="tool-item">
                    <img src="https://www.vectorlogo.zone/logos/scikit_learn/scikit_learn-icon.svg" alt="Scikit-learn" class="tool-icon">
                    <span class="tool-name">Scikit-learn</span>
                </div>
                <div class="tool-item">
                    <img src="https://seaborn.pydata.org/_images/logo-mark-lightbg.svg" alt="Seaborn" class="tool-icon">
                    <span class="tool-name">Seaborn</span>
                </div>
            </div>
        </div>
    </div>
</body>
</html>
