# Function: <code>manage_tempaddrs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void manage_tempaddrs(struct inet6_dev *idev, struct inet6_ifaddr *ifp, __u32 valid_lft, __u32 prefered_lft, bool create, long unsigned int now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff817ced40)
Location: net/ipv6/addrconf.c:2256
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
```
**Symbols:**

```
ffffffff817ced40-ffffffff817ceec7: manage_tempaddrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void manage_tempaddrs(struct inet6_dev *idev, struct inet6_ifaddr *ifp, __u32 valid_lft, __u32 prefered_lft, bool create, long unsigned int now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8183c400)
Location: net/ipv6/addrconf.c:2306
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
```
**Symbols:**

```
ffffffff8183c400-ffffffff8183c58a: manage_tempaddrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void manage_tempaddrs(struct inet6_dev *idev, struct inet6_ifaddr *ifp, __u32 valid_lft, __u32 prefered_lft, bool create, long unsigned int now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8186e270)
Location: net/ipv6/addrconf.c:2321
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
```
**Symbols:**

```
ffffffff8186e270-ffffffff8186e3fa: manage_tempaddrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void manage_tempaddrs(struct inet6_dev *idev, struct inet6_ifaddr *ifp, __u32 valid_lft, __u32 prefered_lft, bool create, long unsigned int now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81893040)
Location: net/ipv6/addrconf.c:2376
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
```
**Symbols:**

```
ffffffff81893040-ffffffff818931ba: manage_tempaddrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void manage_tempaddrs(struct inet6_dev *idev, struct inet6_ifaddr *ifp, __u32 valid_lft, __u32 prefered_lft, bool create, long unsigned int now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81914310)
Location: net/ipv6/addrconf.c:2400
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
```
**Symbols:**

```
ffffffff81914310-ffffffff8191448c: manage_tempaddrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void manage_tempaddrs(struct inet6_dev *idev, struct inet6_ifaddr *ifp, __u32 valid_lft, __u32 prefered_lft, bool create, long unsigned int now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8196b520)
Location: net/ipv6/addrconf.c:2426
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
```
**Symbols:**

```
ffffffff8196b520-ffffffff8196b69c: manage_tempaddrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void manage_tempaddrs(struct inet6_dev *idev, struct inet6_ifaddr *ifp, __u32 valid_lft, __u32 prefered_lft, bool create, long unsigned int now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff819a13b0)
Location: net/ipv6/addrconf.c:2442
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
```
**Symbols:**

```
ffffffff819a13b0-ffffffff819a152c: manage_tempaddrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void manage_tempaddrs(struct inet6_dev *idev, struct inet6_ifaddr *ifp, __u32 valid_lft, __u32 prefered_lft, bool create, long unsigned int now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81a0d590)
Location: net/ipv6/addrconf.c:2482
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
```
**Symbols:**

```
ffffffff81a0d590-ffffffff81a0d70e: manage_tempaddrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void manage_tempaddrs(struct inet6_dev *idev, struct inet6_ifaddr *ifp, __u32 valid_lft, __u32 prefered_lft, bool create, long unsigned int now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81a44270)
Location: net/ipv6/addrconf.c:2484
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
```
**Symbols:**

```
ffffffff81a44270-ffffffff81a443ee: manage_tempaddrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void manage_tempaddrs(struct inet6_dev *idev, struct inet6_ifaddr *ifp, __u32 valid_lft, __u32 prefered_lft, bool create, long unsigned int now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81b3a430)
Location: net/ipv6/addrconf.c:2473
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
```
**Symbols:**

```
ffffffff81b3a430-ffffffff81b3a5ff: manage_tempaddrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void manage_tempaddrs(struct inet6_dev *idev, struct inet6_ifaddr *ifp, __u32 valid_lft, __u32 prefered_lft, bool create, long unsigned int now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81b49130)
Location: net/ipv6/addrconf.c:2500
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
```
**Symbols:**

```
ffffffff81b49130-ffffffff81b492ff: manage_tempaddrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void manage_tempaddrs(struct inet6_dev *idev, struct inet6_ifaddr *ifp, __u32 valid_lft, __u32 prefered_lft, bool create, long unsigned int now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81b36d90)
Location: net/ipv6/addrconf.c:2502
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
```
**Symbols:**

```
ffffffff81b36d90-ffffffff81b36f26: manage_tempaddrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void manage_tempaddrs(struct inet6_dev *idev, struct inet6_ifaddr *ifp, __u32 valid_lft, __u32 prefered_lft, bool create, long unsigned int now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81bfd540)
Location: net/ipv6/addrconf.c:2509
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
```
**Symbols:**

```
ffffffff81bfd540-ffffffff81bfd6d6: manage_tempaddrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void manage_tempaddrs(struct inet6_dev *idev, struct inet6_ifaddr *ifp, __u32 valid_lft, __u32 prefered_lft, bool create, long unsigned int now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81d96f00)
Location: net/ipv6/addrconf.c:2512
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
```
**Symbols:**

```
ffffffff81d96f00-ffffffff81d970bb: manage_tempaddrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void manage_tempaddrs(struct inet6_dev *idev, struct inet6_ifaddr *ifp, __u32 valid_lft, __u32 prefered_lft, bool create, long unsigned int now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81f65ab0)
Location: net/ipv6/addrconf.c:2512
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
```
**Symbols:**

```
ffffffff81f65ab0-ffffffff81f65c6b: manage_tempaddrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void manage_tempaddrs(struct inet6_dev *idev, struct inet6_ifaddr *ifp, __u32 valid_lft, __u32 prefered_lft, bool create, long unsigned int now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81fc5bc0)
Location: net/ipv6/addrconf.c:2511
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
```
**Symbols:**

```
ffffffff81fc5bc0-ffffffff81fc5d80: manage_tempaddrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void manage_tempaddrs(struct inet6_dev *idev, struct inet6_ifaddr *ifp, __u32 valid_lft, __u32 prefered_lft, bool create, long unsigned int now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff82093190)
Location: net/ipv6/addrconf.c:2539
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
```
**Symbols:**

```
ffffffff82093190-ffffffff82093351: manage_tempaddrs (STB_LOCAL)
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
void manage_tempaddrs(struct inet6_dev *idev, struct inet6_ifaddr *ifp, __u32 valid_lft, __u32 prefered_lft, bool create, long unsigned int now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffff800010d06460)
Location: net/ipv6/addrconf.c:2484
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
```
**Symbols:**

```
ffff800010d06460-ffff800010d0670c: manage_tempaddrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void manage_tempaddrs(struct inet6_dev *idev, struct inet6_ifaddr *ifp, __u32 valid_lft, __u32 prefered_lft, bool create, long unsigned int now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (c0e0d1e4)
Location: net/ipv6/addrconf.c:2484
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
```
**Symbols:**

```
c0e0d1e4-c0e0d358: manage_tempaddrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void manage_tempaddrs(struct inet6_dev *idev, struct inet6_ifaddr *ifp, __u32 valid_lft, __u32 prefered_lft, bool create, long unsigned int now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (c000000000e30740)
Location: net/ipv6/addrconf.c:2484
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
```
**Symbols:**

```
c000000000e30740-c000000000e309cc: manage_tempaddrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void manage_tempaddrs(struct inet6_dev *idev, struct inet6_ifaddr *ifp, __u32 valid_lft, __u32 prefered_lft, bool create, long unsigned int now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffe00084db04)
Location: net/ipv6/addrconf.c:2484
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
```
**Symbols:**

```
ffffffe00084db04-ffffffe00084dc9a: manage_tempaddrs (STB_LOCAL)
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
void manage_tempaddrs(struct inet6_dev *idev, struct inet6_ifaddr *ifp, __u32 valid_lft, __u32 prefered_lft, bool create, long unsigned int now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff819e3900)
Location: net/ipv6/addrconf.c:2484
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
```
**Symbols:**

```
ffffffff819e3900-ffffffff819e3a7e: manage_tempaddrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void manage_tempaddrs(struct inet6_dev *idev, struct inet6_ifaddr *ifp, __u32 valid_lft, __u32 prefered_lft, bool create, long unsigned int now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff819a06c0)
Location: net/ipv6/addrconf.c:2484
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
```
**Symbols:**

```
ffffffff819a06c0-ffffffff819a083e: manage_tempaddrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void manage_tempaddrs(struct inet6_dev *idev, struct inet6_ifaddr *ifp, __u32 valid_lft, __u32 prefered_lft, bool create, long unsigned int now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81a4e380)
Location: net/ipv6/addrconf.c:2484
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
```
**Symbols:**

```
ffffffff81a4e380-ffffffff81a4e4fe: manage_tempaddrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void manage_tempaddrs(struct inet6_dev *idev, struct inet6_ifaddr *ifp, __u32 valid_lft, __u32 prefered_lft, bool create, long unsigned int now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81a5a320)
Location: net/ipv6/addrconf.c:2484
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
```
**Symbols:**

```
ffffffff81a5a320-ffffffff81a5a499: manage_tempaddrs (STB_LOCAL)
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
