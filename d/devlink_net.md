# Function: <code>devlink_net</code>

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
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8194b267)
Location: net/core/devlink.c:95
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_info_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_get_dumpit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_param_get_dumpit
  - net/core/devlink.c:devlink_param_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_port_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_get_dumpit
  - net/core/devlink.c:devlink_port_notify
  - net/core/devlink.c:devlink_notify
  - net/core/devlink.c:devlink_get_from_attrs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81983ea1)
Location: net/core/devlink.c:98
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_trap_notify
  - net/core/devlink.c:devlink_trap_group_notify
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_info_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_get_dumpit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_param_get_dumpit
  - net/core/devlink.c:devlink_param_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_port_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_get_dumpit
  - net/core/devlink.c:devlink_port_notify
  - net/core/devlink.c:devlink_notify
  - net/core/devlink.c:devlink_get_from_attrs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct net *devlink_net(const struct devlink *devlink);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a5dc49)
Location: net/core/devlink.c:98
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_pernet_pre_exit
  - net/core/devlink.c:devlink_trap_policer_notify
  - net/core/devlink.c:devlink_trap_notify
  - net/core/devlink.c:devlink_trap_group_notify
  - net/core/devlink.c:devlink_nl_cmd_trap_policer_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_info_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_get_dumpit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_param_get_dumpit
  - net/core/devlink.c:devlink_param_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_port_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_get_dumpit
  - net/core/devlink.c:devlink_port_notify
  - net/core/devlink.c:devlink_notify
  - net/core/devlink.c:devlink_get_from_attrs
```
**Symbols:**

```
ffffffff81a50140-ffffffff81a50152: devlink_net (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct net *devlink_net(const struct devlink *devlink);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a676ec)
Location: net/core/devlink.c:102
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_pernet_pre_exit
  - net/core/devlink.c:devlink_trap_policer_notify
  - net/core/devlink.c:devlink_trap_notify
  - net/core/devlink.c:devlink_trap_group_notify
  - net/core/devlink.c:devlink_nl_cmd_trap_policer_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_info_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_get_dumpit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_param_get_dumpit
  - net/core/devlink.c:devlink_param_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_reload
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_port_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_get_dumpit
  - net/core/devlink.c:devlink_port_notify
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_notify
  - net/core/devlink.c:devlink_get_from_attrs
```
**Symbols:**

```
ffffffff81a563d0-ffffffff81a563e2: devlink_net (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct net *devlink_net(const struct devlink *devlink);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a4a5ec)
Location: net/core/devlink.c:105
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_pernet_pre_exit
  - net/core/devlink.c:devlink_trap_policer_notify
  - net/core/devlink.c:devlink_trap_notify
  - net/core/devlink.c:devlink_trap_group_notify
  - net/core/devlink.c:devlink_nl_cmd_trap_policer_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_info_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_get_dumpit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_param_get_dumpit
  - net/core/devlink.c:devlink_param_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_reload
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_port_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_get_dumpit
  - net/core/devlink.c:devlink_port_notify
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_notify
  - net/core/devlink.c:devlink_get_from_attrs
```
**Symbols:**

```
ffffffff81a393a0-ffffffff81a393b2: devlink_net (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct net *devlink_net(const struct devlink *devlink);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81b02806)
Location: net/core/devlink.c:106
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_pernet_pre_exit
  - net/core/devlink.c:devlink_trap_policer_notify
  - net/core/devlink.c:devlink_trap_notify
  - net/core/devlink.c:devlink_trap_group_notify
  - net/core/devlink.c:devlink_nl_cmd_trap_policer_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_info_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_get_dumpit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_param_get_dumpit
  - net/core/devlink.c:devlink_param_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_reload
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_port_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_rate_get_dumpit
  - net/core/devlink.c:devlink_rate_notify
  - net/core/devlink.c:devlink_port_notify
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_notify
  - net/core/devlink.c:devlink_get_from_attrs
```
**Symbols:**

```
ffffffff81aef380-ffffffff81aef392: devlink_net (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct net *devlink_net(const struct devlink *devlink);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81c89b04)
Location: net/core/devlink.c:228
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_pernet_pre_exit
  - net/core/devlink.c:devlink_nl_cmd_trap_policer_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_info_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_get_dumpit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_param_get_dumpit
  - net/core/devlink.c:devlink_param_notify
  - net/core/devlink.c:devlink_reload
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_linecard_get_dumpit
  - net/core/devlink.c:devlink_linecard_notify
  - net/core/devlink.c:devlink_nl_cmd_port_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_rate_get_dumpit
  - net/core/devlink.c:devlink_rate_notify
  - net/core/devlink.c:devlink_port_notify
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_notify
  - net/core/devlink.c:devlink_get_from_attrs
```
**Symbols:**

```
ffffffff81c72440-ffffffff81c72458: devlink_net (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct net *devlink_net(const struct devlink *devlink);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81e3e3bb)
Location: net/core/devlink.c:234
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_netdevice_event
  - net/core/devlink.c:devlink_netdevice_event
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_reload
  - net/core/devlink.c:devlink_linecard_notify
  - net/core/devlink.c:devlink_rate_notify
  - net/core/devlink.c:devlink_port_notify
  - net/core/devlink.c:devlink_notify
```
**Symbols:**

```
ffffffff81e2a680-ffffffff81e2a698: devlink_net (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct net *devlink_net(const struct devlink *devlink);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/devlink/core.c (ffffffff82042558)
Location: net/devlink/core.c:31
Inline: True
Inline callers:
  - net/devlink/core.c:devlinks_xa_find_get
Direct callers:
  - net/devlink/leftover.c:devlink_port_netdevice_event
  - net/devlink/leftover.c:devlink_port_netdevice_event
  - net/devlink/leftover.c:devlink_nl_region_notify
  - net/devlink/leftover.c:devlink_linecard_notify
  - net/devlink/leftover.c:devlink_rate_notify
  - net/devlink/leftover.c:devlink_port_notify
  - net/devlink/dev.c:devlink_nl_cmd_reload
  - net/devlink/dev.c:devlink_reload
  - net/devlink/dev.c:devlink_notify
```
**Symbols:**

```
ffffffff82041d20-ffffffff82041d38: devlink_net (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct net *devlink_net(const struct devlink *devlink);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/devlink/core.c (ffffffff82101198)
Location: net/devlink/core.c:253
Inline: True
Inline callers:
  - net/devlink/core.c:devlinks_xa_find_get
  - net/devlink/core.c:devlink_rel_devlink_handle_put
Direct callers:
  - net/devlink/dev.c:devlink_nl_reload_doit
  - net/devlink/dev.c:devlink_reload
  - net/devlink/port.c:devlink_port_netdevice_event
  - net/devlink/port.c:devlink_port_netdevice_event
  - net/devlink/port.c:devlink_port_notify
  - net/devlink/port.c:devlink_port_notify
  - net/devlink/region.c:devlink_nl_region_notify
  - net/devlink/region.c:devlink_nl_region_notify
  - net/devlink/rate.c:devlink_rate_notify
  - net/devlink/rate.c:devlink_rate_notify
  - net/devlink/linecard.c:devlink_linecard_notify
  - net/devlink/linecard.c:devlink_linecard_notify
```
**Symbols:**

```
ffffffff820fde60-ffffffff820fde78: devlink_net (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffff800010c2c4e8)
Location: net/core/devlink.c:98
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_trap_notify
  - net/core/devlink.c:devlink_trap_group_notify
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_info_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_get_dumpit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_param_get_dumpit
  - net/core/devlink.c:devlink_param_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_port_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_get_dumpit
  - net/core/devlink.c:devlink_port_notify
  - net/core/devlink.c:devlink_notify
  - net/core/devlink.c:devlink_get_from_attrs
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c0d4306c)
Location: net/core/devlink.c:98
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_trap_notify
  - net/core/devlink.c:devlink_trap_group_notify
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_info_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_get_dumpit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_param_get_dumpit
  - net/core/devlink.c:devlink_param_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_port_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_get_dumpit
  - net/core/devlink.c:devlink_port_notify
  - net/core/devlink.c:devlink_notify
  - net/core/devlink.c:devlink_get_from_attrs
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c000000000d231b8)
Location: net/core/devlink.c:98
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_trap_notify
  - net/core/devlink.c:devlink_trap_group_notify
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_info_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_get_dumpit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_param_get_dumpit
  - net/core/devlink.c:devlink_param_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_port_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_get_dumpit
  - net/core/devlink.c:devlink_port_notify
  - net/core/devlink.c:devlink_notify
  - net/core/devlink.c:devlink_get_from_attrs
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffe0007a3a1c)
Location: net/core/devlink.c:98
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_trap_notify
  - net/core/devlink.c:devlink_trap_group_notify
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_info_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_get_dumpit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_param_get_dumpit
  - net/core/devlink.c:devlink_param_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_port_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_get_dumpit
  - net/core/devlink.c:devlink_port_notify
  - net/core/devlink.c:devlink_notify
  - net/core/devlink.c:devlink_get_from_attrs
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81923d11)
Location: net/core/devlink.c:98
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_trap_notify
  - net/core/devlink.c:devlink_trap_group_notify
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_info_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_get_dumpit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_param_get_dumpit
  - net/core/devlink.c:devlink_param_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_port_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_get_dumpit
  - net/core/devlink.c:devlink_port_notify
  - net/core/devlink.c:devlink_notify
  - net/core/devlink.c:devlink_get_from_attrs
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff818ddac1)
Location: net/core/devlink.c:98
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_trap_notify
  - net/core/devlink.c:devlink_trap_group_notify
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_info_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_get_dumpit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_param_get_dumpit
  - net/core/devlink.c:devlink_param_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_port_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_get_dumpit
  - net/core/devlink.c:devlink_port_notify
  - net/core/devlink.c:devlink_notify
  - net/core/devlink.c:devlink_get_from_attrs
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81974ea1)
Location: net/core/devlink.c:98
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_trap_notify
  - net/core/devlink.c:devlink_trap_group_notify
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_info_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_get_dumpit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_param_get_dumpit
  - net/core/devlink.c:devlink_param_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_port_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_get_dumpit
  - net/core/devlink.c:devlink_port_notify
  - net/core/devlink.c:devlink_notify
  - net/core/devlink.c:devlink_get_from_attrs
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81997391)
Location: net/core/devlink.c:98
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_trap_notify
  - net/core/devlink.c:devlink_trap_group_notify
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_info_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_get_dumpit
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_param_get_dumpit
  - net/core/devlink.c:devlink_param_notify
  - net/core/devlink.c:__devlink_flash_update_notify
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_port_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_get_dumpit
  - net/core/devlink.c:devlink_port_notify
  - net/core/devlink.c:devlink_notify
  - net/core/devlink.c:devlink_get_from_attrs
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
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
