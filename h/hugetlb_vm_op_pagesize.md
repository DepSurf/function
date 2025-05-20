# Function: <code>hugetlb_vm_op_pagesize</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long unsigned int hugetlb_vm_op_pagesize(struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81251740)
Location: mm/hugetlb.c:3151
Inline: False
```
**Symbols:**

```
ffffffff81251740-ffffffff81251773: hugetlb_vm_op_pagesize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long unsigned int hugetlb_vm_op_pagesize(struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81265b40)
Location: mm/hugetlb.c:3145
Inline: False
```
**Symbols:**

```
ffffffff81265b40-ffffffff81265b73: hugetlb_vm_op_pagesize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long unsigned int hugetlb_vm_op_pagesize(struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81280b70)
Location: mm/hugetlb.c:3213
Inline: False
```
**Symbols:**

```
ffffffff81280b70-ffffffff81280ba3: hugetlb_vm_op_pagesize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int hugetlb_vm_op_pagesize(struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81290580)
Location: mm/hugetlb.c:3330
Inline: False
```
**Symbols:**

```
ffffffff81290580-ffffffff812905b3: hugetlb_vm_op_pagesize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int hugetlb_vm_op_pagesize(struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812c31e0)
Location: mm/hugetlb.c:3741
Inline: False
```
**Symbols:**

```
ffffffff812c31e0-ffffffff812c3213: hugetlb_vm_op_pagesize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int hugetlb_vm_op_pagesize(struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812cef30)
Location: mm/hugetlb.c:3711
Inline: False
```
**Symbols:**

```
ffffffff812cef30-ffffffff812cef63: hugetlb_vm_op_pagesize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int hugetlb_vm_op_pagesize(struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812d5bd0)
Location: mm/hugetlb.c:3882
Inline: False
```
**Symbols:**

```
ffffffff812d5bd0-ffffffff812d5c00: hugetlb_vm_op_pagesize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
long unsigned int hugetlb_vm_op_pagesize(struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:4170
Inline: False
```
**Symbols:**

```
ffffffff8131cc70-ffffffff8131cca4: hugetlb_vm_op_pagesize (STB_LOCAL)
ffffffff81cbf36e-ffffffff81cbf396: hugetlb_vm_op_pagesize.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
long unsigned int hugetlb_vm_op_pagesize(struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:4622
Inline: False
```
**Symbols:**

```
ffffffff81388bf0-ffffffff81388c30: hugetlb_vm_op_pagesize (STB_LOCAL)
ffffffff81e71617-ffffffff81e7164b: hugetlb_vm_op_pagesize.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
long unsigned int hugetlb_vm_op_pagesize(struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:4861
Inline: False
```
**Symbols:**

```
ffffffff81406ec0-ffffffff81406f07: hugetlb_vm_op_pagesize (STB_LOCAL)
ffffffff8206611c-ffffffff82066137: hugetlb_vm_op_pagesize.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
long unsigned int hugetlb_vm_op_pagesize(struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:4936
Inline: False
```
**Symbols:**

```
ffffffff8143a5e0-ffffffff8143a62d: hugetlb_vm_op_pagesize (STB_LOCAL)
ffffffff820e5866-ffffffff820e5881: hugetlb_vm_op_pagesize.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
long unsigned int hugetlb_vm_op_pagesize(struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:5194
Inline: False
```
**Symbols:**

```
ffffffff814746c0-ffffffff8147470d: hugetlb_vm_op_pagesize (STB_LOCAL)
ffffffff821c2a94-ffffffff821c2aaf: hugetlb_vm_op_pagesize.cold (STB_LOCAL)
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
long unsigned int hugetlb_vm_op_pagesize(struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffff80001032d6b8)
Location: mm/hugetlb.c:3330
Inline: False
```
**Symbols:**

```
ffff80001032d6b8-ffff80001032d700: hugetlb_vm_op_pagesize (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long unsigned int hugetlb_vm_op_pagesize(struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (c0000000004051f0)
Location: mm/hugetlb.c:3330
Inline: False
```
**Symbols:**

```
c0000000004051f0-c000000000405220: hugetlb_vm_op_pagesize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long unsigned int hugetlb_vm_op_pagesize(struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffe00022bca4)
Location: mm/hugetlb.c:3330
Inline: False
```
**Symbols:**

```
ffffffe00022bca4-ffffffe00022bcda: hugetlb_vm_op_pagesize (STB_LOCAL)
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
long unsigned int hugetlb_vm_op_pagesize(struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81288b60)
Location: mm/hugetlb.c:3330
Inline: False
```
**Symbols:**

```
ffffffff81288b60-ffffffff81288b93: hugetlb_vm_op_pagesize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int hugetlb_vm_op_pagesize(struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8127a9b0)
Location: mm/hugetlb.c:3330
Inline: False
```
**Symbols:**

```
ffffffff8127a9b0-ffffffff8127a9e3: hugetlb_vm_op_pagesize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int hugetlb_vm_op_pagesize(struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81286970)
Location: mm/hugetlb.c:3330
Inline: False
```
**Symbols:**

```
ffffffff81286970-ffffffff812869a3: hugetlb_vm_op_pagesize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int hugetlb_vm_op_pagesize(struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81296760)
Location: mm/hugetlb.c:3330
Inline: False
```
**Symbols:**

```
ffffffff81296760-ffffffff81296793: hugetlb_vm_op_pagesize (STB_LOCAL)
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
