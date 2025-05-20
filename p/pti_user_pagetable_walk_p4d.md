# Function: <code>pti_user_pagetable_walk_p4d</code>

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
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
p4d_t *pti_user_pagetable_walk_p4d(long unsigned int address);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pti.c (ffffffff826c5402)
Location: arch/x86/mm/pti.c:152
Inline: True
Direct callers:
  - arch/x86/mm/pti.c:pti_init
  - arch/x86/mm/pti.c:pti_init
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
**Symbols:**

```
ffffffff826c5402-ffffffff826c5454: pti_user_pagetable_walk_p4d (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
p4d_t *pti_user_pagetable_walk_p4d(long unsigned int address);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pti.c (ffffffff810832c0)
Location: arch/x86/mm/pti.c:168
Inline: True
Direct callers:
  - arch/x86/mm/pti.c:pti_init
  - arch/x86/mm/pti.c:pti_init
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
**Symbols:**

```
ffffffff810832c0-ffffffff81083317: pti_user_pagetable_walk_p4d (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
p4d_t *pti_user_pagetable_walk_p4d(long unsigned int address);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pti.c (ffffffff81089e70)
Location: arch/x86/mm/pti.c:178
Inline: True
Direct callers:
  - arch/x86/mm/pti.c:pti_init
  - arch/x86/mm/pti.c:pti_init
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
**Symbols:**

```
ffffffff81089e70-ffffffff81089ec7: pti_user_pagetable_walk_p4d (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
p4d_t *pti_user_pagetable_walk_p4d(long unsigned int address);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pti.c (ffffffff8108dc20)
Location: arch/x86/mm/pti.c:172
Inline: True
Direct callers:
  - arch/x86/mm/pti.c:pti_init
  - arch/x86/mm/pti.c:pti_init
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
**Symbols:**

```
ffffffff8108dc20-ffffffff8108dc77: pti_user_pagetable_walk_p4d (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
p4d_t *pti_user_pagetable_walk_p4d(long unsigned int address);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pti.c (ffffffff8108e880)
Location: arch/x86/mm/pti.c:172
Inline: True
Direct callers:
  - arch/x86/mm/pti.c:pti_init
  - arch/x86/mm/pti.c:pti_init
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
**Symbols:**

```
ffffffff8108e880-ffffffff8108e8d7: pti_user_pagetable_walk_p4d (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
p4d_t *pti_user_pagetable_walk_p4d(long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pti.c (ffffffff81094ac0)
Location: arch/x86/mm/pti.c:172
Inline: False
Direct callers:
  - arch/x86/mm/pti.c:pti_clone_p4d
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
**Symbols:**

```
ffffffff81094ac0-ffffffff81094c30: pti_user_pagetable_walk_p4d (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
p4d_t *pti_user_pagetable_walk_p4d(long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pti.c (ffffffff81093e80)
Location: arch/x86/mm/pti.c:171
Inline: False
Direct callers:
  - arch/x86/mm/pti.c:pti_clone_p4d
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
**Symbols:**

```
ffffffff81093e80-ffffffff81093ff0: pti_user_pagetable_walk_p4d (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
p4d_t *pti_user_pagetable_walk_p4d(long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pti.c (ffffffff81094840)
Location: arch/x86/mm/pti.c:171
Inline: False
Direct callers:
  - arch/x86/mm/pti.c:pti_clone_p4d
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
**Symbols:**

```
ffffffff81094840-ffffffff81094989: pti_user_pagetable_walk_p4d (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
p4d_t *pti_user_pagetable_walk_p4d(long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pti.c (0)
Location: arch/x86/mm/pti.c:171
Inline: False
Direct callers:
  - arch/x86/mm/pti.c:pti_clone_p4d
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
**Symbols:**

```
ffffffff810a4790-ffffffff810a48f4: pti_user_pagetable_walk_p4d (STB_LOCAL)
ffffffff81ca2374-ffffffff81ca23a4: pti_user_pagetable_walk_p4d.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
p4d_t *pti_user_pagetable_walk_p4d(long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pti.c (0)
Location: arch/x86/mm/pti.c:171
Inline: False
Direct callers:
  - arch/x86/mm/pti.c:pti_clone_p4d
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
**Symbols:**

```
ffffffff810b9030-ffffffff810b919b: pti_user_pagetable_walk_p4d (STB_LOCAL)
ffffffff81e51a5d-ffffffff81e51a8d: pti_user_pagetable_walk_p4d.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
p4d_t *pti_user_pagetable_walk_p4d(long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pti.c (0)
Location: arch/x86/mm/pti.c:171
Inline: False
Direct callers:
  - arch/x86/mm/pti.c:pti_clone_p4d
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
**Symbols:**

```
ffffffff810d4980-ffffffff810d4af2: pti_user_pagetable_walk_p4d (STB_LOCAL)
ffffffff8205538a-ffffffff820553ba: pti_user_pagetable_walk_p4d.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
p4d_t *pti_user_pagetable_walk_p4d(long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pti.c (0)
Location: arch/x86/mm/pti.c:171
Inline: False
Direct callers:
  - arch/x86/mm/pti.c:pti_clone_p4d
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
**Symbols:**

```
ffffffff810d7e90-ffffffff810d8002: pti_user_pagetable_walk_p4d (STB_LOCAL)
ffffffff820d3955-ffffffff820d3985: pti_user_pagetable_walk_p4d.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
p4d_t *pti_user_pagetable_walk_p4d(long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pti.c (0)
Location: arch/x86/mm/pti.c:171
Inline: False
Direct callers:
  - arch/x86/mm/pti.c:pti_clone_p4d
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
**Symbols:**

```
ffffffff810e0710-ffffffff810e0882: pti_user_pagetable_walk_p4d (STB_LOCAL)
ffffffff821ae7c3-ffffffff821ae7f3: pti_user_pagetable_walk_p4d.cold (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
p4d_t *pti_user_pagetable_walk_p4d(long unsigned int address);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pti.c (ffffffff8108d840)
Location: arch/x86/mm/pti.c:172
Inline: True
Direct callers:
  - arch/x86/mm/pti.c:pti_init
  - arch/x86/mm/pti.c:pti_init
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
**Symbols:**

```
ffffffff8108d840-ffffffff8108d897: pti_user_pagetable_walk_p4d (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
p4d_t *pti_user_pagetable_walk_p4d(long unsigned int address);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pti.c (ffffffff8107c370)
Location: arch/x86/mm/pti.c:172
Inline: True
Direct callers:
  - arch/x86/mm/pti.c:pti_init
  - arch/x86/mm/pti.c:pti_init
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
**Symbols:**

```
ffffffff8107c370-ffffffff8107c3c7: pti_user_pagetable_walk_p4d (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
p4d_t *pti_user_pagetable_walk_p4d(long unsigned int address);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pti.c (ffffffff8108d7f0)
Location: arch/x86/mm/pti.c:172
Inline: True
Direct callers:
  - arch/x86/mm/pti.c:pti_init
  - arch/x86/mm/pti.c:pti_init
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
**Symbols:**

```
ffffffff8108d7f0-ffffffff8108d847: pti_user_pagetable_walk_p4d (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
p4d_t *pti_user_pagetable_walk_p4d(long unsigned int address);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pti.c (ffffffff8108fbd0)
Location: arch/x86/mm/pti.c:172
Inline: True
Direct callers:
  - arch/x86/mm/pti.c:pti_init
  - arch/x86/mm/pti.c:pti_init
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
**Symbols:**

```
ffffffff8108fbd0-ffffffff8108fc27: pti_user_pagetable_walk_p4d (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
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
