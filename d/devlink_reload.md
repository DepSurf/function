# Function: <code>devlink_reload</code>

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
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int devlink_reload(struct devlink *devlink, struct net *dest_net, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a5d970)
Location: net/core/devlink.c:2795
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_pernet_pre_exit
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_nl_cmd_reload
```
**Symbols:**

```
ffffffff81a5d970-ffffffff81a5da9a: devlink_reload (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int devlink_reload(struct devlink *devlink, struct net *dest_net, enum devlink_reload_action action, enum devlink_reload_limit limit, u32 *actions_performed, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a671c0)
Location: net/core/devlink.c:3179
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_pernet_pre_exit
  - net/core/devlink.c:devlink_nl_cmd_reload
```
**Symbols:**

```
ffffffff81a671c0-ffffffff81a673ae: devlink_reload (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int devlink_reload(struct devlink *devlink, struct net *dest_net, enum devlink_reload_action action, enum devlink_reload_limit limit, u32 *actions_performed, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a4a3b0)
Location: net/core/devlink.c:3382
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_pernet_pre_exit
  - net/core/devlink.c:devlink_nl_cmd_reload
```
**Symbols:**

```
ffffffff81a4a3b0-ffffffff81a4a59e: devlink_reload (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int devlink_reload(struct devlink *devlink, struct net *dest_net, enum devlink_reload_action action, enum devlink_reload_limit limit, u32 *actions_performed, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:3947
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_pernet_pre_exit
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_nl_cmd_reload
```
**Symbols:**

```
ffffffff81b024e0-ffffffff81b0274a: devlink_reload (STB_LOCAL)
ffffffff81d38a61-ffffffff81d38a7a: devlink_reload.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int devlink_reload(struct devlink *devlink, struct net *dest_net, enum devlink_reload_action action, enum devlink_reload_limit limit, u32 *actions_performed, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:4462
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_pernet_pre_exit
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_nl_cmd_reload
```
**Symbols:**

```
ffffffff81c86080-ffffffff81c86306: devlink_reload (STB_LOCAL)
ffffffff81f0530e-ffffffff81f05327: devlink_reload.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int devlink_reload(struct devlink *devlink, struct net *dest_net, enum devlink_reload_action action, enum devlink_reload_limit limit, u32 *actions_performed, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:4728
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_pernet_pre_exit
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_nl_cmd_reload
```
**Symbols:**

```
ffffffff81e401c0-ffffffff81e40425: devlink_reload (STB_LOCAL)
ffffffff820ad318-ffffffff820ad331: devlink_reload.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int devlink_reload(struct devlink *devlink, struct net *dest_net, enum devlink_reload_action action, enum devlink_reload_limit limit, u32 *actions_performed, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/devlink/dev.c (0)
Location: net/devlink/dev.c:350
Inline: False
Direct callers:
  - net/devlink/core.c:devlink_pernet_pre_exit
  - net/devlink/dev.c:devlink_nl_cmd_reload
  - net/devlink/dev.c:devlink_nl_cmd_reload
```
**Symbols:**

```
ffffffff82136675-ffffffff82136699: devlink_reload.cold (STB_LOCAL)
ffffffff82044680-ffffffff82044835: devlink_reload (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int devlink_reload(struct devlink *devlink, struct net *dest_net, enum devlink_reload_action action, enum devlink_reload_limit limit, u32 *actions_performed, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/devlink/dev.c (0)
Location: net/devlink/dev.c:442
Inline: False
Direct callers:
  - net/devlink/core.c:devlink_pernet_pre_exit
  - net/devlink/dev.c:devlink_nl_reload_doit
  - net/devlink/dev.c:devlink_nl_reload_doit
```
**Symbols:**

```
ffffffff82217fce-ffffffff82217ff2: devlink_reload.cold (STB_LOCAL)
ffffffff82103e90-ffffffff821040f7: devlink_reload (STB_GLOBAL)
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
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum devlink_reload_action action</code>
</li>
<li>
<b>Param added. </b>
<code>enum devlink_reload_limit limit</code>
</li>
<li>
<b>Param added. </b>
<code>u32 *actions_performed</code>
</li>
<li>
<b>Param reordered. </b>
<code>devlink, dest_net, extack</code> ➡️ <code>devlink, dest_net, action, limit, actions_performed, extack</code>
</li>
</ul>
</details>
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
