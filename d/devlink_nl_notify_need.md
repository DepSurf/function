# Function: <code>devlink_nl_notify_need</code>

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
In net/devlink/dev.c (ffffffff821032fe)
Location: net/devlink/devl_internal.h:188
Inline: True
```
```
In net/devlink/port.c (ffffffff82106c8a)
Location: net/devlink/devl_internal.h:188
Inline: True
Inline callers:
  - net/devlink/port.c:devlink_port_notify
```
```
In net/devlink/param.c (ffffffff8210e3a4)
Location: net/devlink/devl_internal.h:188
Inline: True
```
```
In net/devlink/region.c (ffffffff8210fdb3)
Location: net/devlink/devl_internal.h:188
Inline: True
Inline callers:
  - net/devlink/region.c:devlink_nl_region_notify
```
```
In net/devlink/health.c (ffffffff82113a0c)
Location: net/devlink/devl_internal.h:188
Inline: True
```
```
In net/devlink/trap.c (ffffffff82114e34)
Location: net/devlink/devl_internal.h:188
Inline: True
```
```
In net/devlink/rate.c (ffffffff82118b1a)
Location: net/devlink/devl_internal.h:188
Inline: True
Inline callers:
  - net/devlink/rate.c:devlink_rate_notify
```
```
In net/devlink/linecard.c (ffffffff82119cb2)
Location: net/devlink/devl_internal.h:188
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
