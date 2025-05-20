# Function: <code>blk_init_rl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int blk_init_rl(struct request_list *rl, struct request_queue *q, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813b9760)
Location: block/blk-core.c:615
Inline: False
Direct callers:
  - block/blk-core.c:blk_init_allocated_queue
  - block/blk-cgroup.c:blkg_alloc
```
**Symbols:**

```
ffffffff813b9760-ffffffff813b9811: blk_init_rl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int blk_init_rl(struct request_list *rl, struct request_queue *q, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813fd520)
Location: block/blk-core.c:617
Inline: False
Direct callers:
  - block/blk-core.c:blk_init_allocated_queue
  - block/blk-cgroup.c:blkg_alloc
```
**Symbols:**

```
ffffffff813fd520-ffffffff813fd5d1: blk_init_rl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int blk_init_rl(struct request_list *rl, struct request_queue *q, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81416e70)
Location: block/blk-core.c:618
Inline: False
Direct callers:
  - block/blk-core.c:blk_init_allocated_queue
  - block/blk-cgroup.c:blkg_alloc
```
**Symbols:**

```
ffffffff81416e70-ffffffff81416f21: blk_init_rl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int blk_init_rl(struct request_list *rl, struct request_queue *q, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81424b10)
Location: block/blk-core.c:718
Inline: False
Direct callers:
  - block/blk-core.c:blk_init_allocated_queue
  - block/blk-cgroup.c:blkg_alloc
```
**Symbols:**

```
ffffffff81424b10-ffffffff81424c0c: blk_init_rl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int blk_init_rl(struct request_list *rl, struct request_queue *q, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-core.c (ffffffff8144d277)
Location: block/blk-core.c:768
Inline: True
Inline callers:
  - block/blk-core.c:blk_init_allocated_queue
Direct callers:
  - block/blk-core.c:blk_init_allocated_queue
  - block/blk-cgroup.c:blkg_alloc
```
**Symbols:**

```
ffffffff8144d120-ffffffff8144d20a: blk_init_rl.part.84 (STB_LOCAL)
ffffffff8144fc30-ffffffff8144fc57: blk_init_rl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int blk_init_rl(struct request_list *rl, struct request_queue *q, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-core.c (ffffffff814804f3)
Location: block/blk-core.c:868
Inline: True
Inline callers:
  - block/blk-core.c:blk_init_allocated_queue
Direct callers:
  - block/blk-core.c:blk_init_allocated_queue
  - block/blk-cgroup.c:blkg_alloc
```
**Symbols:**

```
ffffffff814803a0-ffffffff8148048b: blk_init_rl.part.82 (STB_LOCAL)
ffffffff81482e60-ffffffff81482e85: blk_init_rl (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
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
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
</ul>
