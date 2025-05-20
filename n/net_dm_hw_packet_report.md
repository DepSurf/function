# Function: <code>net_dm_hw_packet_report</code>

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
In net/core/drop_monitor.c (ffffffff81975f17)
Location: net/core/drop_monitor.c:842
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
void net_dm_hw_packet_report(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffffffff81a4aac0)
Location: net/core/drop_monitor.c:872
Inline: False
Direct callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
```
**Symbols:**

```
ffffffff81a4aac0-ffffffff81a4abf7: net_dm_hw_packet_report (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void net_dm_hw_packet_report(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffffffff81a50700)
Location: net/core/drop_monitor.c:878
Inline: False
Direct callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
```
**Symbols:**

```
ffffffff81a50700-ffffffff81a50836: net_dm_hw_packet_report (STB_LOCAL)
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
In net/core/drop_monitor.c (ffffffff81a357e1)
Location: net/core/drop_monitor.c:878
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
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
In net/core/drop_monitor.c (ffffffff81aeb3b1)
Location: net/core/drop_monitor.c:880
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
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
In net/core/drop_monitor.c (ffffffff81c6dc10)
Location: net/core/drop_monitor.c:903
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
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
In net/core/drop_monitor.c (ffffffff81e25880)
Location: net/core/drop_monitor.c:891
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
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
In net/core/drop_monitor.c (ffffffff81e9adc0)
Location: net/core/drop_monitor.c:906
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
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
In net/core/drop_monitor.c (ffffffff81f5d51a)
Location: net/core/drop_monitor.c:906
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
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
In net/core/drop_monitor.c (ffff800010c1c100)
Location: net/core/drop_monitor.c:842
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
In net/core/drop_monitor.c (c0d341ec)
Location: net/core/drop_monitor.c:842
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
In net/core/drop_monitor.c (c000000000d0d158)
Location: net/core/drop_monitor.c:842
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
In net/core/drop_monitor.c (ffffffe000796182)
Location: net/core/drop_monitor.c:842
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
In net/core/drop_monitor.c (ffffffff81915ee7)
Location: net/core/drop_monitor.c:842
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
In net/core/drop_monitor.c (ffffffff818cfc97)
Location: net/core/drop_monitor.c:842
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
In net/core/drop_monitor.c (ffffffff81966f17)
Location: net/core/drop_monitor.c:842
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
In net/core/drop_monitor.c (ffffffff819891a7)
Location: net/core/drop_monitor.c:842
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
</ul>
