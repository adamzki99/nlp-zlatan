# WizardOfWikipedia: Knowledge-powered Conversational Agents

## Planned activities

- [x] Monday 8/5: Data exploration activities such as data visualization, clustering and figuring out how a implementation might look like.

- [x] No date set: Continue with development of a retrieval-based response chatbot and figuring out a way to show the validity of the early implementation

- [ ] Wednesday 24/5: Select the implementation that provides the best selection of passages compared to the original dataset. Also select if we want to work on the other extra assignments related to our data set.

- [ ] Sunday 28/5: Hand-in project.

## Project implementation

~~Create a retrieval-based response Chatbot based on lecture slides 57-59 from slideset 8_chatbots~~

The *value* that our solution provides is that we have **eliminated the need of selecting a topic** in order to get fitting passages.

<p float="middle">
  <img src="https://user-images.githubusercontent.com/64151127/236822970-60d83cc4-87ad-40c8-b386-6bd63546af3d.jpg" width="45%"/>
  <img src="https://user-images.githubusercontent.com/64151127/236822989-abe3fd01-0c6b-4854-a232-d54e5e788248.jpg" width="45%"/>
</p>
TBD

## Project description

- Link to paper: https://arxiv.org/pdf/1811.01241.pdf
- Link to dataset: https://parl.ai/downloads/wizard_of_wikipedia/wizard_of_wikipedia.tgz

### Dataset

The dataset consists of open-domain dialog containing utterances that were generated from content extracted from Wikipedia articles. Multiple candidate Wikipedia passages are associated with each turn in the dialog, where one of them is considered the “reference” (i.e. correct) passage and was used to generate the response text.

### Task

The original tasks for this dataset was to (i) choose the correct passage for each turn and (ii) generate the response in the dialog using the information contained in the reference passage.

### Hints and suggestions

You could investigate one or both of the tasks described above. Moreover, you could even try to tackle the third task of retrieving the candidate set of passages for each turn in the dialog.
