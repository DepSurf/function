# Function: <code>blk_trace_request_get_cgid</code>

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
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff81183123)
Location: kernel/trace/blktrace.c:792
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq_remap
  - kernel/trace/blktrace.c:blk_add_trace_rq_complete
  - kernel/trace/blktrace.c:blk_add_trace_rq_requeue
  - kernel/trace/blktrace.c:blk_add_trace_rq_issue
  - kernel/trace/blktrace.c:blk_add_trace_rq_insert
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
In kernel/trace/blktrace.c (ffffffff81192272)
Location: kernel/trace/blktrace.c:792
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq_remap
  - kernel/trace/blktrace.c:blk_add_trace_rq_complete
  - kernel/trace/blktrace.c:blk_add_trace_rq_requeue
  - kernel/trace/blktrace.c:blk_add_trace_rq_issue
  - kernel/trace/blktrace.c:blk_add_trace_rq_insert
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
In kernel/trace/blktrace.c (ffffffff8119faf2)
Location: kernel/trace/blktrace.c:780
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq_remap
  - kernel/trace/blktrace.c:blk_add_trace_rq_complete
  - kernel/trace/blktrace.c:blk_add_trace_rq_requeue
  - kernel/trace/blktrace.c:blk_add_trace_rq_issue
  - kernel/trace/blktrace.c:blk_add_trace_rq_insert
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
In kernel/trace/blktrace.c (ffffffff811ad842)
Location: kernel/trace/blktrace.c:775
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq_remap
  - kernel/trace/blktrace.c:blk_add_trace_rq_complete
  - kernel/trace/blktrace.c:blk_add_trace_rq_requeue
  - kernel/trace/blktrace.c:blk_add_trace_rq_issue
  - kernel/trace/blktrace.c:blk_add_trace_rq_insert
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
In kernel/trace/blktrace.c (ffffffff811b90b7)
Location: kernel/trace/blktrace.c:780
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq_remap
  - kernel/trace/blktrace.c:blk_add_trace_rq_complete
  - kernel/trace/blktrace.c:blk_add_trace_rq_requeue
  - kernel/trace/blktrace.c:blk_add_trace_rq_issue
  - kernel/trace/blktrace.c:blk_add_trace_rq_insert
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
In kernel/trace/blktrace.c (ffffffff811d237d)
Location: kernel/trace/blktrace.c:807
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq_remap
  - kernel/trace/blktrace.c:blk_add_trace_rq_complete
  - kernel/trace/blktrace.c:blk_add_trace_rq_requeue
  - kernel/trace/blktrace.c:blk_add_trace_rq_issue
  - kernel/trace/blktrace.c:blk_add_trace_rq_insert
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff811cedac)
Location: kernel/trace/blktrace.c:798
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_trace_rq_complete
  - kernel/trace/blktrace.c:blk_add_trace_rq_requeue
  - kernel/trace/blktrace.c:blk_add_trace_rq_merge
  - kernel/trace/blktrace.c:blk_add_trace_rq_issue
  - kernel/trace/blktrace.c:blk_add_trace_rq_insert
Direct callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq_remap
```
**Symbols:**

```
ffffffff811ce480-ffffffff811ce4b8: blk_trace_request_get_cgid.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff811d03a2)
Location: kernel/trace/blktrace.c:795
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_trace_rq_complete
  - kernel/trace/blktrace.c:blk_add_trace_rq_requeue
  - kernel/trace/blktrace.c:blk_add_trace_rq_merge
  - kernel/trace/blktrace.c:blk_add_trace_rq_issue
  - kernel/trace/blktrace.c:blk_add_trace_rq_insert
Direct callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq_remap
```
**Symbols:**

```
ffffffff811cee80-ffffffff811ceeb8: blk_trace_request_get_cgid.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff811fd2a5)
Location: kernel/trace/blktrace.c:805
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_trace_rq_complete
  - kernel/trace/blktrace.c:blk_add_trace_rq_requeue
  - kernel/trace/blktrace.c:blk_add_trace_rq_merge
  - kernel/trace/blktrace.c:blk_add_trace_rq_issue
  - kernel/trace/blktrace.c:blk_add_trace_rq_insert
Direct callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq_remap
```
**Symbols:**

```
ffffffff811fc100-ffffffff811fc138: blk_trace_request_get_cgid.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff81236ef6)
Location: kernel/trace/blktrace.c:804
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_trace_rq_complete
  - kernel/trace/blktrace.c:blk_add_trace_rq_requeue
  - kernel/trace/blktrace.c:blk_add_trace_rq_merge
  - kernel/trace/blktrace.c:blk_add_trace_rq_issue
  - kernel/trace/blktrace.c:blk_add_trace_rq_insert
Direct callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq_remap
```
**Symbols:**

```
ffffffff812364c0-ffffffff81236518: blk_trace_request_get_cgid.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff81283c26)
Location: kernel/trace/blktrace.c:807
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_trace_rq_complete
  - kernel/trace/blktrace.c:blk_add_trace_rq_requeue
  - kernel/trace/blktrace.c:blk_add_trace_rq_merge
  - kernel/trace/blktrace.c:blk_add_trace_rq_issue
  - kernel/trace/blktrace.c:blk_add_trace_rq_insert
Direct callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq_remap
```
**Symbols:**

```
ffffffff81283180-ffffffff812831d8: blk_trace_request_get_cgid.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff812a08d6)
Location: kernel/trace/blktrace.c:803
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_trace_rq_complete
  - kernel/trace/blktrace.c:blk_add_trace_rq_requeue
  - kernel/trace/blktrace.c:blk_add_trace_rq_merge
  - kernel/trace/blktrace.c:blk_add_trace_rq_issue
  - kernel/trace/blktrace.c:blk_add_trace_rq_insert
Direct callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq_remap
```
**Symbols:**

```
ffffffff8129fe30-ffffffff8129fe88: blk_trace_request_get_cgid.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff812bc006)
Location: kernel/trace/blktrace.c:803
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_trace_rq_complete
  - kernel/trace/blktrace.c:blk_add_trace_rq_requeue
  - kernel/trace/blktrace.c:blk_add_trace_rq_merge
  - kernel/trace/blktrace.c:blk_add_trace_rq_issue
  - kernel/trace/blktrace.c:blk_add_trace_rq_insert
Direct callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq_remap
```
**Symbols:**

```
ffffffff812bb560-ffffffff812bb5b8: blk_trace_request_get_cgid.isra.0 (STB_LOCAL)
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
In kernel/trace/blktrace.c (ffff800010237cbc)
Location: kernel/trace/blktrace.c:780
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq_remap
  - kernel/trace/blktrace.c:blk_add_trace_rq_complete
  - kernel/trace/blktrace.c:blk_add_trace_rq_requeue
  - kernel/trace/blktrace.c:blk_add_trace_rq_issue
  - kernel/trace/blktrace.c:blk_add_trace_rq_insert
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
In kernel/trace/blktrace.c (c0473310)
Location: kernel/trace/blktrace.c:780
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq_remap
  - kernel/trace/blktrace.c:blk_add_trace_rq_complete
  - kernel/trace/blktrace.c:blk_add_trace_rq_requeue
  - kernel/trace/blktrace.c:blk_add_trace_rq_issue
  - kernel/trace/blktrace.c:blk_add_trace_rq_insert
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
In kernel/trace/blktrace.c (c0000000002c371c)
Location: kernel/trace/blktrace.c:780
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq_remap
  - kernel/trace/blktrace.c:blk_add_trace_rq_complete
  - kernel/trace/blktrace.c:blk_add_trace_rq_requeue
  - kernel/trace/blktrace.c:blk_add_trace_rq_issue
  - kernel/trace/blktrace.c:blk_add_trace_rq_insert
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
In kernel/trace/blktrace.c (ffffffe00018e62c)
Location: kernel/trace/blktrace.c:780
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq_remap
  - kernel/trace/blktrace.c:blk_add_trace_rq_complete
  - kernel/trace/blktrace.c:blk_add_trace_rq_requeue
  - kernel/trace/blktrace.c:blk_add_trace_rq_issue
  - kernel/trace/blktrace.c:blk_add_trace_rq_insert
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
In kernel/trace/blktrace.c (ffffffff811b16d7)
Location: kernel/trace/blktrace.c:780
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq_remap
  - kernel/trace/blktrace.c:blk_add_trace_rq_complete
  - kernel/trace/blktrace.c:blk_add_trace_rq_requeue
  - kernel/trace/blktrace.c:blk_add_trace_rq_issue
  - kernel/trace/blktrace.c:blk_add_trace_rq_insert
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
In kernel/trace/blktrace.c (ffffffff811a4677)
Location: kernel/trace/blktrace.c:780
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq_remap
  - kernel/trace/blktrace.c:blk_add_trace_rq_complete
  - kernel/trace/blktrace.c:blk_add_trace_rq_requeue
  - kernel/trace/blktrace.c:blk_add_trace_rq_issue
  - kernel/trace/blktrace.c:blk_add_trace_rq_insert
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
In kernel/trace/blktrace.c (ffffffff811af4a7)
Location: kernel/trace/blktrace.c:780
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq_remap
  - kernel/trace/blktrace.c:blk_add_trace_rq_complete
  - kernel/trace/blktrace.c:blk_add_trace_rq_requeue
  - kernel/trace/blktrace.c:blk_add_trace_rq_issue
  - kernel/trace/blktrace.c:blk_add_trace_rq_insert
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
In kernel/trace/blktrace.c (ffffffff811bd48f)
Location: kernel/trace/blktrace.c:780
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq_remap
  - kernel/trace/blktrace.c:blk_add_trace_rq_complete
  - kernel/trace/blktrace.c:blk_add_trace_rq_requeue
  - kernel/trace/blktrace.c:blk_add_trace_rq_issue
  - kernel/trace/blktrace.c:blk_add_trace_rq_insert
```
</details>
</li>
</ul>

## Differences
