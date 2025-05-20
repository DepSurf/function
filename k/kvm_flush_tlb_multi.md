# Function: <code>kvm_flush_tlb_multi</code>

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
void kvm_flush_tlb_multi(const struct cpumask *cpumask, const struct flush_tlb_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff8107f450)
Location: arch/x86/kernel/kvm.c:575
Inline: False
```
**Symbols:**

```
ffffffff8107f450-ffffffff8107f4e1: kvm_flush_tlb_multi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void kvm_flush_tlb_multi(const struct cpumask *cpumask, const struct flush_tlb_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff8108e1b0)
Location: arch/x86/kernel/kvm.c:578
Inline: False
```
**Symbols:**

```
ffffffff8108e1b0-ffffffff8108e268: kvm_flush_tlb_multi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void kvm_flush_tlb_multi(const struct cpumask *cpumask, const struct flush_tlb_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff8109eb70)
Location: arch/x86/kernel/kvm.c:648
Inline: False
```
**Symbols:**

```
ffffffff8109eb70-ffffffff8109ec37: kvm_flush_tlb_multi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void kvm_flush_tlb_multi(const struct cpumask *cpumask, const struct flush_tlb_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff810b6a80)
Location: arch/x86/kernel/kvm.c:647
Inline: False
```
**Symbols:**

```
ffffffff810b6a80-ffffffff810b6b5e: kvm_flush_tlb_multi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void kvm_flush_tlb_multi(const struct cpumask *cpumask, const struct flush_tlb_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/kvm.c (0)
Location: arch/x86/kernel/kvm.c:647
Inline: False
```
**Symbols:**

```
ffffffff810b9bc0-ffffffff810b9cfe: kvm_flush_tlb_multi (STB_LOCAL)
ffffffff820d29df-ffffffff820d29f4: kvm_flush_tlb_multi.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void kvm_flush_tlb_multi(const struct cpumask *cpumask, const struct flush_tlb_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/kvm.c (0)
Location: arch/x86/kernel/kvm.c:648
Inline: False
```
**Symbols:**

```
ffffffff810c0e10-ffffffff810c0f4e: kvm_flush_tlb_multi (STB_LOCAL)
ffffffff821ad843-ffffffff821ad858: kvm_flush_tlb_multi.cold (STB_LOCAL)
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
