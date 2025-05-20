# Function: <code>opal_get_async_rc</code>

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
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/platforms/powernv/opal-sysparam.c (c0000000000cbaa4)
Location: arch/powerpc/include/asm/opal.h:389
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/opal-sysparam.c:sys_param_store
  - arch/powerpc/platforms/powernv/opal-sysparam.c:sys_param_show
```
```
In arch/powerpc/platforms/powernv/opal-sensor.c (c0000000000cbec0)
Location: arch/powerpc/include/asm/opal.h:389
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/opal-sensor.c:opal_get_sensor_data
```
```
In arch/powerpc/platforms/powernv/opal-powercap.c (c0000000000cd404)
Location: arch/powerpc/include/asm/opal.h:389
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/opal-powercap.c:powercap_store
  - arch/powerpc/platforms/powernv/opal-powercap.c:powercap_show
```
```
In arch/powerpc/platforms/powernv/opal-psr.c (c0000000000cd7e4)
Location: arch/powerpc/include/asm/opal.h:389
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/opal-psr.c:psr_store
  - arch/powerpc/platforms/powernv/opal-psr.c:psr_show
```
```
In arch/powerpc/platforms/powernv/opal-sensor-groups.c (c0000000000cdae4)
Location: arch/powerpc/include/asm/opal.h:389
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/opal-sensor-groups.c:sensor_group_enable
```
```
In drivers/rtc/rtc-opal.c (c000000000b8fd20)
Location: arch/powerpc/include/asm/opal.h:389
Inline: True
Inline callers:
  - drivers/rtc/rtc-opal.c:opal_set_tpo_time
  - drivers/rtc/rtc-opal.c:opal_get_tpo_time
```
```
In drivers/i2c/busses/i2c-opal.c (c000000000b9e340)
Location: arch/powerpc/include/asm/opal.h:389
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-opal.c:i2c_opal_send_request
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
