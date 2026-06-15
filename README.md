<!DOCTYPE html><html class="dark" lang="en" style=""><head>
<meta charset="utf-8">
<meta content="width=device-width, initial-scale=1.0" name="viewport">
<title>Nikhil Pratap Singh | ML Engineer &amp; Researcher</title>
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<link href="https://fonts.googleapis.com/css2?family=Outfit:wght@100..900&amp;family=Inter:wght@100..900&amp;family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet">
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet">
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@100..900&amp;family=Outfit:wght@100..900&amp;display=swap" rel="stylesheet">
<script id="tailwind-config">
      tailwind.config = {
        darkMode: "class",
        theme: {
          extend: {
            "colors": {
                    "inverse-on-surface": "#313030",
                    "on-surface": "#e5e2e1",
                    "surface-container-low": "#1c1b1b",
                    "surface-variant": "#353534",
                    "background": "#131313",
                    "secondary-fixed-dim": "#c6c6c7",
                    "surface-dim": "#131313",
                    "outline": "#9a8f80",
                    "on-secondary-fixed": "#1a1c1c",
                    "outline-variant": "#4e4639",
                    "text-muted": "#A3A3A3",
                    "tertiary-container": "#9eb6e7",
                    "on-secondary": "#2f3131",
                    "on-error": "#690005",
                    "surface-container-high": "#2a2a2a",
                    "on-error-container": "#ffdad6",
                    "primary-fixed": "#ffdea7",
                    "secondary-container": "#454747",
                    "on-tertiary-fixed-variant": "#2e4771",
                    "surface-bright": "#3a3939",
                    "on-primary-fixed-variant": "#5e4201",
                    "primary-fixed-dim": "#eac077",
                    "on-secondary-container": "#b4b5b5",
                    "on-primary-container": "#5e4202",
                    "on-primary": "#412d00",
                    "primary": "#f6cb81",
                    "error-container": "#93000a",
                    "secondary": "#c6c6c7",
                    "surface-container-highest": "#353534",
                    "on-background": "#e5e2e1",
                    "on-surface-variant": "#d1c5b4",
                    "on-tertiary-container": "#2e4771",
                    "on-primary-fixed": "#271900",
                    "error": "#ffb4ab",
                    "surface-tint": "#eac077",
                    "inverse-primary": "#78591a",
                    "tertiary": "#bcd2ff",
                    "secondary-fixed": "#e2e2e2",
                    "primary-container": "#d8b068",
                    "surface": "#131313",
                    "tertiary-fixed": "#d7e2ff",
                    "surface-border": "#262626",
                    "on-tertiary": "#153059",
                    "surface-container-lowest": "#0e0e0e",
                    "on-secondary-fixed-variant": "#454747",
                    "surface-container": "#201f1f",
                    "inverse-surface": "#e5e2e1",
                    "surface-elevated": "#121212",
                    "tertiary-fixed-dim": "#afc7f9",
                    "on-tertiary-fixed": "#001b3f"
            },
            "borderRadius": {
                    "DEFAULT": "0.125rem",
                    "lg": "0.25rem",
                    "xl": "0.5rem",
                    "full": "0.75rem"
            },
            "spacing": {
                    "gutter": "24px",
                    "base": "8px",
                    "margin-mobile": "20px",
                    "section-gap": "120px",
                    "container-max": "1200px"
            },
            "fontFamily": {
                    "body-lg": ["Inter"],
                    "headline-lg": ["Outfit"],
                    "body-md": ["Inter"],
                    "label-md": ["Inter"],
                    "mono-code": ["Inter"],
                    "headline-md": ["Outfit"],
                    "display-lg-mobile": ["Outfit"],
                    "display-lg": ["Outfit"]
            },
            "fontSize": {
                    "body-lg": ["18px", {"lineHeight": "28px", "fontWeight": "400"}],
                    "headline-lg": ["32px", {"lineHeight": "40px", "fontWeight": "700"}],
                    "body-md": ["16px", {"lineHeight": "24px", "fontWeight": "400"}],
                    "label-md": ["14px", {"lineHeight": "20px", "letterSpacing": "0.05em", "fontWeight": "600"}],
                    "mono-code": ["14px", {"lineHeight": "22px", "fontWeight": "400"}],
                    "headline-md": ["24px", {"lineHeight": "32px", "fontWeight": "600"}],
                    "display-lg-mobile": ["40px", {"lineHeight": "44px", "letterSpacing": "-0.02em", "fontWeight": "800"}],
                    "display-lg": ["72px", {"lineHeight": "80px", "letterSpacing": "-0.04em", "fontWeight": "800"}]
            }
          },
        },
      }
    </script>
<style>
        .material-symbols-outlined {
            font-variation-settings: 'FILL' 0, 'wght' 400, 'GRAD' 0, 'opsz' 24;
        }
        body {
            background-color: #131313;
            color: #e5e2e1;
            scroll-behavior: smooth;
        }
        .bento-grid {
            display: grid;
            grid-template-columns: repeat(12, 1fr);
            gap: 24px;
        }
        .skill-chip {
            background: rgba(216, 176, 104, 0.05);
            border: 1px solid rgba(216, 176, 104, 0.2);
        }
        .custom-glow {
            box-shadow: 0 0 40px -10px rgba(216, 176, 104, 0.15);
        }
        @media (max-width: 768px) {
            .bento-grid {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body class="font-body-md text-body-md antialiased" data-mode="connect">
<!-- Top Navigation Shell -->
<nav class="fixed top-0 left-0 w-full z-50 flex justify-between items-center px-gutter py-4 max-w-container-max mx-auto bg-background/80 backdrop-blur-md border-b border-surface-border">
<div class="font-headline-md text-headline-md font-bold text-on-surface tracking-tighter uppercase">NIKHIL PRATAP SINGH</div>
<div class="hidden md:flex items-center gap-8">
<a class="text-text-muted font-medium hover:text-on-surface transition-colors font-body-md text-body-md" href="#experience">Experience</a>
<a class="text-text-muted font-medium hover:text-on-surface transition-colors font-body-md text-body-md" href="#projects">Projects</a>
<a class="text-text-muted font-medium hover:text-on-surface transition-colors font-body-md text-body-md" href="#skills">Skills</a>
<a class="text-text-muted font-medium hover:text-on-surface transition-colors font-body-md text-body-md" href="#achievements">Achievements</a>
</div>
<button class="bg-primary-container text-on-primary font-label-md text-label-md px-6 py-2 rounded-DEFAULT font-bold active:scale-95 transition-all">Contact Me</button>
</nav>
<main class="pt-24">
<!-- Hero Section -->
<section class="relative min-h-[819px] flex flex-col justify-center px-gutter max-w-container-max mx-auto overflow-hidden transition-all duration-1000 opacity-100 translate-y-0">

<div class="max-w-4xl space-y-8">
<p class="text-primary font-label-md text-label-md uppercase tracking-widest animate-pulse">Machine Learning Engineer</p>
<h1 class="font-display-lg text-display-lg leading-none uppercase md:text-display-lg text-display-lg-mobile">
                    Crafting <span class="text-primary">Intelligence</span><br>Through Mathematics.
                </h1>
<p class="font-body-lg text-body-lg text-text-muted max-w-2xl">
                    Dual Degree student at <span class="text-on-surface font-bold">IIT (BHU) Varanasi</span>. Architecting high-performance Machine Learning models with a focus on mathematical precision and technical excellence.
                </p>
<div class="flex flex-wrap gap-4 pt-4">
<a class="flex items-center gap-2 border border-surface-border bg-surface-elevated px-6 py-3 hover:border-primary transition-colors" href="https://linkedin.com">
<span class="material-symbols-outlined text-primary">link</span>
<span class="font-label-md text-label-md">LinkedIn</span>
</a>
<a class="flex items-center gap-2 border border-surface-border bg-surface-elevated px-6 py-3 hover:border-primary transition-colors" href="https://github.com">
<span class="material-symbols-outlined text-primary">terminal</span>
<span class="font-label-md text-label-md">GitHub</span>
</a>
</div>
</div>
</section>
<!-- Professional Summary -->
<section class="py-section-gap px-gutter max-w-container-max mx-auto transition-all duration-1000 opacity-100 translate-y-0">
<div class="grid md:grid-cols-2 gap-12 items-center">
<div class="relative group">
<div class="absolute -inset-2 bg-primary/20 blur-2xl rounded-full opacity-0 group-hover:opacity-100 transition-opacity duration-700"></div>
<img class="relative w-full aspect-[4/5] object-cover border border-surface-border grayscale hover:grayscale-0 transition-all duration-700" data-alt="A professional, high-contrast black and white portrait of a young male engineer in a modern setting. The lighting is dramatic, creating sharp silhouettes and emphasizing a mood of focused intelligence. The environment is minimalist and technical, with a slight golden rim light that connects to the brand's primary accent color. The overall style is cinematic and editorial." src="https://lh3.googleusercontent.com/aida-public/AB6AXuAeUMleu1fYR2Zj6JbkSZqjuGP0C9rwfENYldWdZ8hUv5D7_hXG-ajAHl2CWpor1vNQbt_Hj1br6UTTKUQ9KucHIyZdw-59dX6V34Dh_ZJNJAxns0PACYb1NXW8wXRLdI8NZdpDLRb_vBk0IGvqt7W75SNClEg5JvgC6IU4AZbNwgMBDAGrRhlmCT03Hy8foDmhTUXIlmJ6KMu8oRo7k_nTRjOnjJhPlR8Z26U6SoGwQvNF988MO0SwnYDh23cgLVrOs1RM5-LzyuKb">
</div>
<div class="space-y-6">
<h2 class="font-headline-lg text-headline-lg text-on-surface uppercase border-l-4 border-primary pl-6">The Thesis</h2>
<p class="font-body-lg text-body-lg text-text-muted leading-relaxed">
                        I specialize in bridging the gap between theoretical mathematics and practical engineering. My journey at IIT (BHU) has been defined by a relentless pursuit of optimizing neural architectures and predictive algorithms. 
                    </p>
<p class="font-body-lg text-body-lg text-text-muted leading-relaxed">
                        Whether it's detecting subtle facial expressions in real-time or predicting financial outcomes through complex data pipelines, my approach remains the same: <span class="text-on-surface font-semibold">Maximum Clarity, Minimal Latency.</span>
</p>
<div class="pt-6 grid grid-cols-2 gap-8">
<div>
<div class="text-primary font-display-lg text-headline-lg">IIT (BHU)</div>
<p class="text-label-md text-text-muted">Dual Degree Engineering</p>
</div>
<div>
<div class="text-primary font-display-lg text-headline-lg">99th%</div>
<p class="text-label-md text-text-muted">Problem Solving Skills</p>
</div>
</div>
</div>
</div>
</section>
<!-- Skills Grid (Bento Style) -->
<section class="py-section-gap px-gutter max-w-container-max mx-auto bg-surface-container-lowest py-24 transition-all duration-1000 opacity-100 translate-y-0" id="skills">
<h2 class="font-headline-lg text-headline-lg text-on-surface mb-16 text-center uppercase tracking-tighter">Core Competencies</h2>
<div class="bento-grid">
<!-- ML Concepts -->
<div class="col-span-12 md:col-span-4 bg-surface-elevated border border-surface-border p-8 hover:border-primary transition-all group">
<span class="material-symbols-outlined text-primary mb-4 text-4xl" data-weight="fill">neurology</span>
<h3 class="font-headline-md text-headline-md mb-4 uppercase">ML Concepts</h3>
<div class="flex flex-wrap gap-2">
<span class="px-3 py-1 skill-chip text-label-md rounded-lg">Supervised Learning</span>
<span class="px-3 py-1 skill-chip text-label-md rounded-lg">Unsupervised Learning</span>
<span class="px-3 py-1 skill-chip text-label-md rounded-lg">Deep Learning</span>
<span class="px-3 py-1 skill-chip text-label-md rounded-lg">Feature Engineering</span>
</div>
</div>
<!-- Programming -->
<div class="col-span-12 md:col-span-8 bg-surface-elevated border border-surface-border p-8 hover:border-primary transition-all">
<span class="material-symbols-outlined text-primary mb-4 text-4xl">code</span>
<h3 class="font-headline-md text-headline-md mb-4 uppercase">Programming &amp; Mathematics</h3>
<div class="grid grid-cols-2 md:grid-cols-4 gap-4">
<ul class="space-y-2 text-text-muted">
<li class="flex items-center gap-2"><span class="w-1 h-1 bg-primary"></span>Python</li>
<li class="flex items-center gap-2"><span class="w-1 h-1 bg-primary"></span>C++</li>
<li class="flex items-center gap-2"><span class="w-1 h-1 bg-primary"></span>SQL</li>
</ul>
<ul class="space-y-2 text-text-muted">
<li class="flex items-center gap-2"><span class="w-1 h-1 bg-primary"></span>Linear Algebra</li>
<li class="flex items-center gap-2"><span class="w-1 h-1 bg-primary"></span>Calculus</li>
<li class="flex items-center gap-2"><span class="w-1 h-1 bg-primary"></span>Statistics</li>
</ul>
</div>
</div>
<!-- Libraries -->
<div class="col-span-12 md:col-span-8 bg-surface-elevated border border-surface-border p-8 hover:border-primary transition-all">
<span class="material-symbols-outlined text-primary mb-4 text-4xl">inventory_2</span>
<h3 class="font-headline-md text-headline-md mb-4 uppercase">Libraries &amp; Frameworks</h3>
<div class="flex flex-wrap gap-4 text-on-surface">
<div class="flex items-center gap-3 bg-background p-3 border border-surface-border">
<span class="material-symbols-outlined text-primary">analytics</span> NumPy / Pandas
                        </div>
<div class="flex items-center gap-3 bg-background p-3 border border-surface-border">
<span class="material-symbols-outlined text-primary">hub</span> PyTorch / TensorFlow
                        </div>
<div class="flex items-center gap-3 bg-background p-3 border border-surface-border">
<span class="material-symbols-outlined text-primary">show_chart</span> Scikit-Learn
                        </div>
<div class="flex items-center gap-3 bg-background p-3 border border-surface-border">
<span class="material-symbols-outlined text-primary">data_object</span> Matplotlib
                        </div>
</div>
</div>
<!-- Tools -->
<div class="col-span-12 md:col-span-4 bg-surface-elevated border border-surface-border p-8 hover:border-primary transition-all">
<span class="material-symbols-outlined text-primary mb-4 text-4xl">build</span>
<h3 class="font-headline-md text-headline-md mb-4 uppercase">Toolchain</h3>
<ul class="space-y-3 text-text-muted">
<li class="">Git &amp; GitHub</li>
<li class="">VS Code / Jupyter</li>
<li class="">Docker</li>
<li class="">Postman</li>
</ul>
</div>
</div>
</section>
<!-- Projects Section -->
<section class="py-section-gap px-gutter max-w-container-max mx-auto transition-all duration-1000 opacity-100 translate-y-0" id="projects">
<div class="flex justify-between items-end mb-16">
<div>
<h2 class="font-headline-lg text-headline-lg uppercase text-on-surface">Featured Works</h2>
<p class="text-text-muted mt-2">End-to-end Machine Learning Implementations</p>
</div>
<div class="h-px flex-1 bg-surface-border mx-8 hidden md:block"></div>
</div>
<div class="grid md:grid-cols-3 gap-8">
<!-- Project 1 -->
<div class="group bg-surface-elevated border border-surface-border overflow-hidden flex flex-col">
<div class="h-64 overflow-hidden bg-background">
<img class="w-full h-full object-cover grayscale group-hover:grayscale-0 group-hover:scale-105 transition-all duration-500" data-alt="A sophisticated close-up of a human eye with a digital grid overlaying the face, representing facial recognition technology. The scene is illuminated with a dark moody lighting, featuring sharp gold and white data points across the features. The aesthetic is clean, technical, and high-contrast, fitting a professional ML portfolio." src="https://lh3.googleusercontent.com/aida-public/AB6AXuDm4rfotIczDfFCAEOvjppWY13t-FMtvoYXSZw3p8rzd9fNumk5SasQ4cI4y0LjnhUu8vJhkS-SsN23hRG1LsRV3Mx-PeQaW5WiCH03gPqqVDVKKwSY2vCiAutU6MU4CJmiVmvt41bz6bz3uOKslicUEi9Fmfck5qegj5SEEBn4sg5xsfK9fayn_bL1iobmH3vk0V2tR5mKlx1sh79xktzJQhsrDmetqbiEAYPf1rIKwR4-WSzcoLuopKM1Vi77UVuPe0LXBKFLAljn">
</div>
<div class="p-8 flex-1 flex flex-col">
<div class="flex flex-wrap gap-2 mb-4">
<span class="text-[10px] uppercase font-bold tracking-wider text-primary border border-primary/30 px-2 py-0.5">CNN</span>
<span class="text-[10px] uppercase font-bold tracking-wider text-primary border border-primary/30 px-2 py-0.5">PyTorch</span>
</div>
<h3 class="font-headline-md text-headline-md uppercase mb-4">Facial Emotion Recognition</h3>
<ul class="text-text-muted space-y-2 mb-8 flex-1">
<li class="flex items-start gap-2"><span class="text-primary mt-1.5 w-1.5 h-1.5 rounded-full shrink-0 bg-primary"></span> Developed a real-time emotion detection system using deep CNNs.</li>
<li class="flex items-start gap-2"><span class="text-primary mt-1.5 w-1.5 h-1.5 rounded-full shrink-0 bg-primary"></span> Optimized model architecture for low-latency inference on edge devices.</li>
</ul>
<a class="mt-auto flex items-center gap-2 font-label-md text-label-md text-on-surface hover:text-primary transition-colors" href="#">
                            View Repository <span class="material-symbols-outlined text-sm">arrow_outward</span>
</a>
</div>
</div>
<!-- Project 2 -->
<div class="group bg-surface-elevated border border-surface-border overflow-hidden flex flex-col">
<div class="h-64 overflow-hidden bg-background">
<img class="w-full h-full object-cover grayscale group-hover:grayscale-0 group-hover:scale-105 transition-all duration-500" data-alt="A minimalist abstract visualization of financial data flows and probability curves. Deep black background with glowing golden lines representing predictive analytics and loan repayment trends. The lighting is sophisticated and directional, creating a sense of professional reliability and mathematical precision." src="https://lh3.googleusercontent.com/aida-public/AB6AXuAhurBmKXMg8hq5QMVrp5H9TdLDhG8-x9gUSowVlUT_kRYIc-XdDlJQTWzbZdzHzZIn81XzhFxJP46iRIfZ1zNsgcdeK3PnWb4ctGglRHTG_bBIUM0EWBTQTMBtkRvSkFz9Xl5AENi-erckdadIceo37cQt3zcc_yHO3NrKHJihXqZ9-mQgmM5hgJlrmYzfXSTy3TnU4oAcgj_lwIYPvuE-3xSe--XlddZflM58QAOY5eODhrvLLfDpeo1TegADU1xZB1T5aAXjToXE">
</div>
<div class="p-8 flex-1 flex flex-col">
<div class="flex flex-wrap gap-2 mb-4">
<span class="text-[10px] uppercase font-bold tracking-wider text-primary border border-primary/30 px-2 py-0.5">XGBoost</span>
<span class="text-[10px] uppercase font-bold tracking-wider text-primary border border-primary/30 px-2 py-0.5">FinTech</span>
</div>
<h3 class="font-headline-md text-headline-md uppercase mb-4">Loan Repayment Prediction</h3>
<ul class="text-text-muted space-y-2 mb-8 flex-1">
<li class="flex items-start gap-2"><span class="text-primary mt-1.5 w-1.5 h-1.5 rounded-full shrink-0 bg-primary"></span> Engineered robust risk assessment models using ensemble techniques.</li>
<li class="flex items-start gap-2"><span class="text-primary mt-1.5 w-1.5 h-1.5 rounded-full shrink-0 bg-primary"></span> Achieved 94%+ accuracy on imbalanced datasets via SMOTE.</li>
</ul>
<a class="mt-auto flex items-center gap-2 font-label-md text-label-md text-on-surface hover:text-primary transition-colors" href="#">
                            View Repository <span class="material-symbols-outlined text-sm">arrow_outward</span>
</a>
</div>
</div>
<!-- Project 3 -->
<div class="group bg-surface-elevated border border-surface-border overflow-hidden flex flex-col">
<div class="h-64 overflow-hidden bg-background">
<img class="w-full h-full object-cover grayscale group-hover:grayscale-0 group-hover:scale-105 transition-all duration-500" data-alt="An artistic representation of high-level academic achievement and data. A dark, sophisticated study environment with modern tech and classical library elements subtly visible in the background. Glowing golden particles represent successful admissions and data points flowing towards a centralized goal. Elegant, high-contrast style." src="https://lh3.googleusercontent.com/aida-public/AB6AXuBgUPEaYqyr124_HNnvxI8d-pAcTJlRfhYzhQR_WUulhnO1fmCkiRD4HmXdCIH4zD6vxNvtkTzq10hYkKnu13T6gOqgBsuBRHr5Dt4Vw0z1DkNxiU6W7mZrUFsQVt1tjU2_w1tUY5GCVPD4r_Ts5KsIzoHwbZUGgypFvsqVSCRlxxyxr5Vt2vtWclkUW5hv3CsUZ6aczTEmcqy8mXRwoSPHRhlP-7voINVttm0VVUkLSfd-8YInWGU1A48aFGFaF7EmgHgxrUU9FXfR">
</div>
<div class="p-8 flex-1 flex flex-col">
<div class="flex flex-wrap gap-2 mb-4">
<span class="text-[10px] uppercase font-bold tracking-wider text-primary border border-primary/30 px-2 py-0.5">Regression</span>
<span class="text-[10px] uppercase font-bold tracking-wider text-primary border border-primary/30 px-2 py-0.5">Pandas</span>
</div>
<h3 class="font-headline-md text-headline-md uppercase mb-4">Graduate Admission Prediction</h3>
<ul class="text-text-muted space-y-2 mb-8 flex-1">
<li class="flex items-start gap-2"><span class="text-primary mt-1.5 w-1.5 h-1.5 rounded-full shrink-0 bg-primary"></span> Statistical modeling of university entrance metrics and success rates.</li>
<li class="flex items-start gap-2"><span class="text-primary mt-1.5 w-1.5 h-1.5 rounded-full shrink-0 bg-primary"></span> Interactive visualization dashboard for prospective graduate students.</li>
</ul>
<a class="mt-auto flex items-center gap-2 font-label-md text-label-md text-on-surface hover:text-primary transition-colors" href="#">
                            View Repository <span class="material-symbols-outlined text-sm">arrow_outward</span>
</a>
</div>
</div>
</div>
</section>
<!-- Experience & Achievements Timeline -->
<section class="py-section-gap px-gutter max-w-container-max mx-auto bg-surface-container-lowest transition-all duration-1000 opacity-100 translate-y-0" id="experience">
<div class="grid md:grid-cols-2 gap-24">
<!-- Experience -->
<div class="">
<h2 class="font-headline-lg text-headline-lg uppercase text-on-surface mb-12 flex items-center gap-4">
                        Professional Timeline <span class="h-px flex-1 bg-surface-border"></span>
</h2>
<div class="space-y-12">
<div class="relative pl-8 border-l-2 border-surface-border group">
<div class="absolute -left-1.5 top-0 w-2.5 h-2.5 bg-primary group-hover:scale-150 transition-transform"></div>
<span class="text-primary font-label-md text-label-md mb-2 block uppercase">&nbsp;2026</span>
<h3 class="font-headline-md text-headline-md text-on-surface">Machine Learning Intern</h3>
<p class="text-text-muted mb-4">Tech-Focused Startup</p>
<p class="text-body-md text-text-muted">
                                Developing and deploying automated data labeling pipelines and optimizing pre-trained transformer models for specific industry use cases. Reduced manual labeling effort by 40%.
                            </p>
</div>
<div class="relative pl-8 border-l-2 border-surface-border group opacity-60">
<div class="absolute -left-1.5 top-0 w-2.5 h-2.5 bg-surface-border group-hover:bg-primary transition-colors"></div>
<span class="text-text-muted font-label-md text-label-md mb-2 block uppercase">2023 - 2028</span>
<h3 class="font-headline-md text-headline-md text-on-surface">Dual Degree (B.Tech + M.Tech)</h3>
<p class="text-text-muted mb-4">IIT (BHU) Varanasi</p>
<p class="text-body-md text-text-muted">
                                Comprehensive curriculum focusing on Computer Science, Advanced Statistics, and Neural Computing.
                            </p>
</div>
</div>
</div>
<!-- Achievements -->
<div id="achievements">
<h2 class="font-headline-lg text-headline-lg uppercase text-on-surface mb-12 flex items-center gap-4">
                        Milestones <span class="h-px flex-1 bg-surface-border"></span>
</h2>
<div class="space-y-6">
<div class="bg-surface-elevated p-6 border border-surface-border flex items-center gap-6 hover:bg-surface-container-high transition-colors">
<div class="w-16 h-16 flex items-center justify-center bg-background border border-primary/20 shrink-0">
<span class="material-symbols-outlined text-primary text-3xl">military_tech</span>
</div>
<div>
<h4 class="font-headline-md text-body-lg text-on-surface font-bold uppercase">Competitive Programming</h4>
<p class="text-text-muted text-label-md">Ranked in top 5% on global coding platforms (Codeforces/LeetCode).</p>
</div>
</div>
<div class="bg-surface-elevated p-6 border border-surface-border flex items-center gap-6 hover:bg-surface-container-high transition-colors">
<div class="w-16 h-16 flex items-center justify-center bg-background border border-primary/20 shrink-0">
<span class="material-symbols-outlined text-primary text-3xl">workspace_premium</span>
</div>
<div>
<h4 class="font-headline-md text-body-lg text-on-surface font-bold uppercase">Academic Excellence</h4>
<p class="text-text-muted text-label-md">Secured high percentile in JEE Mains and qualified JEE Advanced to join IIT (BHU).</p>
</div>
</div>
<div class="bg-surface-elevated p-6 border border-surface-border flex items-center gap-6 hover:bg-surface-container-high transition-colors">
<div class="w-16 h-16 flex items-center justify-center bg-background border border-primary/20 shrink-0">
<span class="material-symbols-outlined text-primary text-3xl">verified</span>
</div>
<div>
<h4 class="font-headline-md text-body-lg text-on-surface font-bold uppercase">Certified ML Expert</h4>
<p class="text-text-muted text-label-md">DeepLearning.AI &amp; Stanford Specialized Certifications.</p>
</div>
</div>
</div>
</div>
</div>
</section>
<!-- CTA Section -->
<section class="py-section-gap px-gutter text-center max-w-container-max mx-auto overflow-hidden relative transition-all duration-1000 opacity-100 translate-y-0">

<div class="relative z-10 space-y-8">
<h2 class="font-display-lg text-display-lg-mobile md:text-display-lg uppercase tracking-tight">Ready to Solve <br>Complex <span class="text-primary italic">Problems?</span></h2>
<p class="text-body-lg text-text-muted max-w-xl mx-auto">I'm currently open to research opportunities and engineering roles in Machine Learning and Computer Vision.</p>
<div class="flex justify-center gap-6">
<button class="bg-primary text-background px-12 py-4 font-bold uppercase tracking-widest hover:bg-on-primary transition-all active:scale-95">Get In Touch</button>
</div>
</div>
</section>
</main>
<!-- Footer Shell -->
<footer class="w-full py-base px-gutter flex flex-col md:flex-row justify-between items-center gap-4 bg-surface-container-lowest dark:bg-surface-container-lowest border-t border-surface-border py-12">
<div class="font-headline-md text-headline-md font-black text-on-surface uppercase tracking-tighter">NPS</div>
<div class="text-text-muted font-label-md text-label-md">Nikhil Pratap Singh • IIT (BHU) Varanasi
        </div>
<div class="flex gap-6">
<a class="text-text-muted hover:text-on-surface transition-colors font-label-md text-label-md" href="#">LinkedIn</a>
<a class="text-text-muted hover:text-on-surface transition-colors font-label-md text-label-md" href="#">GitHub</a>

<a class="text-text-muted hover:text-on-surface transition-colors font-label-md text-label-md" href="mailto:techskills2027@gmail.com">techskills2027@gmail.com</a>
</div>
</footer>
<script>
        // Intersection Observer for fade-in animations
        const observerOptions = {
            threshold: 0.1
        };

        const observer = new IntersectionObserver((entries) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    entry.target.classList.add('opacity-100', 'translate-y-0');
                    entry.target.classList.remove('opacity-0', 'translate-y-8');
                }
            });
        }, observerOptions);

        document.querySelectorAll('section').forEach(section => {
            section.classList.add('transition-all', 'duration-1000', 'opacity-0', 'translate-y-8');
            observer.observe(section);
        });
    </script>






</body></html>
