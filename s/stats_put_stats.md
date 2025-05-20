# Function: <code>stats_put_stats</code>

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
int stats_put_stats(struct sk_buff *skb, const struct stats_reply_data *data, u32 id, u32 ss_id, int (*cb)(struct sk_buff *, const struct stats_reply_data *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/stats.c (ffffffff81a82130)
Location: net/ethtool/stats.c:348
Inline: False
Direct callers:
  - net/ethtool/stats.c:stats_fill_reply
  - net/ethtool/stats.c:stats_fill_reply
  - net/ethtool/stats.c:stats_fill_reply
  - net/ethtool/stats.c:stats_fill_reply
```
**Symbols:**

```
ffffffff81a82130-ffffffff81a82241: stats_put_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int stats_put_stats(struct sk_buff *skb, const struct stats_reply_data *data, u32 id, u32 ss_id, int (*cb)(struct sk_buff *, const struct stats_reply_data *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/stats.c (ffffffff81b3bcf0)
Location: net/ethtool/stats.c:348
Inline: False
Direct callers:
  - net/ethtool/stats.c:stats_fill_reply
  - net/ethtool/stats.c:stats_fill_reply
  - net/ethtool/stats.c:stats_fill_reply
  - net/ethtool/stats.c:stats_fill_reply
```
**Symbols:**

```
ffffffff81b3bcf0-ffffffff81b3be01: stats_put_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int stats_put_stats(struct sk_buff *skb, const struct stats_reply_data *data, u32 id, u32 ss_id, int (*cb)(struct sk_buff *, const struct stats_reply_data *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/stats.c (ffffffff81cc7f40)
Location: net/ethtool/stats.c:347
Inline: False
Direct callers:
  - net/ethtool/stats.c:stats_fill_reply
  - net/ethtool/stats.c:stats_fill_reply
  - net/ethtool/stats.c:stats_fill_reply
  - net/ethtool/stats.c:stats_fill_reply
```
**Symbols:**

```
ffffffff81cc7f40-ffffffff81cc805a: stats_put_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int stats_put_stats(struct sk_buff *skb, const struct stats_reply_data *data, u32 id, u32 ss_id, int (*cb)(struct sk_buff *, const struct stats_reply_data *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/stats.c (ffffffff81e87660)
Location: net/ethtool/stats.c:347
Inline: False
Direct callers:
  - net/ethtool/stats.c:stats_fill_reply
  - net/ethtool/stats.c:stats_fill_reply
  - net/ethtool/stats.c:stats_fill_reply
  - net/ethtool/stats.c:stats_fill_reply
```
**Symbols:**

```
ffffffff81e87660-ffffffff81e8777a: stats_put_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int stats_put_stats(struct sk_buff *skb, const struct stats_reply_data *data, u32 id, u32 ss_id, int (*cb)(struct sk_buff *, const struct stats_reply_data *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/stats.c (ffffffff81ee42b0)
Location: net/ethtool/stats.c:374
Inline: False
Direct callers:
  - net/ethtool/stats.c:stats_fill_reply
  - net/ethtool/stats.c:stats_fill_reply
  - net/ethtool/stats.c:stats_fill_reply
  - net/ethtool/stats.c:stats_fill_reply
```
**Symbols:**

```
ffffffff81ee42b0-ffffffff81ee43ca: stats_put_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int stats_put_stats(struct sk_buff *skb, const struct stats_reply_data *data, u32 id, u32 ss_id, int (*cb)(struct sk_buff *, const struct stats_reply_data *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/stats.c (ffffffff81fa8090)
Location: net/ethtool/stats.c:373
Inline: False
Direct callers:
  - net/ethtool/stats.c:stats_fill_reply
  - net/ethtool/stats.c:stats_fill_reply
  - net/ethtool/stats.c:stats_fill_reply
  - net/ethtool/stats.c:stats_fill_reply
```
**Symbols:**

```
ffffffff81fa8090-ffffffff81fa81aa: stats_put_stats (STB_LOCAL)
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
