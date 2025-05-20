# Function: <code>__early_set_fixmap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __early_set_fixmap(enum fixed_addresses idx, phys_addr_t phys, pgprot_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff81f77f7e)
Location: arch/x86/mm/ioremap.c:484
Inline: False
Direct callers:
  - mm/early_ioremap.c:__early_ioremap
  - mm/early_ioremap.c:early_iounmap
```
**Symbols:**

```
ffffffff81f77f7e-ffffffff81f78019: __early_set_fixmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __early_set_fixmap(enum fixed_addresses idx, phys_addr_t phys, pgprot_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff81fa06d9)
Location: arch/x86/mm/ioremap.c:483
Inline: False
Direct callers:
  - mm/early_ioremap.c:early_iounmap
  - mm/early_ioremap.c:__early_ioremap
```
**Symbols:**

```
ffffffff81fa06d9-ffffffff81fa0771: __early_set_fixmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __early_set_fixmap(enum fixed_addresses idx, phys_addr_t phys, pgprot_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff81fdbc4a)
Location: arch/x86/mm/ioremap.c:483
Inline: False
Direct callers:
  - mm/early_ioremap.c:early_iounmap
  - mm/early_ioremap.c:__early_ioremap
```
**Symbols:**

```
ffffffff81fdbc4a-ffffffff81fdbce2: __early_set_fixmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __early_set_fixmap(enum fixed_addresses idx, phys_addr_t phys, pgprot_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff820bcc15)
Location: arch/x86/mm/ioremap.c:485
Inline: False
Direct callers:
  - mm/early_ioremap.c:early_iounmap
  - mm/early_ioremap.c:__early_ioremap
```
**Symbols:**

```
ffffffff820bcc15-ffffffff820bccaf: __early_set_fixmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __early_set_fixmap(enum fixed_addresses idx, phys_addr_t phys, pgprot_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff826c37f1)
Location: arch/x86/mm/ioremap.c:807
Inline: False
Direct callers:
  - mm/early_ioremap.c:early_iounmap
  - mm/early_ioremap.c:__early_ioremap
```
**Symbols:**

```
ffffffff826c37f1-ffffffff826c3898: __early_set_fixmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __early_set_fixmap(enum fixed_addresses idx, phys_addr_t phys, pgprot_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff826eda50)
Location: arch/x86/mm/ioremap.c:807
Inline: False
Direct callers:
  - mm/early_ioremap.c:early_iounmap
  - mm/early_ioremap.c:__early_ioremap
```
**Symbols:**

```
ffffffff826eda50-ffffffff826edb1d: __early_set_fixmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __early_set_fixmap(enum fixed_addresses idx, phys_addr_t phys, pgprot_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff828a45e2)
Location: arch/x86/mm/ioremap.c:815
Inline: False
Direct callers:
  - mm/early_ioremap.c:early_iounmap
  - mm/early_ioremap.c:__early_ioremap
```
**Symbols:**

```
ffffffff828a45e2-ffffffff828a46af: __early_set_fixmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __early_set_fixmap(enum fixed_addresses idx, phys_addr_t phys, pgprot_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff828bcac0)
Location: arch/x86/mm/ioremap.c:840
Inline: False
Direct callers:
  - mm/early_ioremap.c:early_iounmap
  - mm/early_ioremap.c:__early_ioremap
```
**Symbols:**

```
ffffffff828bcac0-ffffffff828bcb7a: __early_set_fixmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __early_set_fixmap(enum fixed_addresses idx, phys_addr_t phys, pgprot_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff828c2f5b)
Location: arch/x86/mm/ioremap.c:862
Inline: False
Direct callers:
  - mm/early_ioremap.c:early_iounmap
  - mm/early_ioremap.c:__early_ioremap
```
**Symbols:**

```
ffffffff828c2f5b-ffffffff828c3015: __early_set_fixmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __early_set_fixmap(enum fixed_addresses idx, phys_addr_t phys, pgprot_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff82ce6353)
Location: arch/x86/mm/ioremap.c:869
Inline: False
Direct callers:
  - mm/early_ioremap.c:early_iounmap
  - mm/early_ioremap.c:__early_ioremap
```
**Symbols:**

```
ffffffff82ce6353-ffffffff82ce63fb: __early_set_fixmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __early_set_fixmap(enum fixed_addresses idx, phys_addr_t phys, pgprot_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff82fd3cd9)
Location: arch/x86/mm/ioremap.c:869
Inline: False
Direct callers:
  - mm/early_ioremap.c:early_iounmap
  - mm/early_ioremap.c:__early_ioremap
```
**Symbols:**

```
ffffffff82fd3cd9-ffffffff82fd3d6c: __early_set_fixmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __early_set_fixmap(enum fixed_addresses idx, phys_addr_t phys, pgprot_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff831de81a)
Location: arch/x86/mm/ioremap.c:852
Inline: False
Direct callers:
  - mm/early_ioremap.c:early_iounmap
  - mm/early_ioremap.c:__early_ioremap
```
**Symbols:**

```
ffffffff831de81a-ffffffff831de8ad: __early_set_fixmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __early_set_fixmap(enum fixed_addresses idx, phys_addr_t phys, pgprot_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff832c1b90)
Location: arch/x86/mm/ioremap.c:897
Inline: False
Direct callers:
  - mm/early_ioremap.c:early_iounmap
  - mm/early_ioremap.c:__early_ioremap
```
**Symbols:**

```
ffffffff832c1b90-ffffffff832c1c23: __early_set_fixmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __early_set_fixmap(enum fixed_addresses idx, phys_addr_t phys, pgprot_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff834742a3)
Location: arch/x86/mm/ioremap.c:902
Inline: False
Direct callers:
  - mm/early_ioremap.c:early_iounmap
  - mm/early_ioremap.c:__early_ioremap
```
**Symbols:**

```
ffffffff834742a3-ffffffff8347433d: __early_set_fixmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __early_set_fixmap(enum fixed_addresses idx, phys_addr_t phys, pgprot_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff83e9c010)
Location: arch/x86/mm/ioremap.c:911
Inline: False
Direct callers:
  - mm/early_ioremap.c:early_iounmap
  - mm/early_ioremap.c:__early_ioremap
```
**Symbols:**

```
ffffffff83e9c010-ffffffff83e9c0ef: __early_set_fixmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __early_set_fixmap(enum fixed_addresses idx, phys_addr_t phys, pgprot_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff836bfab0)
Location: arch/x86/mm/ioremap.c:916
Inline: False
Direct callers:
  - mm/early_ioremap.c:early_iounmap
  - mm/early_ioremap.c:__early_ioremap
```
**Symbols:**

```
ffffffff836bfab0-ffffffff836bfb8f: __early_set_fixmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __early_set_fixmap(enum fixed_addresses idx, phys_addr_t phys, pgprot_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff838f05d0)
Location: arch/x86/mm/ioremap.c:916
Inline: False
Direct callers:
  - mm/early_ioremap.c:early_iounmap
  - mm/early_ioremap.c:__early_ioremap
```
**Symbols:**

```
ffffffff838f05d0-ffffffff838f06af: __early_set_fixmap (STB_GLOBAL)
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
void __early_set_fixmap(enum fixed_addresses idx, phys_addr_t phys, pgprot_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff828adf31)
Location: arch/x86/mm/ioremap.c:862
Inline: False
Direct callers:
  - mm/early_ioremap.c:early_iounmap
  - mm/early_ioremap.c:__early_ioremap
```
**Symbols:**

```
ffffffff828adf31-ffffffff828adfeb: __early_set_fixmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __early_set_fixmap(enum fixed_addresses idx, phys_addr_t phys, pgprot_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff828a6158)
Location: arch/x86/mm/ioremap.c:862
Inline: False
Direct callers:
  - mm/early_ioremap.c:early_iounmap
  - mm/early_ioremap.c:__early_ioremap
```
**Symbols:**

```
ffffffff828a6158-ffffffff828a61ed: __early_set_fixmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __early_set_fixmap(enum fixed_addresses idx, phys_addr_t phys, pgprot_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff828c0e30)
Location: arch/x86/mm/ioremap.c:862
Inline: False
Direct callers:
  - mm/early_ioremap.c:early_iounmap
  - mm/early_ioremap.c:__early_ioremap
```
**Symbols:**

```
ffffffff828c0e30-ffffffff828c0eea: __early_set_fixmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __early_set_fixmap(enum fixed_addresses idx, phys_addr_t phys, pgprot_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff828c3f7b)
Location: arch/x86/mm/ioremap.c:862
Inline: False
Direct callers:
  - mm/early_ioremap.c:early_iounmap
  - mm/early_ioremap.c:__early_ioremap
```
**Symbols:**

```
ffffffff828c3f7b-ffffffff828c4035: __early_set_fixmap (STB_GLOBAL)
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
