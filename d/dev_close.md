# Function: <code>dev_close</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int dev_close(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffff81716e90)
Location: net/core/dev.c:1468
Inline: True
Direct callers:
  - net/ipv4/ipmr.c:vif_add
```
**Symbols:**

```
ffffffff81716e90-ffffffff81716eff: dev_close.part.78 (STB_LOCAL)
ffffffff81716f00-ffffffff81716f1e: dev_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int dev_close(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffff8177ee60)
Location: net/core/dev.c:1472
Inline: True
Direct callers:
  - net/ipv4/ipmr.c:vif_add
```
**Symbols:**

```
ffffffff8177ee60-ffffffff8177eecf: dev_close.part.82 (STB_LOCAL)
ffffffff8177eed0-ffffffff8177eeee: dev_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
int dev_close(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffff817ac570)
Location: net/core/dev.c:1471
Inline: True
Direct callers:
  - net/ipv4/ipmr.c:vif_add
```
**Symbols:**

```
ffffffff817ac570-ffffffff817ac5df: dev_close.part.84 (STB_LOCAL)
ffffffff817ac5e0-ffffffff817ac5fe: dev_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int dev_close(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffff817cad10)
Location: net/core/dev.c:1505
Inline: True
Direct callers:
  - net/ipv4/ipmr.c:vif_add
```
**Symbols:**

```
ffffffff817cad10-ffffffff817cad7f: dev_close.part.86 (STB_LOCAL)
ffffffff817cad80-ffffffff817cad9e: dev_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dev_close(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffff81844550)
Location: net/core/dev.c:1520
Inline: True
Direct callers:
  - net/ipv4/ipmr.c:ipmr_del_tunnel
```
**Symbols:**

```
ffffffff81844550-ffffffff818445bf: dev_close.part.90 (STB_LOCAL)
ffffffff818445c0-ffffffff818445db: dev_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dev_close(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffff8188fd59)
Location: net/core/dev.c:1521
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_net_namespace
Direct callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/ipv4/ipmr.c:ipmr_del_tunnel
```
**Symbols:**

```
ffffffff8188e2d0-ffffffff8188e33f: dev_close.part.103 (STB_LOCAL)
ffffffff8188e340-ffffffff8188e35a: dev_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dev_close(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffff818b06be)
Location: net/core/dev.c:1524
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_net_namespace
Direct callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/ipv4/ipmr.c:ipmr_del_tunnel
```
**Symbols:**

```
ffffffff818af1e0-ffffffff818af24f: dev_close.part.108 (STB_LOCAL)
ffffffff818af250-ffffffff818af26a: dev_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dev_close(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffff818fd415)
Location: net/core/dev.c:1534
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_net_namespace
Direct callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/ipv4/ipmr.c:ipmr_del_tunnel
```
**Symbols:**

```
ffffffff818fb020-ffffffff818fb08f: dev_close.part.0 (STB_LOCAL)
ffffffff818fb090-ffffffff818fb0aa: dev_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dev_close(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffff8192fa2f)
Location: net/core/dev.c:1452
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_net_namespace
Direct callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/ipv4/ipmr.c:ipmr_del_tunnel
```
**Symbols:**

```
ffffffff8192d170-ffffffff8192d1df: dev_close.part.0 (STB_LOCAL)
ffffffff8192d1e0-ffffffff8192d1fa: dev_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void dev_close(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a04bac)
Location: net/core/dev.c:1644
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
Direct callers:
  - net/ipv4/ipmr.c:ipmr_new_tunnel
```
**Symbols:**

```
ffffffff81a01100-ffffffff81a01174: dev_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void dev_close(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a051cc)
Location: net/core/dev.c:1669
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
Direct callers:
  - net/ipv4/ipmr.c:ipmr_new_tunnel
```
**Symbols:**

```
ffffffff81a015c0-ffffffff81a01634: dev_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void dev_close(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819ed487)
Location: net/core/dev.c:1738
Inline: True
Inline callers:
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
Direct callers:
  - net/ipv4/ipmr.c:ipmr_new_tunnel
```
**Symbols:**

```
ffffffff819e7de0-ffffffff819e7e51: dev_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void dev_close(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a9e6a7)
Location: net/core/dev.c:1613
Inline: True
Inline callers:
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
Direct callers:
  - net/ipv4/ipmr.c:ipmr_new_tunnel
```
**Symbols:**

```
ffffffff81a98a90-ffffffff81a98b01: dev_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void dev_close(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c17380)
Location: net/core/dev.c:1561
Inline: True
Inline callers:
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
Direct callers:
  - net/ipv4/ipmr.c:ipmr_new_tunnel
```
**Symbols:**

```
ffffffff81c0ef40-ffffffff81c0efbd: dev_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void dev_close(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dc8380)
Location: net/core/dev.c:1546
Inline: True
Inline callers:
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
Direct callers:
  - net/ipv4/ipmr.c:ipmr_new_tunnel
```
**Symbols:**

```
ffffffff81dbec70-ffffffff81dbeced: dev_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void dev_close(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e38735)
Location: net/core/dev.c:1571
Inline: True
Inline callers:
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
Direct callers:
  - drivers/net/net_failover.c:net_failover_slave_unregister
  - drivers/net/net_failover.c:net_failover_slave_register
  - drivers/net/net_failover.c:net_failover_close
  - drivers/net/net_failover.c:net_failover_close
  - drivers/net/net_failover.c:net_failover_open
  - net/ipv4/ipmr.c:ipmr_new_tunnel
```
**Symbols:**

```
ffffffff81e38370-ffffffff81e383ed: dev_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void dev_close(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81ef6840)
Location: net/core/dev.c:1575
Inline: True
Inline callers:
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
Direct callers:
  - drivers/net/net_failover.c:net_failover_slave_unregister
  - drivers/net/net_failover.c:net_failover_slave_register
  - drivers/net/net_failover.c:net_failover_close
  - drivers/net/net_failover.c:net_failover_close
  - drivers/net/net_failover.c:net_failover_open
  - net/ipv4/ipmr.c:ipmr_new_tunnel
```
**Symbols:**

```
ffffffff81ef6400-ffffffff81ef6486: dev_close (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dev_close(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffff800010bccf18)
Location: net/core/dev.c:1452
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_net_namespace
Direct callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/ipv4/ipmr.c:ipmr_del_tunnel
```
**Symbols:**

```
ffff800010bcaff8-ffff800010bcb068: dev_close.part.0 (STB_LOCAL)
ffff800010bcb068-ffff800010bcb0a8: dev_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dev_close(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (c0ce8954)
Location: net/core/dev.c:1452
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_net_namespace
Direct callers:
  - drivers/net/ethernet/ti/cpsw_ethtool.c:cpsw_fail
  - net/core/dev.c:dev_change_net_namespace
  - net/ipv4/ipmr.c:ipmr_del_tunnel
```
**Symbols:**

```
c0ce5ea0-c0ce5f24: dev_close.part.0 (STB_LOCAL)
c0ce5f24-c0ce5f4c: dev_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dev_close(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (c000000000caacd0)
Location: net/core/dev.c:1452
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_net_namespace
Direct callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/ipv4/ipmr.c:ipmr_del_tunnel
```
**Symbols:**

```
c000000000ca6bb0-c000000000ca6c3c: dev_close.part.0 (STB_LOCAL)
c000000000ca6c40-c000000000ca6c60: dev_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dev_close(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffe000757624)
Location: net/core/dev.c:1452
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_net_namespace
Direct callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/ipv4/ipmr.c:ipmr_del_tunnel
```
**Symbols:**

```
ffffffe000755e94-ffffffe000755ee0: dev_close.part.0 (STB_LOCAL)
ffffffe000755ee0-ffffffe000755f1c: dev_close (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dev_close(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffff818cfa2f)
Location: net/core/dev.c:1452
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_net_namespace
Direct callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/ipv4/ipmr.c:ipmr_del_tunnel
```
**Symbols:**

```
ffffffff818cd170-ffffffff818cd1df: dev_close.part.0 (STB_LOCAL)
ffffffff818cd1e0-ffffffff818cd1fa: dev_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dev_close(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffff81889b4f)
Location: net/core/dev.c:1452
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_net_namespace
Direct callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/ipv4/ipmr.c:ipmr_del_tunnel
```
**Symbols:**

```
ffffffff81887200-ffffffff8188726f: dev_close.part.0 (STB_LOCAL)
ffffffff81887270-ffffffff8188728a: dev_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dev_close(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffff81920a2f)
Location: net/core/dev.c:1452
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_net_namespace
Direct callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/ipv4/ipmr.c:ipmr_del_tunnel
```
**Symbols:**

```
ffffffff8191e170-ffffffff8191e1df: dev_close.part.0 (STB_LOCAL)
ffffffff8191e1e0-ffffffff8191e1fa: dev_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dev_close(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffff819427bf)
Location: net/core/dev.c:1452
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_net_namespace
Direct callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/ipv4/ipmr.c:ipmr_del_tunnel
```
**Symbols:**

```
ffffffff8193f800-ffffffff8193f86f: dev_close.part.0 (STB_LOCAL)
ffffffff8193f870-ffffffff8193f88a: dev_close (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
