# Function: <code>kvm_cpu_online</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int kvm_cpu_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff81067250)
Location: arch/x86/kernel/kvm.c:432
Inline: False
```
**Symbols:**

```
ffffffff81067250-ffffffff81067270: kvm_cpu_online (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int kvm_cpu_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff81066560)
Location: arch/x86/kernel/kvm.c:439
Inline: False
```
**Symbols:**

```
ffffffff81066560-ffffffff81066580: kvm_cpu_online (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int kvm_cpu_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff8106a730)
Location: arch/x86/kernel/kvm.c:479
Inline: False
```
**Symbols:**

```
ffffffff8106a730-ffffffff8106a750: kvm_cpu_online (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int kvm_cpu_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff8106d380)
Location: arch/x86/kernel/kvm.c:486
Inline: False
```
**Symbols:**

```
ffffffff8106d380-ffffffff8106d3a0: kvm_cpu_online (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int kvm_cpu_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff81073550)
Location: arch/x86/kernel/kvm.c:572
Inline: False
```
**Symbols:**

```
ffffffff81073550-ffffffff81073570: kvm_cpu_online (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int kvm_cpu_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff810770c0)
Location: arch/x86/kernel/kvm.c:571
Inline: False
```
**Symbols:**

```
ffffffff810770c0-ffffffff810770e0: kvm_cpu_online (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int kvm_cpu_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff81078110)
Location: arch/x86/kernel/kvm.c:559
Inline: False
```
**Symbols:**

```
ffffffff81078110-ffffffff81078130: kvm_cpu_online (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int kvm_cpu_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff8107f420)
Location: arch/x86/kernel/kvm.c:583
Inline: False
```
**Symbols:**

```
ffffffff8107f420-ffffffff8107f440: kvm_cpu_online (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int kvm_cpu_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff8107f0f0)
Location: arch/x86/kernel/kvm.c:599
Inline: False
```
**Symbols:**

```
ffffffff8107f0f0-ffffffff8107f110: kvm_cpu_online (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int kvm_cpu_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff810802a1)
Location: arch/x86/kernel/kvm.c:442
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_resume
```
**Symbols:**

```
ffffffff81080250-ffffffff8108028c: kvm_cpu_online (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int kvm_cpu_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff8108f111)
Location: arch/x86/kernel/kvm.c:442
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_resume
```
**Symbols:**

```
ffffffff8108f0c0-ffffffff8108f0fc: kvm_cpu_online (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int kvm_cpu_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff8109fd80)
Location: arch/x86/kernel/kvm.c:461
Inline: False
```
**Symbols:**

```
ffffffff8109fd80-ffffffff8109fdb5: kvm_cpu_online (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int kvm_cpu_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff810b7720)
Location: arch/x86/kernel/kvm.c:460
Inline: False
```
**Symbols:**

```
ffffffff810b7720-ffffffff810b775d: kvm_cpu_online (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int kvm_cpu_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff810ba910)
Location: arch/x86/kernel/kvm.c:460
Inline: False
```
**Symbols:**

```
ffffffff810ba910-ffffffff810ba94d: kvm_cpu_online (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int kvm_cpu_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff810c1d50)
Location: arch/x86/kernel/kvm.c:461
Inline: False
```
**Symbols:**

```
ffffffff810c1d50-ffffffff810c1d8d: kvm_cpu_online (STB_LOCAL)
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
int kvm_cpu_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff81077110)
Location: arch/x86/kernel/kvm.c:559
Inline: False
```
**Symbols:**

```
ffffffff81077110-ffffffff81077130: kvm_cpu_online (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int kvm_cpu_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff81067250)
Location: arch/x86/kernel/kvm.c:559
Inline: False
```
**Symbols:**

```
ffffffff81067250-ffffffff81067264: kvm_cpu_online (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int kvm_cpu_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff810770c0)
Location: arch/x86/kernel/kvm.c:559
Inline: False
```
**Symbols:**

```
ffffffff810770c0-ffffffff810770e0: kvm_cpu_online (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int kvm_cpu_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff81079130)
Location: arch/x86/kernel/kvm.c:559
Inline: False
```
**Symbols:**

```
ffffffff81079130-ffffffff81079150: kvm_cpu_online (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
