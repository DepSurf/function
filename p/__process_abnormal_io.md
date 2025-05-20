# Function: <code>__process_abnormal_io</code>

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
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool __process_abnormal_io(struct clone_info *ci, struct dm_target *ti, int *result);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff818085a0)
Location: drivers/md/dm.c:1505
Inline: True
Direct callers:
  - drivers/md/dm.c:__process_bio
  - drivers/md/dm.c:__split_and_process_non_flush
```
**Symbols:**

```
ffffffff818085a0-ffffffff81808633: __process_abnormal_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool __process_abnormal_io(struct clone_info *ci, struct dm_target *ti, int *result);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81834470)
Location: drivers/md/dm.c:1536
Inline: False
Direct callers:
  - drivers/md/dm.c:__process_bio
  - drivers/md/dm.c:__split_and_process_non_flush
```
**Symbols:**

```
ffffffff81834470-ffffffff818344f6: __process_abnormal_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool __process_abnormal_io(struct clone_info *ci, struct dm_target *ti, int *result);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81876240)
Location: drivers/md/dm.c:1546
Inline: True
Direct callers:
  - drivers/md/dm.c:__process_bio
  - drivers/md/dm.c:__split_and_process_non_flush
```
**Symbols:**

```
ffffffff81876240-ffffffff818762ca: __process_abnormal_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool __process_abnormal_io(struct clone_info *ci, struct dm_target *ti, int *result);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff818a8040)
Location: drivers/md/dm.c:1546
Inline: True
Direct callers:
  - drivers/md/dm.c:__process_bio
  - drivers/md/dm.c:__split_and_process_non_flush
```
**Symbols:**

```
ffffffff818a8040-ffffffff818a80ca: __process_abnormal_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool __process_abnormal_io(struct clone_info *ci, struct dm_target *ti, int *result);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff819790b0)
Location: drivers/md/dm.c:1554
Inline: False
Direct callers:
  - drivers/md/dm.c:__process_bio
  - drivers/md/dm.c:__split_and_process_non_flush
```
**Symbols:**

```
ffffffff819790b0-ffffffff81979176: __process_abnormal_io (STB_LOCAL)
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
In drivers/md/dm.c (ffffffff8197d0e4)
Location: drivers/md/dm.c:1551
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
In drivers/md/dm.c (ffffffff819610b4)
Location: drivers/md/dm.c:1558
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
In drivers/md/dm.c (ffffffff81a0acd4)
Location: drivers/md/dm.c:1454
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
In drivers/md/dm.c (ffffffff81b72c57)
Location: drivers/md/dm.c:1534
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
In drivers/md/dm.c (ffffffff81d0fa34)
Location: drivers/md/dm.c:1599
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
In drivers/md/dm.c (ffffffff81d78e52)
Location: drivers/md/dm.c:1628
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_split_and_process_bio
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
In drivers/md/dm.c (ffffffff81e2ffd1)
Location: drivers/md/dm.c:1621
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_split_and_process_bio
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
bool __process_abnormal_io(struct clone_info *ci, struct dm_target *ti, int *result);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffff800010afeca0)
Location: drivers/md/dm.c:1546
Inline: True
Direct callers:
  - drivers/md/dm.c:__process_bio
  - drivers/md/dm.c:__split_and_process_non_flush
```
**Symbols:**

```
ffff800010afeca0-ffff800010afed48: __process_abnormal_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool __process_abnormal_io(struct clone_info *ci, struct dm_target *ti, int *result);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (c0bddbf0)
Location: drivers/md/dm.c:1546
Inline: True
Direct callers:
  - drivers/md/dm.c:__process_bio
  - drivers/md/dm.c:__split_and_process_non_flush
```
**Symbols:**

```
c0bddbf0-c0bddc98: __process_abnormal_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool __process_abnormal_io(struct clone_info *ci, struct dm_target *ti, int *result);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (c000000000becba0)
Location: drivers/md/dm.c:1546
Inline: True
Direct callers:
  - drivers/md/dm.c:__process_bio
  - drivers/md/dm.c:__split_and_process_non_flush
```
**Symbols:**

```
c000000000becba0-c000000000becc60: __process_abnormal_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool __process_abnormal_io(struct clone_info *ci, struct dm_target *ti, int *result);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffe0006ee51e)
Location: drivers/md/dm.c:1546
Inline: True
Direct callers:
  - drivers/md/dm.c:__process_bio
  - drivers/md/dm.c:__split_and_process_non_flush
```
**Symbols:**

```
ffffffe0006ee51e-ffffffe0006ee5a0: __process_abnormal_io (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
bool __process_abnormal_io(struct clone_info *ci, struct dm_target *ti, int *result);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8184dec0)
Location: drivers/md/dm.c:1546
Inline: True
Direct callers:
  - drivers/md/dm.c:__process_bio
  - drivers/md/dm.c:__split_and_process_non_flush
```
**Symbols:**

```
ffffffff8184dec0-ffffffff8184df4a: __process_abnormal_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool __process_abnormal_io(struct clone_info *ci, struct dm_target *ti, int *result);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff818154e0)
Location: drivers/md/dm.c:1546
Inline: True
Direct callers:
  - drivers/md/dm.c:__process_bio
  - drivers/md/dm.c:__split_and_process_non_flush
```
**Symbols:**

```
ffffffff818154e0-ffffffff8181556a: __process_abnormal_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool __process_abnormal_io(struct clone_info *ci, struct dm_target *ti, int *result);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8189d4f0)
Location: drivers/md/dm.c:1546
Inline: True
Direct callers:
  - drivers/md/dm.c:__process_bio
  - drivers/md/dm.c:__split_and_process_non_flush
```
**Symbols:**

```
ffffffff8189d4f0-ffffffff8189d57a: __process_abnormal_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool __process_abnormal_io(struct clone_info *ci, struct dm_target *ti, int *result);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff818b9850)
Location: drivers/md/dm.c:1546
Inline: True
Direct callers:
  - drivers/md/dm.c:__process_bio
  - drivers/md/dm.c:__split_and_process_non_flush
```
**Symbols:**

```
ffffffff818b9850-ffffffff818b98da: __process_abnormal_io (STB_LOCAL)
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
