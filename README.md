# UseGalaxy.eu Workflow Testing

Based off of [jmchilton's template](https://github.com/jmchilton/planemo-workflow-test-template), except running tests against UseGalaxy.eu

## Testing

We are [automatically running](https://build.galaxyproject.eu/job/usegalaxy-eu/job/workflow-testing/) these workflows weekly against UseGalaxy.eu

Workflow                                                                                     | Status
---                                                                                          | ---
example1/wf3-shed-tools.ga                                                                   | [![Build Status](https://build.galaxyproject.eu/job/usegalaxy-eu/job/workflow-testing/PYTHON=System-CPython-2.7,WORKFLOW=example1%2Fwf3-shed-tools.ga/badge/icon                                                                       )](https://build.galaxyproject.eu/job/usegalaxy-eu/job/workflow-testing/PYTHON=System-CPython-2.7,WORKFLOW=example1%2Fwf3-shed-tools.ga/)
example2/wf4-shed-tools.ga                                                                   | [![Build Status](https://build.galaxyproject.eu/job/usegalaxy-eu/job/workflow-testing/PYTHON=System-CPython-2.7,WORKFLOW=example2%2Fwf4-shed-tools.ga/badge/icon                                                                       )](https://build.galaxyproject.eu/job/usegalaxy-eu/job/workflow-testing/PYTHON=System-CPython-2.7,WORKFLOW=example2%2Fwf4-shed-tools.ga/)
HiCExplorer/scratch-to-contact.ga                                                            | [![Build Status](https://build.galaxyproject.eu/job/usegalaxy-eu/job/workflow-testing/PYTHON=System-CPython-2.7,WORKFLOW=HiCExplorer%2Fscratch-to-contact.ga/badge/icon                                                                )](https://build.galaxyproject.eu/job/usegalaxy-eu/job/workflow-testing/PYTHON=System-CPython-2.7,WORKFLOW=HiCExplorer%2Fscratch-to-contact.ga/)
example_blockclust/blockclust_workflow.ga                                                    | [![Build Status](https://build.galaxyproject.eu/job/usegalaxy-eu/job/workflow-testing/PYTHON=System-CPython-2.7,WORKFLOW=example_blockclust%2Fblockclust_workflow.ga/badge/icon                                                        )](https://build.galaxyproject.eu/job/usegalaxy-eu/job/workflow-testing/PYTHON=System-CPython-2.7,WORKFLOW=example_blockclust%2Fblockclust_workflow.ga/)
training/variant-analysis/microbial-variants/microbial_variant_calling.ga                    | [![Build Status](https://build.galaxyproject.eu/job/usegalaxy-eu/job/workflow-testing/PYTHON=System-CPython-2.7,WORKFLOW=training%2Fvariant-analysis%2Fmicrobial-variants%2Fmicrobial_variant_calling.ga/badge/icon                    )](https://build.galaxyproject.eu/job/usegalaxy-eu/job/workflow-testing/PYTHON=System-CPython-2.7,WORKFLOW=training%2Fvariant-analysis%2Fmicrobial-variants%2Fmicrobial_variant_calling.ga/)
training/sequence-analysis/quality-control/quality_control.ga                                | [![Build Status](https://build.galaxyproject.eu/job/usegalaxy-eu/job/workflow-testing/PYTHON=System-CPython-2.7,WORKFLOW=training%2Fsequence-analysis%2Fquality-control%2Fquality_control.ga/badge/icon                                )](https://build.galaxyproject.eu/job/usegalaxy-eu/job/workflow-testing/PYTHON=System-CPython-2.7,WORKFLOW=training%2Fsequence-analysis%2Fquality-control%2Fquality_control.ga/)
training/sequence-analysis/mapping/mapping.ga                                                | [![Build Status](https://build.galaxyproject.eu/job/usegalaxy-eu/job/workflow-testing/PYTHON=System-CPython-2.7,WORKFLOW=training%2Fsequence-analysis%2Fmapping%2Fmapping.ga/badge/icon                                                )](https://build.galaxyproject.eu/job/usegalaxy-eu/job/workflow-testing/PYTHON=System-CPython-2.7,WORKFLOW=training%2Fsequence-analysis%2Fmapping%2Fmapping.ga/)
training/chip-seq/formation_of_super-structures_on_xi/formation_of_super_structures_on_xi.ga | [![Build Status](https://build.galaxyproject.eu/job/usegalaxy-eu/job/workflow-testing/PYTHON=System-CPython-2.7,WORKFLOW=training%2Fchip-seq%2Fformation_of_super-structures_on_xi%2Fformation_of_super_structures_on_xi.ga/badge/icon )](https://build.galaxyproject.eu/job/usegalaxy-eu/job/workflow-testing/PYTHON=System-CPython-2.7,WORKFLOW=training%2Fchip-seq%2Fformation_of_super-structures_on_xi%2Fformation_of_super_structures_on_xi.ga/)
training/epigenetics/methylation-seq/methylation-seq.ga                                      | [![Build Status](https://build.galaxyproject.eu/job/usegalaxy-eu/job/workflow-testing/PYTHON=System-CPython-2.7,WORKFLOW=training%2Fepigenetics%2Fmethylation-seq%2Fmethylation-seq.ga/badge/icon                                      )](https://build.galaxyproject.eu/job/usegalaxy-eu/job/workflow-testing/PYTHON=System-CPython-2.7,WORKFLOW=training%2Fepigenetics%2Fmethylation-seq%2Fmethylation-seq.ga/)
training/assembly/general-introduction/assembly-general-introduction.ga                      | [![Build Status](https://build.galaxyproject.eu/job/usegalaxy-eu/job/workflow-testing/PYTHON=System-CPython-2.7,WORKFLOW=training%2Fassembly%2Fgeneral-introduction%2Fassembly-general-introduction.ga/badge/icon                      )](https://build.galaxyproject.eu/job/usegalaxy-eu/job/workflow-testing/PYTHON=System-CPython-2.7,WORKFLOW=training%2Fassembly%2Fgeneral-introduction%2Fassembly-general-introduction.ga/)
training/assembly/unicycler-assembly/unicycler.ga                                            | [![Build Status](https://build.galaxyproject.eu/job/usegalaxy-eu/job/workflow-testing/PYTHON=System-CPython-2.7,WORKFLOW=training%2Fassembly%2Funicycler-assembly%2Funicycler.ga/badge/icon                                            )](https://build.galaxyproject.eu/job/usegalaxy-eu/job/workflow-testing/PYTHON=System-CPython-2.7,WORKFLOW=training%2Fassembly%2Funicycler-assembly%2Funicycler.ga/)
training/metagenomics/general-tutorial/amplicon.ga                                           | [![Build Status](https://build.galaxyproject.eu/job/usegalaxy-eu/job/workflow-testing/PYTHON=System-CPython-2.7,WORKFLOW=training%2Fmetagenomics%2Fgeneral-tutorial%2Famplicon.ga/badge/icon                                           )](https://build.galaxyproject.eu/job/usegalaxy-eu/job/workflow-testing/PYTHON=System-CPython-2.7,WORKFLOW=training%2Fmetagenomics%2Fgeneral-tutorial%2Famplicon.ga/)
training/transcriptomics/ref-based/ref_based.ga                                              | [![Build Status](https://build.galaxyproject.eu/job/usegalaxy-eu/job/workflow-testing/PYTHON=System-CPython-2.7,WORKFLOW=training%2Ftranscriptomics%2Fref-based%2Fref_based.ga/badge/icon                                              )](https://build.galaxyproject.eu/job/usegalaxy-eu/job/workflow-testing/PYTHON=System-CPython-2.7,WORKFLOW=training%2Ftranscriptomics%2Fref-based%2Fref_based.ga/)
GraphClust2/GC-lite.ga                                                                       | [![Build Status](https://build.galaxyproject.eu/job/usegalaxy-eu/job/workflow-testing/PYTHON=System-CPython-2.7,WORKFLOW=GraphClust2%2FGC-lite.ga/badge/icon                                                                           )](https://build.galaxyproject.eu/job/usegalaxy-eu/job/workflow-testing/PYTHON=System-CPython-2.7,WORKFLOW=GraphClust2%2FGC-lite.ga/)

## Test Files

For providing test files, each folder contains a `urls.txt` which contains a set of URLs that should be downloaded.
