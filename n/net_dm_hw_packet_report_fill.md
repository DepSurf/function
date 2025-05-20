# Function: <code>net_dm_hw_packet_report_fill</code>

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
In net/core/drop_monitor.c (ffffffff81975d09)
Location: net/core/drop_monitor.c:730
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int net_dm_hw_packet_report_fill(struct sk_buff *msg, struct sk_buff *skb, size_t payload_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffffffff81a4a870)
Location: net/core/drop_monitor.c:743
Inline: False
Direct callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_report
```
**Symbols:**

```
ffffffff81a4a870-ffffffff81a4aab6: net_dm_hw_packet_report_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int net_dm_hw_packet_report_fill(struct sk_buff *msg, struct sk_buff *skb, size_t payload_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffffffff81a504b0)
Location: net/core/drop_monitor.c:749
Inline: False
Direct callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_report
```
**Symbols:**

```
ffffffff81a504b0-ffffffff81a506f6: net_dm_hw_packet_report_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int net_dm_hw_packet_report_fill(struct sk_buff *msg, struct sk_buff *skb, size_t payload_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffffffff81a353d0)
Location: net/core/drop_monitor.c:749
Inline: False
Direct callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
```
**Symbols:**

```
ffffffff81a353d0-ffffffff81a3561a: net_dm_hw_packet_report_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int net_dm_hw_packet_report_fill(struct sk_buff *msg, struct sk_buff *skb, size_t payload_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffffffff81aeafa0)
Location: net/core/drop_monitor.c:753
Inline: False
Direct callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
```
**Symbols:**

```
ffffffff81aeafa0-ffffffff81aeb1ea: net_dm_hw_packet_report_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int net_dm_hw_packet_report_fill(struct sk_buff *msg, struct sk_buff *skb, size_t payload_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffffffff81c6d7f0)
Location: net/core/drop_monitor.c:776
Inline: False
Direct callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
```
**Symbols:**

```
ffffffff81c6d7f0-ffffffff81c6da4d: net_dm_hw_packet_report_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int net_dm_hw_packet_report_fill(struct sk_buff *msg, struct sk_buff *skb, size_t payload_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffffffff81e25450)
Location: net/core/drop_monitor.c:763
Inline: False
Direct callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
```
**Symbols:**

```
ffffffff81e25450-ffffffff81e256ad: net_dm_hw_packet_report_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int net_dm_hw_packet_report_fill(struct sk_buff *msg, struct sk_buff *skb, size_t payload_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffffffff81e9a990)
Location: net/core/drop_monitor.c:778
Inline: False
Direct callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
```
**Symbols:**

```
ffffffff81e9a990-ffffffff81e9abed: net_dm_hw_packet_report_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int net_dm_hw_packet_report_fill(struct sk_buff *msg, struct sk_buff *skb, size_t payload_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffffffff81f5d0d0)
Location: net/core/drop_monitor.c:778
Inline: False
Direct callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
```
**Symbols:**

```
ffffffff81f5d0d0-ffffffff81f5d334: net_dm_hw_packet_report_fill (STB_LOCAL)
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
In net/core/drop_monitor.c (ffff800010c1c1b4)
Location: net/core/drop_monitor.c:730
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
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
In net/core/drop_monitor.c (c0d33fe8)
Location: net/core/drop_monitor.c:730
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
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
In net/core/drop_monitor.c (c000000000d0cf14)
Location: net/core/drop_monitor.c:730
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
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
In net/core/drop_monitor.c (ffffffe000796268)
Location: net/core/drop_monitor.c:730
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
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
In net/core/drop_monitor.c (ffffffff81915cd9)
Location: net/core/drop_monitor.c:730
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
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
In net/core/drop_monitor.c (ffffffff818cfa89)
Location: net/core/drop_monitor.c:730
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
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
In net/core/drop_monitor.c (ffffffff81966d09)
Location: net/core/drop_monitor.c:730
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
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
In net/core/drop_monitor.c (ffffffff81988f99)
Location: net/core/drop_monitor.c:730
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
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
