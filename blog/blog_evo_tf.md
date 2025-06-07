---
layout: page
permalink: /blog/blog_evo_tf/
---

<style>
/* White card-style blog post on black background */
.medium-style-post {
  background-color: white;
  color: black;
  font-family: Georgia, "Times New Roman", serif;
  padding: 2rem;
  max-width: 900px;
  margin: 4rem auto;
  border-radius: 8px;
  box-shadow: 0 4px 10px rgba(0,0,0,0.2);
}

/* Title styled like Medium */
.medium-style-post h1 {
  font-size: 1.5rem;
  font-weight: 700;
  margin-bottom: 1.5rem;
}

/* Paragraph styling */
.medium-style-post p {
  font-size: 0.9rem;
  line-height: 1.7;
  margin-bottom: 1.25rem;
}
</style>

<div class="medium-style-post">
  <h1>Evolutionary perspective on transcription factors</h1>

  <p> Every living organism with a DNA genome needs a way to control its gene expression. Transcription factors (TFs) are the widely known main effectors of this process. How these factors have evolved around different branches of the living organisms has always been an intriguing aspect for me.  </p>
  
  <figure style="text-align: center; margin-top: 2rem;">
    <img src="/blog/image/blog_evo_tf_1.png" alt="TF Evolution" style="max-width: 30%; height: auto; border-radius: 8px; margin-top: 1rem;">
    <figcaption style="font-size: 0.9rem; color: #555; margin-top: 0.5rem;">
      Figure 1. Summary statistics of TF from Kribelbauer et al.
    </figcaption>
  </figure>
  
  <p>The numeric aspect of TFs is an interesting angle to consider. Different organisms have different numbers of TF. Based on the review article, <a href="https://www-annualreviews-org.stanford.idm.oclc.org/content/journals/10.1146/annurev-cellbio-100617-062719" target="_blank">Kribelbauer et al.</a>, while the length of DNA binding domains is similar, eukaryotic organisms tend to have more and diverse domain structures of TFs than prokaryotic organisms, which makes sense that Eukaryotic organisms tend to have larger sizes and more complicated biochemical structures of genome and regulation process. But even among eukaryotic organisms, the sizes of genomes and the number of TFs varied a lot. (Figure 1) Plants tend to have more TF per gene than animals. For example, maize has a putative ~2,500 TF (2.3Gb genome) while human has ~1,600 TF (3.3Gb genome). Arabidopsis, one of the most popular plant model organisms, is known to have 1800~2000 TF, which is comparable to the number of human TF sets, while the genome size is only 3% (0.135Gb) of the human genome. So, it’s been well taken observation that genome size and the number of TFs are not well correlated.</p>

  <p>This is not completely out-of-sense observation considering that a bigger genome doesn’t necessarily mean more information. The proportions of actively transcribed regions are usually very minor portions of the entire genome (less than 1% in humans, but it might be slightly higher in prokaryotes, considering that they don’t have introns). Also, Genomes can be bigger for different reasons, such as genome duplications, transposon activities, repeat regions, and others. For those reasons, the number of genes and the size of the genome are also not well correlated. Human has ~18000 genes with a 3.2Gb genome while C. elegans also has a similar range of genes, just with 0.1 Gb.
Then, what does this number of TF indicate? For example, in humans, is 1600 just enough number to control 20,000 genes? (~60,000 genes, including noncoding RNA and pseudogenes) or excessive or low? Are any of them dispensable? What is the order of the acquisition of TF over the evolutions? What is the most recently emerged TF? All those questions are still unanswered.</p>

  <figure style="text-align: center; margin-top: 2rem;">
    <img src="/blog/image/blog_evo_tf_2.png" alt="TF Evolution" style="max-width: 80%; height: auto; border-radius: 8px; margin-top: 1rem;">
    <figcaption style="font-size: 0.9rem; color: #555; margin-top: 0.5rem;">
      Figure 2. Differential expression of TF across different tissues. (from Lambert et al.)
    </figcaption>
  </figure>

  <figure style="text-align: center; margin-top: 2rem;">
    <img src="/blog/image/blog_evo_tf_3.png" alt="TF Evolution" style="max-width: 80%; height: auto; border-radius: 8px; margin-top: 1rem;">
    <figcaption style="font-size: 0.9rem; color: #555; margin-top: 0.5rem;">
      Figure 3. Evolutionary conservation of human TFs. (from Lambert et al.)
    </figcaption>
  </figure>
  
  <p>Another context to consider is that not all the TFs are expressed in every tissue. Based on <a href="https://pubmed.ncbi.nlm.nih.gov/29425488/" target="_blank">Lambert et al.</a>, there are differential expressions of TF across different cell types, and roughly one-third of the human TFs displayed tissue-specific expression. (Figure 2) There were some differences based on the families that homeodomain TFs tend to be more tissue-specific, and C2H2-ZF tends to be less tissue-specific. This suggests that specific TFs are involved in different gene regulation programs. However, the majority of the TF seem to be widely expressed, even though their expression levels could be variable over different tissue systems. It would be an interesting question to see if there is an association between tissue specificity and evolutionary conservation. The expected hypothesis would be less tissue specific TF (more broadly expressed TF) will likely to be more evolutionarily conserved because (1) more human tissue-specific TF means that their functions are likely to be confined in the specific biological contexts and (2) those might not have been required unless the specific organs were shown up in the tree of life. This hypothesis seems to be well backed up by the low evolutionary conservancy of C2H2-ZF with KRAB, which is highly enriched in testis organs to repress other genes. (Figure 3) However, it would be an interesting angle to identify highly tissue-specific TF that’s evolutionarily well conserved to study how the role has been changed over different organismal systems and how it became tissue-specific in humans.</p>

</div>
