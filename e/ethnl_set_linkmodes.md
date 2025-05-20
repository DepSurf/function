# Function: <code>ethnl_set_linkmodes</code>

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
int ethnl_set_linkmodes(struct sk_buff *skb, struct genl_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/linkmodes.c (ffffffff81a88fe0)
Location: net/ethtool/linkmodes.c:376
Inline: False
```
**Symbols:**

```
ffffffff81a88fe0-ffffffff81a89218: ethnl_set_linkmodes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ethnl_set_linkmodes(struct sk_buff *skb, struct genl_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/linkmodes.c (ffffffff81a928d0)
Location: net/ethtool/linkmodes.c:380
Inline: False
```
**Symbols:**

```
ffffffff81a928d0-ffffffff81a92a94: ethnl_set_linkmodes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ethnl_set_linkmodes(struct sk_buff *skb, struct genl_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/linkmodes.c (ffffffff81a7c200)
Location: net/ethtool/linkmodes.c:308
Inline: False
```
**Symbols:**

```
ffffffff81a7c200-ffffffff81a7c4a3: ethnl_set_linkmodes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ethnl_set_linkmodes(struct sk_buff *skb, struct genl_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ethtool/linkmodes.c (0)
Location: net/ethtool/linkmodes.c:308
Inline: False
```
**Symbols:**

```
ffffffff81d3999a-ffffffff81d399af: ethnl_set_linkmodes.cold (STB_LOCAL)
ffffffff81b36540-ffffffff81b367cc: ethnl_set_linkmodes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ethnl_set_linkmodes(struct sk_buff *skb, struct genl_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ethtool/linkmodes.c (0)
Location: net/ethtool/linkmodes.c:308
Inline: False
```
**Symbols:**

```
ffffffff81f06114-ffffffff81f06129: ethnl_set_linkmodes.cold (STB_LOCAL)
ffffffff81cc1e90-ffffffff81cc2105: ethnl_set_linkmodes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int ethnl_set_linkmodes(struct sk_buff *skb, struct genl_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ethtool/linkmodes.c (0)
Location: net/ethtool/linkmodes.c:313
Inline: False
```
**Symbols:**

```
ffffffff820adde7-ffffffff820addfc: ethnl_set_linkmodes.cold (STB_LOCAL)
ffffffff81e80c80-ffffffff81e80ef5: ethnl_set_linkmodes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int ethnl_set_linkmodes(struct ethnl_req_info *req_info, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ethtool/linkmodes.c (0)
Location: net/ethtool/linkmodes.c:319
Inline: False
```
**Symbols:**

```
ffffffff81edd400-ffffffff81edd53e: ethnl_set_linkmodes (STB_LOCAL)
ffffffff8212f030-ffffffff8212f045: ethnl_set_linkmodes.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int ethnl_set_linkmodes(struct ethnl_req_info *req_info, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ethtool/linkmodes.c (0)
Location: net/ethtool/linkmodes.c:319
Inline: False
```
**Symbols:**

```
ffffffff81fa11d0-ffffffff81fa130e: ethnl_set_linkmodes (STB_LOCAL)
ffffffff82210dc1-ffffffff82210dd6: ethnl_set_linkmodes.cold (STB_LOCAL)
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
