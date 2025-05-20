# Function: <code>devlink_fmsg_err_if_binary</code>

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
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/devlink/health.c (ffffffff82114278)
Location: net/devlink/health.c:677
Inline: True
Inline callers:
  - net/devlink/health.c:devlink_nl_health_reporter_diagnose_doit
  - net/devlink/health.c:devlink_nl_health_reporter_diagnose_doit
  - net/devlink/health.c:devlink_nl_health_reporter_diagnose_doit
  - net/devlink/health.c:devlink_nl_health_reporter_diagnose_doit
  - net/devlink/health.c:devlink_fmsg_binary_pair_put
  - net/devlink/health.c:devlink_fmsg_binary_pair_put
  - net/devlink/health.c:devlink_fmsg_binary_pair_put
  - net/devlink/health.c:devlink_fmsg_string_pair_put
  - net/devlink/health.c:devlink_fmsg_string_pair_put
  - net/devlink/health.c:devlink_fmsg_u64_pair_put
  - net/devlink/health.c:devlink_fmsg_u64_pair_put
  - net/devlink/health.c:devlink_fmsg_u64_pair_put
  - net/devlink/health.c:devlink_fmsg_u64_pair_put
  - net/devlink/health.c:devlink_fmsg_u32_pair_put
  - net/devlink/health.c:devlink_fmsg_u32_pair_put
  - net/devlink/health.c:devlink_fmsg_u32_pair_put
  - net/devlink/health.c:devlink_fmsg_u32_pair_put
  - net/devlink/health.c:devlink_fmsg_u8_pair_put
  - net/devlink/health.c:devlink_fmsg_u8_pair_put
  - net/devlink/health.c:devlink_fmsg_u8_pair_put
  - net/devlink/health.c:devlink_fmsg_u8_pair_put
  - net/devlink/health.c:devlink_fmsg_bool_pair_put
  - net/devlink/health.c:devlink_fmsg_bool_pair_put
  - net/devlink/health.c:devlink_fmsg_bool_pair_put
  - net/devlink/health.c:devlink_fmsg_bool_pair_put
  - net/devlink/health.c:devlink_fmsg_string_put
  - net/devlink/health.c:devlink_fmsg_string_put
  - net/devlink/health.c:devlink_fmsg_pair_nest_start
  - net/devlink/health.c:devlink_fmsg_pair_nest_start
  - net/devlink/health.c:devlink_fmsg_put_name
  - net/devlink/health.c:devlink_fmsg_put_name
  - net/devlink/health.c:devlink_health_do_dump
  - net/devlink/health.c:devlink_health_do_dump
  - net/devlink/health.c:devlink_health_do_dump
  - net/devlink/health.c:devlink_health_do_dump
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
