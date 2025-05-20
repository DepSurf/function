# Function: <code>cgwb_create</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff811af12c)
Location: mm/backing-dev.c:518
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
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
In mm/backing-dev.c (ffffffff811c854c)
Location: mm/backing-dev.c:518
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
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
In mm/backing-dev.c (ffffffff811d867c)
Location: mm/backing-dev.c:519
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
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
In mm/backing-dev.c (ffffffff811e1982)
Location: mm/backing-dev.c:542
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
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
In mm/backing-dev.c (ffffffff811f79d2)
Location: mm/backing-dev.c:555
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
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
In mm/backing-dev.c (ffffffff81218d0e)
Location: mm/backing-dev.c:535
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff8122bb5e)
Location: mm/backing-dev.c:536
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff8123b83a)
Location: mm/backing-dev.c:523
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff81249ccb)
Location: mm/backing-dev.c:527
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int cgwb_create(struct backing_dev_info *bdi, struct cgroup_subsys_state *memcg_css, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff81277ed0)
Location: mm/backing-dev.c:526
Inline: False
Direct callers:
  - mm/backing-dev.c:wb_get_create
```
**Symbols:**

```
ffffffff81277ed0-ffffffff812782df: cgwb_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int cgwb_create(struct backing_dev_info *bdi, struct cgroup_subsys_state *memcg_css, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff81282650)
Location: mm/backing-dev.c:427
Inline: False
Direct callers:
  - mm/backing-dev.c:wb_get_create
```
**Symbols:**

```
ffffffff81282650-ffffffff81282a7d: cgwb_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int cgwb_create(struct backing_dev_info *bdi, struct cgroup_subsys_state *memcg_css, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff81287760)
Location: mm/backing-dev.c:426
Inline: False
Direct callers:
  - mm/backing-dev.c:wb_get_create
```
**Symbols:**

```
ffffffff81287760-ffffffff81287ba2: cgwb_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int cgwb_create(struct backing_dev_info *bdi, struct cgroup_subsys_state *memcg_css, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff812c6ec0)
Location: mm/backing-dev.c:448
Inline: False
Direct callers:
  - mm/backing-dev.c:wb_get_create
```
**Symbols:**

```
ffffffff812c6ec0-ffffffff812c7344: cgwb_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int cgwb_create(struct backing_dev_info *bdi, struct cgroup_subsys_state *memcg_css, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff813236a0)
Location: mm/backing-dev.c:437
Inline: False
Direct callers:
  - mm/backing-dev.c:wb_get_create
```
**Symbols:**

```
ffffffff813236a0-ffffffff81323bab: cgwb_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int cgwb_create(struct backing_dev_info *bdi, struct cgroup_subsys_state *memcg_css, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff81397f10)
Location: mm/backing-dev.c:564
Inline: False
Direct callers:
  - mm/backing-dev.c:wb_get_create
```
**Symbols:**

```
ffffffff81397f10-ffffffff81398419: cgwb_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int cgwb_create(struct backing_dev_info *bdi, struct cgroup_subsys_state *memcg_css, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff813cae90)
Location: mm/backing-dev.c:577
Inline: False
Direct callers:
  - mm/backing-dev.c:wb_get_create
```
**Symbols:**

```
ffffffff813cae90-ffffffff813cb399: cgwb_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int cgwb_create(struct backing_dev_info *bdi, struct cgroup_subsys_state *memcg_css, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff813f56c0)
Location: mm/backing-dev.c:575
Inline: False
Direct callers:
  - mm/backing-dev.c:wb_get_create
```
**Symbols:**

```
ffffffff813f56c0-ffffffff813f5ba3: cgwb_create (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffff8000102df45c)
Location: mm/backing-dev.c:527
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (c05042dc)
Location: mm/backing-dev.c:527
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (c00000000039efbc)
Location: mm/backing-dev.c:527
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffe0001f7206)
Location: mm/backing-dev.c:527
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff8124231b)
Location: mm/backing-dev.c:527
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff812352eb)
Location: mm/backing-dev.c:527
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff812400bb)
Location: mm/backing-dev.c:527
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff8124f80c)
Location: mm/backing-dev.c:527
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
