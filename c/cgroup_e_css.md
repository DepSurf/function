# Function: <code>cgroup_e_css</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct cgroup_subsys_state *cgroup_e_css(struct cgroup *cgrp, struct cgroup_subsys *ss);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff81111dd0)
Location: kernel/cgroup.c:384
Inline: False
Direct callers:
  - kernel/cgroup.c:find_css_set
  - kernel/cgroup.c:cgroup_taskset_migrate
  - kernel/cgroup.c:cgroup_taskset_migrate
  - kernel/cgroup.c:cgroup_taskset_migrate
```
**Symbols:**

```
ffffffff81111dd0-ffffffff81111e23: cgroup_e_css (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff8111c3d8)
Location: kernel/cgroup.c:427
Inline: True
Inline callers:
  - kernel/cgroup.c:find_css_set
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff81124708)
Location: kernel/cgroup.c:430
Inline: True
Inline callers:
  - kernel/cgroup.c:find_css_set
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81123a92)
Location: kernel/cgroup/cgroup.c:385
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:find_css_set
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8112fee3)
Location: kernel/cgroup/cgroup.c:498
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:find_css_set
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8113e5e8)
Location: kernel/cgroup/cgroup.c:501
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:find_css_set
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct cgroup_subsys_state *cgroup_e_css(struct cgroup *cgrp, struct cgroup_subsys *ss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811499f0)
Location: kernel/cgroup/cgroup.c:540
Inline: False
Direct callers:
  - block/bio.c:bio_associate_blkg_from_page
```
**Symbols:**

```
ffffffff811499f0-ffffffff81149a35: cgroup_e_css (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct cgroup_subsys_state *cgroup_e_css(struct cgroup *cgrp, struct cgroup_subsys *ss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81154f90)
Location: kernel/cgroup/cgroup.c:542
Inline: False
Direct callers:
  - block/bio.c:bio_associate_blkg_from_page
```
**Symbols:**

```
ffffffff81154f90-ffffffff81154fd9: cgroup_e_css (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct cgroup_subsys_state *cgroup_e_css(struct cgroup *cgrp, struct cgroup_subsys *ss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81160bc0)
Location: kernel/cgroup/cgroup.c:542
Inline: False
Direct callers:
  - block/bio.c:bio_associate_blkg_from_page
```
**Symbols:**

```
ffffffff81160bc0-ffffffff81160c05: cgroup_e_css (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct cgroup_subsys_state *cgroup_e_css(struct cgroup *cgrp, struct cgroup_subsys *ss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81172220)
Location: kernel/cgroup/cgroup.c:535
Inline: False
Direct callers:
  - block/bio.c:bio_associate_blkg_from_page
```
**Symbols:**

```
ffffffff81172220-ffffffff81172262: cgroup_e_css (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct cgroup_subsys_state *cgroup_e_css(struct cgroup *cgrp, struct cgroup_subsys *ss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8116ee70)
Location: kernel/cgroup/cgroup.c:532
Inline: False
Direct callers:
  - mm/page_io.c:__swap_writepage
```
**Symbols:**

```
ffffffff8116ee70-ffffffff8116eeb3: cgroup_e_css (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct cgroup_subsys_state *cgroup_e_css(struct cgroup *cgrp, struct cgroup_subsys *ss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8116faa0)
Location: kernel/cgroup/cgroup.c:532
Inline: False
Direct callers:
  - mm/page_io.c:__swap_writepage
```
**Symbols:**

```
ffffffff8116faa0-ffffffff8116fae3: cgroup_e_css (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct cgroup_subsys_state *cgroup_e_css(struct cgroup *cgrp, struct cgroup_subsys *ss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81195f10)
Location: kernel/cgroup/cgroup.c:556
Inline: False
Direct callers:
  - mm/page_io.c:__swap_writepage
```
**Symbols:**

```
ffffffff81195f10-ffffffff81195f91: cgroup_e_css (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct cgroup_subsys_state *cgroup_e_css(struct cgroup *cgrp, struct cgroup_subsys *ss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811c5df0)
Location: kernel/cgroup/cgroup.c:557
Inline: False
Direct callers:
  - mm/page_io.c:__swap_writepage
```
**Symbols:**

```
ffffffff811c5df0-ffffffff811c5e8a: cgroup_e_css (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct cgroup_subsys_state *cgroup_e_css(struct cgroup *cgrp, struct cgroup_subsys *ss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81208870)
Location: kernel/cgroup/cgroup.c:562
Inline: False
Direct callers:
  - mm/page_io.c:__swap_writepage
```
**Symbols:**

```
ffffffff81208870-ffffffff81208909: cgroup_e_css (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct cgroup_subsys_state *cgroup_e_css(struct cgroup *cgrp, struct cgroup_subsys *ss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8121df80)
Location: kernel/cgroup/cgroup.c:561
Inline: False
Direct callers:
  - mm/page_io.c:bio_associate_blkg_from_page
```
**Symbols:**

```
ffffffff8121df80-ffffffff8121e02a: cgroup_e_css (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct cgroup_subsys_state *cgroup_e_css(struct cgroup *cgrp, struct cgroup_subsys *ss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81235be0)
Location: kernel/cgroup/cgroup.c:541
Inline: False
```
**Symbols:**

```
ffffffff81235be0-ffffffff81235c8a: cgroup_e_css (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct cgroup_subsys_state *cgroup_e_css(struct cgroup *cgrp, struct cgroup_subsys *ss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffff8000101d1db8)
Location: kernel/cgroup/cgroup.c:542
Inline: False
Direct callers:
  - block/bio.c:bio_associate_blkg_from_page
```
**Symbols:**

```
ffff8000101d1db8-ffff8000101d1e14: cgroup_e_css (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct cgroup_subsys_state *cgroup_e_css(struct cgroup *cgrp, struct cgroup_subsys *ss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c0414d10)
Location: kernel/cgroup/cgroup.c:542
Inline: False
Direct callers:
  - block/bio.c:bio_associate_blkg_from_page
```
**Symbols:**

```
c0414d10-c0414d68: cgroup_e_css (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct cgroup_subsys_state *cgroup_e_css(struct cgroup *cgrp, struct cgroup_subsys *ss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c00000000023c870)
Location: kernel/cgroup/cgroup.c:542
Inline: False
Direct callers:
  - block/bio.c:bio_associate_blkg_from_page
```
**Symbols:**

```
c00000000023c870-c00000000023c8e0: cgroup_e_css (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct cgroup_subsys_state *cgroup_e_css(struct cgroup *cgrp, struct cgroup_subsys *ss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffe00014b818)
Location: kernel/cgroup/cgroup.c:542
Inline: False
Direct callers:
  - block/bio.c:bio_associate_blkg_from_page
```
**Symbols:**

```
ffffffe00014b818-ffffffe00014b86e: cgroup_e_css (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
struct cgroup_subsys_state *cgroup_e_css(struct cgroup *cgrp, struct cgroup_subsys *ss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811591e0)
Location: kernel/cgroup/cgroup.c:542
Inline: False
Direct callers:
  - block/bio.c:bio_associate_blkg_from_page
```
**Symbols:**

```
ffffffff811591e0-ffffffff81159225: cgroup_e_css (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct cgroup_subsys_state *cgroup_e_css(struct cgroup *cgrp, struct cgroup_subsys *ss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8114c4f0)
Location: kernel/cgroup/cgroup.c:542
Inline: False
Direct callers:
  - block/bio.c:bio_associate_blkg_from_page
```
**Symbols:**

```
ffffffff8114c4f0-ffffffff8114c535: cgroup_e_css (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct cgroup_subsys_state *cgroup_e_css(struct cgroup *cgrp, struct cgroup_subsys *ss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81156fb0)
Location: kernel/cgroup/cgroup.c:542
Inline: False
Direct callers:
  - block/bio.c:bio_associate_blkg_from_page
```
**Symbols:**

```
ffffffff81156fb0-ffffffff81156ff5: cgroup_e_css (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct cgroup_subsys_state *cgroup_e_css(struct cgroup *cgrp, struct cgroup_subsys *ss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81163f70)
Location: kernel/cgroup/cgroup.c:542
Inline: False
Direct callers:
  - block/bio.c:bio_associate_blkg_from_page
```
**Symbols:**

```
ffffffff81163f70-ffffffff81163fb5: cgroup_e_css (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
