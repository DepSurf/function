# Function: <code>ptdump_walk_user_pgd_level_checkwx</code>

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
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/dump_pagetables.c (ffffffff8107cb09)
Location: arch/x86/mm/dump_pagetables.c:543
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_checkwx
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
In arch/x86/mm/dump_pagetables.c (ffffffff8107f7f9)
Location: arch/x86/mm/dump_pagetables.c:566
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_checkwx
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void ptdump_walk_user_pgd_level_checkwx();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/dump_pagetables.c (0)
Location: arch/x86/mm/dump_pagetables.c:589
Inline: False
Direct callers:
  - arch/x86/mm/pti.c:pti_finalize
  - arch/x86/mm/pti.c:pti_finalize
```
**Symbols:**

```
ffffffff8108661f-ffffffff8108664c: ptdump_walk_user_pgd_level_checkwx.cold.8 (STB_LOCAL)
ffffffff81086330-ffffffff81086350: ptdump_walk_user_pgd_level_checkwx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void ptdump_walk_user_pgd_level_checkwx();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/dump_pagetables.c (0)
Location: arch/x86/mm/dump_pagetables.c:584
Inline: False
Direct callers:
  - arch/x86/mm/pti.c:pti_finalize
  - arch/x86/mm/pti.c:pti_finalize
```
**Symbols:**

```
ffffffff8108a227-ffffffff8108a254: ptdump_walk_user_pgd_level_checkwx.cold (STB_LOCAL)
ffffffff81089ed0-ffffffff81089ef8: ptdump_walk_user_pgd_level_checkwx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void ptdump_walk_user_pgd_level_checkwx();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/dump_pagetables.c (0)
Location: arch/x86/mm/dump_pagetables.c:584
Inline: False
Direct callers:
  - arch/x86/mm/pti.c:pti_finalize
  - arch/x86/mm/pti.c:pti_finalize
```
**Symbols:**

```
ffffffff8108aea3-ffffffff8108aed0: ptdump_walk_user_pgd_level_checkwx.cold (STB_LOCAL)
ffffffff8108ab40-ffffffff8108ab68: ptdump_walk_user_pgd_level_checkwx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void ptdump_walk_user_pgd_level_checkwx();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/dump_pagetables.c (0)
Location: arch/x86/mm/dump_pagetables.c:419
Inline: False
Direct callers:
  - arch/x86/mm/pti.c:pti_finalize
```
**Symbols:**

```
ffffffff81092243-ffffffff81092274: ptdump_walk_user_pgd_level_checkwx.cold (STB_LOCAL)
ffffffff81091fa0-ffffffff81091fc8: ptdump_walk_user_pgd_level_checkwx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void ptdump_walk_user_pgd_level_checkwx();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/dump_pagetables.c (0)
Location: arch/x86/mm/dump_pagetables.c:419
Inline: False
Direct callers:
  - arch/x86/mm/pti.c:pti_finalize
```
**Symbols:**

```
ffffffff81bd9ec8-ffffffff81bd9ef9: ptdump_walk_user_pgd_level_checkwx.cold (STB_LOCAL)
ffffffff810918c0-ffffffff810918e8: ptdump_walk_user_pgd_level_checkwx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void ptdump_walk_user_pgd_level_checkwx();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/dump_pagetables.c (0)
Location: arch/x86/mm/dump_pagetables.c:419
Inline: False
Direct callers:
  - arch/x86/mm/pti.c:pti_finalize
  - arch/x86/mm/pti.c:pti_finalize
```
**Symbols:**

```
ffffffff81bcbf33-ffffffff81bcbf65: ptdump_walk_user_pgd_level_checkwx.cold (STB_LOCAL)
ffffffff810923b0-ffffffff810923d3: ptdump_walk_user_pgd_level_checkwx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void ptdump_walk_user_pgd_level_checkwx();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/dump_pagetables.c (0)
Location: arch/x86/mm/dump_pagetables.c:419
Inline: False
Direct callers:
  - arch/x86/mm/pti.c:pti_finalize
  - arch/x86/mm/pti.c:pti_finalize
```
**Symbols:**

```
ffffffff81ca1d55-ffffffff81ca1d87: ptdump_walk_user_pgd_level_checkwx.cold (STB_LOCAL)
ffffffff810a2070-ffffffff810a2093: ptdump_walk_user_pgd_level_checkwx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void ptdump_walk_user_pgd_level_checkwx();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/dump_pagetables.c (0)
Location: arch/x86/mm/dump_pagetables.c:419
Inline: False
Direct callers:
  - arch/x86/mm/pti.c:pti_finalize
  - arch/x86/mm/pti.c:pti_finalize
```
**Symbols:**

```
ffffffff81e513a5-ffffffff81e513e8: ptdump_walk_user_pgd_level_checkwx.cold (STB_LOCAL)
ffffffff810b65b0-ffffffff810b65f5: ptdump_walk_user_pgd_level_checkwx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ptdump_walk_user_pgd_level_checkwx();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/dump_pagetables.c (ffffffff810d1820)
Location: arch/x86/mm/dump_pagetables.c:419
Inline: False
Direct callers:
  - arch/x86/mm/pti.c:pti_finalize
  - arch/x86/mm/pti.c:pti_finalize
```
**Symbols:**

```
ffffffff810d1820-ffffffff810d1892: ptdump_walk_user_pgd_level_checkwx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ptdump_walk_user_pgd_level_checkwx();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/dump_pagetables.c (ffffffff810d4cd0)
Location: arch/x86/mm/dump_pagetables.c:419
Inline: False
Direct callers:
  - arch/x86/mm/pti.c:pti_finalize
  - arch/x86/mm/pti.c:pti_finalize
```
**Symbols:**

```
ffffffff810d4cd0-ffffffff810d4d42: ptdump_walk_user_pgd_level_checkwx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ptdump_walk_user_pgd_level_checkwx();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/dump_pagetables.c (ffffffff810dd470)
Location: arch/x86/mm/dump_pagetables.c:419
Inline: False
Direct callers:
  - arch/x86/mm/pti.c:pti_finalize
  - arch/x86/mm/pti.c:pti_finalize
```
**Symbols:**

```
ffffffff810dd470-ffffffff810dd4e2: ptdump_walk_user_pgd_level_checkwx (STB_GLOBAL)
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
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void ptdump_walk_user_pgd_level_checkwx();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/dump_pagetables.c (0)
Location: arch/x86/mm/dump_pagetables.c:584
Inline: False
Direct callers:
  - arch/x86/mm/pti.c:pti_finalize
  - arch/x86/mm/pti.c:pti_finalize
```
**Symbols:**

```
ffffffff81089e63-ffffffff81089e90: ptdump_walk_user_pgd_level_checkwx.cold (STB_LOCAL)
ffffffff81089b00-ffffffff81089b28: ptdump_walk_user_pgd_level_checkwx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void ptdump_walk_user_pgd_level_checkwx();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/dump_pagetables.c (0)
Location: arch/x86/mm/dump_pagetables.c:584
Inline: False
Direct callers:
  - arch/x86/mm/pti.c:pti_finalize
  - arch/x86/mm/pti.c:pti_finalize
```
**Symbols:**

```
ffffffff81078a43-ffffffff81078a70: ptdump_walk_user_pgd_level_checkwx.cold (STB_LOCAL)
ffffffff810786e0-ffffffff81078708: ptdump_walk_user_pgd_level_checkwx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void ptdump_walk_user_pgd_level_checkwx();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/dump_pagetables.c (0)
Location: arch/x86/mm/dump_pagetables.c:584
Inline: False
Direct callers:
  - arch/x86/mm/pti.c:pti_finalize
  - arch/x86/mm/pti.c:pti_finalize
```
**Symbols:**

```
ffffffff81089e13-ffffffff81089e40: ptdump_walk_user_pgd_level_checkwx.cold (STB_LOCAL)
ffffffff81089ab0-ffffffff81089ad8: ptdump_walk_user_pgd_level_checkwx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void ptdump_walk_user_pgd_level_checkwx();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/dump_pagetables.c (0)
Location: arch/x86/mm/dump_pagetables.c:584
Inline: False
Direct callers:
  - arch/x86/mm/pti.c:pti_finalize
  - arch/x86/mm/pti.c:pti_finalize
```
**Symbols:**

```
ffffffff8108c0b3-ffffffff8108c0e0: ptdump_walk_user_pgd_level_checkwx.cold (STB_LOCAL)
ffffffff8108bd50-ffffffff8108bd78: ptdump_walk_user_pgd_level_checkwx (STB_GLOBAL)
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
