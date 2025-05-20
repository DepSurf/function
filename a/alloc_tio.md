# Function: <code>alloc_tio</code>

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
In drivers/md/dm.c (ffffffff816a0d9b)
Location: drivers/md/dm.c:1542
Inline: True
Inline callers:
  - drivers/md/dm.c:__clone_and_map_simple_bio
  - drivers/md/dm.c:__split_and_process_bio
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
In drivers/md/dm.c (ffffffff81703313)
Location: drivers/md/dm.c:1049
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:__clone_and_map_simple_bio
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
In drivers/md/dm.c (ffffffff817351e0)
Location: drivers/md/dm.c:1104
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:__clone_and_map_simple_bio
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
In drivers/md/dm.c (ffffffff8174d411)
Location: drivers/md/dm.c:1277
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__clone_and_map_simple_bio
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
In drivers/md/dm.c (ffffffff817bf5f1)
Location: drivers/md/dm.c:1268
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__clone_and_map_simple_bio
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/dm.c (ffffffff81807d20)
Location: drivers/md/dm.c:566
Inline: True
Direct callers:
  - drivers/md/dm.c:__process_bio
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__send_duplicate_bios
  - drivers/md/dm.c:__send_duplicate_bios
```
**Symbols:**

```
ffffffff81807d20-ffffffff81807d8b: alloc_tio.isra.30 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/dm.c (ffffffff81833bf0)
Location: drivers/md/dm.c:617
Inline: True
Direct callers:
  - drivers/md/dm.c:__process_bio
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__send_duplicate_bios
  - drivers/md/dm.c:__send_duplicate_bios
```
**Symbols:**

```
ffffffff81833bf0-ffffffff81833c5b: alloc_tio.isra.35 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/dm.c (ffffffff818759e0)
Location: drivers/md/dm.c:597
Inline: True
Direct callers:
  - drivers/md/dm.c:__process_bio
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__send_duplicate_bios
  - drivers/md/dm.c:__send_duplicate_bios
```
**Symbols:**

```
ffffffff818759e0-ffffffff81875a4b: alloc_tio.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/dm.c (ffffffff818a77d0)
Location: drivers/md/dm.c:597
Inline: True
Direct callers:
  - drivers/md/dm.c:__process_bio
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__send_duplicate_bios
  - drivers/md/dm.c:__send_duplicate_bios
```
**Symbols:**

```
ffffffff818a77d0-ffffffff818a783b: alloc_tio.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81979216)
Location: drivers/md/dm.c:628
Inline: True
Inline callers:
  - drivers/md/dm.c:__process_bio
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__send_duplicate_bios
  - drivers/md/dm.c:__send_duplicate_bios
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8197d19e)
Location: drivers/md/dm.c:663
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__send_duplicate_bios
  - drivers/md/dm.c:__send_duplicate_bios
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
In drivers/md/dm.c (ffffffff81961172)
Location: drivers/md/dm.c:668
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__send_duplicate_bios
  - drivers/md/dm.c:__send_duplicate_bios
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
In drivers/md/dm.c (ffffffff81a0ad92)
Location: drivers/md/dm.c:548
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__send_duplicate_bios
  - drivers/md/dm.c:__send_duplicate_bios
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct bio *alloc_tio(struct clone_info *ci, struct dm_target *ti, unsigned int target_bio_nr, unsigned int *len, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81b702d0)
Location: drivers/md/dm.c:611
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm.c:__send_duplicate_bios
  - drivers/md/dm.c:__send_duplicate_bios
```
**Symbols:**

```
ffffffff81b702d0-ffffffff81b70401: alloc_tio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct bio *alloc_tio(struct clone_info *ci, struct dm_target *ti, unsigned int target_bio_nr, unsigned int *len, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81d0cbe0)
Location: drivers/md/dm.c:605
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm.c:__send_duplicate_bios
  - drivers/md/dm.c:__send_duplicate_bios
```
**Symbols:**

```
ffffffff81d0cbe0-ffffffff81d0cd11: alloc_tio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct bio *alloc_tio(struct clone_info *ci, struct dm_target *ti, unsigned int target_bio_nr, unsigned int *len, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81d759b0)
Location: drivers/md/dm.c:612
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm.c:__send_duplicate_bios
  - drivers/md/dm.c:__send_duplicate_bios
```
**Symbols:**

```
ffffffff81d759b0-ffffffff81d75ae0: alloc_tio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct bio *alloc_tio(struct clone_info *ci, struct dm_target *ti, unsigned int target_bio_nr, unsigned int *len, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81e2cab0)
Location: drivers/md/dm.c:614
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm.c:__send_duplicate_bios
```
**Symbols:**

```
ffffffff81e2cab0-ffffffff81e2cbe0: alloc_tio (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/dm.c (ffff800010afc6b8)
Location: drivers/md/dm.c:597
Inline: True
Direct callers:
  - drivers/md/dm.c:__process_bio
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__send_duplicate_bios
  - drivers/md/dm.c:__send_duplicate_bios
```
**Symbols:**

```
ffff800010afc6b8-ffff800010afc748: alloc_tio.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct dm_target_io *alloc_tio(struct clone_info *ci, struct dm_target *ti, unsigned int target_bio_nr, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (c0bdcae0)
Location: drivers/md/dm.c:597
Inline: False
Direct callers:
  - drivers/md/dm.c:__process_bio
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__send_duplicate_bios
  - drivers/md/dm.c:__send_duplicate_bios
```
**Symbols:**

```
c0bdcae0-c0bdcb64: alloc_tio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/dm.c (c000000000bebdf0)
Location: drivers/md/dm.c:597
Inline: True
Direct callers:
  - drivers/md/dm.c:__process_bio
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__send_duplicate_bios
  - drivers/md/dm.c:__send_duplicate_bios
```
**Symbols:**

```
c000000000bebdf0-c000000000bebeb0: alloc_tio.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/dm.c (ffffffe0006ede2e)
Location: drivers/md/dm.c:597
Inline: True
Direct callers:
  - drivers/md/dm.c:__process_bio
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__send_duplicate_bios
  - drivers/md/dm.c:__send_duplicate_bios
```
**Symbols:**

```
ffffffe0006ede2e-ffffffe0006edea2: alloc_tio.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/dm.c (ffffffff8184d650)
Location: drivers/md/dm.c:597
Inline: True
Direct callers:
  - drivers/md/dm.c:__process_bio
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__send_duplicate_bios
  - drivers/md/dm.c:__send_duplicate_bios
```
**Symbols:**

```
ffffffff8184d650-ffffffff8184d6bb: alloc_tio.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/dm.c (ffffffff81814c70)
Location: drivers/md/dm.c:597
Inline: True
Direct callers:
  - drivers/md/dm.c:__process_bio
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__send_duplicate_bios
  - drivers/md/dm.c:__send_duplicate_bios
```
**Symbols:**

```
ffffffff81814c70-ffffffff81814cdb: alloc_tio.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/dm.c (ffffffff8189cc80)
Location: drivers/md/dm.c:597
Inline: True
Direct callers:
  - drivers/md/dm.c:__process_bio
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__send_duplicate_bios
  - drivers/md/dm.c:__send_duplicate_bios
```
**Symbols:**

```
ffffffff8189cc80-ffffffff8189cceb: alloc_tio.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/dm.c (ffffffff818b8fe0)
Location: drivers/md/dm.c:597
Inline: True
Direct callers:
  - drivers/md/dm.c:__process_bio
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__send_duplicate_bios
  - drivers/md/dm.c:__send_duplicate_bios
```
**Symbols:**

```
ffffffff818b8fe0-ffffffff818b904b: alloc_tio.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
