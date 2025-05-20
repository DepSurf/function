# Function: <code>pause_put_stats</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pause_put_stats(struct sk_buff *skb, const struct ethtool_pause_stats *pause_stats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/pause.c (ffffffff81a95530)
Location: net/ethtool/pause.c:81
Inline: False
Direct callers:
  - net/ethtool/pause.c:pause_fill_reply
```
**Symbols:**

```
ffffffff81a95530-ffffffff81a95643: pause_put_stats (STB_LOCAL)
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
In net/ethtool/pause.c (ffffffff81a7f0ec)
Location: net/ethtool/pause.c:75
Inline: True
Inline callers:
  - net/ethtool/pause.c:pause_fill_reply
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
In net/ethtool/pause.c (ffffffff81b3914c)
Location: net/ethtool/pause.c:74
Inline: True
Inline callers:
  - net/ethtool/pause.c:pause_fill_reply
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
In net/ethtool/pause.c (ffffffff81cc4f4e)
Location: net/ethtool/pause.c:74
Inline: True
Inline callers:
  - net/ethtool/pause.c:pause_fill_reply
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
In net/ethtool/pause.c (ffffffff81e8444e)
Location: net/ethtool/pause.c:74
Inline: True
Inline callers:
  - net/ethtool/pause.c:pause_fill_reply
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
In net/ethtool/pause.c (ffffffff81ee0fbe)
Location: net/ethtool/pause.c:118
Inline: True
Inline callers:
  - net/ethtool/pause.c:pause_fill_reply
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
In net/ethtool/pause.c (ffffffff81fa4e4e)
Location: net/ethtool/pause.c:117
Inline: True
Inline callers:
  - net/ethtool/pause.c:pause_fill_reply
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
</ul>
