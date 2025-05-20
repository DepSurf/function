# Function: <code>pgd_ctor</code>

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
In arch/x86/mm/pgtable.c (ffffffff81070dda)
Location: arch/x86/mm/pgtable.c:116
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pgd_alloc
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
In arch/x86/mm/pgtable.c (ffffffff81070cea)
Location: arch/x86/mm/pgtable.c:116
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pgd_alloc
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
In arch/x86/mm/pgtable.c (ffffffff8107487a)
Location: arch/x86/mm/pgtable.c:116
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pgd_alloc
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
In arch/x86/mm/pgtable.c (ffffffff81073dca)
Location: arch/x86/mm/pgtable.c:124
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pgd_alloc
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
In arch/x86/mm/pgtable.c (ffffffff810797bd)
Location: arch/x86/mm/pgtable.c:125
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pgd_alloc
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
In arch/x86/mm/pgtable.c (ffffffff8107c38d)
Location: arch/x86/mm/pgtable.c:130
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pgd_alloc
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
In arch/x86/mm/pgtable.c (ffffffff81082d50)
Location: arch/x86/mm/pgtable.c:132
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pgd_alloc
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
In arch/x86/mm/pgtable.c (ffffffff81086980)
Location: arch/x86/mm/pgtable.c:116
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pgd_alloc
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
In arch/x86/mm/pgtable.c (ffffffff81087670)
Location: arch/x86/mm/pgtable.c:116
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pgd_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void pgd_ctor(struct mm_struct *mm, pgd_t *pgd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81089740)
Location: arch/x86/mm/pgtable.c:123
Inline: False
Direct callers:
  - arch/x86/mm/pgtable.c:pgd_alloc
```
**Symbols:**

```
ffffffff81089740-ffffffff8108987f: pgd_ctor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void pgd_ctor(struct mm_struct *mm, pgd_t *pgd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81089920)
Location: arch/x86/mm/pgtable.c:123
Inline: False
Direct callers:
  - arch/x86/mm/pgtable.c:pgd_alloc
```
**Symbols:**

```
ffffffff81089920-ffffffff81089a5f: pgd_ctor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void pgd_ctor(struct mm_struct *mm, pgd_t *pgd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff8108a5c0)
Location: arch/x86/mm/pgtable.c:123
Inline: False
Direct callers:
  - arch/x86/mm/pgtable.c:pgd_alloc
```
**Symbols:**

```
ffffffff8108a5c0-ffffffff8108a6ff: pgd_ctor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void pgd_ctor(struct mm_struct *mm, pgd_t *pgd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/mm/pgtable.c:123
Inline: False
Direct callers:
  - arch/x86/mm/pgtable.c:pgd_alloc
```
**Symbols:**

```
ffffffff81099b30-ffffffff81099c85: pgd_ctor (STB_LOCAL)
ffffffff81ca1093-ffffffff81ca1109: pgd_ctor.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void pgd_ctor(struct mm_struct *mm, pgd_t *pgd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/mm/pgtable.c:123
Inline: False
Direct callers:
  - arch/x86/mm/pgtable.c:pgd_alloc
```
**Symbols:**

```
ffffffff810acb40-ffffffff810acc9c: pgd_ctor (STB_LOCAL)
ffffffff81e50672-ffffffff81e5070a: pgd_ctor.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void pgd_ctor(struct mm_struct *mm, pgd_t *pgd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/mm/pgtable.c:123
Inline: False
Direct callers:
  - arch/x86/mm/pgtable.c:pgd_alloc
```
**Symbols:**

```
ffffffff810c6c10-ffffffff810c6d6c: pgd_ctor (STB_LOCAL)
ffffffff82054b53-ffffffff82054beb: pgd_ctor.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void pgd_ctor(struct mm_struct *mm, pgd_t *pgd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/mm/pgtable.c:123
Inline: False
Direct callers:
  - arch/x86/mm/pgtable.c:pgd_alloc
```
**Symbols:**

```
ffffffff810ca3b0-ffffffff810ca4bc: pgd_ctor (STB_LOCAL)
ffffffff820d3157-ffffffff820d31cf: pgd_ctor.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void pgd_ctor(struct mm_struct *mm, pgd_t *pgd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/mm/pgtable.c:126
Inline: False
Direct callers:
  - arch/x86/mm/pgtable.c:pgd_alloc
```
**Symbols:**

```
ffffffff810d28a0-ffffffff810d29ac: pgd_ctor (STB_LOCAL)
ffffffff821adfc5-ffffffff821ae03d: pgd_ctor.cold (STB_LOCAL)
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81086670)
Location: arch/x86/mm/pgtable.c:116
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pgd_alloc
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
In arch/x86/mm/pgtable.c (ffffffff8107537e)
Location: arch/x86/mm/pgtable.c:116
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pgd_alloc
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
In arch/x86/mm/pgtable.c (ffffffff81086620)
Location: arch/x86/mm/pgtable.c:116
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pgd_alloc
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
In arch/x86/mm/pgtable.c (ffffffff81088760)
Location: arch/x86/mm/pgtable.c:116
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pgd_alloc
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
