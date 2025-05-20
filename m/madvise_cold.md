# Function: <code>madvise_cold</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int madvise_cold(struct vm_area_struct *vma, struct vm_area_struct **prev, long unsigned int start_addr, long unsigned int end_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff81283440)
Location: mm/madvise.c:491
Inline: False
Direct callers:
  - mm/madvise.c:__do_sys_madvise
```
**Symbols:**

```
ffffffff81283440-ffffffff8128350d: madvise_cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int madvise_cold(struct vm_area_struct *vma, struct vm_area_struct **prev, long unsigned int start_addr, long unsigned int end_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff812b5ba0)
Location: mm/madvise.c:492
Inline: False
```
**Symbols:**

```
ffffffff812b5ba0-ffffffff812b5c6d: madvise_cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int madvise_cold(struct vm_area_struct *vma, struct vm_area_struct **prev, long unsigned int start_addr, long unsigned int end_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff812c0d50)
Location: mm/madvise.c:497
Inline: False
```
**Symbols:**

```
ffffffff812c0d50-ffffffff812c0e1d: madvise_cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int madvise_cold(struct vm_area_struct *vma, struct vm_area_struct **prev, long unsigned int start_addr, long unsigned int end_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff812c7cc0)
Location: mm/madvise.c:497
Inline: False
```
**Symbols:**

```
ffffffff812c7cc0-ffffffff812c7d7d: madvise_cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int madvise_cold(struct vm_area_struct *vma, struct vm_area_struct **prev, long unsigned int start_addr, long unsigned int end_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff8130ca80)
Location: mm/madvise.c:499
Inline: False
```
**Symbols:**

```
ffffffff8130ca80-ffffffff8130cb3d: madvise_cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int madvise_cold(struct vm_area_struct *vma, struct vm_area_struct **prev, long unsigned int start_addr, long unsigned int end_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff813757b0)
Location: mm/madvise.c:519
Inline: False
Direct callers:
  - mm/madvise.c:madvise_vma_behavior
```
**Symbols:**

```
ffffffff813757b0-ffffffff81375a18: madvise_cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int madvise_cold(struct vm_area_struct *vma, struct vm_area_struct **prev, long unsigned int start_addr, long unsigned int end_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff813f3200)
Location: mm/madvise.c:548
Inline: False
Direct callers:
  - mm/madvise.c:madvise_vma_behavior
```
**Symbols:**

```
ffffffff813f3200-ffffffff813f3335: madvise_cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int madvise_cold(struct vm_area_struct *vma, struct vm_area_struct **prev, long unsigned int start_addr, long unsigned int end_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff81426c50)
Location: mm/madvise.c:560
Inline: False
Direct callers:
  - mm/madvise.c:madvise_vma_behavior
```
**Symbols:**

```
ffffffff81426c50-ffffffff81426d85: madvise_cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int madvise_cold(struct vm_area_struct *vma, struct vm_area_struct **prev, long unsigned int start_addr, long unsigned int end_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff81460400)
Location: mm/madvise.c:557
Inline: False
Direct callers:
  - mm/madvise.c:madvise_vma_behavior
```
**Symbols:**

```
ffffffff81460400-ffffffff8146062f: madvise_cold (STB_LOCAL)
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
long int madvise_cold(struct vm_area_struct *vma, struct vm_area_struct **prev, long unsigned int start_addr, long unsigned int end_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffff80001031dbc8)
Location: mm/madvise.c:491
Inline: False
Direct callers:
  - mm/madvise.c:__arm64_sys_madvise
```
**Symbols:**

```
ffff80001031dbc8-ffff80001031dcb4: madvise_cold (STB_LOCAL)
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
In mm/madvise.c (c0538128)
Location: mm/madvise.c:491
Inline: True
Inline callers:
  - mm/madvise.c:__se_sys_madvise
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int madvise_cold(struct vm_area_struct *vma, struct vm_area_struct **prev, long unsigned int start_addr, long unsigned int end_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (c0000000003f16d0)
Location: mm/madvise.c:491
Inline: False
Direct callers:
  - mm/madvise.c:__se_sys_madvise
```
**Symbols:**

```
c0000000003f16d0-c0000000003f1808: madvise_cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int madvise_cold(struct vm_area_struct *vma, struct vm_area_struct **prev, long unsigned int start_addr, long unsigned int end_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffe000220aa6)
Location: mm/madvise.c:491
Inline: False
Direct callers:
  - mm/madvise.c:__se_sys_madvise
```
**Symbols:**

```
ffffffe000220aa6-ffffffe000220ba8: madvise_cold (STB_LOCAL)
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
long int madvise_cold(struct vm_area_struct *vma, struct vm_area_struct **prev, long unsigned int start_addr, long unsigned int end_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff8127ba90)
Location: mm/madvise.c:491
Inline: False
Direct callers:
  - mm/madvise.c:__do_sys_madvise
```
**Symbols:**

```
ffffffff8127ba90-ffffffff8127bb5d: madvise_cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int madvise_cold(struct vm_area_struct *vma, struct vm_area_struct **prev, long unsigned int start_addr, long unsigned int end_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff8126d970)
Location: mm/madvise.c:491
Inline: False
Direct callers:
  - mm/madvise.c:__do_sys_madvise
```
**Symbols:**

```
ffffffff8126d970-ffffffff8126da3d: madvise_cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int madvise_cold(struct vm_area_struct *vma, struct vm_area_struct **prev, long unsigned int start_addr, long unsigned int end_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff81279830)
Location: mm/madvise.c:491
Inline: False
Direct callers:
  - mm/madvise.c:__do_sys_madvise
```
**Symbols:**

```
ffffffff81279830-ffffffff812798fd: madvise_cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int madvise_cold(struct vm_area_struct *vma, struct vm_area_struct **prev, long unsigned int start_addr, long unsigned int end_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff81289420)
Location: mm/madvise.c:491
Inline: False
Direct callers:
  - mm/madvise.c:__do_sys_madvise
```
**Symbols:**

```
ffffffff81289420-ffffffff812894ed: madvise_cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
