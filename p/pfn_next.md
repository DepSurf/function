# Function: <code>pfn_next</code>

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
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/memremap.c (ffffffff811e9b4d)
Location: kernel/memremap.c:106
Inline: True
Inline callers:
  - kernel/memremap.c:devm_memremap_pages
  - kernel/memremap.c:devm_memremap_pages_release
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
In kernel/memremap.c (ffffffff811fa149)
Location: kernel/memremap.c:77
Inline: True
Inline callers:
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
In mm/memremap.c (ffffffff812c25a2)
Location: mm/memremap.c:68
Inline: True
Inline callers:
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
In mm/memremap.c (ffffffff812d44db)
Location: mm/memremap.c:69
Inline: True
Inline callers:
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
In mm/memremap.c (ffffffff8130a7ad)
Location: mm/memremap.c:93
Inline: True
Inline callers:
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
In mm/memremap.c (ffffffff813163e4)
Location: mm/memremap.c:105
Inline: True
Inline callers:
  - mm/memremap.c:memunmap_pages
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
In mm/memremap.c (ffffffff8131c4ba)
Location: mm/memremap.c:105
Inline: True
Inline callers:
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
In mm/memremap.c (ffffffff813697b7)
Location: mm/memremap.c:105
Inline: True
Inline callers:
  - mm/memremap.c:memunmap_pages
```
</details>
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
In mm/memremap.c (c00000000046dc74)
Location: mm/memremap.c:69
Inline: True
Inline callers:
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
In mm/memremap.c (ffffffff812ccabb)
Location: mm/memremap.c:69
Inline: True
Inline callers:
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
In mm/memremap.c (ffffffff812bd92b)
Location: mm/memremap.c:69
Inline: True
Inline callers:
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
In mm/memremap.c (ffffffff812ca8cb)
Location: mm/memremap.c:69
Inline: True
Inline callers:
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
In mm/memremap.c (ffffffff812db5be)
Location: mm/memremap.c:69
Inline: True
Inline callers:
  - mm/memremap.c:memunmap_pages
```
</details>
</li>
</ul>

## Differences
