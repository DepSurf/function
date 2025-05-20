# Function: <code>pv_ipi_supported</code>

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
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff82ce2feb)
Location: arch/x86/kernel/kvm.c:444
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_alloc_cpumask
  - arch/x86/kernel/kvm.c:kvm_apic_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff82fd02dd)
Location: arch/x86/kernel/kvm.c:465
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_alloc_cpumask
  - arch/x86/kernel/kvm.c:kvm_apic_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff831dad59)
Location: arch/x86/kernel/kvm.c:463
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_apic_init
  - arch/x86/kernel/kvm.c:kvm_alloc_cpumask
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool pv_ipi_supported();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff81c9f142)
Location: arch/x86/kernel/kvm.c:464
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_apic_init
  - arch/x86/kernel/kvm.c:kvm_alloc_cpumask
```
**Symbols:**

```
ffffffff81c9f142-ffffffff81c9f172: pv_ipi_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool pv_ipi_supported();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff81e4e899)
Location: arch/x86/kernel/kvm.c:484
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_apic_init
  - arch/x86/kernel/kvm.c:kvm_alloc_cpumask
```
**Symbols:**

```
ffffffff81e4e899-ffffffff81e4e8ca: pv_ipi_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff83e96925)
Location: arch/x86/kernel/kvm.c:483
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_apic_init
  - arch/x86/kernel/kvm.c:kvm_alloc_cpumask
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff836ba4d5)
Location: arch/x86/kernel/kvm.c:483
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_apic_init
  - arch/x86/kernel/kvm.c:kvm_alloc_cpumask
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff838eae45)
Location: arch/x86/kernel/kvm.c:484
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_apic_init
  - arch/x86/kernel/kvm.c:kvm_alloc_cpumask
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
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
</ul>
