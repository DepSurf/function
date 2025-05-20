# Function: <code>net_dm_packet_report</code>

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
In net/core/drop_monitor.c (ffffffff819762f5)
Location: net/core/drop_monitor.c:651
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_packet_work
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void net_dm_packet_report(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffffffff81a4af40)
Location: net/core/drop_monitor.c:655
Inline: False
Direct callers:
  - net/core/drop_monitor.c:net_dm_packet_work
```
**Symbols:**

```
ffffffff81a4af40-ffffffff81a4b051: net_dm_packet_report (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void net_dm_packet_report(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffffffff81a50b80)
Location: net/core/drop_monitor.c:661
Inline: False
Direct callers:
  - net/core/drop_monitor.c:net_dm_packet_work
```
**Symbols:**

```
ffffffff81a50b80-ffffffff81a50c90: net_dm_packet_report (STB_LOCAL)
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
In net/core/drop_monitor.c (ffffffff81a35c31)
Location: net/core/drop_monitor.c:661
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_packet_work
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffffffff81aeb801)
Location: net/core/drop_monitor.c:665
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_packet_work
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffffffff81c6e11c)
Location: net/core/drop_monitor.c:686
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_packet_work
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
In net/core/drop_monitor.c (ffffffff81e25d9d)
Location: net/core/drop_monitor.c:673
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_packet_work
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
In net/core/drop_monitor.c (ffffffff81e9b340)
Location: net/core/drop_monitor.c:690
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_packet_work
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffffffff81f5daaa)
Location: net/core/drop_monitor.c:690
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_packet_work
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
In net/core/drop_monitor.c (ffff800010c1c530)
Location: net/core/drop_monitor.c:651
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_packet_work
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
In net/core/drop_monitor.c (c0d3462c)
Location: net/core/drop_monitor.c:651
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_packet_work
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
In net/core/drop_monitor.c (c000000000d0d3bc)
Location: net/core/drop_monitor.c:651
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_packet_work
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
In net/core/drop_monitor.c (ffffffe0007964e2)
Location: net/core/drop_monitor.c:651
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_packet_work
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
In net/core/drop_monitor.c (ffffffff819162c5)
Location: net/core/drop_monitor.c:651
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_packet_work
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
In net/core/drop_monitor.c (ffffffff818d0075)
Location: net/core/drop_monitor.c:651
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_packet_work
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
In net/core/drop_monitor.c (ffffffff819672f5)
Location: net/core/drop_monitor.c:651
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_packet_work
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
In net/core/drop_monitor.c (ffffffff81989585)
Location: net/core/drop_monitor.c:651
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_packet_work
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
</ul>
