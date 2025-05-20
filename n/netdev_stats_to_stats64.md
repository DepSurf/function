# Function: <code>netdev_stats_to_stats64</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void netdev_stats_to_stats64(struct rtnl_link_stats64 *stats64, const struct net_device_stats *netdev_stats);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81713dc0)
Location: net/core/dev.c:6966
Inline: True
Inline callers:
  - net/core/dev.c:dev_get_stats
  - net/core/dev.c:dev_get_stats
Direct callers:
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_get_stats64
```
**Symbols:**

```
ffffffff81713dc0-ffffffff81713dfd: netdev_stats_to_stats64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void netdev_stats_to_stats64(struct rtnl_link_stats64 *stats64, const struct net_device_stats *netdev_stats);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8177bba0)
Location: net/core/dev.c:7477
Inline: False
Direct callers:
  - net/core/dev.c:dev_get_stats
  - net/core/dev.c:dev_get_stats
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_get_stats64
```
**Symbols:**

```
ffffffff8177bba0-ffffffff8177bbeb: netdev_stats_to_stats64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void netdev_stats_to_stats64(struct rtnl_link_stats64 *stats64, const struct net_device_stats *netdev_stats);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817a9340)
Location: net/core/dev.c:7647
Inline: False
Direct callers:
  - net/core/dev.c:dev_get_stats
  - net/core/dev.c:dev_get_stats
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_get_stats64
```
**Symbols:**

```
ffffffff817a9340-ffffffff817a938b: netdev_stats_to_stats64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void netdev_stats_to_stats64(struct rtnl_link_stats64 *stats64, const struct net_device_stats *netdev_stats);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817c78e0)
Location: net/core/dev.c:7836
Inline: False
Direct callers:
  - net/core/dev.c:dev_get_stats
  - net/core/dev.c:dev_get_stats
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_get_stats64
```
**Symbols:**

```
ffffffff817c78e0-ffffffff817c792b: netdev_stats_to_stats64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void netdev_stats_to_stats64(struct rtnl_link_stats64 *stats64, const struct net_device_stats *netdev_stats);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818414c0)
Location: net/core/dev.c:8015
Inline: False
Direct callers:
  - net/core/dev.c:dev_get_stats
  - net/core/dev.c:dev_get_stats
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_get_stats64
```
**Symbols:**

```
ffffffff818414c0-ffffffff8184150b: netdev_stats_to_stats64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void netdev_stats_to_stats64(struct rtnl_link_stats64 *stats64, const struct net_device_stats *netdev_stats);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8188bbd0)
Location: net/core/dev.c:8278
Inline: False
Direct callers:
  - net/core/dev.c:dev_get_stats
  - net/core/dev.c:dev_get_stats
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_get_stats64
```
**Symbols:**

```
ffffffff8188bbd0-ffffffff8188bc1b: netdev_stats_to_stats64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void netdev_stats_to_stats64(struct rtnl_link_stats64 *stats64, const struct net_device_stats *netdev_stats);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818acdb0)
Location: net/core/dev.c:8908
Inline: False
Direct callers:
  - net/core/dev.c:dev_get_stats
  - net/core/dev.c:dev_get_stats
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_get_stats64
```
**Symbols:**

```
ffffffff818acdb0-ffffffff818acdfb: netdev_stats_to_stats64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void netdev_stats_to_stats64(struct rtnl_link_stats64 *stats64, const struct net_device_stats *netdev_stats);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818f8530)
Location: net/core/dev.c:9013
Inline: False
Direct callers:
  - net/core/dev.c:dev_get_stats
  - net/core/dev.c:dev_get_stats
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_get_stats64
```
**Symbols:**

```
ffffffff818f8530-ffffffff818f857b: netdev_stats_to_stats64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void netdev_stats_to_stats64(struct rtnl_link_stats64 *stats64, const struct net_device_stats *netdev_stats);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8192a6d0)
Location: net/core/dev.c:9351
Inline: False
Direct callers:
  - net/core/dev.c:dev_get_stats
  - net/core/dev.c:dev_get_stats
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_get_stats64
```
**Symbols:**

```
ffffffff8192a6d0-ffffffff8192a71b: netdev_stats_to_stats64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void netdev_stats_to_stats64(struct rtnl_link_stats64 *stats64, const struct net_device_stats *netdev_stats);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819fe400)
Location: net/core/dev.c:9807
Inline: False
Direct callers:
  - net/core/dev.c:dev_get_stats
  - net/core/dev.c:dev_get_stats
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_get_stats64
```
**Symbols:**

```
ffffffff819fe400-ffffffff819fe44b: netdev_stats_to_stats64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void netdev_stats_to_stats64(struct rtnl_link_stats64 *stats64, const struct net_device_stats *netdev_stats);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819fdff0)
Location: net/core/dev.c:10452
Inline: False
Direct callers:
  - net/core/dev.c:dev_get_tstats64
  - net/core/dev.c:dev_get_stats
  - net/core/dev.c:dev_get_stats
```
**Symbols:**

```
ffffffff819fdff0-ffffffff819fe03b: netdev_stats_to_stats64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void netdev_stats_to_stats64(struct rtnl_link_stats64 *stats64, const struct net_device_stats *netdev_stats);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819e48b0)
Location: net/core/dev.c:10624
Inline: False
Direct callers:
  - net/core/dev.c:dev_get_tstats64
  - net/core/dev.c:dev_get_stats
  - net/core/dev.c:dev_get_stats
```
**Symbols:**

```
ffffffff819e48b0-ffffffff819e48fb: netdev_stats_to_stats64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void netdev_stats_to_stats64(struct rtnl_link_stats64 *stats64, const struct net_device_stats *netdev_stats);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a95670)
Location: net/core/dev.c:10631
Inline: False
Direct callers:
  - net/core/dev.c:dev_get_tstats64
  - net/core/dev.c:dev_get_stats
  - net/core/dev.c:dev_get_stats
```
**Symbols:**

```
ffffffff81a95670-ffffffff81a956bb: netdev_stats_to_stats64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void netdev_stats_to_stats64(struct rtnl_link_stats64 *stats64, const struct net_device_stats *netdev_stats);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c0bfe0)
Location: net/core/dev.c:10376
Inline: False
Direct callers:
  - net/core/dev.c:dev_get_tstats64
  - net/core/dev.c:dev_get_stats
  - net/core/dev.c:dev_get_stats
```
**Symbols:**

```
ffffffff81c0bfe0-ffffffff81c0c044: netdev_stats_to_stats64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void netdev_stats_to_stats64(struct rtnl_link_stats64 *stats64, const struct net_device_stats *netdev_stats);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dbbe70)
Location: net/core/dev.c:10363
Inline: False
Direct callers:
  - net/core/dev.c:dev_get_tstats64
  - net/core/dev.c:dev_get_stats
  - net/core/dev.c:dev_get_stats
```
**Symbols:**

```
ffffffff81dbbe70-ffffffff81dbbeb6: netdev_stats_to_stats64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void netdev_stats_to_stats64(struct rtnl_link_stats64 *stats64, const struct net_device_stats *netdev_stats);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e2c620)
Location: net/core/dev.c:10375
Inline: False
Direct callers:
  - net/core/dev.c:dev_get_tstats64
  - net/core/dev.c:dev_get_stats
  - net/core/dev.c:dev_get_stats
```
**Symbols:**

```
ffffffff81e2c620-ffffffff81e2c666: netdev_stats_to_stats64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void netdev_stats_to_stats64(struct rtnl_link_stats64 *stats64, const struct net_device_stats *netdev_stats);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81eea610)
Location: net/core/dev.c:10568
Inline: False
Direct callers:
  - net/core/dev.c:dev_get_tstats64
  - net/core/dev.c:dev_get_stats
  - net/core/dev.c:dev_get_stats
```
**Symbols:**

```
ffffffff81eea610-ffffffff81eea656: netdev_stats_to_stats64 (STB_GLOBAL)
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
void netdev_stats_to_stats64(struct rtnl_link_stats64 *stats64, const struct net_device_stats *netdev_stats);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bc70a0)
Location: net/core/dev.c:9351
Inline: False
Direct callers:
  - net/core/dev.c:dev_get_stats
  - net/core/dev.c:dev_get_stats
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_get_stats64
```
**Symbols:**

```
ffff800010bc70a0-ffff800010bc70dc: netdev_stats_to_stats64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void netdev_stats_to_stats64(struct rtnl_link_stats64 *stats64, const struct net_device_stats *netdev_stats);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0ce242c)
Location: net/core/dev.c:9351
Inline: False
Direct callers:
  - net/core/dev.c:dev_get_stats
  - net/core/dev.c:dev_get_stats
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_get_stats64
```
**Symbols:**

```
c0ce242c-c0ce2470: netdev_stats_to_stats64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void netdev_stats_to_stats64(struct rtnl_link_stats64 *stats64, const struct net_device_stats *netdev_stats);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000ca1e30)
Location: net/core/dev.c:9351
Inline: False
Direct callers:
  - net/core/dev.c:dev_get_stats
  - net/core/dev.c:dev_get_stats
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_get_stats64
```
**Symbols:**

```
c000000000ca1e30-c000000000ca1e7c: netdev_stats_to_stats64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void netdev_stats_to_stats64(struct rtnl_link_stats64 *stats64, const struct net_device_stats *netdev_stats);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe0007535be)
Location: net/core/dev.c:9351
Inline: False
Direct callers:
  - net/core/dev.c:dev_get_stats
  - net/core/dev.c:dev_get_stats
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_get_stats64
```
**Symbols:**

```
ffffffe0007535be-ffffffe000753614: netdev_stats_to_stats64 (STB_GLOBAL)
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
void netdev_stats_to_stats64(struct rtnl_link_stats64 *stats64, const struct net_device_stats *netdev_stats);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818ca6d0)
Location: net/core/dev.c:9351
Inline: False
Direct callers:
  - net/core/dev.c:dev_get_stats
  - net/core/dev.c:dev_get_stats
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_get_stats64
```
**Symbols:**

```
ffffffff818ca6d0-ffffffff818ca71b: netdev_stats_to_stats64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void netdev_stats_to_stats64(struct rtnl_link_stats64 *stats64, const struct net_device_stats *netdev_stats);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81884610)
Location: net/core/dev.c:9351
Inline: False
Direct callers:
  - net/core/dev.c:dev_get_stats
  - net/core/dev.c:dev_get_stats
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_get_stats64
```
**Symbols:**

```
ffffffff81884610-ffffffff8188465b: netdev_stats_to_stats64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void netdev_stats_to_stats64(struct rtnl_link_stats64 *stats64, const struct net_device_stats *netdev_stats);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8191b6d0)
Location: net/core/dev.c:9351
Inline: False
Direct callers:
  - net/core/dev.c:dev_get_stats
  - net/core/dev.c:dev_get_stats
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_get_stats64
```
**Symbols:**

```
ffffffff8191b6d0-ffffffff8191b71b: netdev_stats_to_stats64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void netdev_stats_to_stats64(struct rtnl_link_stats64 *stats64, const struct net_device_stats *netdev_stats);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8193c8d0)
Location: net/core/dev.c:9351
Inline: False
Direct callers:
  - net/core/dev.c:dev_get_stats
  - net/core/dev.c:dev_get_stats
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_get_stats64
```
**Symbols:**

```
ffffffff8193c8d0-ffffffff8193c91b: netdev_stats_to_stats64 (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
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
