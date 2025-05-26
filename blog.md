<!-- Tailwind CDN (add in <head> if needed) -->
<link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">

<!-- Horizontal card container -->
<div class="space-y-6">

  <!-- Card -->
  <a href="/blog/blog-1/" class="flex flex-col md:flex-row bg-white rounded-xl shadow-md hover:shadow-xl transition-shadow duration-300 overflow-hidden">
    <!-- Left: Image -->
    <img class="w-full md:w-64 h-48 object-cover md:h-auto" src="/assets/project_pic1.png" alt="TF Modeling Image">

    <!-- Right: Text content -->
    <div class="p-4 flex flex-col justify-between">
      <div class="mb-2 flex space-x-2 text-sm text-gray-600">
        <span class="bg-gray-200 px-2 py-1 rounded">TF</span>
        <span class="bg-gray-200 px-2 py-1 rounded">ML</span>
      </div>
      <h3 class="text-lg font-bold text-black mb-2">Modeling TF Activity from Binding Data</h3>
      <p class="text-gray-700 text-sm">
        We model transcription activity from a limited number of TF binding datasets using interpretable machine learning, uncovering combinatorial logic with SHAP values.
      </p>
      <div class="mt-4 text-sm text-gray-500 font-semibold">Gyu Kim</div>
    </div>
  </a>

  <!-- Add more <a> cards below here for additional posts -->

  <!-- Card -->
  <a href="https://medium.com/stanford-cs224w/enabling-prediction-of-rna-structure-from-sequences-by-estimating-chemical-probe-maps-with-graph-45faa6617717" class="flex flex-col md:flex-row bg-white rounded-xl shadow-md hover:shadow-xl transition-shadow duration-300 overflow-hidden">
    <!-- Left: Image -->
    <img class="w-full md:w-64 h-48 object-cover md:h-auto" src="/blog/blog1.png" alt="TF Modeling Image">

    <!-- Right: Text content -->
    <div class="p-4 flex flex-col justify-between">
      <div class="mb-2 flex space-x-2 text-sm text-gray-600">
        <span class="bg-gray-200 px-2 py-1 rounded">Graph ML</span>
        <span class="bg-gray-200 px-2 py-1 rounded">ML</span>
        <span class="bg-gray-200 px-2 py-1 rounded">RNA</span>
      </div>
      <h3 class="text-lg font-bold text-black mb-2">Predicting RNA reactivity using Graph Machine Learning</h3>
      <p class="text-gray-700 text-sm">
        We tried to predict the reactivity profiles for DMS and 2A3 from the RNA sequence using Graph Attention Network (GAT) by using Stanford Ribonanze RNA Folding dataset and RFold algorithm.
      </p>
      <div class="mt-4 text-sm text-gray-500 font-semibold">Gyu Kim, Kaya Güvendi, Daniel Lee</div>
    </div>
  </a>

</div>
