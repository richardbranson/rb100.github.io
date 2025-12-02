# rb100 Tool Kit
A collection of developer resources, embed widgets, API examples and open-source tools from [RB100.Fitness](https://rb100.fitness/). Designed for gyms, PTs and hybrid training platforms wanting to integrate evidence-based exercise cards, WOD modules and performance calculators directly into their websites and apps.

[rb100.Fitness on GitHub Pages](https://richardbranson.github.io/rb100.fitness/)
[rb.100.Fitness Tools](https://richardbranson.github.io/rb100.fitness/fitness-tools/)

⸻

## RB100 Fitness Integration Toolkit

Embed RB100 exercise cards, workouts, and training tools into your website.

Welcome to the RB100 Fitness Integration Toolkit. This repository provides developer-friendly resources that allow gyms, personal trainers, coaches, and hybrid training platforms to embed RB100 components directly into their websites or apps.

RB100.Fitness publishes evidence-based exercise guides, HYROX training resources, and performance-focused tools. These integrations help you bring that content directly to your users.

⸻

1. Exercise Library Embed

Easily display any RB100 Exercise Card on your site.
```
<div data-rb100-exercise="sandbag-zercher-lunge"></div>
<script src="https://rb100.fitness/embed/exercise.js"></script>

Replace "sandbag-zercher-lunge" with any exercise slug from the RB100 Exercise Library:
https://rb100.fitness/exercise/
```
⸻

2. Workout of the Day (WOD) Embed

Embed the RB100 daily or weekly workout on any site:
```
<div id="rb100-wod"></div>
<script src="https://rb100.fitness/embed/wod.js"></script>
```
Customisation options (coming soon):
	- difficulty
	- equipment
	- duration

⸻

3. REST API Access

All RB100 exercises, including ACF fields, are accessible via the WordPress REST API.

Example endpoint:
```
https://rb100.fitness/wp-json/wp/v2/exercise?slug=sandbag-zercher-lunge&acf_format=standard
```
Typical JSON response includes:
	- Exercise name
	- Excerpt
	- Movement patterns
	- Muscle groups
	- ACF coaching cues
	- Variations
	- Regressions
	- Programming ideas

Use this data to build custom components, dashboards or integrations.

⸻

4. Tools & Calculators

This repo will include source code for training tools developed for RB100, such as:
	•	Zone 2 Heart Rate Calculators
	•	HYROX Pace Predictors
	•	Rep Scheme Generators
	•	Timer Logic
	•	Workout data schemas
	•	Sensor scripts for training devices

Open-source examples will be added over time to support gyms, coaches and developers.

⸻

5. Who This Is For

This integration toolkit is designed for:
	•	Gym owners
	•	Personal trainers
	•	HYROX coaches
	•	Online programming platforms
	•	Fitness app developers
	•	Sport-tech builders
	•	Hybrid athletes

If you create something using this toolkit, feel free to share it — we’d love to see it.

⸻

6. About RB100.Fitness

RB100 is a hybrid-fitness platform specialising in the intersection of strength, engine capacity, and race performance.
We produce:
	- [Exercise library](https://rb100.fitness/exercises)
	- [Exercise of the Day]([https://rb100.fitness/](http://rb100.fitness/exercises/exercise-of-the-day/))
	- Training plans
	- [HYROX Article Series](https://rb100.fitness/hyrox)
	- [100-challenge workouts](https://rb100.fitness/relentless-bravery-challenges/)
	- Athlete insights
	- Performance tools and calculators

Visit the full platform here:
[RB100.Fitness](https://rb100.fitness/)

⸻

7. License

This project is licensed under the MIT License unless otherwise stated.
You are free to modify, adapt and integrate components as needed.

⸻

