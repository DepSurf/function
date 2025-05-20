# Function: <code>xen_pv_cpu_up</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int xen_pv_cpu_up(unsigned int cpu, struct task_struct *idle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp_pv.c (ffffffff81029450)
Location: arch/x86/xen/smp_pv.c:341
Inline: False
```
**Symbols:**

```
ffffffff81029450-ffffffff810298ef: xen_pv_cpu_up (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int xen_pv_cpu_up(unsigned int cpu, struct task_struct *idle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp_pv.c (ffffffff81029670)
Location: arch/x86/xen/smp_pv.c:353
Inline: False
```
**Symbols:**

```
ffffffff81029670-ffffffff81029b04: xen_pv_cpu_up (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int xen_pv_cpu_up(unsigned int cpu, struct task_struct *idle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp_pv.c (ffffffff8102a0f0)
Location: arch/x86/xen/smp_pv.c:358
Inline: False
```
**Symbols:**

```
ffffffff8102a0f0-ffffffff8102a5ac: xen_pv_cpu_up (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int xen_pv_cpu_up(unsigned int cpu, struct task_struct *idle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp_pv.c (ffffffff8102a740)
Location: arch/x86/xen/smp_pv.c:360
Inline: False
```
**Symbols:**

```
ffffffff8102a740-ffffffff8102abed: xen_pv_cpu_up (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int xen_pv_cpu_up(unsigned int cpu, struct task_struct *idle);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp_pv.c (ffffffff8102c550)
Location: arch/x86/xen/smp_pv.c:362
Inline: True
```
**Symbols:**

```
ffffffff8102c550-ffffffff8102c9bd: xen_pv_cpu_up (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int xen_pv_cpu_up(unsigned int cpu, struct task_struct *idle);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp_pv.c (ffffffff8102ce20)
Location: arch/x86/xen/smp_pv.c:362
Inline: True
```
**Symbols:**

```
ffffffff8102ce20-ffffffff8102d28d: xen_pv_cpu_up (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int xen_pv_cpu_up(unsigned int cpu, struct task_struct *idle);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/smp_pv.c (ffffffff8102f230)
Location: arch/x86/xen/smp_pv.c:365
Inline: True
```
**Symbols:**

```
ffffffff8102f230-ffffffff8102f2dd: xen_pv_cpu_up.part.0 (STB_LOCAL)
ffffffff8102f2e0-ffffffff8102f30d: xen_pv_cpu_up (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int xen_pv_cpu_up(unsigned int cpu, struct task_struct *idle);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/smp_pv.c (ffffffff81030040)
Location: arch/x86/xen/smp_pv.c:346
Inline: True
```
**Symbols:**

```
ffffffff81030040-ffffffff810300ed: xen_pv_cpu_up.part.0 (STB_LOCAL)
ffffffff810300f0-ffffffff8103011d: xen_pv_cpu_up (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int xen_pv_cpu_up(unsigned int cpu, struct task_struct *idle);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp_pv.c (ffffffff81030b60)
Location: arch/x86/xen/smp_pv.c:346
Inline: True
```
**Symbols:**

```
ffffffff81030b60-ffffffff81030c1b: xen_pv_cpu_up (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int xen_pv_cpu_up(unsigned int cpu, struct task_struct *idle);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp_pv.c (ffffffff81035a90)
Location: arch/x86/xen/smp_pv.c:324
Inline: True
```
**Symbols:**

```
ffffffff81035a90-ffffffff81035b8c: xen_pv_cpu_up (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int xen_pv_cpu_up(unsigned int cpu, struct task_struct *idle);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp_pv.c (ffffffff8103b8a0)
Location: arch/x86/xen/smp_pv.c:319
Inline: True
```
**Symbols:**

```
ffffffff8103b8a0-ffffffff8103b9bd: xen_pv_cpu_up (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int xen_pv_cpu_up(unsigned int cpu, struct task_struct *idle);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp_pv.c (ffffffff81044080)
Location: arch/x86/xen/smp_pv.c:319
Inline: True
```
**Symbols:**

```
ffffffff81044080-ffffffff8104419d: xen_pv_cpu_up (STB_LOCAL)
```
</details>
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int xen_pv_cpu_up(unsigned int cpu, struct task_struct *idle);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp_pv.c (ffffffff8102cf80)
Location: arch/x86/xen/smp_pv.c:362
Inline: True
```
**Symbols:**

```
ffffffff8102cf80-ffffffff8102d3ed: xen_pv_cpu_up (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int xen_pv_cpu_up(unsigned int cpu, struct task_struct *idle);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp_pv.c (ffffffff8102cde0)
Location: arch/x86/xen/smp_pv.c:362
Inline: True
```
**Symbols:**

```
ffffffff8102cde0-ffffffff8102d24d: xen_pv_cpu_up (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int xen_pv_cpu_up(unsigned int cpu, struct task_struct *idle);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp_pv.c (ffffffff8102dbd0)
Location: arch/x86/xen/smp_pv.c:362
Inline: True
```
**Symbols:**

```
ffffffff8102dbd0-ffffffff8102e03d: xen_pv_cpu_up (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
