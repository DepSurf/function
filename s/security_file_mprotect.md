# Function: <code>security_file_mprotect</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int security_file_mprotect(struct vm_area_struct *vma, long unsigned int reqprot, long unsigned int prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8133dec0)
Location: security/security.c:814
Inline: False
Direct callers:
  - mm/mprotect.c:SyS_mprotect
```
**Symbols:**

```
ffffffff8133dec0-ffffffff8133df1b: security_file_mprotect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int security_file_mprotect(struct vm_area_struct *vma, long unsigned int reqprot, long unsigned int prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81373520)
Location: security/security.c:836
Inline: False
Direct callers:
  - mm/mprotect.c:SyS_mprotect
```
**Symbols:**

```
ffffffff81373520-ffffffff8137357b: security_file_mprotect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int security_file_mprotect(struct vm_area_struct *vma, long unsigned int reqprot, long unsigned int prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81389e50)
Location: security/security.c:857
Inline: False
Direct callers:
  - mm/mprotect.c:do_mprotect_pkey
```
**Symbols:**

```
ffffffff81389e50-ffffffff81389eab: security_file_mprotect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int security_file_mprotect(struct vm_area_struct *vma, long unsigned int reqprot, long unsigned int prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8139f250)
Location: security/security.c:1469
Inline: False
Direct callers:
  - mm/mprotect.c:do_mprotect_pkey
```
**Symbols:**

```
ffffffff8139f250-ffffffff8139f2ab: security_file_mprotect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int security_file_mprotect(struct vm_area_struct *vma, long unsigned int reqprot, long unsigned int prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813c4d80)
Location: security/security.c:1427
Inline: False
Direct callers:
  - mm/mprotect.c:do_mprotect_pkey
```
**Symbols:**

```
ffffffff813c4d80-ffffffff813c4de1: security_file_mprotect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int security_file_mprotect(struct vm_area_struct *vma, long unsigned int reqprot, long unsigned int prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813f5050)
Location: security/security.c:953
Inline: False
Direct callers:
  - mm/mprotect.c:do_mprotect_pkey
```
**Symbols:**

```
ffffffff813f5050-ffffffff813f509e: security_file_mprotect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int security_file_mprotect(struct vm_area_struct *vma, long unsigned int reqprot, long unsigned int prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81410490)
Location: security/security.c:1489
Inline: False
Direct callers:
  - mm/mprotect.c:do_mprotect_pkey
```
**Symbols:**

```
ffffffff81410490-ffffffff814104de: security_file_mprotect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int security_file_mprotect(struct vm_area_struct *vma, long unsigned int reqprot, long unsigned int prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143dbe0)
Location: security/security.c:1508
Inline: False
Direct callers:
  - mm/mprotect.c:do_mprotect_pkey
```
**Symbols:**

```
ffffffff8143dbe0-ffffffff8143dc39: security_file_mprotect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int security_file_mprotect(struct vm_area_struct *vma, long unsigned int reqprot, long unsigned int prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814576d0)
Location: security/security.c:1547
Inline: False
Direct callers:
  - mm/mprotect.c:do_mprotect_pkey
```
**Symbols:**

```
ffffffff814576d0-ffffffff8145771e: security_file_mprotect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int security_file_mprotect(struct vm_area_struct *vma, long unsigned int reqprot, long unsigned int prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814aa4c0)
Location: security/security.c:1718
Inline: False
Direct callers:
  - mm/mprotect.c:do_mprotect_pkey
```
**Symbols:**

```
ffffffff814aa4c0-ffffffff814aa517: security_file_mprotect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_file_mprotect(struct vm_area_struct *vma, long unsigned int reqprot, long unsigned int prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814c7ad0)
Location: security/security.c:1720
Inline: False
Direct callers:
  - mm/mprotect.c:do_mprotect_pkey
```
**Symbols:**

```
ffffffff814c7ad0-ffffffff814c7b27: security_file_mprotect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_file_mprotect(struct vm_area_struct *vma, long unsigned int reqprot, long unsigned int prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814ce100)
Location: security/security.c:1770
Inline: False
Direct callers:
  - mm/mprotect.c:do_mprotect_pkey
```
**Symbols:**

```
ffffffff814ce100-ffffffff814ce157: security_file_mprotect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int security_file_mprotect(struct vm_area_struct *vma, long unsigned int reqprot, long unsigned int prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81526eb0)
Location: security/security.c:1778
Inline: False
Direct callers:
  - mm/mprotect.c:do_mprotect_pkey
```
**Symbols:**

```
ffffffff81526eb0-ffffffff81526f07: security_file_mprotect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int security_file_mprotect(struct vm_area_struct *vma, long unsigned int reqprot, long unsigned int prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815bbab0)
Location: security/security.c:1783
Inline: False
Direct callers:
  - mm/mprotect.c:do_mprotect_pkey
```
**Symbols:**

```
ffffffff815bbab0-ffffffff815bbb26: security_file_mprotect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int security_file_mprotect(struct vm_area_struct *vma, long unsigned int reqprot, long unsigned int prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816678a0)
Location: security/security.c:1825
Inline: False
Direct callers:
  - mm/mprotect.c:do_mprotect_pkey
```
**Symbols:**

```
ffffffff816678a0-ffffffff81667916: security_file_mprotect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int security_file_mprotect(struct vm_area_struct *vma, long unsigned int reqprot, long unsigned int prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8169fec0)
Location: security/security.c:2851
Inline: False
Direct callers:
  - mm/mprotect.c:do_mprotect_pkey
```
**Symbols:**

```
ffffffff8169fec0-ffffffff8169ff36: security_file_mprotect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int security_file_mprotect(struct vm_area_struct *vma, long unsigned int reqprot, long unsigned int prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816dc7b0)
Location: security/security.c:2929
Inline: False
Direct callers:
  - mm/mprotect.c:do_mprotect_pkey
```
**Symbols:**

```
ffffffff816dc7b0-ffffffff816dc826: security_file_mprotect (STB_GLOBAL)
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
int security_file_mprotect(struct vm_area_struct *vma, long unsigned int reqprot, long unsigned int prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffff8000105432e8)
Location: security/security.c:1547
Inline: False
Direct callers:
  - mm/mprotect.c:__arm64_sys_mprotect
```
**Symbols:**

```
ffff8000105432e8-ffff80001054334c: security_file_mprotect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int security_file_mprotect(struct vm_area_struct *vma, long unsigned int reqprot, long unsigned int prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c06f9250)
Location: security/security.c:1547
Inline: False
Direct callers:
  - mm/mprotect.c:__se_sys_mprotect
```
**Symbols:**

```
c06f9250-c06f92b4: security_file_mprotect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int security_file_mprotect(struct vm_area_struct *vma, long unsigned int reqprot, long unsigned int prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c000000000697130)
Location: security/security.c:1547
Inline: False
Direct callers:
  - mm/mprotect.c:__se_sys_mprotect
```
**Symbols:**

```
c000000000697130-c000000000697200: security_file_mprotect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int security_file_mprotect(struct vm_area_struct *vma, long unsigned int reqprot, long unsigned int prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffe00039f8a8)
Location: security/security.c:1547
Inline: False
Direct callers:
  - mm/mprotect.c:__se_sys_mprotect
```
**Symbols:**

```
ffffffe00039f8a8-ffffffe00039f8f4: security_file_mprotect (STB_GLOBAL)
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
int security_file_mprotect(struct vm_area_struct *vma, long unsigned int reqprot, long unsigned int prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144fcb0)
Location: security/security.c:1547
Inline: False
Direct callers:
  - mm/mprotect.c:do_mprotect_pkey
```
**Symbols:**

```
ffffffff8144fcb0-ffffffff8144fcfe: security_file_mprotect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int security_file_mprotect(struct vm_area_struct *vma, long unsigned int reqprot, long unsigned int prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81440700)
Location: security/security.c:1547
Inline: False
Direct callers:
  - mm/mprotect.c:do_mprotect_pkey
```
**Symbols:**

```
ffffffff81440700-ffffffff8144074e: security_file_mprotect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int security_file_mprotect(struct vm_area_struct *vma, long unsigned int reqprot, long unsigned int prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144bd50)
Location: security/security.c:1547
Inline: False
Direct callers:
  - mm/mprotect.c:do_mprotect_pkey
```
**Symbols:**

```
ffffffff8144bd50-ffffffff8144bd9e: security_file_mprotect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int security_file_mprotect(struct vm_area_struct *vma, long unsigned int reqprot, long unsigned int prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81463120)
Location: security/security.c:1547
Inline: False
Direct callers:
  - mm/mprotect.c:do_mprotect_pkey
```
**Symbols:**

```
ffffffff81463120-ffffffff8146316e: security_file_mprotect (STB_GLOBAL)
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
