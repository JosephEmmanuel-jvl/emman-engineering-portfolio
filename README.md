# Joseph Emmanuel V. Landeza | Computer Engineering Portfolio

Live portfolio: https://josephemmanuel-portfolio.vercel.app/

A static portfolio for my computer engineering projects. It covers VERDE, Campus Lost and Found, the earlier VERDE YOLOv8 experiment, and Ethically Me.

The Campus Lost and Found section includes screenshots captured from the live Student demo account and a short account of my later backend contributions. The item records shown are sample data; no demo credentials are stored in this repository.

The VERDE thesis section says the final panel defense passed and the team is addressing panel recommendations. It lists Healthy, Yellowing, Wilting, and Harvest-Ready for the thesis system and distinguishes the earlier public three-class YOLOv8s experiment. As submitted for defense, the three-state detector scored 96.67% mAP@0.5 on a 200-image test split, with the top prediction matching the annotation in 198 images. The separate Harvest-Ready classifier, combined with days since planting, had 100% recall and 77.83% precision on 209 images at 30 days since planting. The split is not yet proven independent by plant or source, and external testing remains future work. The public experiment card separately reports the 0.962 mAP50 and 0.713 mAP50-95 figures from its repository README with its own test-split caveat.

## Run locally

From this folder:

```powershell
python -m http.server 4173
```

Open `http://127.0.0.1:4173/`. The site uses HTML, CSS, and JavaScript without a build step.

## Later, after the content is final

- Add a general résumé PDF when it is ready.
- Add restrained motion to the system diagram and project visuals, with a reduced-motion option.
