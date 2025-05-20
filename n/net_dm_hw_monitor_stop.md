# Function: <code>net_dm_hw_monitor_stop</code>

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
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffffffff819751fc)
Location: net/core/drop_monitor.c:1003
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_trace
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void net_dm_hw_monitor_stop(struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffffffff81a49e90)
Location: net/core/drop_monitor.c:1033
Inline: False
Direct callers:
  - net/core/drop_monitor.c:net_dm_cmd_trace
```
**Symbols:**

```
ffffffff81a49e90-ffffffff81a49fcb: net_dm_hw_monitor_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void net_dm_hw_monitor_stop(struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffffffff81a4f980)
Location: net/core/drop_monitor.c:1074
Inline: False
Direct callers:
  - net/core/drop_monitor.c:net_dm_cmd_trace
```
**Symbols:**

```
ffffffff81a4f980-ffffffff81a4fae7: net_dm_hw_monitor_stop (STB_LOCAL)
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
In net/core/drop_monitor.c (ffffffff81a34bcd)
Location: net/core/drop_monitor.c:1074
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_trace
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void net_dm_hw_monitor_stop(struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/drop_monitor.c (0)
Location: net/core/drop_monitor.c:1076
Inline: False
Direct callers:
  - net/core/drop_monitor.c:net_dm_cmd_trace
```
**Symbols:**

```
ffffffff81aea410-ffffffff81aea5e5: net_dm_hw_monitor_stop (STB_LOCAL)
ffffffff81d3817f-ffffffff81d38194: net_dm_hw_monitor_stop.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void net_dm_hw_monitor_stop(struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/drop_monitor.c (0)
Location: net/core/drop_monitor.c:1099
Inline: False
Direct callers:
  - net/core/drop_monitor.c:net_dm_cmd_trace
```
**Symbols:**

```
ffffffff81c6cbf0-ffffffff81c6cdd2: net_dm_hw_monitor_stop (STB_LOCAL)
ffffffff81f04b68-ffffffff81f04b7d: net_dm_hw_monitor_stop.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void net_dm_hw_monitor_stop(struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/drop_monitor.c (0)
Location: net/core/drop_monitor.c:1087
Inline: False
Direct callers:
  - net/core/drop_monitor.c:net_dm_cmd_trace
```
**Symbols:**

```
ffffffff81e247e0-ffffffff81e249d2: net_dm_hw_monitor_stop (STB_LOCAL)
ffffffff820acc69-ffffffff820acc7e: net_dm_hw_monitor_stop.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void net_dm_hw_monitor_stop(struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/drop_monitor.c (0)
Location: net/core/drop_monitor.c:1102
Inline: False
Direct callers:
  - net/core/drop_monitor.c:net_dm_cmd_trace
```
**Symbols:**

```
ffffffff81e99a30-ffffffff81e99c22: net_dm_hw_monitor_stop (STB_LOCAL)
ffffffff8212e354-ffffffff8212e369: net_dm_hw_monitor_stop.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void net_dm_hw_monitor_stop(struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/drop_monitor.c (0)
Location: net/core/drop_monitor.c:1102
Inline: False
Direct callers:
  - net/core/drop_monitor.c:net_dm_cmd_trace
```
**Symbols:**

```
ffffffff81f5c160-ffffffff81f5c352: net_dm_hw_monitor_stop (STB_LOCAL)
ffffffff82210133-ffffffff82210148: net_dm_hw_monitor_stop.cold (STB_LOCAL)
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
In net/core/drop_monitor.c (ffff800010c1afbc)
Location: net/core/drop_monitor.c:1003
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_trace
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
In net/core/drop_monitor.c (c0d33348)
Location: net/core/drop_monitor.c:1003
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_trace
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
In net/core/drop_monitor.c (c000000000d0bc78)
Location: net/core/drop_monitor.c:1003
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_trace
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
In net/core/drop_monitor.c (ffffffe00079587a)
Location: net/core/drop_monitor.c:1003
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_trace
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
In net/core/drop_monitor.c (ffffffff819151cc)
Location: net/core/drop_monitor.c:1003
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_trace
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
In net/core/drop_monitor.c (ffffffff818cef7c)
Location: net/core/drop_monitor.c:1003
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_trace
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
In net/core/drop_monitor.c (ffffffff819661fc)
Location: net/core/drop_monitor.c:1003
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_trace
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
In net/core/drop_monitor.c (ffffffff8198848c)
Location: net/core/drop_monitor.c:1003
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_trace
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
