# Function: <code>swsusp_extents_insert</code>

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
In kernel/power/swap.c (ffffffff810d4032)
Location: kernel/power/swap.c:122
Inline: True
Inline callers:
  - kernel/power/swap.c:alloc_swapdev_block
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
In kernel/power/swap.c (ffffffff810d8e31)
Location: kernel/power/swap.c:130
Inline: True
Inline callers:
  - kernel/power/swap.c:alloc_swapdev_block
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
In kernel/power/swap.c (ffffffff810df921)
Location: kernel/power/swap.c:130
Inline: True
Inline callers:
  - kernel/power/swap.c:alloc_swapdev_block
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
In kernel/power/swap.c (ffffffff810dea75)
Location: kernel/power/swap.c:130
Inline: True
Inline callers:
  - kernel/power/swap.c:alloc_swapdev_block
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
In kernel/power/swap.c (ffffffff810e6cf5)
Location: kernel/power/swap.c:132
Inline: True
Inline callers:
  - kernel/power/swap.c:alloc_swapdev_block
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
In kernel/power/swap.c (0)
Location: kernel/power/swap.c:132
Inline: True
Inline callers:
  - kernel/power/swap.c:alloc_swapdev_block
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
In kernel/power/swap.c (0)
Location: kernel/power/swap.c:132
Inline: True
Inline callers:
  - kernel/power/swap.c:alloc_swapdev_block
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
In kernel/power/swap.c (0)
Location: kernel/power/swap.c:130
Inline: True
Inline callers:
  - kernel/power/swap.c:alloc_swapdev_block
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
In kernel/power/swap.c (0)
Location: kernel/power/swap.c:130
Inline: True
Inline callers:
  - kernel/power/swap.c:alloc_swapdev_block
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int swsusp_extents_insert(long unsigned int swap_offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff81119890)
Location: kernel/power/swap.c:130
Inline: False
Direct callers:
  - kernel/power/swap.c:alloc_swapdev_block
```
**Symbols:**

```
ffffffff81119890-ffffffff81119982: swsusp_extents_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int swsusp_extents_insert(long unsigned int swap_offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff811150e0)
Location: kernel/power/swap.c:130
Inline: False
Direct callers:
  - kernel/power/swap.c:alloc_swapdev_block
```
**Symbols:**

```
ffffffff811150e0-ffffffff811151d2: swsusp_extents_insert (STB_LOCAL)
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
In kernel/power/swap.c (0)
Location: kernel/power/swap.c:130
Inline: True
Inline callers:
  - kernel/power/swap.c:alloc_swapdev_block
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
In kernel/power/swap.c (0)
Location: kernel/power/swap.c:130
Inline: True
Inline callers:
  - kernel/power/swap.c:alloc_swapdev_block
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
In kernel/power/swap.c (0)
Location: kernel/power/swap.c:132
Inline: True
Inline callers:
  - kernel/power/swap.c:alloc_swapdev_block
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
In kernel/power/swap.c (0)
Location: kernel/power/swap.c:132
Inline: True
Inline callers:
  - kernel/power/swap.c:alloc_swapdev_block
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
In kernel/power/swap.c (0)
Location: kernel/power/swap.c:132
Inline: True
Inline callers:
  - kernel/power/swap.c:alloc_swapdev_block
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
In kernel/power/swap.c (0)
Location: kernel/power/swap.c:132
Inline: True
Inline callers:
  - kernel/power/swap.c:alloc_swapdev_block
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (0)
Location: kernel/power/swap.c:130
Inline: True
Inline callers:
  - kernel/power/swap.c:alloc_swapdev_block
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In kernel/power/swap.c (0)
Location: kernel/power/swap.c:125
Inline: True
Inline callers:
  - kernel/power/swap.c:alloc_swapdev_block
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
In kernel/power/swap.c (0)
Location: kernel/power/swap.c:130
Inline: True
Inline callers:
  - kernel/power/swap.c:alloc_swapdev_block
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
In kernel/power/swap.c (0)
Location: kernel/power/swap.c:130
Inline: True
Inline callers:
  - kernel/power/swap.c:alloc_swapdev_block
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
In kernel/power/swap.c (0)
Location: kernel/power/swap.c:130
Inline: True
Inline callers:
  - kernel/power/swap.c:alloc_swapdev_block
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
