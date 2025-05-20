# Function: <code>cleanup_prefix_route</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void cleanup_prefix_route(struct inet6_ifaddr *ifp, long unsigned int expires, bool del_rt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff817c9ca0)
Location: net/ipv6/addrconf.c:1068
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
```
**Symbols:**

```
ffffffff817c9ca0-ffffffff817c9d10: cleanup_prefix_route (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void cleanup_prefix_route(struct inet6_ifaddr *ifp, long unsigned int expires, bool del_rt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81836e40)
Location: net/ipv6/addrconf.c:1082
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:ipv6_del_addr
```
**Symbols:**

```
ffffffff81836e40-ffffffff81836eb0: cleanup_prefix_route (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void cleanup_prefix_route(struct inet6_ifaddr *ifp, long unsigned int expires, bool del_rt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81868a00)
Location: net/ipv6/addrconf.c:1109
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:ipv6_del_addr
```
**Symbols:**

```
ffffffff81868a00-ffffffff81868a70: cleanup_prefix_route (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void cleanup_prefix_route(struct inet6_ifaddr *ifp, long unsigned int expires, bool del_rt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8188d0e0)
Location: net/ipv6/addrconf.c:1151
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:ipv6_del_addr
```
**Symbols:**

```
ffffffff8188d0e0-ffffffff8188d150: cleanup_prefix_route (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void cleanup_prefix_route(struct inet6_ifaddr *ifp, long unsigned int expires, bool del_rt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8190fc50)
Location: net/ipv6/addrconf.c:1192
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:ipv6_del_addr
```
**Symbols:**

```
ffffffff8190fc50-ffffffff8190fcc0: cleanup_prefix_route (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void cleanup_prefix_route(struct inet6_ifaddr *ifp, long unsigned int expires, bool del_rt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81966da0)
Location: net/ipv6/addrconf.c:1178
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:ipv6_del_addr
```
**Symbols:**

```
ffffffff81966da0-ffffffff81966e3a: cleanup_prefix_route (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void cleanup_prefix_route(struct inet6_ifaddr *ifp, long unsigned int expires, bool del_rt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8199c390)
Location: net/ipv6/addrconf.c:1194
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:ipv6_del_addr
```
**Symbols:**

```
ffffffff8199c390-ffffffff8199c42a: cleanup_prefix_route (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void cleanup_prefix_route(struct inet6_ifaddr *ifp, long unsigned int expires, bool del_rt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81a089a0)
Location: net/ipv6/addrconf.c:1229
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:ipv6_del_addr
```
**Symbols:**

```
ffffffff81a089a0-ffffffff81a08a44: cleanup_prefix_route (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void cleanup_prefix_route(struct inet6_ifaddr *ifp, long unsigned int expires, bool del_rt, bool del_peer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81a3f8e0)
Location: net/ipv6/addrconf.c:1229
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:ipv6_del_addr
```
**Symbols:**

```
ffffffff81a3f8e0-ffffffff81a3f994: cleanup_prefix_route (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void cleanup_prefix_route(struct inet6_ifaddr *ifp, long unsigned int expires, bool del_rt, bool del_peer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81b345c0)
Location: net/ipv6/addrconf.c:1229
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:ipv6_del_addr
```
**Symbols:**

```
ffffffff81b345c0-ffffffff81b3468d: cleanup_prefix_route (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void cleanup_prefix_route(struct inet6_ifaddr *ifp, long unsigned int expires, bool del_rt, bool del_peer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81b43090)
Location: net/ipv6/addrconf.c:1229
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:ipv6_del_addr
```
**Symbols:**

```
ffffffff81b43090-ffffffff81b4315d: cleanup_prefix_route (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void cleanup_prefix_route(struct inet6_ifaddr *ifp, long unsigned int expires, bool del_rt, bool del_peer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81b30db0)
Location: net/ipv6/addrconf.c:1231
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:ipv6_del_addr
```
**Symbols:**

```
ffffffff81b30db0-ffffffff81b30e7d: cleanup_prefix_route (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void cleanup_prefix_route(struct inet6_ifaddr *ifp, long unsigned int expires, bool del_rt, bool del_peer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81bf72d0)
Location: net/ipv6/addrconf.c:1238
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:ipv6_del_addr
```
**Symbols:**

```
ffffffff81bf72d0-ffffffff81bf739d: cleanup_prefix_route (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void cleanup_prefix_route(struct inet6_ifaddr *ifp, long unsigned int expires, bool del_rt, bool del_peer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81d90940)
Location: net/ipv6/addrconf.c:1244
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:ipv6_del_addr
```
**Symbols:**

```
ffffffff81d90940-ffffffff81d90a30: cleanup_prefix_route (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void cleanup_prefix_route(struct inet6_ifaddr *ifp, long unsigned int expires, bool del_rt, bool del_peer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81f5f040)
Location: net/ipv6/addrconf.c:1244
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:ipv6_del_addr
```
**Symbols:**

```
ffffffff81f5f040-ffffffff81f5f130: cleanup_prefix_route (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void cleanup_prefix_route(struct inet6_ifaddr *ifp, long unsigned int expires, bool del_rt, bool del_peer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81fbebf0)
Location: net/ipv6/addrconf.c:1243
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:ipv6_del_addr
```
**Symbols:**

```
ffffffff81fbebf0-ffffffff81fbece0: cleanup_prefix_route (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void cleanup_prefix_route(struct inet6_ifaddr *ifp, long unsigned int expires, bool del_rt, bool del_peer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8208c080)
Location: net/ipv6/addrconf.c:1270
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:ipv6_del_addr
```
**Symbols:**

```
ffffffff8208c080-ffffffff8208c170: cleanup_prefix_route (STB_LOCAL)
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
void cleanup_prefix_route(struct inet6_ifaddr *ifp, long unsigned int expires, bool del_rt, bool del_peer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffff800010cffaa0)
Location: net/ipv6/addrconf.c:1229
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:ipv6_del_addr
```
**Symbols:**

```
ffff800010cffaa0-ffff800010cffb74: cleanup_prefix_route (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void cleanup_prefix_route(struct inet6_ifaddr *ifp, long unsigned int expires, bool del_rt, bool del_peer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (c0e08034)
Location: net/ipv6/addrconf.c:1229
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:ipv6_del_addr
```
**Symbols:**

```
c0e08034-c0e080f4: cleanup_prefix_route (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void cleanup_prefix_route(struct inet6_ifaddr *ifp, long unsigned int expires, bool del_rt, bool del_peer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (c000000000e29b80)
Location: net/ipv6/addrconf.c:1229
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:ipv6_del_addr
```
**Symbols:**

```
c000000000e29b80-c000000000e29cc0: cleanup_prefix_route (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void cleanup_prefix_route(struct inet6_ifaddr *ifp, long unsigned int expires, bool del_rt, bool del_peer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffe000848fa0)
Location: net/ipv6/addrconf.c:1229
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:ipv6_del_addr
```
**Symbols:**

```
ffffffe000848fa0-ffffffe000849056: cleanup_prefix_route (STB_LOCAL)
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
void cleanup_prefix_route(struct inet6_ifaddr *ifp, long unsigned int expires, bool del_rt, bool del_peer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff819def70)
Location: net/ipv6/addrconf.c:1229
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:ipv6_del_addr
```
**Symbols:**

```
ffffffff819def70-ffffffff819df024: cleanup_prefix_route (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void cleanup_prefix_route(struct inet6_ifaddr *ifp, long unsigned int expires, bool del_rt, bool del_peer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8199bd30)
Location: net/ipv6/addrconf.c:1229
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:ipv6_del_addr
```
**Symbols:**

```
ffffffff8199bd30-ffffffff8199bde4: cleanup_prefix_route (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void cleanup_prefix_route(struct inet6_ifaddr *ifp, long unsigned int expires, bool del_rt, bool del_peer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81a499f0)
Location: net/ipv6/addrconf.c:1229
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:ipv6_del_addr
```
**Symbols:**

```
ffffffff81a499f0-ffffffff81a49aa4: cleanup_prefix_route (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void cleanup_prefix_route(struct inet6_ifaddr *ifp, long unsigned int expires, bool del_rt, bool del_peer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81a55930)
Location: net/ipv6/addrconf.c:1229
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:ipv6_del_addr
```
**Symbols:**

```
ffffffff81a55930-ffffffff81a559e4: cleanup_prefix_route (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool del_peer</code>
</li>
</ul>
</details>
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
