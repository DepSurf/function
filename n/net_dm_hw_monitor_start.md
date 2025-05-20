# Function: <code>net_dm_hw_monitor_start</code>

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
In net/core/drop_monitor.c (ffffffff81975269)
Location: net/core/drop_monitor.c:971
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
int net_dm_hw_monitor_start(struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffffffff81a49090)
Location: net/core/drop_monitor.c:1001
Inline: False
Direct callers:
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_cmd_trace
```
**Symbols:**

```
ffffffff81a49090-ffffffff81a4918f: net_dm_hw_monitor_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int net_dm_hw_monitor_start(struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffffffff81a4faf0)
Location: net/core/drop_monitor.c:1018
Inline: False
Direct callers:
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_cmd_trace
```
**Symbols:**

```
ffffffff81a4faf0-ffffffff81a4fd22: net_dm_hw_monitor_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int net_dm_hw_monitor_start(struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffffffff81a34900)
Location: net/core/drop_monitor.c:1018
Inline: False
Direct callers:
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_cmd_trace
```
**Symbols:**

```
ffffffff81a34900-ffffffff81a34b63: net_dm_hw_monitor_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int net_dm_hw_monitor_start(struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/drop_monitor.c (0)
Location: net/core/drop_monitor.c:1020
Inline: False
Direct callers:
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_cmd_trace
```
**Symbols:**

```
ffffffff81aea5f0-ffffffff81aea8c0: net_dm_hw_monitor_start (STB_LOCAL)
ffffffff81d38194-ffffffff81d381a8: net_dm_hw_monitor_start.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int net_dm_hw_monitor_start(struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/drop_monitor.c (0)
Location: net/core/drop_monitor.c:1043
Inline: False
Direct callers:
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_cmd_trace
```
**Symbols:**

```
ffffffff81c6cde0-ffffffff81c6d0ae: net_dm_hw_monitor_start (STB_LOCAL)
ffffffff81f04b7d-ffffffff81f04b91: net_dm_hw_monitor_start.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int net_dm_hw_monitor_start(struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/drop_monitor.c (0)
Location: net/core/drop_monitor.c:1031
Inline: False
Direct callers:
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_cmd_trace
```
**Symbols:**

```
ffffffff81e244f0-ffffffff81e247c6: net_dm_hw_monitor_start (STB_LOCAL)
ffffffff820acc55-ffffffff820acc69: net_dm_hw_monitor_start.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int net_dm_hw_monitor_start(struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/drop_monitor.c (0)
Location: net/core/drop_monitor.c:1046
Inline: False
Direct callers:
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_cmd_trace
```
**Symbols:**

```
ffffffff81e99c40-ffffffff81e99f16: net_dm_hw_monitor_start (STB_LOCAL)
ffffffff8212e369-ffffffff8212e37d: net_dm_hw_monitor_start.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int net_dm_hw_monitor_start(struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/drop_monitor.c (0)
Location: net/core/drop_monitor.c:1046
Inline: False
Direct callers:
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_cmd_trace
```
**Symbols:**

```
ffffffff81f5c370-ffffffff81f5c646: net_dm_hw_monitor_start (STB_LOCAL)
ffffffff82210148-ffffffff8221015c: net_dm_hw_monitor_start.cold (STB_LOCAL)
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
In net/core/drop_monitor.c (ffff800010c1b028)
Location: net/core/drop_monitor.c:971
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
In net/core/drop_monitor.c (c0d333b8)
Location: net/core/drop_monitor.c:971
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
In net/core/drop_monitor.c (c000000000d0be50)
Location: net/core/drop_monitor.c:971
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
In net/core/drop_monitor.c (ffffffe00079589a)
Location: net/core/drop_monitor.c:971
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
In net/core/drop_monitor.c (ffffffff81915239)
Location: net/core/drop_monitor.c:971
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
In net/core/drop_monitor.c (ffffffff818cefe9)
Location: net/core/drop_monitor.c:971
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
In net/core/drop_monitor.c (ffffffff81966269)
Location: net/core/drop_monitor.c:971
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
In net/core/drop_monitor.c (ffffffff819884f9)
Location: net/core/drop_monitor.c:971
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
