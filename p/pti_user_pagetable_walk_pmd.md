# Function: <code>pti_user_pagetable_walk_pmd</code>

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
<summary>In <code>4.15</code>: ✅</summary>

```c
pmd_t *pti_user_pagetable_walk_pmd(long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pti.c (ffffffff826c5454)
Location: arch/x86/mm/pti.c:180
Inline: False
Direct callers:
  - arch/x86/mm/pti.c:pti_init
  - arch/x86/mm/pti.c:pti_init
```
**Symbols:**

```
ffffffff826c5454-ffffffff826c557f: pti_user_pagetable_walk_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
pmd_t *pti_user_pagetable_walk_pmd(long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pti.c (ffffffff81083320)
Location: arch/x86/mm/pti.c:196
Inline: False
Direct callers:
  - arch/x86/mm/pti.c:pti_init
```
**Symbols:**

```
ffffffff81083320-ffffffff810834be: pti_user_pagetable_walk_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
pmd_t *pti_user_pagetable_walk_pmd(long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pti.c (ffffffff81089ed0)
Location: arch/x86/mm/pti.c:206
Inline: False
Direct callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
**Symbols:**

```
ffffffff81089ed0-ffffffff8108a07c: pti_user_pagetable_walk_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
pmd_t *pti_user_pagetable_walk_pmd(long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pti.c (0)
Location: arch/x86/mm/pti.c:200
Inline: False
Direct callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
**Symbols:**

```
ffffffff8108dc80-ffffffff8108de1b: pti_user_pagetable_walk_pmd (STB_LOCAL)
ffffffff8108e041-ffffffff8108e057: pti_user_pagetable_walk_pmd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
pmd_t *pti_user_pagetable_walk_pmd(long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pti.c (ffffffff8108e8e0)
Location: arch/x86/mm/pti.c:200
Inline: False
Direct callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
**Symbols:**

```
ffffffff8108e8e0-ffffffff8108ea88: pti_user_pagetable_walk_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
pmd_t *pti_user_pagetable_walk_pmd(long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pti.c (ffffffff81094c30)
Location: arch/x86/mm/pti.c:200
Inline: False
Direct callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
**Symbols:**

```
ffffffff81094c30-ffffffff81094dd1: pti_user_pagetable_walk_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
pmd_t *pti_user_pagetable_walk_pmd(long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pti.c (ffffffff81093ff0)
Location: arch/x86/mm/pti.c:199
Inline: False
Direct callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
**Symbols:**

```
ffffffff81093ff0-ffffffff81094191: pti_user_pagetable_walk_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
pmd_t *pti_user_pagetable_walk_pmd(long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pti.c (ffffffff81094990)
Location: arch/x86/mm/pti.c:199
Inline: False
Direct callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
**Symbols:**

```
ffffffff81094990-ffffffff81094b33: pti_user_pagetable_walk_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
pmd_t *pti_user_pagetable_walk_pmd(long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pti.c (ffffffff810a4900)
Location: arch/x86/mm/pti.c:199
Inline: False
Direct callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
**Symbols:**

```
ffffffff810a4900-ffffffff810a4aa5: pti_user_pagetable_walk_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
pmd_t *pti_user_pagetable_walk_pmd(long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pti.c (ffffffff810b91a0)
Location: arch/x86/mm/pti.c:199
Inline: False
Direct callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
**Symbols:**

```
ffffffff810b91a0-ffffffff810b934d: pti_user_pagetable_walk_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
pmd_t *pti_user_pagetable_walk_pmd(long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pti.c (ffffffff810d4b10)
Location: arch/x86/mm/pti.c:199
Inline: False
Direct callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
**Symbols:**

```
ffffffff810d4b10-ffffffff810d4cc5: pti_user_pagetable_walk_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
pmd_t *pti_user_pagetable_walk_pmd(long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pti.c (ffffffff810d8020)
Location: arch/x86/mm/pti.c:199
Inline: False
Direct callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
**Symbols:**

```
ffffffff810d8020-ffffffff810d81cf: pti_user_pagetable_walk_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
pmd_t *pti_user_pagetable_walk_pmd(long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pti.c (ffffffff810e08a0)
Location: arch/x86/mm/pti.c:199
Inline: False
Direct callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
**Symbols:**

```
ffffffff810e08a0-ffffffff810e0a4f: pti_user_pagetable_walk_pmd (STB_LOCAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
pmd_t *pti_user_pagetable_walk_pmd(long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pti.c (ffffffff8108d8a0)
Location: arch/x86/mm/pti.c:200
Inline: False
Direct callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
**Symbols:**

```
ffffffff8108d8a0-ffffffff8108da48: pti_user_pagetable_walk_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
pmd_t *pti_user_pagetable_walk_pmd(long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pti.c (ffffffff8107c3d0)
Location: arch/x86/mm/pti.c:200
Inline: False
Direct callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
**Symbols:**

```
ffffffff8107c3d0-ffffffff8107c59e: pti_user_pagetable_walk_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
pmd_t *pti_user_pagetable_walk_pmd(long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pti.c (ffffffff8108d850)
Location: arch/x86/mm/pti.c:200
Inline: False
Direct callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
**Symbols:**

```
ffffffff8108d850-ffffffff8108d9f8: pti_user_pagetable_walk_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
pmd_t *pti_user_pagetable_walk_pmd(long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pti.c (ffffffff8108fc30)
Location: arch/x86/mm/pti.c:200
Inline: False
Direct callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
**Symbols:**

```
ffffffff8108fc30-ffffffff8108fdd8: pti_user_pagetable_walk_pmd (STB_LOCAL)
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
