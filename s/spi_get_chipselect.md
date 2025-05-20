# Function: <code>spi_get_chipselect</code>

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
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81c2c888)
Location: include/linux/spi/spi.h:279
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_set_cs
  - drivers/spi/spi.c:spi_set_cs
  - drivers/spi/spi.c:spi_add_device
  - drivers/spi/spi.c:__spi_add_device
  - drivers/spi/spi.c:__spi_add_device
  - drivers/spi/spi.c:spi_dev_check
  - drivers/spi/spi.c:spi_dev_check
  - drivers/spi/spi.c:spi_dev_set_name
  - drivers/spi/spi.c:perf_trace_spi_transfer
  - drivers/spi/spi.c:perf_trace_spi_message_done
  - drivers/spi/spi.c:perf_trace_spi_message
  - drivers/spi/spi.c:perf_trace_spi_set_cs
  - drivers/spi/spi.c:perf_trace_spi_setup
  - drivers/spi/spi.c:trace_event_raw_event_spi_transfer
  - drivers/spi/spi.c:trace_event_raw_event_spi_message_done
  - drivers/spi/spi.c:trace_event_raw_event_spi_message
  - drivers/spi/spi.c:trace_event_raw_event_spi_set_cs
  - drivers/spi/spi.c:trace_event_raw_event_spi_setup
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81cdf2ab)
Location: include/linux/spi/spi.h:292
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_set_cs
  - drivers/spi/spi.c:spi_set_cs
  - drivers/spi/spi.c:spi_set_cs
  - drivers/spi/spi.c:__spi_add_device
  - drivers/spi/spi.c:__spi_add_device
  - drivers/spi/spi.c:__spi_add_device
  - drivers/spi/spi.c:__spi_add_device
  - drivers/spi/spi.c:__spi_add_device
  - drivers/spi/spi.c:spi_dev_check
  - drivers/spi/spi.c:spi_dev_check
  - drivers/spi/spi.c:spi_dev_set_name
  - drivers/spi/spi.c:perf_trace_spi_transfer
  - drivers/spi/spi.c:perf_trace_spi_message_done
  - drivers/spi/spi.c:perf_trace_spi_message
  - drivers/spi/spi.c:perf_trace_spi_set_cs
  - drivers/spi/spi.c:perf_trace_spi_setup
  - drivers/spi/spi.c:trace_event_raw_event_spi_transfer
  - drivers/spi/spi.c:trace_event_raw_event_spi_message_done
  - drivers/spi/spi.c:trace_event_raw_event_spi_message
  - drivers/spi/spi.c:trace_event_raw_event_spi_set_cs
  - drivers/spi/spi.c:trace_event_raw_event_spi_setup
```
</details>
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
