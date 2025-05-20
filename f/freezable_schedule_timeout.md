# Function: <code>freezable_schedule_timeout</code>

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
In net/unix/af_unix.c (ffffffff817bfad4)
Location: include/linux/freezer.h:187
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
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
In net/unix/af_unix.c (ffffffff8182c935)
Location: include/linux/freezer.h:187
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
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
In net/unix/af_unix.c (ffffffff8185e3ec)
Location: include/linux/freezer.h:187
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
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
In net/unix/af_unix.c (ffffffff818833ed)
Location: include/linux/freezer.h:187
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
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
In net/unix/af_unix.c (ffffffff81903f88)
Location: include/linux/freezer.h:188
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
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
In net/unix/af_unix.c (ffffffff8195c0b5)
Location: include/linux/freezer.h:188
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
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
In net/unix/af_unix.c (ffffffff819908c4)
Location: include/linux/freezer.h:188
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
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
In mm/khugepaged.c (ffffffff812ac5fe)
Location: include/linux/freezer.h:188
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In net/unix/af_unix.c (ffffffff819fbfaa)
Location: include/linux/freezer.h:188
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
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
In mm/khugepaged.c (ffffffff812beb39)
Location: include/linux/freezer.h:188
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In net/unix/af_unix.c (ffffffff81a32c3a)
Location: include/linux/freezer.h:188
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
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
In mm/khugepaged.c (ffffffff812f004f)
Location: include/linux/freezer.h:188
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_wait_work
```
```
In net/unix/af_unix.c (ffffffff81b24838)
Location: include/linux/freezer.h:188
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_data_wait
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
In mm/compaction.c (ffffffff8128e5ab)
Location: include/linux/freezer.h:188
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
```
```
In mm/khugepaged.c (ffffffff812fb80f)
Location: include/linux/freezer.h:188
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_wait_work
```
```
In net/unix/af_unix.c (ffffffff81b332a2)
Location: include/linux/freezer.h:188
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_data_wait
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
In mm/compaction.c (ffffffff81293c3b)
Location: include/linux/freezer.h:188
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
```
```
In mm/khugepaged.c (ffffffff813025df)
Location: include/linux/freezer.h:188
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_wait_work
```
```
In net/unix/af_unix.c (ffffffff81b20fe2)
Location: include/linux/freezer.h:188
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_data_wait
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
In mm/compaction.c (ffffffff812d4295)
Location: include/linux/freezer.h:188
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
```
```
In mm/khugepaged.c (ffffffff8134c34f)
Location: include/linux/freezer.h:188
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_wait_work
```
```
In drivers/xen/balloon.c (ffffffff81791e34)
Location: include/linux/freezer.h:188
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_thread
```
```
In net/unix/af_unix.c (ffffffff81be60a2)
Location: include/linux/freezer.h:188
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_data_wait
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
In mm/compaction.c (ffffffff813331fd)
Location: include/linux/freezer.h:188
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
```
```
In mm/khugepaged.c (ffffffff813c3a81)
Location: include/linux/freezer.h:188
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_wait_work
```
```
In drivers/xen/balloon.c (ffffffff818caa6c)
Location: include/linux/freezer.h:188
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_thread
```
```
In net/unix/af_unix.c (ffffffff81d7d295)
Location: include/linux/freezer.h:188
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_data_wait
```
</details>
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
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffff80001035ff78)
Location: include/linux/freezer.h:188
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In net/unix/af_unix.c (ffff800010cf23c0)
Location: include/linux/freezer.h:188
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
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
In net/unix/af_unix.c (c0dfa328)
Location: include/linux/freezer.h:188
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
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
In mm/khugepaged.c (c00000000044b720)
Location: include/linux/freezer.h:188
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In net/unix/af_unix.c (c000000000e18840)
Location: include/linux/freezer.h:188
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
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
In net/unix/af_unix.c (ffffffe00083f092)
Location: include/linux/freezer.h:188
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
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
In mm/khugepaged.c (ffffffff812b7119)
Location: include/linux/freezer.h:188
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In net/unix/af_unix.c (ffffffff819d22ca)
Location: include/linux/freezer.h:188
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
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
In mm/khugepaged.c (ffffffff812a82e9)
Location: include/linux/freezer.h:188
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In net/unix/af_unix.c (ffffffff8198f08a)
Location: include/linux/freezer.h:188
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
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
In mm/khugepaged.c (ffffffff812b4f29)
Location: include/linux/freezer.h:188
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In net/unix/af_unix.c (ffffffff81a3cd4a)
Location: include/linux/freezer.h:188
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
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
In mm/khugepaged.c (ffffffff812c4d57)
Location: include/linux/freezer.h:188
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In net/unix/af_unix.c (ffffffff81a48306)
Location: include/linux/freezer.h:188
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
```
</details>
</li>
</ul>

## Differences
