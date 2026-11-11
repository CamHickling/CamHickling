## Hi, I'm Cam 👋

I build products for research teams. I start with the problem they can't solve, decide what to build
and what to leave out, ship it to the people who need it, and keep improving it based on what the data shows.

📍 Vancouver, BC · [LinkedIn](https://www.linkedin.com/in/camhickling/)

---

### 👁️ [SocialEyes](https://github.com/CamHickling/SocialEyes): the first open-source phone social media feed with eye tracking

No existing tool offered a realistic social media feed that researchers control, with eye tracking built in.
SocialEyes runs a researcher-controlled feed on a phone while participants wear eye-tracking glasses, with
the app and glasses kept in sync. Mapping gaze onto each post is the next part being built.

<p align="center">
  <a href="https://github.com/CamHickling/SocialEyes"><img src="https://raw.githubusercontent.com/CamHickling/SocialEyes/main/video/socialeyes-15s.gif" width="600" alt="15-second demo of SocialEyes: the feed on a phone, the guided study builder, a double-tap like on a post labelled as digitally altered, and a heatmap of simulated data"></a>
</p>

- **Users:** a team of 8 UBC researchers studying attention and gaze on social media. They expected a
  working tool by the end of their 2-year grant; **I delivered what they needed, and more, in 2 months**, so the
  rest of the funding can go to studies. 3 pilots are being planned and started.
- **Shipped:** a phone app, a desktop app with a guided study builder and a Windows installer, and session
  analysis (touches, scrolling, data quality) into analysis-ready tables
- **Learned from users and data:** I interviewed researchers several times, drew on my own experience using
  eye-tracking tools in studies, and tested the study builder with 3 professors. Most of the team don't use a
  terminal, so I built a guided builder and a Windows installer instead of config files. Pilot measurements
  changed the product too: gaze accuracy (about 4 mm on the screen) turned out coarser than the gap between
  comment lines, so SocialEyes doesn't claim to know which comment someone read.
- **Product calls:** never delete data automatically; lock the analysis plan before anyone sees the results, so
  findings can't be cherry-picked; ship unproven features marked *Experimental*

### 🥋 Iris + FlowAnalytics: a synced capture + analytics platform for movement science research

The UBC Brain, Attention and Reality Lab needed cameras, heart rate and spoken narration recorded together
and lined up precisely. Nothing available could do it, so I built the pipeline from capture to analysis.

**My first version failed its pilots.** It only worked if the operator did everything perfectly, and the
3 pilot sessions had partial data loss, mistimed cues and nervous experimenters. I redesigned Iris as a 7-step
recipe where each step unlocks only when the one before it is done, logged every event to one shared timeline,
and moved heavy processing to after the session. Since then: **zero lost sessions across 50 participants.**

<p align="center">
  <a href="https://github.com/CamHickling/Iris"><img src="https://raw.githubusercontent.com/CamHickling/Iris/main/video/iris-15s.gif" width="600" alt="15-second demo of Iris with simulated devices: a checklist unlocks the next phase, six devices turn green, recording starts, and every device is logged to one shared timeline"></a>
</p>

- **[Iris](https://github.com/CamHickling/Iris)** runs each lab session: every camera, the heart-rate strap and
  the microphone from one app, on one shared timeline.
- **[FlowAnalytics](https://github.com/CamHickling/FlowAnalytics)** turns each session into a synced review
  video and data ready for researchers to analyse.

**Impact:** **90+ hours** of manual alignment cut, a review video for every trial, and motion and facial
analysis the lab couldn't do before. The study is now in analysis, ahead of publication.

---

**How I work**

- **Problem first.** I find out what a team is blocked on before deciding what to build.
- **Honest status.** Each project says what works, what's experimental and what's next
  ([example](https://github.com/CamHickling/SocialEyes#feature-status)).
- **Small, frequent releases.** SocialEyes's phone app shipped
  [16 versions in its first 6 weeks](https://github.com/CamHickling/SocialEyes/commits/main), each change
  tracked as a ticket in Linear.
- **AI in the loop.** I use AI coding tools every day to go from spec to working software, which leaves more
  of my time for users and decisions. Where AI does research work, such as labelling what athletes said about
  their performance, I measure its agreement with people before trusting it.

---

📫 Open to product roles. The best way to reach me is [LinkedIn](https://www.linkedin.com/in/camhickling/).
