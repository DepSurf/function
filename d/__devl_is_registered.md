# Function: <code>__devl_is_registered</code>

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
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/devlink/core.c (ffffffff82101298)
Location: net/devlink/devl_internal.h:94
Inline: True
Inline callers:
  - net/devlink/core.c:devlink_pernet_pre_exit
  - net/devlink/core.c:devlink_rel_nested_in_notify_work
```
```
In net/devlink/netlink.c (ffffffff82101d69)
Location: net/devlink/devl_internal.h:94
Inline: True
Inline callers:
  - net/devlink/netlink.c:devlink_nl_dumpit
  - net/devlink/netlink.c:devlink_get_from_attrs_lock
```
```
In net/devlink/dev.c (ffffffff82104eda)
Location: net/devlink/devl_internal.h:94
Inline: True
Inline callers:
  - net/devlink/dev.c:devlink_compat_flash_update
  - net/devlink/dev.c:devlink_compat_running_version
```
```
In net/devlink/port.c (ffffffff82106c40)
Location: net/devlink/devl_internal.h:94
Inline: True
Inline callers:
  - net/devlink/port.c:devlink_port_notify
```
```
In net/devlink/param.c (ffffffff8210e350)
Location: net/devlink/devl_internal.h:94
Inline: True
```
```
In net/devlink/region.c (ffffffff8210fd6a)
Location: net/devlink/devl_internal.h:94
Inline: True
Inline callers:
  - net/devlink/region.c:devlink_nl_region_notify
```
```
In net/devlink/trap.c (ffffffff82114de0)
Location: net/devlink/devl_internal.h:94
Inline: True
```
```
In net/devlink/rate.c (ffffffff82118ac4)
Location: net/devlink/devl_internal.h:94
Inline: True
Inline callers:
  - net/devlink/rate.c:devlink_rate_notify
```
```
In net/devlink/linecard.c (ffffffff82119c68)
Location: net/devlink/devl_internal.h:94
Inline: True
Inline callers:
  - net/devlink/linecard.c:devlink_linecard_notify
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
