# Function: <code>mem_cgroup_wb_stats</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void mem_cgroup_wb_stats(struct bdi_writeback *wb, long unsigned int *pfilepages, long unsigned int *pheadroom, long unsigned int *pdirty, long unsigned int *pwriteback);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff811fffc0)
Location: mm/memcontrol.c:3748
Inline: False
Direct callers:
  - mm/page-writeback.c:wb_over_bg_thresh
```
**Symbols:**

```
ffffffff811fffc0-ffffffff812000a8: mem_cgroup_wb_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void mem_cgroup_wb_stats(struct bdi_writeback *wb, long unsigned int *pfilepages, long unsigned int *pheadroom, long unsigned int *pdirty, long unsigned int *pwriteback);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81223d30)
Location: mm/memcontrol.c:3672
Inline: False
Direct callers:
  - mm/page-writeback.c:wb_over_bg_thresh
```
**Symbols:**

```
ffffffff81223d30-ffffffff81223e18: mem_cgroup_wb_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void mem_cgroup_wb_stats(struct bdi_writeback *wb, long unsigned int *pfilepages, long unsigned int *pheadroom, long unsigned int *pdirty, long unsigned int *pwriteback);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81236220)
Location: mm/memcontrol.c:3645
Inline: False
Direct callers:
  - mm/page-writeback.c:wb_over_bg_thresh
```
**Symbols:**

```
ffffffff81236220-ffffffff81236308: mem_cgroup_wb_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void mem_cgroup_wb_stats(struct bdi_writeback *wb, long unsigned int *pfilepages, long unsigned int *pheadroom, long unsigned int *pdirty, long unsigned int *pwriteback);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81241ca0)
Location: mm/memcontrol.c:3665
Inline: False
Direct callers:
  - mm/page-writeback.c:wb_over_bg_thresh
```
**Symbols:**

```
ffffffff81241ca0-ffffffff81241e16: mem_cgroup_wb_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void mem_cgroup_wb_stats(struct bdi_writeback *wb, long unsigned int *pfilepages, long unsigned int *pheadroom, long unsigned int *pdirty, long unsigned int *pwriteback);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812619f0)
Location: mm/memcontrol.c:3692
Inline: False
Direct callers:
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:balance_dirty_pages
```
**Symbols:**

```
ffffffff812619f0-ffffffff81261b4c: mem_cgroup_wb_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void mem_cgroup_wb_stats(struct bdi_writeback *wb, long unsigned int *pfilepages, long unsigned int *pheadroom, long unsigned int *pdirty, long unsigned int *pwriteback);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812859e0)
Location: mm/memcontrol.c:3619
Inline: False
Direct callers:
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:balance_dirty_pages
```
**Symbols:**

```
ffffffff812859e0-ffffffff81285aa8: mem_cgroup_wb_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void mem_cgroup_wb_stats(struct bdi_writeback *wb, long unsigned int *pfilepages, long unsigned int *pheadroom, long unsigned int *pdirty, long unsigned int *pwriteback);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8129a8f0)
Location: mm/memcontrol.c:3894
Inline: False
Direct callers:
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:balance_dirty_pages
```
**Symbols:**

```
ffffffff8129a8f0-ffffffff8129a9b8: mem_cgroup_wb_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void mem_cgroup_wb_stats(struct bdi_writeback *wb, long unsigned int *pfilepages, long unsigned int *pheadroom, long unsigned int *pdirty, long unsigned int *pwriteback);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812b5b80)
Location: mm/memcontrol.c:4234
Inline: False
Direct callers:
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:balance_dirty_pages
```
**Symbols:**

```
ffffffff812b5b80-ffffffff812b5c5a: mem_cgroup_wb_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void mem_cgroup_wb_stats(struct bdi_writeback *wb, long unsigned int *pfilepages, long unsigned int *pheadroom, long unsigned int *pdirty, long unsigned int *pwriteback);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812c7830)
Location: mm/memcontrol.c:4435
Inline: False
Direct callers:
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:balance_dirty_pages
  - fs/fs-writeback.c:cgroup_writeback_by_id
```
**Symbols:**

```
ffffffff812c7830-ffffffff812c790a: mem_cgroup_wb_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void mem_cgroup_wb_stats(struct bdi_writeback *wb, long unsigned int *pfilepages, long unsigned int *pheadroom, long unsigned int *pdirty, long unsigned int *pwriteback);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812fd1d0)
Location: mm/memcontrol.c:4315
Inline: False
Direct callers:
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:balance_dirty_pages
  - fs/fs-writeback.c:cgroup_writeback_by_id
```
**Symbols:**

```
ffffffff812fd1d0-ffffffff812fd3a0: mem_cgroup_wb_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void mem_cgroup_wb_stats(struct bdi_writeback *wb, long unsigned int *pfilepages, long unsigned int *pheadroom, long unsigned int *pdirty, long unsigned int *pwriteback);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81309630)
Location: mm/memcontrol.c:4580
Inline: False
Direct callers:
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:balance_dirty_pages
  - fs/fs-writeback.c:cgroup_writeback_by_id
```
**Symbols:**

```
ffffffff81309630-ffffffff8130981a: mem_cgroup_wb_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void mem_cgroup_wb_stats(struct bdi_writeback *wb, long unsigned int *pfilepages, long unsigned int *pheadroom, long unsigned int *pdirty, long unsigned int *pwriteback);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8130fd70)
Location: mm/memcontrol.c:4347
Inline: False
Direct callers:
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:balance_dirty_pages
  - fs/fs-writeback.c:cgroup_writeback_by_id
```
**Symbols:**

```
ffffffff8130fd70-ffffffff8130fe58: mem_cgroup_wb_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void mem_cgroup_wb_stats(struct bdi_writeback *wb, long unsigned int *pfilepages, long unsigned int *pheadroom, long unsigned int *pdirty, long unsigned int *pwriteback);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8135b020)
Location: mm/memcontrol.c:4514
Inline: False
Direct callers:
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:balance_dirty_pages
```
**Symbols:**

```
ffffffff8135b020-ffffffff8135b0fe: mem_cgroup_wb_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void mem_cgroup_wb_stats(struct bdi_writeback *wb, long unsigned int *pfilepages, long unsigned int *pheadroom, long unsigned int *pdirty, long unsigned int *pwriteback);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff813d46a0)
Location: mm/memcontrol.c:4465
Inline: False
Direct callers:
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:balance_dirty_pages
```
**Symbols:**

```
ffffffff813d46a0-ffffffff813d47a2: mem_cgroup_wb_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void mem_cgroup_wb_stats(struct bdi_writeback *wb, long unsigned int *pfilepages, long unsigned int *pheadroom, long unsigned int *pdirty, long unsigned int *pwriteback);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8145a0b0)
Location: mm/memcontrol.c:4575
Inline: False
Direct callers:
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:balance_dirty_pages
```
**Symbols:**

```
ffffffff8145a0b0-ffffffff8145a1c1: mem_cgroup_wb_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void mem_cgroup_wb_stats(struct bdi_writeback *wb, long unsigned int *pfilepages, long unsigned int *pheadroom, long unsigned int *pdirty, long unsigned int *pwriteback);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8148fd10)
Location: mm/memcontrol.c:4599
Inline: False
Direct callers:
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:balance_dirty_pages
```
**Symbols:**

```
ffffffff8148fd10-ffffffff8148fe21: mem_cgroup_wb_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void mem_cgroup_wb_stats(struct bdi_writeback *wb, long unsigned int *pfilepages, long unsigned int *pheadroom, long unsigned int *pdirty, long unsigned int *pwriteback);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff814bf540)
Location: mm/memcontrol.c:4796
Inline: False
Direct callers:
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:balance_dirty_pages
```
**Symbols:**

```
ffffffff814bf540-ffffffff814bf63d: mem_cgroup_wb_stats (STB_GLOBAL)
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
void mem_cgroup_wb_stats(struct bdi_writeback *wb, long unsigned int *pfilepages, long unsigned int *pheadroom, long unsigned int *pdirty, long unsigned int *pwriteback);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffff80001036a658)
Location: mm/memcontrol.c:4435
Inline: False
Direct callers:
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:balance_dirty_pages
  - fs/fs-writeback.c:cgroup_writeback_by_id
```
**Symbols:**

```
ffff80001036a658-ffff80001036a738: mem_cgroup_wb_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void mem_cgroup_wb_stats(struct bdi_writeback *wb, long unsigned int *pfilepages, long unsigned int *pheadroom, long unsigned int *pdirty, long unsigned int *pwriteback);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c055bb90)
Location: mm/memcontrol.c:4435
Inline: False
Direct callers:
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:balance_dirty_pages
  - fs/fs-writeback.c:cgroup_writeback_by_id
```
**Symbols:**

```
c055bb90-c055bc5c: mem_cgroup_wb_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void mem_cgroup_wb_stats(struct bdi_writeback *wb, long unsigned int *pfilepages, long unsigned int *pheadroom, long unsigned int *pdirty, long unsigned int *pwriteback);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c000000000459850)
Location: mm/memcontrol.c:4435
Inline: False
Direct callers:
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:balance_dirty_pages
  - fs/fs-writeback.c:cgroup_writeback_by_id
```
**Symbols:**

```
c000000000459850-c000000000459978: mem_cgroup_wb_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void mem_cgroup_wb_stats(struct bdi_writeback *wb, long unsigned int *pfilepages, long unsigned int *pheadroom, long unsigned int *pdirty, long unsigned int *pwriteback);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffe000247ecc)
Location: mm/memcontrol.c:4435
Inline: False
Direct callers:
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:balance_dirty_pages
  - fs/fs-writeback.c:cgroup_writeback_by_id
```
**Symbols:**

```
ffffffe000247ecc-ffffffe000247f88: mem_cgroup_wb_stats (STB_GLOBAL)
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
void mem_cgroup_wb_stats(struct bdi_writeback *wb, long unsigned int *pfilepages, long unsigned int *pheadroom, long unsigned int *pdirty, long unsigned int *pwriteback);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812bfe10)
Location: mm/memcontrol.c:4435
Inline: False
Direct callers:
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:balance_dirty_pages
  - fs/fs-writeback.c:cgroup_writeback_by_id
```
**Symbols:**

```
ffffffff812bfe10-ffffffff812bfeea: mem_cgroup_wb_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void mem_cgroup_wb_stats(struct bdi_writeback *wb, long unsigned int *pfilepages, long unsigned int *pheadroom, long unsigned int *pdirty, long unsigned int *pwriteback);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812b0ee0)
Location: mm/memcontrol.c:4435
Inline: False
Direct callers:
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:balance_dirty_pages
  - fs/fs-writeback.c:cgroup_writeback_by_id
```
**Symbols:**

```
ffffffff812b0ee0-ffffffff812b0fba: mem_cgroup_wb_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void mem_cgroup_wb_stats(struct bdi_writeback *wb, long unsigned int *pfilepages, long unsigned int *pheadroom, long unsigned int *pdirty, long unsigned int *pwriteback);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812bdc20)
Location: mm/memcontrol.c:4435
Inline: False
Direct callers:
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:balance_dirty_pages
  - fs/fs-writeback.c:cgroup_writeback_by_id
```
**Symbols:**

```
ffffffff812bdc20-ffffffff812bdcfa: mem_cgroup_wb_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void mem_cgroup_wb_stats(struct bdi_writeback *wb, long unsigned int *pfilepages, long unsigned int *pheadroom, long unsigned int *pdirty, long unsigned int *pwriteback);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812ce580)
Location: mm/memcontrol.c:4435
Inline: False
Direct callers:
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:balance_dirty_pages
  - fs/fs-writeback.c:cgroup_writeback_by_id
```
**Symbols:**

```
ffffffff812ce580-ffffffff812ce65a: mem_cgroup_wb_stats (STB_GLOBAL)
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
