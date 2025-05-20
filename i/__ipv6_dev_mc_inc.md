# Function: <code>__ipv6_dev_mc_inc</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __ipv6_dev_mc_inc(struct net_device *dev, const struct in6_addr *addr, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff8198e170)
Location: net/ipv6/mcast.c:886
Inline: False
Direct callers:
  - net/ipv6/mcast.c:ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
**Symbols:**

```
ffffffff8198e170-ffffffff8198e3e4: __ipv6_dev_mc_inc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __ipv6_dev_mc_inc(struct net_device *dev, const struct in6_addr *addr, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff819c4a30)
Location: net/ipv6/mcast.c:886
Inline: False
Direct callers:
  - net/ipv6/mcast.c:ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
**Symbols:**

```
ffffffff819c4a30-ffffffff819c4c94: __ipv6_dev_mc_inc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __ipv6_dev_mc_inc(struct net_device *dev, const struct in6_addr *addr, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff81a33880)
Location: net/ipv6/mcast.c:883
Inline: False
Direct callers:
  - net/ipv6/mcast.c:ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
**Symbols:**

```
ffffffff81a33880-ffffffff81a33b09: __ipv6_dev_mc_inc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __ipv6_dev_mc_inc(struct net_device *dev, const struct in6_addr *addr, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff81a6a3d0)
Location: net/ipv6/mcast.c:883
Inline: False
Direct callers:
  - net/ipv6/mcast.c:ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
**Symbols:**

```
ffffffff81a6a3d0-ffffffff81a6a659: __ipv6_dev_mc_inc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __ipv6_dev_mc_inc(struct net_device *dev, const struct in6_addr *addr, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff81b632f0)
Location: net/ipv6/mcast.c:880
Inline: False
Direct callers:
  - net/ipv6/mcast.c:ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
**Symbols:**

```
ffffffff81b632f0-ffffffff81b63591: __ipv6_dev_mc_inc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __ipv6_dev_mc_inc(struct net_device *dev, const struct in6_addr *addr, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff81b71a90)
Location: net/ipv6/mcast.c:880
Inline: False
Direct callers:
  - net/ipv6/mcast.c:ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
**Symbols:**

```
ffffffff81b71a90-ffffffff81b71d36: __ipv6_dev_mc_inc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __ipv6_dev_mc_inc(struct net_device *dev, const struct in6_addr *addr, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff81b5fec0)
Location: net/ipv6/mcast.c:901
Inline: False
Direct callers:
  - net/ipv6/mcast.c:ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
**Symbols:**

```
ffffffff81b5fec0-ffffffff81b60233: __ipv6_dev_mc_inc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __ipv6_dev_mc_inc(struct net_device *dev, const struct in6_addr *addr, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/mcast.c (0)
Location: net/ipv6/mcast.c:906
Inline: False
Direct callers:
  - net/ipv6/mcast.c:ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
**Symbols:**

```
ffffffff81c27790-ffffffff81c27b2c: __ipv6_dev_mc_inc (STB_LOCAL)
ffffffff81d40a0f-ffffffff81d40a24: __ipv6_dev_mc_inc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __ipv6_dev_mc_inc(struct net_device *dev, const struct in6_addr *addr, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/mcast.c (0)
Location: net/ipv6/mcast.c:906
Inline: False
Direct callers:
  - net/ipv6/mcast.c:ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
**Symbols:**

```
ffffffff81dc4b00-ffffffff81dc4ec5: __ipv6_dev_mc_inc (STB_LOCAL)
ffffffff81f0d3f9-ffffffff81f0d40e: __ipv6_dev_mc_inc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int __ipv6_dev_mc_inc(struct net_device *dev, const struct in6_addr *addr, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/mcast.c (0)
Location: net/ipv6/mcast.c:906
Inline: False
Direct callers:
  - net/ipv6/mcast.c:ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
**Symbols:**

```
ffffffff81f95650-ffffffff81f95a15: __ipv6_dev_mc_inc (STB_LOCAL)
ffffffff820b4842-ffffffff820b4857: __ipv6_dev_mc_inc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int __ipv6_dev_mc_inc(struct net_device *dev, const struct in6_addr *addr, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/mcast.c (0)
Location: net/ipv6/mcast.c:906
Inline: False
Direct callers:
  - net/ipv6/mcast.c:ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
**Symbols:**

```
ffffffff81ff6000-ffffffff81ff63c5: __ipv6_dev_mc_inc (STB_LOCAL)
ffffffff8213589b-ffffffff821358b0: __ipv6_dev_mc_inc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int __ipv6_dev_mc_inc(struct net_device *dev, const struct in6_addr *addr, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/mcast.c (0)
Location: net/ipv6/mcast.c:906
Inline: False
Direct callers:
  - net/ipv6/mcast.c:ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
**Symbols:**

```
ffffffff820c3c10-ffffffff820c4004: __ipv6_dev_mc_inc (STB_LOCAL)
ffffffff822173a8-ffffffff822173bd: __ipv6_dev_mc_inc.cold (STB_LOCAL)
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
int __ipv6_dev_mc_inc(struct net_device *dev, const struct in6_addr *addr, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffff800010d31408)
Location: net/ipv6/mcast.c:883
Inline: False
Direct callers:
  - net/ipv6/mcast.c:ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
**Symbols:**

```
ffff800010d31408-ffff800010d31714: __ipv6_dev_mc_inc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __ipv6_dev_mc_inc(struct net_device *dev, const struct in6_addr *addr, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (c0e347f0)
Location: net/ipv6/mcast.c:883
Inline: False
Direct callers:
  - net/ipv6/mcast.c:ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
**Symbols:**

```
c0e347f0-c0e34ab4: __ipv6_dev_mc_inc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __ipv6_dev_mc_inc(struct net_device *dev, const struct in6_addr *addr, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (c000000000e639e0)
Location: net/ipv6/mcast.c:883
Inline: False
Direct callers:
  - net/ipv6/mcast.c:ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
**Symbols:**

```
c000000000e639e0-c000000000e63dbc: __ipv6_dev_mc_inc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __ipv6_dev_mc_inc(struct net_device *dev, const struct in6_addr *addr, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffe00086fd02)
Location: net/ipv6/mcast.c:883
Inline: False
Direct callers:
  - net/ipv6/mcast.c:ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
**Symbols:**

```
ffffffe00086fd02-ffffffe00086ff78: __ipv6_dev_mc_inc (STB_LOCAL)
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
int __ipv6_dev_mc_inc(struct net_device *dev, const struct in6_addr *addr, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff81a09a60)
Location: net/ipv6/mcast.c:883
Inline: False
Direct callers:
  - net/ipv6/mcast.c:ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
**Symbols:**

```
ffffffff81a09a60-ffffffff81a09ce9: __ipv6_dev_mc_inc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __ipv6_dev_mc_inc(struct net_device *dev, const struct in6_addr *addr, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff819c6820)
Location: net/ipv6/mcast.c:883
Inline: False
Direct callers:
  - net/ipv6/mcast.c:ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
**Symbols:**

```
ffffffff819c6820-ffffffff819c6aa9: __ipv6_dev_mc_inc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __ipv6_dev_mc_inc(struct net_device *dev, const struct in6_addr *addr, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff81a744e0)
Location: net/ipv6/mcast.c:883
Inline: False
Direct callers:
  - net/ipv6/mcast.c:ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
**Symbols:**

```
ffffffff81a744e0-ffffffff81a74769: __ipv6_dev_mc_inc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __ipv6_dev_mc_inc(struct net_device *dev, const struct in6_addr *addr, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff81a80b80)
Location: net/ipv6/mcast.c:883
Inline: False
Direct callers:
  - net/ipv6/mcast.c:ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
**Symbols:**

```
ffffffff81a80b80-ffffffff81a80e13: __ipv6_dev_mc_inc (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
