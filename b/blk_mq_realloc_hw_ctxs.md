# Function: <code>blk_mq_realloc_hw_ctxs</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void blk_mq_realloc_hw_ctxs(struct blk_mq_tag_set *set, struct request_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81407940)
Location: block/blk-mq.c:2003
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
**Symbols:**

```
ffffffff81407940-ffffffff81407e68: blk_mq_realloc_hw_ctxs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void blk_mq_realloc_hw_ctxs(struct blk_mq_tag_set *set, struct request_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81422600)
Location: block/blk-mq.c:2049
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
**Symbols:**

```
ffffffff81422600-ffffffff81422b0b: blk_mq_realloc_hw_ctxs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void blk_mq_realloc_hw_ctxs(struct blk_mq_tag_set *set, struct request_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814321b0)
Location: block/blk-mq.c:2262
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
**Symbols:**

```
ffffffff814321b0-ffffffff814325ad: blk_mq_realloc_hw_ctxs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void blk_mq_realloc_hw_ctxs(struct blk_mq_tag_set *set, struct request_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8145dce0)
Location: block/blk-mq.c:2403
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
**Symbols:**

```
ffffffff8145dce0-ffffffff8145e177: blk_mq_realloc_hw_ctxs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void blk_mq_realloc_hw_ctxs(struct blk_mq_tag_set *set, struct request_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814915d0)
Location: block/blk-mq.c:2465
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
**Symbols:**

```
ffffffff814915d0-ffffffff81491aaf: blk_mq_realloc_hw_ctxs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void blk_mq_realloc_hw_ctxs(struct blk_mq_tag_set *set, struct request_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (0)
Location: block/blk-mq.c:2734
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
**Symbols:**

```
ffffffff814ab080-ffffffff814ab4e3: blk_mq_realloc_hw_ctxs (STB_LOCAL)
ffffffff814ac9c8-ffffffff814ac9e2: blk_mq_realloc_hw_ctxs.cold.79 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void blk_mq_realloc_hw_ctxs(struct blk_mq_tag_set *set, struct request_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (0)
Location: block/blk-mq.c:2767
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
**Symbols:**

```
ffffffff814d91c0-ffffffff814d96d6: blk_mq_realloc_hw_ctxs (STB_LOCAL)
ffffffff814dacba-ffffffff814dacd4: blk_mq_realloc_hw_ctxs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void blk_mq_realloc_hw_ctxs(struct blk_mq_tag_set *set, struct request_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (0)
Location: block/blk-mq.c:2790
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
**Symbols:**

```
ffffffff814f2580-ffffffff814f2a96: blk_mq_realloc_hw_ctxs (STB_LOCAL)
ffffffff814f4063-ffffffff814f407d: blk_mq_realloc_hw_ctxs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void blk_mq_realloc_hw_ctxs(struct blk_mq_tag_set *set, struct request_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (0)
Location: block/blk-mq.c:2990
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
**Symbols:**

```
ffffffff81552e00-ffffffff81552fb5: blk_mq_realloc_hw_ctxs (STB_LOCAL)
ffffffff815546cf-ffffffff815546e9: blk_mq_realloc_hw_ctxs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void blk_mq_realloc_hw_ctxs(struct blk_mq_tag_set *set, struct request_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (0)
Location: block/blk-mq.c:3095
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
**Symbols:**

```
ffffffff8156f440-ffffffff8156f606: blk_mq_realloc_hw_ctxs (STB_LOCAL)
ffffffff81bf279d-ffffffff81bf27b7: blk_mq_realloc_hw_ctxs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void blk_mq_realloc_hw_ctxs(struct blk_mq_tag_set *set, struct request_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (0)
Location: block/blk-mq.c:3155
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
**Symbols:**

```
ffffffff815770f0-ffffffff815774b8: blk_mq_realloc_hw_ctxs (STB_LOCAL)
ffffffff81be4764-ffffffff81be477d: blk_mq_realloc_hw_ctxs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void blk_mq_realloc_hw_ctxs(struct blk_mq_tag_set *set, struct request_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (0)
Location: block/blk-mq.c:3194
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
**Symbols:**

```
ffffffff815dbe50-ffffffff815dc218: blk_mq_realloc_hw_ctxs (STB_LOCAL)
ffffffff81cd857c-ffffffff81cd8595: blk_mq_realloc_hw_ctxs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void blk_mq_realloc_hw_ctxs(struct blk_mq_tag_set *set, struct request_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (0)
Location: block/blk-mq.c:3964
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
**Symbols:**

```
ffffffff81686a40-ffffffff81686bcb: blk_mq_realloc_hw_ctxs (STB_LOCAL)
ffffffff81e8ba94-ffffffff81e8bac7: blk_mq_realloc_hw_ctxs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void blk_mq_realloc_hw_ctxs(struct blk_mq_tag_set *set, struct request_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81745320)
Location: block/blk-mq.c:4171
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
**Symbols:**

```
ffffffff81745320-ffffffff817455c5: blk_mq_realloc_hw_ctxs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void blk_mq_realloc_hw_ctxs(struct blk_mq_tag_set *set, struct request_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81781290)
Location: block/blk-mq.c:4183
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
**Symbols:**

```
ffffffff81781290-ffffffff81781543: blk_mq_realloc_hw_ctxs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void blk_mq_realloc_hw_ctxs(struct blk_mq_tag_set *set, struct request_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff817c3af0)
Location: block/blk-mq.c:4199
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
**Symbols:**

```
ffffffff817c3af0-ffffffff817c3da3: blk_mq_realloc_hw_ctxs (STB_LOCAL)
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
void blk_mq_realloc_hw_ctxs(struct blk_mq_tag_set *set, struct request_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffff8000105f1e28)
Location: block/blk-mq.c:2790
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
**Symbols:**

```
ffff8000105f1e28-ffff8000105f22b4: blk_mq_realloc_hw_ctxs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void blk_mq_realloc_hw_ctxs(struct blk_mq_tag_set *set, struct request_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c079dee8)
Location: block/blk-mq.c:2790
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
**Symbols:**

```
c079dee8-c079e3c0: blk_mq_realloc_hw_ctxs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void blk_mq_realloc_hw_ctxs(struct blk_mq_tag_set *set, struct request_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c000000000788e30)
Location: block/blk-mq.c:2790
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
**Symbols:**

```
c000000000788e30-c000000000789454: blk_mq_realloc_hw_ctxs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void blk_mq_realloc_hw_ctxs(struct blk_mq_tag_set *set, struct request_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffe0004307a6)
Location: block/blk-mq.c:2790
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
**Symbols:**

```
ffffffe0004307a6-ffffffe000430bd2: blk_mq_realloc_hw_ctxs (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void blk_mq_realloc_hw_ctxs(struct blk_mq_tag_set *set, struct request_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (0)
Location: block/blk-mq.c:2790
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
**Symbols:**

```
ffffffff814eab60-ffffffff814eb076: blk_mq_realloc_hw_ctxs (STB_LOCAL)
ffffffff814ec643-ffffffff814ec65d: blk_mq_realloc_hw_ctxs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void blk_mq_realloc_hw_ctxs(struct blk_mq_tag_set *set, struct request_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (0)
Location: block/blk-mq.c:2790
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
**Symbols:**

```
ffffffff814db0b0-ffffffff814db5c6: blk_mq_realloc_hw_ctxs (STB_LOCAL)
ffffffff814dcb93-ffffffff814dcbad: blk_mq_realloc_hw_ctxs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void blk_mq_realloc_hw_ctxs(struct blk_mq_tag_set *set, struct request_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (0)
Location: block/blk-mq.c:2790
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
**Symbols:**

```
ffffffff814e6bf0-ffffffff814e7106: blk_mq_realloc_hw_ctxs (STB_LOCAL)
ffffffff814e86d3-ffffffff814e86ed: blk_mq_realloc_hw_ctxs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void blk_mq_realloc_hw_ctxs(struct blk_mq_tag_set *set, struct request_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (0)
Location: block/blk-mq.c:2790
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
**Symbols:**

```
ffffffff814ffba0-ffffffff815000a8: blk_mq_realloc_hw_ctxs (STB_LOCAL)
ffffffff81501673-ffffffff8150168d: blk_mq_realloc_hw_ctxs.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
