# Function: <code>devlink_dump_state</code>

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
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/devlink/leftover.c (ffffffff820378b8)
Location: net/devlink/devl_internal.h:134
Inline: True
Inline callers:
  - net/devlink/leftover.c:devlink_nl_cmd_trap_policer_get_dump_one
  - net/devlink/leftover.c:devlink_nl_cmd_trap_group_get_dump_one
  - net/devlink/leftover.c:devlink_nl_cmd_trap_get_dump_one
  - net/devlink/leftover.c:devlink_nl_cmd_region_read_dumpit
  - net/devlink/leftover.c:devlink_nl_cmd_region_get_dump_one
  - net/devlink/leftover.c:devlink_nl_cmd_param_get_dump_one
  - net/devlink/leftover.c:devlink_nl_cmd_sb_pool_get_dump_one
  - net/devlink/leftover.c:devlink_nl_cmd_sb_get_dump_one
  - net/devlink/leftover.c:devlink_nl_cmd_linecard_get_dump_one
  - net/devlink/leftover.c:devlink_nl_cmd_port_get_dump_one
  - net/devlink/leftover.c:devlink_nl_cmd_rate_get_dump_one
```
```
In net/devlink/netlink.c (ffffffff82042975)
Location: net/devlink/devl_internal.h:134
Inline: True
Inline callers:
  - net/devlink/netlink.c:devlink_nl_instance_iter_dumpit
```
```
In net/devlink/health.c (ffffffff820483cb)
Location: net/devlink/devl_internal.h:134
Inline: True
Inline callers:
  - net/devlink/health.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/devlink/health.c:devlink_nl_cmd_health_reporter_get_dump_one
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/devlink/netlink.c (0)
Location: net/devlink/devl_internal.h:167
Inline: True
```
```
In net/devlink/port.c (ffffffff82106b1c)
Location: net/devlink/devl_internal.h:167
Inline: True
Inline callers:
  - net/devlink/port.c:devlink_nl_port_get_dump_one
```
```
In net/devlink/sb.c (ffffffff82109295)
Location: net/devlink/devl_internal.h:167
Inline: True
Inline callers:
  - net/devlink/sb.c:devlink_nl_sb_pool_get_dump_one
  - net/devlink/sb.c:devlink_nl_sb_get_dump_one
```
```
In net/devlink/param.c (ffffffff8210eeb1)
Location: net/devlink/devl_internal.h:167
Inline: True
Inline callers:
  - net/devlink/param.c:devlink_nl_param_get_dump_one
```
```
In net/devlink/region.c (ffffffff8210f946)
Location: net/devlink/devl_internal.h:167
Inline: True
Inline callers:
  - net/devlink/region.c:devlink_nl_region_get_dump_one
```
```
In net/devlink/health.c (ffffffff821144e2)
Location: net/devlink/devl_internal.h:167
Inline: True
Inline callers:
  - net/devlink/health.c:devlink_nl_health_reporter_dump_get_dumpit
```
```
In net/devlink/trap.c (ffffffff82114ce8)
Location: net/devlink/devl_internal.h:167
Inline: True
Inline callers:
  - net/devlink/trap.c:devlink_nl_trap_policer_get_dump_one
  - net/devlink/trap.c:devlink_nl_trap_group_get_dump_one
  - net/devlink/trap.c:devlink_nl_trap_get_dump_one
```
```
In net/devlink/rate.c (ffffffff82119012)
Location: net/devlink/devl_internal.h:167
Inline: True
Inline callers:
  - net/devlink/rate.c:devlink_nl_rate_get_dump_one
```
```
In net/devlink/linecard.c (ffffffff82119b6c)
Location: net/devlink/devl_internal.h:167
Inline: True
Inline callers:
  - net/devlink/linecard.c:devlink_nl_linecard_get_dump_one
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
