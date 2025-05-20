# Function: <code>scan_movable_pages</code>

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
In mm/memory_hotplug.c (ffffffff8181a38b)
Location: mm/memory_hotplug.c:1412
Inline: True
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
In mm/memory_hotplug.c (ffffffff81893e25)
Location: mm/memory_hotplug.c:1532
Inline: True
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
In mm/memory_hotplug.c (ffffffff818c8573)
Location: mm/memory_hotplug.c:1537
Inline: True
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
In mm/memory_hotplug.c (ffffffff818ffb51)
Location: mm/memory_hotplug.c:1348
Inline: True
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
In mm/memory_hotplug.c (ffffffff81989b40)
Location: mm/memory_hotplug.c:1336
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
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
In mm/memory_hotplug.c (ffffffff819e6438)
Location: mm/memory_hotplug.c:1345
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
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
In mm/memory_hotplug.c (ffffffff81a2187f)
Location: mm/memory_hotplug.c:1321
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
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
In mm/memory_hotplug.c (ffffffff81a921f4)
Location: mm/memory_hotplug.c:1304
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
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
In mm/memory_hotplug.c (ffffffff81ac9984)
Location: mm/memory_hotplug.c:1279
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int scan_movable_pages(long unsigned int start, long unsigned int end, long unsigned int *movable_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff812e0d30)
Location: mm/memory_hotplug.c:1236
Inline: False
Direct callers:
  - mm/memory_hotplug.c:__offline_pages
```
**Symbols:**

```
ffffffff812e0d30-ffffffff812e0eec: scan_movable_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int scan_movable_pages(long unsigned int start, long unsigned int end, long unsigned int *movable_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff812ebb30)
Location: mm/memory_hotplug.c:1247
Inline: False
Direct callers:
  - mm/memory_hotplug.c:offline_pages
```
**Symbols:**

```
ffffffff812ebb30-ffffffff812ebce8: scan_movable_pages (STB_LOCAL)
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
In mm/memory_hotplug.c (ffffffff81c2d7cf)
Location: mm/memory_hotplug.c:1483
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
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
In mm/memory_hotplug.c (ffffffff81d4c0a5)
Location: mm/memory_hotplug.c:1642
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
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
In mm/memory_hotplug.c (ffffffff81f1ba19)
Location: mm/memory_hotplug.c:1578
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
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
In mm/memory_hotplug.c (ffffffff820c39a9)
Location: mm/memory_hotplug.c:1576
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
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
In mm/memory_hotplug.c (ffffffff8214778a)
Location: mm/memory_hotplug.c:1551
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
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
In mm/memory_hotplug.c (ffffffff82229fc7)
Location: mm/memory_hotplug.c:1733
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
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
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (c0000000004308b4)
Location: mm/memory_hotplug.c:1279
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
```
</details>
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
In mm/memory_hotplug.c (ffffffff81a687f4)
Location: mm/memory_hotplug.c:1279
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
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
In mm/memory_hotplug.c (ffffffff81a252b4)
Location: mm/memory_hotplug.c:1279
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
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
In mm/memory_hotplug.c (ffffffff81ad4c04)
Location: mm/memory_hotplug.c:1279
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
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
In mm/memory_hotplug.c (ffffffff81ae10df)
Location: mm/memory_hotplug.c:1279
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
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
