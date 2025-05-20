# Function: <code>ip_check_mc_rcu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ip_check_mc_rcu(struct in_device *in_dev, __be32 mc_addr, __be32 src_addr, u8 proto);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81799940)
Location: net/ipv4/igmp.c:2569
Inline: False
Direct callers:
  - net/ipv4/route.c:__ip_route_output_key_hash
  - net/ipv4/udp.c:udp_v4_early_demux
```
**Symbols:**

```
ffffffff81799940-ffffffff817999ec: ip_check_mc_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ip_check_mc_rcu(struct in_device *in_dev, __be32 mc_addr, __be32 src_addr, u8 proto);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff818074d0)
Location: net/ipv4/igmp.c:2580
Inline: False
Direct callers:
  - net/ipv4/route.c:__ip_route_output_key_hash
  - net/ipv4/udp.c:udp_v4_early_demux
```
**Symbols:**

```
ffffffff818074d0-ffffffff8180757f: ip_check_mc_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ip_check_mc_rcu(struct in_device *in_dev, __be32 mc_addr, __be32 src_addr, u8 proto);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81838560)
Location: net/ipv4/igmp.c:2618
Inline: False
Direct callers:
  - net/ipv4/route.c:__ip_route_output_key_hash
  - net/ipv4/route.c:ip_route_input_noref
  - net/ipv4/route.c:ip_route_input_noref
  - net/ipv4/udp.c:udp_v4_early_demux
```
**Symbols:**

```
ffffffff81838560-ffffffff81838609: ip_check_mc_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ip_check_mc_rcu(struct in_device *in_dev, __be32 mc_addr, __be32 src_addr, u8 proto);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff818599b0)
Location: net/ipv4/igmp.c:2632
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/udp.c:udp_v4_early_demux
```
**Symbols:**

```
ffffffff818599b0-ffffffff81859a5b: ip_check_mc_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ip_check_mc_rcu(struct in_device *in_dev, __be32 mc_addr, __be32 src_addr, u8 proto);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff818d98b0)
Location: net/ipv4/igmp.c:2660
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/udp.c:udp_v4_early_demux
```
**Symbols:**

```
ffffffff818d98b0-ffffffff818d995b: ip_check_mc_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ip_check_mc_rcu(struct in_device *in_dev, __be32 mc_addr, __be32 src_addr, u8 proto);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff819302f0)
Location: net/ipv4/igmp.c:2686
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/udp.c:udp_v4_early_demux
```
**Symbols:**

```
ffffffff819302f0-ffffffff8193039b: ip_check_mc_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ip_check_mc_rcu(struct in_device *in_dev, __be32 mc_addr, __be32 src_addr, u8 proto);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff8195f7d0)
Location: net/ipv4/igmp.c:2702
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/udp.c:udp_v4_early_demux
```
**Symbols:**

```
ffffffff8195f7d0-ffffffff8195f87b: ip_check_mc_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ip_check_mc_rcu(struct in_device *in_dev, __be32 mc_addr, __be32 src_addr, u8 proto);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff819c4660)
Location: net/ipv4/igmp.c:2698
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/udp.c:udp_v4_early_demux
```
**Symbols:**

```
ffffffff819c4660-ffffffff819c4712: ip_check_mc_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ip_check_mc_rcu(struct in_device *in_dev, __be32 mc_addr, __be32 src_addr, u8 proto);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff819fb200)
Location: net/ipv4/igmp.c:2698
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/udp.c:udp_v4_early_demux
```
**Symbols:**

```
ffffffff819fb200-ffffffff819fb2b2: ip_check_mc_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ip_check_mc_rcu(struct in_device *in_dev, __be32 mc_addr, __be32 src_addr, u8 proto);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81ae9b30)
Location: net/ipv4/igmp.c:2688
Inline: False
Direct callers:
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/udp.c:udp_v4_early_demux
```
**Symbols:**

```
ffffffff81ae9b30-ffffffff81ae9be7: ip_check_mc_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ip_check_mc_rcu(struct in_device *in_dev, __be32 mc_addr, __be32 src_addr, u8 proto);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81af69d0)
Location: net/ipv4/igmp.c:2688
Inline: False
Direct callers:
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/udp.c:udp_v4_early_demux
```
**Symbols:**

```
ffffffff81af69d0-ffffffff81af6a87: ip_check_mc_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ip_check_mc_rcu(struct in_device *in_dev, __be32 mc_addr, __be32 src_addr, u8 proto);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81ae2120)
Location: net/ipv4/igmp.c:2696
Inline: False
Direct callers:
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/udp.c:udp_v4_early_demux
```
**Symbols:**

```
ffffffff81ae2120-ffffffff81ae21d2: ip_check_mc_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ip_check_mc_rcu(struct in_device *in_dev, __be32 mc_addr, __be32 src_addr, u8 proto);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81ba18c0)
Location: net/ipv4/igmp.c:2702
Inline: False
Direct callers:
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/udp.c:udp_v4_early_demux
```
**Symbols:**

```
ffffffff81ba18c0-ffffffff81ba19a4: ip_check_mc_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ip_check_mc_rcu(struct in_device *in_dev, __be32 mc_addr, __be32 src_addr, u8 proto);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81d33ec0)
Location: net/ipv4/igmp.c:2711
Inline: False
Direct callers:
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/udp.c:udp_v4_early_demux
```
**Symbols:**

```
ffffffff81d33ec0-ffffffff81d33fc7: ip_check_mc_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ip_check_mc_rcu(struct in_device *in_dev, __be32 mc_addr, __be32 src_addr, u8 proto);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81efc350)
Location: net/ipv4/igmp.c:2715
Inline: False
Direct callers:
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/udp.c:udp_v4_early_demux
```
**Symbols:**

```
ffffffff81efc350-ffffffff81efc457: ip_check_mc_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ip_check_mc_rcu(struct in_device *in_dev, __be32 mc_addr, __be32 src_addr, u8 proto);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81f5bd70)
Location: net/ipv4/igmp.c:2716
Inline: False
Direct callers:
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/udp.c:udp_v4_early_demux
```
**Symbols:**

```
ffffffff81f5bd70-ffffffff81f5be77: ip_check_mc_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ip_check_mc_rcu(struct in_device *in_dev, __be32 mc_addr, __be32 src_addr, u8 proto);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff820222d0)
Location: net/ipv4/igmp.c:2718
Inline: False
Direct callers:
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/udp.c:udp_v4_early_demux
```
**Symbols:**

```
ffffffff820222d0-ffffffff820223d7: ip_check_mc_rcu (STB_GLOBAL)
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
int ip_check_mc_rcu(struct in_device *in_dev, __be32 mc_addr, __be32 src_addr, u8 proto);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffff800010cb2d88)
Location: net/ipv4/igmp.c:2698
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/udp.c:udp_v4_early_demux
```
**Symbols:**

```
ffff800010cb2d88-ffff800010cb2e98: ip_check_mc_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ip_check_mc_rcu(struct in_device *in_dev, __be32 mc_addr, __be32 src_addr, u8 proto);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (c0dbe824)
Location: net/ipv4/igmp.c:2698
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/udp.c:udp_v4_early_demux
```
**Symbols:**

```
c0dbe824-c0dbe914: ip_check_mc_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ip_check_mc_rcu(struct in_device *in_dev, __be32 mc_addr, __be32 src_addr, u8 proto);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (c000000000dc9f20)
Location: net/ipv4/igmp.c:2698
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/udp.c:udp_v4_early_demux
```
**Symbols:**

```
c000000000dc9f20-c000000000dca040: ip_check_mc_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ip_check_mc_rcu(struct in_device *in_dev, __be32 mc_addr, __be32 src_addr, u8 proto);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffe00080b17a)
Location: net/ipv4/igmp.c:2698
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/udp.c:udp_v4_early_demux
```
**Symbols:**

```
ffffffe00080b17a-ffffffe00080b238: ip_check_mc_rcu (STB_GLOBAL)
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
int ip_check_mc_rcu(struct in_device *in_dev, __be32 mc_addr, __be32 src_addr, u8 proto);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff8199afa0)
Location: net/ipv4/igmp.c:2698
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/udp.c:udp_v4_early_demux
```
**Symbols:**

```
ffffffff8199afa0-ffffffff8199b052: ip_check_mc_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ip_check_mc_rcu(struct in_device *in_dev, __be32 mc_addr, __be32 src_addr, u8 proto);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81954a60)
Location: net/ipv4/igmp.c:2698
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/udp.c:udp_v4_early_demux
```
**Symbols:**

```
ffffffff81954a60-ffffffff81954b12: ip_check_mc_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ip_check_mc_rcu(struct in_device *in_dev, __be32 mc_addr, __be32 src_addr, u8 proto);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81a05840)
Location: net/ipv4/igmp.c:2698
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/udp.c:udp_v4_early_demux
```
**Symbols:**

```
ffffffff81a05840-ffffffff81a058f2: ip_check_mc_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ip_check_mc_rcu(struct in_device *in_dev, __be32 mc_addr, __be32 src_addr, u8 proto);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81a0fe10)
Location: net/ipv4/igmp.c:2698
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/udp.c:udp_v4_early_demux
```
**Symbols:**

```
ffffffff81a0fe10-ffffffff81a0fec2: ip_check_mc_rcu (STB_GLOBAL)
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
