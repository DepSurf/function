# Function: <code>process_huge_page</code>

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
In mm/memory.c (ffffffff812317a7)
Location: mm/memory.c:4609
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
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
In mm/memory.c (ffffffff81244f87)
Location: mm/memory.c:4399
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
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
In mm/memory.c (ffffffff81256f57)
Location: mm/memory.c:4454
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
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
In mm/memory.c (ffffffff812654e7)
Location: mm/memory.c:4479
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
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
In mm/memory.c (ffffffff812958e1)
Location: mm/memory.c:4844
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
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
In mm/memory.c (ffffffff812a0758)
Location: mm/memory.c:5071
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
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
In mm/memory.c (ffffffff812a6098)
Location: mm/memory.c:5138
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
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
In mm/memory.c (ffffffff812e7528)
Location: mm/memory.c:5284
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
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
In mm/memory.c (ffffffff813487d9)
Location: mm/memory.c:5583
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
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
In mm/memory.c (ffffffff813c0cc9)
Location: mm/memory.c:5663
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
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
In mm/memory.c (ffffffff813f5a70)
Location: mm/memory.c:5869
Inline: True
Inline callers:
  - mm/memory.c:copy_user_large_folio
  - mm/memory.c:clear_huge_page
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
In mm/memory.c (ffffffff8142174d)
Location: mm/memory.c:6093
Inline: True
Inline callers:
  - mm/memory.c:copy_user_large_folio
  - mm/memory.c:clear_huge_page
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
In mm/memory.c (ffff8000102fbf2c)
Location: mm/memory.c:4479
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
```
</details>
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
In mm/memory.c (c0000000003c75d8)
Location: mm/memory.c:4479
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
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
In mm/memory.c (ffffffe00020b508)
Location: mm/memory.c:4479
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
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
In mm/memory.c (ffffffff8125db37)
Location: mm/memory.c:4479
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
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
In mm/memory.c (ffffffff8124ff87)
Location: mm/memory.c:4479
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
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
In mm/memory.c (ffffffff8125b8d7)
Location: mm/memory.c:4479
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
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
In mm/memory.c (ffffffff8126b2a1)
Location: mm/memory.c:4479
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
```
</details>
</li>
</ul>

## Differences
