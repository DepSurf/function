# Function: <code>modify_prefix_route</code>

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
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8196d37b)
Location: net/ipv6/addrconf.c:4528
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff819a2e6d)
Location: net/ipv6/addrconf.c:4550
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81a0de36)
Location: net/ipv6/addrconf.c:4588
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_addr_modify
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int modify_prefix_route(struct inet6_ifaddr *ifp, long unsigned int expires, u32 flags, bool modify_peer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81a3f9a0)
Location: net/ipv6/addrconf.c:4594
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_modify
```
**Symbols:**

```
ffffffff81a3f9a0-ffffffff81a3facb: modify_prefix_route (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int modify_prefix_route(struct inet6_ifaddr *ifp, long unsigned int expires, u32 flags, bool modify_peer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81b34690)
Location: net/ipv6/addrconf.c:4611
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_modify
```
**Symbols:**

```
ffffffff81b34690-ffffffff81b347dd: modify_prefix_route (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int modify_prefix_route(struct inet6_ifaddr *ifp, long unsigned int expires, u32 flags, bool modify_peer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81b43160)
Location: net/ipv6/addrconf.c:4638
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_modify
```
**Symbols:**

```
ffffffff81b43160-ffffffff81b432ad: modify_prefix_route (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int modify_prefix_route(struct inet6_ifaddr *ifp, long unsigned int expires, u32 flags, bool modify_peer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81b30e80)
Location: net/ipv6/addrconf.c:4642
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_modify
```
**Symbols:**

```
ffffffff81b30e80-ffffffff81b30fcd: modify_prefix_route (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int modify_prefix_route(struct inet6_ifaddr *ifp, long unsigned int expires, u32 flags, bool modify_peer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81bf73a0)
Location: net/ipv6/addrconf.c:4678
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_modify
```
**Symbols:**

```
ffffffff81bf73a0-ffffffff81bf74ed: modify_prefix_route (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int modify_prefix_route(struct inet6_ifaddr *ifp, long unsigned int expires, u32 flags, bool modify_peer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81d90a30)
Location: net/ipv6/addrconf.c:4685
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_modify
```
**Symbols:**

```
ffffffff81d90a30-ffffffff81d90b58: modify_prefix_route (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int modify_prefix_route(struct inet6_ifaddr *ifp, long unsigned int expires, u32 flags, bool modify_peer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81f5f140)
Location: net/ipv6/addrconf.c:4698
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_modify
```
**Symbols:**

```
ffffffff81f5f140-ffffffff81f5f268: modify_prefix_route (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int modify_prefix_route(struct inet6_ifaddr *ifp, long unsigned int expires, u32 flags, bool modify_peer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81fbecf0)
Location: net/ipv6/addrconf.c:4704
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_modify
```
**Symbols:**

```
ffffffff81fbecf0-ffffffff81fbee18: modify_prefix_route (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int modify_prefix_route(struct inet6_ifaddr *ifp, long unsigned int expires, u32 flags, bool modify_peer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8208c180)
Location: net/ipv6/addrconf.c:4755
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_modify
```
**Symbols:**

```
ffffffff8208c180-ffffffff8208c2a8: modify_prefix_route (STB_LOCAL)
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
int modify_prefix_route(struct inet6_ifaddr *ifp, long unsigned int expires, u32 flags, bool modify_peer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffff800010cffb78)
Location: net/ipv6/addrconf.c:4594
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_modify
```
**Symbols:**

```
ffff800010cffb78-ffff800010cffcd4: modify_prefix_route (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int modify_prefix_route(struct inet6_ifaddr *ifp, long unsigned int expires, u32 flags, bool modify_peer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (c0e080f4)
Location: net/ipv6/addrconf.c:4594
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_modify
```
**Symbols:**

```
c0e080f4-c0e08208: modify_prefix_route (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int modify_prefix_route(struct inet6_ifaddr *ifp, long unsigned int expires, u32 flags, bool modify_peer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (c000000000e29cc0)
Location: net/ipv6/addrconf.c:4594
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_modify
```
**Symbols:**

```
c000000000e29cc0-c000000000e29eb8: modify_prefix_route (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int modify_prefix_route(struct inet6_ifaddr *ifp, long unsigned int expires, u32 flags, bool modify_peer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffe000849056)
Location: net/ipv6/addrconf.c:4594
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_modify
```
**Symbols:**

```
ffffffe000849056-ffffffe00084915c: modify_prefix_route (STB_LOCAL)
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
int modify_prefix_route(struct inet6_ifaddr *ifp, long unsigned int expires, u32 flags, bool modify_peer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff819df030)
Location: net/ipv6/addrconf.c:4594
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_modify
```
**Symbols:**

```
ffffffff819df030-ffffffff819df15b: modify_prefix_route (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int modify_prefix_route(struct inet6_ifaddr *ifp, long unsigned int expires, u32 flags, bool modify_peer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8199bdf0)
Location: net/ipv6/addrconf.c:4594
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_modify
```
**Symbols:**

```
ffffffff8199bdf0-ffffffff8199bf1b: modify_prefix_route (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int modify_prefix_route(struct inet6_ifaddr *ifp, long unsigned int expires, u32 flags, bool modify_peer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81a49ab0)
Location: net/ipv6/addrconf.c:4594
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_modify
```
**Symbols:**

```
ffffffff81a49ab0-ffffffff81a49bdb: modify_prefix_route (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int modify_prefix_route(struct inet6_ifaddr *ifp, long unsigned int expires, u32 flags, bool modify_peer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81a559f0)
Location: net/ipv6/addrconf.c:4594
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_modify
```
**Symbols:**

```
ffffffff81a559f0-ffffffff81a55b1b: modify_prefix_route (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
