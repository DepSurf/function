# Function: <code>devl_unlock</code>

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
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void devl_unlock(struct devlink *devlink);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81c72b70)
Location: net/core/devlink.c:268
Inline: False
```
**Symbols:**

```
ffffffff81c72b70-ffffffff81c72b8d: devl_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void devl_unlock(struct devlink *devlink);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81e44a3c)
Location: net/core/devlink.c:291
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_flash_update
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_trap_groups_unregister
  - net/core/devlink.c:devlink_trap_groups_register
  - net/core/devlink.c:devlink_traps_unregister
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_region_destroy
  - net/core/devlink.c:devlink_port_region_create
  - net/core/devlink.c:devlink_port_region_create
  - net/core/devlink.c:devlink_region_create
  - net/core/devlink.c:devlink_resource_occ_get_unregister
  - net/core/devlink.c:devlink_resource_occ_get_register
  - net/core/devlink.c:devlink_resources_unregister
  - net/core/devlink.c:devlink_resource_register
  - net/core/devlink.c:devlink_sb_unregister
  - net/core/devlink.c:devlink_sb_register
  - net/core/devlink.c:devlink_port_unregister
  - net/core/devlink.c:devlink_port_register
  - net/core/devlink.c:devlink_nl_cmd_trap_policer_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_trap_policer_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit
  - net/core/devlink.c:devlink_health_report
  - net/core/devlink.c:devlink_nl_cmd_info_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_param_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_param_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_selftests_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_port_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_port_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_rate_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_rate_get_dumpit
  - net/core/devlink.c:devlink_nl_post_doit
  - net/core/devlink.c:devlink_nl_pre_doit
```
**Symbols:**

```
ffffffff81e2b5f0-ffffffff81e2b60d: devl_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void devl_unlock(struct devlink *devlink);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/devlink/core.c (ffffffff820425ef)
Location: net/devlink/core.c:64
Inline: True
Inline callers:
  - net/devlink/core.c:devlink_pernet_pre_exit
  - net/devlink/core.c:devlink_unregister
  - net/devlink/core.c:devlink_register
Direct callers:
  - net/devlink/leftover.c:devlink_trap_groups_unregister
  - net/devlink/leftover.c:devlink_trap_groups_register
  - net/devlink/leftover.c:devlink_traps_unregister
  - net/devlink/leftover.c:devlink_traps_register
  - net/devlink/leftover.c:devlink_region_destroy
  - net/devlink/leftover.c:devlink_port_region_create
  - net/devlink/leftover.c:devlink_port_region_create
  - net/devlink/leftover.c:devlink_region_create
  - net/devlink/leftover.c:devlink_params_unregister
  - net/devlink/leftover.c:devlink_params_register
  - net/devlink/leftover.c:devlink_resource_occ_get_unregister
  - net/devlink/leftover.c:devlink_resource_occ_get_register
  - net/devlink/leftover.c:devlink_resources_unregister
  - net/devlink/leftover.c:devlink_resource_register
  - net/devlink/leftover.c:devlink_sb_unregister
  - net/devlink/leftover.c:devlink_sb_register
  - net/devlink/leftover.c:devlink_port_unregister
  - net/devlink/leftover.c:devlink_port_register_with_ops
  - net/devlink/leftover.c:devlink_nl_cmd_region_read_dumpit
  - net/devlink/leftover.c:devlink_nl_cmd_region_read_dumpit
  - net/devlink/netlink.c:devlink_nl_instance_iter_dumpit
  - net/devlink/netlink.c:devlink_nl_instance_iter_dumpit
  - net/devlink/netlink.c:devlink_nl_post_doit
  - net/devlink/netlink.c:devlink_nl_pre_doit
  - net/devlink/netlink.c:devlink_get_from_attrs_lock
  - net/devlink/dev.c:devlink_compat_flash_update
  - net/devlink/dev.c:devlink_compat_running_version
  - net/devlink/dev.c:devlink_compat_running_version
  - net/devlink/health.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/devlink/health.c:devlink_health_report
  - net/devlink/health.c:devlink_health_reporter_destroy
  - net/devlink/health.c:devlink_health_reporter_create
  - net/devlink/health.c:devlink_port_health_reporter_create
```
**Symbols:**

```
ffffffff82041dd0-ffffffff82041ded: devl_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void devl_unlock(struct devlink *devlink);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/devlink/core.c (ffffffff8210122f)
Location: net/devlink/core.c:286
Inline: True
Inline callers:
  - net/devlink/core.c:devlink_pernet_pre_exit
  - net/devlink/core.c:devlink_unregister
  - net/devlink/core.c:devlink_register
  - net/devlink/core.c:devlink_rel_nested_in_notify_work
Direct callers:
  - net/devlink/netlink.c:devlink_nl_dumpit
  - net/devlink/netlink.c:devlink_nl_dumpit
  - net/devlink/netlink.c:devlink_nl_dumpit
  - net/devlink/netlink.c:devlink_nl_post_doit_dev_lock
  - net/devlink/netlink.c:devlink_nl_post_doit
  - net/devlink/netlink.c:devlink_nl_pre_doit_port
  - net/devlink/netlink.c:devlink_get_from_attrs_lock
  - net/devlink/netlink.c:devlink_get_from_attrs_lock
  - net/devlink/netlink.c:devlink_get_from_attrs_lock
  - net/devlink/dev.c:devlink_compat_flash_update
  - net/devlink/dev.c:devlink_compat_running_version
  - net/devlink/dev.c:devlink_compat_running_version
  - net/devlink/port.c:devlink_port_unregister
  - net/devlink/port.c:devlink_port_register_with_ops
  - net/devlink/sb.c:devlink_sb_unregister
  - net/devlink/sb.c:devlink_sb_register
  - net/devlink/resource.c:devlink_resource_occ_get_unregister
  - net/devlink/resource.c:devlink_resource_occ_get_register
  - net/devlink/resource.c:devlink_resources_unregister
  - net/devlink/resource.c:devlink_resource_register
  - net/devlink/param.c:devlink_params_unregister
  - net/devlink/param.c:devlink_params_register
  - net/devlink/region.c:devlink_region_destroy
  - net/devlink/region.c:devlink_port_region_create
  - net/devlink/region.c:devlink_port_region_create
  - net/devlink/region.c:devlink_region_create
  - net/devlink/region.c:devlink_nl_region_read_dumpit
  - net/devlink/region.c:devlink_nl_region_read_dumpit
  - net/devlink/health.c:devlink_nl_health_reporter_dump_get_dumpit
  - net/devlink/health.c:devlink_nl_health_reporter_dump_get_dumpit
  - net/devlink/health.c:devlink_nl_health_reporter_dump_get_dumpit
  - net/devlink/health.c:devlink_health_report
  - net/devlink/health.c:devlink_health_report
  - net/devlink/health.c:devlink_health_reporter_destroy
  - net/devlink/health.c:devlink_health_reporter_create
  - net/devlink/health.c:devlink_port_health_reporter_create
  - net/devlink/trap.c:devlink_trap_groups_unregister
  - net/devlink/trap.c:devlink_trap_groups_register
  - net/devlink/trap.c:devlink_traps_unregister
  - net/devlink/trap.c:devlink_traps_register
```
**Symbols:**

```
ffffffff820fe810-ffffffff820fe82d: devl_unlock (STB_GLOBAL)
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
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
