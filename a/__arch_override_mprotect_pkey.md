# Function: <code>__arch_override_mprotect_pkey</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __arch_override_mprotect_pkey(struct vm_area_struct *vma, int prot, int pkey);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pkeys.c (ffffffff81077920)
Location: arch/x86/mm/pkeys.c:67
Inline: False
Direct callers:
  - mm/mprotect.c:SyS_mprotect
```
**Symbols:**

```
ffffffff81077920-ffffffff81077992: __arch_override_mprotect_pkey (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __arch_override_mprotect_pkey(struct vm_area_struct *vma, int prot, int pkey);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pkeys.c (ffffffff8107b6d0)
Location: arch/x86/mm/pkeys.c:90
Inline: False
Direct callers:
  - mm/mprotect.c:do_mprotect_pkey
```
**Symbols:**

```
ffffffff8107b6d0-ffffffff8107b747: __arch_override_mprotect_pkey (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __arch_override_mprotect_pkey(struct vm_area_struct *vma, int prot, int pkey);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pkeys.c (ffffffff81079e90)
Location: arch/x86/mm/pkeys.c:90
Inline: False
Direct callers:
  - mm/mprotect.c:do_mprotect_pkey
```
**Symbols:**

```
ffffffff81079e90-ffffffff81079f05: __arch_override_mprotect_pkey (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __arch_override_mprotect_pkey(struct vm_area_struct *vma, int prot, int pkey);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pkeys.c (ffffffff81080100)
Location: arch/x86/mm/pkeys.c:89
Inline: False
Direct callers:
  - mm/mprotect.c:do_mprotect_pkey
```
**Symbols:**

```
ffffffff81080100-ffffffff81080175: __arch_override_mprotect_pkey (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __arch_override_mprotect_pkey(struct vm_area_struct *vma, int prot, int pkey);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pkeys.c (ffffffff81083210)
Location: arch/x86/mm/pkeys.c:89
Inline: False
Direct callers:
  - mm/mprotect.c:do_mprotect_pkey
```
**Symbols:**

```
ffffffff81083210-ffffffff8108327b: __arch_override_mprotect_pkey (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __arch_override_mprotect_pkey(struct vm_area_struct *vma, int prot, int pkey);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pkeys.c (ffffffff81089dc0)
Location: arch/x86/mm/pkeys.c:89
Inline: False
Direct callers:
  - mm/mprotect.c:do_mprotect_pkey
```
**Symbols:**

```
ffffffff81089dc0-ffffffff81089e2b: __arch_override_mprotect_pkey (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __arch_override_mprotect_pkey(struct vm_area_struct *vma, int prot, int pkey);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pkeys.c (ffffffff8108db40)
Location: arch/x86/mm/pkeys.c:77
Inline: False
Direct callers:
  - mm/mprotect.c:do_mprotect_pkey
```
**Symbols:**

```
ffffffff8108db40-ffffffff8108dbab: __arch_override_mprotect_pkey (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __arch_override_mprotect_pkey(struct vm_area_struct *vma, int prot, int pkey);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pkeys.c (ffffffff8108e7a0)
Location: arch/x86/mm/pkeys.c:77
Inline: False
Direct callers:
  - mm/mprotect.c:do_mprotect_pkey
```
**Symbols:**

```
ffffffff8108e7a0-ffffffff8108e80b: __arch_override_mprotect_pkey (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __arch_override_mprotect_pkey(struct vm_area_struct *vma, int prot, int pkey);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pkeys.c (ffffffff81094910)
Location: arch/x86/mm/pkeys.c:77
Inline: False
Direct callers:
  - mm/mprotect.c:do_mprotect_pkey
```
**Symbols:**

```
ffffffff81094910-ffffffff81094986: __arch_override_mprotect_pkey (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __arch_override_mprotect_pkey(struct vm_area_struct *vma, int prot, int pkey);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pkeys.c (ffffffff81093d00)
Location: arch/x86/mm/pkeys.c:77
Inline: False
Direct callers:
  - mm/mprotect.c:do_mprotect_pkey
```
**Symbols:**

```
ffffffff81093d00-ffffffff81093d76: __arch_override_mprotect_pkey (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __arch_override_mprotect_pkey(struct vm_area_struct *vma, int prot, int pkey);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pkeys.c (ffffffff810946c0)
Location: arch/x86/mm/pkeys.c:77
Inline: False
Direct callers:
  - mm/mprotect.c:do_mprotect_pkey
```
**Symbols:**

```
ffffffff810946c0-ffffffff81094736: __arch_override_mprotect_pkey (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __arch_override_mprotect_pkey(struct vm_area_struct *vma, int prot, int pkey);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pkeys.c (ffffffff810a4670)
Location: arch/x86/mm/pkeys.c:76
Inline: False
Direct callers:
  - mm/mprotect.c:do_mprotect_pkey
```
**Symbols:**

```
ffffffff810a4670-ffffffff810a46de: __arch_override_mprotect_pkey (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __arch_override_mprotect_pkey(struct vm_area_struct *vma, int prot, int pkey);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pkeys.c (ffffffff810b8eb0)
Location: arch/x86/mm/pkeys.c:76
Inline: False
Direct callers:
  - mm/mprotect.c:do_mprotect_pkey
```
**Symbols:**

```
ffffffff810b8eb0-ffffffff810b8f42: __arch_override_mprotect_pkey (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __arch_override_mprotect_pkey(struct vm_area_struct *vma, int prot, int pkey);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pkeys.c (ffffffff810d47d0)
Location: arch/x86/mm/pkeys.c:76
Inline: False
Direct callers:
  - mm/mprotect.c:do_mprotect_pkey
```
**Symbols:**

```
ffffffff810d47d0-ffffffff810d4862: __arch_override_mprotect_pkey (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __arch_override_mprotect_pkey(struct vm_area_struct *vma, int prot, int pkey);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pkeys.c (ffffffff810d7ce0)
Location: arch/x86/mm/pkeys.c:76
Inline: False
Direct callers:
  - mm/mprotect.c:do_mprotect_pkey
```
**Symbols:**

```
ffffffff810d7ce0-ffffffff810d7d72: __arch_override_mprotect_pkey (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __arch_override_mprotect_pkey(struct vm_area_struct *vma, int prot, int pkey);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pkeys.c (ffffffff810e0560)
Location: arch/x86/mm/pkeys.c:76
Inline: False
Direct callers:
  - mm/mprotect.c:do_mprotect_pkey
```
**Symbols:**

```
ffffffff810e0560-ffffffff810e05f2: __arch_override_mprotect_pkey (STB_GLOBAL)
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
int __arch_override_mprotect_pkey(struct vm_area_struct *vma, int prot, int pkey);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pkeys.c (ffffffff8108d760)
Location: arch/x86/mm/pkeys.c:77
Inline: False
Direct callers:
  - mm/mprotect.c:do_mprotect_pkey
```
**Symbols:**

```
ffffffff8108d760-ffffffff8108d7cb: __arch_override_mprotect_pkey (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __arch_override_mprotect_pkey(struct vm_area_struct *vma, int prot, int pkey);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pkeys.c (ffffffff8107c290)
Location: arch/x86/mm/pkeys.c:77
Inline: False
Direct callers:
  - mm/mprotect.c:do_mprotect_pkey
```
**Symbols:**

```
ffffffff8107c290-ffffffff8107c2fb: __arch_override_mprotect_pkey (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __arch_override_mprotect_pkey(struct vm_area_struct *vma, int prot, int pkey);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pkeys.c (ffffffff8108d710)
Location: arch/x86/mm/pkeys.c:77
Inline: False
Direct callers:
  - mm/mprotect.c:do_mprotect_pkey
```
**Symbols:**

```
ffffffff8108d710-ffffffff8108d77b: __arch_override_mprotect_pkey (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __arch_override_mprotect_pkey(struct vm_area_struct *vma, int prot, int pkey);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pkeys.c (ffffffff8108fad0)
Location: arch/x86/mm/pkeys.c:77
Inline: False
Direct callers:
  - mm/mprotect.c:do_mprotect_pkey
```
**Symbols:**

```
ffffffff8108fad0-ffffffff8108fb3b: __arch_override_mprotect_pkey (STB_GLOBAL)
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
