# Function: <code>do_move_pages_to_node</code>

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
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/migrate.c (ffffffff81271a74)
Location: mm/migrate.c:1472
Inline: True
Inline callers:
  - mm/migrate.c:kernel_move_pages
  - mm/migrate.c:kernel_move_pages
  - mm/migrate.c:kernel_move_pages
Direct callers:
  - mm/migrate.c:kernel_move_pages
  - mm/migrate.c:kernel_move_pages
  - mm/migrate.c:kernel_move_pages
```
**Symbols:**

```
ffffffff81271780-ffffffff812717ce: do_move_pages_to_node.isra.62.part.63 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/migrate.c (ffffffff81286094)
Location: mm/migrate.c:1505
Inline: True
Inline callers:
  - mm/migrate.c:kernel_move_pages
  - mm/migrate.c:kernel_move_pages
  - mm/migrate.c:kernel_move_pages
Direct callers:
  - mm/migrate.c:kernel_move_pages
  - mm/migrate.c:kernel_move_pages
  - mm/migrate.c:kernel_move_pages
```
**Symbols:**

```
ffffffff81285da0-ffffffff81285dee: do_move_pages_to_node.isra.58.part.59 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/migrate.c (ffffffff812a05e2)
Location: mm/migrate.c:1500
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:do_pages_move
Direct callers:
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:do_pages_move
```
**Symbols:**

```
ffffffff812a0490-ffffffff812a04e1: do_move_pages_to_node.isra.0.part.0 (STB_LOCAL)
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
In mm/migrate.c (ffffffff812b1991)
Location: mm/migrate.c:1501
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:do_pages_move
Direct callers:
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:do_pages_move
```
**Symbols:**

```
ffffffff812b1830-ffffffff812b1881: do_move_pages_to_node.isra.0.part.0 (STB_LOCAL)
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
In mm/migrate.c (ffffffff812e7095)
Location: mm/migrate.c:1518
Inline: True
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
In mm/migrate.c (ffffffff812f2612)
Location: mm/migrate.c:1635
Inline: True
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
In mm/migrate.c (ffffffff812f89b3)
Location: mm/migrate.c:1617
Inline: True
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
In mm/migrate.c (ffffffff81343067)
Location: mm/migrate.c:1661
Inline: True
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
In mm/migrate.c (ffffffff813b57ef)
Location: mm/migrate.c:1592
Inline: True
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
In mm/migrate.c (ffffffff814358ea)
Location: mm/migrate.c:1699
Inline: True
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
In mm/migrate.c (ffffffff8146b5fa)
Location: mm/migrate.c:2030
Inline: True
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
In mm/migrate.c (ffffffff8149a59a)
Location: mm/migrate.c:2054
Inline: True
Inline callers:
  - mm/migrate.c:move_pages_and_store_status
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
In mm/migrate.c (ffff800010352140)
Location: mm/migrate.c:1501
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:do_pages_move
Direct callers:
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:do_pages_move
```
**Symbols:**

```
ffff800010351e30-ffff800010351e9c: do_move_pages_to_node.isra.0.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/migrate.c (c00000000043896c)
Location: mm/migrate.c:1501
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:do_pages_move
Direct callers:
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:do_pages_move
```
**Symbols:**

```
c0000000004386a0-c000000000438734: do_move_pages_to_node.isra.0.part.0 (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/migrate.c (ffffffff812a9f71)
Location: mm/migrate.c:1501
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:do_pages_move
Direct callers:
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:do_pages_move
```
**Symbols:**

```
ffffffff812a9e10-ffffffff812a9e61: do_move_pages_to_node.isra.0.part.0 (STB_LOCAL)
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
In mm/migrate.c (ffffffff8129b8d1)
Location: mm/migrate.c:1501
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:do_pages_move
Direct callers:
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:do_pages_move
```
**Symbols:**

```
ffffffff8129b770-ffffffff8129b7c1: do_move_pages_to_node.isra.0.part.0 (STB_LOCAL)
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
In mm/migrate.c (ffffffff812a7d81)
Location: mm/migrate.c:1501
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:do_pages_move
Direct callers:
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:do_pages_move
```
**Symbols:**

```
ffffffff812a7c20-ffffffff812a7c71: do_move_pages_to_node.isra.0.part.0 (STB_LOCAL)
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
In mm/migrate.c (ffffffff812b8081)
Location: mm/migrate.c:1501
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:do_pages_move
Direct callers:
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:do_pages_move
```
**Symbols:**

```
ffffffff812b7f20-ffffffff812b7f71: do_move_pages_to_node.isra.0.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
