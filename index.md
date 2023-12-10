
---
layout: default
---
{% if site.logo %}

{% else %}

&nbsp;  
&nbsp;  
## Personal statement

<div class="dark_box">
<p class="dark_paragraph">
{% if site.application == "MSFT" %}
!INCLUDE "msft.md"
{% else %}
  {% if site.application == "AMZN" %}
!INCLUDE "amzn.md"
  {% else %}
    {% if site.application == "DPMND" %}
!INCLUDE "dpmnd.md"
    {% else %}
      {% if site.application == "AZN" %}
!INCLUDE "azn.md"
      {% else %}
        {% if site.application == "SMSNG" %}
!INCLUDE "smsng.md"
        {% else %}
          OTHER
        {% endif %}
      {% endif %}
    {% endif %}  
  {% endif %}
{% endif %}
</p>
</div>  
&nbsp;  

{% endif %}

{% if site.logo %}
{% else %}


&nbsp;  
&nbsp;  
{% endif %}
## Industry advanced product development [l](#industry-advanced-product-development)  

<div class="dark_box">

 
<p class="dark_paragraph">
I'm a tech lead and principal engineer in <a href="https://research.samsung.com/">Samsung Research</a>, driving on-device AI vision and speech applied research projects, focusing on ML-hardware aware solutions (Auto ML): frameworks and neural network models optimisation for the next generation of Samsung products; from proof-of-concepts to commercial products.
</p>

<p class="dark_paragraph">
Between 2022-2018, as a principal engineer in Arm's Machine Learning Group, I worked  with David Mansell and <a href="https://www.linkedin.com/in/ianbratt" title="Ian Bratt">Ian Bratt</a>, analysing neural networks of future use-cases, identifying the most relevant operations and data patterns, capturing key insights with data science techniques to advance real-world performance of <a href="https://www.arm.com">Arm</a>'s new software and hardware solutions.
</p>

<p class="dark_paragraph">
Between 2016-2017 I worked with <a href="https://uk.linkedin.com/in/paulshughes">Paul Hughes</a> in <a href="https://www.arm.com/">Arm</a>'s Architecture and Technology 
Group, as member of the Intelligent Machines Future System Design 
team, analysing and prototyping computer vision and ML subsystems for ADAS.
</p>

<p class="dark_paragraph">
In 2012 I joined <a href="https://www.arm.com/">Arm</a>'s Processor Division working in system architecture 
and heterogeneous computing projects with <a href="https://uk.linkedin.com/in/charles-garc%C3%ADa-tobin-0374071">Charles Garcia-Tobin</a> 
and <a href="https://www.linkedin.com/in/jason-parker-1548aa1/">Jason Parker</a>.
</p>
</div>
&nbsp;

## Academic research [l](#academic-research)
<div class="dark_box">

<!--
<p class="dark_paragraph">
I have a Ph. D. in Computer Science from <a href="https://www.udg.edu/en/?_ga=2.210128597.1782169398.1547342987-753952721.1547342987">University of Girona</a>.
</p>

<p class="dark_paragraph">
My research concerned with parallel efficient data structures for data 
visualization, geometric modelling, image-based representations and ray-tracing. 
</p>

<p class="dark_paragraph">
My work explored practical applications in a variety of areas in computer 
graphics, including real-time rendering, GPU efficient 
data-structures for geometry processing and texturing, and 
dynamic parallel data-structures for ray-tracing and general-purpose 
GPU applications.
</p>

<p class="dark_paragraph">
In 2011 I did a doctorate research internship in <a href="http://alice.loria.fr">ALICE Project-Team</a>
(<a href="https://www.inria.fr/en/centre/nancy">INRIA Nancy</a>), collaborating with <a href="http://www.antexel.com/sylefeb/research">Dr. Sylvain Lefebrve</a>.
</p>

<p class="dark_paragraph">
In 2007 I started my Phd. in Computer Graphics joining the 
<a href="http://ggg.udg.edu/">GGG research group</a>, under the supervision of <a href="http://ima.udg.edu/~dagush/">Dr. Gustavo Patow</a>.
</p>

<p class="dark_paragraph">
In 2005 I did a research internship collaborating with <a href="http://www.fsz.bme.hu/~szirmay/szirmay.html">Prof. Laszlo Szirmay-Kalos</a> at <a href="https://www.bme.hu/?language=en">Technical University of Budapest</a>
<a href="">Computer Graphics Research Group</a>.
</p>

<p class="dark_paragraph">
I was introduced in the Computer Graphics field advised 
by <a href="http://ima.udg.edu/~mateu/">Prof. Mateu Sbert</a>.
</p>
-->

<p class="dark_paragraph">
I have a Ph. D. in Computer Science from <a href="https://www.udg.edu/en/">University of Girona</a>. My research concerned with parallel efficient data structures for data visualization, geometric modeling, image-based representations and ray-tracing.
</p>

<p class="dark_paragraph">
My previous research explored practical applications in a variety of areas in computer graphics, including real-time rendering, GPU efficient data-structures for geometry processing and texturing, and dynamic parallel data-structures for ray-tracing and general-purpose GPU applications.
</p>

<p class="dark_paragraph">
I was introduced in the Computer Graphics field advised by <a href="http://ima.udg.edu/~mateu/">Prof. Mateu Sbert</a>. In 2005 I did a research internship collaborating with <a href="http://www.fsz.bme.hu/~szirmay/szirmay.html">Prof. Laszlo Szirmay-Kalos</a> at <a href="https://www.bme.hu/?language=en">Technical University of Budapest</a> <a href="http://cg.iit.bme.hu/portal/en/cg">Computer Graphics Research Group</a>. In 2007 I started my Phd. in Computer Graphics joining the <a href="http://ggg.udg.edu/">GGG research group</a>, under the supervision of <a href="http://ima.udg.edu/~dagush/">Dr. Gustavo Patow</a> with doctorate research internships with <a href="http://alice.loria.fr">ALICE Project-Team</a> (<a href="https://www.inria.fr/en/centre/nancy">INRIA Nancy</a>), collaborating with <a href="http://www.antexel.com/sylefeb/research">Dr. Sylvain Lefebrve</a>.
</p>

</div>  
&nbsp;

## Selected industry projects ordered chronologically [l](#selected-industry-projects-ordered-chronologically)

{% if site.logo %}
{% else %}
&nbsp;  
&nbsp;  
{% endif %}

### Speech Separation and Enhancement [2022-2023] [l](#predictive-models-for-kernel-selection-heuristics)

![Octocat](assets/img/npu_speech_separation.png){:width="128px"} Designed and developed efficient real-time RNN architecture models that distinguishes and separates the primary voice from other sounds. The key is to take advantage of Neural Processing Units to achieve <a href="https://news.samsung.com/us/ai-driven-sound-innovation-redefining-the-tv-audio-experience/">optimal sound enhancements in real-time</a>, providing deeper and greater details by analyzing content scene by scene and accentuating various audio elements including human voices, background music and sound effects. 

_Keywords_: Deep Neural Networks, Convolutions, RNN, Speech Processing, Speaker Source Separation, Neural Processing Units, Real-time Processing

{% if site.logo %}
{% else %}
&nbsp;  
&nbsp;  
{% endif %}


### Predictive Models for Kernel Selection Heuristics [2020-2022] [l](#predictive-models-for-kernel-selection-heuristics)

![Octocat](assets/img/gemm_kernel_heuristics.png){:width="192px"} Designed and developed innovative predictive model for CPUs & GPUs, for high-performance selection of kernels implementations of GEMM (General Matrix Multiply) and convolutions, within Machine Learning use-cases; choosing the right implementation in microseconds is crucial through fast and general heuristics.

_Keywords_: Deep Neural Networks, Convolutions, General Matrix Multiply, Classification, Regression, AutoML, Data Augmentation, Performance Analysis

{% if site.logo %}
{% else %}
&nbsp;  
&nbsp;  
{% endif %}

### Exploring new Armv9-A ML CPU ISA extensions (SME)<br>[2020-2022] [l](#exploring-new-armv9-a-ml-cpu-isa-extensions-sme)

![Octocat](assets/img/sme_extensions.png){:width="192px"} Investigated the impact of <a href="https://community.arm.com/developer/ip-products/processors/b/processors-ip-blog/posts/scalable-matrix-extension-armv9-a-architecture">SME (Scalable Matrix Extension)</a> instruction set in ML workloads and network architectures, exploiting outer product operations with a new programmer’s model and register state to support matrix operations.

_Keywords_: Matrix multiplication, Outer product, Modelling, CPU Architecture, Deep Neural Network, Performance Analysis

{% if site.logo %}
{% else %} 
{% endif %}

### Exploring Deep Neural Networks Performance [2018-2022] [l](#exploring-deep-neural-networks-performance)

![Octocat](assets/img/dnn_analysis.png){:width="128px"} Investigated deep neural networks for future use-cases, analysing them and breaking them down to distill the most relevant operations and data patterns, capturing key insights with data science techniques, to then drive new software and hardware solutions.

_Keywords_: Deep Neural Networks, Convolutions, General Matrix Multiply, Classification, Regression, LSTM, Transformers, GAN, Clustering, Ensemble Learning, AutoML, Data Augmentation, Performance Analysis

{% if site.logo %}
{% else %}
&nbsp;  
&nbsp;  
{% endif %}

### Advanced Driver-Assistance System and Computational Biology applications [2016-2017] [l](#advanced-driver-assistance-system-and-computational-biology-applications)

![Octocat](assets/img/adas_cb_subsys.png){:width="128px"} Analysed and prototyped
computer vision and ML subsystems for Advanced Driver-Assistance System and Computational Biology applications.

_Keywords_: Modelling,  Image Segmentation, Graph/Network Structures, Deep Neural Networks, Virtualization, System Architecture, Memory management, Radar, SLAM, Stereo matching, Object Detection, Performance Analysis

### Exploring new Armv8-A CPU ISA extensions (SVE) [2015-2016] [l](#exploring-new-armv8-a-cpu-isa-extensions-sve)

![Octocat](assets/img/sve_asm.png){:width="128px"} Investigated the impact of <a href="https://community.arm.com/tools/hpc/b/hpc/posts/technology-update-the-scalable-vector-extension-sve-for-the-armv8-a-architecture">SVE (Scalable Vector Extension)</a> instruction set in computer vision workloads, exploiting as much data-level parallelism as possible, with new instructions and vector lengths that scale from 128 to 2048 bits.

_Keywords_: Single Instruction, Multiple Data (SIMD)
programming model, Vector Instructions, Parallel Programming, Modelling, CPU Architecture, Computer Vision, Keypoint and Features Detection, Assembly Language, Performance Analysis

### Heterogeneous Computing and GPU Coherency [2012-2014] [l](#heterogeneous-computing-and-gpu-coherency)

![Octocat](assets/img/gpu_coh.png){:width="128px"} Modelled and prototyped low-level software, and analysed heterogeneous compute use-cases to incorporate <a href="https://community.arm.com/processors/b/blog/posts/exploring-how-cache-coherency-accelerates-heterogeneous-compute">Shared Virtual Memory (SVM)</a> support between different type of processors (CPU & GPU), enabling them to share data, as simply as passing a pointer, which massively simplify the software, and delivers more power efficient and higher performance applications than other software managed cache synchronization mechanisms.

_Keywords_: Memory Models, Cache Memory, Interconnect, Heterogeneous Computing, System Architecture, Modelling, System Programming, Simulation Waveform, FPGA prototyping

#### Note: Other experimental projects can be provided upon request.


## Honors and awards [l](#honors-and-awards)

<!--
#### 2021        Interview and career recognition [book publication date: November 2021] 
Career recognition by the board of trustees of the <a href="https://patronateps.udg.edu/">Polytechnic School Patronage</a> (<a href="https://www.udg.edu/en/">University of Girona</a>) in 25th anniversary book, by founding members, industrialists, representatives of institutions, Chamber of Commerce, delegates from different government departments and presidents and deans of professional associations from <a href="https://www.udg.edu/en/">University of Girona</a>.
<a href="https://patronateps.udg.edu/llibre-25-anys-premis-patronat/">25th Anniversary Book: Polytechnic School Patronage</a>
-->

#### 2013        Best Ph.D. Thesis Award of the School of Computer Science  
Parallel spatial data structures for interactive rendering, PhD Thesis, defended October 2012  
**<a href="http://www2.udg.edu/Portals/165/Resoluci%C3%B3%20convocat%C3%B2ria%202013.pdf">Publication September 2013</a>**  
**<a href="https://www.udg.edu/en/?_ga=2.210128597.1782169398.1547342987-753952721.1547342987">University of Girona</a>, 2013**  
  
#### 2007	Best Computer Science Project Award 2006-2007  
Generation and real-time visualization of 3D vegetation  
<a href="https://www.udg.edu/ca/study-at-the-udg">University of Girona</a>, Spain  
Patronat Award 12th Edition winner  
Supervised by <a href="http://ima.udg.edu/~dagush">Dr. Gustavo Patow</a> and <a href="http://ima.udg.edu/~mateu">Prof. Mateu Sbert</a>  


{% if site.logo %}
{% else %}
{% endif %}

## Selected publications [l](#selected-publications)

#### Parallel spatial data structures for interactive rendering
![Octocat](assets/img/phd_thesis_2012_caption.png){:width="128px"} PhD Thesis, October 2012 <a href="https://www.tdx.cat/bitstream/handle/10803/107998/tigf.pdf?sequence=8&isAllowed=y">[pdf]</a>

Best Ph.D. Thesis Award of the School of Computer Science 2013  
<a href="https://www.udg.edu/en/?_ga=2.210128597.1782169398.1547342987-753952721.1547342987">University of Girona</a>
&nbsp;
<div class="publicationabstract">
{% if site.phone_contact == "dummy_phone" %}

The focus of this study is to design and provide time- and space-efficient parallel data structures and algorithms for real-time rendering and general-purpose GPU applications. 

A large number of operations in computer graphics are concerned with the process of collecting spatial data in a computer’s memory, in such a way that the information can be subsequently recovered as quickly as possible in order to be processed and generate a screen image in real-time. In this context, it is important to retain and organize the spatial data in such a way that fast retrieval and evaluation are possible.  

This thesis introduces three specific representations of spatial data with efficient parallel random-access for interactive rendering applications. Surface and volume representations of
different topology and sparsity are handled with efficient encoding and rendering algorithms, where the key idea is to create a mapping of the input data to a virtual grid, which naturally suits for parallel graphics processing units with a Single Instruction, Multiple Data (SIMD)
programming model.  

The proposed approaches create a coarse lattice in which each cell contains a local description of surface and volume information, required for rendering such regions of the domain. This low-bandwidth localized memory access pattern is increasingly advantageous in many-core architectures, were the usage of random-access parallel data structures is crucial to provide fast rendering speed and good visual quality.

{% else %}

The focus of our study is to design and provide time- and space-efficient parallel data structures and algorithms for real-time rendering and general-purpose GPU applications. This thesis introduces three specific representations of spatial data with efficient parallel random-access for interactive rendering applications.

{% endif %}
</div>  
&nbsp;
<p>
<em>Keywords</em>: Spatial data, Dense and Sparse Data Structures, Parallel Computing, Spatial Hashing, Surface Parameterization, Subdivision Surfaces, Surface Simplification
</p>

{% if site.logo %}
{% else %}
{% endif %}


#### Interactive Applications for Sketch-Based Editable Polycube Map
![Octocat](assets/img/editablepc_tvc2013_teaser.png){:width="128px"} IEEE Transactions on Visualization and Computer Graphics, (Volume:19, Issue: 7, July 2013); Ismael Garcia, Jiazhi Xia, Ying He, Shi-Qing Xin, Gustavo Patow <a href="https://ieeexplore.ieee.org/document/6361388">[pdf]</a> 
<div class="publicationabstract">
{% if site.phone_contact == "dummy_phone" %}

In this paper we propose a sketch-based editable polycube mapping method that, given a general mesh and a simple polycube that coarsely resembles the shape of the object, plus sketched features indicating relevant correspondences between the two, provides a uniform, regular and user-controllable quads-only mesh that can be used as a basis structure for subdivision. Large scale models with complex geometry and topology can be processed efficiently with simple, intuitive operations. We show that the simple, intuitive nature of the polycube map is a substantial advantage from the point of view of the interface by demonstrating a series of applications, including kit-basing, shape morphing, painting over the parameterization domain, and GPU-friendly tessellated subdivision displacement, where the user is also able to control the number of patches in the base mesh by the construction of the base polycube.

{% else %}

In this paper we propose a sketch-based editable polycube mapping framework that, given a general mesh and a simple polycube, plus sketched features, provides a uniform user-controllable quads-only mesh that can be used as a basis structure for subdivision surfaces with displacement mapping, kit-basing, shape morphing and painting over the parameterization domain.

{% endif %}
</div>
&nbsp;  
_Keywords_: Digital Geometry Processing, Surface Parameterization, Polycube Map, GPU Subdivision Surface

#### A Runtime Cache for Interactive Procedural Modeling
![Octocat](assets/img/hash_cache_teaser.png){:width="128px"} SMI 2012: Shape Modeling International, Computer & Graphics; Tim Reiner, Sylvain Lefebvre, Lorenz Diener, Ismael Garcia, Bruno Jobard, Carsten Dachsbacher <a href="http://ggg.udg.edu/publicacions/UsersWebs/hashcache_smi2012/">[project page]</a>
 

<div class="publicationabstract">
{% if site.phone_contact == "dummy_phone" %}

We present an efficient runtime cache to accelerate the display of procedurally displaced and textured implicit surfaces, exploiting spatio-temporal coherence between consecutive frames. We cache evaluations of implicit textures covering a conceptually infinite space. Rotating objects, zooming onto surfaces, and locally deforming shapes now requires minor cache updates per frame and benefits from mostly cached values, avoiding expensive re-evaluations. A novel parallel hashing scheme supports arbitrarily large data records and allows for an automated deletion policy: new information may evict information no longer required from the cache, resulting in an efficient usage. This sets our solution apart from previous caching techniques, which do not dynamically adapt to view changes and interactive shape modifications. We provide a thorough analysis on cache behavior for different procedural noise functions to displace implicit base shapes, during typical modeling operations.  

{% else %}

We present an efficient runtime cache to accelerate the display of procedurally displaced and textured implicit surfaces, exploiting spatio-temporal coherence between consecutive frames, using a novel parallel hashing scheme supports arbitrarily large data records and allows for an automated deletion policy: new information may evict information no longer required from the cache.

{% endif %}
</div>
&nbsp;  
_Keywords_: Parallel Hashing, Runtime Cache, Interactive Shape Modeling, Implicit Surface Rendering, Procedural Textures 

#### Coherent parallel hashing
![Octocat](assets/img/cohash_2011.png){:width="128px"} ACM Transactions on Graphics  
Proceedings of SIGGRAPH Asia, Vol. 30(6), 2011, Ismael Garcia, Sylvain Lefebvre, Samuel Hornus, Anass Lasram <a href="http://ggg.udg.edu/publicacions/UsersWebs/cohash_siga2011/index.shtml">[project page]</a>

<div class="publicationabstract">
{% if site.phone_contact == "dummy_phone" %}

Recent spatial hashing schemes hash millions of keys in parallel, compacting sparse spatial data in small hash tables while still allowing for fast access from the GPU. Unfortunately, available schemes suffer from two drawbacks: Multiple runs of the construction process are often required before success, and the random nature of the hash functions decreases access performance. We introduce a new parallel hashing scheme which reaches high load factor with a very low failure rate. In addition our scheme has the unique advantage to exploit coherence in the data and the access patterns for faster performance. Compared to existing approaches, it exhibits much greater locality of memory accesses and consistent execution paths within groups of threads. This is especially well suited to Computer Graphics applications, where spatial coherence is common. In absence of coherence our scheme performs similarly to previous methods, but does not suffer from construction failures. Our scheme is based on the Robin Hood scheme modified to quickly abort queries of keys that are not in the table, and to preserve coherence. We demonstrate our scheme on a variety of data sets. We analyze construction and access performance, as well as cache and threads behavior.

{% else %}

We introduce a new parallel hashing scheme which reaches high load factor with a very low failure rate, with the unique advantage to exploit coherence in the data and the access patterns for faster performance. Compared to existing approaches, it exhibits much greater locality of memory accesses and consistent execution paths within groups of threads.

{% endif %}
</div>
&nbsp;  
_Keywords_: Spatial Data, Parallel Computing, Coherent Memory, Cache Memory, Hashing, Sparse Data


{% if site.logo %}
{% else %}
{% endif %}


#### Editable Polycube Map for GPU-based Subdivision Surfaces
![Octocat](assets/img/epcm_i3d_200w_148h.png){:width="128px"} I3D 2011: Proceedings of Symposium on Interactive 3D Graphics &amp; Games; Jiazhi Xia, Ismael Garcia, Ying He, Shi-Qing Xin, Gustavo Patow <a href="http://ggg.udg.edu/publicacions/UsersWebs/igarcia_epcm_i3d2011/index.shtml">[project page]</a>

<div class="publicationabstract">
{% if site.phone_contact == "dummy_phone" %}

In this paper we propose an editable polycube mapping method that, given an arbitrary high-resolution polygonal mesh and a simple polycube representation plus optional sketched features indicating relevant correspondences between the two, provides a uniform, regular and artist-controllable quads-only mesh with a parameterized subdivision scheme. The method introduces a global parameterization, based on a divide and conquer strategy, which allows to create polycube-maps with a much smaller number of patches, and gives the user much more control over the quality of the induced subdivision surface. All this makes it a practical method for real-time rendering on modern hardware (e.g. OGL 4.1 and D3D11 tessellation hardware). By sketching these correspondence features, processing large-scale models with complex geometry and topology is now feasible. This is crucial for obtaining watertight displaced Catmull-Clark subdivision surfaces and high-quality texturing on real-time applications.

{% else %}

We propose an editable polycube mapping method that, given an arbitrary high-resolution polygonal mesh and a simple polycube representation plus optional sketched features indicating relevant correspondences between the two, provides a uniform, regular and artist-controllable quads-only mesh with a parameterized subdivision scheme. 

{% endif %}
</div>
&nbsp;  
_Keywords_: Digital Geometry Processing, Surface Parameterization, Polycube Map, GPU Subdivision Surface

{% if site.logo %}
{% else %}
{% endif %}

#### IGT: Inverse Geometric Textures
![Octocat](assets/img/Teaser_200w_128h.png){:width="128px"} ACM Transactions on Graphics, Proceedings of SIGGRAPH Asia, Vol. 27(5), 2008; Ismael Garcia, Gustavo Patow  
<a href="http://ggg.udg.edu/publicacions/UsersWebs/igarcia_igt_siga2008/">[project page]</a>

<div class="publicationabstract">
{% if site.phone_contact == "dummy_phone" %}

Preserving details from a high resolution reference model onto lower resolution models is a complex, and sometimes daunting, task as manual intervention is required to correct texture misplacements. Inverse Geometric Textures (IGT) is a parameterization independent texturing technique that allows preservation of texture details from a high resolution reference model onto lower resolutions, generated with a given simplification method. IGT uses a parameterization defined on the reference model to generate an inversely parameterized texture that stores, for each texel, a list of all triangles that mapped onto it. This way, for any valid texture coordinate, IGT can know the point and the triangle of the detailed model that was projected, allowing application of details from the reference model onto the fragment from the low-resolution model. IGT is encoded in compact data structures and can be evaluated quickly. Furthermore, the high resolution model can have its own independent, secondary parameterization, so that no additional effort is required to directly use artist-designed content. 

{% else %}

Inverse Geometric Textures (IGT) generates an inversely parameterized texture from high resolution triangle model to store, for each texel, a list of all triangles that mapped onto it. Then, it allows to retrieve for any valid texture coordinate, the point and the triangle of the detailed model that was projected onto the fragment from the low-resolution model.

{% endif %}
</div>
&nbsp;  
_Keywords_: Appearance Preserving Simplification, Detail-Recovery, Computer Games, Texturing, Parameterizations, Level-of-Detail


#### Generation and interactive visualization of 3D vegetation
![Octocat](assets/img/nph07.png){:width="128px"} Master thesis in Computing, 2007; from the University of Girona and the UPC Barcelona Tech; advised by <a href="http://ima.udg.edu/~dagush">Dr. Gustavo Patow</a> and <a href="http://ima.udg.edu/~mateu">Prof. Mateu Sbert</a>  <a href="http://www.gametools.org/archives/publications/mastertesi_isma.pdf">[pdf]</a>

#### Multi-layered indirect texturing for tree rendering
![Octocat](assets/img/cork_close_view_polygonal_left_121_billboards_multilayer_right_200w_128h.png){:width="128px"} Eurographics Workshop on Natural Phenomena 2007; Ismael Garcia, Gustavo Patow, Laszlo Szirmay-Kalos, Mateu Sbert  
<a href="http://ggg.udg.edu/publicacions/UsersWebs/igarcia_tree_np2007/">[project page]</a>

<div class="publicationabstract">
{% if site.phone_contact == "dummy_phone" %}

This paper presents a technique to render in real time complex trees using billboard clouds as an impostor simplification for the original polygonal tree, combined with a new texture-based representation for the foliage. The technique provides several new contributions with respect to previous approaches. The new algorithm allows progressive level of detail both at the geometric and at the shader levels. It also preserves the parallax effects of the original polygonal model keeping leaf positions, orientations, and preserving the overlapping of the leaves as seen from any view point. In addition, the texture-based representation provides high-definition close views without introducing high memory requeriments. We adapted a realistic lighting model with soft shadows and a global illumination precomputation, allowing to render highly complex scenes with thousands of trees in real time. 

{% else %}

This paper presents a technique to render in real time complex trees using billboard clouds as an impostor simplification for the original polygonal tree, combined with a new texture-based representation for the foliage. The new algorithm allows progressive level of detail both at the geometric and at the shader levels, preserving the parallax effects of the original polygonal model: leaf positions, orientations as seen from any view point. 

{% endif %}
</div>
&nbsp;  
_Keywords_: Image Generation, Clustering, 3D Graphics, Realism

<!--
#### Tree rendering with billboard clouds
![Octocat](assets/img/billboardIndirectTexturing_200w_128h.png){:width="128px"} Third Hungarian Conference on Computer Graphics and Geometry, 2005; Ismael Garcia, Mateu Sbert, Laszlo Szirmay-Kalos  

<div class="publicationabstract">
{% if site.phone_contact == "dummy_phone" %}

This paper presents a method to render complex trees on high frame rates while providing accurate occlusion and parallax effects. Based on the recognition that a planar billboard is accurate if the represented polygon is in its plane, we find a billboard for each of those groups of tree leaves that lie approximately in the same plane. The tree is thus represented by a set of billboards, called billboard cloud. The billboards are built automatically by a clustering algorithm. Unlike classical billboards, the billboards of a billboard cloud are not rotated when the camera moves, thus the expected occlusion and parallax effects are provided. On the other hand, this approach allows the replacement of a large number of leaves by a single semi-transparent quadrilateral, which considerably improvesnthe rendering performance. A billboard cloud well represents the tree from any direction and provides accurate depth values, thus the method is also good for shadow, obscurances, and indirect illumination computation. In order to provide high quality results even if the observer gets close to the tree, we also propose a novel approach to encode textures representing the billboards. This approach is called indirect texturing and generates very high resolution textures on the fly while requiring just moderate amount of texture memory.

{% else %}

This paper presents a simple method to render complex trees on high frame rates while maintaining parallax effects with impostor planes generated automatically by a clustering algorithm. Unlike billboards, these impostors are not rotated when the camera moves, thus the expected parallax effects are provided.

{% endif %}
</div>
&nbsp;
-->

{% if site.logo %}
{% else %}
&nbsp;  
&nbsp;  
{% endif %}


#### Leaf cluster impostors for tree rendering with parallax
![Octocat](assets/img/billboardComparison_200w_128h.png){:width="128px"} Short Paper of Eurographics (Dublin, Ireland), pp. 69-72, 2005; Ismael Garcia, Mateu Sbert, Laszlo Szirmay-Kalos  

<div class="publicationabstract">
{% if site.phone_contact == "dummy_phone" %}

This paper presents a simple method to render complex trees on high frame rates while maintaining parallax effects. Based on the recognition that a planar impostor is accurate if the represented polygon is in its plane, we find an impostor for each of those groups of tree leaves that lie approximately in the same plane. The groups are built automatically by a clustering algorithm. Unlike billboards, these impostors are not rotated when the camera moves, thus the expected parallax effects are provided. On the other hand, clustering allows the replacement of a large number of leaves by a single semi-transparent quadrilateral, which improves rendering time considerably. Our impostors well represent the tree from any direction and provide accurate depth values, thus the method is also good for shadow computation.

{% else %}

This paper presents a simple method to render complex trees on high frame rates while maintaining parallax effects with impostor planes generated automatically by a clustering algorithm. Unlike billboards, these impostors are not rotated when the camera moves, thus the expected parallax effects are provided.

{% endif %}
</div>
&nbsp;  
_Keywords_: Image Generation, Clustering, 3D Graphics, Realism

## Technical skills [l](#tecnical-skills)

### Languages [l](#languages) 
English (Read, Write and Speak: Fluent),
Spanish (mother language),
Catalan (Read, Write and Speak: Fluent).

### Programming Languages [l](#programming-languages)
R, Python, C, C++, Objective C, OpenCL, CUDA, Aarch64 Assembly (NEON, SVE), Javascript, Latex, MatLab, GLSL, SQL, NoSQL, HTML, CSS, PHP.

### Programming frameworks, tools and APIs [l](#programming-frameworks-tools-and-apis) 

Tensorflow, Pytorch, JAX, RStudio, Mathematica, Jupyter Notebook, Caffe2, OpenCV, DirectX, OpenGL, OpenMP, Unity, Android NDK, LLVM,
AWS (EC2, EFS, S3), Google Cloud Platform, Docker, Kubernetes, Spark, Hadoop, Git, Confluence, JIRA, Sharepoint, Visual Studio, GDB, 
3ds Max, Maya, Zbrush, Blender, Photoshop, Gimp, Inkscape.

### Operating System and Firmware development [l](#operating-system-and-firmware-development)

OSX, Linux, Android, Windows, Firmware and bare-metal.

_Keywords_: parallel computing, multi-threaded design, algorithm design, numerical methods, data visualization, machine learning, computer vision, 3d graphics and game engine programming, white papers, technical papers, GPU, CPU and FPGA development

## Academic teaching [l](#academic-teaching) 

#### From 2010 to 2011	Multimedia  and computing technologies,  
Technical Computer Engineering  (University  of Girona)  
Teaching assistant  

#### From 2009 to 2010	Multimedia  and computing technologies,  
Technical Computer Engineering  (University  of Girona)  
Teaching assistant  

#### From 2008 to 2009	Information Technologies,  
Enviromental Science (University  of Girona)  
Teaching assistant  

#### From 2007 to 2008	Effective audio-visual presentations, 
Law (University of Girona)  
Teaching assistant  

#### From 2007 to 2008	Information Technologies,  
Enviromental Science (University  of Girona)  
Teaching assistant  


## Conference talks [l](#conference-talks)

#### 2021: Modelling Machine Learning networks with Scalable Matrix Extensions
Global Engineering Conference<br>
Arm internal engineering conference

#### 2019: Data-driven analytics to advance Arm ML-solutions
Global Engineering Conference<br>
Arm internal engineering conference
  
#### 2018: Improving ML solutions with Data Science
Data + Insights<br>
Arm internal Data Science Conference

#### 2011: Event Lab Talk
Parallel computing for data processing, rendering & interaction  
<a href="http://www.event-lab.org">Event Lab</a> Invited Speaker  
<a href="https://www.ub.edu/web/ub/en/?">University of Barcelona</a>
Barcelona, Spain

#### 2011:	Coherent parallel hashing
<a href="https://sa2018.siggraph.org/en/about-us/about-siggraph-asia">SIGGRAPH Asia 2011</a>  
Hong Kong, China  

#### 2011:       Editable Polycube Map for GPU-based Subdivision Surfaces
<a href="http://graphics.cs.umass.edu/i3d2011/program.php">Symposium on Interactive 3D Graphics and Games 2011</a>  
San Francisco, USA  

{% if site.logo %}
{% else %}
&nbsp;  
&nbsp;  
{% endif %}

#### 2008:	IGT: Inverse Geometric Textures
<a href="https://sa2018.siggraph.org/en/about-us/about-siggraph-asia">SIGGRAPH Asia 2011</a>  
Singapure, Singapore  

#### 2007:	Multi-layered indirect texturing for tree rendering
<a href="http://dcgi.fel.cvut.cz/cgg/egwnp07/">Eurographics Workshop on Natural Phenomena 2007</a>    
Prague, Czech Republic  

#### 2005:	Leaf cluster impostors for tree rendering with parallax
<a href="http://isg.cs.tcd.ie/eg2005/">Eurographics 2005</a>   
Dublin, Ireland  

## Supervised Bachelor Students: [l](#supervised-bachelor-students)

#### 2017    Gershom Akoli Agim
Deep Neural Networks on Arm Cortex-A CPUs: Analysis of CPU Inference on Vision workloads
<br>
MEng Electrical & Electronic Engineering Hons Project   
<a href="https://www.hw.ac.uk/">Heriot-Watt University</a>, United Kingdom

#### 2016    Jan-Peter Larsson 
3D Reconstruction using Stereo Matching Techniques on Scalable Vector Processors  
MEng Electrical Hons Project  
<a href="https://www.ed.ac.uk/home">Edinburgh University</a>, United Kingdom
 
#### 2011	Enrique Nuzete
Interactive polycubemap editor  
BEng Project, Technical Computer Engineering   
<a href="https://www.udg.edu/ca/study-at-the-udg">University of Girona</a>, Spain 

#### 2011    Tania Mendes
Modelling and visualization of skeleton-based animations  
BEng Project, Technical Computer Engineering   
<a href="https://www.udg.edu/ca/study-at-the-udg">University of Girona</a>, Spain

#### 2007    Verena Skuk
Procedural modelling and rendering of vegetation  
Student Research Project  
<a href="https://www.udg.edu/ca/study-at-the-udg">University of Girona</a>, Spain

#### 2007    Isaac Moles
Real-time rendering of large forest  
BEng Project, Technical Computer Engineering   
<a href="https://www.udg.edu/ca/study-at-the-udg">University of Girona</a>, Spain


{% if site.logo %}
{% else %}
&nbsp;   
&nbsp;  
{% endif %}


## Other professional activities [l](#other-professional-activites)

### Program Committee Member [l](#program-committee-member)	 
#### CGVCVIP  Computer  Graphics, Visualization, Computer  Vision &  Image Processing
2012
<a href="http://www.iadisportal.org/digital-library/iadis-international-conference-computer-graphics-visualization-computer-vision-and-image-processing-2012-part-of-mccsis-2012">IADIS International Conference Computer Graphics Visualization and Image Processing</a>  
Journal program committee member  

#### CEIG: 
<a href="http://ceig2015.uji.es">CEIG 2015</a>  
Conference program committee member

### Reviewer [l](#reviewer)
 
#### Siggraph Asia: 
<a href="https://sa2015.siggraph.org/en">Siggraph Asia 2015</a>  
Technical papers reviewer  
<a href="https://sa2014.siggraph.org/en">Siggraph Asia 2014</a>  
Technical papers reviewer  

#### CGI Computer Graphics International: 
<a href="https://blogs.bournemouth.ac.uk/cgi2012">CGI 2012</a>  
Technical papers reviewer  
 
#### I3D Interactive 3D Graphics and Games: 
<a href="https://i3dsymposium.github.io/2012">I3D 2012</a>  
Technical papers reviewer

#### EG Eurographics:
<a href="http://eg2013.udg.edu">EG 2013</a>    
Technical papers reviewer  

<a href="https://www.ics.forth.gr/eg2008/home.php">EG 2008</a>  
Technical papers reviewer  

#### Computer Animation and Virtual Worlds Journal: 
2014 <a href="https://onlinelibrary.wiley.com/journal/1546427x">Computer Animation and Virtual Worlds Journal</a>   
Technical papers reviewer

#### CEIG Congreso Español de Informática Gráfica:
2015 <a href="http://ceig2015.uji.es">CEIG 2015</a>  
Technical papers reviewer  
 
2009 <a href="https://dblp.org/db/conf/ceig/ceig2009.html">CEIG 2009</a>  
Technical papers reviewer  

2008 <a href="http://www.lsi.upc.edu/events/ceig">CEIG 2008</a>  
Technical papers reviewer  


### Conference Organizer [l](#conference-organizer)	
2009 <a href="http://iiia.udg.edu/EGSR2009/">Eurographics Symposium on Rendering, EGSR</a>  
Girona, Spain  
Local organizer  

### Industry research collaborations [l](#industry-research-collaboration)	
2010 GPU Mesh Processing tools  
NVIDIA Mutual Non-Disclosure Agreement 

## Education and training [l](#education-and-training) 

#### 2007 – 2012	Ph.D. in Computer  Science
Dissertation: Parallel spatial data structures for interactive rendering  
BR PhD Fellowship from the <a href="https://www.udg.edu/ca/study-at-the-udg">University of Girona</a>

#### 2006 – 2007	Master in computing
From the <a href="https://www.udg.edu/ca/study-at-the-udg">University of Girona</a>, and the <a href="https://www.upc.edu/en?set_language=en">UPC Barcelona Tech</a>  

{% if site.logo %}
{% else %}
&nbsp;  
&nbsp;  
{% endif %}

#### 2003 – 2006	Computer Engineering
<a href="https://www.udg.edu/ca/study-at-the-udg">University of Girona</a>, Spain  

#### 1999 – 2003	Technical Computer Engineering 
<a href="https://www.udg.edu/ca/study-at-the-udg">University of Girona</a>, Spain  


## Academic experience

#### From June 2011 to December 2013	Advances in virtual reality for cutting edge applications
<a href="http://ima.udg.edu/~sellares/Tin2010/Tin2010.htm">Spanish Ministry of Science and Technology Project (TIN2010-20590-C02-02)</a>  
Research developer  
 
#### From November 2007 to July 2010	CALBaD: Computer Aided Light Based Design  
<a href="http://www.ia.urjc.es/jspTIN2010/informesPDF/TIN2007-67120.pdf">Spanish Ministry of Science and Technology Project (TIN2007-67120)</a>  
Research developer  

#### From October 2009 to December 2009	Research intership - INRIA Nancy (France), Alice project-team
Phd thesis research intership under supervision of Dr.Sylvain Lefebvre  
Mobility grant TME2008-00961 from <a href="http://alice.loria.fr/">Alice project-team</a>  
<a href="https://www.inria.fr/en/centre/nancy">INRIA Nancy</a> France  
Reserch developer  

#### From May 2007 to May 2011	PhD research fellowship BR
<a href="https://www.udg.edu/ca/study-at-the-udg">University of Girona</a>  
Research PhD student    

{% if site.logo %}
{% else %}
&nbsp;  
&nbsp;  
{% endif %}

#### From September 2004 to April 2007	Gametools Project
<a href="http://ima.udg.edu/~sellares/Tin2010/Tin2010.htm">European Union Project (IST-2-004363)</a>  
Research developer  

{% if site.logo %}
{% else %}
&nbsp;  
&nbsp;  
{% endif %}

#### From February 2010 to April 2010	Research intership - INRIA Nancy (France), Alice project-team
Phd thesis research intership under supervision of <a href="http://www.antexel.com/sylefeb/research">Dr.Sylvain Lefebvre</a>, INRIA contract <a href="http://alice.loria.fr/">Alice project-team</a>  
<a href="https://www.inria.fr/en/centre/nancy">INRIA Nancy</a>, France
Research developer

#### From February 2005 to May 2005	Research undergraduate intership
Undergraduate final project under supervision of <a href="http://www.fsz.bme.hu/~szirmay/szirmay.html">Prof.László Szirmay-Kalos</a>
<a href="https://www.bme.hu/?language=en">Technical University of Budapest</a>  
Erasmus programme grant  
Research developer  

<!--
## Conferences attendance

#### 2017 Implementing Machine Vision with FPGA and SoC platforms Conference
https://nmi.org.uk/event/fpga-network-implementing-machine-vision-with-fpga-and-soc-platforms/

#### 2018 Arm Research Summit
https://www.arm.com/company/events/research-summit

#### 2013 Global Engineering Conference
Arms global engineering conference

#### International Workshop on OpenCL, 
IWOCL 2013 https://www.iwocl.org/2013-presentations/
IWOCL 2014 https://www.iwocl.org/iwocl-2014/agenda-and-slides/
-->

## Previous experience

#### From June 2003 to March 2006	El Baúl S.A. – Grupo editorial el baúl
Redesign and implementation of online classified advertisement and community website. 
<a href="http://www.elbaul.com">elbaul.com</a>  
Web developer

#### From July 2002 to December 2002	Institut d’Informàtica i Aplicacions, Universitat  de Girona
Review and performance analysis of of the Sony’s Playstation 2 Linux Development Kit.
Project number TIC2001-2416-C03-01, financed by the Spanish Ministery of Science and Technology
<a href="http://gplsi.dlsi.ua.es/congresos/mcyt03/pdf/tic/TIC2001-2416-C03.pdf">[pdf]</a>  
Software developer  

#### From June 2000 to September 2000	Igm Web S.L.
Design and implementation of several corporative websites.  
<a href="http://www.igmweb.com/indexcat.html">Igm Web S.L.</a>  
Web developer

#### From June 1999 to September 1999	Kripton Networks
Writing technical reviews of videogames as a freelance web journalist.
<a href="http://www.iespana.es/">Iespana/Informatica</a>  
Web technical writer

