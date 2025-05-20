# Function: <code>opal_poll_events</code>

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
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int64_t opal_poll_events(int64_t a0, int64_t a1, int64_t a2, int64_t a3, int64_t a4, int64_t a5, int64_t a6, int64_t a7);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/platforms/powernv/opal-call.c (c0000000000c28b0)
Location: arch/powerpc/platforms/powernv/opal-call.c:143
Inline: False
Direct callers:
  - arch/powerpc/platforms/powernv/setup.c:pnv_power_off
  - arch/powerpc/platforms/powernv/setup.c:pnv_power_off
  - arch/powerpc/platforms/powernv/setup.c:pnv_restart
  - arch/powerpc/platforms/powernv/setup.c:pnv_restart
  - arch/powerpc/platforms/powernv/setup.c:pnv_restart
  - arch/powerpc/platforms/powernv/opal.c:opal_shutdown
  - arch/powerpc/platforms/powernv/opal.c:__opal_flush_console
  - arch/powerpc/platforms/powernv/opal.c:__opal_put_chars
  - arch/powerpc/platforms/powernv/opal.c:opal_get_chars
  - arch/powerpc/platforms/powernv/opal-rtc.c:opal_get_boot_time
  - arch/powerpc/platforms/powernv/opal-nvram.c:opal_nvram_write
  - arch/powerpc/platforms/powernv/opal-dump.c:dump_attr_read
  - arch/powerpc/platforms/powernv/opal-irqchip.c:opal_handle_events
  - drivers/rtc/rtc-opal.c:opal_set_rtc_time
  - drivers/rtc/rtc-opal.c:opal_get_rtc_time
```
**Symbols:**

```
c0000000000c28b0-c0000000000c28e8: opal_poll_events (STB_GLOBAL)
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
