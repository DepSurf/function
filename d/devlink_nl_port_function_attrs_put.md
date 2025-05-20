# Function: <code>devlink_nl_port_function_attrs_put</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int devlink_nl_port_function_attrs_put(struct sk_buff *msg, struct devlink_port *port, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a5dea0)
Location: net/core/devlink.c:716
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_port_fill
```
**Symbols:**

```
ffffffff81a5dea0-ffffffff81a5dfbc: devlink_nl_port_function_attrs_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a45ee3)
Location: net/core/devlink.c:804
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_port_fill
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int devlink_nl_port_function_attrs_put(struct sk_buff *msg, struct devlink_port *port, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81af6310)
Location: net/core/devlink.c:951
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_port_fill
```
**Symbols:**

```
ffffffff81af6310-ffffffff81af6538: devlink_nl_port_function_attrs_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int devlink_nl_port_function_attrs_put(struct sk_buff *msg, struct devlink_port *port, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81c79520)
Location: net/core/devlink.c:1169
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_port_fill
```
**Symbols:**

```
ffffffff81c79520-ffffffff81c7976e: devlink_nl_port_function_attrs_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81e3cf21)
Location: net/core/devlink.c:1398
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_port_fill
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/devlink/leftover.c (ffffffff8203cadf)
Location: net/devlink/leftover.c:869
Inline: True
Inline callers:
  - net/devlink/leftover.c:devlink_nl_port_fill
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int devlink_nl_port_function_attrs_put(struct sk_buff *msg, struct devlink_port *port, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/devlink/port.c (0)
Location: net/devlink/port.c:413
Inline: False
Direct callers:
  - net/devlink/port.c:devlink_nl_port_fill
```
**Symbols:**

```
ffffffff821064f0-ffffffff82106781: devlink_nl_port_function_attrs_put (STB_LOCAL)
ffffffff82218087-ffffffff8221809c: devlink_nl_port_function_attrs_put.cold (STB_LOCAL)
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
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
</ul>
