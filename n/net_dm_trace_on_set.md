# Function: <code>net_dm_trace_on_set</code>

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
In net/core/drop_monitor.c (ffffffff81975362)
Location: net/core/drop_monitor.c:1037
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
int net_dm_trace_on_set(struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffffffff81a49620)
Location: net/core/drop_monitor.c:1067
Inline: False
Direct callers:
  - net/core/drop_monitor.c:net_dm_cmd_trace
```
**Symbols:**

```
ffffffff81a49620-ffffffff81a49774: net_dm_trace_on_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int net_dm_trace_on_set(struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffffffff81a4f660)
Location: net/core/drop_monitor.c:1108
Inline: False
Direct callers:
  - net/core/drop_monitor.c:net_dm_cmd_trace
```
**Symbols:**

```
ffffffff81a4f660-ffffffff81a4f858: net_dm_trace_on_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int net_dm_trace_on_set(struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffffffff81a34680)
Location: net/core/drop_monitor.c:1108
Inline: False
Direct callers:
  - net/core/drop_monitor.c:net_dm_cmd_trace
```
**Symbols:**

```
ffffffff81a34680-ffffffff81a348a6: net_dm_trace_on_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int net_dm_trace_on_set(struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffffffff81aea130)
Location: net/core/drop_monitor.c:1110
Inline: False
Direct callers:
  - net/core/drop_monitor.c:net_dm_cmd_trace
```
**Symbols:**

```
ffffffff81aea130-ffffffff81aea3bb: net_dm_trace_on_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int net_dm_trace_on_set(struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffffffff81c6c8f0)
Location: net/core/drop_monitor.c:1133
Inline: False
Direct callers:
  - net/core/drop_monitor.c:net_dm_cmd_trace
```
**Symbols:**

```
ffffffff81c6c8f0-ffffffff81c6cb75: net_dm_trace_on_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int net_dm_trace_on_set(struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffffffff81e249f0)
Location: net/core/drop_monitor.c:1121
Inline: False
Direct callers:
  - net/core/drop_monitor.c:net_dm_cmd_trace
```
**Symbols:**

```
ffffffff81e249f0-ffffffff81e24c88: net_dm_trace_on_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int net_dm_trace_on_set(struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffffffff81e99f30)
Location: net/core/drop_monitor.c:1136
Inline: False
Direct callers:
  - net/core/drop_monitor.c:net_dm_cmd_trace
```
**Symbols:**

```
ffffffff81e99f30-ffffffff81e9a1c8: net_dm_trace_on_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int net_dm_trace_on_set(struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffffffff81f5c660)
Location: net/core/drop_monitor.c:1136
Inline: False
Direct callers:
  - net/core/drop_monitor.c:net_dm_cmd_trace
```
**Symbols:**

```
ffffffff81f5c660-ffffffff81f5c8f8: net_dm_trace_on_set (STB_LOCAL)
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
In net/core/drop_monitor.c (ffff800010c1b15c)
Location: net/core/drop_monitor.c:1037
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
In net/core/drop_monitor.c (c0d334ec)
Location: net/core/drop_monitor.c:1037
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
In net/core/drop_monitor.c (c000000000d0bce0)
Location: net/core/drop_monitor.c:1037
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
In net/core/drop_monitor.c (ffffffe0007958ae)
Location: net/core/drop_monitor.c:1037
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
In net/core/drop_monitor.c (ffffffff81915332)
Location: net/core/drop_monitor.c:1037
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
In net/core/drop_monitor.c (ffffffff818cf0e2)
Location: net/core/drop_monitor.c:1037
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
In net/core/drop_monitor.c (ffffffff81966362)
Location: net/core/drop_monitor.c:1037
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
In net/core/drop_monitor.c (ffffffff819885f2)
Location: net/core/drop_monitor.c:1037
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
