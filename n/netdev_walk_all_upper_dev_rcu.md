# Function: <code>netdev_walk_all_upper_dev_rcu</code>

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
int netdev_walk_all_upper_dev_rcu(struct net_device *dev, int (*fn)(struct net_device *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817a8cc0)
Location: net/core/dev.c:5564
Inline: False
Direct callers:
  - net/core/dev.c:netdev_walk_all_upper_dev_rcu
  - net/core/dev.c:netdev_has_upper_dev_all_rcu
  - net/core/dev.c:netdev_has_upper_dev
```
**Symbols:**

```
ffffffff817a8cc0-ffffffff817a8d28: netdev_walk_all_upper_dev_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int netdev_walk_all_upper_dev_rcu(struct net_device *dev, int (*fn)(struct net_device *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817c7360)
Location: net/core/dev.c:5770
Inline: False
Direct callers:
  - net/core/dev.c:netdev_walk_all_upper_dev_rcu
  - net/core/dev.c:netdev_has_upper_dev_all_rcu
  - net/core/dev.c:netdev_has_upper_dev
```
**Symbols:**

```
ffffffff817c7360-ffffffff817c73c8: netdev_walk_all_upper_dev_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int netdev_walk_all_upper_dev_rcu(struct net_device *dev, int (*fn)(struct net_device *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81840f40)
Location: net/core/dev.c:5911
Inline: False
Direct callers:
  - net/core/dev.c:netdev_walk_all_upper_dev_rcu
  - net/core/dev.c:netdev_has_upper_dev_all_rcu
  - net/core/dev.c:netdev_has_upper_dev
```
**Symbols:**

```
ffffffff81840f40-ffffffff81840faa: netdev_walk_all_upper_dev_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int netdev_walk_all_upper_dev_rcu(struct net_device *dev, int (*fn)(struct net_device *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8188b590)
Location: net/core/dev.c:6041
Inline: False
Direct callers:
  - net/core/dev.c:netdev_walk_all_upper_dev_rcu
  - net/core/dev.c:netdev_has_upper_dev_all_rcu
  - net/core/dev.c:netdev_has_upper_dev
```
**Symbols:**

```
ffffffff8188b590-ffffffff8188b5fa: netdev_walk_all_upper_dev_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int netdev_walk_all_upper_dev_rcu(struct net_device *dev, int (*fn)(struct net_device *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818ac710)
Location: net/core/dev.c:6616
Inline: False
Direct callers:
  - net/core/dev.c:netdev_walk_all_upper_dev_rcu
  - net/core/dev.c:netdev_has_upper_dev_all_rcu
  - net/core/dev.c:netdev_has_upper_dev
```
**Symbols:**

```
ffffffff818ac710-ffffffff818ac77a: netdev_walk_all_upper_dev_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int netdev_walk_all_upper_dev_rcu(struct net_device *dev, int (*fn)(struct net_device *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818f7f50)
Location: net/core/dev.c:6626
Inline: False
Direct callers:
  - net/core/dev.c:netdev_walk_all_upper_dev_rcu
  - net/core/dev.c:netdev_has_upper_dev_all_rcu
  - net/core/dev.c:netdev_has_upper_dev
```
**Symbols:**

```
ffffffff818f7f50-ffffffff818f7fba: netdev_walk_all_upper_dev_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int netdev_walk_all_upper_dev_rcu(struct net_device *dev, int (*fn)(struct net_device *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81929e00)
Location: net/core/dev.c:6651
Inline: False
Direct callers:
  - net/core/dev.c:netdev_has_upper_dev_all_rcu
  - net/core/dev.c:netdev_has_upper_dev
```
**Symbols:**

```
ffffffff81929e00-ffffffff81929edb: netdev_walk_all_upper_dev_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int netdev_walk_all_upper_dev_rcu(struct net_device *dev, int (*fn)(struct net_device *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819fde40)
Location: net/core/dev.c:7042
Inline: False
Direct callers:
  - net/core/dev.c:netdev_has_upper_dev_all_rcu
  - net/core/dev.c:netdev_has_upper_dev
```
**Symbols:**

```
ffffffff819fde40-ffffffff819fdf1b: netdev_walk_all_upper_dev_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int netdev_walk_all_upper_dev_rcu(struct net_device *dev, int (*fn)(struct net_device *, struct netdev_nested_priv *), struct netdev_nested_priv *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819fd990)
Location: net/core/dev.c:7199
Inline: False
Direct callers:
  - net/core/dev.c:netdev_has_upper_dev_all_rcu
  - net/core/dev.c:netdev_has_upper_dev
```
**Symbols:**

```
ffffffff819fd990-ffffffff819fda6b: netdev_walk_all_upper_dev_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int netdev_walk_all_upper_dev_rcu(struct net_device *dev, int (*fn)(struct net_device *, struct netdev_nested_priv *), struct netdev_nested_priv *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819e4180)
Location: net/core/dev.c:7458
Inline: False
Direct callers:
  - net/core/dev.c:netdev_has_upper_dev_all_rcu
  - net/core/dev.c:netdev_has_upper_dev
```
**Symbols:**

```
ffffffff819e4180-ffffffff819e425b: netdev_walk_all_upper_dev_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int netdev_walk_all_upper_dev_rcu(struct net_device *dev, int (*fn)(struct net_device *, struct netdev_nested_priv *), struct netdev_nested_priv *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a94990)
Location: net/core/dev.c:7448
Inline: False
Direct callers:
  - net/core/dev.c:netdev_has_upper_dev_all_rcu
  - net/core/dev.c:netdev_has_upper_dev
```
**Symbols:**

```
ffffffff81a94990-ffffffff81a94b52: netdev_walk_all_upper_dev_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int netdev_walk_all_upper_dev_rcu(struct net_device *dev, int (*fn)(struct net_device *, struct netdev_nested_priv *), struct netdev_nested_priv *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c0ae90)
Location: net/core/dev.c:6969
Inline: False
Direct callers:
  - net/core/dev.c:netdev_has_upper_dev_all_rcu
  - net/core/dev.c:netdev_has_upper_dev
```
**Symbols:**

```
ffffffff81c0ae90-ffffffff81c0b07a: netdev_walk_all_upper_dev_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int netdev_walk_all_upper_dev_rcu(struct net_device *dev, int (*fn)(struct net_device *, struct netdev_nested_priv *), struct netdev_nested_priv *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dbae30)
Location: net/core/dev.c:6955
Inline: False
Direct callers:
  - net/core/dev.c:netdev_has_upper_dev_all_rcu
  - net/core/dev.c:netdev_has_upper_dev
```
**Symbols:**

```
ffffffff81dbae30-ffffffff81dbb01a: netdev_walk_all_upper_dev_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int netdev_walk_all_upper_dev_rcu(struct net_device *dev, int (*fn)(struct net_device *, struct netdev_nested_priv *), struct netdev_nested_priv *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e2b5c0)
Location: net/core/dev.c:6960
Inline: False
Direct callers:
  - net/core/dev.c:netdev_has_upper_dev_all_rcu
  - net/core/dev.c:netdev_has_upper_dev
```
**Symbols:**

```
ffffffff81e2b5c0-ffffffff81e2b7aa: netdev_walk_all_upper_dev_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int netdev_walk_all_upper_dev_rcu(struct net_device *dev, int (*fn)(struct net_device *, struct netdev_nested_priv *), struct netdev_nested_priv *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81ee9620)
Location: net/core/dev.c:7078
Inline: False
Direct callers:
  - net/core/dev.c:netdev_has_upper_dev_all_rcu
  - net/core/dev.c:netdev_has_upper_dev
```
**Symbols:**

```
ffffffff81ee9620-ffffffff81ee980a: netdev_walk_all_upper_dev_rcu (STB_GLOBAL)
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
int netdev_walk_all_upper_dev_rcu(struct net_device *dev, int (*fn)(struct net_device *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bc6598)
Location: net/core/dev.c:6651
Inline: False
Direct callers:
  - net/core/dev.c:netdev_has_upper_dev_all_rcu
  - net/core/dev.c:netdev_has_upper_dev
```
**Symbols:**

```
ffff800010bc6598-ffff800010bc6698: netdev_walk_all_upper_dev_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int netdev_walk_all_upper_dev_rcu(struct net_device *dev, int (*fn)(struct net_device *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0ce1b44)
Location: net/core/dev.c:6651
Inline: False
Direct callers:
  - net/core/dev.c:netdev_has_upper_dev_all_rcu
  - net/core/dev.c:netdev_has_upper_dev
```
**Symbols:**

```
c0ce1b44-c0ce1c2c: netdev_walk_all_upper_dev_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int netdev_walk_all_upper_dev_rcu(struct net_device *dev, int (*fn)(struct net_device *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000ca1190)
Location: net/core/dev.c:6651
Inline: False
Direct callers:
  - net/core/dev.c:netdev_has_upper_dev_all_rcu
  - net/core/dev.c:netdev_has_upper_dev
```
**Symbols:**

```
c000000000ca1190-c000000000ca12d8: netdev_walk_all_upper_dev_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int netdev_walk_all_upper_dev_rcu(struct net_device *dev, int (*fn)(struct net_device *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe000752cd0)
Location: net/core/dev.c:6651
Inline: False
Direct callers:
  - net/core/dev.c:netdev_has_upper_dev_all_rcu
  - net/core/dev.c:netdev_has_upper_dev
```
**Symbols:**

```
ffffffe000752cd0-ffffffe000752d78: netdev_walk_all_upper_dev_rcu (STB_GLOBAL)
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
int netdev_walk_all_upper_dev_rcu(struct net_device *dev, int (*fn)(struct net_device *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818c9e00)
Location: net/core/dev.c:6651
Inline: False
Direct callers:
  - net/core/dev.c:netdev_has_upper_dev_all_rcu
  - net/core/dev.c:netdev_has_upper_dev
```
**Symbols:**

```
ffffffff818c9e00-ffffffff818c9edb: netdev_walk_all_upper_dev_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int netdev_walk_all_upper_dev_rcu(struct net_device *dev, int (*fn)(struct net_device *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81883d40)
Location: net/core/dev.c:6651
Inline: False
Direct callers:
  - net/core/dev.c:netdev_has_upper_dev_all_rcu
  - net/core/dev.c:netdev_has_upper_dev
```
**Symbols:**

```
ffffffff81883d40-ffffffff81883e1b: netdev_walk_all_upper_dev_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int netdev_walk_all_upper_dev_rcu(struct net_device *dev, int (*fn)(struct net_device *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8191ae00)
Location: net/core/dev.c:6651
Inline: False
Direct callers:
  - net/core/dev.c:netdev_has_upper_dev_all_rcu
  - net/core/dev.c:netdev_has_upper_dev
```
**Symbols:**

```
ffffffff8191ae00-ffffffff8191aedb: netdev_walk_all_upper_dev_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int netdev_walk_all_upper_dev_rcu(struct net_device *dev, int (*fn)(struct net_device *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8193c000)
Location: net/core/dev.c:6651
Inline: False
Direct callers:
  - net/core/dev.c:netdev_has_upper_dev_all_rcu
  - net/core/dev.c:netdev_has_upper_dev
```
**Symbols:**

```
ffffffff8193c000-ffffffff8193c0db: netdev_walk_all_upper_dev_rcu (STB_GLOBAL)
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
