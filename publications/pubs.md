---
layout: page
title: Publications
description: Omid Bazangani's publications
---

<style>
    /* Global Styles */
   
    .article-title {
        font-size: 18px;
        font-weight: 600;
        margin: 20px 0;
        border-bottom: 1px solid #2c3e50;
        padding-bottom: px; /* Added for spacing */
    }

    .article-summary {
        margin: 10px 0 20px;
        font-size: 14px;
        line-height: 1.5;
        color: #555;
        border-left: 4px solid #2c3e50;
        padding-left: 10px;
    }

    h2 {
        margin-top: 30px; /* Added for spacing */
    }
</style>

<div class="navbar">
    <div class="navbar-inner">
        <ul class="nav">
            <li><a href="#articles">Articles</a></li>
            <li><a href="#techreports">Tech reports</a></li>
            <li><a href="#thesis">Thesis</a></li>
        </ul>
    </div>
</div>

<h2><a name="articles"></a>Articles</h2>

<h3>2021</h3>

<div class="article">
    <div class="article-title">
        ABBY: <a href="https://eprint.iacr.org/2021/1569">Automating the creation of transition-based leakage models</a>
    </div>
    <div class="article-summary">
        Summary: We introduce ABBY, an open source side-channel leakage profiling framework that targets the microarchitecture layer. Existing solutions to characterize the microarchitecture layer of a given target require extensive manual effort. The main innovation of ABBY is the training framework, which can automatically characterize the microarchitecture of a target device. To benchmark ABBY, we target an ARM
        CORTEX-MO board, for which tools that profile the microarchitecture already exist. Using ABBY, we create the ABBY-CM0 dataset, which
        covers 80% of the entire ARMv6 instruction set. ABBY-CM0 will be the first open source dataset with detailed information about the microarchitecture layer and can be used to create any number of transition-based leakage models. The main application for such leakage models is
        the creation of leakage simulators. A preliminary evaluation of a leakage model produced with the ABBY-CM0 dataset of real-world crypto implementations shows performance comparable to state-of-the-art leakage
        simulators.
    </div>
</div>

<h2><a name="thesis"></a>Thesis</h2>

<!-- Content for Thesis can be added here -->

<h2><a name="techreports"></a>Technical Reports</h2>

<!-- Content for Technical Reports can be added here -->
