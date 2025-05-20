# Function: <code>phys_mem_access_prot_allowed</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int phys_mem_access_prot_allowed(struct file *file, long unsigned int pfn, long unsigned int size, pgprot_t *vma_prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff810703f0)
Location: arch/x86/mm/pat.c:725
Inline: False
Direct callers:
  - drivers/char/mem.c:mmap_mem
```
**Symbols:**

```
ffffffff810703f0-ffffffff81070429: phys_mem_access_prot_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int phys_mem_access_prot_allowed(struct file *file, long unsigned int pfn, long unsigned int size, pgprot_t *vma_prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff81070140)
Location: arch/x86/mm/pat.c:766
Inline: False
Direct callers:
  - drivers/char/mem.c:mmap_mem
```
**Symbols:**

```
ffffffff81070140-ffffffff8107017b: phys_mem_access_prot_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int phys_mem_access_prot_allowed(struct file *file, long unsigned int pfn, long unsigned int size, pgprot_t *vma_prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff81073d80)
Location: arch/x86/mm/pat.c:780
Inline: False
Direct callers:
  - drivers/char/mem.c:mmap_mem
```
**Symbols:**

```
ffffffff81073d80-ffffffff81073dbb: phys_mem_access_prot_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int phys_mem_access_prot_allowed(struct file *file, long unsigned int pfn, long unsigned int size, pgprot_t *vma_prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff81073330)
Location: arch/x86/mm/pat.c:777
Inline: False
Direct callers:
  - drivers/char/mem.c:mmap_mem
```
**Symbols:**

```
ffffffff81073330-ffffffff81073358: phys_mem_access_prot_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int phys_mem_access_prot_allowed(struct file *file, long unsigned int pfn, long unsigned int size, pgprot_t *vma_prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff81078cf0)
Location: arch/x86/mm/pat.c:799
Inline: False
Direct callers:
  - drivers/char/mem.c:mmap_mem
```
**Symbols:**

```
ffffffff81078cf0-ffffffff81078d18: phys_mem_access_prot_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int phys_mem_access_prot_allowed(struct file *file, long unsigned int pfn, long unsigned int size, pgprot_t *vma_prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff8107b710)
Location: arch/x86/mm/pat.c:815
Inline: False
Direct callers:
  - drivers/char/mem.c:mmap_mem
```
**Symbols:**

```
ffffffff8107b710-ffffffff8107b738: phys_mem_access_prot_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int phys_mem_access_prot_allowed(struct file *file, long unsigned int pfn, long unsigned int size, pgprot_t *vma_prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff81082080)
Location: arch/x86/mm/pat.c:824
Inline: False
Direct callers:
  - drivers/char/mem.c:mmap_mem
```
**Symbols:**

```
ffffffff81082080-ffffffff810820a8: phys_mem_access_prot_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int phys_mem_access_prot_allowed(struct file *file, long unsigned int pfn, long unsigned int size, pgprot_t *vma_prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff81085d00)
Location: arch/x86/mm/pat.c:825
Inline: False
Direct callers:
  - drivers/char/mem.c:mmap_mem
```
**Symbols:**

```
ffffffff81085d00-ffffffff81085d28: phys_mem_access_prot_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int phys_mem_access_prot_allowed(struct file *file, long unsigned int pfn, long unsigned int size, pgprot_t *vma_prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff810869f0)
Location: arch/x86/mm/pat.c:825
Inline: False
Direct callers:
  - drivers/char/mem.c:mmap_mem
```
**Symbols:**

```
ffffffff810869f0-ffffffff81086a18: phys_mem_access_prot_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int phys_mem_access_prot_allowed(struct file *file, long unsigned int pfn, long unsigned int size, pgprot_t *vma_prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/memtype.c (ffffffff81090170)
Location: arch/x86/mm/pat/memtype.c:853
Inline: False
Direct callers:
  - drivers/char/mem.c:mmap_mem
```
**Symbols:**

```
ffffffff81090170-ffffffff810901ac: phys_mem_access_prot_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int phys_mem_access_prot_allowed(struct file *file, long unsigned int pfn, long unsigned int size, pgprot_t *vma_prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/memtype.c (ffffffff8108fe70)
Location: arch/x86/mm/pat/memtype.c:853
Inline: False
Direct callers:
  - drivers/char/mem.c:mmap_mem
```
**Symbols:**

```
ffffffff8108fe70-ffffffff8108feac: phys_mem_access_prot_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int phys_mem_access_prot_allowed(struct file *file, long unsigned int pfn, long unsigned int size, pgprot_t *vma_prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/memtype.c (ffffffff81090970)
Location: arch/x86/mm/pat/memtype.c:855
Inline: False
Direct callers:
  - drivers/char/mem.c:mmap_mem
```
**Symbols:**

```
ffffffff81090970-ffffffff810909a4: phys_mem_access_prot_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int phys_mem_access_prot_allowed(struct file *file, long unsigned int pfn, long unsigned int size, pgprot_t *vma_prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/memtype.c (ffffffff810a04c0)
Location: arch/x86/mm/pat/memtype.c:860
Inline: False
Direct callers:
  - drivers/char/mem.c:mmap_mem
```
**Symbols:**

```
ffffffff810a04c0-ffffffff810a04f4: phys_mem_access_prot_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int phys_mem_access_prot_allowed(struct file *file, long unsigned int pfn, long unsigned int size, pgprot_t *vma_prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/memtype.c (ffffffff810b4430)
Location: arch/x86/mm/pat/memtype.c:868
Inline: False
Direct callers:
  - drivers/char/mem.c:mmap_mem
```
**Symbols:**

```
ffffffff810b4430-ffffffff810b446c: phys_mem_access_prot_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int phys_mem_access_prot_allowed(struct file *file, long unsigned int pfn, long unsigned int size, pgprot_t *vma_prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/memtype.c (ffffffff810cf080)
Location: arch/x86/mm/pat/memtype.c:821
Inline: False
Direct callers:
  - drivers/char/mem.c:mmap_mem
```
**Symbols:**

```
ffffffff810cf080-ffffffff810cf0bc: phys_mem_access_prot_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int phys_mem_access_prot_allowed(struct file *file, long unsigned int pfn, long unsigned int size, pgprot_t *vma_prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/memtype.c (ffffffff810d2630)
Location: arch/x86/mm/pat/memtype.c:821
Inline: False
Direct callers:
  - drivers/char/mem.c:mmap_mem
```
**Symbols:**

```
ffffffff810d2630-ffffffff810d266c: phys_mem_access_prot_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int phys_mem_access_prot_allowed(struct file *file, long unsigned int pfn, long unsigned int size, pgprot_t *vma_prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/memtype.c (ffffffff810dadc0)
Location: arch/x86/mm/pat/memtype.c:821
Inline: False
Direct callers:
  - drivers/char/mem.c:mmap_mem
```
**Symbols:**

```
ffffffff810dadc0-ffffffff810dadfc: phys_mem_access_prot_allowed (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int phys_mem_access_prot_allowed(struct file *file, long unsigned int pfn, long unsigned int size, pgprot_t *vma_prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/mem.c (ffff8000108aba20)
Location: drivers/char/mem.c:271
Inline: False
Direct callers:
  - drivers/char/mem.c:mmap_mem
```
**Symbols:**

```
ffff8000108aba20-ffff8000108aba3c: phys_mem_access_prot_allowed (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int phys_mem_access_prot_allowed(struct file *file, long unsigned int pfn, long unsigned int size, pgprot_t *vma_prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/mem.c (c09a7808)
Location: drivers/char/mem.c:271
Inline: False
Direct callers:
  - drivers/char/mem.c:mmap_mem
```
**Symbols:**

```
c09a7808-c09a7824: phys_mem_access_prot_allowed (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int phys_mem_access_prot_allowed(struct file *file, long unsigned int pfn, long unsigned int size, pgprot_t *vma_prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/mem.c (c000000000943140)
Location: drivers/char/mem.c:271
Inline: False
Direct callers:
  - drivers/char/mem.c:mmap_mem
```
**Symbols:**

```
c000000000943140-c000000000943150: phys_mem_access_prot_allowed (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int phys_mem_access_prot_allowed(struct file *file, long unsigned int pfn, long unsigned int size, pgprot_t *vma_prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/mem.c (ffffffe00056023a)
Location: drivers/char/mem.c:271
Inline: False
Direct callers:
  - drivers/char/mem.c:mmap_mem
```
**Symbols:**

```
ffffffe00056023a-ffffffe000560256: phys_mem_access_prot_allowed (STB_WEAK)
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
int phys_mem_access_prot_allowed(struct file *file, long unsigned int pfn, long unsigned int size, pgprot_t *vma_prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff810859f0)
Location: arch/x86/mm/pat.c:825
Inline: False
Direct callers:
  - drivers/char/mem.c:mmap_mem
```
**Symbols:**

```
ffffffff810859f0-ffffffff81085a18: phys_mem_access_prot_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int phys_mem_access_prot_allowed(struct file *file, long unsigned int pfn, long unsigned int size, pgprot_t *vma_prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff81074770)
Location: arch/x86/mm/pat.c:825
Inline: False
Direct callers:
  - drivers/char/mem.c:mmap_mem
```
**Symbols:**

```
ffffffff81074770-ffffffff81074798: phys_mem_access_prot_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int phys_mem_access_prot_allowed(struct file *file, long unsigned int pfn, long unsigned int size, pgprot_t *vma_prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff810859a0)
Location: arch/x86/mm/pat.c:825
Inline: False
Direct callers:
  - drivers/char/mem.c:mmap_mem
```
**Symbols:**

```
ffffffff810859a0-ffffffff810859c8: phys_mem_access_prot_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int phys_mem_access_prot_allowed(struct file *file, long unsigned int pfn, long unsigned int size, pgprot_t *vma_prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff81087af0)
Location: arch/x86/mm/pat.c:825
Inline: False
Direct callers:
  - drivers/char/mem.c:mmap_mem
```
**Symbols:**

```
ffffffff81087af0-ffffffff81087b18: phys_mem_access_prot_allowed (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
