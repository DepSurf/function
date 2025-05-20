# Function: <code>vclocks_set_used</code>

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
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff81020340)
Location: arch/x86/include/asm/clocksource.h:16
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_cs_enable
```
```
In arch/x86/kernel/tsc.c (ffffffff8103e680)
Location: arch/x86/include/asm/clocksource.h:16
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_cs_enable
```
```
In arch/x86/kernel/kvmclock.c (ffffffff8107f5e0)
Location: arch/x86/include/asm/clocksource.h:16
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvm_cs_enable
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff819c2e65)
Location: arch/x86/include/asm/clocksource.h:16
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_cs_enable
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff81020d70)
Location: arch/x86/include/asm/clocksource.h:16
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_cs_enable
```
```
In arch/x86/kernel/tsc.c (ffffffff8103e730)
Location: arch/x86/include/asm/clocksource.h:16
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_cs_enable
```
```
In arch/x86/kernel/kvmclock.c (ffffffff8107f240)
Location: arch/x86/include/asm/clocksource.h:16
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvm_cs_enable
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff819c3255)
Location: arch/x86/include/asm/clocksource.h:16
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_cs_enable
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff81023110)
Location: arch/x86/include/asm/clocksource.h:16
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_cs_enable
```
```
In arch/x86/kernel/tsc.c (ffffffff81040100)
Location: arch/x86/include/asm/clocksource.h:16
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_cs_enable
```
```
In arch/x86/kernel/kvmclock.c (ffffffff810803a0)
Location: arch/x86/include/asm/clocksource.h:16
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvm_cs_enable
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff819a76c5)
Location: arch/x86/include/asm/clocksource.h:16
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_cs_enable
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff81027280)
Location: arch/x86/include/asm/clocksource.h:16
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_cs_enable
```
```
In arch/x86/kernel/tsc.c (ffffffff81046120)
Location: arch/x86/include/asm/clocksource.h:16
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_cs_enable
```
```
In arch/x86/kernel/kvmclock.c (ffffffff8108f230)
Location: arch/x86/include/asm/clocksource.h:16
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvm_cs_enable
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff81a54bc5)
Location: arch/x86/include/asm/clocksource.h:16
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_cs_enable
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff8102b450)
Location: arch/x86/include/asm/clocksource.h:16
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_cs_enable
```
```
In arch/x86/kernel/tsc.c (ffffffff8104ed40)
Location: arch/x86/include/asm/clocksource.h:16
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_cs_enable
```
```
In arch/x86/kernel/kvmclock.c (ffffffff8109ff20)
Location: arch/x86/include/asm/clocksource.h:16
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvm_cs_enable
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff81bc41d5)
Location: arch/x86/include/asm/clocksource.h:16
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_cs_enable
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff810321b0)
Location: arch/x86/include/asm/clocksource.h:16
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_cs_enable
```
```
In arch/x86/kernel/tsc.c (ffffffff8105bca0)
Location: arch/x86/include/asm/clocksource.h:16
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_cs_enable
```
```
In arch/x86/kernel/kvmclock.c (ffffffff810b7930)
Location: arch/x86/include/asm/clocksource.h:16
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvm_cs_enable
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff81d69935)
Location: arch/x86/include/asm/clocksource.h:16
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_cs_enable
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff810321b0)
Location: arch/x86/include/asm/clocksource.h:16
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_cs_enable
```
```
In arch/x86/kernel/tsc.c (ffffffff8105d1d0)
Location: arch/x86/include/asm/clocksource.h:16
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_cs_enable
```
```
In arch/x86/kernel/kvmclock.c (ffffffff810bab20)
Location: arch/x86/include/asm/clocksource.h:16
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvm_cs_enable
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff81dd4f25)
Location: arch/x86/include/asm/clocksource.h:16
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_cs_enable
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff810384a0)
Location: arch/x86/include/asm/clocksource.h:16
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_cs_enable
```
```
In arch/x86/kernel/tsc.c (ffffffff81064290)
Location: arch/x86/include/asm/clocksource.h:16
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_cs_enable
```
```
In arch/x86/kernel/kvmclock.c (ffffffff810c1f60)
Location: arch/x86/include/asm/clocksource.h:16
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvm_cs_enable
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff81e8d075)
Location: arch/x86/include/asm/clocksource.h:16
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_cs_enable
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
