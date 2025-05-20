# Function: <code>max_io_len_target_boundary</code>

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
In drivers/md/dm.c (ffffffff816a0f16)
Location: drivers/md/dm.c:1386
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
In drivers/md/dm.c (ffffffff817031f5)
Location: drivers/md/dm.c:863
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:__send_changing_extent_only
  - drivers/md/dm.c:__send_changing_extent_only
  - drivers/md/dm.c:dm_blk_direct_access
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
In drivers/md/dm.c (ffffffff817350c1)
Location: drivers/md/dm.c:863
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:__send_changing_extent_only
  - drivers/md/dm.c:__send_changing_extent_only
  - drivers/md/dm.c:dm_blk_direct_access
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
In drivers/md/dm.c (ffffffff8174d358)
Location: drivers/md/dm.c:876
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__send_changing_extent_only
  - drivers/md/dm.c:__send_changing_extent_only
  - drivers/md/dm.c:dm_dax_direct_access
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
In drivers/md/dm.c (ffffffff817bf538)
Location: drivers/md/dm.c:885
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__send_changing_extent_only
  - drivers/md/dm.c:__send_changing_extent_only
  - drivers/md/dm.c:dm_dax_direct_access
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
In drivers/md/dm.c (ffffffff818086af)
Location: drivers/md/dm.c:969
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__send_changing_extent_only
  - drivers/md/dm.c:__send_changing_extent_only
  - drivers/md/dm.c:dm_dax_direct_access
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
In drivers/md/dm.c (ffffffff81834566)
Location: drivers/md/dm.c:1024
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__send_changing_extent_only
  - drivers/md/dm.c:dm_dax_direct_access
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
In drivers/md/dm.c (ffffffff81876c5b)
Location: drivers/md/dm.c:1018
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_process_bio
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__send_changing_extent_only
  - drivers/md/dm.c:dm_dax_direct_access
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
In drivers/md/dm.c (ffffffff818a8b7b)
Location: drivers/md/dm.c:1018
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_process_bio
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__send_changing_extent_only
  - drivers/md/dm.c:dm_dax_direct_access
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
In drivers/md/dm.c (ffffffff819793c6)
Location: drivers/md/dm.c:1044
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__process_abnormal_io
  - drivers/md/dm.c:dm_dax_direct_access
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
In drivers/md/dm.c (ffffffff8197d117)
Location: drivers/md/dm.c:1050
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:max_io_len
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
In drivers/md/dm.c (ffffffff819610e7)
Location: drivers/md/dm.c:1054
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:max_io_len
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
In drivers/md/dm.c (ffffffff81a0ad07)
Location: drivers/md/dm.c:941
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:max_io_len
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
Location: drivers/md/dm.c:1078
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm.c:max_io_len
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
Location: drivers/md/dm.c:1156
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm.c:max_io_len
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
In drivers/md/dm.c (ffffffff81d75470)
Location: drivers/md/dm.c:1173
Inline: True
Inline callers:
  - drivers/md/dm.c:__max_io_len
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
In drivers/md/dm.c (ffffffff81e2c580)
Location: drivers/md/dm.c:1159
Inline: True
Inline callers:
  - drivers/md/dm.c:__max_io_len
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
In drivers/md/dm.c (ffff800010aff4fc)
Location: drivers/md/dm.c:1018
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_process_bio
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__send_changing_extent_only
  - drivers/md/dm.c:dm_dax_direct_access
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
In drivers/md/dm.c (c0bddb54)
Location: drivers/md/dm.c:1018
Inline: True
Inline callers:
  - drivers/md/dm.c:__send_changing_extent_only
  - drivers/md/dm.c:max_io_len
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
In drivers/md/dm.c (c000000000beda60)
Location: drivers/md/dm.c:1018
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_process_bio
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__send_changing_extent_only
  - drivers/md/dm.c:dm_dax_direct_access
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
In drivers/md/dm.c (ffffffe0006eed80)
Location: drivers/md/dm.c:1018
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_process_bio
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__send_changing_extent_only
  - drivers/md/dm.c:dm_dax_direct_access
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
In drivers/md/dm.c (ffffffff8184e9fb)
Location: drivers/md/dm.c:1018
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_process_bio
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__send_changing_extent_only
  - drivers/md/dm.c:dm_dax_direct_access
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
In drivers/md/dm.c (ffffffff8181601b)
Location: drivers/md/dm.c:1018
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_process_bio
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__send_changing_extent_only
  - drivers/md/dm.c:dm_dax_direct_access
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
In drivers/md/dm.c (ffffffff8189e02b)
Location: drivers/md/dm.c:1018
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_process_bio
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__send_changing_extent_only
  - drivers/md/dm.c:dm_dax_direct_access
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
In drivers/md/dm.c (ffffffff818baebb)
Location: drivers/md/dm.c:1018
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_process_bio
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__send_changing_extent_only
  - drivers/md/dm.c:dm_dax_direct_access
```
</details>
</li>
</ul>

## Differences
