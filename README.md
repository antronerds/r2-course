# R2 Courses

This contains courses for the molecular biology data analysis platform R2 (r2-platform.com r2.amc.nl)

We have to think about the structure of the course currently given at the Academic Medical Center from the University of Amsterdam; course title does not cover the topics: Molecular Genetics; while it only studies the pathways in CRC and the MES/NE switch in Neuroblastoma (it is part of the Biomedical Sciences Bachelor). A preliminary search (bioinformatics of oncology) reveals that we’re probably stretching a bit; most courses found are for phd/researchers. However, these and also more basic courses cover a broader range of topics. So try to set this up as a simpler (more click through) research project (including the research cycle) leading to a research conclusion; several endpoints that can be presented...

### Steps to change this
* Check other sources; ongoing
* Study the actual book
* Define learning goals
* Search examples from literature that used R2 for publication

### Other ideas
* follow several articles that were published using R2
* Use a Docker inspired environment; so including working links directly showing the actual example in R2
* Further elaborate upon the current setup; wider range of topics, less deep but still on an example basis
* Use Kris’s tips
* Integrate this into RTD format; linked to an R2 datascope; already setup using form variables (a la Docker)


As an aid I pasted the detailed table of contents of the book here. This actually follows a pretty decent logical flow.
We can use this as an aid to formulate several microworkflows that lead the students through an analysis workflow

### TOC: Weinberg: The biology of cancer
Chapter 1 The Biology and Genetics of Cells and Organisms
* 1.1 Mendel establishes the basic rules of genetics
* 1.2 Mendelian genetics helps to explain Darwinian evolution
* 1.3 Mendelian genetics governs how both genes and chromosomes behave
* 1.4 Chromosomes are altered in most types of cancer cells
* 1.5 Mutations causing cancer occur in both the germ-line and the soma
* 1.6 Genotype embodied in DNA sequences creates phenotype through proteins
* 1.7 Gene expression patterns also control phenotype
* 1.8 Histone modifications and Transcription factors control gene expression
* 1.9 Metazoa are formed from components conserved over vast evolutionary time periods
* 1.10 Gene cloning techniques revolutionized the study of normal and malignant cells
* Chapter 2 The Nature of Cancer
* 2.1 Tumors are complex tissues
* 2.2 Tumors arise from many specialized cell types throughout the body
* 2.3 Some types of tumors do not fit into the major classifications
* 2.4 Cancers seem to develop progressively
* 2.5 Tumors are monoclonal growths
* 2.6 Cancers occur with vastly different frequencies in different human populations
* 2.7 The risks of cancers often seem to be increased by assignable influences including lifestyle
* 2.8 Specific chemical agents can induce cancer
* 2.9 Both physical and chemical carcinogens act as mutagens
* 2.10 Mutagens may be responsible for some human cancers
* 2.11 Synopsis and prospects
* Essential Concepts
* Additional Reading
* Chapter 3 Tumor viruses
* 3.1 Peyton Rous discovers a chicken sarcoma virus
* 3.2 Rous sarcoma virus is discovered to transform infected cells in culture
* 3.3 The continued presence of RSV is needed to maintain transformation
* 3.4 Viruses containing DNA molecules are also able to induce cancer
* 3.5 Tumor viruses induce multiple changes in cell phenotype including acquisition of tumorigenicity
* 3.6 Tumor virus genomes persist in virus-transformed cells by becoming part of host cell DNA 
* 3.7 Retroviral genomes become integrated into the chromosomes of infected cells
* 3.8 A version of the src gene carried by RSV is also present in uninfected cells
* 3.9 RSV exploits a kidnapped cellular gene to transform cells
* 3.10 The vertebrate genome carries a large group of proto-oncogenes
* 3.11 Slowly transforming retroviruses activate proto-oncogenes by inserting their genomes adjacent to these cellular genes
* 3.12 Some retroviruses naturally carry oncogenes
*  3.13 Synopsis and prospects
* Essential Concepts
* Additional Reading
* Chapter 4 Cellular oncogenes
* 4.1 Can cancers be triggered by the activation of endogenous retroviruses?
* 4.2 Transfection of DNA provides a strategy for detecting nonviral oncogenes
* 4.3 Oncogenes discovered in human tumor cell lines are related to those carried by transforming retroviruses
* 4.4 Proto-oncogenes can be activated by genetic changes affecting either protein expression or structure
* 4.5 Variations on a theme: the myc oncogene can arise via at least three additional distinct mechanisms
* 4.6 A diverse array of structural changes in proteins can also lead to oncogene activation
* 4.7 Synopsis and prospects
* Essential Concepts
* Additional Reading
* Chapter 5 Growth factors and their receptors
* 5.1 Normal metazoan cells control each other's lives
* 5.2 The Src protein functions as a tyrosine kinase
* 5.3 The EGF receptor functions as a tyrosine kinase
* 5.4 An altered growth factor receptor can function as an oncoprotein
* 5.5 A growth factor gene can become an oncogene: the case of sis
* 5.6. Transphosphorylation underlies the operations of receptor tyrosine kinases
* 5.7 Yet other types of receptors enable mammalian cells to communicate with their environment
* 5.8 Integrin receptors sense association between the cell and the extracellular matrix
* 5.9 The Ras protein, an apparent component of the downstream signaling cascade, functions as a G protein 
* 5.10 Synopsis and Prospects
* Essential Concepts
* Additional Reading
* Chapter 6 Cytoplasmic Signaling Circuitry Programs Many of the Traits of Cancer
* 6.1 A signaling pathway reaches from the cell surface into the nucleus
* 6.2 The Ras protein stands in the middle of a complex signaling cascade
* 6.3 Tyrosine phosphorylation controls the location and thereby the actions of many cytoplasmic signaling proteins
* 6.4 SH2 groups explain how growth factor receptors activate Ras and acquire signaling specificity
* 6.5 A cascade of kinases forms one of three important signaling pathways downstream of Ras 
* 6.6 A second pathway downstream of Ras controls inositol lipids and the Akt/PKB kinase
* 6.7 A third Ras-regulated pathway acts through the Ral, a distant cousin of Ras 
* 6.8 The Jak-STAT pathway allows signals to be transmitted from the plasma membrane directly to the nucleus
* 6.9 Cell adhesion receptors emit signals that converge with those released by growth factor receptors
* 6.10 The Wnt-_-catenin pathway contributes to cell proliferation
* 6.11 G-protein coupled receptors can also drive normal and neoplastic proliferation
* 6.12 Four other signaling pathways contribute in different fashions to normal and neoplastic proliferation
* 6.13 Synopsis and prospects
* Essential Concepts
* Additional reading
* Chapter 7 Tumor suppressor genes
* 7.1 Cell fusion experiments indicate that the cancer phenotype is recessive
* 7.2 The recessive nature of the cancer cell phenotype requires a genetic explanation 
* 7.3 The retinoblastoma tumor provides a solution to the genetic puzzle of tumor suppressor genes
* 7.4 Incipient cancer cells invent ways to eliminate wild-type copies of tumor suppressor genes
* 7.5 The Rb gene often undergoes loss-of-heterozygosity 
* 7.6 Loss-of-heterozygosity events can be used to find tumor suppressor genes
* 7.7 Many familial cancers can be explained by inheritance of mutant tumor suppressor genes
* 7. 8 Promoter methylation represents an important mechanism for inactivating tumor suppressor genes
* 7.9 Tumor suppressor genes and proteins function in diverse ways
* 7.10 The NF1 protein acts as a negative regulator of Ras signaling
* 7.11 Apc facilitates egress of cells from colonic crypts
* 7.12 Von Hippel-Lindau disease: pVHL modulates the hypoxic response
* 7.13 Synopsis and Prospects
* Essential Concepts
* Additional reading
* Chapter 8 pRb and Control of the Cell Cycle Clock
* 8.1 External signals influence a cell's decision to enter into the active cell cycle
* 8.2 Cells make decisions about growth and quiescence during a specific period in the G1 phase
* 8.3 Cyclins and cyclin-dependent kinases constitute the core components of the cell cycle clock
* 8.4 Cyclin-Cdk complexes are also regulated by Cdk inhibitors
* 8.5 Viral oncoproteins reveal how pRb controls the transition through the cell cycle 
* 8.6 pRb is deployed by the cell cycle clock to serve as a guardian of the restriction point gate
* 8.7 E2F transcription factors enable pRb to implement growth-versus-quiescence decisions
* 8.8 A variety of mitogenic signaling pathways control the phosphorylation state of pRb
* 8.9 The Myc oncoprotein perturbs the decision to phosphorylate pRb and thereby deregulates control of cell cycle progression
* 8.10 TGF-_ prevents phosphorylation of pRb and thereby blocks cell cycle progression
* 8.11 pRb function and the process of differentiation are closely linked
* 8.12 Control of pRb function is perturbed in most if not all human cancers
* 8.13 Synopsis and Prospects
* Essential Concepts
* Additional reading
* Chapter 9 p53 and Apoptosis: Master Guardian and Executioner
* 9.1 Papovaviruses lead to the discovery of p53
* 9.2 p53 is discovered to be a tumor suppressor gene
* 9.3 Mutant versions of p53 interfere with normal p53 function
* 9.4 p53 protein molecules usually have short lifetimes
* 9.5 A variety of signals cause p53 induction
* 9.6 DNA damage and deregulated growth signals cause p53 stabilization
* 9.7 Mdm2 and ARF battle over the fate of p53
* 9.8 ARF and p53-mediated apoptosis protect against cancer by monitoring intracellular signaling
* 9.9 p53 functions as a transcription factor that halts cell cycle advance in response to DNA damage and attempts to aid in the repair process 
* 9.10 p53 often ushers in the apoptotic death program
* 9.11 p53 inactivation provides advantage to incipient cancer cells at a number of steps in tumor progression
* 9.12 Inherited mutant alleles of p53 predispose one to a variety of tumors
* 9.13 Apoptosis is a complex program that often depends on mitochondria
* 9.14 Two distinct signaling channels can trigger apoptosis
* 9.15 Cancer cells invent numerous ways to inactivate some or all of the apoptotic machinery
* 9.16 Synopsis and Prospects
* Essential Concepts
* Additional reading
* Chapter 10 Eternal Life: Cell Immortalization and Tumorigenesis
* 10.1 Normal cell populations register the number of cell generations separating them from their ancestors in the early embryo
* 10.2 Cancer cells need to become immortal in order to form tumors
* 10.3 Cell-physiologic stresses impose a limitation on replication
* 10.4 The proliferation of cultured cells is also limited by the telomeres of their chromosomes
* 10.5 Telomeres are complex molecular structures that are not easily replicated
* 10.6 Incipient cancer cells can escape crisis by expressing telomerase
* 10.7 Telomerase plays a key role in the proliferation of human cancer cells
* 10.8 Some immortalized cells can maintain telomeres without telomerase
* 10.9 Telomeres play different roles in the cells of laboratory mice and in human cells
* 10.10 Telomerase-negative mice show both decreased and increased cancer susceptibility
* 10.11 The mechanisms underlying cancer pathogenesis in telomerase-negative mice may also operate during the development of human tumors
* 10.12 Synopsis and Prospects
* Essential Concepts
* Additional reading
* Chapter 11 Multistep tumorigenesis
* 11.1 Most human cancers develop over many decades of time
* 11.2 Histopathology provides evidence of multi-step tumor formation
* 11.3 Colonic growths accumulate genetic alterations as tumor progression proceeds
* 11.4 Multi-step tumor progression helps to explain familial polyposis
* 11.5 Cancer development seems to follow the rules of Darwinian evolution
* 11.6 Tumor stem cells further complicate the Darwinian model of clonal succession and tumor progression
* 11.7 A linear path of clonal succession oversimplifies the reality of cancer
* 11.8 The Darwinian model of tumor development is difficult to validate experimentally
* 11.9 Multiple lines of evidence reveal that normal cells are resistant to transformation by a single mutated gene
* 11.10 Transformation usually requires collaboration between two or more mutant genes
* 11.11 Transgenic mice provide models of oncogene collaboration and multi-step cell transformation
* 11.12 Human cells are constructed to be highly resistant to immortalization and transformation
* 11.13 Nonmutagenic agents, including those favoring cell proliferation, make important contributions to tumorigenesis
* 11.14 Toxic and mitogenic agents can act as human tumor promoters
* 11.15 Chronic inflammation often serves to promote tumor progression in mice and humans
* 11.16 Inflammation hyphen dependent tumor promotion operates through defined signaling pathways
* 11.17 Tumor promotion is likely to be a critical determinant of the rate of tumor progression in many humans tissues
* 11.18 Synopsis and Prospects
* Essential Concepts
* Additional Reading
* Chapter 12 Maintenance of Genomic Integrity and the Development of Cancer
* 12.1 Tissues are organized to minimize the progressive accumulation of mutations
* 12.2 Stem cells are the likely targets of the mutagenesis that leads to cancer
* 12.3 Various strategies offer tissues a way to minimize the accumulation of mutant stem cells
* 12.4 Cell genomes are threatened by errors made during DNA replication 
* 12.5 Cell genomes are under constant attack from endogenous biochemical processes
* 12.6 Cell genomes are under occasional attack from exogenous mutagens and their metabolites 
* 12.7 Cells deploy a variety of defenses to protect DNA molecules from attack by mutagens
* 12.8 Repair enzymes fix DNA that has been altered by mutagens
* 12.9 Inherited defects in nucleotide excision repair, base excision repair, and mismatch repair lead to specific cancer susceptibility syndromes
* 12.10 A variety of other DNA repair defects confer increased cancer susceptibility through poorly understood mechanisms
* 12.11 The karyotype of cancer cells is often changed through alterations in chromosome structure
* 12.12 The karyotype of cancer cells is often changed through alterations in chromosome number
* 12.13 Synopsis and Prospects
* Additional reading
* Chapter 13 Dialogue replaces Monologue: Heterotypic Interactions and the Biology of Angiogenesis
* 13.1 Normal and neoplastic epithelial tissues are formed from interdependent cell types
* 13.2 The cells forming cancer cell lines develop without heterotypic interactions and deviate from the behavior of cells within human tumors
* 13.3 Tumors resemble wounded tissues that do not heal
* 13.4 Stromal cells are active contributors to tumorigenesis
* 13.5 Macrophages represent important participants in activating the tumor-associated stroma
* 13.6 Endothelial cells and the vessels that they form ensure tumors adequate access to the circulation
* 13.7 Tripping the angiogenic switch is essential for tumor expansion
* 13.8 The angiogenic switch initiates a highly complex process
* 13.9 Angiogenesis is normally suppressed by physiologic inhibitors
* 13.10 Certain anti-angiogenesis therapies hold great promise for treating cancer
* 13.11 Synopsis and Prospects
* Essential Concepts
* Additional Reading
* Chapter 14 Moving Out: Invasion and Metastasis
* 14.1 Travel of cancer cells from a primary tumor to a site of potential metastasis depends on a series of complex biological steps
* 14.2 Colonization represents the most complex and challenging step of the invasion-metastasis cascade
* 14.3 The epithelial-mesenchymal transition and associated loss of E-cadherin expression enables carcinoma cells to become invasive
* 14.4 The epithelial-mesenchymal transition is often induced by stromal signals
* 14.5 EMTs are programmed by transcription factors that orchestrate key steps of embryogenesis
* 14.6 Extracellular proteases play key roles in invasiveness
* 14.7 Small Ras-like GTPases control cellular processes including adhesion, cell shape and cell motility
* 14.8 Metastasizing cells can use lymphatic vessels to disperse from the primary tumor
* 14.9 A variety of factors govern the organ sites in which disseminated cancer cells form metastases
* 14.10 Metastasis to bone requires the subversion of osteoblasts and osteoclasts
* 14.11 Metastasis suppressor genes contribute to regulating the metastatic phenotype
* 14.12 Occult micrometastases represent a threat to the long-term survival of cancer patients
* 14.13 Synopsis and Prospects
* Essential Concepts
* Additional reading
* Chapter 15 Crowd Control: Tumor Immunology and Immunotherapy
* 15.1 The immune system functions in complex ways to destroy foreign invaders and abnormal cells in the body's tissues
* 15.2 The adaptive immune response leads to antibody production
* 15.3 Another adaptive immune response leads to the formation of cytotoxic cells
* 15.4 The innate immune response does not require prior sensitization
* 15.5 The need to distinguish self from non-self results in immune tolerance
* 15.6 Regulatory T cells are able to suppress major components of the adaptive immune response
* 15.7 The immunosurveillance theory is born and then suffers major setbacks
* 15.8 Use of genetically altered mice leads to a resurrection of the immunosurveillance theory
* 15.9 The human immune system plays a critical role in warding off various types of human cancer
* 15.10 Subtle differences between normal and neoplastic tissues may allow the immune system to distinguish between them
* 15.11 Immune recognition of tumors may be delayed until relatively late in tumor progression
* 15.12 Tumor-specific transplantation antigens often provoke a potent immune response
* 15.13 Tumor-associated transplantation antigens may also evoke anti-tumor immunity
* 15.14 Cancer cells can evade immune detection by suppressing cell-surface display of tumor antigens
* 15.15 Cancer cells protect themselves from NK-mediated attack
* 15.16 Tumor cells launch counterattacks on immunocytes
* 15.17 Cancer cells become intrinsically resistant to various forms of killing used by the immune system
* 15.18 Cancer cells attract regulatory T cells to fend off attacks by other lymphocytes
* 15.19 Passive immunization with Herceptin can be used to kill breast cancer cells
* 15.20 Passive immunization with antibody can be used to treat B-cell tumors
* 15.21 Passive immunization can be achieved by transfer of immunocytes from one individual to another
* 15.22 Patients' immune systems can be mobilized to attack their tumors
* 15.23 Synopsis and prospects
* Essential Concepts
* Additional reading
* Chapter 16 The Rational Treatment of Cancer
*  16.1 The development and clinical use of effective therapies will depend on accurate diagnosis of disease 
* 16.2 Successful anti-cancer drugs can elicit several responses from tumor cells
* 16.3 Functional considerations dictate that only a subset of the defective proteins in cancer cells are attractive targets for drug development
* 16.4 The biochemistry of proteins also determines whether they are attractive targets for intervention
* 16.5 Pharmaceutical chemists can generate and explore the biochemical properties of a wide array of potential drugs
* 16.6 Drug candidates must be tested on cell models as an initial measurement of their utility in whole organisms
* 16.7 Studies of a drug's action in laboratory animals are an essential part of preclinical testing
* 16.8 Promising candidate drugs must be subjected to rigorous and extensive clinical trials in Phase I trials in humans
* 16.9 Phase II and III trials provide credible indications of clinical efficacy
* 16.10 Tumors often develop resistance to initially effective therapy
* 16.11 Gleevec development has paved the way for the development of many other highly targeted compounds
* 16.12 EGF receptor antagonists may be useful for treating a wide variety of tumor types
* 16.13 Proteasome inhibitors yield unexpected therapeutic benefit
* 16.14 A sheep teratogen may be useful as a highly potent anti-cancer drug
* 16.15 mTOR, a master regulator of cell physiology, represents an attractive target for anticancer therapy
* 16.16 Synopsis and Prospects: Challenges and opportunities on the road ahead

###About the workings of Read the docs and github contents

The setup of the documention in Github is according to the Cytoscape manual as done by Barry Demcak
It has tags identifying the material that goes into the user manual for each version. A tag is formatted according to semantic versioning rules (e.g., 1.1).

The outstanding issues are identified as GitHub Issues. 

While the course sources are maintained in GitHub, the document is actually assembled, formatted, and staged by the ReadTheDocs.org site. ReadTheDocs presents online and PDF versions, and we will use both.

ReadTheDocs can present versions of the tutorials for each release, as identified by GitHub tags. For example, given a tag of 1.1, ReadTheDocs will produce a document containing the repository files as they were for R2-tutorials 1.1, and will make it available at http://r2-course.readthedocs.io/en/1.1/ ReadTheDocs will make a "stable" version of the manual available at http://r2-course.readthedocs.io/en/stable ... it will resolve to the latest tagged version (ignoring beta versions such as 3.4b1). The "latest" version of the manual will be available at http://r2-course.readthedocs.io/en/latest, and will contain all of the latest GitHub content, irrespective of tagging.

Note that for a manual under developement, we should make "latest" non-public (configurable in ReadTheDocs) so it isn't indexed by Google.

## Editing the Manual

The manual is in Markdown format; more about this readable markup format at these urls:

*  [Github related](https://help.github.com/articles/basic-writing-and-formatting-syntax/)
*  [Extensive list](https://daringfireball.net/projects/markdown/syntax)

There is a [standard template](/docs/_templates/R2_Chapter_Template.md) in the _template directory 

To edit manual text, you must first check out this repository and use a text editor on your workstation. (You can use GitHub's native Markdown editor directly, too, for small edits.) 
Another option is use the online wysiwyg editor http://dillinger.io/ It has an underwater screen and shows direct output of your actions. You'll have to create an access token though: https://github.com/joemccann/dillinger/blob/master/plugins/github/README.md

All document components are in the "docs" directory. Each chapter is contained in its own file, and the files are assembled as a complete document by naming them in the "docs/index.rst" file.

Images are stored in the "docs/_static/images" directory, organized into subdirectories by chapter.

Simple tables can be represented in Markdown, but high quality formatting requires direct HTML coding. By convention, we encode tables as HTML-tagged data, but do not specify visual attributes and layout inline. Instead, we use preset table styles contained in "docs/_static/css" for formatting -- we do not use Markdown's table formatting. Note that additional CSS files can be added, but must be accounted for in "conf.py". Note that while the tables appear in the HTML document, they do not appear in the PDF version -- we're working on this.

More documentation here: http://www.sphinx-doc.org/en/stable/templating.html#configuration-variables
And here: http://stackoverflow.com/questions/32079200/how-do-i-set-up-custom-styles-for-restructuredtext-sphinx-readthedocs-etc/32079202#32079202

Note that the GitHub file viewer displays Markdown files reasonably well. However, it only approximates the look of tables created via HTML. For an accurate view of a table, you must look at a document rendered by ReadTheDocs.

Note that a full (browsable) link to a location has the form: "http://r2-course.readthedocs.io/en/stable/Introduction.html#mylink" where "http://r2-course.readthedocs.io/en/stable/" is the full URL, "Introduction" is the root name of the file containing the target link, and "mylink" is a named section (e.g., <a name="mylink">System requirements</a>). A link between chapters in the document has the form [My Link](Introduction.html#mylink), and a link within the same chapter can have the form [My Link](#mylink). For intra-document references, best to use the Introduction.html#mylink form, as ReadTheDocs will append the full URL appropriate for the build (e.g., "stable", "latest", "3.3", etc).

## Rebuilding the Course materials
The "latest" course materials are automatically rebuilt by ReadTheDocs when the GitHub repository is updated. To rebuild other versions, you'll need to be in the ReadTheDocs web site on the Build page.

The rebuild can be observed by logging into the ReadTheDocs account (see devnotes google doc for credentials) and choosing the "r2-course" project. To see the build log, click on the grey Builds button. You can watch the progress of the build by manually refreshing your browser window until the build status shows either Passed or Failed - a build can take anywhere from 3 minutes to 10 minutes, depending on how busy the build server is. When the build is complete, if the status shows Passed, you can view the build result by clicking on the green View Docs button. Note that for the fresh pdf you might have to reload your page. 

Note that the "stable" version of the manual is the build for the most recent release tag (e.g., "3.3") according to semantic versioning rules. This is the version that should be reference from the R2 web site. Note, too, that for testing, we can set a tag (e.g., "3.4.0") and have ReadTheDocs build from the tagged GitHub files. It will be available at http://r2-course.readthedocs.io//3.4.0 ... and as we refine the document, we can use GitHub to move the tag to the appropriate latest checkin. This is useful for testing with a candidate 3.4.0 that will eventually stop being re-tagged.

