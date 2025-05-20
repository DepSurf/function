# Function: <code>net_dm_packet_report_fill</code>

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
In net/core/drop_monitor.c (ffffffff819760ca)
Location: net/core/drop_monitor.c:592
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_packet_work
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int net_dm_packet_report_fill(struct sk_buff *msg, struct sk_buff *skb, size_t payload_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/drop_monitor.c (0)
Location: net/core/drop_monitor.c:596
Inline: False
Direct callers:
  - net/core/drop_monitor.c:net_dm_packet_report
```
**Symbols:**

```
ffffffff81a4ad00-ffffffff81a4af3d: net_dm_packet_report_fill (STB_LOCAL)
ffffffff81a4b385-ffffffff81a4b39d: net_dm_packet_report_fill.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int net_dm_packet_report_fill(struct sk_buff *msg, struct sk_buff *skb, size_t payload_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/drop_monitor.c (0)
Location: net/core/drop_monitor.c:602
Inline: False
Direct callers:
  - net/core/drop_monitor.c:net_dm_packet_report
```
**Symbols:**

```
ffffffff81a50940-ffffffff81a50b7d: net_dm_packet_report_fill (STB_LOCAL)
ffffffff81c31e83-ffffffff81c31e9b: net_dm_packet_report_fill.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int net_dm_packet_report_fill(struct sk_buff *msg, struct sk_buff *skb, size_t payload_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/drop_monitor.c (0)
Location: net/core/drop_monitor.c:602
Inline: False
Direct callers:
  - net/core/drop_monitor.c:net_dm_packet_work
```
**Symbols:**

```
ffffffff81a35850-ffffffff81a35a91: net_dm_packet_report_fill (STB_LOCAL)
ffffffff81c2414c-ffffffff81c24164: net_dm_packet_report_fill.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int net_dm_packet_report_fill(struct sk_buff *msg, struct sk_buff *skb, size_t payload_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/drop_monitor.c (0)
Location: net/core/drop_monitor.c:606
Inline: False
Direct callers:
  - net/core/drop_monitor.c:net_dm_packet_work
```
**Symbols:**

```
ffffffff81aeb420-ffffffff81aeb661: net_dm_packet_report_fill (STB_LOCAL)
ffffffff81d381c0-ffffffff81d381d8: net_dm_packet_report_fill.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int net_dm_packet_report_fill(struct sk_buff *msg, struct sk_buff *skb, size_t payload_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/drop_monitor.c (0)
Location: net/core/drop_monitor.c:622
Inline: False
Direct callers:
  - net/core/drop_monitor.c:net_dm_packet_work
```
**Symbols:**

```
ffffffff81c6dc90-ffffffff81c6df5d: net_dm_packet_report_fill (STB_LOCAL)
ffffffff81f04ba9-ffffffff81f04bc1: net_dm_packet_report_fill.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int net_dm_packet_report_fill(struct sk_buff *msg, struct sk_buff *skb, size_t payload_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffffffff81e25910)
Location: net/core/drop_monitor.c:609
Inline: False
Direct callers:
  - net/core/drop_monitor.c:net_dm_packet_work
```
**Symbols:**

```
ffffffff81e25910-ffffffff81e25bd7: net_dm_packet_report_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int net_dm_packet_report_fill(struct sk_buff *msg, struct sk_buff *skb, size_t payload_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffffffff81e9ae50)
Location: net/core/drop_monitor.c:609
Inline: False
Direct callers:
  - net/core/drop_monitor.c:net_dm_packet_work
```
**Symbols:**

```
ffffffff81e9ae50-ffffffff81e9b19e: net_dm_packet_report_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int net_dm_packet_report_fill(struct sk_buff *msg, struct sk_buff *skb, size_t payload_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffffffff81f5d5b0)
Location: net/core/drop_monitor.c:609
Inline: False
Direct callers:
  - net/core/drop_monitor.c:net_dm_packet_work
```
**Symbols:**

```
ffffffff81f5d5b0-ffffffff81f5d8fe: net_dm_packet_report_fill (STB_LOCAL)
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
In net/core/drop_monitor.c (ffff800010c1c5ac)
Location: net/core/drop_monitor.c:592
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
In net/core/drop_monitor.c (c0d3440c)
Location: net/core/drop_monitor.c:592
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
In net/core/drop_monitor.c (c000000000d0d454)
Location: net/core/drop_monitor.c:592
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
In net/core/drop_monitor.c (ffffffe00079658a)
Location: net/core/drop_monitor.c:592
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
In net/core/drop_monitor.c (ffffffff8191609a)
Location: net/core/drop_monitor.c:592
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
In net/core/drop_monitor.c (ffffffff818cfe4a)
Location: net/core/drop_monitor.c:592
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
In net/core/drop_monitor.c (ffffffff819670ca)
Location: net/core/drop_monitor.c:592
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
In net/core/drop_monitor.c (ffffffff8198935a)
Location: net/core/drop_monitor.c:592
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
