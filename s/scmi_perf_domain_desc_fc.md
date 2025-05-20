# Function: <code>scmi_perf_domain_desc_fc</code>

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
void scmi_perf_domain_desc_fc(const struct scmi_handle *handle, u32 domain, u32 message_id, void **p_addr, struct scmi_fc_db_info **p_db);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/arm_scmi/perf.c (ffff800010b58498)
Location: drivers/firmware/arm_scmi/perf.c:495
Inline: False
Direct callers:
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_protocol_init
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_protocol_init
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_protocol_init
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_protocol_init
```
**Symbols:**

```
ffff800010b58498-ffff800010b58620: scmi_perf_domain_desc_fc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void scmi_perf_domain_desc_fc(const struct scmi_handle *handle, u32 domain, u32 message_id, void **p_addr, struct scmi_fc_db_info **p_db);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/arm_scmi/perf.c (c0c399f0)
Location: drivers/firmware/arm_scmi/perf.c:495
Inline: False
Direct callers:
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_protocol_init
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_protocol_init
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_protocol_init
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_protocol_init
```
**Symbols:**

```
c0c399f0-c0c39b88: scmi_perf_domain_desc_fc (STB_LOCAL)
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
