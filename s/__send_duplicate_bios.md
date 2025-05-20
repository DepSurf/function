# Function: <code>__send_duplicate_bios</code>

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
In drivers/md/dm.c (ffffffff816a0ebd)
Location: drivers/md/dm.c:1575
Inline: True
Inline callers:
  - drivers/md/dm.c:__send_changing_extent_only
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
In drivers/md/dm.c (ffffffff8170342f)
Location: drivers/md/dm.c:1082
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:__send_changing_extent_only
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
In drivers/md/dm.c (ffffffff81735310)
Location: drivers/md/dm.c:1137
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:__send_changing_extent_only
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
In drivers/md/dm.c (ffffffff8174e534)
Location: drivers/md/dm.c:1310
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:__send_changing_extent_only
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
In drivers/md/dm.c (ffffffff817c0555)
Location: drivers/md/dm.c:1301
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:__send_changing_extent_only
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __send_duplicate_bios(struct clone_info *ci, struct dm_target *ti, unsigned int num_bios, unsigned int *len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff818082a0)
Location: drivers/md/dm.c:1379
Inline: False
Direct callers:
  - drivers/md/dm.c:__send_changing_extent_only
```
**Symbols:**

```
ffffffff818082a0-ffffffff81808481: __send_duplicate_bios (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __send_duplicate_bios(struct clone_info *ci, struct dm_target *ti, unsigned int num_bios, unsigned int *len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff818341b0)
Location: drivers/md/dm.c:1402
Inline: False
Direct callers:
  - drivers/md/dm.c:__send_changing_extent_only
```
**Symbols:**

```
ffffffff818341b0-ffffffff81834394: __send_duplicate_bios (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __send_duplicate_bios(struct clone_info *ci, struct dm_target *ti, unsigned int num_bios, unsigned int *len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81875fe0)
Location: drivers/md/dm.c:1407
Inline: False
Direct callers:
  - drivers/md/dm.c:__send_changing_extent_only
```
**Symbols:**

```
ffffffff81875fe0-ffffffff818761be: __send_duplicate_bios (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __send_duplicate_bios(struct clone_info *ci, struct dm_target *ti, unsigned int num_bios, unsigned int *len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff818a7de0)
Location: drivers/md/dm.c:1407
Inline: False
Direct callers:
  - drivers/md/dm.c:__send_changing_extent_only
```
**Symbols:**

```
ffffffff818a7de0-ffffffff818a7fbe: __send_duplicate_bios (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __send_duplicate_bios(struct clone_info *ci, struct dm_target *ti, unsigned int num_bios, unsigned int *len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81978080)
Location: drivers/md/dm.c:1418
Inline: False
Direct callers:
  - drivers/md/dm.c:__process_abnormal_io
```
**Symbols:**

```
ffffffff81978080-ffffffff819782cd: __send_duplicate_bios (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __send_duplicate_bios(struct clone_info *ci, struct dm_target *ti, unsigned int num_bios, unsigned int *len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8197cd70)
Location: drivers/md/dm.c:1449
Inline: False
Direct callers:
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__send_empty_flush
```
**Symbols:**

```
ffffffff8197cd70-ffffffff8197cfb1: __send_duplicate_bios (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __send_duplicate_bios(struct clone_info *ci, struct dm_target *ti, unsigned int num_bios, unsigned int *len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81960c90)
Location: drivers/md/dm.c:1457
Inline: False
Direct callers:
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__send_empty_flush
```
**Symbols:**

```
ffffffff81960c90-ffffffff81960ecc: __send_duplicate_bios (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __send_duplicate_bios(struct clone_info *ci, struct dm_target *ti, unsigned int num_bios, unsigned int *len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm.c (0)
Location: drivers/md/dm.c:1353
Inline: False
Direct callers:
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__send_empty_flush
```
**Symbols:**

```
ffffffff81a0a920-ffffffff81a0ab61: __send_duplicate_bios (STB_LOCAL)
ffffffff81d29fc8-ffffffff81d29fe3: __send_duplicate_bios.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __send_duplicate_bios(struct clone_info *ci, struct dm_target *ti, unsigned int num_bios, unsigned int *len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81b725a0)
Location: drivers/md/dm.c:1429
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm.c:__send_empty_flush
```
**Symbols:**

```
ffffffff81b725a0-ffffffff81b72743: __send_duplicate_bios (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __send_duplicate_bios(struct clone_info *ci, struct dm_target *ti, unsigned int num_bios, unsigned int *len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81d0f300)
Location: drivers/md/dm.c:1494
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm.c:__send_empty_flush
```
**Symbols:**

```
ffffffff81d0f300-ffffffff81d0f4e7: __send_duplicate_bios (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __send_duplicate_bios(struct clone_info *ci, struct dm_target *ti, unsigned int num_bios, unsigned int *len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81d786b0)
Location: drivers/md/dm.c:1520
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm.c:__send_empty_flush
```
**Symbols:**

```
ffffffff81d786b0-ffffffff81d788ef: __send_duplicate_bios (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
unsigned int __send_duplicate_bios(struct clone_info *ci, struct dm_target *ti, unsigned int num_bios, unsigned int *len, gfp_t gfp_flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81e2f920)
Location: drivers/md/dm.c:1513
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm.c:__send_empty_flush
```
**Symbols:**

```
ffffffff81e2f920-ffffffff81e2fb20: __send_duplicate_bios (STB_LOCAL)
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
void __send_duplicate_bios(struct clone_info *ci, struct dm_target *ti, unsigned int num_bios, unsigned int *len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffff800010afea10)
Location: drivers/md/dm.c:1407
Inline: False
Direct callers:
  - drivers/md/dm.c:__send_changing_extent_only
```
**Symbols:**

```
ffff800010afea10-ffff800010afebdc: __send_duplicate_bios (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __send_duplicate_bios(struct clone_info *ci, struct dm_target *ti, unsigned int num_bios, unsigned int *len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (c0bdd94c)
Location: drivers/md/dm.c:1407
Inline: False
Direct callers:
  - drivers/md/dm.c:__send_changing_extent_only
```
**Symbols:**

```
c0bdd94c-c0bddb1c: __send_duplicate_bios (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __send_duplicate_bios(struct clone_info *ci, struct dm_target *ti, unsigned int num_bios, unsigned int *len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (c000000000bec810)
Location: drivers/md/dm.c:1407
Inline: False
Direct callers:
  - drivers/md/dm.c:__send_changing_extent_only
```
**Symbols:**

```
c000000000bec810-c000000000becabc: __send_duplicate_bios (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __send_duplicate_bios(struct clone_info *ci, struct dm_target *ti, unsigned int num_bios, unsigned int *len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffe0006ee314)
Location: drivers/md/dm.c:1407
Inline: False
Direct callers:
  - drivers/md/dm.c:__send_changing_extent_only
```
**Symbols:**

```
ffffffe0006ee314-ffffffe0006ee4a0: __send_duplicate_bios (STB_LOCAL)
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
void __send_duplicate_bios(struct clone_info *ci, struct dm_target *ti, unsigned int num_bios, unsigned int *len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8184dc60)
Location: drivers/md/dm.c:1407
Inline: False
Direct callers:
  - drivers/md/dm.c:__send_changing_extent_only
```
**Symbols:**

```
ffffffff8184dc60-ffffffff8184de3e: __send_duplicate_bios (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __send_duplicate_bios(struct clone_info *ci, struct dm_target *ti, unsigned int num_bios, unsigned int *len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81815280)
Location: drivers/md/dm.c:1407
Inline: False
Direct callers:
  - drivers/md/dm.c:__send_changing_extent_only
```
**Symbols:**

```
ffffffff81815280-ffffffff8181545e: __send_duplicate_bios (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __send_duplicate_bios(struct clone_info *ci, struct dm_target *ti, unsigned int num_bios, unsigned int *len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8189d290)
Location: drivers/md/dm.c:1407
Inline: False
Direct callers:
  - drivers/md/dm.c:__send_changing_extent_only
```
**Symbols:**

```
ffffffff8189d290-ffffffff8189d46e: __send_duplicate_bios (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __send_duplicate_bios(struct clone_info *ci, struct dm_target *ti, unsigned int num_bios, unsigned int *len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff818b95f0)
Location: drivers/md/dm.c:1407
Inline: False
Direct callers:
  - drivers/md/dm.c:__send_changing_extent_only
```
**Symbols:**

```
ffffffff818b95f0-ffffffff818b97ce: __send_duplicate_bios (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>gfp_t gfp_flag</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>unsigned int</code>
</li>
</ul>
</details>
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
