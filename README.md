# P300-based-Brain-Computer-Interface
BCI paradigm that uses EEG -- a P300 based on-screen menu selection.

Brain-computer interfaces (BCIs) are an exciting possibility of modern-day Biomedical Engineering. They
have a broad range of potential applications from augmenting human sensorimotor action in both medical
(e.g., prostheses) and non-medical contexts (e.g., virtual-reality games), to neurofeedback for training and
therapy (e.g., management of chronic pain, ADHD, rehabilitation after stroke). Electroencephalography
(EEG) provides a non-invasive window to measure brain responses to various kinds of stimuli and how they
interact with behaviors. 
Classically, the P300 is a positive response peak that occurs in the EEG
when an environmental stimulus happens to match a target expectation. It has been suggested that the
P300 could be exploited to device a mental prosthetic that can be used for spelling when the patient is
otherwise paralyzed (e.g., see Kübler et al., 2009).
In this project, I will use the data collected by Ulrich Hoffmann’s research group at EPFL accompanying
their 2008 publication in the Journal of Neuroscience Methods (Hoffmann et al., 2008). Here, subjects were
asked to concentrate on one of six different pictures on screen as they are periodically flashed one at a time
and count the number of times the target flashed. The idea is that this simulates a scenario where a patient
is trying to mentally select one of the six possible menu items on screen. When the target image (i.e., the
one that the subject is concentrating on) flashes, the EEG data exhibits a P300 response (see Hoffmann et
al., 2008 for details). The engineering problem is then one of decoding which of the six menu items the
subject intended to select, by using just the EEG data. The faster the target is decoded from the EEG, the
more quickly the action corresponding to the selected menu item can be executed. Further, the fewer the
number of EEG channels required to decode the target, the interface becomes simpler and less intrusive.
Also, if the features that differentiate the target menu item from the other items is consistent across
multiple sessions for a given subjects, or is consistent across different individuals, then the BCI can be
optimized for the “average” person without having to train the BCI for each individual or for each session.
