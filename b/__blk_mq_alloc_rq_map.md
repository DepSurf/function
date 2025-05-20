# Function: <code>__blk_mq_alloc_rq_map</code>

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
bool __blk_mq_alloc_rq_map(struct blk_mq_tag_set *set, int hctx_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81432920)
Location: block/blk-mq.c:2017
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_map_swqueue
```
**Symbols:**

```
ffffffff81432920-ffffffff814329a4: __blk_mq_alloc_rq_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool __blk_mq_alloc_rq_map(struct blk_mq_tag_set *set, int hctx_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8145e4f0)
Location: block/blk-mq.c:2155
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_map_swqueue
```
**Symbols:**

```
ffffffff8145e4f0-ffffffff8145e574: __blk_mq_alloc_rq_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool __blk_mq_alloc_rq_map(struct blk_mq_tag_set *set, int hctx_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81491e20)
Location: block/blk-mq.c:2217
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_map_swqueue
```
**Symbols:**

```
ffffffff81491e20-ffffffff81491ea6: __blk_mq_alloc_rq_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool __blk_mq_alloc_rq_map(struct blk_mq_tag_set *set, int hctx_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814ab890)
Location: block/blk-mq.c:2383
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_map_swqueue
```
**Symbols:**

```
ffffffff814ab890-ffffffff814ab916: __blk_mq_alloc_rq_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool __blk_mq_alloc_rq_map(struct blk_mq_tag_set *set, int hctx_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d9a80)
Location: block/blk-mq.c:2420
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_map_swqueue
```
**Symbols:**

```
ffffffff814d9a80-ffffffff814d9b06: __blk_mq_alloc_rq_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool __blk_mq_alloc_rq_map(struct blk_mq_tag_set *set, int hctx_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814f2e40)
Location: block/blk-mq.c:2446
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_map_swqueue
```
**Symbols:**

```
ffffffff814f2e40-ffffffff814f2ec6: __blk_mq_alloc_rq_map (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
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
bool __blk_mq_alloc_rq_map(struct blk_mq_tag_set *set, int hctx_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffff8000105f2670)
Location: block/blk-mq.c:2446
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_map_swqueue
```
**Symbols:**

```
ffff8000105f2670-ffff8000105f2724: __blk_mq_alloc_rq_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool __blk_mq_alloc_rq_map(struct blk_mq_tag_set *set, int hctx_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c079e76c)
Location: block/blk-mq.c:2446
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_map_swqueue
```
**Symbols:**

```
c079e76c-c079e7f0: __blk_mq_alloc_rq_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool __blk_mq_alloc_rq_map(struct blk_mq_tag_set *set, int hctx_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c0000000007899c0)
Location: block/blk-mq.c:2446
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_map_swqueue
```
**Symbols:**

```
c0000000007899c0-c000000000789ab0: __blk_mq_alloc_rq_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool __blk_mq_alloc_rq_map(struct blk_mq_tag_set *set, int hctx_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffe000430f00)
Location: block/blk-mq.c:2446
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_map_swqueue
```
**Symbols:**

```
ffffffe000430f00-ffffffe000430f94: __blk_mq_alloc_rq_map (STB_LOCAL)
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
bool __blk_mq_alloc_rq_map(struct blk_mq_tag_set *set, int hctx_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814eb420)
Location: block/blk-mq.c:2446
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_map_swqueue
```
**Symbols:**

```
ffffffff814eb420-ffffffff814eb4a6: __blk_mq_alloc_rq_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool __blk_mq_alloc_rq_map(struct blk_mq_tag_set *set, int hctx_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814db970)
Location: block/blk-mq.c:2446
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_map_swqueue
```
**Symbols:**

```
ffffffff814db970-ffffffff814db9f6: __blk_mq_alloc_rq_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool __blk_mq_alloc_rq_map(struct blk_mq_tag_set *set, int hctx_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e74b0)
Location: block/blk-mq.c:2446
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_map_swqueue
```
**Symbols:**

```
ffffffff814e74b0-ffffffff814e7536: __blk_mq_alloc_rq_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool __blk_mq_alloc_rq_map(struct blk_mq_tag_set *set, int hctx_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81500450)
Location: block/blk-mq.c:2446
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_map_swqueue
```
**Symbols:**

```
ffffffff81500450-ffffffff815004d6: __blk_mq_alloc_rq_map (STB_LOCAL)
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
