# Function: <code>ip_within_syscall_gap</code>

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
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff81c351f2)
Location: arch/x86/include/asm/ptrace.h:181
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:vc_switch_off_ist
```
```
In arch/x86/kernel/sev-es.c (ffffffff81c38228)
Location: arch/x86/include/asm/ptrace.h:181
Inline: True
Inline callers:
  - arch/x86/kernel/sev-es.c:__sev_es_ist_enter
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
In arch/x86/kernel/traps.c (ffffffff81c27682)
Location: arch/x86/include/asm/ptrace.h:184
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:vc_switch_off_ist
```
```
In arch/x86/kernel/sev.c (ffffffff81c2a6ef)
Location: arch/x86/include/asm/ptrace.h:184
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:__sev_es_ist_enter
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
In arch/x86/kernel/traps.c (ffffffff81d456d2)
Location: arch/x86/include/asm/ptrace.h:184
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:vc_switch_off_ist
```
```
In arch/x86/kernel/sev.c (ffffffff81d48cdf)
Location: arch/x86/include/asm/ptrace.h:184
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:__sev_es_ist_enter
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
In arch/x86/kernel/traps.c (ffffffff81f138e4)
Location: arch/x86/include/asm/ptrace.h:184
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:vc_switch_off_ist
```
```
In arch/x86/kernel/sev.c (ffffffff81f17ff8)
Location: arch/x86/include/asm/ptrace.h:184
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:__sev_es_ist_enter
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
In arch/x86/kernel/traps.c (ffffffff820baac4)
Location: arch/x86/include/asm/ptrace.h:184
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:vc_switch_off_ist
```
```
In arch/x86/kernel/sev.c (ffffffff820bf7b8)
Location: arch/x86/include/asm/ptrace.h:184
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:__sev_es_ist_enter
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
In arch/x86/kernel/traps.c (ffffffff8213c1e4)
Location: arch/x86/include/asm/ptrace.h:184
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:vc_switch_off_ist
```
```
In arch/x86/kernel/sev.c (ffffffff821414b8)
Location: arch/x86/include/asm/ptrace.h:184
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:__sev_es_ist_enter
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
In arch/x86/kernel/traps.c (ffffffff8221e1e4)
Location: arch/x86/include/asm/ptrace.h:184
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:vc_switch_off_ist
```
```
In arch/x86/kernel/sev.c (ffffffff822233c8)
Location: arch/x86/include/asm/ptrace.h:184
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:__sev_es_ist_enter
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
