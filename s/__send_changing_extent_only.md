# Function: <code>__send_changing_extent_only</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __send_changing_extent_only(struct clone_info *ci, get_num_bios_fn get_num_bios, is_split_required_fn is_split_required);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff816a0e20)
Location: drivers/md/dm.c:1637
Inline: False
Direct callers:
  - drivers/md/dm.c:__split_and_process_bio
```
**Symbols:**

```
ffffffff816a0e20-ffffffff816a0f7d: __send_changing_extent_only (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __send_changing_extent_only(struct clone_info *ci, get_num_bios_fn get_num_bios, is_split_required_fn is_split_required);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81702180)
Location: drivers/md/dm.c:1151
Inline: False
Direct callers:
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:__split_and_process_bio
```
**Symbols:**

```
ffffffff81702180-ffffffff817022dd: __send_changing_extent_only (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __send_changing_extent_only(struct clone_info *ci, get_num_bios_fn get_num_bios, is_split_required_fn is_split_required);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81734070)
Location: drivers/md/dm.c:1206
Inline: False
Direct callers:
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:__split_and_process_bio
```
**Symbols:**

```
ffffffff81734070-ffffffff817341cd: __send_changing_extent_only (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __send_changing_extent_only(struct clone_info *ci, get_num_bios_fn get_num_bios, is_split_required_fn is_split_required);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8174d180)
Location: drivers/md/dm.c:1384
Inline: False
Direct callers:
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__split_and_process_non_flush
```
**Symbols:**

```
ffffffff8174d180-ffffffff8174d2d4: __send_changing_extent_only (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __send_changing_extent_only(struct clone_info *ci, get_num_bios_fn get_num_bios, is_split_required_fn is_split_required);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff817bf360)
Location: drivers/md/dm.c:1375
Inline: False
Direct callers:
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__split_and_process_non_flush
```
**Symbols:**

```
ffffffff817bf360-ffffffff817bf4b9: __send_changing_extent_only (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __send_changing_extent_only(struct clone_info *ci, struct dm_target *ti, get_num_bios_fn get_num_bios, is_split_required_fn is_split_required);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81808490)
Location: drivers/md/dm.c:1454
Inline: False
```
**Symbols:**

```
ffffffff81808490-ffffffff8180859a: __send_changing_extent_only (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __send_changing_extent_only(struct clone_info *ci, struct dm_target *ti, unsigned int num_bios, bool is_split_required);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff818343a0)
Location: drivers/md/dm.c:1488
Inline: False
Direct callers:
  - drivers/md/dm.c:__process_abnormal_io
  - drivers/md/dm.c:__process_abnormal_io
  - drivers/md/dm.c:__process_abnormal_io
  - drivers/md/dm.c:__process_abnormal_io
```
**Symbols:**

```
ffffffff818343a0-ffffffff8183446a: __send_changing_extent_only (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __send_changing_extent_only(struct clone_info *ci, struct dm_target *ti, unsigned int num_bios);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff818761c0)
Location: drivers/md/dm.c:1486
Inline: False
```
**Symbols:**

```
ffffffff818761c0-ffffffff81876234: __send_changing_extent_only (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __send_changing_extent_only(struct clone_info *ci, struct dm_target *ti, unsigned int num_bios);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff818a7fc0)
Location: drivers/md/dm.c:1486
Inline: False
```
**Symbols:**

```
ffffffff818a7fc0-ffffffff818a8034: __send_changing_extent_only (STB_LOCAL)
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
In drivers/md/dm.c (ffffffff81979110)
Location: drivers/md/dm.c:1494
Inline: True
Inline callers:
  - drivers/md/dm.c:__process_abnormal_io
  - drivers/md/dm.c:__process_abnormal_io
  - drivers/md/dm.c:__process_abnormal_io
  - drivers/md/dm.c:__process_abnormal_io
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
In drivers/md/dm.c (ffffffff8197d10f)
Location: drivers/md/dm.c:1510
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_non_flush
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
In drivers/md/dm.c (ffffffff819610df)
Location: drivers/md/dm.c:1517
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_non_flush
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
In drivers/md/dm.c (ffffffff81a0acff)
Location: drivers/md/dm.c:1413
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_non_flush
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
In drivers/md/dm.c (ffffffff81b72c78)
Location: drivers/md/dm.c:1495
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_split_and_process_bio
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
In drivers/md/dm.c (ffffffff81d0fa53)
Location: drivers/md/dm.c:1560
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_split_and_process_bio
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
In drivers/md/dm.c (ffffffff81d78e94)
Location: drivers/md/dm.c:1588
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_split_and_process_bio
```
</details>
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
int __send_changing_extent_only(struct clone_info *ci, struct dm_target *ti, unsigned int num_bios);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffff800010afebe0)
Location: drivers/md/dm.c:1486
Inline: False
```
**Symbols:**

```
ffff800010afebe0-ffff800010afec9c: __send_changing_extent_only (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __send_changing_extent_only(struct clone_info *ci, struct dm_target *ti, unsigned int num_bios);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (c0bddb1c)
Location: drivers/md/dm.c:1486
Inline: False
```
**Symbols:**

```
c0bddb1c-c0bddbf0: __send_changing_extent_only (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __send_changing_extent_only(struct clone_info *ci, struct dm_target *ti, unsigned int num_bios);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (c000000000becac0)
Location: drivers/md/dm.c:1486
Inline: False
```
**Symbols:**

```
c000000000becac0-c000000000becb9c: __send_changing_extent_only (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __send_changing_extent_only(struct clone_info *ci, struct dm_target *ti, unsigned int num_bios);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffe0006ee4a0)
Location: drivers/md/dm.c:1486
Inline: False
```
**Symbols:**

```
ffffffe0006ee4a0-ffffffe0006ee51e: __send_changing_extent_only (STB_LOCAL)
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
int __send_changing_extent_only(struct clone_info *ci, struct dm_target *ti, unsigned int num_bios);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8184de40)
Location: drivers/md/dm.c:1486
Inline: False
```
**Symbols:**

```
ffffffff8184de40-ffffffff8184deb4: __send_changing_extent_only (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __send_changing_extent_only(struct clone_info *ci, struct dm_target *ti, unsigned int num_bios);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81815460)
Location: drivers/md/dm.c:1486
Inline: False
```
**Symbols:**

```
ffffffff81815460-ffffffff818154d4: __send_changing_extent_only (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __send_changing_extent_only(struct clone_info *ci, struct dm_target *ti, unsigned int num_bios);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8189d470)
Location: drivers/md/dm.c:1486
Inline: False
```
**Symbols:**

```
ffffffff8189d470-ffffffff8189d4e4: __send_changing_extent_only (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __send_changing_extent_only(struct clone_info *ci, struct dm_target *ti, unsigned int num_bios);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff818b97d0)
Location: drivers/md/dm.c:1486
Inline: False
```
**Symbols:**

```
ffffffff818b97d0-ffffffff818b9844: __send_changing_extent_only (STB_LOCAL)
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
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct dm_target *ti</code>
</li>
<li>
<b>Param reordered. </b>
<code>ci, get_num_bios, is_split_required</code> ➡️ <code>ci, ti, get_num_bios, is_split_required</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int num_bios</code>
</li>
<li>
<b>Param removed. </b>
<code>get_num_bios_fn get_num_bios</code>
</li>
<li>
<b>Param type changed. </b>
<code>is_split_required_fn is_split_required</code> ➡️ <code>bool is_split_required</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool is_split_required</code>
</li>
</ul>
</details>
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
