# Function: <code>mpic_processor_id</code>

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
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/sysdev/mpic.c (c0000000000b6b64)
Location: arch/powerpc/sysdev/mpic.c:158
Inline: True
Inline callers:
  - arch/powerpc/sysdev/mpic.c:smp_mpic_message_pass
  - arch/powerpc/sysdev/mpic.c:_mpic_get_one_irq
  - arch/powerpc/sysdev/mpic.c:_mpic_get_one_irq
  - arch/powerpc/sysdev/mpic.c:_mpic_get_one_irq
  - arch/powerpc/sysdev/mpic.c:mpic_teardown_this_cpu
  - arch/powerpc/sysdev/mpic.c:mpic_teardown_this_cpu
  - arch/powerpc/sysdev/mpic.c:mpic_cpu_set_priority
  - arch/powerpc/sysdev/mpic.c:mpic_cpu_get_priority
  - arch/powerpc/sysdev/mpic.c:mpic_setup_this_cpu
  - arch/powerpc/sysdev/mpic.c:mpic_init
  - arch/powerpc/sysdev/mpic.c:mpic_host_map
  - arch/powerpc/sysdev/mpic.c:mpic_end_ipi
  - arch/powerpc/sysdev/mpic.c:mpic_end_irq
```
</details>
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
