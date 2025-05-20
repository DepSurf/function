# Function: <code>features_send_reply</code>

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
int features_send_reply(struct net_device *dev, struct genl_info *info, const long unsigned int *wanted, const long unsigned int *wanted_mask, const long unsigned int *active, const long unsigned int *active_mask, bool compact);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/features.c (ffffffff81a89e60)
Location: net/ethtool/features.c:168
Inline: False
Direct callers:
  - net/ethtool/features.c:ethnl_set_features
```
**Symbols:**

```
ffffffff81a89e60-ffffffff81a8a03e: features_send_reply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int features_send_reply(struct net_device *dev, struct genl_info *info, const long unsigned int *wanted, const long unsigned int *wanted_mask, const long unsigned int *active, const long unsigned int *active_mask, bool compact);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/features.c (ffffffff81a93730)
Location: net/ethtool/features.c:157
Inline: False
Direct callers:
  - net/ethtool/features.c:ethnl_set_features
```
**Symbols:**

```
ffffffff81a93730-ffffffff81a9390e: features_send_reply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int features_send_reply(struct net_device *dev, struct genl_info *info, const long unsigned int *wanted, const long unsigned int *wanted_mask, const long unsigned int *active, const long unsigned int *active_mask, bool compact);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/features.c (ffffffff81a7d150)
Location: net/ethtool/features.c:157
Inline: False
Direct callers:
  - net/ethtool/features.c:ethnl_set_features
```
**Symbols:**

```
ffffffff81a7d150-ffffffff81a7d32c: features_send_reply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int features_send_reply(struct net_device *dev, struct genl_info *info, const long unsigned int *wanted, const long unsigned int *wanted_mask, const long unsigned int *active, const long unsigned int *active_mask, bool compact);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ethtool/features.c (0)
Location: net/ethtool/features.c:157
Inline: False
Direct callers:
  - net/ethtool/features.c:ethnl_set_features
```
**Symbols:**

```
ffffffff81b37330-ffffffff81b3751b: features_send_reply (STB_LOCAL)
ffffffff81d39a36-ffffffff81d39a4b: features_send_reply.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int features_send_reply(struct net_device *dev, struct genl_info *info, const long unsigned int *wanted, const long unsigned int *wanted_mask, const long unsigned int *active, const long unsigned int *active_mask, bool compact);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ethtool/features.c (0)
Location: net/ethtool/features.c:156
Inline: False
Direct callers:
  - net/ethtool/features.c:ethnl_set_features
```
**Symbols:**

```
ffffffff81cc2d20-ffffffff81cc2f30: features_send_reply (STB_LOCAL)
ffffffff81f061b1-ffffffff81f061c6: features_send_reply.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int features_send_reply(struct net_device *dev, struct genl_info *info, const long unsigned int *wanted, const long unsigned int *wanted_mask, const long unsigned int *active, const long unsigned int *active_mask, bool compact);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ethtool/features.c (0)
Location: net/ethtool/features.c:156
Inline: False
Direct callers:
  - net/ethtool/features.c:ethnl_set_features
```
**Symbols:**

```
ffffffff81e82010-ffffffff81e82220: features_send_reply (STB_LOCAL)
ffffffff820ade85-ffffffff820ade9a: features_send_reply.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int features_send_reply(struct net_device *dev, struct genl_info *info, const long unsigned int *wanted, const long unsigned int *wanted_mask, const long unsigned int *active, const long unsigned int *active_mask, bool compact);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ethtool/features.c (0)
Location: net/ethtool/features.c:156
Inline: False
Direct callers:
  - net/ethtool/features.c:ethnl_set_features
```
**Symbols:**

```
ffffffff81ede670-ffffffff81ede880: features_send_reply (STB_LOCAL)
ffffffff8212f0d2-ffffffff8212f0e7: features_send_reply.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int features_send_reply(struct net_device *dev, struct genl_info *info, const long unsigned int *wanted, const long unsigned int *wanted_mask, const long unsigned int *active, const long unsigned int *active_mask, bool compact);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ethtool/features.c (0)
Location: net/ethtool/features.c:156
Inline: False
Direct callers:
  - net/ethtool/features.c:ethnl_set_features
```
**Symbols:**

```
ffffffff81fa24a0-ffffffff81fa26b0: features_send_reply (STB_LOCAL)
ffffffff82210e63-ffffffff82210e78: features_send_reply.cold (STB_LOCAL)
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
