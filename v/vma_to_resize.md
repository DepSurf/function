# Function: <code>vma_to_resize</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct vm_area_struct *vma_to_resize(long unsigned int addr, long unsigned int old_len, long unsigned int new_len, long unsigned int *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mremap.c (ffffffff811c9140)
Location: mm/mremap.c:344
Inline: False
Direct callers:
  - mm/mremap.c:SyS_mremap
  - mm/mremap.c:SyS_mremap
```
**Symbols:**

```
ffffffff811c9140-ffffffff811c92bb: vma_to_resize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct vm_area_struct *vma_to_resize(long unsigned int addr, long unsigned int old_len, long unsigned int new_len, long unsigned int *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mremap.c (ffffffff811e5540)
Location: mm/mremap.c:347
Inline: False
Direct callers:
  - mm/mremap.c:SyS_mremap
  - mm/mremap.c:SyS_mremap
```
**Symbols:**

```
ffffffff811e5540-ffffffff811e569a: vma_to_resize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct vm_area_struct *vma_to_resize(long unsigned int addr, long unsigned int old_len, long unsigned int new_len, long unsigned int *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mremap.c (ffffffff811f5760)
Location: mm/mremap.c:363
Inline: False
Direct callers:
  - mm/mremap.c:SyS_mremap
  - mm/mremap.c:SyS_mremap
```
**Symbols:**

```
ffffffff811f5760-ffffffff811f58ba: vma_to_resize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct vm_area_struct *vma_to_resize(long unsigned int addr, long unsigned int old_len, long unsigned int new_len, long unsigned int *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mremap.c (ffffffff81200540)
Location: mm/mremap.c:377
Inline: False
Direct callers:
  - mm/mremap.c:SyS_mremap
  - mm/mremap.c:SyS_mremap
```
**Symbols:**

```
ffffffff81200540-ffffffff81200696: vma_to_resize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct vm_area_struct *vma_to_resize(long unsigned int addr, long unsigned int old_len, long unsigned int new_len, long unsigned int *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mremap.c (ffffffff81218ce0)
Location: mm/mremap.c:378
Inline: False
Direct callers:
  - mm/mremap.c:SyS_mremap
  - mm/mremap.c:SyS_mremap
```
**Symbols:**

```
ffffffff81218ce0-ffffffff81218e84: vma_to_resize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
struct vm_area_struct *vma_to_resize(long unsigned int addr, long unsigned int old_len, long unsigned int new_len, long unsigned int *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/mremap.c (0)
Location: mm/mremap.c:374
Inline: False
Direct callers:
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
  - mm/mremap.c:mremap_to
```
**Symbols:**

```
ffffffff8123a650-ffffffff8123a818: vma_to_resize (STB_LOCAL)
ffffffff8123be97-ffffffff8123bec4: vma_to_resize.cold.25 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
struct vm_area_struct *vma_to_resize(long unsigned int addr, long unsigned int old_len, long unsigned int new_len, long unsigned int *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/mremap.c (0)
Location: mm/mremap.c:432
Inline: False
Direct callers:
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
  - mm/mremap.c:mremap_to
```
**Symbols:**

```
ffffffff8124e7c0-ffffffff8124e988: vma_to_resize (STB_LOCAL)
ffffffff812502b4-ffffffff812502e1: vma_to_resize.cold.32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct vm_area_struct *vma_to_resize(long unsigned int addr, long unsigned int old_len, long unsigned int new_len, long unsigned int *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/mremap.c (0)
Location: mm/mremap.c:433
Inline: False
Direct callers:
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
  - mm/mremap.c:mremap_to
```
**Symbols:**

```
ffffffff81260b10-ffffffff81260cdc: vma_to_resize (STB_LOCAL)
ffffffff812625ac-ffffffff812625d9: vma_to_resize.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct vm_area_struct *vma_to_resize(long unsigned int addr, long unsigned int old_len, long unsigned int new_len, long unsigned int *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/mremap.c (0)
Location: mm/mremap.c:433
Inline: False
Direct callers:
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
  - mm/mremap.c:mremap_to
```
**Symbols:**

```
ffffffff8126f2a0-ffffffff8126f46c: vma_to_resize (STB_LOCAL)
ffffffff81270d7c-ffffffff81270da9: vma_to_resize.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct vm_area_struct *vma_to_resize(long unsigned int addr, long unsigned int old_len, long unsigned int new_len, long unsigned int flags, long unsigned int *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/mremap.c (0)
Location: mm/mremap.c:479
Inline: False
Direct callers:
  - mm/mremap.c:__do_sys_mremap
  - mm/mremap.c:mremap_to
```
**Symbols:**

```
ffffffff8129f830-ffffffff8129fa33: vma_to_resize (STB_LOCAL)
ffffffff812a1454-ffffffff812a1484: vma_to_resize.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct vm_area_struct *vma_to_resize(long unsigned int addr, long unsigned int old_len, long unsigned int new_len, long unsigned int flags, long unsigned int *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/mremap.c (0)
Location: mm/mremap.c:627
Inline: False
Direct callers:
  - mm/mremap.c:__do_sys_mremap
  - mm/mremap.c:mremap_to
```
**Symbols:**

```
ffffffff812aaca0-ffffffff812aaea3: vma_to_resize (STB_LOCAL)
ffffffff81be7aa0-ffffffff81be7ad0: vma_to_resize.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct vm_area_struct *vma_to_resize(long unsigned int addr, long unsigned int old_len, long unsigned int new_len, long unsigned int flags, long unsigned int *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/mremap.c (0)
Location: mm/mremap.c:632
Inline: False
Direct callers:
  - mm/mremap.c:__do_sys_mremap
  - mm/mremap.c:mremap_to
```
**Symbols:**

```
ffffffff812b00e0-ffffffff812b02b5: vma_to_resize (STB_LOCAL)
ffffffff81bd9902-ffffffff81bd9932: vma_to_resize.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct vm_area_struct *vma_to_resize(long unsigned int addr, long unsigned int old_len, long unsigned int new_len, long unsigned int flags, long unsigned int *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/mremap.c (0)
Location: mm/mremap.c:710
Inline: False
Direct callers:
  - mm/mremap.c:__do_sys_mremap
  - mm/mremap.c:mremap_to
```
**Symbols:**

```
ffffffff812f1960-ffffffff812f1b06: vma_to_resize (STB_LOCAL)
ffffffff81cbca59-ffffffff81cbcaa2: vma_to_resize.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct vm_area_struct *vma_to_resize(long unsigned int addr, long unsigned int old_len, long unsigned int new_len, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/mremap.c (0)
Location: mm/mremap.c:725
Inline: False
Direct callers:
  - mm/mremap.c:__do_sys_mremap
```
**Symbols:**

```
ffffffff81355890-ffffffff81355a06: vma_to_resize (STB_LOCAL)
ffffffff81e6e640-ffffffff81e6e654: vma_to_resize.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct vm_area_struct *vma_to_resize(long unsigned int addr, long unsigned int old_len, long unsigned int new_len, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/mremap.c (0)
Location: mm/mremap.c:727
Inline: False
Direct callers:
  - mm/mremap.c:__do_sys_mremap
```
**Symbols:**

```
ffffffff813cfc90-ffffffff813cfdf5: vma_to_resize (STB_LOCAL)
ffffffff82064538-ffffffff8206454c: vma_to_resize.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct vm_area_struct *vma_to_resize(long unsigned int addr, long unsigned int old_len, long unsigned int new_len, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/mremap.c (0)
Location: mm/mremap.c:746
Inline: False
Direct callers:
  - mm/mremap.c:__do_sys_mremap
```
**Symbols:**

```
ffffffff81404750-ffffffff814048b9: vma_to_resize (STB_LOCAL)
ffffffff820e3c13-ffffffff820e3c27: vma_to_resize.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct vm_area_struct *vma_to_resize(long unsigned int addr, long unsigned int old_len, long unsigned int new_len, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/mremap.c (0)
Location: mm/mremap.c:813
Inline: False
Direct callers:
  - mm/mremap.c:__do_sys_mremap
```
**Symbols:**

```
ffffffff81430d20-ffffffff81430e89: vma_to_resize (STB_LOCAL)
ffffffff821c07bc-ffffffff821c07d0: vma_to_resize.cold (STB_LOCAL)
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
struct vm_area_struct *vma_to_resize(long unsigned int addr, long unsigned int old_len, long unsigned int new_len, long unsigned int *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mremap.c (ffff800010305c50)
Location: mm/mremap.c:433
Inline: False
Direct callers:
  - mm/mremap.c:__arm64_sys_mremap
  - mm/mremap.c:__arm64_sys_mremap
```
**Symbols:**

```
ffff800010305c50-ffff800010305df8: vma_to_resize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct vm_area_struct *vma_to_resize(long unsigned int addr, long unsigned int old_len, long unsigned int new_len, long unsigned int *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mremap.c (c0523b78)
Location: mm/mremap.c:433
Inline: False
Direct callers:
  - mm/mremap.c:__se_sys_mremap
  - mm/mremap.c:__se_sys_mremap
```
**Symbols:**

```
c0523b78-c0523d1c: vma_to_resize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct vm_area_struct *vma_to_resize(long unsigned int addr, long unsigned int old_len, long unsigned int new_len, long unsigned int *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mremap.c (c0000000003d3300)
Location: mm/mremap.c:433
Inline: False
Direct callers:
  - mm/mremap.c:__se_sys_mremap
  - mm/mremap.c:__se_sys_mremap
```
**Symbols:**

```
c0000000003d3300-c0000000003d3550: vma_to_resize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct vm_area_struct *vma_to_resize(long unsigned int addr, long unsigned int old_len, long unsigned int new_len, long unsigned int *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mremap.c (ffffffe0002118fa)
Location: mm/mremap.c:433
Inline: False
Direct callers:
  - mm/mremap.c:__se_sys_mremap
  - mm/mremap.c:__se_sys_mremap
```
**Symbols:**

```
ffffffe0002118fa-ffffffe000211a3a: vma_to_resize (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
struct vm_area_struct *vma_to_resize(long unsigned int addr, long unsigned int old_len, long unsigned int new_len, long unsigned int *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/mremap.c (0)
Location: mm/mremap.c:433
Inline: False
Direct callers:
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
  - mm/mremap.c:mremap_to
```
**Symbols:**

```
ffffffff812678f0-ffffffff81267abc: vma_to_resize (STB_LOCAL)
ffffffff812693cc-ffffffff812693f9: vma_to_resize.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct vm_area_struct *vma_to_resize(long unsigned int addr, long unsigned int old_len, long unsigned int new_len, long unsigned int *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/mremap.c (0)
Location: mm/mremap.c:433
Inline: False
Direct callers:
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
  - mm/mremap.c:mremap_to
```
**Symbols:**

```
ffffffff81259c40-ffffffff81259e0c: vma_to_resize (STB_LOCAL)
ffffffff8125b6bc-ffffffff8125b6e9: vma_to_resize.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct vm_area_struct *vma_to_resize(long unsigned int addr, long unsigned int old_len, long unsigned int new_len, long unsigned int *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/mremap.c (0)
Location: mm/mremap.c:433
Inline: False
Direct callers:
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
  - mm/mremap.c:mremap_to
```
**Symbols:**

```
ffffffff81265690-ffffffff8126585c: vma_to_resize (STB_LOCAL)
ffffffff8126716c-ffffffff81267199: vma_to_resize.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct vm_area_struct *vma_to_resize(long unsigned int addr, long unsigned int old_len, long unsigned int new_len, long unsigned int *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/mremap.c (0)
Location: mm/mremap.c:433
Inline: False
Direct callers:
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
  - mm/mremap.c:mremap_to
```
**Symbols:**

```
ffffffff81275040-ffffffff8127520c: vma_to_resize (STB_LOCAL)
ffffffff81276b0c-ffffffff81276b39: vma_to_resize.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int flags</code>
</li>
<li>
<b>Param reordered. </b>
<code>addr, old_len, new_len, p</code> ➡️ <code>addr, old_len, new_len, flags, p</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>long unsigned int *p</code>
</li>
</ul>
</details>
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
