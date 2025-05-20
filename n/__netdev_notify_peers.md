# Function: <code>__netdev_notify_peers</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __netdev_notify_peers(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819fec00)
Location: net/core/dev.c:1482
Inline: False
Direct callers:
  - net/core/dev.c:netdev_notify_peers
```
**Symbols:**

```
ffffffff819fec00-ffffffff819feca3: __netdev_notify_peers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __netdev_notify_peers(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819e54a0)
Location: net/core/dev.c:1530
Inline: False
Direct callers:
  - net/core/dev.c:netdev_notify_peers
```
**Symbols:**

```
ffffffff819e54a0-ffffffff819e5543: __netdev_notify_peers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __netdev_notify_peers(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:1405
Inline: False
Direct callers:
  - net/core/dev.c:netdev_notify_peers
```
**Symbols:**

```
ffffffff81d35874-ffffffff81d35889: __netdev_notify_peers.cold (STB_LOCAL)
ffffffff81a972c0-ffffffff81a9737a: __netdev_notify_peers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __netdev_notify_peers(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:1352
Inline: False
Direct callers:
  - net/core/dev.c:netdev_notify_peers
```
**Symbols:**

```
ffffffff81f01e76-ffffffff81f01e8b: __netdev_notify_peers.cold (STB_LOCAL)
ffffffff81c0e1a0-ffffffff81c0e266: __netdev_notify_peers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void __netdev_notify_peers(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:1337
Inline: False
Direct callers:
  - net/core/dev.c:netdev_notify_peers
```
**Symbols:**

```
ffffffff820ab1f8-ffffffff820ab20d: __netdev_notify_peers.cold (STB_LOCAL)
ffffffff81dbe210-ffffffff81dbe2d6: __netdev_notify_peers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void __netdev_notify_peers(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:1362
Inline: False
Direct callers:
  - net/core/dev.c:netdev_notify_peers
```
**Symbols:**

```
ffffffff8212cc10-ffffffff8212cc25: __netdev_notify_peers.cold (STB_LOCAL)
ffffffff81e37fc0-ffffffff81e38086: __netdev_notify_peers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void __netdev_notify_peers(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:1366
Inline: False
Direct callers:
  - net/core/dev.c:netdev_notify_peers
```
**Symbols:**

```
ffffffff8220e94e-ffffffff8220e963: __netdev_notify_peers.cold (STB_LOCAL)
ffffffff81ef6010-ffffffff81ef60d6: __netdev_notify_peers (STB_GLOBAL)
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
