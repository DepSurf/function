# Function: <code>wb_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int wb_init(struct bdi_writeback *wb, struct backing_dev_info *bdi, int blkcg_id, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff811aec20)
Location: mm/backing-dev.c:289
Inline: False
Direct callers:
  - mm/backing-dev.c:bdi_init
  - mm/backing-dev.c:wb_get_create
```
**Symbols:**

```
ffffffff811aec20-ffffffff811aee25: wb_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int wb_init(struct bdi_writeback *wb, struct backing_dev_info *bdi, int blkcg_id, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff811c8060)
Location: mm/backing-dev.c:289
Inline: False
Direct callers:
  - mm/backing-dev.c:bdi_init
  - mm/backing-dev.c:wb_get_create
```
**Symbols:**

```
ffffffff811c8060-ffffffff811c827c: wb_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int wb_init(struct bdi_writeback *wb, struct backing_dev_info *bdi, int blkcg_id, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff811d8180)
Location: mm/backing-dev.c:289
Inline: False
Direct callers:
  - mm/backing-dev.c:bdi_init
  - mm/backing-dev.c:wb_get_create
```
**Symbols:**

```
ffffffff811d8180-ffffffff811d83aa: wb_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int wb_init(struct bdi_writeback *wb, struct backing_dev_info *bdi, int blkcg_id, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff811e14a0)
Location: mm/backing-dev.c:290
Inline: False
Direct callers:
  - mm/backing-dev.c:cgwb_bdi_init
  - mm/backing-dev.c:wb_get_create
```
**Symbols:**

```
ffffffff811e14a0-ffffffff811e16f5: wb_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int wb_init(struct bdi_writeback *wb, struct backing_dev_info *bdi, int blkcg_id, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff811f74c0)
Location: mm/backing-dev.c:303
Inline: False
Direct callers:
  - mm/backing-dev.c:cgwb_bdi_init
  - mm/backing-dev.c:wb_get_create
```
**Symbols:**

```
ffffffff811f74c0-ffffffff811f771b: wb_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int wb_init(struct bdi_writeback *wb, struct backing_dev_info *bdi, int blkcg_id, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff812188d0)
Location: mm/backing-dev.c:293
Inline: False
Direct callers:
  - mm/backing-dev.c:cgwb_bdi_init
  - mm/backing-dev.c:wb_get_create
```
**Symbols:**

```
ffffffff812188d0-ffffffff81218b0c: wb_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int wb_init(struct bdi_writeback *wb, struct backing_dev_info *bdi, int blkcg_id, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff8122b630)
Location: mm/backing-dev.c:293
Inline: False
Direct callers:
  - mm/backing-dev.c:cgwb_bdi_init
  - mm/backing-dev.c:wb_get_create
```
**Symbols:**

```
ffffffff8122b630-ffffffff8122b86c: wb_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int wb_init(struct bdi_writeback *wb, struct backing_dev_info *bdi, int blkcg_id, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff8123b270)
Location: mm/backing-dev.c:280
Inline: False
Direct callers:
  - mm/backing-dev.c:cgwb_bdi_init
  - mm/backing-dev.c:wb_get_create
```
**Symbols:**

```
ffffffff8123b270-ffffffff8123b4d2: wb_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int wb_init(struct bdi_writeback *wb, struct backing_dev_info *bdi, int blkcg_id, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff81249790)
Location: mm/backing-dev.c:284
Inline: False
Direct callers:
  - mm/backing-dev.c:cgwb_bdi_init
  - mm/backing-dev.c:wb_get_create
```
**Symbols:**

```
ffffffff81249790-ffffffff812499f2: wb_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int wb_init(struct bdi_writeback *wb, struct backing_dev_info *bdi, int blkcg_id, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff812779c0)
Location: mm/backing-dev.c:283
Inline: False
Direct callers:
  - mm/backing-dev.c:cgwb_bdi_init
  - mm/backing-dev.c:cgwb_create
```
**Symbols:**

```
ffffffff812779c0-ffffffff81277c7b: wb_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int wb_init(struct bdi_writeback *wb, struct backing_dev_info *bdi, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff81282020)
Location: mm/backing-dev.c:280
Inline: False
Direct callers:
  - mm/backing-dev.c:cgwb_bdi_init
  - mm/backing-dev.c:cgwb_create
```
**Symbols:**

```
ffffffff81282020-ffffffff8128229f: wb_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int wb_init(struct bdi_writeback *wb, struct backing_dev_info *bdi, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff81287130)
Location: mm/backing-dev.c:279
Inline: False
Direct callers:
  - mm/backing-dev.c:cgwb_bdi_init
  - mm/backing-dev.c:cgwb_create
```
**Symbols:**

```
ffffffff81287130-ffffffff812873ab: wb_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int wb_init(struct bdi_writeback *wb, struct backing_dev_info *bdi, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff812c69d0)
Location: mm/backing-dev.c:287
Inline: False
Direct callers:
  - mm/backing-dev.c:cgwb_bdi_init
  - mm/backing-dev.c:cgwb_create
```
**Symbols:**

```
ffffffff812c69d0-ffffffff812c6d27: wb_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int wb_init(struct bdi_writeback *wb, struct backing_dev_info *bdi, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff81322bf0)
Location: mm/backing-dev.c:282
Inline: False
Direct callers:
  - mm/backing-dev.c:bdi_init
  - mm/backing-dev.c:cgwb_create
```
**Symbols:**

```
ffffffff81322bf0-ffffffff81322e64: wb_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int wb_init(struct bdi_writeback *wb, struct backing_dev_info *bdi, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff813973d0)
Location: mm/backing-dev.c:409
Inline: False
Direct callers:
  - mm/backing-dev.c:bdi_init
  - mm/backing-dev.c:cgwb_create
```
**Symbols:**

```
ffffffff813973d0-ffffffff81397644: wb_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int wb_init(struct bdi_writeback *wb, struct backing_dev_info *bdi, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff813ca360)
Location: mm/backing-dev.c:414
Inline: False
Direct callers:
  - mm/backing-dev.c:bdi_init
  - mm/backing-dev.c:cgwb_create
```
**Symbols:**

```
ffffffff813ca360-ffffffff813ca5d4: wb_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int wb_init(struct bdi_writeback *wb, struct backing_dev_info *bdi, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff813f4cf0)
Location: mm/backing-dev.c:413
Inline: False
Direct callers:
  - mm/backing-dev.c:bdi_init
  - mm/backing-dev.c:cgwb_create
```
**Symbols:**

```
ffffffff813f4cf0-ffffffff813f4f60: wb_init (STB_LOCAL)
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
int wb_init(struct bdi_writeback *wb, struct backing_dev_info *bdi, int blkcg_id, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffff8000102df008)
Location: mm/backing-dev.c:284
Inline: False
Direct callers:
  - mm/backing-dev.c:cgwb_bdi_init
  - mm/backing-dev.c:wb_get_create
```
**Symbols:**

```
ffff8000102df008-ffff8000102df20c: wb_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int wb_init(struct bdi_writeback *wb, struct backing_dev_info *bdi, int blkcg_id, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (c0503e80)
Location: mm/backing-dev.c:284
Inline: False
Direct callers:
  - mm/backing-dev.c:cgwb_bdi_init
  - mm/backing-dev.c:wb_get_create
```
**Symbols:**

```
c0503e80-c0504078: wb_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int wb_init(struct bdi_writeback *wb, struct backing_dev_info *bdi, int blkcg_id, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (c00000000039e980)
Location: mm/backing-dev.c:284
Inline: False
Direct callers:
  - mm/backing-dev.c:cgwb_bdi_init
  - mm/backing-dev.c:wb_get_create
```
**Symbols:**

```
c00000000039e980-c00000000039ec28: wb_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int wb_init(struct bdi_writeback *wb, struct backing_dev_info *bdi, int blkcg_id, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffe0001f6e00)
Location: mm/backing-dev.c:284
Inline: False
Direct callers:
  - mm/backing-dev.c:cgwb_bdi_init
  - mm/backing-dev.c:wb_get_create
```
**Symbols:**

```
ffffffe0001f6e00-ffffffe0001f6fda: wb_init (STB_LOCAL)
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
int wb_init(struct bdi_writeback *wb, struct backing_dev_info *bdi, int blkcg_id, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff81241de0)
Location: mm/backing-dev.c:284
Inline: False
Direct callers:
  - mm/backing-dev.c:cgwb_bdi_init
  - mm/backing-dev.c:wb_get_create
```
**Symbols:**

```
ffffffff81241de0-ffffffff81242042: wb_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int wb_init(struct bdi_writeback *wb, struct backing_dev_info *bdi, int blkcg_id, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff81234db0)
Location: mm/backing-dev.c:284
Inline: False
Direct callers:
  - mm/backing-dev.c:cgwb_bdi_init
  - mm/backing-dev.c:wb_get_create
```
**Symbols:**

```
ffffffff81234db0-ffffffff81235012: wb_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int wb_init(struct bdi_writeback *wb, struct backing_dev_info *bdi, int blkcg_id, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff8123fb80)
Location: mm/backing-dev.c:284
Inline: False
Direct callers:
  - mm/backing-dev.c:cgwb_bdi_init
  - mm/backing-dev.c:wb_get_create
```
**Symbols:**

```
ffffffff8123fb80-ffffffff8123fde2: wb_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int wb_init(struct bdi_writeback *wb, struct backing_dev_info *bdi, int blkcg_id, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff8124f2e0)
Location: mm/backing-dev.c:284
Inline: False
Direct callers:
  - mm/backing-dev.c:cgwb_bdi_init
  - mm/backing-dev.c:wb_get_create
```
**Symbols:**

```
ffffffff8124f2e0-ffffffff8124f542: wb_init (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int blkcg_id</code>
</li>
<li>
<b>Param reordered. </b>
<code>wb, bdi, blkcg_id, gfp</code> ➡️ <code>wb, bdi, gfp</code>
</li>
</ul>
</details>
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
