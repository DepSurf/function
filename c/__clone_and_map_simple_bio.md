# Function: <code>__clone_and_map_simple_bio</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __clone_and_map_simple_bio(struct clone_info *ci, struct dm_target *ti, unsigned int target_bio_nr, unsigned int *len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff816a0d80)
Location: drivers/md/dm.c:1559
Inline: False
Direct callers:
  - drivers/md/dm.c:__send_changing_extent_only
  - drivers/md/dm.c:__split_and_process_bio
```
**Symbols:**

```
ffffffff816a0d80-ffffffff816a0e12: __clone_and_map_simple_bio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __clone_and_map_simple_bio(struct clone_info *ci, struct dm_target *ti, unsigned int target_bio_nr, unsigned int *len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff817020e0)
Location: drivers/md/dm.c:1066
Inline: False
Direct callers:
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:__send_changing_extent_only
```
**Symbols:**

```
ffffffff817020e0-ffffffff81702172: __clone_and_map_simple_bio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __clone_and_map_simple_bio(struct clone_info *ci, struct dm_target *ti, unsigned int target_bio_nr, unsigned int *len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81733fd0)
Location: drivers/md/dm.c:1121
Inline: False
Direct callers:
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:__send_changing_extent_only
```
**Symbols:**

```
ffffffff81733fd0-ffffffff81734062: __clone_and_map_simple_bio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __clone_and_map_simple_bio(struct clone_info *ci, struct dm_target *ti, unsigned int target_bio_nr, unsigned int *len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8174d0e0)
Location: drivers/md/dm.c:1294
Inline: False
Direct callers:
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:__send_changing_extent_only
```
**Symbols:**

```
ffffffff8174d0e0-ffffffff8174d175: __clone_and_map_simple_bio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __clone_and_map_simple_bio(struct clone_info *ci, struct dm_target *ti, unsigned int target_bio_nr, unsigned int *len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff817bf2c0)
Location: drivers/md/dm.c:1285
Inline: False
Direct callers:
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:__send_changing_extent_only
```
**Symbols:**

```
ffffffff817bf2c0-ffffffff817bf355: __clone_and_map_simple_bio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81808952)
Location: drivers/md/dm.c:1365
Inline: True
Inline callers:
  - drivers/md/dm.c:__process_bio
  - drivers/md/dm.c:__send_duplicate_bios
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81834b36)
Location: drivers/md/dm.c:1388
Inline: True
Inline callers:
  - drivers/md/dm.c:__process_bio
  - drivers/md/dm.c:__send_duplicate_bios
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81876892)
Location: drivers/md/dm.c:1393
Inline: True
Inline callers:
  - drivers/md/dm.c:__process_bio
  - drivers/md/dm.c:__send_duplicate_bios
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
In drivers/md/dm.c (ffffffff818a8692)
Location: drivers/md/dm.c:1393
Inline: True
Inline callers:
  - drivers/md/dm.c:__process_bio
  - drivers/md/dm.c:__send_duplicate_bios
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
In drivers/md/dm.c (ffffffff81979274)
Location: drivers/md/dm.c:1404
Inline: True
Inline callers:
  - drivers/md/dm.c:__process_bio
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
In drivers/md/dm.c (ffffffff8197ced8)
Location: drivers/md/dm.c:1435
Inline: True
Inline callers:
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
In drivers/md/dm.c (ffffffff81960df8)
Location: drivers/md/dm.c:1443
Inline: True
Inline callers:
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
In drivers/md/dm.c (ffffffff81a0aa8f)
Location: drivers/md/dm.c:1339
Inline: True
Inline callers:
  - drivers/md/dm.c:__send_duplicate_bios
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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffff800010aff0e8)
Location: drivers/md/dm.c:1393
Inline: True
Inline callers:
  - drivers/md/dm.c:__process_bio
  - drivers/md/dm.c:__send_duplicate_bios
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
In drivers/md/dm.c (c0bde2e8)
Location: drivers/md/dm.c:1393
Inline: True
Inline callers:
  - drivers/md/dm.c:__process_bio
  - drivers/md/dm.c:__send_duplicate_bios
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
In drivers/md/dm.c (c000000000bed46c)
Location: drivers/md/dm.c:1393
Inline: True
Inline callers:
  - drivers/md/dm.c:__process_bio
  - drivers/md/dm.c:__send_duplicate_bios
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
In drivers/md/dm.c (ffffffe0006eeac8)
Location: drivers/md/dm.c:1393
Inline: True
Inline callers:
  - drivers/md/dm.c:__process_bio
  - drivers/md/dm.c:__send_duplicate_bios
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
In drivers/md/dm.c (ffffffff8184e512)
Location: drivers/md/dm.c:1393
Inline: True
Inline callers:
  - drivers/md/dm.c:__process_bio
  - drivers/md/dm.c:__send_duplicate_bios
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
In drivers/md/dm.c (ffffffff81815b32)
Location: drivers/md/dm.c:1393
Inline: True
Inline callers:
  - drivers/md/dm.c:__process_bio
  - drivers/md/dm.c:__send_duplicate_bios
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
In drivers/md/dm.c (ffffffff8189db42)
Location: drivers/md/dm.c:1393
Inline: True
Inline callers:
  - drivers/md/dm.c:__process_bio
  - drivers/md/dm.c:__send_duplicate_bios
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
In drivers/md/dm.c (ffffffff818b9ef2)
Location: drivers/md/dm.c:1393
Inline: True
Inline callers:
  - drivers/md/dm.c:__process_bio
  - drivers/md/dm.c:__send_duplicate_bios
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
</ul>
