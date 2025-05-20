# Function: <code>arch_trigger_all_cpu_backtrace</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void arch_trigger_all_cpu_backtrace(bool include_self);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/hw_nmi.c (ffffffff81055ce0)
Location: arch/x86/kernel/apic/hw_nmi.c:36
Inline: False
Direct callers:
  - kernel/hung_task.c:watchdog
  - kernel/watchdog.c:watchdog_timer_fn
  - drivers/tty/sysrq.c:sysrq_handle_showallcpus
```
**Symbols:**

```
ffffffff81055ce0-ffffffff81055cfb: arch_trigger_all_cpu_backtrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void arch_trigger_all_cpu_backtrace(bool include_self);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/hw_nmi.c (ffffffff81055f20)
Location: arch/x86/kernel/apic/hw_nmi.c:35
Inline: False
Direct callers:
  - kernel/hung_task.c:watchdog
  - kernel/watchdog.c:watchdog_timer_fn
  - drivers/tty/sysrq.c:sysrq_handle_showallcpus
```
**Symbols:**

```
ffffffff81055f20-ffffffff81055f3b: arch_trigger_all_cpu_backtrace (STB_GLOBAL)
```
</details>
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
</ul>
