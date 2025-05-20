# Function: <code>hv_smp_prepare_cpus</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void hv_smp_prepare_cpus(unsigned int max_cpus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff831cf54e)
Location: arch/x86/kernel/cpu/mshyperv.c:226
Inline: False
```
**Symbols:**

```
ffffffff831cf54e-ffffffff831cf5f2: hv_smp_prepare_cpus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void hv_smp_prepare_cpus(unsigned int max_cpus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff832b193f)
Location: arch/x86/kernel/cpu/mshyperv.c:227
Inline: False
```
**Symbols:**

```
ffffffff832b193f-ffffffff832b1a14: hv_smp_prepare_cpus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void hv_smp_prepare_cpus(unsigned int max_cpus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff83462ba7)
Location: arch/x86/kernel/cpu/mshyperv.c:229
Inline: False
```
**Symbols:**

```
ffffffff83462ba7-ffffffff83462c7f: hv_smp_prepare_cpus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void hv_smp_prepare_cpus(unsigned int max_cpus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff83e85120)
Location: arch/x86/kernel/cpu/mshyperv.c:229
Inline: False
```
**Symbols:**

```
ffffffff83e85120-ffffffff83e8523b: hv_smp_prepare_cpus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void hv_smp_prepare_cpus(unsigned int max_cpus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff836a8660)
Location: arch/x86/kernel/cpu/mshyperv.c:289
Inline: False
```
**Symbols:**

```
ffffffff836a8660-ffffffff836a8775: hv_smp_prepare_cpus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void hv_smp_prepare_cpus(unsigned int max_cpus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff838d8be0)
Location: arch/x86/kernel/cpu/mshyperv.c:297
Inline: False
```
**Symbols:**

```
ffffffff838d8be0-ffffffff838d8d39: hv_smp_prepare_cpus (STB_LOCAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
