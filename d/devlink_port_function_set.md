# Function: <code>devlink_port_function_set</code>

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
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a66838)
Location: net/core/devlink.c:1023
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_port_set_doit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int devlink_port_function_set(struct devlink *devlink, struct devlink_port *port, const struct nlattr *attr, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a466f0)
Location: net/core/devlink.c:1109
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_port_set_doit
```
**Symbols:**

```
ffffffff81a466f0-ffffffff81a46951: devlink_port_function_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int devlink_port_function_set(struct devlink_port *port, const struct nlattr *attr, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81b01460)
Location: net/core/devlink.c:1372
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_port_set_doit
```
**Symbols:**

```
ffffffff81b01460-ffffffff81b016c2: devlink_port_function_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int devlink_port_function_set(struct devlink_port *port, const struct nlattr *attr, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81c809f0)
Location: net/core/devlink.c:1600
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_port_set_doit
```
**Symbols:**

```
ffffffff81c809f0-ffffffff81c80c64: devlink_port_function_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int devlink_port_function_set(struct devlink_port *port, const struct nlattr *attr, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81e3d800)
Location: net/core/devlink.c:1834
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_port_set_doit
```
**Symbols:**

```
ffffffff81e3d800-ffffffff81e3dc94: devlink_port_function_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int devlink_port_function_set(struct devlink_port *port, const struct nlattr *attr, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/leftover.c (ffffffff8203d420)
Location: net/devlink/leftover.c:1229
Inline: False
Direct callers:
  - net/devlink/leftover.c:devlink_nl_cmd_port_set_doit
```
**Symbols:**

```
ffffffff8203d420-ffffffff8203d879: devlink_port_function_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int devlink_port_function_set(struct devlink_port *port, const struct nlattr *attr, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/port.c (ffffffff82106e90)
Location: net/devlink/port.c:732
Inline: False
Direct callers:
  - net/devlink/port.c:devlink_nl_port_set_doit
```
**Symbols:**

```
ffffffff82106e90-ffffffff82107193: devlink_port_function_set (STB_LOCAL)
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
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct devlink *devlink</code>
</li>
<li>
<b>Param reordered. </b>
<code>devlink, port, attr, extack</code> ➡️ <code>port, attr, extack</code>
</li>
</ul>
</details>
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
