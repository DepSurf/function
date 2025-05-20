# Function: <code>scmi_xfer_done_no_timeout</code>

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
bool scmi_xfer_done_no_timeout(const struct scmi_chan_info *cinfo, struct scmi_xfer *xfer, ktime_t stop);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/arm_scmi/driver.c (ffff800010b56838)
Location: drivers/firmware/arm_scmi/driver.c:412
Inline: False
Direct callers:
  - drivers/firmware/arm_scmi/driver.c:scmi_do_xfer
  - drivers/firmware/arm_scmi/driver.c:scmi_do_xfer
  - drivers/firmware/arm_scmi/driver.c:scmi_do_xfer
```
**Symbols:**

```
ffff800010b56838-ffff800010b568d8: scmi_xfer_done_no_timeout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool scmi_xfer_done_no_timeout(const struct scmi_chan_info *cinfo, struct scmi_xfer *xfer, ktime_t stop);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/arm_scmi/driver.c (c0c374f0)
Location: drivers/firmware/arm_scmi/driver.c:412
Inline: False
Direct callers:
  - drivers/firmware/arm_scmi/driver.c:scmi_do_xfer
  - drivers/firmware/arm_scmi/driver.c:scmi_do_xfer
```
**Symbols:**

```
c0c374f0-c0c37568: scmi_xfer_done_no_timeout (STB_LOCAL)
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
