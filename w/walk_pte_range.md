# Function: <code>walk_pte_range</code>

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
In mm/pagewalk.c (ffffffff811cffed)
Location: mm/pagewalk.c:6
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
In mm/pagewalk.c (ffffffff811ed193)
Location: mm/pagewalk.c:6
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
In mm/pagewalk.c (ffffffff811f7583)
Location: mm/pagewalk.c:6
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
In mm/pagewalk.c (ffffffff812026b3)
Location: mm/pagewalk.c:6
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
Location: mm/pagewalk.c:7
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
In mm/pagewalk.c (ffffffff8123d215)
Location: mm/pagewalk.c:7
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
In mm/pagewalk.c (ffffffff812516ed)
Location: mm/pagewalk.c:7
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
In mm/pagewalk.c (ffffffff812639b4)
Location: mm/pagewalk.c:7
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
In mm/pagewalk.c (ffffffff81271e8d)
Location: mm/pagewalk.c:7
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int walk_pte_range(pmd_t *pmd, long unsigned int addr, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pagewalk.c (ffffffff812a2420)
Location: mm/pagewalk.c:41
Inline: False
```
**Symbols:**

```
ffffffff812a2420-ffffffff812a25d8: walk_pte_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int walk_pte_range(pmd_t *pmd, long unsigned int addr, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pagewalk.c (ffffffff812add60)
Location: mm/pagewalk.c:41
Inline: False
```
**Symbols:**

```
ffffffff812add60-ffffffff812adf14: walk_pte_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int walk_pte_range(pmd_t *pmd, long unsigned int addr, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pagewalk.c (ffffffff812b3150)
Location: mm/pagewalk.c:41
Inline: False
```
**Symbols:**

```
ffffffff812b3150-ffffffff812b3307: walk_pte_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int walk_pte_range(pmd_t *pmd, long unsigned int addr, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/pagewalk.c (0)
Location: mm/pagewalk.c:41
Inline: False
```
**Symbols:**

```
ffffffff812f4cd0-ffffffff812f4e96: walk_pte_range (STB_LOCAL)
ffffffff81cbcba7-ffffffff81cbcbc4: walk_pte_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int walk_pte_range(pmd_t *pmd, long unsigned int addr, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/pagewalk.c (0)
Location: mm/pagewalk.c:41
Inline: False
```
**Symbols:**

```
ffffffff81358ba0-ffffffff81358da2: walk_pte_range (STB_LOCAL)
ffffffff81e6e7e2-ffffffff81e6e807: walk_pte_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Transformation ⚠️</summary>

```c
bool walk_pte_range(pmd_t *pmd, long unsigned int start, long unsigned int end, struct mm_walk *args);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmscan.c (0)
Location: mm/vmscan.c:3915
Inline: False
Direct callers:
  - mm/vmscan.c:walk_pmd_range
```
```
In mm/pagewalk.c (0)
Location: mm/pagewalk.c:41
Inline: False
```
**Symbols:**

```
ffffffff8137e360-ffffffff8137e69a: walk_pte_range (STB_LOCAL)
ffffffff82062988-ffffffff820629a3: walk_pte_range.cold (STB_LOCAL)
ffffffff813d3470-ffffffff813d367d: walk_pte_range (STB_LOCAL)
ffffffff820646ed-ffffffff82064712: walk_pte_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Transformation ⚠️</summary>

```c
bool walk_pte_range(pmd_t *pmd, long unsigned int start, long unsigned int end, struct mm_walk *args);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmscan.c (0)
Location: mm/vmscan.c:4003
Inline: False
Direct callers:
  - mm/vmscan.c:walk_pmd_range
```
```
In mm/pagewalk.c (0)
Location: mm/pagewalk.c:41
Inline: False
```
**Symbols:**

```
ffffffff813ae540-ffffffff813ae820: walk_pte_range (STB_LOCAL)
ffffffff820e20ed-ffffffff820e2116: walk_pte_range.cold (STB_LOCAL)
ffffffff81407e90-ffffffff814080ce: walk_pte_range (STB_LOCAL)
ffffffff820e3e2b-ffffffff820e3e48: walk_pte_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Transformation ⚠️</summary>

```c
bool walk_pte_range(pmd_t *pmd, long unsigned int start, long unsigned int end, struct mm_walk *args);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmscan.c (0)
Location: mm/vmscan.c:3322
Inline: False
Direct callers:
  - mm/vmscan.c:walk_pmd_range
```
```
In mm/pagewalk.c (0)
Location: mm/pagewalk.c:41
Inline: False
```
**Symbols:**

```
ffffffff813d7b70-ffffffff813d7e7a: walk_pte_range (STB_LOCAL)
ffffffff821beabc-ffffffff821beae5: walk_pte_range.cold (STB_LOCAL)
ffffffff81434570-ffffffff814347ee: walk_pte_range (STB_LOCAL)
ffffffff821c09fb-ffffffff821c0a20: walk_pte_range.cold (STB_LOCAL)
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
In mm/pagewalk.c (ffff800010307a4c)
Location: mm/pagewalk.c:7
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
In mm/pagewalk.c (c0525118)
Location: mm/pagewalk.c:7
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
In mm/pagewalk.c (c0000000003d6b44)
Location: mm/pagewalk.c:7
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
In mm/pagewalk.c (ffffffe000212a8e)
Location: mm/pagewalk.c:7
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
In mm/pagewalk.c (ffffffff8126a4dd)
Location: mm/pagewalk.c:7
Inline: True
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
In mm/pagewalk.c (ffffffff8125c98d)
Location: mm/pagewalk.c:7
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
In mm/pagewalk.c (ffffffff8126827d)
Location: mm/pagewalk.c:7
Inline: True
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
In mm/pagewalk.c (ffffffff81277bfd)
Location: mm/pagewalk.c:7
Inline: True
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int start</code>
</li>
<li>
<b>Param added. </b>
<code>struct mm_walk *args</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int addr</code>
</li>
<li>
<b>Param removed. </b>
<code>struct mm_walk *walk</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
