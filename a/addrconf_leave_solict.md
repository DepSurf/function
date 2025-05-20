# Function: <code>addrconf_leave_solict</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void addrconf_leave_solict(struct inet6_dev *idev, const struct in6_addr *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff817cac50)
Location: net/ipv6/addrconf.c:1917
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
Direct callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
```
**Symbols:**

```
ffffffff817cac50-ffffffff817caca9: addrconf_leave_solict.part.48 (STB_LOCAL)
ffffffff817d0870-ffffffff817d088d: addrconf_leave_solict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void addrconf_leave_solict(struct inet6_dev *idev, const struct in6_addr *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81838edd)
Location: net/ipv6/addrconf.c:1968
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_ifdown
Direct callers:
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_ifdown
```
**Symbols:**

```
ffffffff81837c40-ffffffff81837c99: addrconf_leave_solict.part.51 (STB_LOCAL)
ffffffff8183e1b0-ffffffff8183e1cd: addrconf_leave_solict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
void addrconf_leave_solict(struct inet6_dev *idev, const struct in6_addr *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8186a8fd)
Location: net/ipv6/addrconf.c:2016
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_ifdown
Direct callers:
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_ifdown
```
**Symbols:**

```
ffffffff81869c00-ffffffff81869c59: addrconf_leave_solict.part.52 (STB_LOCAL)
ffffffff8186fdc0-ffffffff8186fddd: addrconf_leave_solict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void addrconf_leave_solict(struct inet6_dev *idev, const struct in6_addr *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8188ee41)
Location: net/ipv6/addrconf.c:2058
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_ifdown
Direct callers:
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_ifdown
```
**Symbols:**

```
ffffffff8188e0c0-ffffffff8188e12b: addrconf_leave_solict.part.51 (STB_LOCAL)
ffffffff81894b20-ffffffff81894b3e: addrconf_leave_solict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void addrconf_leave_solict(struct inet6_dev *idev, const struct in6_addr *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81910491)
Location: net/ipv6/addrconf.c:2082
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_ifdown
Direct callers:
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_ifdown
```
**Symbols:**

```
ffffffff8190f150-ffffffff8190f1bb: addrconf_leave_solict.part.53 (STB_LOCAL)
ffffffff81915ff0-ffffffff8191600e: addrconf_leave_solict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void addrconf_leave_solict(struct inet6_dev *idev, const struct in6_addr *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff819678c2)
Location: net/ipv6/addrconf.c:2104
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_ifdown
Direct callers:
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_ifdown
```
**Symbols:**

```
ffffffff81966260-ffffffff819662b9: addrconf_leave_solict.part.65 (STB_LOCAL)
ffffffff8196d6f0-ffffffff8196d70d: addrconf_leave_solict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void addrconf_leave_solict(struct inet6_dev *idev, const struct in6_addr *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8199cf9e)
Location: net/ipv6/addrconf.c:2120
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_ifdown
Direct callers:
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_ifdown
```
**Symbols:**

```
ffffffff8199b6d0-ffffffff8199b729: addrconf_leave_solict.part.66 (STB_LOCAL)
ffffffff819a3250-ffffffff819a326d: addrconf_leave_solict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void addrconf_leave_solict(struct inet6_dev *idev, const struct in6_addr *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81a09180)
Location: net/ipv6/addrconf.c:2153
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_ifdown
Direct callers:
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_ifdown
```
**Symbols:**

```
ffffffff81a07600-ffffffff81a07659: addrconf_leave_solict.part.0 (STB_LOCAL)
ffffffff81a0f540-ffffffff81a0f55d: addrconf_leave_solict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void addrconf_leave_solict(struct inet6_dev *idev, const struct in6_addr *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81a3fe30)
Location: net/ipv6/addrconf.c:2155
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_ifdown
Direct callers:
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_ifdown
```
**Symbols:**

```
ffffffff81a3e170-ffffffff81a3e1c9: addrconf_leave_solict.part.0 (STB_LOCAL)
ffffffff81a46280-ffffffff81a4629d: addrconf_leave_solict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void addrconf_leave_solict(struct inet6_dev *idev, const struct in6_addr *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81b35a01)
Location: net/ipv6/addrconf.c:2146
Inline: True
Direct callers:
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
```
**Symbols:**

```
ffffffff81b3d2b0-ffffffff81b3d30c: addrconf_leave_solict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void addrconf_leave_solict(struct inet6_dev *idev, const struct in6_addr *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81b444f1)
Location: net/ipv6/addrconf.c:2172
Inline: True
Direct callers:
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
```
**Symbols:**

```
ffffffff81b4bf10-ffffffff81b4bf6c: addrconf_leave_solict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void addrconf_leave_solict(struct inet6_dev *idev, const struct in6_addr *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81b31fa1)
Location: net/ipv6/addrconf.c:2174
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
Direct callers:
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
```
**Symbols:**

```
ffffffff81b39af0-ffffffff81b39b53: addrconf_leave_solict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void addrconf_leave_solict(struct inet6_dev *idev, const struct in6_addr *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81bf8071)
Location: net/ipv6/addrconf.c:2181
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
Direct callers:
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
```
**Symbols:**

```
ffffffff81c002a0-ffffffff81c00303: addrconf_leave_solict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void addrconf_leave_solict(struct inet6_dev *idev, const struct in6_addr *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81d91411)
Location: net/ipv6/addrconf.c:2184
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
Direct callers:
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
```
**Symbols:**

```
ffffffff81d99dd0-ffffffff81d99e3d: addrconf_leave_solict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void addrconf_leave_solict(struct inet6_dev *idev, const struct in6_addr *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81f5fb71)
Location: net/ipv6/addrconf.c:2184
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
Direct callers:
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
```
**Symbols:**

```
ffffffff81f68ba0-ffffffff81f68c0d: addrconf_leave_solict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void addrconf_leave_solict(struct inet6_dev *idev, const struct in6_addr *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81fbf8a1)
Location: net/ipv6/addrconf.c:2183
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
Direct callers:
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
```
**Symbols:**

```
ffffffff81fc8c70-ffffffff81fc8cdd: addrconf_leave_solict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void addrconf_leave_solict(struct inet6_dev *idev, const struct in6_addr *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8208cd41)
Location: net/ipv6/addrconf.c:2211
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
Direct callers:
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
```
**Symbols:**

```
ffffffff820963f0-ffffffff8209645d: addrconf_leave_solict (STB_GLOBAL)
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
void addrconf_leave_solict(struct inet6_dev *idev, const struct in6_addr *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (ffff800010d010b8)
Location: net/ipv6/addrconf.c:2155
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_ifdown
Direct callers:
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_ifdown
```
**Symbols:**

```
ffff800010cff0a0-ffff800010cff118: addrconf_leave_solict.part.0 (STB_LOCAL)
ffff800010d08eb8-ffff800010d08f00: addrconf_leave_solict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
void addrconf_leave_solict(struct inet6_dev *idev, const struct in6_addr *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (c0e08be4)
Location: net/ipv6/addrconf.c:2155
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_ifdown
Direct callers:
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_ifdown
```
**Symbols:**

```
c0e073b4-c0e07430: addrconf_leave_solict.part.0 (STB_LOCAL)
c0e0f494-c0e0f4c0: addrconf_leave_solict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
void addrconf_leave_solict(struct inet6_dev *idev, const struct in6_addr *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (c000000000e2af54)
Location: net/ipv6/addrconf.c:2155
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_ifdown
Direct callers:
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_ifdown
```
**Symbols:**

```
c000000000e28610-c000000000e28690: addrconf_leave_solict.part.0 (STB_LOCAL)
c000000000e33460-c000000000e33484: addrconf_leave_solict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void addrconf_leave_solict(struct inet6_dev *idev, const struct in6_addr *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (ffffffe00084b032)
Location: net/ipv6/addrconf.c:2155
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_ifdown
Direct callers:
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_ifdown
```
**Symbols:**

```
ffffffe000849a66-ffffffe000849ab6: addrconf_leave_solict.part.0 (STB_LOCAL)
ffffffe000850c30-ffffffe000850c6e: addrconf_leave_solict (STB_GLOBAL)
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
void addrconf_leave_solict(struct inet6_dev *idev, const struct in6_addr *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff819df4c0)
Location: net/ipv6/addrconf.c:2155
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_ifdown
Direct callers:
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_ifdown
```
**Symbols:**

```
ffffffff819dd800-ffffffff819dd859: addrconf_leave_solict.part.0 (STB_LOCAL)
ffffffff819e5910-ffffffff819e592d: addrconf_leave_solict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void addrconf_leave_solict(struct inet6_dev *idev, const struct in6_addr *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8199c280)
Location: net/ipv6/addrconf.c:2155
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_ifdown
Direct callers:
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_ifdown
```
**Symbols:**

```
ffffffff8199a5c0-ffffffff8199a619: addrconf_leave_solict.part.0 (STB_LOCAL)
ffffffff819a26d0-ffffffff819a26ed: addrconf_leave_solict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void addrconf_leave_solict(struct inet6_dev *idev, const struct in6_addr *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81a49f40)
Location: net/ipv6/addrconf.c:2155
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_ifdown
Direct callers:
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_ifdown
```
**Symbols:**

```
ffffffff81a48280-ffffffff81a482d9: addrconf_leave_solict.part.0 (STB_LOCAL)
ffffffff81a50390-ffffffff81a503ad: addrconf_leave_solict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void addrconf_leave_solict(struct inet6_dev *idev, const struct in6_addr *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81a55e80)
Location: net/ipv6/addrconf.c:2155
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_ifdown
Direct callers:
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_ifdown
```
**Symbols:**

```
ffffffff81a541b0-ffffffff81a54209: addrconf_leave_solict.part.0 (STB_LOCAL)
ffffffff81a5c3b0-ffffffff81a5c3cd: addrconf_leave_solict (STB_GLOBAL)
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
