# Function: <code>__execute_only_pkey</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int __execute_only_pkey(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pkeys.c (ffffffff810778c0)
Location: arch/x86/mm/pkeys.c:22
Inline: True
Direct callers:
  - arch/x86/mm/pkeys.c:__arch_override_mprotect_pkey
  - mm/mmap.c:do_mmap
```
**Symbols:**

```
ffffffff810778c0-ffffffff8107791a: __execute_only_pkey (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __execute_only_pkey(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pkeys.c (ffffffff8107b5d0)
Location: arch/x86/mm/pkeys.c:23
Inline: False
Direct callers:
  - arch/x86/mm/pkeys.c:__arch_override_mprotect_pkey
  - mm/mmap.c:do_mmap
```
**Symbols:**

```
ffffffff8107b5d0-ffffffff8107b6c3: __execute_only_pkey (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __execute_only_pkey(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pkeys.c (ffffffff81079d90)
Location: arch/x86/mm/pkeys.c:23
Inline: False
Direct callers:
  - arch/x86/mm/pkeys.c:__arch_override_mprotect_pkey
  - mm/mmap.c:do_mmap
```
**Symbols:**

```
ffffffff81079d90-ffffffff81079e85: __execute_only_pkey (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __execute_only_pkey(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pkeys.c (ffffffff81080000)
Location: arch/x86/mm/pkeys.c:22
Inline: False
Direct callers:
  - arch/x86/mm/pkeys.c:__arch_override_mprotect_pkey
  - mm/mmap.c:do_mmap
```
**Symbols:**

```
ffffffff81080000-ffffffff810800f5: __execute_only_pkey (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __execute_only_pkey(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pkeys.c (ffffffff81083110)
Location: arch/x86/mm/pkeys.c:22
Inline: False
Direct callers:
  - arch/x86/mm/pkeys.c:__arch_override_mprotect_pkey
  - mm/mmap.c:do_mmap
```
**Symbols:**

```
ffffffff81083110-ffffffff81083208: __execute_only_pkey (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __execute_only_pkey(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pkeys.c (ffffffff81089cc0)
Location: arch/x86/mm/pkeys.c:22
Inline: False
Direct callers:
  - arch/x86/mm/pkeys.c:__arch_override_mprotect_pkey
  - mm/mmap.c:do_mmap
```
**Symbols:**

```
ffffffff81089cc0-ffffffff81089db8: __execute_only_pkey (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __execute_only_pkey(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pkeys.c (ffffffff8108da40)
Location: arch/x86/mm/pkeys.c:15
Inline: False
Direct callers:
  - arch/x86/mm/pkeys.c:__arch_override_mprotect_pkey
  - mm/mmap.c:do_mmap
```
**Symbols:**

```
ffffffff8108da40-ffffffff8108db3b: __execute_only_pkey (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __execute_only_pkey(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pkeys.c (ffffffff8108e6a0)
Location: arch/x86/mm/pkeys.c:15
Inline: False
Direct callers:
  - arch/x86/mm/pkeys.c:__arch_override_mprotect_pkey
  - mm/mmap.c:do_mmap
```
**Symbols:**

```
ffffffff8108e6a0-ffffffff8108e79b: __execute_only_pkey (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __execute_only_pkey(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pkeys.c (ffffffff81094810)
Location: arch/x86/mm/pkeys.c:15
Inline: False
Direct callers:
  - arch/x86/mm/pkeys.c:__arch_override_mprotect_pkey
  - mm/mmap.c:do_mmap
```
**Symbols:**

```
ffffffff81094810-ffffffff8109490b: __execute_only_pkey (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __execute_only_pkey(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pkeys.c (ffffffff81093c00)
Location: arch/x86/mm/pkeys.c:15
Inline: False
Direct callers:
  - arch/x86/mm/pkeys.c:__arch_override_mprotect_pkey
  - mm/mmap.c:do_mmap
```
**Symbols:**

```
ffffffff81093c00-ffffffff81093cfb: __execute_only_pkey (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __execute_only_pkey(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pkeys.c (ffffffff810945c0)
Location: arch/x86/mm/pkeys.c:15
Inline: False
Direct callers:
  - arch/x86/mm/pkeys.c:__arch_override_mprotect_pkey
  - mm/mmap.c:do_mmap
```
**Symbols:**

```
ffffffff810945c0-ffffffff810946bc: __execute_only_pkey (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __execute_only_pkey(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pkeys.c (0)
Location: arch/x86/mm/pkeys.c:14
Inline: False
Direct callers:
  - arch/x86/mm/pkeys.c:__arch_override_mprotect_pkey
  - mm/mmap.c:do_mmap
```
**Symbols:**

```
ffffffff81ca226a-ffffffff81ca22db: __execute_only_pkey.cold (STB_LOCAL)
ffffffff810a4520-ffffffff810a4669: __execute_only_pkey (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __execute_only_pkey(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pkeys.c (0)
Location: arch/x86/mm/pkeys.c:14
Inline: False
Direct callers:
  - arch/x86/mm/pkeys.c:__arch_override_mprotect_pkey
  - mm/mmap.c:do_mmap
```
**Symbols:**

```
ffffffff81e5191c-ffffffff81e51976: __execute_only_pkey.cold (STB_LOCAL)
ffffffff810b8d60-ffffffff810b8ea8: __execute_only_pkey (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int __execute_only_pkey(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pkeys.c (0)
Location: arch/x86/mm/pkeys.c:14
Inline: False
Direct callers:
  - arch/x86/mm/pkeys.c:__arch_override_mprotect_pkey
  - mm/mmap.c:do_mmap
```
**Symbols:**

```
ffffffff820552fe-ffffffff8205538a: __execute_only_pkey.cold (STB_LOCAL)
ffffffff810d4640-ffffffff810d47b3: __execute_only_pkey (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int __execute_only_pkey(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pkeys.c (0)
Location: arch/x86/mm/pkeys.c:14
Inline: False
Direct callers:
  - arch/x86/mm/pkeys.c:__arch_override_mprotect_pkey
  - mm/mmap.c:do_mmap
```
**Symbols:**

```
ffffffff820d38cd-ffffffff820d3955: __execute_only_pkey.cold (STB_LOCAL)
ffffffff810d7b80-ffffffff810d7cc4: __execute_only_pkey (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int __execute_only_pkey(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pkeys.c (0)
Location: arch/x86/mm/pkeys.c:14
Inline: False
Direct callers:
  - arch/x86/mm/pkeys.c:__arch_override_mprotect_pkey
  - mm/mmap.c:do_mmap
```
**Symbols:**

```
ffffffff821ae73b-ffffffff821ae7c3: __execute_only_pkey.cold (STB_LOCAL)
ffffffff810e0400-ffffffff810e0544: __execute_only_pkey (STB_GLOBAL)
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
int __execute_only_pkey(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pkeys.c (ffffffff8108d660)
Location: arch/x86/mm/pkeys.c:15
Inline: False
Direct callers:
  - arch/x86/mm/pkeys.c:__arch_override_mprotect_pkey
  - mm/mmap.c:do_mmap
```
**Symbols:**

```
ffffffff8108d660-ffffffff8108d75b: __execute_only_pkey (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __execute_only_pkey(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pkeys.c (ffffffff8107c190)
Location: arch/x86/mm/pkeys.c:15
Inline: False
Direct callers:
  - arch/x86/mm/pkeys.c:__arch_override_mprotect_pkey
  - mm/mmap.c:do_mmap
```
**Symbols:**

```
ffffffff8107c190-ffffffff8107c28b: __execute_only_pkey (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __execute_only_pkey(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pkeys.c (ffffffff8108d610)
Location: arch/x86/mm/pkeys.c:15
Inline: False
Direct callers:
  - arch/x86/mm/pkeys.c:__arch_override_mprotect_pkey
  - mm/mmap.c:do_mmap
```
**Symbols:**

```
ffffffff8108d610-ffffffff8108d70b: __execute_only_pkey (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __execute_only_pkey(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pkeys.c (ffffffff8108f9d0)
Location: arch/x86/mm/pkeys.c:15
Inline: False
Direct callers:
  - arch/x86/mm/pkeys.c:__arch_override_mprotect_pkey
  - mm/mmap.c:do_mmap
```
**Symbols:**

```
ffffffff8108f9d0-ffffffff8108facb: __execute_only_pkey (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
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
