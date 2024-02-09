---
title: "Books That I Suggest"
date: 2024-02-09T23:26:52+03:30
draft: true
slug: "suggested-books"
---

These days every topic in science (and in any other areas) has lots of books, but we can not read all of them.
So I decided to list the books in my library (digital or physical) which I've read.

<!-- 
- Subjects' name syntax
    subject_name["and this is complete name"]
- Subjects' references syntax
    subjectName_referenceName_author("complete name / author")
 -->

```mermaid
graph LR

    gen_phy123["General Physics 1/2/3"]
    gen_phy4["General Physics 4"]
    ana_mec["Analytical Mechanics 1/2"]
    mat_phy["Mathematical Physics 1/2"]
    %% stat_phy["Statistical Physics 1/2"]
    %% elec_meg["Electromagnetism 1/2"]

    genPhy123_UnPhy_FmYg("University Physics / Freedman, Young")
    genPhy123_FuPhy_HdRk("Fundamentals of Physics / Halliday, Resnick")
    genPhy4_ElMPhy_WeSe("Elementary Modern Physics / Weidner, Sells")
    anaMec_AnaMec_Fs("Analytical Mechanics / Fowles")
    anaMec_ClDy_MnTn("Classical Dynamics / Thornton, Marion")
    matPhy_MtPhy_Af("Mathematical Methods for Physicists / Arfken")

    gen_phy123 --> genPhy123_UnPhy_FmYg
    gen_phy123 --> genPhy123_FuPhy_HdRk

    gen_phy4 --> genPhy4_ElMPhy_WeSe

    ana_mec --> anaMec_AnaMec_Fs
    ana_mec --> anaMec_ClDy_MnTn

    mat_phy --> matPhy_MtPhy_Af
```
