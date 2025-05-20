# Function: <code>devlink_nl_dumpit</code>

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
<summary>In <code>6.8</code>: ✅</summary>

```c
int devlink_nl_dumpit(struct sk_buff *msg, struct netlink_callback *cb, devlink_nl_dump_one_func_t *dump_one);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/netlink.c (ffffffff82101c70)
Location: net/devlink/netlink.c:346
Inline: False
Direct callers:
  - net/devlink/dev.c:devlink_nl_selftests_get_dumpit
  - net/devlink/dev.c:devlink_nl_info_get_dumpit
  - net/devlink/dev.c:devlink_nl_get_dumpit
  - net/devlink/port.c:devlink_nl_port_get_dumpit
  - net/devlink/sb.c:devlink_nl_sb_tc_pool_bind_get_dumpit
  - net/devlink/sb.c:devlink_nl_sb_port_pool_get_dumpit
  - net/devlink/sb.c:devlink_nl_sb_pool_get_dumpit
  - net/devlink/sb.c:devlink_nl_sb_get_dumpit
  - net/devlink/param.c:devlink_nl_param_get_dumpit
  - net/devlink/region.c:devlink_nl_region_get_dumpit
  - net/devlink/health.c:devlink_nl_health_reporter_get_dumpit
  - net/devlink/trap.c:devlink_nl_trap_policer_get_dumpit
  - net/devlink/trap.c:devlink_nl_trap_group_get_dumpit
  - net/devlink/trap.c:devlink_nl_trap_get_dumpit
  - net/devlink/rate.c:devlink_nl_rate_get_dumpit
  - net/devlink/linecard.c:devlink_nl_linecard_get_dumpit
```
**Symbols:**

```
ffffffff82101c70-ffffffff82101dc7: devlink_nl_dumpit (STB_GLOBAL)
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
<b>Regular</b>
<ul>
</ul>
