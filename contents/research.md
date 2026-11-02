### AudioIP: Joint Speaker Identity Profiling and Spoof Detection

**ICASSP 2027 · Under Review**

Built VoicePrint, a benchmark of 172,779 utterances from 448 speakers with structured voice-type annotations derived from public audio and metadata. Designed an open-set evaluation protocol with disjoint training, enrolment, and query audio and separate seen and unseen cloning methods to assess generalisation to unseen speakers and cloning techniques.

Proposed AudioIP to unify spoofing detection and clone-identity attribution through a shared WavLM-Base encoder, attentive statistics pooling, and temporal convolutions with attention pooling. At the EER-calibrated operating point, it achieved full-chain accuracy of 74.3% on seen and 30.0% on unseen cloning methods, while reducing parameters from 191.8M to 97.1M and MACs from 14.3G to 7.2G.

### Direction-Reading Inference from semantic-preserving Transformations

**IEEE S&P 2027 · Under Review**

Introduced DRIFT, an image-side membership inference attack against vision-language models that infers training membership solely from model responses to nine semantics-preserving image variants, without using the original image's output statistic.

Achieved 0.7712 AUC on the LLaVA-1.5-7B description slice of the Geometry dataset, substantially exceeding the un-fine-tuned control's 0.4610. Established response direction, rather than displacement magnitude, as the membership signal, and exposed provenance confounding in the Flickr dataset by recovering membership from image provenance alone at 0.9945 AUC. Introduced a model-free reference line and systematically validated Geometry as a benchmark free of this confound.
