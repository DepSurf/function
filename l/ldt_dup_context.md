# Function: <code>ldt_dup_context</code>

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
int ldt_dup_context(struct mm_struct *old_mm, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81032300)
Location: arch/x86/kernel/ldt.c:252
Inline: False
```
**Symbols:**

```
ffffffff81032300-ffffffff810323c2: ldt_dup_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ldt_dup_context(struct mm_struct *old_mm, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff810337f0)
Location: arch/x86/kernel/ldt.c:256
Inline: False
Direct callers:
  - kernel/fork.c:copy_mm
```
**Symbols:**

```
ffffffff810337f0-ffffffff810338b4: ldt_dup_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ldt_dup_context(struct mm_struct *old_mm, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81034b50)
Location: arch/x86/kernel/ldt.c:359
Inline: False
```
**Symbols:**

```
ffffffff81034b50-ffffffff81034c14: ldt_dup_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ldt_dup_context(struct mm_struct *old_mm, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81036a10)
Location: arch/x86/kernel/ldt.c:359
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
```
**Symbols:**

```
ffffffff81036a10-ffffffff81036afb: ldt_dup_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ldt_dup_context(struct mm_struct *old_mm, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81037240)
Location: arch/x86/kernel/ldt.c:359
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
```
**Symbols:**

```
ffffffff81037240-ffffffff8103732b: ldt_dup_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ldt_dup_context(struct mm_struct *old_mm, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff810390f0)
Location: arch/x86/kernel/ldt.c:443
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
```
**Symbols:**

```
ffffffff810390f0-ffffffff810391cb: ldt_dup_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ldt_dup_context(struct mm_struct *old_mm, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81039a20)
Location: arch/x86/kernel/ldt.c:443
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
```
**Symbols:**

```
ffffffff81039a20-ffffffff81039afb: ldt_dup_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ldt_dup_context(struct mm_struct *old_mm, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff8103b4f0)
Location: arch/x86/kernel/ldt.c:449
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
```
**Symbols:**

```
ffffffff8103b4f0-ffffffff8103b5cb: ldt_dup_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ldt_dup_context(struct mm_struct *old_mm, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81040f50)
Location: arch/x86/kernel/ldt.c:449
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
```
**Symbols:**

```
ffffffff81040f50-ffffffff8104102b: ldt_dup_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ldt_dup_context(struct mm_struct *old_mm, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81048a70)
Location: arch/x86/kernel/ldt.c:449
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
```
**Symbols:**

```
ffffffff81048a70-ffffffff81048b50: ldt_dup_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ldt_dup_context(struct mm_struct *old_mm, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff810537d0)
Location: arch/x86/kernel/ldt.c:449
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
```
**Symbols:**

```
ffffffff810537d0-ffffffff810538b0: ldt_dup_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ldt_dup_context(struct mm_struct *old_mm, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff810547b0)
Location: arch/x86/kernel/ldt.c:451
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
```
**Symbols:**

```
ffffffff810547b0-ffffffff81054890: ldt_dup_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ldt_dup_context(struct mm_struct *old_mm, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff8105b9f0)
Location: arch/x86/kernel/ldt.c:451
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
```
**Symbols:**

```
ffffffff8105b9f0-ffffffff8105bad0: ldt_dup_context (STB_GLOBAL)
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
int ldt_dup_context(struct mm_struct *old_mm, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff810373a0)
Location: arch/x86/kernel/ldt.c:359
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
```
**Symbols:**

```
ffffffff810373a0-ffffffff8103748b: ldt_dup_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ldt_dup_context(struct mm_struct *old_mm, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81026d90)
Location: arch/x86/kernel/ldt.c:359
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
```
**Symbols:**

```
ffffffff81026d90-ffffffff81026e68: ldt_dup_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ldt_dup_context(struct mm_struct *old_mm, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81037200)
Location: arch/x86/kernel/ldt.c:359
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
```
**Symbols:**

```
ffffffff81037200-ffffffff810372eb: ldt_dup_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ldt_dup_context(struct mm_struct *old_mm, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81038200)
Location: arch/x86/kernel/ldt.c:359
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
```
**Symbols:**

```
ffffffff81038200-ffffffff810382eb: ldt_dup_context (STB_GLOBAL)
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
