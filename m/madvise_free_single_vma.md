# Function: <code>madvise_free_single_vma</code>

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
int madvise_free_single_vma(struct vm_area_struct *vma, long unsigned int start_addr, long unsigned int end_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff811ee670)
Location: mm/madvise.c:410
Inline: False
Direct callers:
  - mm/madvise.c:SyS_madvise
```
**Symbols:**

```
ffffffff811ee670-ffffffff811ee824: madvise_free_single_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int madvise_free_single_vma(struct vm_area_struct *vma, long unsigned int start_addr, long unsigned int end_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff811fefc0)
Location: mm/madvise.c:411
Inline: False
Direct callers:
  - mm/madvise.c:SyS_madvise
```
**Symbols:**

```
ffffffff811fefc0-ffffffff811ff174: madvise_free_single_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int madvise_free_single_vma(struct vm_area_struct *vma, long unsigned int start_addr, long unsigned int end_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff81209b90)
Location: mm/madvise.c:448
Inline: False
Direct callers:
  - mm/madvise.c:SyS_madvise
```
**Symbols:**

```
ffffffff81209b90-ffffffff81209cda: madvise_free_single_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int madvise_free_single_vma(struct vm_area_struct *vma, long unsigned int start_addr, long unsigned int end_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff81222cc0)
Location: mm/madvise.c:458
Inline: False
Direct callers:
  - mm/madvise.c:SyS_madvise
```
**Symbols:**

```
ffffffff81222cc0-ffffffff81222e0c: madvise_free_single_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int madvise_free_single_vma(struct vm_area_struct *vma, long unsigned int start_addr, long unsigned int end_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff81244af0)
Location: mm/madvise.c:458
Inline: False
Direct callers:
  - mm/madvise.c:__ia32_sys_madvise
  - mm/madvise.c:__x64_sys_madvise
```
**Symbols:**

```
ffffffff81244af0-ffffffff81244c44: madvise_free_single_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int madvise_free_single_vma(struct vm_area_struct *vma, long unsigned int start_addr, long unsigned int end_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff81258e90)
Location: mm/madvise.c:458
Inline: False
Direct callers:
  - mm/madvise.c:__ia32_sys_madvise
  - mm/madvise.c:__x64_sys_madvise
```
**Symbols:**

```
ffffffff81258e90-ffffffff81259015: madvise_free_single_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int madvise_free_single_vma(struct vm_area_struct *vma, long unsigned int start_addr, long unsigned int end_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff812746a0)
Location: mm/madvise.c:458
Inline: False
Direct callers:
  - mm/madvise.c:__do_sys_madvise
```
**Symbols:**

```
ffffffff812746a0-ffffffff81274848: madvise_free_single_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int madvise_free_single_vma(struct vm_area_struct *vma, long unsigned int start_addr, long unsigned int end_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff81283630)
Location: mm/madvise.c:699
Inline: False
Direct callers:
  - mm/madvise.c:__do_sys_madvise
```
**Symbols:**

```
ffffffff81283630-ffffffff812837f8: madvise_free_single_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int madvise_free_single_vma(struct vm_area_struct *vma, long unsigned int start_addr, long unsigned int end_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff812b5490)
Location: mm/madvise.c:700
Inline: False
```
**Symbols:**

```
ffffffff812b5490-ffffffff812b565b: madvise_free_single_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int madvise_free_single_vma(struct vm_area_struct *vma, long unsigned int start_addr, long unsigned int end_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff812c0750)
Location: mm/madvise.c:705
Inline: False
```
**Symbols:**

```
ffffffff812c0750-ffffffff812c091b: madvise_free_single_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int madvise_free_single_vma(struct vm_area_struct *vma, long unsigned int start_addr, long unsigned int end_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff812c76f0)
Location: mm/madvise.c:706
Inline: False
```
**Symbols:**

```
ffffffff812c76f0-ffffffff812c7896: madvise_free_single_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int madvise_free_single_vma(struct vm_area_struct *vma, long unsigned int start_addr, long unsigned int end_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff8130c4b0)
Location: mm/madvise.c:708
Inline: False
```
**Symbols:**

```
ffffffff8130c4b0-ffffffff8130c656: madvise_free_single_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int madvise_free_single_vma(struct vm_area_struct *vma, long unsigned int start_addr, long unsigned int end_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff81375a20)
Location: mm/madvise.c:731
Inline: False
Direct callers:
  - mm/madvise.c:madvise_vma_behavior
```
**Symbols:**

```
ffffffff81375a20-ffffffff81375d84: madvise_free_single_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int madvise_free_single_vma(struct vm_area_struct *vma, long unsigned int start_addr, long unsigned int end_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff813f2fc0)
Location: mm/madvise.c:751
Inline: False
Direct callers:
  - mm/madvise.c:madvise_vma_behavior
```
**Symbols:**

```
ffffffff813f2fc0-ffffffff813f31e3: madvise_free_single_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int madvise_free_single_vma(struct vm_area_struct *vma, long unsigned int start_addr, long unsigned int end_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff81426a00)
Location: mm/madvise.c:765
Inline: False
Direct callers:
  - mm/madvise.c:madvise_vma_behavior
```
**Symbols:**

```
ffffffff81426a00-ffffffff81426c3e: madvise_free_single_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int madvise_free_single_vma(struct vm_area_struct *vma, long unsigned int start_addr, long unsigned int end_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff81460640)
Location: mm/madvise.c:759
Inline: False
Direct callers:
  - mm/madvise.c:madvise_vma_behavior
```
**Symbols:**

```
ffffffff81460640-ffffffff8146097b: madvise_free_single_vma (STB_LOCAL)
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
int madvise_free_single_vma(struct vm_area_struct *vma, long unsigned int start_addr, long unsigned int end_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffff80001031ddf8)
Location: mm/madvise.c:699
Inline: False
Direct callers:
  - mm/madvise.c:__arm64_sys_madvise
```
**Symbols:**

```
ffff80001031ddf8-ffff80001031df94: madvise_free_single_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int madvise_free_single_vma(struct vm_area_struct *vma, long unsigned int start_addr, long unsigned int end_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (c0537474)
Location: mm/madvise.c:699
Inline: False
Direct callers:
  - mm/madvise.c:__se_sys_madvise
```
**Symbols:**

```
c0537474-c0537658: madvise_free_single_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int madvise_free_single_vma(struct vm_area_struct *vma, long unsigned int start_addr, long unsigned int end_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (c0000000003f19a0)
Location: mm/madvise.c:699
Inline: False
Direct callers:
  - mm/madvise.c:__se_sys_madvise
```
**Symbols:**

```
c0000000003f19a0-c0000000003f1bd0: madvise_free_single_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int madvise_free_single_vma(struct vm_area_struct *vma, long unsigned int start_addr, long unsigned int end_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffe000220e16)
Location: mm/madvise.c:699
Inline: False
Direct callers:
  - mm/madvise.c:__se_sys_madvise
```
**Symbols:**

```
ffffffe000220e16-ffffffe000220fd4: madvise_free_single_vma (STB_LOCAL)
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
int madvise_free_single_vma(struct vm_area_struct *vma, long unsigned int start_addr, long unsigned int end_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff8127bc80)
Location: mm/madvise.c:699
Inline: False
Direct callers:
  - mm/madvise.c:__do_sys_madvise
```
**Symbols:**

```
ffffffff8127bc80-ffffffff8127be48: madvise_free_single_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int madvise_free_single_vma(struct vm_area_struct *vma, long unsigned int start_addr, long unsigned int end_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff8126db60)
Location: mm/madvise.c:699
Inline: False
Direct callers:
  - mm/madvise.c:__do_sys_madvise
```
**Symbols:**

```
ffffffff8126db60-ffffffff8126dd28: madvise_free_single_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int madvise_free_single_vma(struct vm_area_struct *vma, long unsigned int start_addr, long unsigned int end_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff81279a20)
Location: mm/madvise.c:699
Inline: False
Direct callers:
  - mm/madvise.c:__do_sys_madvise
```
**Symbols:**

```
ffffffff81279a20-ffffffff81279be8: madvise_free_single_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int madvise_free_single_vma(struct vm_area_struct *vma, long unsigned int start_addr, long unsigned int end_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff81289610)
Location: mm/madvise.c:699
Inline: False
Direct callers:
  - mm/madvise.c:__do_sys_madvise
```
**Symbols:**

```
ffffffff81289610-ffffffff812897c3: madvise_free_single_vma (STB_LOCAL)
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
