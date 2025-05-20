# Function: <code>vmware_cpu_online</code>

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
int vmware_cpu_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/vmware.c (ffffffff81067810)
Location: arch/x86/kernel/cpu/vmware.c:298
Inline: False
```
**Symbols:**

```
ffffffff81067810-ffffffff8106783b: vmware_cpu_online (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int vmware_cpu_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/vmware.c (ffffffff810695d0)
Location: arch/x86/kernel/cpu/vmware.c:299
Inline: False
```
**Symbols:**

```
ffffffff810695d0-ffffffff810695fb: vmware_cpu_online (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int vmware_cpu_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/vmware.c (ffffffff8106a060)
Location: arch/x86/kernel/cpu/vmware.c:300
Inline: False
```
**Symbols:**

```
ffffffff8106a060-ffffffff8106a08b: vmware_cpu_online (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int vmware_cpu_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/vmware.c (ffffffff81074840)
Location: arch/x86/kernel/cpu/vmware.c:300
Inline: False
```
**Symbols:**

```
ffffffff81074840-ffffffff81074860: vmware_cpu_online (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int vmware_cpu_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/vmware.c (ffffffff81082f20)
Location: arch/x86/kernel/cpu/vmware.c:300
Inline: False
```
**Symbols:**

```
ffffffff81082f20-ffffffff81082f42: vmware_cpu_online (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int vmware_cpu_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/vmware.c (ffffffff81095a50)
Location: arch/x86/kernel/cpu/vmware.c:300
Inline: False
```
**Symbols:**

```
ffffffff81095a50-ffffffff81095a7a: vmware_cpu_online (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int vmware_cpu_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/vmware.c (ffffffff81098a90)
Location: arch/x86/kernel/cpu/vmware.c:300
Inline: False
```
**Symbols:**

```
ffffffff81098a90-ffffffff81098aba: vmware_cpu_online (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int vmware_cpu_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/vmware.c (ffffffff810a0030)
Location: arch/x86/kernel/cpu/vmware.c:300
Inline: False
```
**Symbols:**

```
ffffffff810a0030-ffffffff810a005a: vmware_cpu_online (STB_LOCAL)
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
