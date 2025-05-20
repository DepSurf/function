# Function: <code>ethnl_set_privflags</code>

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
int ethnl_set_privflags(struct sk_buff *skb, struct genl_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/privflags.c (ffffffff81a8a5f0)
Location: net/ethtool/privflags.c:147
Inline: False
```
**Symbols:**

```
ffffffff81a8a5f0-ffffffff81a8a829: ethnl_set_privflags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ethnl_set_privflags(struct sk_buff *skb, struct genl_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/privflags.c (ffffffff81a93e50)
Location: net/ethtool/privflags.c:142
Inline: False
```
**Symbols:**

```
ffffffff81a93e50-ffffffff81a9403c: ethnl_set_privflags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ethnl_set_privflags(struct sk_buff *skb, struct genl_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/privflags.c (ffffffff81a7d850)
Location: net/ethtool/privflags.c:142
Inline: False
```
**Symbols:**

```
ffffffff81a7d850-ffffffff81a7da42: ethnl_set_privflags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ethnl_set_privflags(struct sk_buff *skb, struct genl_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ethtool/privflags.c (0)
Location: net/ethtool/privflags.c:142
Inline: False
```
**Symbols:**

```
ffffffff81d39aa9-ffffffff81d39ada: ethnl_set_privflags.cold (STB_LOCAL)
ffffffff81b37a20-ffffffff81b37c1c: ethnl_set_privflags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ethnl_set_privflags(struct sk_buff *skb, struct genl_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ethtool/privflags.c (0)
Location: net/ethtool/privflags.c:142
Inline: False
```
**Symbols:**

```
ffffffff81f06225-ffffffff81f0624e: ethnl_set_privflags.cold (STB_LOCAL)
ffffffff81cc34d0-ffffffff81cc36d8: ethnl_set_privflags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int ethnl_set_privflags(struct sk_buff *skb, struct genl_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ethtool/privflags.c (0)
Location: net/ethtool/privflags.c:142
Inline: False
```
**Symbols:**

```
ffffffff820adef9-ffffffff820adf22: ethnl_set_privflags.cold (STB_LOCAL)
ffffffff81e82830-ffffffff81e82a38: ethnl_set_privflags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int ethnl_set_privflags(struct ethnl_req_info *req_info, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ethtool/privflags.c (0)
Location: net/ethtool/privflags.c:145
Inline: False
```
**Symbols:**

```
ffffffff81edef20-ffffffff81edf06c: ethnl_set_privflags (STB_LOCAL)
ffffffff8212f146-ffffffff8212f16f: ethnl_set_privflags.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int ethnl_set_privflags(struct ethnl_req_info *req_info, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ethtool/privflags.c (0)
Location: net/ethtool/privflags.c:145
Inline: False
```
**Symbols:**

```
ffffffff81fa2d60-ffffffff81fa2eac: ethnl_set_privflags (STB_LOCAL)
ffffffff82210ed7-ffffffff82210f00: ethnl_set_privflags.cold (STB_LOCAL)
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
