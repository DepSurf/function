# Function: <code>blk_bvec_map_sg</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (0)
Location: block/blk-merge.c:345
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_bios_map_sg
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
In block/blk-merge.c (0)
Location: block/blk-merge.c:398
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_bios_map_sg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
unsigned int blk_bvec_map_sg(struct request_queue *q, struct bio_vec *bvec, struct scatterlist *sglist, struct scatterlist **sg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff8154aff0)
Location: block/blk-merge.c:407
Inline: False
Direct callers:
  - block/blk-merge.c:__blk_bios_map_sg
```
**Symbols:**

```
ffffffff8154aff0-ffffffff8154b104: blk_bvec_map_sg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
unsigned int blk_bvec_map_sg(struct request_queue *q, struct bio_vec *bvec, struct scatterlist *sglist, struct scatterlist **sg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff81566e80)
Location: block/blk-merge.c:423
Inline: False
Direct callers:
  - block/blk-merge.c:__blk_bios_map_sg
```
**Symbols:**

```
ffffffff81566e80-ffffffff81566f94: blk_bvec_map_sg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (0)
Location: block/blk-merge.c:422
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_bios_map_sg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (0)
Location: block/blk-merge.c:424
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_bios_map_sg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (0)
Location: block/blk-merge.c:424
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_bios_map_sg
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (0)
Location: block/blk-merge.c:461
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_bios_map_sg
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (0)
Location: block/blk-merge.c:462
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_bios_map_sg
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (0)
Location: block/blk-merge.c:458
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_bios_map_sg
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
In block/blk-merge.c (0)
Location: block/blk-merge.c:398
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_bios_map_sg
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
In block/blk-merge.c (0)
Location: block/blk-merge.c:398
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_bios_map_sg
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
In block/blk-merge.c (0)
Location: block/blk-merge.c:398
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_bios_map_sg
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
In block/blk-merge.c (ffffffe00042a1b2)
Location: block/blk-merge.c:398
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_bios_map_sg
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
In block/blk-merge.c (0)
Location: block/blk-merge.c:398
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_bios_map_sg
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
In block/blk-merge.c (0)
Location: block/blk-merge.c:398
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_bios_map_sg
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
In block/blk-merge.c (0)
Location: block/blk-merge.c:398
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_bios_map_sg
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
In block/blk-merge.c (0)
Location: block/blk-merge.c:398
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_bios_map_sg
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
</ul>
