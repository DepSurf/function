# Function: <code>ethnl_set_channels</code>

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
int ethnl_set_channels(struct sk_buff *skb, struct genl_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/channels.c (ffffffff81a8afc0)
Location: net/ethtool/channels.c:128
Inline: False
```
**Symbols:**

```
ffffffff81a8afc0-ffffffff81a8b43c: ethnl_set_channels (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ethnl_set_channels(struct sk_buff *skb, struct genl_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/channels.c (ffffffff81a94750)
Location: net/ethtool/channels.c:112
Inline: False
```
**Symbols:**

```
ffffffff81a94750-ffffffff81a94b0e: ethnl_set_channels (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ethnl_set_channels(struct sk_buff *skb, struct genl_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/channels.c (ffffffff81a7e160)
Location: net/ethtool/channels.c:112
Inline: False
```
**Symbols:**

```
ffffffff81a7e160-ffffffff81a7e561: ethnl_set_channels (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ethnl_set_channels(struct sk_buff *skb, struct genl_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ethtool/channels.c (0)
Location: net/ethtool/channels.c:112
Inline: False
```
**Symbols:**

```
ffffffff81d39ada-ffffffff81d39b0b: ethnl_set_channels.cold (STB_LOCAL)
ffffffff81b382b0-ffffffff81b386a1: ethnl_set_channels (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ethnl_set_channels(struct sk_buff *skb, struct genl_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/channels.c (ffffffff81cc4020)
Location: net/ethtool/channels.c:112
Inline: False
```
**Symbols:**

```
ffffffff81cc4020-ffffffff81cc440c: ethnl_set_channels (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ethnl_set_channels(struct sk_buff *skb, struct genl_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/channels.c (ffffffff81e83400)
Location: net/ethtool/channels.c:112
Inline: False
```
**Symbols:**

```
ffffffff81e83400-ffffffff81e83868: ethnl_set_channels (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int ethnl_set_channels(struct ethnl_req_info *req_info, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ethtool/channels.c (0)
Location: net/ethtool/channels.c:110
Inline: False
```
**Symbols:**

```
ffffffff81edfbd0-ffffffff81edff9f: ethnl_set_channels (STB_LOCAL)
ffffffff8212f16f-ffffffff8212f196: ethnl_set_channels.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int ethnl_set_channels(struct ethnl_req_info *req_info, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ethtool/channels.c (0)
Location: net/ethtool/channels.c:110
Inline: False
```
**Symbols:**

```
ffffffff81fa3a70-ffffffff81fa3e3f: ethnl_set_channels (STB_LOCAL)
ffffffff82210f00-ffffffff82210f27: ethnl_set_channels.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct ethnl_req_info *req_info</code>
</li>
<li>
<b>Param removed. </b>
<code>struct sk_buff *skb</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
