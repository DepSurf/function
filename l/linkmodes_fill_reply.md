# Function: <code>linkmodes_fill_reply</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int linkmodes_fill_reply(struct sk_buff *skb, const struct ethnl_req_info *req_base, const struct ethnl_reply_data *reply_base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/linkmodes.c (ffffffff81a88a90)
Location: net/ethtool/linkmodes.c:101
Inline: False
```
**Symbols:**

```
ffffffff81a88a90-ffffffff81a88c0d: linkmodes_fill_reply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int linkmodes_fill_reply(struct sk_buff *skb, const struct ethnl_req_info *req_base, const struct ethnl_reply_data *reply_base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/linkmodes.c (ffffffff81a92370)
Location: net/ethtool/linkmodes.c:93
Inline: False
```
**Symbols:**

```
ffffffff81a92370-ffffffff81a924ed: linkmodes_fill_reply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int linkmodes_fill_reply(struct sk_buff *skb, const struct ethnl_req_info *req_base, const struct ethnl_reply_data *reply_base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/linkmodes.c (ffffffff81a7bba0)
Location: net/ethtool/linkmodes.c:99
Inline: False
```
**Symbols:**

```
ffffffff81a7bba0-ffffffff81a7bd5d: linkmodes_fill_reply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int linkmodes_fill_reply(struct sk_buff *skb, const struct ethnl_req_info *req_base, const struct ethnl_reply_data *reply_base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ethtool/linkmodes.c (0)
Location: net/ethtool/linkmodes.c:99
Inline: False
```
**Symbols:**

```
ffffffff81b35f00-ffffffff81b360d0: linkmodes_fill_reply (STB_LOCAL)
ffffffff81d39970-ffffffff81d39985: linkmodes_fill_reply.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int linkmodes_fill_reply(struct sk_buff *skb, const struct ethnl_req_info *req_base, const struct ethnl_reply_data *reply_base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ethtool/linkmodes.c (0)
Location: net/ethtool/linkmodes.c:99
Inline: False
```
**Symbols:**

```
ffffffff81cc17f0-ffffffff81cc19da: linkmodes_fill_reply (STB_LOCAL)
ffffffff81f060ea-ffffffff81f060ff: linkmodes_fill_reply.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int linkmodes_fill_reply(struct sk_buff *skb, const struct ethnl_req_info *req_base, const struct ethnl_reply_data *reply_base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ethtool/linkmodes.c (0)
Location: net/ethtool/linkmodes.c:100
Inline: False
```
**Symbols:**

```
ffffffff81e80580-ffffffff81e8077e: linkmodes_fill_reply (STB_LOCAL)
ffffffff820addbd-ffffffff820addd2: linkmodes_fill_reply.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int linkmodes_fill_reply(struct sk_buff *skb, const struct ethnl_req_info *req_base, const struct ethnl_reply_data *reply_base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ethtool/linkmodes.c (0)
Location: net/ethtool/linkmodes.c:100
Inline: False
```
**Symbols:**

```
ffffffff81edcd70-ffffffff81edcf6e: linkmodes_fill_reply (STB_LOCAL)
ffffffff8212f006-ffffffff8212f01b: linkmodes_fill_reply.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int linkmodes_fill_reply(struct sk_buff *skb, const struct ethnl_req_info *req_base, const struct ethnl_reply_data *reply_base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ethtool/linkmodes.c (0)
Location: net/ethtool/linkmodes.c:100
Inline: False
```
**Symbols:**

```
ffffffff81fa0b40-ffffffff81fa0d3e: linkmodes_fill_reply (STB_LOCAL)
ffffffff82210d97-ffffffff82210dac: linkmodes_fill_reply.cold (STB_LOCAL)
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
