---
layout: page
title: Tutorials
description: Omid's tutorials
---

<style>
.tutorial-section {
    margin-bottom: 40px;
    border-bottom: 1px solid #e0e0e0;
    padding-bottom: 20px;
}

.tutorial-title {
    font-size: 20px;
    color: #2c3e50;
    margin-bottom: 15px;
}

.tutorial-link {
    display: block;
    margin-bottom: 10px;
    color: #3498db;
    text-decoration: none;
    transition: color 0.3s ease;
}

.tutorial-link:hover {
    color: #2980b9;
}

.tutorial-link::before {
    content: '🔗 ';
    display: inline-block;
    margin-right: 5px;
}

.pdf-link::before {
    content: '📄 ';
}

.notebook-link::before {
    content: '📓 ';
}

</style>

<div class="tutorial-section">
    <h2 class="tutorial-title">Test Vector Leakage Assessment(TVLA)</h2>
    <a class="tutorial-link pdf-link" href="{{ BASE_PATH }}/PDFDocs/TVLA_Tutorial.pdf">Instruction in PDF</a>
    <a class="tutorial-link notebook-link" href="https://github.com/omidbazangani/Teaching_Content/blob/main/PhysicalAttack_2023/TinyAES_TVLA-Student.ipynb">Companion Jupyter Notebook</a>
    <a class="tutorial-link notebook-link" href="https://github.com/omidbazangani/Teaching_Content/blob/main/PhysicalAttack_2023/TinyAES_TVLA_Teacher.ipynb">Solution Jupyter Notebook</a>
</div>

<div class="tutorial-section">
    <h2 class="tutorial-title">Fault Injection (FI) Attack</h2>
    <a class="tutorial-link pdf-link" href="{{ BASE_PATH }}/PDFDocs/FI_Toturial.pdf">Instruction in PDF</a>
    <a class="tutorial-link notebook-link" href="https://github.com/omidbazangani/Teaching_Content/blob/main/PhysicalAttack_2023/FI_Tutorial_ClockGlitch_Student.ipynb">Companion Jupyter Notebook</a>
    <a class="tutorial-link notebook-link" href="https://github.com/omidbazangani/Teaching_Content/blob/main/PhysicalAttack_2023/FI_Tutorial_ClockGlitch_Teacher.ipynb">Solution Jupyter Notebook</a>
</div>

