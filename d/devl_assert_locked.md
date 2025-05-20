# Function: <code>devl_assert_locked</code>

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
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void devl_assert_locked(struct devlink *devlink);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81c72460)
Location: net/core/devlink.c:247
Inline: True
```
**Symbols:**

```
ffffffff81c72460-ffffffff81c7246f: devl_assert_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void devl_assert_locked(struct devlink *devlink);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81e2a6b0)
Location: net/core/devlink.c:264
Inline: True
```
**Symbols:**

```
ffffffff81e2a6b0-ffffffff81e2a6bf: devl_assert_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void devl_assert_locked(struct devlink *devlink);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/devlink/core.c (ffffffff82041d50)
Location: net/devlink/core.c:37
Inline: True
Direct callers:
  - net/devlink/leftover.c:devl_trap_policers_unregister
  - net/devlink/leftover.c:devl_trap_policers_register
  - net/devlink/leftover.c:devlink_trap_groups_unregister
  - net/devlink/leftover.c:devl_trap_groups_register
  - net/devlink/leftover.c:devl_traps_unregister
  - net/devlink/leftover.c:devlink_traps_register
  - net/devlink/leftover.c:devl_region_destroy
  - net/devlink/leftover.c:devl_region_create
  - net/devlink/leftover.c:devl_param_driverinit_value_set
  - net/devlink/leftover.c:devl_rate_nodes_destroy
  - net/devlink/leftover.c:devl_rate_leaf_destroy
  - net/devlink/leftover.c:devl_rate_leaf_create
  - net/devlink/leftover.c:devl_port_register_with_ops
  - net/devlink/netlink.c:devlink_nl_instance_iter_dumpit
  - net/devlink/netlink.c:devlink_get_from_attrs_lock
  - net/devlink/dev.c:devlink_compat_flash_update
  - net/devlink/dev.c:devlink_compat_running_version
  - net/devlink/health.c:devlink_health_reporter_destroy
  - net/devlink/health.c:devl_health_reporter_create
  - net/devlink/health.c:devl_port_health_reporter_create
```
**Symbols:**

```
ffffffff82041d50-ffffffff82041d5f: devl_assert_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void devl_assert_locked(struct devlink *devlink);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/devlink/core.c (ffffffff820fde90)
Location: net/devlink/core.c:259
Inline: True
Direct callers:
  - net/devlink/netlink.c:devlink_nl_dumpit
  - net/devlink/netlink.c:devlink_get_from_attrs_lock
  - net/devlink/netlink.c:devlink_get_from_attrs_lock
  - net/devlink/dev.c:devlink_compat_flash_update
  - net/devlink/dev.c:devlink_compat_running_version
  - net/devlink/port.c:devl_port_register_with_ops
  - net/devlink/param.c:devl_param_driverinit_value_set
  - net/devlink/region.c:devl_region_destroy
  - net/devlink/region.c:devl_region_create
  - net/devlink/health.c:devlink_health_reporter_destroy
  - net/devlink/health.c:devl_health_reporter_create
  - net/devlink/health.c:devl_port_health_reporter_create
  - net/devlink/trap.c:devl_trap_policers_unregister
  - net/devlink/trap.c:devl_trap_policers_register
  - net/devlink/trap.c:devlink_trap_groups_unregister
  - net/devlink/trap.c:devl_trap_groups_register
  - net/devlink/trap.c:devl_traps_unregister
  - net/devlink/trap.c:devlink_traps_register
  - net/devlink/rate.c:devl_rate_nodes_destroy
  - net/devlink/rate.c:devl_rate_leaf_destroy
  - net/devlink/rate.c:devl_rate_leaf_create
  - net/devlink/rate.c:devlink_rate_notify
```
**Symbols:**

```
ffffffff820fde90-ffffffff820fde9f: devl_assert_locked (STB_GLOBAL)
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
