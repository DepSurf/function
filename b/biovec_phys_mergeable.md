# Function: <code>biovec_phys_mergeable</code>

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
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81497641)
Location: block/blk.h:69
Inline: True
```
```
In block/blk-merge.c (ffffffff814a5328)
Location: block/blk.h:69
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:blk_rq_map_sg
  - block/blk-merge.c:__blk_recalc_rq_segments
  - block/blk-merge.c:blk_queue_split
```
```
In block/blk-integrity.c (ffffffff814ca75d)
Location: block/blk.h:69
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_rq_map_integrity_sg
  - block/blk-integrity.c:blk_rq_count_integrity_sg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff814d34d9)
Location: block/blk.h:67
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:__blk_bios_map_sg
```
```
In block/blk-integrity.c (ffffffff814f8fea)
Location: block/blk.h:67
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_rq_map_integrity_sg
  - block/blk-integrity.c:blk_rq_count_integrity_sg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff814ec809)
Location: block/blk.h:75
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:__blk_bios_map_sg
```
```
In block/blk-integrity.c (ffffffff81516ea6)
Location: block/blk.h:75
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_rq_map_integrity_sg
  - block/blk-integrity.c:blk_rq_count_integrity_sg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff8154c767)
Location: block/blk.h:66
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:__blk_bios_map_sg
```
```
In block/blk-integrity.c (ffffffff81577640)
Location: block/blk.h:66
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_rq_map_integrity_sg
  - block/blk-integrity.c:blk_rq_count_integrity_sg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff81567b6d)
Location: block/blk.h:58
Inline: True
Inline callers:
  - block/blk-merge.c:ll_merge_requests_fn
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:__blk_bios_map_sg
```
```
In block/blk-integrity.c (ffffffff8159421e)
Location: block/blk.h:58
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_rq_map_integrity_sg
  - block/blk-integrity.c:blk_rq_count_integrity_sg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff8156f89c)
Location: block/blk.h:64
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-merge.c:bio_will_gap
```
```
In block/blk-integrity.c (ffffffff8159b020)
Location: block/blk.h:64
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_rq_map_integrity_sg
  - block/blk-integrity.c:blk_rq_count_integrity_sg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff815d3f28)
Location: block/blk.h:62
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-merge.c:bio_will_gap
```
```
In block/blk-integrity.c (ffffffff8160327e)
Location: block/blk.h:62
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_rq_map_integrity_sg
  - block/blk-integrity.c:blk_rq_count_integrity_sg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff8167fd3f)
Location: block/blk.h:89
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-merge.c:bio_will_gap
```
```
In block/blk-integrity.c (ffffffff816b5ade)
Location: block/blk.h:89
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_rq_map_integrity_sg
  - block/blk-integrity.c:blk_rq_count_integrity_sg
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff8173d0e8)
Location: block/blk.h:79
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-merge.c:bio_will_gap
```
```
In block/blk-integrity.c (ffffffff81775da3)
Location: block/blk.h:79
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_rq_map_integrity_sg
  - block/blk-integrity.c:blk_rq_count_integrity_sg
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff81779683)
Location: block/blk.h:83
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-merge.c:bio_will_gap
```
```
In block/blk-integrity.c (ffffffff817b5a53)
Location: block/blk.h:83
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_rq_map_integrity_sg
  - block/blk-integrity.c:blk_rq_count_integrity_sg
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff817bba53)
Location: block/blk.h:82
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-merge.c:bio_will_gap
```
```
In block/blk-integrity.c (ffffffff817fa463)
Location: block/blk.h:82
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_rq_map_integrity_sg
  - block/blk-integrity.c:blk_rq_count_integrity_sg
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffff8000105eb278)
Location: block/blk.h:75
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:__blk_bios_map_sg
```
```
In block/blk-integrity.c (ffff80001061e2f0)
Location: block/blk.h:75
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_rq_map_integrity_sg
  - block/blk-integrity.c:blk_rq_count_integrity_sg
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (c0797770)
Location: block/blk.h:75
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:__blk_bios_map_sg
```
```
In block/blk-integrity.c (c07c5d3c)
Location: block/blk.h:75
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_rq_map_integrity_sg
  - block/blk-integrity.c:blk_rq_count_integrity_sg
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (c000000000780428)
Location: block/blk.h:75
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:__blk_bios_map_sg
```
```
In block/blk-integrity.c (c0000000007bd4f0)
Location: block/blk.h:75
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_rq_map_integrity_sg
  - block/blk-integrity.c:blk_rq_count_integrity_sg
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffe00042b170)
Location: block/blk.h:75
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:__blk_bios_map_sg
```
```
In block/blk-integrity.c (ffffffe000450e80)
Location: block/blk.h:75
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_rq_map_integrity_sg
  - block/blk-integrity.c:blk_rq_count_integrity_sg
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff814e4de9)
Location: block/blk.h:75
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:__blk_bios_map_sg
```
```
In block/blk-integrity.c (ffffffff8150f486)
Location: block/blk.h:75
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_rq_map_integrity_sg
  - block/blk-integrity.c:blk_rq_count_integrity_sg
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff814d5559)
Location: block/blk.h:75
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:__blk_bios_map_sg
```
```
In block/blk-integrity.c (ffffffff814ff8a5)
Location: block/blk.h:75
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_rq_map_integrity_sg
  - block/blk-integrity.c:blk_rq_count_integrity_sg
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff814e0e79)
Location: block/blk.h:75
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:__blk_bios_map_sg
```
```
In block/blk-integrity.c (ffffffff8150b516)
Location: block/blk.h:75
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_rq_map_integrity_sg
  - block/blk-integrity.c:blk_rq_count_integrity_sg
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff814f9cf9)
Location: block/blk.h:75
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:__blk_bios_map_sg
```
```
In block/blk-integrity.c (ffffffff81524bb6)
Location: block/blk.h:75
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_rq_map_integrity_sg
  - block/blk-integrity.c:blk_rq_count_integrity_sg
```
</details>
</li>
</ul>

## Differences
