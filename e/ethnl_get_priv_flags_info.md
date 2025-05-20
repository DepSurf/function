# Function: <code>ethnl_get_priv_flags_info</code>

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
int ethnl_get_priv_flags_info(struct net_device *dev, unsigned int *count, const char[32] **names);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/privflags.c (ffffffff81a8a3b0)
Location: net/ethtool/privflags.c:28
Inline: False
Direct callers:
  - net/ethtool/privflags.c:ethnl_set_privflags
  - net/ethtool/privflags.c:privflags_prepare_data
  - net/ethtool/privflags.c:privflags_prepare_data
```
**Symbols:**

```
ffffffff81a8a3b0-ffffffff81a8a49a: ethnl_get_priv_flags_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ethnl_get_priv_flags_info(struct net_device *dev, unsigned int *count, const char[32] **names);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/privflags.c (ffffffff81a93c10)
Location: net/ethtool/privflags.c:26
Inline: False
Direct callers:
  - net/ethtool/privflags.c:ethnl_set_privflags
  - net/ethtool/privflags.c:privflags_prepare_data
  - net/ethtool/privflags.c:privflags_prepare_data
```
**Symbols:**

```
ffffffff81a93c10-ffffffff81a93cfa: ethnl_get_priv_flags_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ethnl_get_priv_flags_info(struct net_device *dev, unsigned int *count, const char[32] **names);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/privflags.c (ffffffff81a7d610)
Location: net/ethtool/privflags.c:26
Inline: False
Direct callers:
  - net/ethtool/privflags.c:ethnl_set_privflags
  - net/ethtool/privflags.c:privflags_prepare_data
  - net/ethtool/privflags.c:privflags_prepare_data
```
**Symbols:**

```
ffffffff81a7d610-ffffffff81a7d6f9: ethnl_get_priv_flags_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ethnl_get_priv_flags_info(struct net_device *dev, unsigned int *count, const char[32] **names);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ethtool/privflags.c (0)
Location: net/ethtool/privflags.c:26
Inline: False
Direct callers:
  - net/ethtool/privflags.c:ethnl_set_privflags
  - net/ethtool/privflags.c:privflags_prepare_data
```
**Symbols:**

```
ffffffff81b37850-ffffffff81b37945: ethnl_get_priv_flags_info (STB_LOCAL)
ffffffff81d39a95-ffffffff81d39aa9: ethnl_get_priv_flags_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ethnl_get_priv_flags_info(struct net_device *dev, unsigned int *count, const char[32] **names);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ethtool/privflags.c (0)
Location: net/ethtool/privflags.c:26
Inline: False
Direct callers:
  - net/ethtool/privflags.c:ethnl_set_privflags
  - net/ethtool/privflags.c:privflags_prepare_data
```
**Symbols:**

```
ffffffff81cc32d0-ffffffff81cc33c8: ethnl_get_priv_flags_info (STB_LOCAL)
ffffffff81f06210-ffffffff81f06225: ethnl_get_priv_flags_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int ethnl_get_priv_flags_info(struct net_device *dev, unsigned int *count, const char[32] **names);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ethtool/privflags.c (0)
Location: net/ethtool/privflags.c:26
Inline: False
Direct callers:
  - net/ethtool/privflags.c:ethnl_set_privflags
  - net/ethtool/privflags.c:privflags_prepare_data
```
**Symbols:**

```
ffffffff81e82610-ffffffff81e82708: ethnl_get_priv_flags_info (STB_LOCAL)
ffffffff820adee4-ffffffff820adef9: ethnl_get_priv_flags_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int ethnl_get_priv_flags_info(struct net_device *dev, unsigned int *count, const char[32] **names);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ethtool/privflags.c (0)
Location: net/ethtool/privflags.c:26
Inline: False
Direct callers:
  - net/ethtool/privflags.c:ethnl_set_privflags
  - net/ethtool/privflags.c:privflags_prepare_data
```
**Symbols:**

```
ffffffff81eded00-ffffffff81ededf8: ethnl_get_priv_flags_info (STB_LOCAL)
ffffffff8212f131-ffffffff8212f146: ethnl_get_priv_flags_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int ethnl_get_priv_flags_info(struct net_device *dev, unsigned int *count, const char[32] **names);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ethtool/privflags.c (0)
Location: net/ethtool/privflags.c:26
Inline: False
Direct callers:
  - net/ethtool/privflags.c:ethnl_set_privflags
  - net/ethtool/privflags.c:privflags_prepare_data
```
**Symbols:**

```
ffffffff81fa2b30-ffffffff81fa2c3e: ethnl_get_priv_flags_info (STB_LOCAL)
ffffffff82210ec2-ffffffff82210ed7: ethnl_get_priv_flags_info.cold (STB_LOCAL)
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
