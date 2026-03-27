# PLACID Project Page
Project page for "PLACID: Identity-Preserving Multi-Object Compositing via Video Diffusion with Synthetic Trajectories".
Live at: https://mbaradad.github.io/placid

## Image and Video Paths in index.html
Below is every asset referenced in the page, its S3 source, and what it's used for. Replace any of these with your preferred alternatives.

### Paper Figures

| File in `index.html` | Local path | S3 source | Section |
|---|---|---|---|
| `static/images/placid_teaser.png` | `static/images/placid_teaser.png` | `s3://cangemma-exp/results_papermodel/paper_figures/teaser5.png` | Teaser |
| `static/images/placid_architecture.jpg` | `static/images/placid_architecture.jpg` | `s3://cangemma-exp/results_papermodel/paper_figures/architecture6.jpeg` | Method Overview |
| `static/images/placid_training_data.jpg` | `static/images/placid_training_data.jpg` | `s3://cangemma-exp/results_papermodel/paper_figures/trainingdatagen10.jpeg` | Training Data Generation |
| `static/images/placid_comparison.png` | `static/images/placid_comparison.png` | `s3://cangemma-exp/results_papermodel/paper_figures/qualitativefig7.png` | Comparison to SOTA |
| `static/images/placid_userstudy.png` | `static/images/placid_userstudy.png` | `s3://cangemma-exp/results_papermodel/paper_figures/userstudies5.png` | User Studies |
| `static/images/placid_emerging.jpg` | `static/images/placid_emerging.jpg` | `s3://cangemma-exp/results_papermodel/paper_figures/versatility8.jpeg` | Emerging Capabilities |

### Training Data Pipeline Figures

| File in `index.html` | Local path | S3 source | Section |
|---|---|---|---|
| `static/images/traindata_unsplash_pipeline.png` | `static/images/traindata_unsplash_pipeline.png` | `s3://cangemma-exp/results_papermodel/paper_figures/unsplash_supmat_fig3.png` | Training Data (i) Unsplash |
| `static/images/traindata_figma_pipeline.png` | `static/images/traindata_figma_pipeline.png` | `s3://cangemma-exp/results_papermodel/paper_figures/figma_supmat_fig4.png` | Training Data (ii) Manual Designs |
| `static/images/traindata_subject200k_pipeline.png` | `static/images/traindata_subject200k_pipeline.png` | `s3://cangemma-exp/results_papermodel/paper_figures/subject_supmat_fig4.png` | Training Data (iii) Subject-200k |
| `static/images/traindata_sidebyside_pipeline.png` | `static/images/traindata_sidebyside_pipeline.png` | `s3://cangemma-exp/results_papermodel/paper_figures/RGBA_supmat_fig4.png` | Training Data (iv) Side-by-side |

### Training Data Construction Videos

| File in `index.html` | Local path | S3 source | Label |
|---|---|---|---|
| `static/videos/training_data/supmat_unsplash.mp4` | `static/videos/training_data/supmat_unsplash.mp4` | `s3://cangemma-exp/results_papermodel/training_data/supmat_unsplash.mp4` | Unsplash (in-the-wild) |
| `static/videos/training_data/supmat_figmarot_pinkmakeup2.mp4` | `static/videos/training_data/supmat_figmarot_pinkmakeup2.mp4` | `s3://cangemma-exp/results_papermodel/training_data/supmat_figmarot_pinkmakeup2.mp4` | Manual designs |
| `static/videos/training_data/motion_subject200k_3.mp4` | `static/videos/training_data/motion_subject200k_3.mp4` | `s3://cangemma-exp/results_papermodel/training_data/motion_subject200k_3.mp4` | Subject-200k pairs |
| `static/videos/training_data/supmat_RGBA4.mp4` | `static/videos/training_data/supmat_RGBA4.mp4` | `s3://cangemma-exp/results_papermodel/training_data/supmat_RGBA4.mp4` | Synthetic side-by-side |

Additional training data videos available (not currently in page):
- `static/videos/training_data/papervideointerpolation.mp4`
- `static/videos/training_data/papervideointerpolation_20F.mp4`
- `static/videos/training_data/papervideomotion3.mp4`

### Extra figures downloaded (not in index.html, available for use)

| Local path | S3 source | Description |
|---|---|---|
| `static/images/placid_editing.png` | `s3://cangemma-exp/results_papermodel/paper_figures/supmat_edit3.png` | Editing examples |
| `static/images/placid_customization.png` | `s3://cangemma-exp/results_papermodel/paper_figures/supmat_customization2.png` | Customization examples |
| `static/images/placid_textinteract.png` | `s3://cangemma-exp/results_papermodel/paper_figures/supmat_textinteract.png` | Text-guided interacting objects |
| `static/images/placid_intro_limitations.jpg` | `s3://cangemma-exp/results_papermodel/paper_figures/intro2.jpg` | Limitations of prior work (Fig.2) |

### Example Result Input Images

Input object images and backgrounds used in the Example Results section. From `s3://cangemma-exp/abo_testset/`.

**Backgrounds:**

| File in `index.html` | S3 source |
|---|---|
| `static/images/inputs/bg2.jpg` | `s3://cangemma-exp/abo_testset/testset_bg/bg2.jpg` |
| `static/images/inputs/bg5.jpg` | `s3://cangemma-exp/abo_testset/testset_bg/bg5.jpg` |
| `static/images/inputs/bg7.jpg` | `s3://cangemma-exp/abo_testset/testset_bg/bg7.jpg` |
| `static/images/inputs/bg26.jpg` | `s3://cangemma-exp/abo_testset/testset_bg/bg26.jpg` |
| `static/images/inputs/bg40.jpg` | `s3://cangemma-exp/abo_testset/testset_bg/bg40.jpg` |
| `static/images/inputs/bg42.jpg` | `s3://cangemma-exp/abo_testset/testset_bg/bg42.jpg` |
| `static/images/inputs/bg43.jpg` | `s3://cangemma-exp/abo_testset/testset_bg/bg43.jpg` |
| `static/images/inputs/bg48.jpg` | `s3://cangemma-exp/abo_testset/testset_bg/bg48.jpg` |
| `static/images/inputs/bg51.jpg` | `s3://cangemma-exp/abo_testset/testset_bg/bg51.jpg` |

**Object images:**

| File in `index.html` | Example | S3 source |
|---|---|---|
| `static/images/inputs/12.jpg` | Test 7 (watch) | `s3://cangemma-exp/abo_testset/12.jpg` |
| `static/images/inputs/1abfbe4f.jpg` | Test 2 (ring 1) | `s3://cangemma-exp/abo_testset/1abfbe4f.jpg` |
| `static/images/inputs/1c9f948a.jpg` | Test 2 (ring 2) | `s3://cangemma-exp/abo_testset/1c9f948a.jpg` |
| `static/images/inputs/36.jpg` | Test 5 (ceramics) | `s3://cangemma-exp/abo_testset/36.jpg` |
| `static/images/inputs/0a2efe1f.jpg` | Test 5 (vase) | `s3://cangemma-exp/abo_testset/0a2efe1f.jpg` |
| `static/images/inputs/50.jpg` | Test 1 (duck) | `s3://cangemma-exp/abo_testset/50.jpg` |
| `static/images/inputs/0bbf3d2f.jpg` | Test 1 (truck) | `s3://cangemma-exp/abo_testset/0bbf3d2f.jpg` |
| `static/images/inputs/18.jpg` | Test 1 (robot) | `s3://cangemma-exp/abo_testset/18.jpg` |
| `static/images/inputs/1bd2c385.jpg` | Test 11 (orange chair) | `s3://cangemma-exp/abo_testset/1bd2c385.jpg` |
| `static/images/inputs/0faf08e4.jpg` | Test 11 (wooden table) | `s3://cangemma-exp/abo_testset/0faf08e4.jpg` |
| `static/images/inputs/0eff2fa0.jpg` | Test 11 (multicolored vase) | `s3://cangemma-exp/abo_testset/0eff2fa0.jpg` |
| `static/images/inputs/0ca1a4ab.jpg` | Test 9 (scarf) | `s3://cangemma-exp/abo_testset/0ca1a4ab.jpg` |
| `static/images/inputs/00fca538.jpg` | Test 9 (necklace) | `s3://cangemma-exp/abo_testset/00fca538.jpg` |
| `static/images/inputs/1a8f660b.jpg` | Test 9 (bracelet) | `s3://cangemma-exp/abo_testset/1a8f660b.jpg` |
| `static/images/inputs/13.jpg` | Test 6 (teddy bear) | `s3://cangemma-exp/abo_testset/13.jpg` |
| `static/images/inputs/20.jpg` | Test 6 (rubik's cube) | `s3://cangemma-exp/abo_testset/20.jpg` |
| `static/images/inputs/31.jpg` | Test 6 (toy) | `s3://cangemma-exp/abo_testset/31.jpg` |
| `static/images/inputs/34.jpg` | Test 6 (toy) | `s3://cangemma-exp/abo_testset/34.jpg` |
| `static/images/inputs/0a1e57ec.jpg` | Test 3 (plaid chair) | `s3://cangemma-exp/abo_testset/0a1e57ec.jpg` |
| `static/images/inputs/0c0cc953.jpg` | Test 3 (blue chair) | `s3://cangemma-exp/abo_testset/0c0cc953.jpg` |
| `static/images/inputs/1b99e8aa.jpg` | Test 3 (table) | `s3://cangemma-exp/abo_testset/1b99e8aa.jpg` |
| `static/images/inputs/0a2f9964.jpg` | Test 3 (lamp) | `s3://cangemma-exp/abo_testset/0a2f9964.jpg` |
| `static/images/inputs/1e60f202.jpg` | Test 8 (wine) | `s3://cangemma-exp/abo_testset/1e60f202.jpg` |
| `static/images/inputs/1df7d7e9.jpg` | Test 8 (salad) | `s3://cangemma-exp/abo_testset/1df7d7e9.jpg` |
| `static/images/inputs/8ac8a148.jpg` | Test 8 (sauce) | `s3://cangemma-exp/abo_testset/8ac8a148.jpg` |
| `static/images/inputs/0adf522f.jpg` | Test 8 (watermelon) | `s3://cangemma-exp/abo_testset/0adf522f.jpg` |
| `static/images/inputs/0b6e1c5a.jpg` | Test 8 (plate) | `s3://cangemma-exp/abo_testset/0b6e1c5a.jpg` |

To find which objects belong to which test set ID, see `s3://cangemma-exp/abo_testset/testset_100.json`.

### Example Result Images

All from `s3://cangemma-exp/results_papermodel/images/`. These are curated results on the evaluation set.

| File in `index.html` | S3 source | Description |
|---|---|---|
| `static/images/examples/7_1.png` | `s3://cangemma-exp/results_papermodel/images/7_1.png` | 1 object (watch) |
| `static/images/examples/2_1.png` | `s3://cangemma-exp/results_papermodel/images/2_1.png` | 2 objects (rings) |
| `static/images/examples/5_1.png` | `s3://cangemma-exp/results_papermodel/images/5_1.png` | 2 objects (ceramics) |
| `static/images/examples/1_1.png` | `s3://cangemma-exp/results_papermodel/images/1_1.png` | 3 objects (duck, truck, robot) |
| `static/images/examples/11_1.png` | `s3://cangemma-exp/results_papermodel/images/11_1.png` | 3 objects (chair, table, vase) |
| `static/images/examples/9_1.png` | `s3://cangemma-exp/results_papermodel/images/9_1.png` | 3 objects (accessories) |
| `static/images/examples/6_1.png` | `s3://cangemma-exp/results_papermodel/images/6_1.png` | 4 objects (teddy bear, toys) |
| `static/images/examples/3_1.png` | `s3://cangemma-exp/results_papermodel/images/3_1.png` | 4 objects (furniture) |
| `static/images/examples/8_1.png` | `s3://cangemma-exp/results_papermodel/images/8_1.png` | 5 objects (food) |

To download other result images:
```bash
aws s3 ls s3://cangemma-exp/results_papermodel/images/
# Then: aws s3 cp s3://cangemma-exp/results_papermodel/images/{ID}.png static/images/examples/
```

### Example Result Videos

All from `s3://cangemma-exp/finetune_experiments_1obj/ablationloss_ff_33frames_119000/`.

| File in `index.html` | S3 source |
|---|---|
| `static/videos/test_7_0_1335230976.mp4` | `s3://cangemma-exp/finetune_experiments_1obj/ablationloss_ff_33frames_119000/test_7_0_1335230976.mp4` |
| `static/videos/test_2_0_1065640400.mp4` | `s3://cangemma-exp/finetune_experiments_1obj/ablationloss_ff_33frames_119000/test_2_0_1065640400.mp4` |
| `static/videos/test_1_0_1150295423.mp4` | `s3://cangemma-exp/finetune_experiments_1obj/ablationloss_ff_33frames_119000/test_1_0_1150295423.mp4` |
| `static/videos/test_11_0_2521346317.mp4` | `s3://cangemma-exp/finetune_experiments_1obj/ablationloss_ff_33frames_119000/test_11_0_2521346317.mp4` |
| `static/videos/test_6_0_2152621784.mp4` | `s3://cangemma-exp/finetune_experiments_1obj/ablationloss_ff_33frames_119000/test_6_0_2152621784.mp4` |
| `static/videos/test_8_0_1080565479.mp4` | `s3://cangemma-exp/finetune_experiments_1obj/ablationloss_ff_33frames_119000/test_8_0_1080565479.mp4` |

To download other videos for a given test ID:
```bash
aws s3 ls s3://cangemma-exp/finetune_experiments_1obj/ablationloss_ff_33frames_119000/ | grep "test_{ID}_"
```

## Swapping Examples

To replace an example image or video:

1. Download the new asset from S3 (see paths above)
2. Place it in the appropriate directory (`static/images/examples/`, `static/images/inputs/`, or `static/videos/`)
3. Update the `src` attribute in `index.html`

### Example Results layout

Each example result is displayed as an `.example-tile` in a 3x3 grid (`.examples-grid`) with:
- `.tile-section-label` "OBJECTS" — object thumbnails left-aligned
- `.tile-section-label` "BACKGROUND" — background image with blue border
- `.tile-arrow` — down arrow separator
- `.tile-output` — the composited result image
- `.tile-caption` — object count label

To swap an example, you need to update both the input images (objects + background) and the output result image. Use `testset_100.json` to look up which objects and background belong to a given test set ID.

### Training Data layout

The training data section shows the motion-vs-interpolation comparison figure and a 2x2 video grid (`.traindata-video-grid`) showing how training data is constructed for each of the four sources.

### Video grid

The video output section uses a 3-column grid (`.video-grid`) with 6 videos (3x2). Add or remove `<video>` elements as needed.
