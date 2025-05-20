# Function: <code>pgmap_array_delete</code>

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
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/memremap.c (ffffffff811fa57a)
Location: kernel/memremap.c:51
Inline: True
Inline callers:
  - kernel/memremap.c:devm_memremap_pages
  - kernel/memremap.c:devm_memremap_pages_release
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
In mm/memremap.c (ffffffff812c2bd8)
Location: mm/memremap.c:48
Inline: True
Inline callers:
  - mm/memremap.c:devm_memremap_pages
  - mm/memremap.c:devm_memremap_pages_release
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
In mm/memremap.c (ffffffff812d4a8b)
Location: mm/memremap.c:49
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memunmap_pages
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
In mm/memremap.c (ffffffff8130a5ba)
Location: mm/memremap.c:73
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memunmap_pages
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
In mm/memremap.c (ffffffff81315f47)
Location: mm/memremap.c:66
Inline: True
Inline callers:
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:pageunmap_range
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
In mm/memremap.c (ffffffff8131c143)
Location: mm/memremap.c:66
Inline: True
Inline callers:
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:memunmap_pages
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
In mm/memremap.c (ffffffff8136942f)
Location: mm/memremap.c:66
Inline: True
Inline callers:
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:memunmap_pages
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
In mm/memremap.c (ffffffff813e75b2)
Location: mm/memremap.c:65
Inline: True
Inline callers:
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:memunmap_pages
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
In mm/memremap.c (ffffffff8146f232)
Location: mm/memremap.c:65
Inline: True
Inline callers:
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:memunmap_pages
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
In mm/memremap.c (ffffffff814a3a04)
Location: mm/memremap.c:65
Inline: True
Inline callers:
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:memunmap_pages
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
In mm/memremap.c (ffffffff814d48b1)
Location: mm/memremap.c:66
Inline: True
Inline callers:
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:memunmap_pages
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
In mm/memremap.c (c00000000046e378)
Location: mm/memremap.c:49
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memunmap_pages
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
In mm/memremap.c (ffffffff812cd06b)
Location: mm/memremap.c:49
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memunmap_pages
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
In mm/memremap.c (ffffffff812bdedb)
Location: mm/memremap.c:49
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memunmap_pages
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
In mm/memremap.c (ffffffff812cae7b)
Location: mm/memremap.c:49
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memunmap_pages
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
In mm/memremap.c (ffffffff812dbbb9)
Location: mm/memremap.c:49
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memunmap_pages
```
</details>
</li>
</ul>

## Differences
