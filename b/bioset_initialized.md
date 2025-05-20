# Function: <code>bioset_initialized</code>

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
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (0)
Location: include/linux/bio.h:771
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/bio.h:771
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (0)
Location: include/linux/bio.h:733
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/bio.h:733
Inline: True
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
In drivers/md/md.c (0)
Location: include/linux/bio.h:729
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/bio.h:729
Inline: True
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
In drivers/md/md.c (0)
Location: include/linux/bio.h:730
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/bio.h:730
Inline: True
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
In drivers/md/md.c (ffffffff8196d201)
Location: include/linux/bio.h:720
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:submit_flushes
```
```
In drivers/md/dm.c (ffffffff8197717f)
Location: include/linux/bio.h:720
Inline: True
Inline callers:
  - drivers/md/dm.c:__bind_mempools
  - drivers/md/dm.c:__bind_mempools
  - drivers/md/dm.c:__bind_mempools
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
In drivers/md/md.c (ffffffff81974081)
Location: include/linux/bio.h:722
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:submit_flushes
```
```
In drivers/md/dm.c (ffffffff8197be5f)
Location: include/linux/bio.h:722
Inline: True
Inline callers:
  - drivers/md/dm.c:__bind_mempools
  - drivers/md/dm.c:__bind_mempools
  - drivers/md/dm.c:__bind_mempools
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
In drivers/md/md.c (ffffffff819580b3)
Location: include/linux/bio.h:720
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
```
```
In drivers/md/dm.c (ffffffff8195fe62)
Location: include/linux/bio.h:720
Inline: True
Inline callers:
  - drivers/md/dm.c:__bind
  - drivers/md/dm.c:__bind
  - drivers/md/dm.c:__bind
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
In drivers/md/md.c (ffffffff819fd833)
Location: include/linux/bio.h:691
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
```
```
In drivers/md/dm.c (ffffffff81a07e0e)
Location: include/linux/bio.h:691
Inline: True
Inline callers:
  - drivers/md/dm.c:__bind
  - drivers/md/dm.c:__bind
  - drivers/md/dm.c:__bind
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
In drivers/md/md.c (ffffffff81b64eb2)
Location: include/linux/bio.h:684
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
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
In drivers/md/md.c (ffffffff81cfffb3)
Location: include/linux/bio.h:684
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
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
In drivers/md/md.c (ffffffff81d631d0)
Location: include/linux/bio.h:697
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
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
In drivers/md/md.c (ffffffff81e1a0b0)
Location: include/linux/bio.h:712
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
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
In drivers/md/md.c (0)
Location: include/linux/bio.h:730
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/bio.h:730
Inline: True
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
In drivers/md/md.c (c0bd2bd8)
Location: include/linux/bio.h:730
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
```
```
In drivers/md/dm.c (c0be064c)
Location: include/linux/bio.h:730
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:dm_swap_table
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
In drivers/md/md.c (c000000000bddc10)
Location: include/linux/bio.h:730
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
```
```
In drivers/md/dm.c (c000000000beff38)
Location: include/linux/bio.h:730
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:dm_swap_table
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
In drivers/md/md.c (ffffffe0006e5510)
Location: include/linux/bio.h:730
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
```
```
In drivers/md/dm.c (ffffffe0006f0ea0)
Location: include/linux/bio.h:730
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:dm_swap_table
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
In drivers/md/md.c (0)
Location: include/linux/bio.h:730
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/bio.h:730
Inline: True
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
In drivers/md/md.c (0)
Location: include/linux/bio.h:730
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/bio.h:730
Inline: True
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
In drivers/md/md.c (0)
Location: include/linux/bio.h:730
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/bio.h:730
Inline: True
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
In drivers/md/md.c (0)
Location: include/linux/bio.h:730
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/bio.h:730
Inline: True
```
</details>
</li>
</ul>

## Differences
