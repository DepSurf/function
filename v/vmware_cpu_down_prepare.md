# Function: <code>vmware_cpu_down_prepare</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int vmware_cpu_down_prepare(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/vmware.c (ffffffff81067780)
Location: arch/x86/kernel/cpu/vmware.c:306
Inline: False
```
**Symbols:**

```
ffffffff81067780-ffffffff810677b0: vmware_cpu_down_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int vmware_cpu_down_prepare(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/vmware.c (ffffffff81069540)
Location: arch/x86/kernel/cpu/vmware.c:307
Inline: False
```
**Symbols:**

```
ffffffff81069540-ffffffff81069570: vmware_cpu_down_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int vmware_cpu_down_prepare(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/vmware.c (ffffffff81069fc0)
Location: arch/x86/kernel/cpu/vmware.c:308
Inline: False
```
**Symbols:**

```
ffffffff81069fc0-ffffffff81069ff0: vmware_cpu_down_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int vmware_cpu_down_prepare(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/vmware.c (0)
Location: arch/x86/kernel/cpu/vmware.c:308
Inline: False
```
**Symbols:**

```
ffffffff81074860-ffffffff810748a1: vmware_cpu_down_prepare (STB_LOCAL)
ffffffff81c9cfb6-ffffffff81c9cfca: vmware_cpu_down_prepare.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int vmware_cpu_down_prepare(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/vmware.c (0)
Location: arch/x86/kernel/cpu/vmware.c:308
Inline: False
```
**Symbols:**

```
ffffffff81082fa0-ffffffff81082fe7: vmware_cpu_down_prepare (STB_LOCAL)
ffffffff81e4c2d2-ffffffff81e4c2e6: vmware_cpu_down_prepare.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int vmware_cpu_down_prepare(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/vmware.c (0)
Location: arch/x86/kernel/cpu/vmware.c:308
Inline: False
```
**Symbols:**

```
ffffffff81095af0-ffffffff81095b3b: vmware_cpu_down_prepare (STB_LOCAL)
ffffffff82053944-ffffffff82053958: vmware_cpu_down_prepare.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int vmware_cpu_down_prepare(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/vmware.c (0)
Location: arch/x86/kernel/cpu/vmware.c:308
Inline: False
```
**Symbols:**

```
ffffffff81098b30-ffffffff81098b7b: vmware_cpu_down_prepare (STB_LOCAL)
ffffffff820d1f5c-ffffffff820d1f70: vmware_cpu_down_prepare.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int vmware_cpu_down_prepare(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/vmware.c (0)
Location: arch/x86/kernel/cpu/vmware.c:308
Inline: False
```
**Symbols:**

```
ffffffff810a00d0-ffffffff810a011b: vmware_cpu_down_prepare (STB_LOCAL)
ffffffff821acbc0-ffffffff821acbd4: vmware_cpu_down_prepare.cold (STB_LOCAL)
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
