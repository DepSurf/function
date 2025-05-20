# Function: <code>net_dm_cmd_config</code>

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
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int net_dm_cmd_config(struct sk_buff *skb, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffffffff81974600)
Location: net/core/drop_monitor.c:1209
Inline: False
```
**Symbols:**

```
ffffffff81974600-ffffffff81974694: net_dm_cmd_config (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int net_dm_cmd_config(struct sk_buff *skb, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffffffff81a49780)
Location: net/core/drop_monitor.c:1239
Inline: True
```
**Symbols:**

```
ffffffff81a49780-ffffffff81a49814: net_dm_cmd_config (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int net_dm_cmd_config(struct sk_buff *skb, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffffffff81a4ef50)
Location: net/core/drop_monitor.c:1289
Inline: True
```
**Symbols:**

```
ffffffff81a4ef50-ffffffff81a4efe4: net_dm_cmd_config (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int net_dm_cmd_config(struct sk_buff *skb, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffffffff81a33f90)
Location: net/core/drop_monitor.c:1289
Inline: True
```
**Symbols:**

```
ffffffff81a33f90-ffffffff81a34045: net_dm_cmd_config (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int net_dm_cmd_config(struct sk_buff *skb, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/drop_monitor.c (ffffffff81ae9ad6)
Location: net/core/drop_monitor.c:1291
Inline: True
```
**Symbols:**

```
ffffffff81ae9a80-ffffffff81ae9b50: net_dm_cmd_config (STB_LOCAL)
ffffffff81d3816a-ffffffff81d3817f: net_dm_cmd_config.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int net_dm_cmd_config(struct sk_buff *skb, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/drop_monitor.c (ffffffff81c6c336)
Location: net/core/drop_monitor.c:1306
Inline: True
```
**Symbols:**

```
ffffffff81c6c2e0-ffffffff81c6c3ae: net_dm_cmd_config (STB_LOCAL)
ffffffff81f04b53-ffffffff81f04b68: net_dm_cmd_config.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
int net_dm_cmd_config(struct sk_buff *skb, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/drop_monitor.c (ffffffff81e23d26)
Location: net/core/drop_monitor.c:1294
Inline: True
```
**Symbols:**

```
ffffffff81e23cd0-ffffffff81e23d9e: net_dm_cmd_config (STB_LOCAL)
ffffffff820acc40-ffffffff820acc55: net_dm_cmd_config.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
int net_dm_cmd_config(struct sk_buff *skb, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/drop_monitor.c (ffffffff81e99095)
Location: net/core/drop_monitor.c:1309
Inline: True
```
**Symbols:**

```
ffffffff81e99040-ffffffff81e9910b: net_dm_cmd_config (STB_LOCAL)
ffffffff8212e33f-ffffffff8212e354: net_dm_cmd_config.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int net_dm_cmd_config(struct sk_buff *skb, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/drop_monitor.c (ffffffff81f5b755)
Location: net/core/drop_monitor.c:1309
Inline: True
```
**Symbols:**

```
ffffffff81f5b700-ffffffff81f5b7cb: net_dm_cmd_config (STB_LOCAL)
ffffffff8221011e-ffffffff82210133: net_dm_cmd_config.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int net_dm_cmd_config(struct sk_buff *skb, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffff800010c1a4b8)
Location: net/core/drop_monitor.c:1209
Inline: False
```
**Symbols:**

```
ffff800010c1a4b8-ffff800010c1a594: net_dm_cmd_config (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int net_dm_cmd_config(struct sk_buff *skb, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (c0d32574)
Location: net/core/drop_monitor.c:1209
Inline: False
```
**Symbols:**

```
c0d32574-c0d3263c: net_dm_cmd_config (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int net_dm_cmd_config(struct sk_buff *skb, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (c000000000d0a8e0)
Location: net/core/drop_monitor.c:1209
Inline: False
```
**Symbols:**

```
c000000000d0a8e0-c000000000d0a9dc: net_dm_cmd_config (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int net_dm_cmd_config(struct sk_buff *skb, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffffffe000794a6c)
Location: net/core/drop_monitor.c:1209
Inline: False
```
**Symbols:**

```
ffffffe000794a6c-ffffffe000794b0e: net_dm_cmd_config (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int net_dm_cmd_config(struct sk_buff *skb, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffffffff819145d0)
Location: net/core/drop_monitor.c:1209
Inline: False
```
**Symbols:**

```
ffffffff819145d0-ffffffff81914664: net_dm_cmd_config (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int net_dm_cmd_config(struct sk_buff *skb, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffffffff818ce390)
Location: net/core/drop_monitor.c:1209
Inline: False
```
**Symbols:**

```
ffffffff818ce390-ffffffff818ce424: net_dm_cmd_config (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int net_dm_cmd_config(struct sk_buff *skb, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffffffff81965600)
Location: net/core/drop_monitor.c:1209
Inline: False
```
**Symbols:**

```
ffffffff81965600-ffffffff81965694: net_dm_cmd_config (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int net_dm_cmd_config(struct sk_buff *skb, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffffffff81987840)
Location: net/core/drop_monitor.c:1209
Inline: False
```
**Symbols:**

```
ffffffff81987840-ffffffff819878d4: net_dm_cmd_config (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
