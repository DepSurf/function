# Function: <code>scmi_xfer_get_init</code>

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
int scmi_xfer_get_init(const struct scmi_handle *handle, u8 msg_id, u8 prot_id, size_t tx_size, size_t rx_size, struct scmi_xfer **p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/arm_scmi/driver.c (ffff800010b56de8)
Location: drivers/firmware/arm_scmi/driver.c:528
Inline: False
Direct callers:
  - drivers/firmware/arm_scmi/driver.c:scmi_version_get
  - drivers/firmware/arm_scmi/base.c:scmi_base_protocol_init
  - drivers/firmware/arm_scmi/base.c:scmi_base_protocol_init
  - drivers/firmware/arm_scmi/base.c:scmi_base_protocol_init
  - drivers/firmware/arm_scmi/base.c:scmi_base_protocol_init
  - drivers/firmware/arm_scmi/base.c:scmi_base_vendor_id_get
  - drivers/firmware/arm_scmi/base.c:scmi_base_vendor_id_get
  - drivers/firmware/arm_scmi/clock.c:scmi_clock_protocol_init
  - drivers/firmware/arm_scmi/clock.c:scmi_clock_protocol_init
  - drivers/firmware/arm_scmi/clock.c:scmi_clock_protocol_init
  - drivers/firmware/arm_scmi/clock.c:scmi_clock_config_set
  - drivers/firmware/arm_scmi/clock.c:scmi_clock_rate_set
  - drivers/firmware/arm_scmi/clock.c:scmi_clock_rate_get
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_protocol_init
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_protocol_init
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_protocol_init
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_domain_desc_fc
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_level_get
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_level_set
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_limits_get
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_limits_set
  - drivers/firmware/arm_scmi/power.c:scmi_power_protocol_init
  - drivers/firmware/arm_scmi/power.c:scmi_power_protocol_init
  - drivers/firmware/arm_scmi/power.c:scmi_power_state_get
  - drivers/firmware/arm_scmi/power.c:scmi_power_state_set
  - drivers/firmware/arm_scmi/reset.c:scmi_reset_protocol_init
  - drivers/firmware/arm_scmi/reset.c:scmi_reset_protocol_init
  - drivers/firmware/arm_scmi/sensors.c:scmi_sensors_protocol_init
  - drivers/firmware/arm_scmi/sensors.c:scmi_sensors_protocol_init
  - drivers/firmware/arm_scmi/sensors.c:scmi_sensor_reading_get
  - drivers/firmware/arm_scmi/sensors.c:scmi_sensor_trip_point_config
  - drivers/firmware/arm_scmi/sensors.c:scmi_sensor_trip_point_notify
```
**Symbols:**

```
ffff800010b56de8-ffff800010b56fb4: scmi_xfer_get_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int scmi_xfer_get_init(const struct scmi_handle *handle, u8 msg_id, u8 prot_id, size_t tx_size, size_t rx_size, struct scmi_xfer **p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/arm_scmi/driver.c (c0c381f8)
Location: drivers/firmware/arm_scmi/driver.c:528
Inline: False
Direct callers:
  - drivers/firmware/arm_scmi/driver.c:scmi_version_get
  - drivers/firmware/arm_scmi/base.c:scmi_base_protocol_init
  - drivers/firmware/arm_scmi/base.c:scmi_base_protocol_init
  - drivers/firmware/arm_scmi/base.c:scmi_base_protocol_init
  - drivers/firmware/arm_scmi/base.c:scmi_base_protocol_init
  - drivers/firmware/arm_scmi/base.c:scmi_base_vendor_id_get
  - drivers/firmware/arm_scmi/clock.c:scmi_clock_protocol_init
  - drivers/firmware/arm_scmi/clock.c:scmi_clock_protocol_init
  - drivers/firmware/arm_scmi/clock.c:scmi_clock_protocol_init
  - drivers/firmware/arm_scmi/clock.c:scmi_clock_config_set
  - drivers/firmware/arm_scmi/clock.c:scmi_clock_rate_set
  - drivers/firmware/arm_scmi/clock.c:scmi_clock_rate_get
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_protocol_init
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_protocol_init
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_protocol_init
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_domain_desc_fc
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_level_get
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_level_set
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_limits_get
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_limits_set
  - drivers/firmware/arm_scmi/power.c:scmi_power_protocol_init
  - drivers/firmware/arm_scmi/power.c:scmi_power_protocol_init
  - drivers/firmware/arm_scmi/power.c:scmi_power_state_get
  - drivers/firmware/arm_scmi/power.c:scmi_power_state_set
  - drivers/firmware/arm_scmi/reset.c:scmi_reset_protocol_init
  - drivers/firmware/arm_scmi/reset.c:scmi_reset_protocol_init
  - drivers/firmware/arm_scmi/sensors.c:scmi_sensors_protocol_init
  - drivers/firmware/arm_scmi/sensors.c:scmi_sensors_protocol_init
  - drivers/firmware/arm_scmi/sensors.c:scmi_sensor_reading_get
  - drivers/firmware/arm_scmi/sensors.c:scmi_sensor_trip_point_config
  - drivers/firmware/arm_scmi/sensors.c:scmi_sensor_trip_point_notify
```
**Symbols:**

```
c0c381f8-c0c3832c: scmi_xfer_get_init (STB_GLOBAL)
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
