# Function: <code>sh_mtu2_write</code>

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
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void sh_mtu2_write(struct sh_mtu2_channel *ch, int reg_nr, long unsigned int value);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clocksource/sh_mtu2.c (c0c45b34)
Location: drivers/clocksource/sh_mtu2.c:167
Inline: True
Inline callers:
  - drivers/clocksource/sh_mtu2.c:sh_mtu2_interrupt
  - drivers/clocksource/sh_mtu2.c:sh_mtu2_start_stop_ch
  - drivers/clocksource/sh_mtu2.c:sh_mtu2_start_stop_ch
Direct callers:
  - drivers/clocksource/sh_mtu2.c:sh_mtu2_clock_event_set_periodic
  - drivers/clocksource/sh_mtu2.c:sh_mtu2_clock_event_set_periodic
  - drivers/clocksource/sh_mtu2.c:sh_mtu2_clock_event_set_periodic
  - drivers/clocksource/sh_mtu2.c:sh_mtu2_clock_event_set_periodic
  - drivers/clocksource/sh_mtu2.c:sh_mtu2_clock_event_set_periodic
  - drivers/clocksource/sh_mtu2.c:sh_mtu2_clock_event_set_periodic
```
**Symbols:**

```
c0c4543c-c0c45490: sh_mtu2_write (STB_LOCAL)
```
</details>
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
<b>Arch</b>
<ul>
</ul>
