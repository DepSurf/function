# Function: <code>kvm_flush_tlb_others</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void kvm_flush_tlb_others(const struct cpumask *cpumask, const struct flush_tlb_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff8106c9d0)
Location: arch/x86/kernel/kvm.c:510
Inline: False
```
**Symbols:**

```
ffffffff8106c9d0-ffffffff8106ca63: kvm_flush_tlb_others (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void kvm_flush_tlb_others(const struct cpumask *cpumask, const struct flush_tlb_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff81072880)
Location: arch/x86/kernel/kvm.c:596
Inline: False
```
**Symbols:**

```
ffffffff81072880-ffffffff81072913: kvm_flush_tlb_others (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void kvm_flush_tlb_others(const struct cpumask *cpumask, const struct flush_tlb_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff810763b0)
Location: arch/x86/kernel/kvm.c:595
Inline: False
```
**Symbols:**

```
ffffffff810763b0-ffffffff81076441: kvm_flush_tlb_others (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void kvm_flush_tlb_others(const struct cpumask *cpumask, const struct flush_tlb_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff810773c0)
Location: arch/x86/kernel/kvm.c:583
Inline: False
```
**Symbols:**

```
ffffffff810773c0-ffffffff81077451: kvm_flush_tlb_others (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void kvm_flush_tlb_others(const struct cpumask *cpumask, const struct flush_tlb_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff8107e710)
Location: arch/x86/kernel/kvm.c:600
Inline: False
```
**Symbols:**

```
ffffffff8107e710-ffffffff8107e7a1: kvm_flush_tlb_others (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void kvm_flush_tlb_others(const struct cpumask *cpumask, const struct flush_tlb_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff8107e340)
Location: arch/x86/kernel/kvm.c:616
Inline: False
```
**Symbols:**

```
ffffffff8107e340-ffffffff8107e3d1: kvm_flush_tlb_others (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
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
<summary>In <code>aws</code>: ✅</summary>

```c
void kvm_flush_tlb_others(const struct cpumask *cpumask, const struct flush_tlb_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff810763c0)
Location: arch/x86/kernel/kvm.c:583
Inline: False
```
**Symbols:**

```
ffffffff810763c0-ffffffff81076451: kvm_flush_tlb_others (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void kvm_flush_tlb_others(const struct cpumask *cpumask, const struct flush_tlb_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff81066330)
Location: arch/x86/kernel/kvm.c:583
Inline: False
```
**Symbols:**

```
ffffffff81066330-ffffffff810663c1: kvm_flush_tlb_others (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void kvm_flush_tlb_others(const struct cpumask *cpumask, const struct flush_tlb_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff81076370)
Location: arch/x86/kernel/kvm.c:583
Inline: False
```
**Symbols:**

```
ffffffff81076370-ffffffff81076401: kvm_flush_tlb_others (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void kvm_flush_tlb_others(const struct cpumask *cpumask, const struct flush_tlb_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff810783c0)
Location: arch/x86/kernel/kvm.c:583
Inline: False
```
**Symbols:**

```
ffffffff810783c0-ffffffff81078451: kvm_flush_tlb_others (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
