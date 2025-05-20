# Function: <code>walk_pgd_range</code>

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
In mm/pagewalk.c (ffffffff811cfdb3)
Location: mm/pagewalk.c:98
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
In mm/pagewalk.c (ffffffff811ecf13)
Location: mm/pagewalk.c:98
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
In mm/pagewalk.c (ffffffff811f7303)
Location: mm/pagewalk.c:98
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
In mm/pagewalk.c (ffffffff81202343)
Location: mm/pagewalk.c:142
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
In mm/pagewalk.c (ffffffff8121af42)
Location: mm/pagewalk.c:143
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
In mm/pagewalk.c (ffffffff8123cda3)
Location: mm/pagewalk.c:143
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int walk_pgd_range(long unsigned int addr, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pagewalk.c (ffffffff81251240)
Location: mm/pagewalk.c:143
Inline: False
```
**Symbols:**

```
ffffffff81251240-ffffffff81251869: walk_pgd_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int walk_pgd_range(long unsigned int addr, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pagewalk.c (ffffffff81263520)
Location: mm/pagewalk.c:143
Inline: False
```
**Symbols:**

```
ffffffff81263520-ffffffff81263b3f: walk_pgd_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int walk_pgd_range(long unsigned int addr, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pagewalk.c (ffffffff81271fe0)
Location: mm/pagewalk.c:147
Inline: False
```
**Symbols:**

```
ffffffff81271fe0-ffffffff8127233f: walk_pgd_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int walk_pgd_range(long unsigned int addr, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pagewalk.c (ffffffff812a2d60)
Location: mm/pagewalk.c:201
Inline: False
Direct callers:
  - mm/pagewalk.c:__walk_page_range
  - mm/pagewalk.c:__walk_page_range
```
**Symbols:**

```
ffffffff812a2d60-ffffffff812a2f00: walk_pgd_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int walk_pgd_range(long unsigned int addr, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pagewalk.c (ffffffff812ae680)
Location: mm/pagewalk.c:201
Inline: False
Direct callers:
  - mm/pagewalk.c:__walk_page_range
  - mm/pagewalk.c:__walk_page_range
```
**Symbols:**

```
ffffffff812ae680-ffffffff812ae820: walk_pgd_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int walk_pgd_range(long unsigned int addr, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pagewalk.c (ffffffff812b3a40)
Location: mm/pagewalk.c:201
Inline: False
Direct callers:
  - mm/pagewalk.c:__walk_page_range
  - mm/pagewalk.c:__walk_page_range
```
**Symbols:**

```
ffffffff812b3a40-ffffffff812b3be0: walk_pgd_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int walk_pgd_range(long unsigned int addr, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/pagewalk.c (0)
Location: mm/pagewalk.c:248
Inline: False
Direct callers:
  - mm/pagewalk.c:__walk_page_range
  - mm/pagewalk.c:__walk_page_range
```
**Symbols:**

```
ffffffff812f55c0-ffffffff812f5794: walk_pgd_range (STB_LOCAL)
ffffffff81cbcc1a-ffffffff81cbccc4: walk_pgd_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int walk_pgd_range(long unsigned int addr, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/pagewalk.c (0)
Location: mm/pagewalk.c:248
Inline: False
Direct callers:
  - mm/pagewalk.c:__walk_page_range
  - mm/pagewalk.c:__walk_page_range
```
**Symbols:**

```
ffffffff81359480-ffffffff81359655: walk_pgd_range (STB_LOCAL)
ffffffff81e6e845-ffffffff81e6e8f0: walk_pgd_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int walk_pgd_range(long unsigned int addr, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/pagewalk.c (0)
Location: mm/pagewalk.c:248
Inline: False
Direct callers:
  - mm/pagewalk.c:walk_page_range_novma
  - mm/pagewalk.c:__walk_page_range
```
**Symbols:**

```
ffffffff813d3d60-ffffffff813d3f35: walk_pgd_range (STB_LOCAL)
ffffffff82064712-ffffffff820647bd: walk_pgd_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int walk_pgd_range(long unsigned int addr, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/pagewalk.c (0)
Location: mm/pagewalk.c:264
Inline: False
Direct callers:
  - mm/pagewalk.c:walk_page_range_novma
  - mm/pagewalk.c:__walk_page_range
```
**Symbols:**

```
ffffffff81408730-ffffffff81408908: walk_pgd_range (STB_LOCAL)
ffffffff820e3e48-ffffffff820e3ef3: walk_pgd_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int walk_pgd_range(long unsigned int addr, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/pagewalk.c (0)
Location: mm/pagewalk.c:264
Inline: False
Direct callers:
  - mm/pagewalk.c:walk_page_range_novma
  - mm/pagewalk.c:__walk_page_range
```
**Symbols:**

```
ffffffff81434e50-ffffffff81435028: walk_pgd_range (STB_LOCAL)
ffffffff821c0a20-ffffffff821c0acb: walk_pgd_range.cold (STB_LOCAL)
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
In mm/pagewalk.c (ffff8000103078bc)
Location: mm/pagewalk.c:147
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int walk_pgd_range(long unsigned int addr, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pagewalk.c (c0524fe8)
Location: mm/pagewalk.c:147
Inline: False
Direct callers:
  - mm/pagewalk.c:walk_page_vma
  - mm/pagewalk.c:walk_page_range
```
**Symbols:**

```
c0524fe8-c05251e4: walk_pgd_range (STB_LOCAL)
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
In mm/pagewalk.c (c0000000003d65ac)
Location: mm/pagewalk.c:147
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
In mm/pagewalk.c (ffffffe0002129cc)
Location: mm/pagewalk.c:147
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int walk_pgd_range(long unsigned int addr, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pagewalk.c (ffffffff8126a630)
Location: mm/pagewalk.c:147
Inline: False
```
**Symbols:**

```
ffffffff8126a630-ffffffff8126a98f: walk_pgd_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int walk_pgd_range(long unsigned int addr, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pagewalk.c (ffffffff8125c520)
Location: mm/pagewalk.c:147
Inline: False
```
**Symbols:**

```
ffffffff8125c520-ffffffff8125caea: walk_pgd_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int walk_pgd_range(long unsigned int addr, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pagewalk.c (ffffffff812683d0)
Location: mm/pagewalk.c:147
Inline: False
```
**Symbols:**

```
ffffffff812683d0-ffffffff8126872f: walk_pgd_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int walk_pgd_range(long unsigned int addr, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pagewalk.c (ffffffff81277d50)
Location: mm/pagewalk.c:147
Inline: False
```
**Symbols:**

```
ffffffff81277d50-ffffffff812780b6: walk_pgd_range (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
