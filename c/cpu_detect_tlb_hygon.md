# Function: <code>cpu_detect_tlb_hygon</code>

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
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void cpu_detect_tlb_hygon(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/hygon.c (ffffffff81048140)
Location: arch/x86/kernel/cpu/hygon.c:366
Inline: True
```
**Symbols:**

```
ffffffff81048140-ffffffff81048288: cpu_detect_tlb_hygon (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void cpu_detect_tlb_hygon(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/hygon.c (ffffffff8104aee0)
Location: arch/x86/kernel/cpu/hygon.c:371
Inline: True
```
**Symbols:**

```
ffffffff8104aee0-ffffffff8104b028: cpu_detect_tlb_hygon (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void cpu_detect_tlb_hygon(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/hygon.c (ffffffff8104b8e0)
Location: arch/x86/kernel/cpu/hygon.c:356
Inline: True
```
**Symbols:**

```
ffffffff8104b8e0-ffffffff8104ba28: cpu_detect_tlb_hygon (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void cpu_detect_tlb_hygon(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/hygon.c (ffffffff81050070)
Location: arch/x86/kernel/cpu/hygon.c:356
Inline: True
```
**Symbols:**

```
ffffffff81050070-ffffffff810501a7: cpu_detect_tlb_hygon.part.0 (STB_LOCAL)
ffffffff810501b0-ffffffff810501ca: cpu_detect_tlb_hygon (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void cpu_detect_tlb_hygon(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/hygon.c (ffffffff8104f280)
Location: arch/x86/kernel/cpu/hygon.c:336
Inline: True
```
**Symbols:**

```
ffffffff8104f280-ffffffff8104f3b7: cpu_detect_tlb_hygon.part.0 (STB_LOCAL)
ffffffff8104f3c0-ffffffff8104f3da: cpu_detect_tlb_hygon (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void cpu_detect_tlb_hygon(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/hygon.c (ffffffff81051360)
Location: arch/x86/kernel/cpu/hygon.c:336
Inline: True
```
**Symbols:**

```
ffffffff81051360-ffffffff8105149f: cpu_detect_tlb_hygon (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void cpu_detect_tlb_hygon(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/hygon.c (ffffffff810598f0)
Location: arch/x86/kernel/cpu/hygon.c:342
Inline: True
```
**Symbols:**

```
ffffffff810598f0-ffffffff81059a2f: cpu_detect_tlb_hygon (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void cpu_detect_tlb_hygon(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/hygon.c (ffffffff81065fa0)
Location: arch/x86/kernel/cpu/hygon.c:348
Inline: False
```
**Symbols:**

```
ffffffff81065fa0-ffffffff81066112: cpu_detect_tlb_hygon (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void cpu_detect_tlb_hygon(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/hygon.c (ffffffff810752f0)
Location: arch/x86/kernel/cpu/hygon.c:348
Inline: False
```
**Symbols:**

```
ffffffff810752f0-ffffffff81075462: cpu_detect_tlb_hygon (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void cpu_detect_tlb_hygon(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/hygon.c (ffffffff81077460)
Location: arch/x86/kernel/cpu/hygon.c:348
Inline: False
```
**Symbols:**

```
ffffffff81077460-ffffffff810775d4: cpu_detect_tlb_hygon (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void cpu_detect_tlb_hygon(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/hygon.c (ffffffff8107e9e0)
Location: arch/x86/kernel/cpu/hygon.c:362
Inline: False
```
**Symbols:**

```
ffffffff8107e9e0-ffffffff8107eb54: cpu_detect_tlb_hygon (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void cpu_detect_tlb_hygon(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/hygon.c (ffffffff8104ba50)
Location: arch/x86/kernel/cpu/hygon.c:356
Inline: True
```
**Symbols:**

```
ffffffff8104ba50-ffffffff8104bb98: cpu_detect_tlb_hygon (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void cpu_detect_tlb_hygon(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/hygon.c (ffffffff8103ad10)
Location: arch/x86/kernel/cpu/hygon.c:356
Inline: True
```
**Symbols:**

```
ffffffff8103ad10-ffffffff8103adc5: cpu_detect_tlb_hygon (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void cpu_detect_tlb_hygon(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/hygon.c (ffffffff8104b890)
Location: arch/x86/kernel/cpu/hygon.c:356
Inline: True
```
**Symbols:**

```
ffffffff8104b890-ffffffff8104b9d8: cpu_detect_tlb_hygon (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void cpu_detect_tlb_hygon(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/hygon.c (ffffffff8104cca0)
Location: arch/x86/kernel/cpu/hygon.c:356
Inline: True
```
**Symbols:**

```
ffffffff8104cca0-ffffffff8104cde8: cpu_detect_tlb_hygon (STB_LOCAL)
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
