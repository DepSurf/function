# Function: <code>netdev_get_xmit_slave</code>

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
struct net_device *netdev_get_xmit_slave(struct net_device *dev, struct sk_buff *skb, bool all_slaves);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819fe170)
Location: net/core/dev.c:7912
Inline: False
```
**Symbols:**

```
ffffffff819fe170-ffffffff819fe199: netdev_get_xmit_slave (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct net_device *netdev_get_xmit_slave(struct net_device *dev, struct sk_buff *skb, bool all_slaves);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819fdd00)
Location: net/core/dev.c:8124
Inline: False
```
**Symbols:**

```
ffffffff819fdd00-ffffffff819fdd29: netdev_get_xmit_slave (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct net_device *netdev_get_xmit_slave(struct net_device *dev, struct sk_buff *skb, bool all_slaves);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819e45c0)
Location: net/core/dev.c:8383
Inline: False
```
**Symbols:**

```
ffffffff819e45c0-ffffffff819e45e9: netdev_get_xmit_slave (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct net_device *netdev_get_xmit_slave(struct net_device *dev, struct sk_buff *skb, bool all_slaves);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a950a0)
Location: net/core/dev.c:8373
Inline: False
```
**Symbols:**

```
ffffffff81a950a0-ffffffff81a950c9: netdev_get_xmit_slave (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct net_device *netdev_get_xmit_slave(struct net_device *dev, struct sk_buff *skb, bool all_slaves);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c0b6d0)
Location: net/core/dev.c:8140
Inline: False
```
**Symbols:**

```
ffffffff81c0b6d0-ffffffff81c0b70d: netdev_get_xmit_slave (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct net_device *netdev_get_xmit_slave(struct net_device *dev, struct sk_buff *skb, bool all_slaves);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dbb720)
Location: net/core/dev.c:8126
Inline: False
```
**Symbols:**

```
ffffffff81dbb720-ffffffff81dbb75d: netdev_get_xmit_slave (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct net_device *netdev_get_xmit_slave(struct net_device *dev, struct sk_buff *skb, bool all_slaves);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e2beb0)
Location: net/core/dev.c:8131
Inline: False
```
**Symbols:**

```
ffffffff81e2beb0-ffffffff81e2beed: netdev_get_xmit_slave (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct net_device *netdev_get_xmit_slave(struct net_device *dev, struct sk_buff *skb, bool all_slaves);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81ee9f10)
Location: net/core/dev.c:8249
Inline: False
```
**Symbols:**

```
ffffffff81ee9f10-ffffffff81ee9f4a: netdev_get_xmit_slave (STB_GLOBAL)
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
