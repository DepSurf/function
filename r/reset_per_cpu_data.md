# Function: <code>reset_per_cpu_data</code>

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
<summary>In <code>5.4</code>: ✅</summary>

```c
struct sk_buff *reset_per_cpu_data(struct per_cpu_dm_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffffffff81974c40)
Location: net/core/drop_monitor.c:129
Inline: False
Direct callers:
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:send_dm_alert
```
**Symbols:**

```
ffffffff81974c40-ffffffff81974d2e: reset_per_cpu_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct sk_buff *reset_per_cpu_data(struct per_cpu_dm_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffffffff81a49520)
Location: net/core/drop_monitor.c:130
Inline: False
Direct callers:
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:send_dm_alert
```
**Symbols:**

```
ffffffff81a49520-ffffffff81a49619: reset_per_cpu_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct sk_buff *reset_per_cpu_data(struct per_cpu_dm_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffffffff81a4ee50)
Location: net/core/drop_monitor.c:132
Inline: False
Direct callers:
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:send_dm_alert
```
**Symbols:**

```
ffffffff81a4ee50-ffffffff81a4ef49: reset_per_cpu_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct sk_buff *reset_per_cpu_data(struct per_cpu_dm_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffffffff81a33e90)
Location: net/core/drop_monitor.c:132
Inline: False
Direct callers:
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:send_dm_alert
```
**Symbols:**

```
ffffffff81a33e90-ffffffff81a33f89: reset_per_cpu_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct sk_buff *reset_per_cpu_data(struct per_cpu_dm_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffffffff81ae9980)
Location: net/core/drop_monitor.c:132
Inline: False
Direct callers:
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:send_dm_alert
```
**Symbols:**

```
ffffffff81ae9980-ffffffff81ae9a79: reset_per_cpu_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct sk_buff *reset_per_cpu_data(struct per_cpu_dm_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffffffff81c6c1d0)
Location: net/core/drop_monitor.c:143
Inline: False
Direct callers:
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:send_dm_alert
```
**Symbols:**

```
ffffffff81c6c1d0-ffffffff81c6c2db: reset_per_cpu_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct sk_buff *reset_per_cpu_data(struct per_cpu_dm_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffffffff81e23ba0)
Location: net/core/drop_monitor.c:130
Inline: False
Direct callers:
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:send_dm_alert
```
**Symbols:**

```
ffffffff81e23ba0-ffffffff81e23cb7: reset_per_cpu_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct sk_buff *reset_per_cpu_data(struct per_cpu_dm_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffffffff81e98f10)
Location: net/core/drop_monitor.c:132
Inline: False
Direct callers:
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:send_dm_alert
```
**Symbols:**

```
ffffffff81e98f10-ffffffff81e99027: reset_per_cpu_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct sk_buff *reset_per_cpu_data(struct per_cpu_dm_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffffffff81f5b5d0)
Location: net/core/drop_monitor.c:132
Inline: False
Direct callers:
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:send_dm_alert
```
**Symbols:**

```
ffffffff81f5b5d0-ffffffff81f5b6e7: reset_per_cpu_data (STB_LOCAL)
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
struct sk_buff *reset_per_cpu_data(struct per_cpu_dm_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffff800010c1ae30)
Location: net/core/drop_monitor.c:129
Inline: False
Direct callers:
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:send_dm_alert
```
**Symbols:**

```
ffff800010c1ae30-ffff800010c1af6c: reset_per_cpu_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct sk_buff *reset_per_cpu_data(struct per_cpu_dm_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (c0d32d14)
Location: net/core/drop_monitor.c:129
Inline: False
Direct callers:
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:send_dm_alert
```
**Symbols:**

```
c0d32d14-c0d32e04: reset_per_cpu_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct sk_buff *reset_per_cpu_data(struct per_cpu_dm_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (c000000000d0b200)
Location: net/core/drop_monitor.c:129
Inline: False
Direct callers:
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:send_dm_alert
```
**Symbols:**

```
c000000000d0b200-c000000000d0b350: reset_per_cpu_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct sk_buff *reset_per_cpu_data(struct per_cpu_dm_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffffffe000795208)
Location: net/core/drop_monitor.c:129
Inline: False
Direct callers:
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:send_dm_alert
```
**Symbols:**

```
ffffffe000795208-ffffffe0007952de: reset_per_cpu_data (STB_LOCAL)
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
struct sk_buff *reset_per_cpu_data(struct per_cpu_dm_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffffffff81914c10)
Location: net/core/drop_monitor.c:129
Inline: False
Direct callers:
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:send_dm_alert
```
**Symbols:**

```
ffffffff81914c10-ffffffff81914cfe: reset_per_cpu_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct sk_buff *reset_per_cpu_data(struct per_cpu_dm_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffffffff818ce9d0)
Location: net/core/drop_monitor.c:129
Inline: False
Direct callers:
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:send_dm_alert
```
**Symbols:**

```
ffffffff818ce9d0-ffffffff818ceabe: reset_per_cpu_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct sk_buff *reset_per_cpu_data(struct per_cpu_dm_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffffffff81965c40)
Location: net/core/drop_monitor.c:129
Inline: False
Direct callers:
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:send_dm_alert
```
**Symbols:**

```
ffffffff81965c40-ffffffff81965d2e: reset_per_cpu_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct sk_buff *reset_per_cpu_data(struct per_cpu_dm_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffffffff81987e80)
Location: net/core/drop_monitor.c:129
Inline: False
Direct callers:
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:send_dm_alert
```
**Symbols:**

```
ffffffff81987e80-ffffffff81987f6e: reset_per_cpu_data (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
