# Function: <code>ti_sci_get_device_state</code>

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
int ti_sci_get_device_state(const struct ti_sci_handle *handle, u32 id, u32 *clcnt, u32 *resets, u8 *p_state, u8 *c_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/ti_sci.c (ffff800010b54520)
Location: drivers/firmware/ti_sci.c:577
Inline: False
Direct callers:
  - drivers/firmware/ti_sci.c:ti_sci_cmd_get_device_resets
  - drivers/firmware/ti_sci.c:ti_sci_cmd_dev_is_trans
  - drivers/firmware/ti_sci.c:ti_sci_cmd_dev_is_on
  - drivers/firmware/ti_sci.c:ti_sci_cmd_dev_is_stop
  - drivers/firmware/ti_sci.c:ti_sci_cmd_dev_is_idle
  - drivers/firmware/ti_sci.c:ti_sci_cmd_dev_get_clcnt
  - drivers/firmware/ti_sci.c:ti_sci_cmd_dev_is_valid
```
**Symbols:**

```
ffff800010b54520-ffff800010b546f0: ti_sci_get_device_state (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
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
