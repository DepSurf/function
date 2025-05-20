# Function: <code>walk_pmd_range</code>

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
In mm/pagewalk.c (ffffffff811cfe64)
Location: mm/pagewalk.c:27
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
In mm/pagewalk.c (ffffffff811ecf37)
Location: mm/pagewalk.c:27
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
In mm/pagewalk.c (ffffffff811f7327)
Location: mm/pagewalk.c:27
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
In mm/pagewalk.c (ffffffff81202366)
Location: mm/pagewalk.c:27
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
In mm/pagewalk.c (ffffffff8121b011)
Location: mm/pagewalk.c:28
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
In mm/pagewalk.c (ffffffff8123d070)
Location: mm/pagewalk.c:28
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
In mm/pagewalk.c (ffffffff81251533)
Location: mm/pagewalk.c:28
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
In mm/pagewalk.c (ffffffff812637fd)
Location: mm/pagewalk.c:28
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
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
In mm/pagewalk.c (ffffffff81271ce0)
Location: mm/pagewalk.c:29
Inline: True
Direct callers:
  - mm/pagewalk.c:walk_pgd_range
```
**Symbols:**

```
ffffffff81271ce0-ffffffff81271fd5: walk_pmd_range.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/pagewalk.c (ffffffff812a25e0)
Location: mm/pagewalk.c:61
Inline: True
```
**Symbols:**

```
ffffffff812a25e0-ffffffff812a2950: walk_pmd_range.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/pagewalk.c (ffffffff812adf20)
Location: mm/pagewalk.c:61
Inline: True
```
**Symbols:**

```
ffffffff812adf20-ffffffff812ae290: walk_pmd_range.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/pagewalk.c (ffffffff812b3310)
Location: mm/pagewalk.c:61
Inline: True
```
**Symbols:**

```
ffffffff812b3310-ffffffff812b367f: walk_pmd_range.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/pagewalk.c (0)
Location: mm/pagewalk.c:100
Inline: True
```
**Symbols:**

```
ffffffff812f4ea0-ffffffff812f520b: walk_pmd_range.isra.0 (STB_LOCAL)
ffffffff81cbcbc4-ffffffff81cbcbef: walk_pmd_range.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/pagewalk.c (0)
Location: mm/pagewalk.c:100
Inline: True
```
**Symbols:**

```
ffffffff81358db0-ffffffff813590c5: walk_pmd_range.isra.0 (STB_LOCAL)
ffffffff81e6e807-ffffffff81e6e822: walk_pmd_range.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
void walk_pmd_range(pud_t *pud, long unsigned int start, long unsigned int end, struct mm_walk *args);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/vmscan.c (0)
Location: mm/vmscan.c:4070
Inline: False
Direct callers:
  - mm/vmscan.c:walk_pud_range
```
```
In mm/pagewalk.c (ffffffff813d3690)
Location: mm/pagewalk.c:100
Inline: True
```
**Symbols:**

```
ffffffff8137f8e0-ffffffff8137fd76: walk_pmd_range (STB_LOCAL)
ffffffff820629c6-ffffffff820629ef: walk_pmd_range.cold (STB_LOCAL)
ffffffff813d3690-ffffffff813d399f: walk_pmd_range.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
void walk_pmd_range(pud_t *pud, long unsigned int start, long unsigned int end, struct mm_walk *args);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/vmscan.c (0)
Location: mm/vmscan.c:4158
Inline: False
Direct callers:
  - mm/vmscan.c:walk_pud_range
```
```
In mm/pagewalk.c (ffffffff814080e0)
Location: mm/pagewalk.c:115
Inline: True
```
**Symbols:**

```
ffffffff813b0e10-ffffffff813b128f: walk_pmd_range (STB_LOCAL)
ffffffff820e2139-ffffffff820e2162: walk_pmd_range.cold (STB_LOCAL)
ffffffff814080e0-ffffffff8140836d: walk_pmd_range.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
void walk_pmd_range(pud_t *pud, long unsigned int start, long unsigned int end, struct mm_walk *args);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/vmscan.c (0)
Location: mm/vmscan.c:3470
Inline: False
Direct callers:
  - mm/vmscan.c:walk_pud_range
```
```
In mm/pagewalk.c (ffffffff81434800)
Location: mm/pagewalk.c:115
Inline: True
```
**Symbols:**

```
ffffffff813da370-ffffffff813da80f: walk_pmd_range (STB_LOCAL)
ffffffff821beb08-ffffffff821beb31: walk_pmd_range.cold (STB_LOCAL)
ffffffff81434800-ffffffff81434a8d: walk_pmd_range.isra.0 (STB_LOCAL)
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
In mm/pagewalk.c (ffff800010307970)
Location: mm/pagewalk.c:29
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
In mm/pagewalk.c (c052506c)
Location: mm/pagewalk.c:29
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
In mm/pagewalk.c (c0000000003d6764)
Location: mm/pagewalk.c:29
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
Location: mm/pagewalk.c:29
Inline: True
```
</details>
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
In mm/pagewalk.c (ffffffff8126a330)
Location: mm/pagewalk.c:29
Inline: True
Direct callers:
  - mm/pagewalk.c:walk_pgd_range
```
**Symbols:**

```
ffffffff8126a330-ffffffff8126a625: walk_pmd_range.isra.0 (STB_LOCAL)
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
In mm/pagewalk.c (ffffffff8125c7f8)
Location: mm/pagewalk.c:29
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
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
In mm/pagewalk.c (ffffffff812680d0)
Location: mm/pagewalk.c:29
Inline: True
Direct callers:
  - mm/pagewalk.c:walk_pgd_range
```
**Symbols:**

```
ffffffff812680d0-ffffffff812683c5: walk_pmd_range.isra.0 (STB_LOCAL)
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
In mm/pagewalk.c (ffffffff81277a50)
Location: mm/pagewalk.c:29
Inline: True
Direct callers:
  - mm/pagewalk.c:walk_pgd_range
```
**Symbols:**

```
ffffffff81277a50-ffffffff81277d45: walk_pmd_range.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
