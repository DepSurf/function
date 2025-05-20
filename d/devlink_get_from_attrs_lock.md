# Function: <code>devlink_get_from_attrs_lock</code>

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
<summary>In <code>6.5</code>: ✅</summary>

```c
struct devlink *devlink_get_from_attrs_lock(struct net *net, struct nlattr **attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/netlink.c (ffffffff82042720)
Location: net/devlink/netlink.c:86
Inline: False
Direct callers:
  - net/devlink/leftover.c:devlink_nl_cmd_region_read_dumpit
  - net/devlink/netlink.c:devlink_nl_pre_doit
  - net/devlink/health.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
```
**Symbols:**

```
ffffffff82042720-ffffffff82042839: devlink_get_from_attrs_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct devlink *devlink_get_from_attrs_lock(struct net *net, struct nlattr **attrs, bool dev_lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/netlink.c (ffffffff82101850)
Location: net/devlink/netlink.c:181
Inline: False
Direct callers:
  - net/devlink/netlink.c:devlink_nl_dumpit
  - net/devlink/netlink.c:devlink_nl_pre_doit_port_optional
  - net/devlink/netlink.c:devlink_nl_pre_doit_dev_lock
  - net/devlink/netlink.c:devlink_nl_pre_doit_port
  - net/devlink/netlink.c:devlink_nl_pre_doit
  - net/devlink/region.c:devlink_nl_region_read_dumpit
  - net/devlink/health.c:devlink_nl_health_reporter_dump_get_dumpit
```
**Symbols:**

```
ffffffff82101850-ffffffff82101a19: devlink_get_from_attrs_lock (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool dev_lock</code>
</li>
</ul>
</details>
</li>
</ul>
