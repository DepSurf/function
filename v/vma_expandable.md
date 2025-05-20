# Function: <code>vma_expandable</code>

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
In mm/mremap.c (ffffffff811ca0d2)
Location: mm/mremap.c:451
Inline: True
Inline callers:
  - mm/mremap.c:SyS_mremap
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
In mm/mremap.c (ffffffff811e6591)
Location: mm/mremap.c:455
Inline: True
Inline callers:
  - mm/mremap.c:SyS_mremap
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
In mm/mremap.c (ffffffff811f6857)
Location: mm/mremap.c:471
Inline: True
Inline callers:
  - mm/mremap.c:SyS_mremap
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
In mm/mremap.c (ffffffff8120160b)
Location: mm/mremap.c:489
Inline: True
Inline callers:
  - mm/mremap.c:SyS_mremap
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
In mm/mremap.c (ffffffff81219fcb)
Location: mm/mremap.c:503
Inline: True
Inline callers:
  - mm/mremap.c:SyS_mremap
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int vma_expandable(struct vm_area_struct *vma, long unsigned int delta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mremap.c (ffffffff8123a600)
Location: mm/mremap.c:499
Inline: False
Direct callers:
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
```
**Symbols:**

```
ffffffff8123a600-ffffffff8123a648: vma_expandable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int vma_expandable(struct vm_area_struct *vma, long unsigned int delta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mremap.c (ffffffff8124e770)
Location: mm/mremap.c:557
Inline: False
Direct callers:
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
```
**Symbols:**

```
ffffffff8124e770-ffffffff8124e7b8: vma_expandable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int vma_expandable(struct vm_area_struct *vma, long unsigned int delta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mremap.c (ffffffff81260ab0)
Location: mm/mremap.c:575
Inline: False
Direct callers:
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
```
**Symbols:**

```
ffffffff81260ab0-ffffffff81260b03: vma_expandable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int vma_expandable(struct vm_area_struct *vma, long unsigned int delta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mremap.c (ffffffff8126f240)
Location: mm/mremap.c:575
Inline: False
Direct callers:
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
```
**Symbols:**

```
ffffffff8126f240-ffffffff8126f293: vma_expandable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mremap.c (ffffffff812a12f1)
Location: mm/mremap.c:643
Inline: True
Inline callers:
  - mm/mremap.c:__do_sys_mremap
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mremap.c (ffffffff812acb48)
Location: mm/mremap.c:791
Inline: True
Inline callers:
  - mm/mremap.c:__do_sys_mremap
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mremap.c (ffffffff812b1e3c)
Location: mm/mremap.c:796
Inline: True
Inline callers:
  - mm/mremap.c:__do_sys_mremap
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mremap.c (ffffffff812f3a22)
Location: mm/mremap.c:875
Inline: True
Inline callers:
  - mm/mremap.c:__do_sys_mremap
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mremap.c (ffffffff813577a5)
Location: mm/mremap.c:866
Inline: True
Inline callers:
  - mm/mremap.c:__do_sys_mremap
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mremap.c (ffffffff813d1e89)
Location: mm/mremap.c:868
Inline: True
Inline callers:
  - mm/mremap.c:__do_sys_mremap
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mremap.c (ffffffff81406a58)
Location: mm/mremap.c:887
Inline: True
Inline callers:
  - mm/mremap.c:__do_sys_mremap
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mremap.c (ffffffff81433167)
Location: mm/mremap.c:954
Inline: True
Inline callers:
  - mm/mremap.c:__do_sys_mremap
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mremap.c (ffff800010306acc)
Location: mm/mremap.c:575
Inline: True
Inline callers:
  - mm/mremap.c:__arm64_sys_mremap
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mremap.c (c05246c4)
Location: mm/mremap.c:575
Inline: True
Inline callers:
  - mm/mremap.c:__se_sys_mremap
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mremap.c (c0000000003d4c54)
Location: mm/mremap.c:575
Inline: True
Inline callers:
  - mm/mremap.c:__se_sys_mremap
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mremap.c (ffffffe0002122f4)
Location: mm/mremap.c:575
Inline: True
Inline callers:
  - mm/mremap.c:__se_sys_mremap
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
int vma_expandable(struct vm_area_struct *vma, long unsigned int delta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mremap.c (ffffffff81267890)
Location: mm/mremap.c:575
Inline: False
Direct callers:
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
```
**Symbols:**

```
ffffffff81267890-ffffffff812678e3: vma_expandable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int vma_expandable(struct vm_area_struct *vma, long unsigned int delta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mremap.c (ffffffff81259be0)
Location: mm/mremap.c:575
Inline: False
Direct callers:
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
```
**Symbols:**

```
ffffffff81259be0-ffffffff81259c33: vma_expandable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int vma_expandable(struct vm_area_struct *vma, long unsigned int delta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mremap.c (ffffffff81265630)
Location: mm/mremap.c:575
Inline: False
Direct callers:
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
```
**Symbols:**

```
ffffffff81265630-ffffffff81265683: vma_expandable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int vma_expandable(struct vm_area_struct *vma, long unsigned int delta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mremap.c (ffffffff81274fe0)
Location: mm/mremap.c:575
Inline: False
Direct callers:
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
```
**Symbols:**

```
ffffffff81274fe0-ffffffff81275033: vma_expandable (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
