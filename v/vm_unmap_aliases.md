# Function: <code>vm_unmap_aliases</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void vm_unmap_aliases();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff811cd080)
Location: mm/vmalloc.c:1040
Inline: False
Direct callers:
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
  - security/apparmor/match.c:aa_dfa_unpack
```
**Symbols:**

```
ffffffff811cd080-ffffffff811cd1ba: vm_unmap_aliases (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void vm_unmap_aliases();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff811ea0d0)
Location: mm/vmalloc.c:1064
Inline: False
Direct callers:
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
  - security/apparmor/match.c:aa_dfa_unpack
```
**Symbols:**

```
ffffffff811ea0d0-ffffffff811ea207: vm_unmap_aliases (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void vm_unmap_aliases();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff811fb630)
Location: mm/vmalloc.c:1035
Inline: True
Direct callers:
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
  - security/apparmor/match.c:aa_dfa_unpack
```
**Symbols:**

```
ffffffff811fb630-ffffffff811fb775: vm_unmap_aliases (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void vm_unmap_aliases();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81206360)
Location: mm/vmalloc.c:1086
Inline: True
Direct callers:
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
  - security/apparmor/match.c:aa_dfa_unpack
```
**Symbols:**

```
ffffffff81206360-ffffffff812064a3: vm_unmap_aliases (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void vm_unmap_aliases();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8121f070)
Location: mm/vmalloc.c:1084
Inline: True
Direct callers:
  - arch/x86/mm/pageattr.c:__set_memory_enc_dec
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
  - security/apparmor/match.c:aa_dfa_unpack
```
**Symbols:**

```
ffffffff8121f070-ffffffff8121f19e: vm_unmap_aliases (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void vm_unmap_aliases();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81241940)
Location: mm/vmalloc.c:1071
Inline: True
Direct callers:
  - arch/x86/mm/pageattr.c:__set_memory_enc_dec
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
  - security/apparmor/match.c:aa_dfa_unpack
```
**Symbols:**

```
ffffffff81241940-ffffffff81241a68: vm_unmap_aliases (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void vm_unmap_aliases();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81256040)
Location: mm/vmalloc.c:1071
Inline: True
Direct callers:
  - arch/x86/mm/pageattr.c:__set_memory_enc_dec
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
  - security/apparmor/match.c:aa_dfa_unpack
```
**Symbols:**

```
ffffffff81256040-ffffffff81256168: vm_unmap_aliases (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void vm_unmap_aliases();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81269718)
Location: mm/vmalloc.c:1714
Inline: True
Inline callers:
  - mm/vmalloc.c:__vunmap
Direct callers:
  - arch/x86/mm/pageattr.c:__set_memory_enc_dec
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
  - security/apparmor/match.c:aa_dfa_unpack
```
**Symbols:**

```
ffffffff81269510-ffffffff8126952b: vm_unmap_aliases (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void vm_unmap_aliases();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8127863b)
Location: mm/vmalloc.c:1722
Inline: True
Inline callers:
  - mm/vmalloc.c:__vunmap
Direct callers:
  - arch/x86/mm/pageattr.c:__set_memory_enc_dec
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
  - security/apparmor/match.c:aa_dfa_unpack
```
**Symbols:**

```
ffffffff81278450-ffffffff8127846b: vm_unmap_aliases (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void vm_unmap_aliases();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812abf84)
Location: mm/vmalloc.c:1821
Inline: True
Inline callers:
  - mm/vmalloc.c:__vunmap
Direct callers:
  - arch/x86/mm/pat/set_memory.c:__set_memory_enc_dec
  - security/apparmor/match.c:unpack_table
```
**Symbols:**

```
ffffffff812a90d0-ffffffff812a90fa: vm_unmap_aliases (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void vm_unmap_aliases();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812b74a4)
Location: mm/vmalloc.c:1803
Inline: True
Inline callers:
  - mm/vmalloc.c:__vunmap
Direct callers:
  - arch/x86/mm/pat/set_memory.c:__set_memory_enc_dec
  - security/apparmor/match.c:unpack_table
```
**Symbols:**

```
ffffffff812b4530-ffffffff812b455a: vm_unmap_aliases (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void vm_unmap_aliases();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812bcd74)
Location: mm/vmalloc.c:2073
Inline: True
Inline callers:
  - mm/vmalloc.c:__vunmap
Direct callers:
  - arch/x86/mm/pat/set_memory.c:__set_memory_enc_dec
  - security/apparmor/match.c:aa_dfa_unpack
```
**Symbols:**

```
ffffffff812b9c10-ffffffff812b9c3a: vm_unmap_aliases (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void vm_unmap_aliases();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812ff4ee)
Location: mm/vmalloc.c:2125
Inline: True
Inline callers:
  - mm/vmalloc.c:__vunmap
Direct callers:
  - arch/x86/mm/pat/set_memory.c:__set_memory_enc_dec
  - security/apparmor/match.c:aa_dfa_unpack
```
**Symbols:**

```
ffffffff812fc220-ffffffff812fc23b: vm_unmap_aliases (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void vm_unmap_aliases();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81366603)
Location: mm/vmalloc.c:2143
Inline: True
Inline callers:
  - mm/vmalloc.c:__vunmap
Direct callers:
  - arch/x86/mm/pat/set_memory.c:__set_memory_enc_pgtable
  - security/apparmor/match.c:unpack_table
```
**Symbols:**

```
ffffffff813633e0-ffffffff81363405: vm_unmap_aliases (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void vm_unmap_aliases();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff813e2213)
Location: mm/vmalloc.c:2205
Inline: True
Inline callers:
  - mm/vmalloc.c:__vunmap
Direct callers:
  - arch/x86/mm/pat/set_memory.c:__set_memory_enc_pgtable
  - security/apparmor/match.c:unpack_table
```
**Symbols:**

```
ffffffff813dee90-ffffffff813deeb5: vm_unmap_aliases (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void vm_unmap_aliases();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81413cc0)
Location: mm/vmalloc.c:2324
Inline: False
Direct callers:
  - arch/x86/mm/pat/set_memory.c:__set_memory_enc_pgtable
  - security/apparmor/match.c:aa_dfa_unpack
```
**Symbols:**

```
ffffffff81413cc0-ffffffff81413ce5: vm_unmap_aliases (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void vm_unmap_aliases();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81440730)
Location: mm/vmalloc.c:2324
Inline: False
Direct callers:
  - arch/x86/mm/pat/set_memory.c:__set_memory_enc_pgtable
  - security/apparmor/match.c:aa_dfa_unpack
```
**Symbols:**

```
ffffffff81440730-ffffffff81440755: vm_unmap_aliases (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void vm_unmap_aliases();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffff80001030ef3c)
Location: mm/vmalloc.c:1722
Inline: True
Inline callers:
  - mm/vmalloc.c:__vunmap
Direct callers:
  - arch/arm64/mm/pageattr.c:change_memory_common
  - security/apparmor/match.c:aa_dfa_unpack
```
**Symbols:**

```
ffff80001030ece8-ffff80001030ed10: vm_unmap_aliases (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void vm_unmap_aliases();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (c052a7a4)
Location: mm/vmalloc.c:1722
Inline: True
Inline callers:
  - mm/vmalloc.c:__vunmap
Direct callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
**Symbols:**

```
c052a594-c052a5bc: vm_unmap_aliases (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void vm_unmap_aliases();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (c0000000003dfef0)
Location: mm/vmalloc.c:1722
Inline: True
Inline callers:
  - mm/vmalloc.c:__vunmap
Direct callers:
  - arch/powerpc/mm/mem.c:arch_remove_memory
  - security/apparmor/match.c:aa_dfa_unpack
```
**Symbols:**

```
c0000000003dfd10-c0000000003dfd30: vm_unmap_aliases (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void vm_unmap_aliases();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffe00021774a)
Location: mm/vmalloc.c:1722
Inline: True
Inline callers:
  - mm/vmalloc.c:__vunmap
Direct callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
**Symbols:**

```
ffffffe0002175f0-ffffffe000217614: vm_unmap_aliases (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void vm_unmap_aliases();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81270c8b)
Location: mm/vmalloc.c:1722
Inline: True
Inline callers:
  - mm/vmalloc.c:__vunmap
Direct callers:
  - arch/x86/mm/pageattr.c:__set_memory_enc_dec
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
  - security/apparmor/match.c:aa_dfa_unpack
```
**Symbols:**

```
ffffffff81270aa0-ffffffff81270abb: vm_unmap_aliases (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void vm_unmap_aliases();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81262bfb)
Location: mm/vmalloc.c:1722
Inline: True
Inline callers:
  - mm/vmalloc.c:__vunmap
Direct callers:
  - arch/x86/mm/pageattr.c:__set_memory_enc_dec
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
  - security/apparmor/match.c:aa_dfa_unpack
```
**Symbols:**

```
ffffffff81262a10-ffffffff81262a2b: vm_unmap_aliases (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void vm_unmap_aliases();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8126ea2b)
Location: mm/vmalloc.c:1722
Inline: True
Inline callers:
  - mm/vmalloc.c:__vunmap
Direct callers:
  - arch/x86/mm/pageattr.c:__set_memory_enc_dec
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
  - security/apparmor/match.c:aa_dfa_unpack
```
**Symbols:**

```
ffffffff8126e840-ffffffff8126e85b: vm_unmap_aliases (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void vm_unmap_aliases();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8127e3e8)
Location: mm/vmalloc.c:1722
Inline: True
Inline callers:
  - mm/vmalloc.c:__vunmap
Direct callers:
  - arch/x86/mm/pageattr.c:__set_memory_enc_dec
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
  - security/apparmor/match.c:aa_dfa_unpack
```
**Symbols:**

```
ffffffff8127e210-ffffffff8127e235: vm_unmap_aliases (STB_GLOBAL)
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
