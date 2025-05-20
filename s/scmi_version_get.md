# Function: <code>scmi_version_get</code>

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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int scmi_version_get(const struct scmi_handle *handle, u8 protocol, u32 *version);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/arm_scmi/driver.c (ffff800010b56fb8)
Location: drivers/firmware/arm_scmi/driver.c:571
Inline: False
Direct callers:
  - drivers/firmware/arm_scmi/base.c:scmi_base_protocol_init
  - drivers/firmware/arm_scmi/clock.c:scmi_clock_protocol_init
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_protocol_init
  - drivers/firmware/arm_scmi/power.c:scmi_power_protocol_init
  - drivers/firmware/arm_scmi/reset.c:scmi_reset_protocol_init
  - drivers/firmware/arm_scmi/sensors.c:scmi_sensors_protocol_init
```
**Symbols:**

```
ffff800010b56fb8-ffff800010b5706c: scmi_version_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int scmi_version_get(const struct scmi_handle *handle, u8 protocol, u32 *version);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/arm_scmi/driver.c (c0c3832c)
Location: drivers/firmware/arm_scmi/driver.c:571
Inline: False
Direct callers:
  - drivers/firmware/arm_scmi/base.c:scmi_base_protocol_init
  - drivers/firmware/arm_scmi/clock.c:scmi_clock_protocol_init
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_protocol_init
  - drivers/firmware/arm_scmi/power.c:scmi_power_protocol_init
  - drivers/firmware/arm_scmi/reset.c:scmi_reset_protocol_init
  - drivers/firmware/arm_scmi/sensors.c:scmi_sensors_protocol_init
```
**Symbols:**

```
c0c3832c-c0c383fc: scmi_version_get (STB_GLOBAL)
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
