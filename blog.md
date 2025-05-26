<!-- Tailwind CDN (include in your <head> if you're not using a build system) -->
<link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">

<div class="p-6 grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">

  <!-- Card 1 -->
  <a href="/blog/blog-1/" class="block bg-white rounded-xl shadow-md overflow-hidden hover:shadow-xl transition-shadow duration-300">
    <img class="h-48 w-full object-cover" src="/assets/project_pic1.png" alt="Research Topic 1">
    <div class="p-4">
      <div class="flex space-x-2 mb-2 text-sm text-gray-600">
        <span class="bg-gray-200 px-2 py-1 rounded">TF</span>
        <span class="bg-gray-200 px-2 py-1 rounded">ML</span>
      </div>
      <h3 class="text-lg font-bold text-black mb-1">Modeling TF</h3>
      <p class="text-gray-700 text-sm">
        We model transcription activity from a limited number of TF binding datasets using interpretable machine learning, uncovering combinatorial logic with SHAP values.
      </p>
      <div class="mt-4 flex items-center text-sm text-gray-500">
        <span class="font-semibold">Gyu Kim</span>
        <span class="ml-auto">2024</span>
      </div>
    </div>
  </a>

  <!-- Card 1 -->
  <a href="https://medium.com/stanford-cs224w/enabling-prediction-of-rna-structure-from-sequences-by-estimating-chemical-probe-maps-with-graph-45faa6617717" class="block bg-white rounded-xl shadow-md overflow-hidden hover:shadow-xl transition-shadow duration-300">
    <img class="h-48 w-full object-cover" src="/blog/blog1.png" alt="Research Topic 1">
    <div class="p-4">
      <div class="flex space-x-2 mb-2 text-sm text-gray-600">
        <span class="bg-gray-200 px-2 py-1 rounded">Graph ML</span>
        <span class="bg-gray-200 px-2 py-1 rounded">RNA</span>
      </div>
      <h3 class="text-lg font-bold text-black mb-1">Predicting RNA reactivity using Graph Machine Learning</h3>
      <p class="text-gray-700 text-sm">
        We tried to predict the reactivity profiles for DMS and 2A3 from the RNA sequence using Graph Attention Network (GAT) by using Stanford Ribonanze RNA Folding dataset and RFold algorithm.
      </p>
      <div class="mt-4 flex items-center text-sm text-gray-500">
        <span class="font-semibold">Gyu Kim</span>
        <span class="ml-auto">2023</span>
      </div>
    </div>
  </a>
