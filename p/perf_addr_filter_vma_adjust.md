# Function: <code>perf_addr_filter_vma_adjust</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff811fbec0)
Location: kernel/events/core.c:7458
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_addr_filters_apply
  - kernel/events/core.c:__perf_addr_filters_adjust
```
**Symbols:**

```
ffffffff811fbec0-ffffffff811fbf6e: perf_addr_filter_vma_adjust.isra.0 (STB_LOCAL)
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
In kernel/events/core.c (ffffffff81208f90)
Location: kernel/events/core.c:7574
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_addr_filters_apply
  - kernel/events/core.c:__perf_addr_filters_adjust
```
**Symbols:**

```
ffffffff81208f90-ffffffff8120903e: perf_addr_filter_vma_adjust.isra.0 (STB_LOCAL)
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
In kernel/events/core.c (ffffffff812326db)
Location: kernel/events/core.c:8125
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_addr_filters_apply
  - kernel/events/core.c:__perf_addr_filters_adjust
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
In kernel/events/core.c (ffffffff8123c2cb)
Location: kernel/events/core.c:8307
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_addr_filters_apply
  - kernel/events/core.c:__perf_addr_filters_adjust
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
In kernel/events/core.c (ffffffff8124091b)
Location: kernel/events/core.c:8436
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_addr_filters_apply
  - kernel/events/core.c:__perf_addr_filters_adjust
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
In kernel/events/core.c (ffffffff8127b39b)
Location: kernel/events/core.c:8556
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_addr_filters_apply
  - kernel/events/core.c:__perf_addr_filters_adjust
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
In kernel/events/core.c (ffffffff812cf181)
Location: kernel/events/core.c:8461
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_addr_filters_apply
  - kernel/events/core.c:__perf_addr_filters_adjust
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool perf_addr_filter_vma_adjust(struct perf_addr_filter *filter, struct vm_area_struct *vma, struct perf_addr_filter_range *fr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81337a4c)
Location: kernel/events/core.c:8743
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_addr_filters_adjust
Direct callers:
  - kernel/events/core.c:perf_event_addr_filters_apply
```
**Symbols:**

```
ffffffff81334200-ffffffff813342f9: perf_addr_filter_vma_adjust (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool perf_addr_filter_vma_adjust(struct perf_addr_filter *filter, struct vm_area_struct *vma, struct perf_addr_filter_range *fr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81368a73)
Location: kernel/events/core.c:8771
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_addr_filters_adjust
Direct callers:
  - kernel/events/core.c:perf_event_addr_filters_apply
```
**Symbols:**

```
ffffffff81364f70-ffffffff81365073: perf_addr_filter_vma_adjust (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool perf_addr_filter_vma_adjust(struct perf_addr_filter *filter, struct vm_area_struct *vma, struct perf_addr_filter_range *fr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff813918a3)
Location: kernel/events/core.c:8841
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_addr_filters_adjust
Direct callers:
  - kernel/events/core.c:perf_event_addr_filters_apply
```
**Symbols:**

```
ffffffff8138df40-ffffffff8138e043: perf_addr_filter_vma_adjust (STB_LOCAL)
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
In kernel/events/core.c (ffff8000102927d8)
Location: kernel/events/core.c:7574
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_addr_filters_apply
  - kernel/events/core.c:perf_event_mmap
```
**Symbols:**

```
ffff8000102927d8-ffff800010292894: perf_addr_filter_vma_adjust.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool perf_addr_filter_vma_adjust(struct perf_addr_filter *filter, struct vm_area_struct *vma, struct perf_addr_filter_range *fr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c04c028c)
Location: kernel/events/core.c:7574
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_addr_filters_apply
  - kernel/events/core.c:perf_event_mmap
```
**Symbols:**

```
c04c028c-c04c0354: perf_addr_filter_vma_adjust (STB_LOCAL)
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
In kernel/events/core.c (c0000000003408a0)
Location: kernel/events/core.c:7574
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_addr_filters_apply
  - kernel/events/core.c:perf_event_mmap
```
**Symbols:**

```
c0000000003408a0-c000000000340978: perf_addr_filter_vma_adjust.isra.0 (STB_LOCAL)
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
In kernel/events/core.c (ffffffe0001c4930)
Location: kernel/events/core.c:7574
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_addr_filters_apply
  - kernel/events/core.c:perf_event_mmap
```
**Symbols:**

```
ffffffe0001c4930-ffffffe0001c49c0: perf_addr_filter_vma_adjust.isra.0 (STB_LOCAL)
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
In kernel/events/core.c (ffffffff812015b0)
Location: kernel/events/core.c:7574
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_addr_filters_apply
  - kernel/events/core.c:__perf_addr_filters_adjust
```
**Symbols:**

```
ffffffff812015b0-ffffffff8120165e: perf_addr_filter_vma_adjust.isra.0 (STB_LOCAL)
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
In kernel/events/core.c (ffffffff811f4300)
Location: kernel/events/core.c:7574
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_addr_filters_apply
  - kernel/events/core.c:__perf_addr_filters_adjust
```
**Symbols:**

```
ffffffff811f4300-ffffffff811f43ae: perf_addr_filter_vma_adjust.isra.0 (STB_LOCAL)
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
In kernel/events/core.c (ffffffff811ff380)
Location: kernel/events/core.c:7574
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_addr_filters_apply
  - kernel/events/core.c:__perf_addr_filters_adjust
```
**Symbols:**

```
ffffffff811ff380-ffffffff811ff42e: perf_addr_filter_vma_adjust.isra.0 (STB_LOCAL)
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
In kernel/events/core.c (ffffffff8120e410)
Location: kernel/events/core.c:7574
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_addr_filters_apply
  - kernel/events/core.c:__perf_addr_filters_adjust
```
**Symbols:**

```
ffffffff8120e410-ffffffff8120e4be: perf_addr_filter_vma_adjust.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
