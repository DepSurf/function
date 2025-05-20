# Function: <code>devlink_nl_cmd_dpipe_entries_get</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int devlink_nl_cmd_dpipe_entries_get(struct sk_buff *skb, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81948510)
Location: net/core/devlink.c:2189
Inline: False
```
**Symbols:**

```
ffffffff81948510-ffffffff8194862b: devlink_nl_cmd_dpipe_entries_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int devlink_nl_cmd_dpipe_entries_get(struct sk_buff *skb, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8197d9c0)
Location: net/core/devlink.c:2191
Inline: False
```
**Symbols:**

```
ffffffff8197d9c0-ffffffff8197dadb: devlink_nl_cmd_dpipe_entries_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int devlink_nl_cmd_dpipe_entries_get(struct sk_buff *skb, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a54790)
Location: net/core/devlink.c:2223
Inline: False
```
**Symbols:**

```
ffffffff81a54790-ffffffff81a548ea: devlink_nl_cmd_dpipe_entries_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int devlink_nl_cmd_dpipe_entries_get(struct sk_buff *skb, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a5b6e0)
Location: net/core/devlink.c:2555
Inline: False
```
**Symbols:**

```
ffffffff81a5b6e0-ffffffff81a5b83a: devlink_nl_cmd_dpipe_entries_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int devlink_nl_cmd_dpipe_entries_get(struct sk_buff *skb, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a3e250)
Location: net/core/devlink.c:2758
Inline: False
```
**Symbols:**

```
ffffffff81a3e250-ffffffff81a3e3a7: devlink_nl_cmd_dpipe_entries_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int devlink_nl_cmd_dpipe_entries_get(struct sk_buff *skb, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:3320
Inline: False
```
**Symbols:**

```
ffffffff81af4890-ffffffff81af49f8: devlink_nl_cmd_dpipe_entries_get (STB_LOCAL)
ffffffff81d385ef-ffffffff81d38604: devlink_nl_cmd_dpipe_entries_get.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int devlink_nl_cmd_dpipe_entries_get(struct sk_buff *skb, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:3835
Inline: False
```
**Symbols:**

```
ffffffff81c78b30-ffffffff81c78cc3: devlink_nl_cmd_dpipe_entries_get (STB_LOCAL)
ffffffff81f04fa0-ffffffff81f04fb5: devlink_nl_cmd_dpipe_entries_get.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int devlink_nl_cmd_dpipe_entries_get(struct sk_buff *skb, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:4099
Inline: False
```
**Symbols:**

```
ffffffff81e319e0-ffffffff81e31b8d: devlink_nl_cmd_dpipe_entries_get (STB_LOCAL)
ffffffff820acf9e-ffffffff820acfb3: devlink_nl_cmd_dpipe_entries_get.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int devlink_nl_cmd_dpipe_entries_get(struct sk_buff *skb, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/devlink/leftover.c (0)
Location: net/devlink/leftover.c:3317
Inline: False
```
**Symbols:**

```
ffffffff82033b40-ffffffff82033ced: devlink_nl_cmd_dpipe_entries_get (STB_LOCAL)
ffffffff82136420-ffffffff82136435: devlink_nl_cmd_dpipe_entries_get.cold (STB_LOCAL)
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int devlink_nl_cmd_dpipe_entries_get(struct sk_buff *skb, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffff800010c253a8)
Location: net/core/devlink.c:2191
Inline: False
```
**Symbols:**

```
ffff800010c253a8-ffff800010c254cc: devlink_nl_cmd_dpipe_entries_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int devlink_nl_cmd_dpipe_entries_get(struct sk_buff *skb, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c0d3c718)
Location: net/core/devlink.c:2191
Inline: False
```
**Symbols:**

```
c0d3c718-c0d3c858: devlink_nl_cmd_dpipe_entries_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int devlink_nl_cmd_dpipe_entries_get(struct sk_buff *skb, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c000000000d19240)
Location: net/core/devlink.c:2191
Inline: False
```
**Symbols:**

```
c000000000d19240-c000000000d193e0: devlink_nl_cmd_dpipe_entries_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int devlink_nl_cmd_dpipe_entries_get(struct sk_buff *skb, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffe00079da16)
Location: net/core/devlink.c:2191
Inline: False
```
**Symbols:**

```
ffffffe00079da16-ffffffe00079daf0: devlink_nl_cmd_dpipe_entries_get (STB_LOCAL)
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
int devlink_nl_cmd_dpipe_entries_get(struct sk_buff *skb, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8191d830)
Location: net/core/devlink.c:2191
Inline: False
```
**Symbols:**

```
ffffffff8191d830-ffffffff8191d94b: devlink_nl_cmd_dpipe_entries_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int devlink_nl_cmd_dpipe_entries_get(struct sk_buff *skb, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff818d75e0)
Location: net/core/devlink.c:2191
Inline: False
```
**Symbols:**

```
ffffffff818d75e0-ffffffff818d76fb: devlink_nl_cmd_dpipe_entries_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int devlink_nl_cmd_dpipe_entries_get(struct sk_buff *skb, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8196e9c0)
Location: net/core/devlink.c:2191
Inline: False
```
**Symbols:**

```
ffffffff8196e9c0-ffffffff8196eadb: devlink_nl_cmd_dpipe_entries_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int devlink_nl_cmd_dpipe_entries_get(struct sk_buff *skb, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81990eb0)
Location: net/core/devlink.c:2191
Inline: False
```
**Symbols:**

```
ffffffff81990eb0-ffffffff81990fcb: devlink_nl_cmd_dpipe_entries_get (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
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
