# Function: <code>madvise_pageout</code>

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
long int madvise_pageout(struct vm_area_struct *vma, struct vm_area_struct **prev, long unsigned int start_addr, long unsigned int end_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff81283510)
Location: mm/madvise.c:540
Inline: False
Direct callers:
  - mm/madvise.c:__do_sys_madvise
```
**Symbols:**

```
ffffffff81283510-ffffffff81283625: madvise_pageout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int madvise_pageout(struct vm_area_struct *vma, struct vm_area_struct **prev, long unsigned int start_addr, long unsigned int end_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff812b5a80)
Location: mm/madvise.c:541
Inline: False
```
**Symbols:**

```
ffffffff812b5a80-ffffffff812b5b95: madvise_pageout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int madvise_pageout(struct vm_area_struct *vma, struct vm_area_struct **prev, long unsigned int start_addr, long unsigned int end_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff812c0c30)
Location: mm/madvise.c:546
Inline: False
```
**Symbols:**

```
ffffffff812c0c30-ffffffff812c0d45: madvise_pageout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int madvise_pageout(struct vm_area_struct *vma, struct vm_area_struct **prev, long unsigned int start_addr, long unsigned int end_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff812c7ba0)
Location: mm/madvise.c:547
Inline: False
```
**Symbols:**

```
ffffffff812c7ba0-ffffffff812c7cb8: madvise_pageout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int madvise_pageout(struct vm_area_struct *vma, struct vm_area_struct **prev, long unsigned int start_addr, long unsigned int end_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff8130c960)
Location: mm/madvise.c:549
Inline: False
```
**Symbols:**

```
ffffffff8130c960-ffffffff8130ca78: madvise_pageout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int madvise_pageout(struct vm_area_struct *vma, struct vm_area_struct **prev, long unsigned int start_addr, long unsigned int end_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff813754f0)
Location: mm/madvise.c:569
Inline: False
Direct callers:
  - mm/madvise.c:madvise_vma_behavior
```
**Symbols:**

```
ffffffff813754f0-ffffffff813757b0: madvise_pageout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int madvise_pageout(struct vm_area_struct *vma, struct vm_area_struct **prev, long unsigned int start_addr, long unsigned int end_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff813f3430)
Location: mm/madvise.c:581
Inline: False
Direct callers:
  - mm/madvise.c:madvise_vma_behavior
```
**Symbols:**

```
ffffffff813f3430-ffffffff813f35d4: madvise_pageout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int madvise_pageout(struct vm_area_struct *vma, struct vm_area_struct **prev, long unsigned int start_addr, long unsigned int end_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff81426e80)
Location: mm/madvise.c:593
Inline: False
Direct callers:
  - mm/madvise.c:madvise_vma_behavior
```
**Symbols:**

```
ffffffff81426e80-ffffffff81427021: madvise_pageout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int madvise_pageout(struct vm_area_struct *vma, struct vm_area_struct **prev, long unsigned int start_addr, long unsigned int end_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff81460150)
Location: mm/madvise.c:590
Inline: False
Direct callers:
  - mm/madvise.c:madvise_vma_behavior
```
**Symbols:**

```
ffffffff81460150-ffffffff814603f0: madvise_pageout (STB_LOCAL)
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
long int madvise_pageout(struct vm_area_struct *vma, struct vm_area_struct **prev, long unsigned int start_addr, long unsigned int end_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffff80001031dcb8)
Location: mm/madvise.c:540
Inline: False
Direct callers:
  - mm/madvise.c:__arm64_sys_madvise
```
**Symbols:**

```
ffff80001031dcb8-ffff80001031ddf8: madvise_pageout (STB_LOCAL)
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
In mm/madvise.c (c053800c)
Location: mm/madvise.c:540
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
long int madvise_pageout(struct vm_area_struct *vma, struct vm_area_struct **prev, long unsigned int start_addr, long unsigned int end_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (c0000000003f1810)
Location: mm/madvise.c:540
Inline: False
Direct callers:
  - mm/madvise.c:__se_sys_madvise
```
**Symbols:**

```
c0000000003f1810-c0000000003f1998: madvise_pageout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int madvise_pageout(struct vm_area_struct *vma, struct vm_area_struct **prev, long unsigned int start_addr, long unsigned int end_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffe0002207e8)
Location: mm/madvise.c:540
Inline: False
Direct callers:
  - mm/madvise.c:__se_sys_madvise
```
**Symbols:**

```
ffffffe0002207e8-ffffffe000220920: madvise_pageout (STB_LOCAL)
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
long int madvise_pageout(struct vm_area_struct *vma, struct vm_area_struct **prev, long unsigned int start_addr, long unsigned int end_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff8127bb60)
Location: mm/madvise.c:540
Inline: False
Direct callers:
  - mm/madvise.c:__do_sys_madvise
```
**Symbols:**

```
ffffffff8127bb60-ffffffff8127bc75: madvise_pageout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int madvise_pageout(struct vm_area_struct *vma, struct vm_area_struct **prev, long unsigned int start_addr, long unsigned int end_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff8126da40)
Location: mm/madvise.c:540
Inline: False
Direct callers:
  - mm/madvise.c:__do_sys_madvise
```
**Symbols:**

```
ffffffff8126da40-ffffffff8126db55: madvise_pageout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int madvise_pageout(struct vm_area_struct *vma, struct vm_area_struct **prev, long unsigned int start_addr, long unsigned int end_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff81279900)
Location: mm/madvise.c:540
Inline: False
Direct callers:
  - mm/madvise.c:__do_sys_madvise
```
**Symbols:**

```
ffffffff81279900-ffffffff81279a15: madvise_pageout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int madvise_pageout(struct vm_area_struct *vma, struct vm_area_struct **prev, long unsigned int start_addr, long unsigned int end_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff812894f0)
Location: mm/madvise.c:540
Inline: False
Direct callers:
  - mm/madvise.c:__do_sys_madvise
```
**Symbols:**

```
ffffffff812894f0-ffffffff81289605: madvise_pageout (STB_LOCAL)
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
