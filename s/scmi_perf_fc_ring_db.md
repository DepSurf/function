# Function: <code>scmi_perf_fc_ring_db</code>

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
void scmi_perf_fc_ring_db(struct scmi_fc_db_info *db);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/arm_scmi/perf.c (ffff800010b57e60)
Location: drivers/firmware/arm_scmi/perf.c:306
Inline: False
Direct callers:
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_level_set
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_limits_set
```
**Symbols:**

```
ffff800010b57e60-ffff800010b57fac: scmi_perf_fc_ring_db (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void scmi_perf_fc_ring_db(struct scmi_fc_db_info *db);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/arm_scmi/perf.c (c0c39610)
Location: drivers/firmware/arm_scmi/perf.c:306
Inline: False
Direct callers:
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_level_set
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_limits_set
```
**Symbols:**

```
c0c39610-c0c39778: scmi_perf_fc_ring_db (STB_LOCAL)
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
