# Function: <code>node_states_clear_node</code>

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
In mm/memory_hotplug.c (ffffffff8181a896)
Location: mm/memory_hotplug.c:1700
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
In mm/memory_hotplug.c (ffffffff8189446e)
Location: mm/memory_hotplug.c:1849
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
In mm/memory_hotplug.c (ffffffff818c8b68)
Location: mm/memory_hotplug.c:1834
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
In mm/memory_hotplug.c (ffffffff819000e5)
Location: mm/memory_hotplug.c:1601
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
In mm/memory_hotplug.c (ffffffff81989d3c)
Location: mm/memory_hotplug.c:1591
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
In mm/memory_hotplug.c (ffffffff819e6875)
Location: mm/memory_hotplug.c:1600
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
In mm/memory_hotplug.c (ffffffff81a21dc3)
Location: mm/memory_hotplug.c:1559
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
In mm/memory_hotplug.c (ffffffff81a92427)
Location: mm/memory_hotplug.c:1513
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
In mm/memory_hotplug.c (ffffffff81ac9bb8)
Location: mm/memory_hotplug.c:1488
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
void node_states_clear_node(int node, struct memory_notify *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff812e0f40)
Location: mm/memory_hotplug.c:1453
Inline: False
Direct callers:
  - mm/memory_hotplug.c:__offline_pages
```
**Symbols:**

```
ffffffff812e0f40-ffffffff812e0f88: node_states_clear_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void node_states_clear_node(int node, struct memory_notify *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff812ebcf0)
Location: mm/memory_hotplug.c:1443
Inline: False
Direct callers:
  - mm/memory_hotplug.c:offline_pages
```
**Symbols:**

```
ffffffff812ebcf0-ffffffff812ebd38: node_states_clear_node (STB_LOCAL)
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
In mm/memory_hotplug.c (ffffffff81c2d96a)
Location: mm/memory_hotplug.c:1686
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
In mm/memory_hotplug.c (ffffffff81d4c256)
Location: mm/memory_hotplug.c:1851
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
In mm/memory_hotplug.c (ffffffff81f1bc3d)
Location: mm/memory_hotplug.c:1774
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
In mm/memory_hotplug.c (ffffffff820c3d0d)
Location: mm/memory_hotplug.c:1772
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
In mm/memory_hotplug.c (ffffffff821478f0)
Location: mm/memory_hotplug.c:1745
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
In mm/memory_hotplug.c (ffffffff8222a255)
Location: mm/memory_hotplug.c:1927
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
In mm/memory_hotplug.c (c000000000430b74)
Location: mm/memory_hotplug.c:1488
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
In mm/memory_hotplug.c (ffffffff81a68a28)
Location: mm/memory_hotplug.c:1488
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
In mm/memory_hotplug.c (ffffffff81a254e8)
Location: mm/memory_hotplug.c:1488
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
In mm/memory_hotplug.c (ffffffff81ad4e38)
Location: mm/memory_hotplug.c:1488
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
In mm/memory_hotplug.c (ffffffff81ae1313)
Location: mm/memory_hotplug.c:1488
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
