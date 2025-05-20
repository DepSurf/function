# Function: <code>pti_user_pagetable_walk_pte</code>

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
In arch/x86/mm/pti.c (ffffffff826c5802)
Location: arch/x86/mm/pti.c:222
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
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
In arch/x86/mm/pti.c (ffffffff826ef8f5)
Location: arch/x86/mm/pti.c:242
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
pte_t *pti_user_pagetable_walk_pte(long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pti.c (ffffffff8108a30e)
Location: arch/x86/mm/pti.c:251
Inline: False
Direct callers:
  - arch/x86/mm/pti.c:pti_init
  - arch/x86/mm/pti.c:pti_init
```
**Symbols:**

```
ffffffff8108a30e-ffffffff8108a42e: pti_user_pagetable_walk_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
pte_t *pti_user_pagetable_walk_pte(long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pti.c (ffffffff8108e057)
Location: arch/x86/mm/pti.c:245
Inline: False
Direct callers:
  - arch/x86/mm/pti.c:pti_init
  - arch/x86/mm/pti.c:pti_init
```
**Symbols:**

```
ffffffff8108e057-ffffffff8108e183: pti_user_pagetable_walk_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
pte_t *pti_user_pagetable_walk_pte(long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pti.c (ffffffff8108ed00)
Location: arch/x86/mm/pti.c:245
Inline: False
Direct callers:
  - arch/x86/mm/pti.c:pti_init
  - arch/x86/mm/pti.c:pti_init
```
**Symbols:**

```
ffffffff8108ed00-ffffffff8108ee20: pti_user_pagetable_walk_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
pte_t *pti_user_pagetable_walk_pte(long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pti.c (ffffffff810950c7)
Location: arch/x86/mm/pti.c:245
Inline: False
Direct callers:
  - arch/x86/mm/pti.c:pti_clone_user_shared
  - arch/x86/mm/pti.c:pti_setup_vsyscall
```
**Symbols:**

```
ffffffff810950c7-ffffffff810951ca: pti_user_pagetable_walk_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
pte_t *pti_user_pagetable_walk_pte(long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pti.c (ffffffff81bda1eb)
Location: arch/x86/mm/pti.c:244
Inline: False
Direct callers:
  - arch/x86/mm/pti.c:pti_clone_user_shared
  - arch/x86/mm/pti.c:pti_setup_vsyscall
```
**Symbols:**

```
ffffffff81bda1eb-ffffffff81bda2ee: pti_user_pagetable_walk_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
pte_t *pti_user_pagetable_walk_pte(long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pti.c (ffffffff81bcc312)
Location: arch/x86/mm/pti.c:244
Inline: False
Direct callers:
  - arch/x86/mm/pti.c:pti_init
  - arch/x86/mm/pti.c:pti_init
```
**Symbols:**

```
ffffffff81bcc312-ffffffff81bcc412: pti_user_pagetable_walk_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
pte_t *pti_user_pagetable_walk_pte(long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pti.c (ffffffff81ca23a4)
Location: arch/x86/mm/pti.c:244
Inline: False
Direct callers:
  - arch/x86/mm/pti.c:pti_init
  - arch/x86/mm/pti.c:pti_init
```
**Symbols:**

```
ffffffff81ca23a4-ffffffff81ca24ba: pti_user_pagetable_walk_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
pte_t *pti_user_pagetable_walk_pte(long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pti.c (ffffffff81e51a8d)
Location: arch/x86/mm/pti.c:244
Inline: False
Direct callers:
  - arch/x86/mm/pti.c:pti_init
  - arch/x86/mm/pti.c:pti_init
```
**Symbols:**

```
ffffffff81e51a8d-ffffffff81e51bb7: pti_user_pagetable_walk_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
pte_t *pti_user_pagetable_walk_pte(long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pti.c (0)
Location: arch/x86/mm/pti.c:244
Inline: False
Direct callers:
  - arch/x86/mm/pti.c:pti_init
  - arch/x86/mm/pti.c:pti_clone_user_shared
```
**Symbols:**

```
ffffffff810d4ce0-ffffffff810d4e76: pti_user_pagetable_walk_pte (STB_LOCAL)
ffffffff820553ba-ffffffff820553ce: pti_user_pagetable_walk_pte.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
pte_t *pti_user_pagetable_walk_pte(long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pti.c (0)
Location: arch/x86/mm/pti.c:244
Inline: False
Direct callers:
  - arch/x86/mm/pti.c:pti_init
  - arch/x86/mm/pti.c:pti_clone_user_shared
```
**Symbols:**

```
ffffffff810d81e0-ffffffff810d8376: pti_user_pagetable_walk_pte (STB_LOCAL)
ffffffff820d3985-ffffffff820d3999: pti_user_pagetable_walk_pte.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
pte_t *pti_user_pagetable_walk_pte(long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pti.c (0)
Location: arch/x86/mm/pti.c:244
Inline: False
Direct callers:
  - arch/x86/mm/pti.c:pti_init
  - arch/x86/mm/pti.c:pti_clone_user_shared
```
**Symbols:**

```
ffffffff810e0a60-ffffffff810e0bf6: pti_user_pagetable_walk_pte (STB_LOCAL)
ffffffff821ae7f3-ffffffff821ae807: pti_user_pagetable_walk_pte.cold (STB_LOCAL)
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
pte_t *pti_user_pagetable_walk_pte(long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pti.c (ffffffff8108dcc0)
Location: arch/x86/mm/pti.c:245
Inline: False
Direct callers:
  - arch/x86/mm/pti.c:pti_init
  - arch/x86/mm/pti.c:pti_init
```
**Symbols:**

```
ffffffff8108dcc0-ffffffff8108dde0: pti_user_pagetable_walk_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
pte_t *pti_user_pagetable_walk_pte(long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pti.c (ffffffff8107c7e0)
Location: arch/x86/mm/pti.c:245
Inline: False
Direct callers:
  - arch/x86/mm/pti.c:pti_init
  - arch/x86/mm/pti.c:pti_init
```
**Symbols:**

```
ffffffff8107c7e0-ffffffff8107c8f0: pti_user_pagetable_walk_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
pte_t *pti_user_pagetable_walk_pte(long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pti.c (ffffffff8108dc70)
Location: arch/x86/mm/pti.c:245
Inline: False
Direct callers:
  - arch/x86/mm/pti.c:pti_init
  - arch/x86/mm/pti.c:pti_init
```
**Symbols:**

```
ffffffff8108dc70-ffffffff8108dd90: pti_user_pagetable_walk_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
pte_t *pti_user_pagetable_walk_pte(long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pti.c (ffffffff81090050)
Location: arch/x86/mm/pti.c:245
Inline: False
Direct callers:
  - arch/x86/mm/pti.c:pti_init
  - arch/x86/mm/pti.c:pti_init
```
**Symbols:**

```
ffffffff81090050-ffffffff81090170: pti_user_pagetable_walk_pte (STB_LOCAL)
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
