# Function: <code>wakeup_flusher_threads_bdi</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void wakeup_flusher_threads_bdi(struct backing_dev_info *bdi, enum wb_reason reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812a7c20)
Location: fs/fs-writeback.c:1986
Inline: False
Direct callers:
  - mm/page-writeback.c:laptop_mode_timer_fn
```
**Symbols:**

```
ffffffff812a7c20-ffffffff812a7c3b: wakeup_flusher_threads_bdi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void wakeup_flusher_threads_bdi(struct backing_dev_info *bdi, enum wb_reason reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812ce7b0)
Location: fs/fs-writeback.c:1987
Inline: False
Direct callers:
  - mm/page-writeback.c:laptop_mode_timer_fn
```
**Symbols:**

```
ffffffff812ce7b0-ffffffff812ce7ca: wakeup_flusher_threads_bdi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void wakeup_flusher_threads_bdi(struct backing_dev_info *bdi, enum wb_reason reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812e3ab0)
Location: fs/fs-writeback.c:2013
Inline: False
Direct callers:
  - mm/page-writeback.c:laptop_mode_timer_fn
```
**Symbols:**

```
ffffffff812e3ab0-ffffffff812e3b0b: wakeup_flusher_threads_bdi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void wakeup_flusher_threads_bdi(struct backing_dev_info *bdi, enum wb_reason reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81302250)
Location: fs/fs-writeback.c:2028
Inline: False
Direct callers:
  - mm/page-writeback.c:laptop_mode_timer_fn
```
**Symbols:**

```
ffffffff81302250-ffffffff813022aa: wakeup_flusher_threads_bdi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void wakeup_flusher_threads_bdi(struct backing_dev_info *bdi, enum wb_reason reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81315360)
Location: fs/fs-writeback.c:2116
Inline: False
Direct callers:
  - mm/page-writeback.c:laptop_mode_timer_fn
```
**Symbols:**

```
ffffffff81315360-ffffffff813153ba: wakeup_flusher_threads_bdi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void wakeup_flusher_threads_bdi(struct backing_dev_info *bdi, enum wb_reason reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8134eb40)
Location: fs/fs-writeback.c:2124
Inline: False
Direct callers:
  - mm/page-writeback.c:laptop_mode_timer_fn
```
**Symbols:**

```
ffffffff8134eb40-ffffffff8134ebf2: wakeup_flusher_threads_bdi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void wakeup_flusher_threads_bdi(struct backing_dev_info *bdi, enum wb_reason reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8135b9c0)
Location: fs/fs-writeback.c:2120
Inline: False
Direct callers:
  - mm/page-writeback.c:laptop_mode_timer_fn
```
**Symbols:**

```
ffffffff8135b9c0-ffffffff8135ba72: wakeup_flusher_threads_bdi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void wakeup_flusher_threads_bdi(struct backing_dev_info *bdi, enum wb_reason reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff813625d0)
Location: fs/fs-writeback.c:2135
Inline: False
Direct callers:
  - mm/page-writeback.c:laptop_mode_timer_fn
```
**Symbols:**

```
ffffffff813625d0-ffffffff81362682: wakeup_flusher_threads_bdi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void wakeup_flusher_threads_bdi(struct backing_dev_info *bdi, enum wb_reason reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff813b0dd0)
Location: fs/fs-writeback.c:2275
Inline: False
Direct callers:
  - mm/page-writeback.c:laptop_mode_timer_fn
```
**Symbols:**

```
ffffffff813b0dd0-ffffffff813b0e82: wakeup_flusher_threads_bdi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void wakeup_flusher_threads_bdi(struct backing_dev_info *bdi, enum wb_reason reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81435c70)
Location: fs/fs-writeback.c:2258
Inline: False
Direct callers:
  - mm/page-writeback.c:laptop_mode_timer_fn
```
**Symbols:**

```
ffffffff81435c70-ffffffff81435d3a: wakeup_flusher_threads_bdi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void wakeup_flusher_threads_bdi(struct backing_dev_info *bdi, enum wb_reason reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff814c3cc0)
Location: fs/fs-writeback.c:2282
Inline: False
Direct callers:
  - mm/page-writeback.c:laptop_mode_timer_fn
```
**Symbols:**

```
ffffffff814c3cc0-ffffffff814c3d32: wakeup_flusher_threads_bdi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void wakeup_flusher_threads_bdi(struct backing_dev_info *bdi, enum wb_reason reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff814f90b0)
Location: fs/fs-writeback.c:2293
Inline: False
Direct callers:
  - mm/page-writeback.c:laptop_mode_timer_fn
```
**Symbols:**

```
ffffffff814f90b0-ffffffff814f9122: wakeup_flusher_threads_bdi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void wakeup_flusher_threads_bdi(struct backing_dev_info *bdi, enum wb_reason reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8152d910)
Location: fs/fs-writeback.c:2315
Inline: False
Direct callers:
  - mm/page-writeback.c:laptop_mode_timer_fn
```
**Symbols:**

```
ffffffff8152d910-ffffffff8152d982: wakeup_flusher_threads_bdi (STB_GLOBAL)
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
void wakeup_flusher_threads_bdi(struct backing_dev_info *bdi, enum wb_reason reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffff8000103cb5e0)
Location: fs/fs-writeback.c:2116
Inline: False
Direct callers:
  - mm/page-writeback.c:laptop_mode_timer_fn
```
**Symbols:**

```
ffff8000103cb5e0-ffff8000103cb61c: wakeup_flusher_threads_bdi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void wakeup_flusher_threads_bdi(struct backing_dev_info *bdi, enum wb_reason reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (c05a7a0c)
Location: fs/fs-writeback.c:2116
Inline: False
Direct callers:
  - mm/page-writeback.c:laptop_mode_timer_fn
```
**Symbols:**

```
c05a7a0c-c05a7a34: wakeup_flusher_threads_bdi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void wakeup_flusher_threads_bdi(struct backing_dev_info *bdi, enum wb_reason reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (c0000000004cd220)
Location: fs/fs-writeback.c:2116
Inline: False
Direct callers:
  - mm/page-writeback.c:laptop_mode_timer_fn
```
**Symbols:**

```
c0000000004cd220-c0000000004cd2b4: wakeup_flusher_threads_bdi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void wakeup_flusher_threads_bdi(struct backing_dev_info *bdi, enum wb_reason reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffe000289444)
Location: fs/fs-writeback.c:2116
Inline: False
Direct callers:
  - mm/page-writeback.c:laptop_mode_timer_fn
```
**Symbols:**

```
ffffffe000289444-ffffffe00028947a: wakeup_flusher_threads_bdi (STB_GLOBAL)
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
void wakeup_flusher_threads_bdi(struct backing_dev_info *bdi, enum wb_reason reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8130d940)
Location: fs/fs-writeback.c:2116
Inline: False
Direct callers:
  - mm/page-writeback.c:laptop_mode_timer_fn
```
**Symbols:**

```
ffffffff8130d940-ffffffff8130d99a: wakeup_flusher_threads_bdi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void wakeup_flusher_threads_bdi(struct backing_dev_info *bdi, enum wb_reason reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812fe550)
Location: fs/fs-writeback.c:2116
Inline: False
Direct callers:
  - mm/page-writeback.c:laptop_mode_timer_fn
```
**Symbols:**

```
ffffffff812fe550-ffffffff812fe5aa: wakeup_flusher_threads_bdi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void wakeup_flusher_threads_bdi(struct backing_dev_info *bdi, enum wb_reason reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8130b730)
Location: fs/fs-writeback.c:2116
Inline: False
Direct callers:
  - mm/page-writeback.c:laptop_mode_timer_fn
```
**Symbols:**

```
ffffffff8130b730-ffffffff8130b78a: wakeup_flusher_threads_bdi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void wakeup_flusher_threads_bdi(struct backing_dev_info *bdi, enum wb_reason reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8131cf40)
Location: fs/fs-writeback.c:2116
Inline: False
Direct callers:
  - mm/page-writeback.c:laptop_mode_timer_fn
```
**Symbols:**

```
ffffffff8131cf40-ffffffff8131cfa6: wakeup_flusher_threads_bdi (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
