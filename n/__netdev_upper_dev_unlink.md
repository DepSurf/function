# Function: <code>__netdev_upper_dev_unlink</code>

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
void __netdev_upper_dev_unlink(struct net_device *dev, struct net_device *upper_dev, struct netdev_nested_priv *priv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a04390)
Location: net/core/dev.c:7945
Inline: False
Direct callers:
  - net/core/dev.c:netdev_adjacent_change_abort
  - net/core/dev.c:netdev_adjacent_change_commit
  - net/core/dev.c:netdev_upper_dev_unlink
```
**Symbols:**

```
ffffffff81a04390-ffffffff81a04570: __netdev_upper_dev_unlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __netdev_upper_dev_unlink(struct net_device *dev, struct net_device *upper_dev, struct netdev_nested_priv *priv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819eb7f0)
Location: net/core/dev.c:8204
Inline: False
Direct callers:
  - net/core/dev.c:netdev_adjacent_change_abort
  - net/core/dev.c:netdev_adjacent_change_commit
  - net/core/dev.c:netdev_upper_dev_unlink
```
**Symbols:**

```
ffffffff819eb7f0-ffffffff819eb9d9: __netdev_upper_dev_unlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __netdev_upper_dev_unlink(struct net_device *dev, struct net_device *upper_dev, struct netdev_nested_priv *priv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:8194
Inline: False
Direct callers:
  - net/core/dev.c:netdev_adjacent_change_abort
  - net/core/dev.c:netdev_adjacent_change_commit
  - net/core/dev.c:netdev_upper_dev_unlink
```
**Symbols:**

```
ffffffff81a9c770-ffffffff81a9c8cb: __netdev_upper_dev_unlink (STB_LOCAL)
ffffffff81d36135-ffffffff81d36149: __netdev_upper_dev_unlink.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __netdev_upper_dev_unlink(struct net_device *dev, struct net_device *upper_dev, struct netdev_nested_priv *priv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:7725
Inline: False
Direct callers:
  - net/core/dev.c:netdev_adjacent_change_abort
  - net/core/dev.c:netdev_adjacent_change_commit
  - net/core/dev.c:netdev_upper_dev_unlink
```
**Symbols:**

```
ffffffff81c16430-ffffffff81c1659b: __netdev_upper_dev_unlink (STB_LOCAL)
ffffffff81f029d8-ffffffff81f029ed: __netdev_upper_dev_unlink.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void __netdev_upper_dev_unlink(struct net_device *dev, struct net_device *upper_dev, struct netdev_nested_priv *priv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:7711
Inline: False
Direct callers:
  - net/core/dev.c:netdev_adjacent_change_abort
  - net/core/dev.c:netdev_adjacent_change_commit
  - net/core/dev.c:netdev_upper_dev_unlink
```
**Symbols:**

```
ffffffff81dc77d0-ffffffff81dc793b: __netdev_upper_dev_unlink (STB_LOCAL)
ffffffff820ab598-ffffffff820ab5ad: __netdev_upper_dev_unlink.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void __netdev_upper_dev_unlink(struct net_device *dev, struct net_device *upper_dev, struct netdev_nested_priv *priv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:7716
Inline: False
Direct callers:
  - net/core/dev.c:netdev_adjacent_change_abort
  - net/core/dev.c:netdev_adjacent_change_commit
  - net/core/dev.c:netdev_upper_dev_unlink
```
**Symbols:**

```
ffffffff81e39580-ffffffff81e396eb: __netdev_upper_dev_unlink (STB_LOCAL)
ffffffff8212ccda-ffffffff8212ccef: __netdev_upper_dev_unlink.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void __netdev_upper_dev_unlink(struct net_device *dev, struct net_device *upper_dev, struct netdev_nested_priv *priv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:7834
Inline: False
Direct callers:
  - net/core/dev.c:netdev_adjacent_change_abort
  - net/core/dev.c:netdev_adjacent_change_commit
  - net/core/dev.c:netdev_upper_dev_unlink
```
**Symbols:**

```
ffffffff81ef7870-ffffffff81ef79db: __netdev_upper_dev_unlink (STB_LOCAL)
ffffffff8220ea19-ffffffff8220ea2e: __netdev_upper_dev_unlink.cold (STB_LOCAL)
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
