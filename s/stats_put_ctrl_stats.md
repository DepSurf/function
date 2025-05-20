# Function: <code>stats_put_ctrl_stats</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int stats_put_ctrl_stats(struct sk_buff *skb, const struct stats_reply_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/stats.c (ffffffff81a82680)
Location: net/ethtool/stats.c:276
Inline: False
```
**Symbols:**

```
ffffffff81a82680-ffffffff81a826f4: stats_put_ctrl_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int stats_put_ctrl_stats(struct sk_buff *skb, const struct stats_reply_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/stats.c (ffffffff81b3c200)
Location: net/ethtool/stats.c:276
Inline: False
```
**Symbols:**

```
ffffffff81b3c200-ffffffff81b3c274: stats_put_ctrl_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int stats_put_ctrl_stats(struct sk_buff *skb, const struct stats_reply_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/stats.c (ffffffff81cc8270)
Location: net/ethtool/stats.c:275
Inline: False
```
**Symbols:**

```
ffffffff81cc8270-ffffffff81cc82dc: stats_put_ctrl_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int stats_put_ctrl_stats(struct sk_buff *skb, const struct stats_reply_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/stats.c (ffffffff81e879c0)
Location: net/ethtool/stats.c:275
Inline: False
```
**Symbols:**

```
ffffffff81e879c0-ffffffff81e87a2c: stats_put_ctrl_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int stats_put_ctrl_stats(struct sk_buff *skb, const struct stats_reply_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/stats.c (ffffffff81ee4650)
Location: net/ethtool/stats.c:302
Inline: False
```
**Symbols:**

```
ffffffff81ee4650-ffffffff81ee46bc: stats_put_ctrl_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int stats_put_ctrl_stats(struct sk_buff *skb, const struct stats_reply_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/stats.c (ffffffff81fa8430)
Location: net/ethtool/stats.c:301
Inline: False
```
**Symbols:**

```
ffffffff81fa8430-ffffffff81fa849c: stats_put_ctrl_stats (STB_LOCAL)
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
