# Function: <code>devlink_nl_port_fill</code>

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
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int devlink_nl_port_fill(struct sk_buff *msg, struct devlink *devlink, struct devlink_port *devlink_port, enum devlink_command cmd, u32 portid, u32 seq, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:547
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_port_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_port_get_doit
  - net/core/devlink.c:devlink_port_notify
```
**Symbols:**

```
ffffffff8194cb60-ffffffff8194ceb9: devlink_nl_port_fill (STB_LOCAL)
ffffffff81952349-ffffffff8195236c: devlink_nl_port_fill.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int devlink_nl_port_fill(struct sk_buff *msg, struct devlink *devlink, struct devlink_port *devlink_port, enum devlink_command cmd, u32 portid, u32 seq, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff819824c0)
Location: net/core/devlink.c:549
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_port_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_port_get_doit
  - net/core/devlink.c:devlink_port_notify
```
**Symbols:**

```
ffffffff819824c0-ffffffff8198281a: devlink_nl_port_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int devlink_nl_port_fill(struct sk_buff *msg, struct devlink *devlink, struct devlink_port *devlink_port, enum devlink_command cmd, u32 portid, u32 seq, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a5a730)
Location: net/core/devlink.c:566
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_port_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_port_get_doit
  - net/core/devlink.c:devlink_port_notify
```
**Symbols:**

```
ffffffff81a5a730-ffffffff81a5a95f: devlink_nl_port_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int devlink_nl_port_fill(struct sk_buff *msg, struct devlink *devlink, struct devlink_port *devlink_port, enum devlink_command cmd, u32 portid, u32 seq, int flags, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:758
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_port_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_port_get_doit
  - net/core/devlink.c:devlink_port_notify
```
**Symbols:**

```
ffffffff81a65f70-ffffffff81a66212: devlink_nl_port_fill (STB_LOCAL)
ffffffff81c31f9b-ffffffff81c31fb3: devlink_nl_port_fill.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int devlink_nl_port_fill(struct sk_buff *msg, struct devlink *devlink, struct devlink_port *devlink_port, enum devlink_command cmd, u32 portid, u32 seq, int flags, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:832
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_port_new_doit
  - net/core/devlink.c:devlink_nl_cmd_port_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_port_get_doit
  - net/core/devlink.c:devlink_port_notify
```
**Symbols:**

```
ffffffff81a45d90-ffffffff81a46248: devlink_nl_port_fill (STB_LOCAL)
ffffffff81c24236-ffffffff81c2424e: devlink_nl_port_fill.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int devlink_nl_port_fill(struct sk_buff *msg, struct devlink_port *devlink_port, enum devlink_command cmd, u32 portid, u32 seq, int flags, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:977
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_port_new_doit
  - net/core/devlink.c:devlink_nl_cmd_port_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_port_get_doit
  - net/core/devlink.c:devlink_port_notify
```
**Symbols:**

```
ffffffff81b00ca0-ffffffff81b00f40: devlink_nl_port_fill (STB_LOCAL)
ffffffff81d38a2a-ffffffff81d38a42: devlink_nl_port_fill.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int devlink_nl_port_fill(struct sk_buff *msg, struct devlink_port *devlink_port, enum devlink_command cmd, u32 portid, u32 seq, int flags, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:1195
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_port_new_doit
  - net/core/devlink.c:devlink_nl_cmd_port_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_port_get_doit
  - net/core/devlink.c:devlink_port_notify
```
**Symbols:**

```
ffffffff81c80330-ffffffff81c8060a: devlink_nl_port_fill (STB_LOCAL)
ffffffff81f05164-ffffffff81f0517c: devlink_nl_port_fill.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int devlink_nl_port_fill(struct sk_buff *msg, struct devlink_port *devlink_port, enum devlink_command cmd, u32 portid, u32 seq, int flags, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:1428
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_port_new_doit
  - net/core/devlink.c:devlink_nl_cmd_port_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_port_get_doit
  - net/core/devlink.c:devlink_port_notify
```
**Symbols:**

```
ffffffff81e3cdd0-ffffffff81e3d445: devlink_nl_port_fill (STB_LOCAL)
ffffffff820ad26b-ffffffff820ad2af: devlink_nl_port_fill.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int devlink_nl_port_fill(struct sk_buff *msg, struct devlink_port *devlink_port, enum devlink_command cmd, u32 portid, u32 seq, int flags, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/devlink/leftover.c (0)
Location: net/devlink/leftover.c:895
Inline: False
Direct callers:
  - net/devlink/leftover.c:devlink_nl_cmd_port_new_doit
  - net/devlink/leftover.c:devlink_nl_cmd_port_get_dump_one
  - net/devlink/leftover.c:devlink_nl_cmd_port_get_doit
  - net/devlink/leftover.c:devlink_port_notify
```
**Symbols:**

```
ffffffff8203c990-ffffffff8203ced7: devlink_nl_port_fill (STB_LOCAL)
ffffffff8213659d-ffffffff821365b1: devlink_nl_port_fill.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int devlink_nl_port_fill(struct sk_buff *msg, struct devlink_port *devlink_port, enum devlink_command cmd, u32 portid, u32 seq, int flags, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/port.c (ffffffff821067a0)
Location: net/devlink/port.c:446
Inline: False
Direct callers:
  - net/devlink/port.c:devlink_nl_port_new_doit
  - net/devlink/port.c:devlink_nl_port_get_dump_one
  - net/devlink/port.c:devlink_nl_port_get_doit
  - net/devlink/port.c:devlink_port_notify
```
**Symbols:**

```
ffffffff821067a0-ffffffff82106ace: devlink_nl_port_fill (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int devlink_nl_port_fill(struct sk_buff *msg, struct devlink *devlink, struct devlink_port *devlink_port, enum devlink_command cmd, u32 portid, u32 seq, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffff800010c2a550)
Location: net/core/devlink.c:549
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_port_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_port_get_doit
  - net/core/devlink.c:devlink_port_notify
```
**Symbols:**

```
ffff800010c2a550-ffff800010c2a908: devlink_nl_port_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int devlink_nl_port_fill(struct sk_buff *msg, struct devlink *devlink, struct devlink_port *devlink_port, enum devlink_command cmd, u32 portid, u32 seq, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c0d41a10)
Location: net/core/devlink.c:549
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_port_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_port_get_doit
  - net/core/devlink.c:devlink_port_notify
```
**Symbols:**

```
c0d41a10-c0d41d60: devlink_nl_port_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int devlink_nl_port_fill(struct sk_buff *msg, struct devlink *devlink, struct devlink_port *devlink_port, enum devlink_command cmd, u32 portid, u32 seq, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c000000000d1f860)
Location: net/core/devlink.c:549
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_port_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_port_get_doit
  - net/core/devlink.c:devlink_port_notify
```
**Symbols:**

```
c000000000d1f860-c000000000d1fcac: devlink_nl_port_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int devlink_nl_port_fill(struct sk_buff *msg, struct devlink *devlink, struct devlink_port *devlink_port, enum devlink_command cmd, u32 portid, u32 seq, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffe0007a1d58)
Location: net/core/devlink.c:549
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_port_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_port_get_doit
  - net/core/devlink.c:devlink_port_notify
```
**Symbols:**

```
ffffffe0007a1d58-ffffffe0007a1ff6: devlink_nl_port_fill (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int devlink_nl_port_fill(struct sk_buff *msg, struct devlink *devlink, struct devlink_port *devlink_port, enum devlink_command cmd, u32 portid, u32 seq, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81922330)
Location: net/core/devlink.c:549
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_port_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_port_get_doit
  - net/core/devlink.c:devlink_port_notify
```
**Symbols:**

```
ffffffff81922330-ffffffff8192268a: devlink_nl_port_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int devlink_nl_port_fill(struct sk_buff *msg, struct devlink *devlink, struct devlink_port *devlink_port, enum devlink_command cmd, u32 portid, u32 seq, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff818dc0e0)
Location: net/core/devlink.c:549
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_port_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_port_get_doit
  - net/core/devlink.c:devlink_port_notify
```
**Symbols:**

```
ffffffff818dc0e0-ffffffff818dc43a: devlink_nl_port_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int devlink_nl_port_fill(struct sk_buff *msg, struct devlink *devlink, struct devlink_port *devlink_port, enum devlink_command cmd, u32 portid, u32 seq, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff819734c0)
Location: net/core/devlink.c:549
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_port_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_port_get_doit
  - net/core/devlink.c:devlink_port_notify
```
**Symbols:**

```
ffffffff819734c0-ffffffff8197381a: devlink_nl_port_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int devlink_nl_port_fill(struct sk_buff *msg, struct devlink *devlink, struct devlink_port *devlink_port, enum devlink_command cmd, u32 portid, u32 seq, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff819959b0)
Location: net/core/devlink.c:549
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_port_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_port_get_doit
  - net/core/devlink.c:devlink_port_notify
```
**Symbols:**

```
ffffffff819959b0-ffffffff81995d0a: devlink_nl_port_fill (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct netlink_ext_ack *extack</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
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
<code>msg, devlink, devlink_port, cmd, portid, seq, flags, extack</code> ➡️ <code>msg, devlink_port, cmd, portid, seq, flags, extack</code>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
