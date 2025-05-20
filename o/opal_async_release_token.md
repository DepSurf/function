# Function: <code>opal_async_release_token</code>

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
int opal_async_release_token(int token);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/platforms/powernv/opal-async.c (c0000000000c66d0)
Location: arch/powerpc/platforms/powernv/opal-async.c:116
Inline: False
Direct callers:
  - arch/powerpc/platforms/powernv/opal-sysparam.c:sys_param_store
  - arch/powerpc/platforms/powernv/opal-sysparam.c:sys_param_show
  - arch/powerpc/platforms/powernv/opal-sysparam.c:sys_param_show
  - arch/powerpc/platforms/powernv/opal-sensor.c:opal_get_sensor_data
  - arch/powerpc/platforms/powernv/opal-powercap.c:powercap_store
  - arch/powerpc/platforms/powernv/opal-powercap.c:powercap_store
  - arch/powerpc/platforms/powernv/opal-powercap.c:powercap_show
  - arch/powerpc/platforms/powernv/opal-psr.c:psr_store
  - arch/powerpc/platforms/powernv/opal-psr.c:psr_store
  - arch/powerpc/platforms/powernv/opal-psr.c:psr_show
  - arch/powerpc/platforms/powernv/opal-sensor-groups.c:sensor_group_enable
  - arch/powerpc/platforms/powernv/pci.c:pnv_pci_set_power_state
  - drivers/rtc/rtc-opal.c:opal_set_tpo_time
  - drivers/rtc/rtc-opal.c:opal_get_tpo_time
  - drivers/i2c/busses/i2c-opal.c:i2c_opal_send_request
```
**Symbols:**

```
c0000000000c66d0-c0000000000c6824: opal_async_release_token (STB_GLOBAL)
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
