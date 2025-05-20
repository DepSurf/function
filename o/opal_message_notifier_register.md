# Function: <code>opal_message_notifier_register</code>

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
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int opal_message_notifier_register(enum opal_msg_type msg_type, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/powerpc/platforms/powernv/opal.c (c0000000000c5690)
Location: arch/powerpc/platforms/powernv/opal.c:244
Inline: True
Direct callers:
  - arch/powerpc/platforms/powernv/opal-async.c:opal_async_comp_init
  - arch/powerpc/platforms/powernv/opal-hmi.c:opal_hmi_handler_init
  - arch/powerpc/platforms/powernv/opal-power.c:opal_power_control_init
  - arch/powerpc/platforms/powernv/opal-power.c:opal_power_control_init
  - arch/powerpc/platforms/powernv/opal-power.c:opal_power_control_init
  - arch/powerpc/platforms/powernv/opal-memory-errors.c:__machine_initcall_powernv_opal_mem_err_init
  - drivers/cpufreq/powernv-cpufreq.c:powernv_cpufreq_init
```
**Symbols:**

```
c0000000000c5690-c0000000000c5708: opal_message_notifier_register (STB_GLOBAL)
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
<b>Arch</b>
<ul>
</ul>
