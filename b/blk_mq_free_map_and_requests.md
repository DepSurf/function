# Function: <code>blk_mq_free_map_and_requests</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void blk_mq_free_map_and_requests(struct blk_mq_tag_set *set, unsigned int hctx_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81432160)
Location: block/blk-mq.c:2036
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_free_tag_set
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_map_swqueue
```
**Symbols:**

```
ffffffff81432160-ffffffff814321a5: blk_mq_free_map_and_requests (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void blk_mq_free_map_and_requests(struct blk_mq_tag_set *set, unsigned int hctx_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8145dc90)
Location: block/blk-mq.c:2174
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_free_tag_set
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_map_swqueue
```
**Symbols:**

```
ffffffff8145dc90-ffffffff8145dcd5: blk_mq_free_map_and_requests (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void blk_mq_free_map_and_requests(struct blk_mq_tag_set *set, unsigned int hctx_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81491580)
Location: block/blk-mq.c:2236
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_free_tag_set
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_map_swqueue
```
**Symbols:**

```
ffffffff81491580-ffffffff814915c5: blk_mq_free_map_and_requests (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void blk_mq_free_map_and_requests(struct blk_mq_tag_set *set, unsigned int hctx_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814ab030)
Location: block/blk-mq.c:2402
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_free_tag_set
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_map_swqueue
```
**Symbols:**

```
ffffffff814ab030-ffffffff814ab07d: blk_mq_free_map_and_requests (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void blk_mq_free_map_and_requests(struct blk_mq_tag_set *set, unsigned int hctx_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d9170)
Location: block/blk-mq.c:2439
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_map_swqueue
```
**Symbols:**

```
ffffffff814d9170-ffffffff814d91ba: blk_mq_free_map_and_requests (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void blk_mq_free_map_and_requests(struct blk_mq_tag_set *set, unsigned int hctx_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814f2530)
Location: block/blk-mq.c:2465
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_map_swqueue
```
**Symbols:**

```
ffffffff814f2530-ffffffff814f257a: blk_mq_free_map_and_requests (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_free_map_and_requests(struct blk_mq_tag_set *set, unsigned int hctx_idx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81552fdd)
Location: block/blk-mq.c:2657
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_free_tag_set
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_map_and_requests
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_map_swqueue
```
**Symbols:**

```
ffffffff81552d70-ffffffff81552df3: blk_mq_free_map_and_requests (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_free_map_and_requests(struct blk_mq_tag_set *set, unsigned int hctx_idx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8156f637)
Location: block/blk-mq.c:2760
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_free_tag_set
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_alloc_map_and_requests
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_map_swqueue
```
**Symbols:**

```
ffffffff8156f3a0-ffffffff8156f43b: blk_mq_free_map_and_requests (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_free_map_and_requests(struct blk_mq_tag_set *set, unsigned int hctx_idx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff815774e7)
Location: block/blk-mq.c:2820
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_free_tag_set
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_map_swqueue
```
**Symbols:**

```
ffffffff81577050-ffffffff815770eb: blk_mq_free_map_and_requests (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void blk_mq_free_map_and_requests(struct blk_mq_tag_set *set, unsigned int hctx_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff815dbdb0)
Location: block/blk-mq.c:2876
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_free_tag_set
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_map_swqueue
```
**Symbols:**

```
ffffffff815dbdb0-ffffffff815dbe4b: blk_mq_free_map_and_requests (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void blk_mq_free_map_and_requests(struct blk_mq_tag_set *set, unsigned int hctx_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffff8000105f1db0)
Location: block/blk-mq.c:2465
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_map_swqueue
```
**Symbols:**

```
ffff8000105f1db0-ffff8000105f1e24: blk_mq_free_map_and_requests (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void blk_mq_free_map_and_requests(struct blk_mq_tag_set *set, unsigned int hctx_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c079de90)
Location: block/blk-mq.c:2465
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_map_swqueue
```
**Symbols:**

```
c079de90-c079dee8: blk_mq_free_map_and_requests (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void blk_mq_free_map_and_requests(struct blk_mq_tag_set *set, unsigned int hctx_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c000000000788db0)
Location: block/blk-mq.c:2465
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_map_swqueue
```
**Symbols:**

```
c000000000788db0-c000000000788e2c: blk_mq_free_map_and_requests (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void blk_mq_free_map_and_requests(struct blk_mq_tag_set *set, unsigned int hctx_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffe000430748)
Location: block/blk-mq.c:2465
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_map_swqueue
```
**Symbols:**

```
ffffffe000430748-ffffffe0004307a6: blk_mq_free_map_and_requests (STB_LOCAL)
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
void blk_mq_free_map_and_requests(struct blk_mq_tag_set *set, unsigned int hctx_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814eab10)
Location: block/blk-mq.c:2465
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_map_swqueue
```
**Symbols:**

```
ffffffff814eab10-ffffffff814eab5a: blk_mq_free_map_and_requests (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void blk_mq_free_map_and_requests(struct blk_mq_tag_set *set, unsigned int hctx_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814db060)
Location: block/blk-mq.c:2465
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_map_swqueue
```
**Symbols:**

```
ffffffff814db060-ffffffff814db0aa: blk_mq_free_map_and_requests (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void blk_mq_free_map_and_requests(struct blk_mq_tag_set *set, unsigned int hctx_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e6ba0)
Location: block/blk-mq.c:2465
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_map_swqueue
```
**Symbols:**

```
ffffffff814e6ba0-ffffffff814e6bea: blk_mq_free_map_and_requests (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void blk_mq_free_map_and_requests(struct blk_mq_tag_set *set, unsigned int hctx_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814ffb50)
Location: block/blk-mq.c:2465
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_map_swqueue
```
**Symbols:**

```
ffffffff814ffb50-ffffffff814ffb9a: blk_mq_free_map_and_requests (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
