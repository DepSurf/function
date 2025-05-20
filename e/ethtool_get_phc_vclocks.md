# Function: <code>ethtool_get_phc_vclocks</code>

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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ethtool_get_phc_vclocks(struct net_device *dev, int **vclock_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/common.c (ffffffff81b32980)
Location: net/ethtool/common.c:559
Inline: False
Direct callers:
  - net/core/sock.c:sock_set_timestamping
  - net/ethtool/phc_vclocks.c:phc_vclocks_prepare_data
```
**Symbols:**

```
ffffffff81b32980-ffffffff81b329fd: ethtool_get_phc_vclocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ethtool_get_phc_vclocks(struct net_device *dev, int **vclock_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/common.c (ffffffff81cbdf20)
Location: net/ethtool/common.c:563
Inline: False
Direct callers:
  - net/core/sock.c:sock_set_timestamping
  - net/ethtool/phc_vclocks.c:phc_vclocks_prepare_data
```
**Symbols:**

```
ffffffff81cbdf20-ffffffff81cbdfa6: ethtool_get_phc_vclocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ethtool_get_phc_vclocks(struct net_device *dev, int **vclock_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/common.c (ffffffff81e7c970)
Location: net/ethtool/common.c:644
Inline: False
Direct callers:
  - net/core/sock.c:sock_set_timestamping
  - net/ethtool/phc_vclocks.c:phc_vclocks_prepare_data
```
**Symbols:**

```
ffffffff81e7c970-ffffffff81e7c9f6: ethtool_get_phc_vclocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ethtool_get_phc_vclocks(struct net_device *dev, int **vclock_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/common.c (ffffffff81ed8d30)
Location: net/ethtool/common.c:652
Inline: False
Direct callers:
  - net/core/sock.c:sock_set_timestamping
  - net/ethtool/phc_vclocks.c:phc_vclocks_prepare_data
```
**Symbols:**

```
ffffffff81ed8d30-ffffffff81ed8db6: ethtool_get_phc_vclocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ethtool_get_phc_vclocks(struct net_device *dev, int **vclock_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/common.c (ffffffff81f9cba0)
Location: net/ethtool/common.c:652
Inline: False
Direct callers:
  - net/core/sock.c:sock_set_timestamping
  - net/ethtool/phc_vclocks.c:phc_vclocks_prepare_data
```
**Symbols:**

```
ffffffff81f9cba0-ffffffff81f9cc26: ethtool_get_phc_vclocks (STB_GLOBAL)
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
