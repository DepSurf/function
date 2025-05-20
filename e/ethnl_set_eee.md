# Function: <code>ethnl_set_eee</code>

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
int ethnl_set_eee(struct sk_buff *skb, struct genl_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/eee.c (ffffffff81a8c560)
Location: net/ethtool/eee.c:146
Inline: False
```
**Symbols:**

```
ffffffff81a8c560-ffffffff81a8c8b3: ethnl_set_eee (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ethnl_set_eee(struct sk_buff *skb, struct genl_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/eee.c (ffffffff81a95cf0)
Location: net/ethtool/eee.c:134
Inline: False
```
**Symbols:**

```
ffffffff81a95cf0-ffffffff81a95fcf: ethnl_set_eee (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ethnl_set_eee(struct sk_buff *skb, struct genl_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/eee.c (ffffffff81a7f780)
Location: net/ethtool/eee.c:134
Inline: False
```
**Symbols:**

```
ffffffff81a7f780-ffffffff81a7fa46: ethnl_set_eee (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ethnl_set_eee(struct sk_buff *skb, struct genl_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ethtool/eee.c (0)
Location: net/ethtool/eee.c:134
Inline: False
```
**Symbols:**

```
ffffffff81d39b0b-ffffffff81d39b1f: ethnl_set_eee.cold (STB_LOCAL)
ffffffff81b39640-ffffffff81b39851: ethnl_set_eee (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ethnl_set_eee(struct sk_buff *skb, struct genl_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ethtool/eee.c (0)
Location: net/ethtool/eee.c:134
Inline: False
```
**Symbols:**

```
ffffffff81f0624e-ffffffff81f06262: ethnl_set_eee.cold (STB_LOCAL)
ffffffff81cc5470-ffffffff81cc569f: ethnl_set_eee (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int ethnl_set_eee(struct sk_buff *skb, struct genl_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ethtool/eee.c (0)
Location: net/ethtool/eee.c:134
Inline: False
```
**Symbols:**

```
ffffffff820adf22-ffffffff820adf36: ethnl_set_eee.cold (STB_LOCAL)
ffffffff81e849c0-ffffffff81e84bef: ethnl_set_eee (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int ethnl_set_eee(struct ethnl_req_info *req_info, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ethtool/eee.c (0)
Location: net/ethtool/eee.c:131
Inline: False
```
**Symbols:**

```
ffffffff81ee13a0-ffffffff81ee1517: ethnl_set_eee (STB_LOCAL)
ffffffff8212f29c-ffffffff8212f2b0: ethnl_set_eee.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int ethnl_set_eee(struct ethnl_req_info *req_info, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ethtool/eee.c (0)
Location: net/ethtool/eee.c:131
Inline: False
```
**Symbols:**

```
ffffffff81fa5230-ffffffff81fa53a7: ethnl_set_eee (STB_LOCAL)
ffffffff8221102d-ffffffff82211041: ethnl_set_eee.cold (STB_LOCAL)
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
