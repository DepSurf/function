# Function: <code>pseudo_lock_dev_mmap</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pseudo_lock_dev_mmap(struct file *filp, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8105c210)
Location: arch/x86/kernel/cpu/resctrl/pseudo_lock.c:1482
Inline: False
```
**Symbols:**

```
ffffffff8105c210-ffffffff8105c3a0: pseudo_lock_dev_mmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int pseudo_lock_dev_mmap(struct file *filp, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (0)
Location: arch/x86/kernel/cpu/resctrl/pseudo_lock.c:1471
Inline: False
```
**Symbols:**

```
ffffffff8105f5b0-ffffffff8105f726: pseudo_lock_dev_mmap (STB_LOCAL)
ffffffff81060e69-ffffffff81060e8e: pseudo_lock_dev_mmap.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int pseudo_lock_dev_mmap(struct file *filp, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8105fe40)
Location: arch/x86/kernel/cpu/resctrl/pseudo_lock.c:1471
Inline: False
```
**Symbols:**

```
ffffffff8105fe40-ffffffff8105ffe4: pseudo_lock_dev_mmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pseudo_lock_dev_mmap(struct file *filp, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81065910)
Location: arch/x86/kernel/cpu/resctrl/pseudo_lock.c:1471
Inline: False
```
**Symbols:**

```
ffffffff81065910-ffffffff81065ab4: pseudo_lock_dev_mmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pseudo_lock_dev_mmap(struct file *filp, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81063bc0)
Location: arch/x86/kernel/cpu/resctrl/pseudo_lock.c:1471
Inline: False
```
**Symbols:**

```
ffffffff81063bc0-ffffffff81063d64: pseudo_lock_dev_mmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pseudo_lock_dev_mmap(struct file *filp, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81064260)
Location: arch/x86/kernel/cpu/resctrl/pseudo_lock.c:1471
Inline: False
```
**Symbols:**

```
ffffffff81064260-ffffffff81064404: pseudo_lock_dev_mmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pseudo_lock_dev_mmap(struct file *filp, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8106e250)
Location: arch/x86/kernel/cpu/resctrl/pseudo_lock.c:1477
Inline: False
```
**Symbols:**

```
ffffffff8106e250-ffffffff8106e3f4: pseudo_lock_dev_mmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pseudo_lock_dev_mmap(struct file *filp, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8107baa0)
Location: arch/x86/kernel/cpu/resctrl/pseudo_lock.c:1477
Inline: False
```
**Symbols:**

```
ffffffff8107baa0-ffffffff8107bc41: pseudo_lock_dev_mmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pseudo_lock_dev_mmap(struct file *filp, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8108cec0)
Location: arch/x86/kernel/cpu/resctrl/pseudo_lock.c:1483
Inline: False
```
**Symbols:**

```
ffffffff8108cec0-ffffffff8108d054: pseudo_lock_dev_mmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pseudo_lock_dev_mmap(struct file *filp, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8108fcc0)
Location: arch/x86/kernel/cpu/resctrl/pseudo_lock.c:1483
Inline: False
```
**Symbols:**

```
ffffffff8108fcc0-ffffffff8108fe5e: pseudo_lock_dev_mmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pseudo_lock_dev_mmap(struct file *filp, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81097050)
Location: arch/x86/kernel/cpu/resctrl/pseudo_lock.c:1497
Inline: False
```
**Symbols:**

```
ffffffff81097050-ffffffff810971ee: pseudo_lock_dev_mmap (STB_LOCAL)
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
int pseudo_lock_dev_mmap(struct file *filp, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8105f9c0)
Location: arch/x86/kernel/cpu/resctrl/pseudo_lock.c:1471
Inline: False
```
**Symbols:**

```
ffffffff8105f9c0-ffffffff8105fb64: pseudo_lock_dev_mmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int pseudo_lock_dev_mmap(struct file *filp, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8104fcf0)
Location: arch/x86/kernel/cpu/resctrl/pseudo_lock.c:1471
Inline: False
```
**Symbols:**

```
ffffffff8104fcf0-ffffffff8104fe94: pseudo_lock_dev_mmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int pseudo_lock_dev_mmap(struct file *filp, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8105fdf0)
Location: arch/x86/kernel/cpu/resctrl/pseudo_lock.c:1471
Inline: False
```
**Symbols:**

```
ffffffff8105fdf0-ffffffff8105ff94: pseudo_lock_dev_mmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int pseudo_lock_dev_mmap(struct file *filp, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81061350)
Location: arch/x86/kernel/cpu/resctrl/pseudo_lock.c:1471
Inline: False
```
**Symbols:**

```
ffffffff81061350-ffffffff810614f4: pseudo_lock_dev_mmap (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
