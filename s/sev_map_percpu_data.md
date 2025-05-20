# Function: <code>sev_map_percpu_data</code>

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
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff826bf999)
Location: arch/x86/kernel/kvm.c:442
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu
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
In arch/x86/kernel/kvm.c (ffffffff826e97a1)
Location: arch/x86/kernel/kvm.c:442
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu
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
In arch/x86/kernel/kvm.c (ffffffff828a03ef)
Location: arch/x86/kernel/kvm.c:433
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu
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
In arch/x86/kernel/kvm.c (ffffffff828b85c2)
Location: arch/x86/kernel/kvm.c:417
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu
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
In arch/x86/kernel/kvm.c (ffffffff828bea9d)
Location: arch/x86/kernel/kvm.c:417
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void sev_map_percpu_data();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff82ce2c8b)
Location: arch/x86/kernel/kvm.c:419
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu
```
**Symbols:**

```
ffffffff82ce2c8b-ffffffff82ce2d21: sev_map_percpu_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void sev_map_percpu_data();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff82fcff28)
Location: arch/x86/kernel/kvm.c:440
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu
```
**Symbols:**

```
ffffffff82fcff28-ffffffff82fcffbe: sev_map_percpu_data (STB_LOCAL)
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
In arch/x86/kernel/kvm.c (ffffffff831dada8)
Location: arch/x86/kernel/kvm.c:417
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff832be057)
Location: arch/x86/kernel/kvm.c:417
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff8346fc13)
Location: arch/x86/kernel/kvm.c:434
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu
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
In arch/x86/kernel/kvm.c (ffffffff83e96495)
Location: arch/x86/kernel/kvm.c:433
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu
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
In arch/x86/kernel/kvm.c (ffffffff836ba015)
Location: arch/x86/kernel/kvm.c:433
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu
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
In arch/x86/kernel/kvm.c (ffffffff838ea945)
Location: arch/x86/kernel/kvm.c:433
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu
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
In arch/x86/kernel/kvm.c (ffffffff828a9a73)
Location: arch/x86/kernel/kvm.c:417
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu
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
In arch/x86/kernel/kvm.c (ffffffff828a1f6a)
Location: arch/x86/kernel/kvm.c:417
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu
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
In arch/x86/kernel/kvm.c (ffffffff828bc972)
Location: arch/x86/kernel/kvm.c:417
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu
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
In arch/x86/kernel/kvm.c (ffffffff828bfaca)
Location: arch/x86/kernel/kvm.c:417
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu
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
</ul>
