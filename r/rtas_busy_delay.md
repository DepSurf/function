# Function: <code>rtas_busy_delay</code>

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
unsigned int rtas_busy_delay(int status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/rtas.c (c00000000003cee0)
Location: arch/powerpc/kernel/rtas.c:508
Inline: False
Direct callers:
  - arch/powerpc/kernel/rtas.c:rtas_os_term
  - arch/powerpc/kernel/rtas.c:rtas_set_indicator
  - arch/powerpc/kernel/rtas.c:rtas_get_sensor
  - arch/powerpc/kernel/rtas.c:rtas_set_power_level
  - arch/powerpc/platforms/pseries/iommu.c:enable_ddw
  - arch/powerpc/platforms/pseries/mobility.c:post_mobility_fixup
  - arch/powerpc/platforms/pseries/eeh_pseries.c:pseries_eeh_configure_bridge
  - arch/powerpc/platforms/pseries/msi.c:rtas_change_msi
  - arch/powerpc/platforms/pseries/msi.c:rtas_change_msi
```
**Symbols:**

```
c00000000003cee0-c00000000003cf98: rtas_busy_delay (STB_GLOBAL)
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
