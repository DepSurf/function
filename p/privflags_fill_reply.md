# Function: <code>privflags_fill_reply</code>

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
int privflags_fill_reply(struct sk_buff *skb, const struct ethnl_req_info *req_base, const struct ethnl_reply_data *reply_base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/privflags.c (ffffffff81a8a2c0)
Location: net/ethtool/privflags.c:102
Inline: False
```
**Symbols:**

```
ffffffff81a8a2c0-ffffffff81a8a326: privflags_fill_reply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int privflags_fill_reply(struct sk_buff *skb, const struct ethnl_req_info *req_base, const struct ethnl_reply_data *reply_base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/privflags.c (ffffffff81a93b40)
Location: net/ethtool/privflags.c:100
Inline: False
```
**Symbols:**

```
ffffffff81a93b40-ffffffff81a93ba6: privflags_fill_reply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int privflags_fill_reply(struct sk_buff *skb, const struct ethnl_req_info *req_base, const struct ethnl_reply_data *reply_base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/privflags.c (ffffffff81a7d540)
Location: net/ethtool/privflags.c:100
Inline: False
```
**Symbols:**

```
ffffffff81a7d540-ffffffff81a7d5a6: privflags_fill_reply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int privflags_fill_reply(struct sk_buff *skb, const struct ethnl_req_info *req_base, const struct ethnl_reply_data *reply_base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ethtool/privflags.c (0)
Location: net/ethtool/privflags.c:100
Inline: False
```
**Symbols:**

```
ffffffff81b37740-ffffffff81b377d0: privflags_fill_reply (STB_LOCAL)
ffffffff81d39a4b-ffffffff81d39a6d: privflags_fill_reply.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int privflags_fill_reply(struct sk_buff *skb, const struct ethnl_req_info *req_base, const struct ethnl_reply_data *reply_base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ethtool/privflags.c (0)
Location: net/ethtool/privflags.c:100
Inline: False
```
**Symbols:**

```
ffffffff81cc3190-ffffffff81cc3232: privflags_fill_reply (STB_LOCAL)
ffffffff81f061c6-ffffffff81f061e8: privflags_fill_reply.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int privflags_fill_reply(struct sk_buff *skb, const struct ethnl_req_info *req_base, const struct ethnl_reply_data *reply_base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ethtool/privflags.c (0)
Location: net/ethtool/privflags.c:100
Inline: False
```
**Symbols:**

```
ffffffff81e824b0-ffffffff81e82552: privflags_fill_reply (STB_LOCAL)
ffffffff820ade9a-ffffffff820adebc: privflags_fill_reply.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int privflags_fill_reply(struct sk_buff *skb, const struct ethnl_req_info *req_base, const struct ethnl_reply_data *reply_base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ethtool/privflags.c (0)
Location: net/ethtool/privflags.c:100
Inline: False
```
**Symbols:**

```
ffffffff81edeba0-ffffffff81edec42: privflags_fill_reply (STB_LOCAL)
ffffffff8212f0e7-ffffffff8212f109: privflags_fill_reply.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int privflags_fill_reply(struct sk_buff *skb, const struct ethnl_req_info *req_base, const struct ethnl_reply_data *reply_base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ethtool/privflags.c (0)
Location: net/ethtool/privflags.c:100
Inline: False
```
**Symbols:**

```
ffffffff81fa29d0-ffffffff81fa2a72: privflags_fill_reply (STB_LOCAL)
ffffffff82210e78-ffffffff82210e9a: privflags_fill_reply.cold (STB_LOCAL)
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
