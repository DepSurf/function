# Function: <code>vdso_fault</code>

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
int vdso_fault(const struct vm_special_mapping *sm, struct vm_area_struct *vma, struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff810040b0)
Location: arch/x86/entry/vdso/vma.c:88
Inline: False
```
**Symbols:**

```
ffffffff810040b0-ffffffff81004152: vdso_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int vdso_fault(const struct vm_special_mapping *sm, struct vm_area_struct *vma, struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81003fb0)
Location: arch/x86/entry/vdso/vma.c:40
Inline: False
```
**Symbols:**

```
ffffffff81003fb0-ffffffff8100404c: vdso_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int vdso_fault(const struct vm_special_mapping *sm, struct vm_area_struct *vma, struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81003d70)
Location: arch/x86/entry/vdso/vma.c:42
Inline: False
```
**Symbols:**

```
ffffffff81003d70-ffffffff81003df7: vdso_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int vdso_fault(const struct vm_special_mapping *sm, struct vm_area_struct *vma, struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81003fc0)
Location: arch/x86/entry/vdso/vma.c:42
Inline: False
```
**Symbols:**

```
ffffffff81003fc0-ffffffff81004048: vdso_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int vdso_fault(const struct vm_special_mapping *sm, struct vm_area_struct *vma, struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81004690)
Location: arch/x86/entry/vdso/vma.c:42
Inline: False
```
**Symbols:**

```
ffffffff81004690-ffffffff81004717: vdso_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
vm_fault_t vdso_fault(const struct vm_special_mapping *sm, struct vm_area_struct *vma, struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff810046c0)
Location: arch/x86/entry/vdso/vma.c:42
Inline: False
```
**Symbols:**

```
ffffffff810046c0-ffffffff81004747: vdso_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
vm_fault_t vdso_fault(const struct vm_special_mapping *sm, struct vm_area_struct *vma, struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81004930)
Location: arch/x86/entry/vdso/vma.c:42
Inline: False
```
**Symbols:**

```
ffffffff81004930-ffffffff810049bd: vdso_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
vm_fault_t vdso_fault(const struct vm_special_mapping *sm, struct vm_area_struct *vma, struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81004990)
Location: arch/x86/entry/vdso/vma.c:42
Inline: False
```
**Symbols:**

```
ffffffff81004990-ffffffff81004a1d: vdso_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
vm_fault_t vdso_fault(const struct vm_special_mapping *sm, struct vm_area_struct *vma, struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81005720)
Location: arch/x86/entry/vdso/vma.c:59
Inline: False
```
**Symbols:**

```
ffffffff81005720-ffffffff810057ad: vdso_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
vm_fault_t vdso_fault(const struct vm_special_mapping *sm, struct vm_area_struct *vma, struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81004680)
Location: arch/x86/entry/vdso/vma.c:59
Inline: False
```
**Symbols:**

```
ffffffff81004680-ffffffff8100470d: vdso_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
vm_fault_t vdso_fault(const struct vm_special_mapping *sm, struct vm_area_struct *vma, struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81004680)
Location: arch/x86/entry/vdso/vma.c:59
Inline: False
```
**Symbols:**

```
ffffffff81004680-ffffffff8100470d: vdso_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
vm_fault_t vdso_fault(const struct vm_special_mapping *sm, struct vm_area_struct *vma, struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81004cb0)
Location: arch/x86/entry/vdso/vma.c:59
Inline: False
```
**Symbols:**

```
ffffffff81004cb0-ffffffff81004d3d: vdso_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
vm_fault_t vdso_fault(const struct vm_special_mapping *sm, struct vm_area_struct *vma, struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81003d50)
Location: arch/x86/entry/vdso/vma.c:59
Inline: False
```
**Symbols:**

```
ffffffff81003d50-ffffffff81003e1c: vdso_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
vm_fault_t vdso_fault(const struct vm_special_mapping *sm, struct vm_area_struct *vma, struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81004820)
Location: arch/x86/entry/vdso/vma.c:59
Inline: False
```
**Symbols:**

```
ffffffff81004820-ffffffff810048ec: vdso_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
vm_fault_t vdso_fault(const struct vm_special_mapping *sm, struct vm_area_struct *vma, struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81003fe0)
Location: arch/x86/entry/vdso/vma.c:62
Inline: False
```
**Symbols:**

```
ffffffff81003fe0-ffffffff810040ac: vdso_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
vm_fault_t vdso_fault(const struct vm_special_mapping *sm, struct vm_area_struct *vma, struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff810068f0)
Location: arch/x86/entry/vdso/vma.c:62
Inline: False
```
**Symbols:**

```
ffffffff810068f0-ffffffff810069b5: vdso_fault (STB_LOCAL)
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
vm_fault_t vdso_fault(const struct vm_special_mapping *sm, struct vm_area_struct *vma, struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81004990)
Location: arch/x86/entry/vdso/vma.c:42
Inline: False
```
**Symbols:**

```
ffffffff81004990-ffffffff81004a1d: vdso_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
vm_fault_t vdso_fault(const struct vm_special_mapping *sm, struct vm_area_struct *vma, struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81003070)
Location: arch/x86/entry/vdso/vma.c:42
Inline: False
```
**Symbols:**

```
ffffffff81003070-ffffffff810030fd: vdso_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
vm_fault_t vdso_fault(const struct vm_special_mapping *sm, struct vm_area_struct *vma, struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81004950)
Location: arch/x86/entry/vdso/vma.c:42
Inline: False
```
**Symbols:**

```
ffffffff81004950-ffffffff810049dd: vdso_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
vm_fault_t vdso_fault(const struct vm_special_mapping *sm, struct vm_area_struct *vma, struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81004a90)
Location: arch/x86/entry/vdso/vma.c:42
Inline: False
```
**Symbols:**

```
ffffffff81004a90-ffffffff81004b1d: vdso_fault (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>vm_fault_t</code>
</li>
</ul>
</details>
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
