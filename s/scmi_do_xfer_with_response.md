# Function: <code>scmi_do_xfer_with_response</code>

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
int scmi_do_xfer_with_response(const struct scmi_handle *handle, struct scmi_xfer *xfer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/arm_scmi/driver.c (ffff800010b56d48)
Location: drivers/firmware/arm_scmi/driver.c:496
Inline: False
Direct callers:
  - drivers/firmware/arm_scmi/clock.c:scmi_clock_rate_set
  - drivers/firmware/arm_scmi/sensors.c:scmi_sensor_reading_get
```
**Symbols:**

```
ffff800010b56d48-ffff800010b56de8: scmi_do_xfer_with_response (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int scmi_do_xfer_with_response(const struct scmi_handle *handle, struct scmi_xfer *xfer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/arm_scmi/driver.c (c0c38158)
Location: drivers/firmware/arm_scmi/driver.c:496
Inline: False
Direct callers:
  - drivers/firmware/arm_scmi/clock.c:scmi_clock_rate_set
  - drivers/firmware/arm_scmi/sensors.c:scmi_sensor_reading_get
```
**Symbols:**

```
c0c38158-c0c381f8: scmi_do_xfer_with_response (STB_GLOBAL)
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
