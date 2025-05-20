# Function: <code>netdev_walk_all_lower_dev_rcu</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int netdev_walk_all_lower_dev_rcu(struct net_device *dev, int (*fn)(struct net_device *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817a8e50)
Location: net/core/dev.c:5730
Inline: False
Direct callers:
  - net/core/dev.c:netdev_walk_all_lower_dev_rcu
```
**Symbols:**

```
ffffffff817a8e50-ffffffff817a8eb8: netdev_walk_all_lower_dev_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int netdev_walk_all_lower_dev_rcu(struct net_device *dev, int (*fn)(struct net_device *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817c74f0)
Location: net/core/dev.c:5936
Inline: False
Direct callers:
  - net/core/dev.c:netdev_walk_all_lower_dev_rcu
```
**Symbols:**

```
ffffffff817c74f0-ffffffff817c7558: netdev_walk_all_lower_dev_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int netdev_walk_all_lower_dev_rcu(struct net_device *dev, int (*fn)(struct net_device *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818410d0)
Location: net/core/dev.c:6077
Inline: False
Direct callers:
  - net/core/dev.c:netdev_walk_all_lower_dev_rcu
```
**Symbols:**

```
ffffffff818410d0-ffffffff8184113a: netdev_walk_all_lower_dev_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int netdev_walk_all_lower_dev_rcu(struct net_device *dev, int (*fn)(struct net_device *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8188b720)
Location: net/core/dev.c:6207
Inline: False
Direct callers:
  - net/core/dev.c:netdev_walk_all_lower_dev_rcu
```
**Symbols:**

```
ffffffff8188b720-ffffffff8188b78a: netdev_walk_all_lower_dev_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int netdev_walk_all_lower_dev_rcu(struct net_device *dev, int (*fn)(struct net_device *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818ac8a0)
Location: net/core/dev.c:6782
Inline: False
Direct callers:
  - net/core/dev.c:netdev_walk_all_lower_dev_rcu
```
**Symbols:**

```
ffffffff818ac8a0-ffffffff818ac90a: netdev_walk_all_lower_dev_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int netdev_walk_all_lower_dev_rcu(struct net_device *dev, int (*fn)(struct net_device *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818f80e0)
Location: net/core/dev.c:6792
Inline: False
Direct callers:
  - net/core/dev.c:netdev_walk_all_lower_dev_rcu
```
**Symbols:**

```
ffffffff818f80e0-ffffffff818f814a: netdev_walk_all_lower_dev_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int netdev_walk_all_lower_dev_rcu(struct net_device *dev, int (*fn)(struct net_device *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8192a180)
Location: net/core/dev.c:6983
Inline: False
```
**Symbols:**

```
ffffffff8192a180-ffffffff8192a25b: netdev_walk_all_lower_dev_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int netdev_walk_all_lower_dev_rcu(struct net_device *dev, int (*fn)(struct net_device *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:7374
Inline: False
```
**Symbols:**

```
ffffffff819fe0e0-ffffffff819fe0ef: netdev_walk_all_lower_dev_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int netdev_walk_all_lower_dev_rcu(struct net_device *dev, int (*fn)(struct net_device *, struct netdev_nested_priv *), struct netdev_nested_priv *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:7548
Inline: False
```
**Symbols:**

```
ffffffff819fdc70-ffffffff819fdc7f: netdev_walk_all_lower_dev_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int netdev_walk_all_lower_dev_rcu(struct net_device *dev, int (*fn)(struct net_device *, struct netdev_nested_priv *), struct netdev_nested_priv *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819e4460)
Location: net/core/dev.c:7807
Inline: False
```
**Symbols:**

```
ffffffff819e4460-ffffffff819e453b: netdev_walk_all_lower_dev_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int netdev_walk_all_lower_dev_rcu(struct net_device *dev, int (*fn)(struct net_device *, struct netdev_nested_priv *), struct netdev_nested_priv *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a94e50)
Location: net/core/dev.c:7797
Inline: False
Direct callers:
  - net/switchdev/switchdev.c:__switchdev_handle_fdb_add_to_device
  - net/switchdev/switchdev.c:__switchdev_handle_fdb_add_to_device
  - net/switchdev/switchdev.c:__switchdev_handle_fdb_add_to_device
  - net/switchdev/switchdev.c:__switchdev_handle_fdb_add_to_device
```
**Symbols:**

```
ffffffff81a94e50-ffffffff81a95012: netdev_walk_all_lower_dev_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int netdev_walk_all_lower_dev_rcu(struct net_device *dev, int (*fn)(struct net_device *, struct netdev_nested_priv *), struct netdev_nested_priv *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c0b3d0)
Location: net/core/dev.c:7328
Inline: False
Direct callers:
  - net/switchdev/switchdev.c:__switchdev_handle_fdb_event_to_device
  - net/switchdev/switchdev.c:__switchdev_handle_fdb_event_to_device
```
**Symbols:**

```
ffffffff81c0b3d0-ffffffff81c0b5ba: netdev_walk_all_lower_dev_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int netdev_walk_all_lower_dev_rcu(struct net_device *dev, int (*fn)(struct net_device *, struct netdev_nested_priv *), struct netdev_nested_priv *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dbb3e0)
Location: net/core/dev.c:7314
Inline: False
Direct callers:
  - net/switchdev/switchdev.c:__switchdev_handle_fdb_event_to_device
  - net/switchdev/switchdev.c:__switchdev_handle_fdb_event_to_device
```
**Symbols:**

```
ffffffff81dbb3e0-ffffffff81dbb5ca: netdev_walk_all_lower_dev_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int netdev_walk_all_lower_dev_rcu(struct net_device *dev, int (*fn)(struct net_device *, struct netdev_nested_priv *), struct netdev_nested_priv *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e2bb70)
Location: net/core/dev.c:7319
Inline: False
Direct callers:
  - net/switchdev/switchdev.c:__switchdev_handle_fdb_event_to_device
  - net/switchdev/switchdev.c:__switchdev_handle_fdb_event_to_device
```
**Symbols:**

```
ffffffff81e2bb70-ffffffff81e2bd5a: netdev_walk_all_lower_dev_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int netdev_walk_all_lower_dev_rcu(struct net_device *dev, int (*fn)(struct net_device *, struct netdev_nested_priv *), struct netdev_nested_priv *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81ee9bd0)
Location: net/core/dev.c:7437
Inline: False
Direct callers:
  - net/switchdev/switchdev.c:__switchdev_handle_fdb_event_to_device
  - net/switchdev/switchdev.c:__switchdev_handle_fdb_event_to_device
```
**Symbols:**

```
ffffffff81ee9bd0-ffffffff81ee9dba: netdev_walk_all_lower_dev_rcu (STB_GLOBAL)
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
int netdev_walk_all_lower_dev_rcu(struct net_device *dev, int (*fn)(struct net_device *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bc6a60)
Location: net/core/dev.c:6983
Inline: False
```
**Symbols:**

```
ffff800010bc6a60-ffff800010bc6b60: netdev_walk_all_lower_dev_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int netdev_walk_all_lower_dev_rcu(struct net_device *dev, int (*fn)(struct net_device *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0ce1f24)
Location: net/core/dev.c:6983
Inline: False
```
**Symbols:**

```
c0ce1f24-c0ce200c: netdev_walk_all_lower_dev_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int netdev_walk_all_lower_dev_rcu(struct net_device *dev, int (*fn)(struct net_device *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000ca16a0)
Location: net/core/dev.c:6983
Inline: False
```
**Symbols:**

```
c000000000ca16a0-c000000000ca17e8: netdev_walk_all_lower_dev_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int netdev_walk_all_lower_dev_rcu(struct net_device *dev, int (*fn)(struct net_device *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe000753042)
Location: net/core/dev.c:6983
Inline: False
```
**Symbols:**

```
ffffffe000753042-ffffffe0007530ea: netdev_walk_all_lower_dev_rcu (STB_GLOBAL)
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
int netdev_walk_all_lower_dev_rcu(struct net_device *dev, int (*fn)(struct net_device *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818ca180)
Location: net/core/dev.c:6983
Inline: False
```
**Symbols:**

```
ffffffff818ca180-ffffffff818ca25b: netdev_walk_all_lower_dev_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int netdev_walk_all_lower_dev_rcu(struct net_device *dev, int (*fn)(struct net_device *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818840c0)
Location: net/core/dev.c:6983
Inline: False
```
**Symbols:**

```
ffffffff818840c0-ffffffff8188419b: netdev_walk_all_lower_dev_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int netdev_walk_all_lower_dev_rcu(struct net_device *dev, int (*fn)(struct net_device *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8191b180)
Location: net/core/dev.c:6983
Inline: False
```
**Symbols:**

```
ffffffff8191b180-ffffffff8191b25b: netdev_walk_all_lower_dev_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int netdev_walk_all_lower_dev_rcu(struct net_device *dev, int (*fn)(struct net_device *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8193c380)
Location: net/core/dev.c:6983
Inline: False
```
**Symbols:**

```
ffffffff8193c380-ffffffff8193c45b: netdev_walk_all_lower_dev_rcu (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct netdev_nested_priv *priv</code>
</li>
<li>
<b>Param removed. </b>
<code>void *data</code>
</li>
<li>
<b>Param type changed. </b>
<code>int (*fn)(struct net_device *, void *)</code> ➡️ <code>int (*fn)(struct net_device *, struct netdev_nested_priv *)</code>
</li>
</ul>
</details>
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
