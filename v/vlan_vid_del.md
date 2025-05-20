# Function: <code>vlan_vid_del</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void vlan_vid_del(struct net_device *dev, __be16 proto, u16 vid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/8021q/vlan_core.c (ffffffff81808f30)
Location: net/8021q/vlan_core.c:286
Inline: False
Direct callers:
  - net/8021q/vlan_core.c:vlan_vids_del_by_dev
  - net/8021q/vlan_core.c:vlan_vids_add_by_dev
```
**Symbols:**

```
ffffffff81808f30-ffffffff818090ef: vlan_vid_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void vlan_vid_del(struct net_device *dev, __be16 proto, u16 vid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/8021q/vlan_core.c (ffffffff8187aa80)
Location: net/8021q/vlan_core.c:286
Inline: False
Direct callers:
  - net/8021q/vlan_core.c:vlan_vids_del_by_dev
  - net/8021q/vlan_core.c:vlan_vids_add_by_dev
```
**Symbols:**

```
ffffffff8187aa80-ffffffff8187ac33: vlan_vid_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void vlan_vid_del(struct net_device *dev, __be16 proto, u16 vid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/8021q/vlan_core.c (ffffffff818af340)
Location: net/8021q/vlan_core.c:286
Inline: False
Direct callers:
  - net/8021q/vlan_core.c:vlan_vids_del_by_dev
  - net/8021q/vlan_core.c:vlan_vids_add_by_dev
```
**Symbols:**

```
ffffffff818af340-ffffffff818af4f3: vlan_vid_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void vlan_vid_del(struct net_device *dev, __be16 proto, u16 vid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/8021q/vlan_core.c (ffffffff818d5b10)
Location: net/8021q/vlan_core.c:286
Inline: False
Direct callers:
  - net/8021q/vlan_core.c:vlan_vids_del_by_dev
  - net/8021q/vlan_core.c:vlan_vids_add_by_dev
```
**Symbols:**

```
ffffffff818d5b10-ffffffff818d5c96: vlan_vid_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void vlan_vid_del(struct net_device *dev, __be16 proto, u16 vid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/8021q/vlan_core.c (ffffffff8195b6c0)
Location: net/8021q/vlan_core.c:293
Inline: False
Direct callers:
  - net/8021q/vlan_core.c:vlan_vids_del_by_dev
  - net/8021q/vlan_core.c:vlan_vids_add_by_dev
```
**Symbols:**

```
ffffffff8195b6c0-ffffffff8195b84c: vlan_vid_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void vlan_vid_del(struct net_device *dev, __be16 proto, u16 vid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/8021q/vlan_core.c (0)
Location: net/8021q/vlan_core.c:344
Inline: False
Direct callers:
  - net/8021q/vlan_core.c:vlan_vids_del_by_dev
  - net/8021q/vlan_core.c:vlan_vids_add_by_dev
```
**Symbols:**

```
ffffffff819b5808-ffffffff819b582a: vlan_vid_del.cold.19 (STB_LOCAL)
ffffffff819b4e60-ffffffff819b4fa2: vlan_vid_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void vlan_vid_del(struct net_device *dev, __be16 proto, u16 vid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/8021q/vlan_core.c (0)
Location: net/8021q/vlan_core.c:371
Inline: False
Direct callers:
  - net/8021q/vlan_core.c:vlan_vids_del_by_dev
  - net/8021q/vlan_core.c:vlan_vids_add_by_dev
```
**Symbols:**

```
ffffffff819ecaca-ffffffff819ecaec: vlan_vid_del.cold.20 (STB_LOCAL)
ffffffff819ebeb0-ffffffff819ebff2: vlan_vid_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void vlan_vid_del(struct net_device *dev, __be16 proto, u16 vid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/8021q/vlan_core.c (0)
Location: net/8021q/vlan_core.c:371
Inline: False
Direct callers:
  - net/8021q/vlan_core.c:vlan_vids_del_by_dev
  - net/8021q/vlan_core.c:vlan_vids_add_by_dev
```
**Symbols:**

```
ffffffff81a5bc98-ffffffff81a5bcb7: vlan_vid_del.cold (STB_LOCAL)
ffffffff81a5b040-ffffffff81a5b194: vlan_vid_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void vlan_vid_del(struct net_device *dev, __be16 proto, u16 vid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/8021q/vlan_core.c (0)
Location: net/8021q/vlan_core.c:371
Inline: False
Direct callers:
  - net/8021q/vlan_core.c:vlan_vids_del_by_dev
  - net/8021q/vlan_core.c:vlan_vids_add_by_dev
```
**Symbols:**

```
ffffffff81a928c3-ffffffff81a928e2: vlan_vid_del.cold (STB_LOCAL)
ffffffff81a91c70-ffffffff81a91dc4: vlan_vid_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void vlan_vid_del(struct net_device *dev, __be16 proto, u16 vid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/8021q/vlan_core.c (0)
Location: net/8021q/vlan_core.c:370
Inline: False
Direct callers:
  - net/8021q/vlan_core.c:vlan_vids_del_by_dev
  - net/8021q/vlan_core.c:vlan_vids_add_by_dev
```
**Symbols:**

```
ffffffff81b8dd74-ffffffff81b8dd93: vlan_vid_del.cold (STB_LOCAL)
ffffffff81b8d250-ffffffff81b8d3aa: vlan_vid_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void vlan_vid_del(struct net_device *dev, __be16 proto, u16 vid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/8021q/vlan_core.c (0)
Location: net/8021q/vlan_core.c:370
Inline: False
Direct callers:
  - net/8021q/vlan_core.c:vlan_vids_del_by_dev
  - net/8021q/vlan_core.c:vlan_vids_add_by_dev
```
**Symbols:**

```
ffffffff81c332c5-ffffffff81c332e4: vlan_vid_del.cold (STB_LOCAL)
ffffffff81b9cec0-ffffffff81b9d01a: vlan_vid_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void vlan_vid_del(struct net_device *dev, __be16 proto, u16 vid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/8021q/vlan_core.c (0)
Location: net/8021q/vlan_core.c:371
Inline: False
Direct callers:
  - net/8021q/vlan_core.c:vlan_vids_del_by_dev
  - net/8021q/vlan_core.c:vlan_vids_add_by_dev
```
**Symbols:**

```
ffffffff81c255e4-ffffffff81c25603: vlan_vid_del.cold (STB_LOCAL)
ffffffff81b8bfd0-ffffffff81b8c12a: vlan_vid_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void vlan_vid_del(struct net_device *dev, __be16 proto, u16 vid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/8021q/vlan_core.c (0)
Location: net/8021q/vlan_core.c:371
Inline: False
Direct callers:
  - net/8021q/vlan_core.c:vlan_vids_del_by_dev
  - net/8021q/vlan_core.c:vlan_vids_add_by_dev
```
**Symbols:**

```
ffffffff81d41ad1-ffffffff81d41b05: vlan_vid_del.cold (STB_LOCAL)
ffffffff81c58600-ffffffff81c58769: vlan_vid_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void vlan_vid_del(struct net_device *dev, __be16 proto, u16 vid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/8021q/vlan_core.c (0)
Location: net/8021q/vlan_core.c:371
Inline: False
Direct callers:
  - net/8021q/vlan_core.c:vlan_vids_del_by_dev
  - net/8021q/vlan_core.c:vlan_vids_add_by_dev
```
**Symbols:**

```
ffffffff81f0e3e7-ffffffff81f0e415: vlan_vid_del.cold (STB_LOCAL)
ffffffff81df99d0-ffffffff81df9b25: vlan_vid_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void vlan_vid_del(struct net_device *dev, __be16 proto, u16 vid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/8021q/vlan_core.c (0)
Location: net/8021q/vlan_core.c:371
Inline: False
Direct callers:
  - net/8021q/vlan_core.c:vlan_vids_del_by_dev
  - net/8021q/vlan_core.c:vlan_vids_add_by_dev
```
**Symbols:**

```
ffffffff820b5492-ffffffff820b54a6: vlan_vid_del.cold (STB_LOCAL)
ffffffff81fce3d0-ffffffff81fce536: vlan_vid_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void vlan_vid_del(struct net_device *dev, __be16 proto, u16 vid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/8021q/vlan_core.c (0)
Location: net/8021q/vlan_core.c:371
Inline: False
Direct callers:
  - drivers/net/net_failover.c:net_failover_vlan_rx_kill_vid
  - drivers/net/net_failover.c:net_failover_vlan_rx_kill_vid
  - drivers/net/net_failover.c:net_failover_vlan_rx_add_vid
  - net/8021q/vlan_core.c:vlan_vids_del_by_dev
  - net/8021q/vlan_core.c:vlan_vids_add_by_dev
```
**Symbols:**

```
ffffffff821369cc-ffffffff821369e0: vlan_vid_del.cold (STB_LOCAL)
ffffffff82049d20-ffffffff82049e86: vlan_vid_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void vlan_vid_del(struct net_device *dev, __be16 proto, u16 vid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/8021q/vlan_core.c (0)
Location: net/8021q/vlan_core.c:371
Inline: False
Direct callers:
  - drivers/net/net_failover.c:net_failover_vlan_rx_kill_vid
  - drivers/net/net_failover.c:net_failover_vlan_rx_kill_vid
  - drivers/net/net_failover.c:net_failover_vlan_rx_add_vid
  - net/8021q/vlan_core.c:vlan_vids_del_by_dev
  - net/8021q/vlan_core.c:vlan_vids_add_by_dev
  - net/8021q/vlan_core.c:vlan_vids_add_by_dev
```
**Symbols:**

```
ffffffff822187cf-ffffffff822187e3: vlan_vid_del.cold (STB_LOCAL)
ffffffff8211c350-ffffffff8211c4b6: vlan_vid_del (STB_GLOBAL)
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
void vlan_vid_del(struct net_device *dev, __be16 proto, u16 vid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/8021q/vlan_core.c (ffff800010d5f8f8)
Location: net/8021q/vlan_core.c:371
Inline: False
Direct callers:
  - net/8021q/vlan_core.c:vlan_vids_del_by_dev
  - net/8021q/vlan_core.c:vlan_vids_add_by_dev
```
**Symbols:**

```
ffff800010d5f8f8-ffff800010d5fa4c: vlan_vid_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void vlan_vid_del(struct net_device *dev, __be16 proto, u16 vid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/8021q/vlan_core.c (c0e5f460)
Location: net/8021q/vlan_core.c:371
Inline: False
Direct callers:
  - net/8021q/vlan_core.c:vlan_vids_del_by_dev
  - net/8021q/vlan_core.c:vlan_vids_add_by_dev
```
**Symbols:**

```
c0e5f460-c0e5f5c4: vlan_vid_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void vlan_vid_del(struct net_device *dev, __be16 proto, u16 vid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/8021q/vlan_core.c (c000000000e9a560)
Location: net/8021q/vlan_core.c:371
Inline: False
Direct callers:
  - net/8021q/vlan_core.c:vlan_vids_del_by_dev
  - net/8021q/vlan_core.c:vlan_vids_add_by_dev
```
**Symbols:**

```
c000000000e9a560-c000000000e9a754: vlan_vid_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void vlan_vid_del(struct net_device *dev, __be16 proto, u16 vid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/8021q/vlan_core.c (ffffffe000894f06)
Location: net/8021q/vlan_core.c:371
Inline: False
Direct callers:
  - net/8021q/vlan_core.c:vlan_vids_del_by_dev
  - net/8021q/vlan_core.c:vlan_vids_add_by_dev
```
**Symbols:**

```
ffffffe000894f06-ffffffe000895026: vlan_vid_del (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void vlan_vid_del(struct net_device *dev, __be16 proto, u16 vid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/8021q/vlan_core.c (0)
Location: net/8021q/vlan_core.c:371
Inline: False
Direct callers:
  - net/8021q/vlan_core.c:vlan_vids_del_by_dev
  - net/8021q/vlan_core.c:vlan_vids_add_by_dev
```
**Symbols:**

```
ffffffff81a31f53-ffffffff81a31f72: vlan_vid_del.cold (STB_LOCAL)
ffffffff81a31300-ffffffff81a31454: vlan_vid_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void vlan_vid_del(struct net_device *dev, __be16 proto, u16 vid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/8021q/vlan_core.c (0)
Location: net/8021q/vlan_core.c:371
Inline: False
Direct callers:
  - net/8021q/vlan_core.c:vlan_vids_del_by_dev
  - net/8021q/vlan_core.c:vlan_vids_add_by_dev
```
**Symbols:**

```
ffffffff819ef143-ffffffff819ef162: vlan_vid_del.cold (STB_LOCAL)
ffffffff819ee4f0-ffffffff819ee644: vlan_vid_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void vlan_vid_del(struct net_device *dev, __be16 proto, u16 vid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/8021q/vlan_core.c (0)
Location: net/8021q/vlan_core.c:371
Inline: False
Direct callers:
  - net/8021q/vlan_core.c:vlan_vids_del_by_dev
  - net/8021q/vlan_core.c:vlan_vids_add_by_dev
```
**Symbols:**

```
ffffffff81a9db03-ffffffff81a9db22: vlan_vid_del.cold (STB_LOCAL)
ffffffff81a9ceb0-ffffffff81a9d004: vlan_vid_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void vlan_vid_del(struct net_device *dev, __be16 proto, u16 vid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/8021q/vlan_core.c (0)
Location: net/8021q/vlan_core.c:371
Inline: False
Direct callers:
  - net/8021q/vlan_core.c:vlan_vids_del_by_dev
  - net/8021q/vlan_core.c:vlan_vids_add_by_dev
```
**Symbols:**

```
ffffffff81aa9d03-ffffffff81aa9d22: vlan_vid_del.cold (STB_LOCAL)
ffffffff81aa90a0-ffffffff81aa91f4: vlan_vid_del (STB_GLOBAL)
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
