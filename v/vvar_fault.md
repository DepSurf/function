# Function: <code>vvar_fault</code>

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
int vvar_fault(const struct vm_special_mapping *sm, struct vm_area_struct *vma, struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81004160)
Location: arch/x86/entry/vdso/vma.c:136
Inline: False
```
**Symbols:**

```
ffffffff81004160-ffffffff81004228: vvar_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int vvar_fault(const struct vm_special_mapping *sm, struct vm_area_struct *vma, struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81003ee0)
Location: arch/x86/entry/vdso/vma.c:88
Inline: False
```
**Symbols:**

```
ffffffff81003ee0-ffffffff81003fa8: vvar_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int vvar_fault(const struct vm_special_mapping *sm, struct vm_area_struct *vma, struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81003e00)
Location: arch/x86/entry/vdso/vma.c:87
Inline: False
```
**Symbols:**

```
ffffffff81003e00-ffffffff81003f10: vvar_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int vvar_fault(const struct vm_special_mapping *sm, struct vm_area_struct *vma, struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81004050)
Location: arch/x86/entry/vdso/vma.c:87
Inline: False
```
**Symbols:**

```
ffffffff81004050-ffffffff8100416e: vvar_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int vvar_fault(const struct vm_special_mapping *sm, struct vm_area_struct *vma, struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff810047f0)
Location: arch/x86/entry/vdso/vma.c:87
Inline: False
```
**Symbols:**

```
ffffffff810047f0-ffffffff8100490e: vvar_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
vm_fault_t vvar_fault(const struct vm_special_mapping *sm, struct vm_area_struct *vma, struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81004750)
Location: arch/x86/entry/vdso/vma.c:87
Inline: False
```
**Symbols:**

```
ffffffff81004750-ffffffff81004865: vvar_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
vm_fault_t vvar_fault(const struct vm_special_mapping *sm, struct vm_area_struct *vma, struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff810049c0)
Location: arch/x86/entry/vdso/vma.c:87
Inline: False
```
**Symbols:**

```
ffffffff810049c0-ffffffff81004aca: vvar_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
vm_fault_t vvar_fault(const struct vm_special_mapping *sm, struct vm_area_struct *vma, struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81004a20)
Location: arch/x86/entry/vdso/vma.c:87
Inline: False
```
**Symbols:**

```
ffffffff81004a20-ffffffff81004b4f: vvar_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
vm_fault_t vvar_fault(const struct vm_special_mapping *sm, struct vm_area_struct *vma, struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff810059a0)
Location: arch/x86/entry/vdso/vma.c:167
Inline: False
```
**Symbols:**

```
ffffffff810059a0-ffffffff81005bcc: vvar_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
vm_fault_t vvar_fault(const struct vm_special_mapping *sm, struct vm_area_struct *vma, struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81004950)
Location: arch/x86/entry/vdso/vma.c:150
Inline: False
```
**Symbols:**

```
ffffffff81004950-ffffffff81004b7c: vvar_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
vm_fault_t vvar_fault(const struct vm_special_mapping *sm, struct vm_area_struct *vma, struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81004940)
Location: arch/x86/entry/vdso/vma.c:150
Inline: False
```
**Symbols:**

```
ffffffff81004940-ffffffff81004b66: vvar_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
vm_fault_t vvar_fault(const struct vm_special_mapping *sm, struct vm_area_struct *vma, struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81004f70)
Location: arch/x86/entry/vdso/vma.c:150
Inline: False
```
**Symbols:**

```
ffffffff81004f70-ffffffff81005196: vvar_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
vm_fault_t vvar_fault(const struct vm_special_mapping *sm, struct vm_area_struct *vma, struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81003fb0)
Location: arch/x86/entry/vdso/vma.c:150
Inline: False
```
**Symbols:**

```
ffffffff81003fb0-ffffffff810041fc: vvar_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
vm_fault_t vvar_fault(const struct vm_special_mapping *sm, struct vm_area_struct *vma, struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81004670)
Location: arch/x86/entry/vdso/vma.c:127
Inline: False
```
**Symbols:**

```
ffffffff81004670-ffffffff8100480e: vvar_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
vm_fault_t vvar_fault(const struct vm_special_mapping *sm, struct vm_area_struct *vma, struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81003e30)
Location: arch/x86/entry/vdso/vma.c:128
Inline: False
```
**Symbols:**

```
ffffffff81003e30-ffffffff81003fce: vvar_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
vm_fault_t vvar_fault(const struct vm_special_mapping *sm, struct vm_area_struct *vma, struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81006740)
Location: arch/x86/entry/vdso/vma.c:128
Inline: False
```
**Symbols:**

```
ffffffff81006740-ffffffff810068de: vvar_fault (STB_LOCAL)
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
vm_fault_t vvar_fault(const struct vm_special_mapping *sm, struct vm_area_struct *vma, struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81004a20)
Location: arch/x86/entry/vdso/vma.c:87
Inline: False
```
**Symbols:**

```
ffffffff81004a20-ffffffff81004b4f: vvar_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
vm_fault_t vvar_fault(const struct vm_special_mapping *sm, struct vm_area_struct *vma, struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81003100)
Location: arch/x86/entry/vdso/vma.c:87
Inline: False
```
**Symbols:**

```
ffffffff81003100-ffffffff8100322f: vvar_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
vm_fault_t vvar_fault(const struct vm_special_mapping *sm, struct vm_area_struct *vma, struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff810049e0)
Location: arch/x86/entry/vdso/vma.c:87
Inline: False
```
**Symbols:**

```
ffffffff810049e0-ffffffff81004b0f: vvar_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
vm_fault_t vvar_fault(const struct vm_special_mapping *sm, struct vm_area_struct *vma, struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81004b20)
Location: arch/x86/entry/vdso/vma.c:87
Inline: False
```
**Symbols:**

```
ffffffff81004b20-ffffffff81004c4f: vvar_fault (STB_LOCAL)
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
