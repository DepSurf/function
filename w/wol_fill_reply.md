# Function: <code>wol_fill_reply</code>

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
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int wol_fill_reply(struct sk_buff *skb, const struct ethnl_req_info *req_base, const struct ethnl_reply_data *reply_base);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ethtool/wol.c (ffffffff81a89810)
Location: net/ethtool/wol.c:67
Inline: True
```
**Symbols:**

```
ffffffff81a89810-ffffffff81a8987f: wol_fill_reply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int wol_fill_reply(struct sk_buff *skb, const struct ethnl_req_info *req_base, const struct ethnl_reply_data *reply_base);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ethtool/wol.c (ffffffff81a93120)
Location: net/ethtool/wol.c:64
Inline: True
```
**Symbols:**

```
ffffffff81a93120-ffffffff81a9318f: wol_fill_reply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int wol_fill_reply(struct sk_buff *skb, const struct ethnl_req_info *req_base, const struct ethnl_reply_data *reply_base);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ethtool/wol.c (ffffffff81a7cb30)
Location: net/ethtool/wol.c:64
Inline: True
```
**Symbols:**

```
ffffffff81a7cb30-ffffffff81a7cb9f: wol_fill_reply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int wol_fill_reply(struct sk_buff *skb, const struct ethnl_req_info *req_base, const struct ethnl_reply_data *reply_base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ethtool/wol.c (0)
Location: net/ethtool/wol.c:64
Inline: False
```
**Symbols:**

```
ffffffff81b36db0-ffffffff81b36e32: wol_fill_reply (STB_LOCAL)
ffffffff81d399f3-ffffffff81d39a08: wol_fill_reply.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int wol_fill_reply(struct sk_buff *skb, const struct ethnl_req_info *req_base, const struct ethnl_reply_data *reply_base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ethtool/wol.c (0)
Location: net/ethtool/wol.c:64
Inline: False
```
**Symbols:**

```
ffffffff81cc2740-ffffffff81cc27d4: wol_fill_reply (STB_LOCAL)
ffffffff81f0616e-ffffffff81f06183: wol_fill_reply.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int wol_fill_reply(struct sk_buff *skb, const struct ethnl_req_info *req_base, const struct ethnl_reply_data *reply_base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ethtool/wol.c (0)
Location: net/ethtool/wol.c:64
Inline: False
```
**Symbols:**

```
ffffffff81e81980-ffffffff81e81a14: wol_fill_reply (STB_LOCAL)
ffffffff820ade41-ffffffff820ade56: wol_fill_reply.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int wol_fill_reply(struct sk_buff *skb, const struct ethnl_req_info *req_base, const struct ethnl_reply_data *reply_base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ethtool/wol.c (0)
Location: net/ethtool/wol.c:64
Inline: False
```
**Symbols:**

```
ffffffff81ede090-ffffffff81ede124: wol_fill_reply (STB_LOCAL)
ffffffff8212f08f-ffffffff8212f0a4: wol_fill_reply.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int wol_fill_reply(struct sk_buff *skb, const struct ethnl_req_info *req_base, const struct ethnl_reply_data *reply_base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ethtool/wol.c (0)
Location: net/ethtool/wol.c:65
Inline: False
```
**Symbols:**

```
ffffffff81fa1ed0-ffffffff81fa1f64: wol_fill_reply (STB_LOCAL)
ffffffff82210e20-ffffffff82210e35: wol_fill_reply.cold (STB_LOCAL)
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
