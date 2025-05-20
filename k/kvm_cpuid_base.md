# Function: <code>kvm_cpuid_base</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff81063d85)
Location: arch/x86/kernel/kvm.c:530
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_detect
  - arch/x86/kernel/kvm.c:kvm_arch_para_features
  - arch/x86/kernel/kvm.c:kvm_guest_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff81f9cc62)
Location: arch/x86/kernel/kvm.c:521
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_detect
  - arch/x86/kernel/kvm.c:kvm_arch_para_features
  - arch/x86/kernel/kvm.c:kvm_guest_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff81fd81b5)
Location: arch/x86/kernel/kvm.c:507
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_detect
  - arch/x86/kernel/kvm.c:kvm_arch_para_features
  - arch/x86/kernel/kvm.c:kvm_guest_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff820b9004)
Location: arch/x86/kernel/kvm.c:514
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_detect
  - arch/x86/kernel/kvm.c:kvm_arch_para_features
  - arch/x86/kernel/kvm.c:kvm_guest_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff826bf8ea)
Location: arch/x86/kernel/kvm.c:555
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_detect
  - arch/x86/kernel/kvm.c:kvm_arch_para_features
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff826e96f6)
Location: arch/x86/kernel/kvm.c:596
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_detect
  - arch/x86/kernel/kvm.c:kvm_arch_para_hints
  - arch/x86/kernel/kvm.c:kvm_arch_para_features
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_spinlock_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff828a02e6)
Location: arch/x86/kernel/kvm.c:681
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_detect
  - arch/x86/kernel/kvm.c:kvm_arch_para_hints
  - arch/x86/kernel/kvm.c:kvm_arch_para_features
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_spinlock_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff828b84e3)
Location: arch/x86/kernel/kvm.c:683
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_detect
  - arch/x86/kernel/kvm.c:kvm_arch_para_hints
  - arch/x86/kernel/kvm.c:kvm_arch_para_features
  - arch/x86/kernel/kvm.c:kvm_para_available
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff828bea06)
Location: arch/x86/kernel/kvm.c:671
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_detect
  - arch/x86/kernel/kvm.c:kvm_arch_para_hints
  - arch/x86/kernel/kvm.c:kvm_arch_para_features
  - arch/x86/kernel/kvm.c:kvm_para_available
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
uint32_t kvm_cpuid_base();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff8107ea40)
Location: arch/x86/kernel/kvm.c:686
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_arch_para_hints
  - arch/x86/kernel/kvm.c:kvm_arch_para_features
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_alloc_cpumask
  - arch/x86/kernel/kvm.c:kvm_detect
```
**Symbols:**

```
ffffffff8107ea40-ffffffff8107ea5d: kvm_cpuid_base (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
uint32_t kvm_cpuid_base();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff8107e670)
Location: arch/x86/kernel/kvm.c:703
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_arch_para_hints
  - arch/x86/kernel/kvm.c:kvm_arch_para_features
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_alloc_cpumask
  - arch/x86/kernel/kvm.c:kvm_detect
```
**Symbols:**

```
ffffffff8107e670-ffffffff8107e68d: kvm_cpuid_base (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
uint32_t kvm_cpuid_base();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff8107f6e0)
Location: arch/x86/kernel/kvm.c:763
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_arch_para_hints
  - arch/x86/kernel/kvm.c:kvm_arch_para_features
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_detect
  - arch/x86/kernel/kvm.c:kvm_alloc_cpumask
```
**Symbols:**

```
ffffffff8107f6e0-ffffffff8107f6fd: kvm_cpuid_base (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
uint32_t kvm_cpuid_base();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff8108e4a0)
Location: arch/x86/kernel/kvm.c:766
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_arch_para_hints
  - arch/x86/kernel/kvm.c:kvm_arch_para_features
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_detect
  - arch/x86/kernel/kvm.c:kvm_alloc_cpumask
```
**Symbols:**

```
ffffffff8108e4a0-ffffffff8108e4bd: kvm_cpuid_base (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
uint32_t kvm_cpuid_base();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff8109eed0)
Location: arch/x86/kernel/kvm.c:887
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_arch_para_hints
  - arch/x86/kernel/kvm.c:kvm_arch_para_features
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_detect
  - arch/x86/kernel/kvm.c:kvm_alloc_cpumask
```
**Symbols:**

```
ffffffff8109eed0-ffffffff8109eef5: kvm_cpuid_base (STB_LOCAL)
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
In arch/x86/kernel/kvm.c (ffffffff83e95fa5)
Location: arch/x86/kernel/kvm.c:880
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_detect
  - arch/x86/kernel/kvm.c:kvm_arch_para_hints
  - arch/x86/kernel/kvm.c:kvm_arch_para_features
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
In arch/x86/kernel/kvm.c (ffffffff836b9b25)
Location: arch/x86/kernel/kvm.c:880
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_detect
  - arch/x86/kernel/kvm.c:kvm_arch_para_hints
  - arch/x86/kernel/kvm.c:kvm_arch_para_features
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
In arch/x86/kernel/kvm.c (ffffffff838ea455)
Location: arch/x86/kernel/kvm.c:881
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_detect
  - arch/x86/kernel/kvm.c:kvm_arch_para_hints
  - arch/x86/kernel/kvm.c:kvm_arch_para_features
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
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff828a99dc)
Location: arch/x86/kernel/kvm.c:671
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_detect
  - arch/x86/kernel/kvm.c:kvm_arch_para_hints
  - arch/x86/kernel/kvm.c:kvm_arch_para_features
  - arch/x86/kernel/kvm.c:kvm_para_available
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff828a1db5)
Location: arch/x86/kernel/kvm.c:671
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_setup_pv_tlb_flush
  - arch/x86/kernel/kvm.c:kvm_setup_pv_tlb_flush
  - arch/x86/kernel/kvm.c:kvm_setup_pv_tlb_flush
  - arch/x86/kernel/kvm.c:kvm_apic_init
  - arch/x86/kernel/kvm.c:kvm_detect
  - arch/x86/kernel/kvm.c:kvm_para_available
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_cpu_down_prepare
  - arch/x86/kernel/kvm.c:kvm_smp_prepare_cpus
  - arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_init
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_init
  - arch/x86/kernel/kvm.c:kvm_guest_cpu_init
  - arch/x86/kernel/kvm.c:kvm_spinlock_init
  - arch/x86/kernel/kvm.c:kvm_spinlock_init
  - arch/x86/kernel/kvm.c:kvm_spinlock_init
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff828bc8db)
Location: arch/x86/kernel/kvm.c:671
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_detect
  - arch/x86/kernel/kvm.c:kvm_arch_para_hints
  - arch/x86/kernel/kvm.c:kvm_arch_para_features
  - arch/x86/kernel/kvm.c:kvm_para_available
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff828bfa33)
Location: arch/x86/kernel/kvm.c:671
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_detect
  - arch/x86/kernel/kvm.c:kvm_arch_para_hints
  - arch/x86/kernel/kvm.c:kvm_arch_para_features
  - arch/x86/kernel/kvm.c:kvm_para_available
```
</details>
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
</ul>
