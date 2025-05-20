# Function: <code>hypervisor_pin_vcpu</code>

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
void hypervisor_pin_vcpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/hypervisor.c (ffffffff81051ac0)
Location: arch/x86/kernel/cpu/hypervisor.c:90
Inline: False
Direct callers:
  - kernel/smp.c:smp_call_on_cpu_callback
  - kernel/smp.c:smp_call_on_cpu_callback
```
**Symbols:**

```
ffffffff81051ac0-ffffffff81051b0e: hypervisor_pin_vcpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void hypervisor_pin_vcpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/hypervisor.c (ffffffff810515b0)
Location: arch/x86/kernel/cpu/hypervisor.c:85
Inline: False
Direct callers:
  - kernel/smp.c:smp_call_on_cpu_callback
  - kernel/smp.c:smp_call_on_cpu_callback
```
**Symbols:**

```
ffffffff810515b0-ffffffff810515f4: hypervisor_pin_vcpu (STB_GLOBAL)
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
In kernel/smp.c (ffffffff8111f2e4)
Location: include/linux/hypervisor.h:12
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_on_cpu_callback
  - kernel/smp.c:smp_call_on_cpu_callback
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
In kernel/smp.c (ffffffff8112c614)
Location: include/linux/hypervisor.h:15
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_on_cpu_callback
  - kernel/smp.c:smp_call_on_cpu_callback
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
In kernel/smp.c (ffffffff81137ee4)
Location: include/linux/hypervisor.h:15
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_on_cpu_callback
  - kernel/smp.c:smp_call_on_cpu_callback
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
In kernel/smp.c (ffffffff81143074)
Location: include/linux/hypervisor.h:15
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_on_cpu_callback
  - kernel/smp.c:smp_call_on_cpu_callback
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
In kernel/smp.c (ffffffff8114ebb4)
Location: include/linux/hypervisor.h:15
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_on_cpu_callback
  - kernel/smp.c:smp_call_on_cpu_callback
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff8115f214)
Location: include/linux/hypervisor.h:15
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_on_cpu_callback
  - kernel/smp.c:smp_call_on_cpu_callback
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
In kernel/smp.c (ffffffff8115b1b4)
Location: include/linux/hypervisor.h:15
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_on_cpu_callback
  - kernel/smp.c:smp_call_on_cpu_callback
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
In kernel/smp.c (ffffffff8115c544)
Location: include/linux/hypervisor.h:15
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_on_cpu_callback
  - kernel/smp.c:smp_call_on_cpu_callback
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
In kernel/smp.c (ffffffff811814c4)
Location: include/linux/hypervisor.h:15
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_on_cpu_callback
  - kernel/smp.c:smp_call_on_cpu_callback
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
In kernel/smp.c (ffffffff811b7a44)
Location: include/linux/hypervisor.h:15
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_on_cpu_callback
  - kernel/smp.c:smp_call_on_cpu_callback
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
In kernel/smp.c (ffffffff811f8c74)
Location: include/linux/hypervisor.h:15
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_on_cpu_callback
  - kernel/smp.c:smp_call_on_cpu_callback
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
In kernel/smp.c (ffffffff8120db04)
Location: include/linux/hypervisor.h:15
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_on_cpu_callback
  - kernel/smp.c:smp_call_on_cpu_callback
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
In kernel/smp.c (ffffffff81225294)
Location: include/linux/hypervisor.h:15
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_on_cpu_callback
  - kernel/smp.c:smp_call_on_cpu_callback
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/smp.c (0)
Location: include/linux/hypervisor.h:24
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/smp.c (0)
Location: include/linux/hypervisor.h:24
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/smp.c (0)
Location: include/linux/hypervisor.h:24
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/smp.c (0)
Location: include/linux/hypervisor.h:24
Inline: True
```
</details>
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
In kernel/smp.c (ffffffff811471d4)
Location: include/linux/hypervisor.h:15
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_on_cpu_callback
  - kernel/smp.c:smp_call_on_cpu_callback
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
In kernel/smp.c (ffffffff8113a4b4)
Location: include/linux/hypervisor.h:15
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_on_cpu_callback
  - kernel/smp.c:smp_call_on_cpu_callback
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
In kernel/smp.c (ffffffff81145084)
Location: include/linux/hypervisor.h:15
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_on_cpu_callback
  - kernel/smp.c:smp_call_on_cpu_callback
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
In kernel/smp.c (ffffffff81151c64)
Location: include/linux/hypervisor.h:15
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_on_cpu_callback
  - kernel/smp.c:smp_call_on_cpu_callback
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
</ul>
