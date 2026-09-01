Radiotherapy is an applied physics problem: ionising radiation deposited in heterogeneous
anatomy, under geometric and biological constraints. In clinical trials, each treatment plan
is checked by a quality-assurance (QA) review before delivery. That review returns a binary
verdict. A plan passes or it fails, and when it fails the review cannot say whether the planning
was poor or whether the patient’s anatomy put the dosimetric goals out of reach. The two sit
uations call for opposite responses, and current QA does not separate them. It is also manual,
expert-dependent, and hard to scale across centres.
This thesis quantifies how difficult a case is from its geometry alone, as the first step towards
a QA process that can explain why a plan fails. The measure is the Tumour Geometric Complex
ity, computed through the Geometric Volume Coefficient at the organ and at the patient level. A
distance-to-target histogram is partitioned into overlap, near-compression, and separation zones,
and the coefficient is built from the delineated contours alone. Its overlap term is purely anatom
ical; its near-compression term additionally carries the limit of machine deliverability, through
the achievable dose gradient. To test the measure against dose, a multi-modality planning study
was carried out in matRad for photon, proton, helium-ion, and carbon-ion plans, with particle
plans evaluated as RBE-weighted dose. The per-organ delivered doses give an independent check
on the geometric measure.
The descriptor was computed for three head-region patients, one of them carried through
the full pipeline in detail. Patient-level values ranged from 0.04 for a well-separated case to 1.15
for one in which the optic chiasm was almost fully enclosed by the target. The central result
is the agreement between geometry and dose. Ordering the organs at risk by their contour
only coefficient reproduces the ordering of their delivered mean doses, with a Spearman rank
correlation between 0.77 and 0.96 across all twelve patient–modality combinations (all p < 0.01),
and the agreement holds for every modality and every patient. A purely geometric descriptor
therefore recovers the dose burden imposed by the anatomy, across the delivery techniques tested.
This is the measure a complexity-aware quality assurance can be built on: it lets the binary
verdict be opened into four classes, Pass, Fail, Sub-optimal (low complexity), and complexity
limited (high complexity), so that a plan limited by poor planning is distinguished from one
limited by the anatomy. That scheme is proposed here as the natural application of the finding.
These findings are a proof of concept established on three cases. The descriptor’s parameters
and the four-class scheme both await validation on the full cohort.
