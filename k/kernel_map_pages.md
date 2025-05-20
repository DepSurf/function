# Function: <code>kernel_map_pages</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (0)
Location: include/linux/mm.h:2172
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/mm.h:2172
Inline: True
```
```
In mm/compaction.c (0)
Location: include/linux/mm.h:2172
Inline: True
```
```
In mm/page_isolation.c (0)
Location: include/linux/mm.h:2172
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (0)
Location: include/linux/mm.h:2299
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/mm.h:2299
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (0)
Location: include/linux/mm.h:2286
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/mm.h:2286
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (0)
Location: include/linux/mm.h:2402
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/mm.h:2402
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (0)
Location: include/linux/mm.h:2511
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/mm.h:2511
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (0)
Location: include/linux/mm.h:2644
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/mm.h:2644
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
In kernel/power/snapshot.c (0)
Location: include/linux/mm.h:2689
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/mm.h:2689
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
In kernel/power/snapshot.c (ffffffff81101629)
Location: include/linux/mm.h:2734
Inline: True
Inline callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_save
```
```
In mm/page_alloc.c (0)
Location: include/linux/mm.h:2734
Inline: True
```
```
In mm/memory_hotplug.c (ffffffff8129bbd5)
Location: include/linux/mm.h:2734
Inline: True
Inline callers:
  - mm/memory_hotplug.c:generic_online_page
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
In kernel/power/snapshot.c (ffffffff8110da5c)
Location: include/linux/mm.h:2725
Inline: True
Inline callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_save
```
```
In mm/page_alloc.c (0)
Location: include/linux/mm.h:2725
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/mm.h:2725
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
In kernel/power/snapshot.c (ffffffff8111818e)
Location: include/linux/mm.h:2972
Inline: True
Inline callers:
  - kernel/power/snapshot.c:safe_copy_page
  - kernel/power/snapshot.c:safe_copy_page
```
```
In mm/page_alloc.c (0)
Location: include/linux/mm.h:2972
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/mm.h:2972
Inline: True
```
</details>
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
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
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (0)
Location: include/linux/mm.h:2725
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/mm.h:2725
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
In kernel/power/snapshot.c (0)
Location: include/linux/mm.h:2734
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/mm.h:2734
Inline: True
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
In mm/page_alloc.c (0)
Location: include/linux/mm.h:2734
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/mm.h:2734
Inline: True
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
In mm/page_alloc.c (0)
Location: include/linux/mm.h:2734
Inline: True
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
In kernel/power/snapshot.c (ffffffff81105c7c)
Location: include/linux/mm.h:2725
Inline: True
Inline callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_save
```
```
In mm/page_alloc.c (0)
Location: include/linux/mm.h:2725
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/mm.h:2725
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
In kernel/power/snapshot.c (ffffffff810f6f1c)
Location: include/linux/mm.h:2725
Inline: True
Inline callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_save
```
```
In mm/page_alloc.c (0)
Location: include/linux/mm.h:2725
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/mm.h:2725
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
In kernel/power/snapshot.c (ffffffff81103f2c)
Location: include/linux/mm.h:2725
Inline: True
Inline callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_save
```
```
In mm/page_alloc.c (0)
Location: include/linux/mm.h:2725
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/mm.h:2725
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
In kernel/power/snapshot.c (ffffffff8110f31c)
Location: include/linux/mm.h:2725
Inline: True
Inline callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_save
```
```
In mm/page_alloc.c (0)
Location: include/linux/mm.h:2725
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/mm.h:2725
Inline: True
```
</details>
</li>
</ul>

## Differences
