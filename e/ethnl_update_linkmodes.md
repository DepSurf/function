# Function: <code>ethnl_update_linkmodes</code>

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
int ethnl_update_linkmodes(struct genl_info *info, struct nlattr **tb, struct ethtool_link_ksettings *ksettings, bool *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/linkmodes.c (ffffffff81a88d80)
Location: net/ethtool/linkmodes.c:324
Inline: False
Direct callers:
  - net/ethtool/linkmodes.c:ethnl_set_linkmodes
```
**Symbols:**

```
ffffffff81a88d80-ffffffff81a88f07: ethnl_update_linkmodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ethnl_update_linkmodes(struct genl_info *info, struct nlattr **tb, struct ethtool_link_ksettings *ksettings, bool *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/linkmodes.c (ffffffff81a92660)
Location: net/ethtool/linkmodes.c:328
Inline: False
Direct callers:
  - net/ethtool/linkmodes.c:ethnl_set_linkmodes
```
**Symbols:**

```
ffffffff81a92660-ffffffff81a927f7: ethnl_update_linkmodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ethnl_update_linkmodes(struct genl_info *info, struct nlattr **tb, struct ethtool_link_ksettings *ksettings, bool *mod, const struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/linkmodes.c (ffffffff81a7bee0)
Location: net/ethtool/linkmodes.c:243
Inline: False
Direct callers:
  - net/ethtool/linkmodes.c:ethnl_set_linkmodes
```
**Symbols:**

```
ffffffff81a7bee0-ffffffff81a7c10c: ethnl_update_linkmodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ethnl_update_linkmodes(struct genl_info *info, struct nlattr **tb, struct ethtool_link_ksettings *ksettings, bool *mod, const struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/linkmodes.c (ffffffff81b36260)
Location: net/ethtool/linkmodes.c:243
Inline: False
Direct callers:
  - net/ethtool/linkmodes.c:ethnl_set_linkmodes
```
**Symbols:**

```
ffffffff81b36260-ffffffff81b3648c: ethnl_update_linkmodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ethnl_update_linkmodes(struct genl_info *info, struct nlattr **tb, struct ethtool_link_ksettings *ksettings, bool *mod, const struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/linkmodes.c (ffffffff81cc1b90)
Location: net/ethtool/linkmodes.c:243
Inline: False
Direct callers:
  - net/ethtool/linkmodes.c:ethnl_set_linkmodes
```
**Symbols:**

```
ffffffff81cc1b90-ffffffff81cc1dcc: ethnl_update_linkmodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ethnl_update_linkmodes(struct genl_info *info, struct nlattr **tb, struct ethtool_link_ksettings *ksettings, bool *mod, const struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/linkmodes.c (ffffffff81e80960)
Location: net/ethtool/linkmodes.c:248
Inline: False
Direct callers:
  - net/ethtool/linkmodes.c:ethnl_set_linkmodes
```
**Symbols:**

```
ffffffff81e80960-ffffffff81e80b9c: ethnl_update_linkmodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ethnl_update_linkmodes(struct genl_info *info, struct nlattr **tb, struct ethtool_link_ksettings *ksettings, bool *mod, const struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/linkmodes.c (ffffffff81edd1a0)
Location: net/ethtool/linkmodes.c:236
Inline: False
Direct callers:
  - net/ethtool/linkmodes.c:ethnl_set_linkmodes
```
**Symbols:**

```
ffffffff81edd1a0-ffffffff81edd3e8: ethnl_update_linkmodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ethnl_update_linkmodes(struct genl_info *info, struct nlattr **tb, struct ethtool_link_ksettings *ksettings, bool *mod, const struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/linkmodes.c (ffffffff81fa0f70)
Location: net/ethtool/linkmodes.c:236
Inline: False
Direct callers:
  - net/ethtool/linkmodes.c:ethnl_set_linkmodes
```
**Symbols:**

```
ffffffff81fa0f70-ffffffff81fa11b8: ethnl_update_linkmodes (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct net_device *dev</code>
</li>
</ul>
</details>
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
