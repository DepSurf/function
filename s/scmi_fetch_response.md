# Function: <code>scmi_fetch_response</code>

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
void scmi_fetch_response(struct scmi_xfer *xfer, struct scmi_shared_mem *mem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/arm_scmi/driver.c (ffff800010b568d8)
Location: drivers/firmware/arm_scmi/driver.c:197
Inline: False
Direct callers:
  - drivers/firmware/arm_scmi/driver.c:scmi_do_xfer
  - drivers/firmware/arm_scmi/driver.c:scmi_rx_callback
  - drivers/firmware/arm_scmi/driver.c:scmi_rx_callback
```
**Symbols:**

```
ffff800010b568d8-ffff800010b56954: scmi_fetch_response (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void scmi_fetch_response(struct scmi_xfer *xfer, struct scmi_shared_mem *mem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/arm_scmi/driver.c (c0c37568)
Location: drivers/firmware/arm_scmi/driver.c:197
Inline: False
Direct callers:
  - drivers/firmware/arm_scmi/driver.c:scmi_do_xfer
  - drivers/firmware/arm_scmi/driver.c:scmi_rx_callback
```
**Symbols:**

```
c0c37568-c0c375b8: scmi_fetch_response (STB_LOCAL)
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
