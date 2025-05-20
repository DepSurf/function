# Function: <code>walk_p4d_range</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/pagewalk.c (ffffffff81202366)
Location: mm/pagewalk.c:116
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
In mm/pagewalk.c (ffffffff8121af49)
Location: mm/pagewalk.c:117
Inline: True
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
In mm/pagewalk.c (ffffffff8123ce02)
Location: mm/pagewalk.c:117
Inline: True
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
In mm/pagewalk.c (ffffffff812512b7)
Location: mm/pagewalk.c:117
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
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
In mm/pagewalk.c (ffffffff81263597)
Location: mm/pagewalk.c:117
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
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
In mm/pagewalk.c (ffffffff8127205d)
Location: mm/pagewalk.c:120
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int walk_p4d_range(pgd_t *pgd, long unsigned int addr, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pagewalk.c (ffffffff812a2be0)
Location: mm/pagewalk.c:168
Inline: False
Direct callers:
  - mm/pagewalk.c:walk_pgd_range
```
**Symbols:**

```
ffffffff812a2be0-ffffffff812a2d54: walk_p4d_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int walk_p4d_range(pgd_t *pgd, long unsigned int addr, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pagewalk.c (ffffffff812ae500)
Location: mm/pagewalk.c:168
Inline: False
Direct callers:
  - mm/pagewalk.c:walk_pgd_range
```
**Symbols:**

```
ffffffff812ae500-ffffffff812ae674: walk_p4d_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int walk_p4d_range(pgd_t *pgd, long unsigned int addr, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pagewalk.c (ffffffff812b3900)
Location: mm/pagewalk.c:168
Inline: False
Direct callers:
  - mm/pagewalk.c:walk_pgd_range
```
**Symbols:**

```
ffffffff812b3900-ffffffff812b3a40: walk_p4d_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int walk_p4d_range(pgd_t *pgd, long unsigned int addr, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pagewalk.c (ffffffff812f5480)
Location: mm/pagewalk.c:213
Inline: False
Direct callers:
  - mm/pagewalk.c:walk_pgd_range
```
**Symbols:**

```
ffffffff812f5480-ffffffff812f55c0: walk_p4d_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int walk_p4d_range(pgd_t *pgd, long unsigned int addr, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pagewalk.c (ffffffff81359330)
Location: mm/pagewalk.c:213
Inline: False
Direct callers:
  - mm/pagewalk.c:walk_pgd_range
```
**Symbols:**

```
ffffffff81359330-ffffffff81359475: walk_p4d_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int walk_p4d_range(pgd_t *pgd, long unsigned int addr, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pagewalk.c (ffffffff813d3c00)
Location: mm/pagewalk.c:213
Inline: False
Direct callers:
  - mm/pagewalk.c:walk_pgd_range
```
**Symbols:**

```
ffffffff813d3c00-ffffffff813d3d45: walk_p4d_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int walk_p4d_range(pgd_t *pgd, long unsigned int addr, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pagewalk.c (ffffffff814085d0)
Location: mm/pagewalk.c:229
Inline: False
Direct callers:
  - mm/pagewalk.c:walk_pgd_range
```
**Symbols:**

```
ffffffff814085d0-ffffffff81408715: walk_p4d_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int walk_p4d_range(pgd_t *pgd, long unsigned int addr, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pagewalk.c (ffffffff81434cf0)
Location: mm/pagewalk.c:229
Inline: False
Direct callers:
  - mm/pagewalk.c:walk_pgd_range
```
**Symbols:**

```
ffffffff81434cf0-ffffffff81434e35: walk_p4d_range (STB_LOCAL)
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
In mm/pagewalk.c (ffff80001030790c)
Location: mm/pagewalk.c:120
Inline: True
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
In mm/pagewalk.c (c0525050)
Location: mm/pagewalk.c:120
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
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
In mm/pagewalk.c (c0000000003d66b0)
Location: mm/pagewalk.c:120
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
In mm/pagewalk.c (ffffffe0002129e8)
Location: mm/pagewalk.c:120
Inline: True
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
In mm/pagewalk.c (ffffffff8126a6ad)
Location: mm/pagewalk.c:120
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
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
In mm/pagewalk.c (ffffffff8125c5a0)
Location: mm/pagewalk.c:120
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
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
In mm/pagewalk.c (ffffffff8126844d)
Location: mm/pagewalk.c:120
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
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
In mm/pagewalk.c (ffffffff81277dcd)
Location: mm/pagewalk.c:120
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
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
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
