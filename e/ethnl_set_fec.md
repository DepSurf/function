# Function: <code>ethnl_set_fec</code>

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
int ethnl_set_fec(struct sk_buff *skb, struct genl_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/fec.c (ffffffff81a81850)
Location: net/ethtool/fec.c:240
Inline: False
```
**Symbols:**

```
ffffffff81a81850-ffffffff81a81bcb: ethnl_set_fec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ethnl_set_fec(struct sk_buff *skb, struct genl_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ethtool/fec.c (0)
Location: net/ethtool/fec.c:240
Inline: False
```
**Symbols:**

```
ffffffff81d39b1f-ffffffff81d39b33: ethnl_set_fec.cold (STB_LOCAL)
ffffffff81b3b570-ffffffff81b3b84a: ethnl_set_fec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ethnl_set_fec(struct sk_buff *skb, struct genl_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ethtool/fec.c (0)
Location: net/ethtool/fec.c:240
Inline: False
```
**Symbols:**

```
ffffffff81f06262-ffffffff81f06276: ethnl_set_fec.cold (STB_LOCAL)
ffffffff81cc7570-ffffffff81cc7852: ethnl_set_fec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int ethnl_set_fec(struct sk_buff *skb, struct genl_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ethtool/fec.c (0)
Location: net/ethtool/fec.c:240
Inline: False
```
**Symbols:**

```
ffffffff820adf36-ffffffff820adf4a: ethnl_set_fec.cold (STB_LOCAL)
ffffffff81e86be0-ffffffff81e86ec2: ethnl_set_fec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int ethnl_set_fec(struct ethnl_req_info *req_info, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ethtool/fec.c (0)
Location: net/ethtool/fec.c:237
Inline: False
```
**Symbols:**

```
ffffffff81ee3450-ffffffff81ee3624: ethnl_set_fec (STB_LOCAL)
ffffffff8212f2b0-ffffffff8212f2c4: ethnl_set_fec.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int ethnl_set_fec(struct ethnl_req_info *req_info, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ethtool/fec.c (0)
Location: net/ethtool/fec.c:237
Inline: False
```
**Symbols:**

```
ffffffff81fa7230-ffffffff81fa7404: ethnl_set_fec (STB_LOCAL)
ffffffff82211041-ffffffff82211055: ethnl_set_fec.cold (STB_LOCAL)
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
