# Function: <code>poison_pages</code>

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
In mm/page_poison.c (0)
Location: mm/page_poison.c:41
Inline: True
Inline callers:
  - mm/page_poison.c:kernel_poison_pages
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
In mm/page_poison.c (0)
Location: mm/page_poison.c:47
Inline: True
Inline callers:
  - mm/page_poison.c:kernel_poison_pages
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
In mm/page_poison.c (0)
Location: mm/page_poison.c:51
Inline: True
Inline callers:
  - mm/page_poison.c:kernel_poison_pages
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
In mm/page_poison.c (0)
Location: mm/page_poison.c:51
Inline: True
Inline callers:
  - mm/page_poison.c:kernel_poison_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void poison_pages(struct page *page, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_poison.c (ffffffff812d71c0)
Location: mm/page_poison.c:51
Inline: False
Direct callers:
  - mm/page_poison.c:kernel_poison_pages
```
**Symbols:**

```
ffffffff812d71c0-ffffffff812d7242: poison_pages (STB_LOCAL)
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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_poison.c (0)
Location: mm/page_poison.c:51
Inline: True
Inline callers:
  - mm/page_poison.c:kernel_poison_pages
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
In mm/page_poison.c (0)
Location: mm/page_poison.c:51
Inline: True
Inline callers:
  - mm/page_poison.c:kernel_poison_pages
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
In mm/page_poison.c (0)
Location: mm/page_poison.c:51
Inline: True
Inline callers:
  - mm/page_poison.c:kernel_poison_pages
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
In mm/page_poison.c (ffffffe0002366f6)
Location: mm/page_poison.c:51
Inline: True
Inline callers:
  - mm/page_poison.c:kernel_poison_pages
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
In mm/page_poison.c (0)
Location: mm/page_poison.c:51
Inline: True
Inline callers:
  - mm/page_poison.c:kernel_poison_pages
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
In mm/page_poison.c (0)
Location: mm/page_poison.c:51
Inline: True
Inline callers:
  - mm/page_poison.c:kernel_poison_pages
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
In mm/page_poison.c (0)
Location: mm/page_poison.c:51
Inline: True
Inline callers:
  - mm/page_poison.c:kernel_poison_pages
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
In mm/page_poison.c (0)
Location: mm/page_poison.c:51
Inline: True
Inline callers:
  - mm/page_poison.c:kernel_poison_pages
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
