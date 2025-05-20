# Function: <code>lwtunnel_valid_encap_type</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int lwtunnel_valid_encap_type(u16 encap_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff817d95c0)
Location: net/core/lwtunnel.c:129
Inline: False
Direct callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
  - net/ipv6/route.c:rtm_to_fib6_config
```
**Symbols:**

```
ffffffff817d95c0-ffffffff817d966f: lwtunnel_valid_encap_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int lwtunnel_valid_encap_type(u16 encap_type, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/lwtunnel.c (ffffffff817f8b78)
Location: net/core/lwtunnel.c:143
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
Direct callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
**Symbols:**

```
ffffffff817f8a20-ffffffff817f8ac1: lwtunnel_valid_encap_type.part.5 (STB_LOCAL)
ffffffff817f8ad0-ffffffff817f8b00: lwtunnel_valid_encap_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int lwtunnel_valid_encap_type(u16 encap_type, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/lwtunnel.c (ffffffff81876458)
Location: net/core/lwtunnel.c:145
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
Direct callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
**Symbols:**

```
ffffffff81876300-ffffffff818763b0: lwtunnel_valid_encap_type.part.5 (STB_LOCAL)
ffffffff818763b0-ffffffff818763e0: lwtunnel_valid_encap_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int lwtunnel_valid_encap_type(u16 encap_type, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff818c7830)
Location: net/core/lwtunnel.c:145
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
**Symbols:**

```
ffffffff818c7830-ffffffff818c7900: lwtunnel_valid_encap_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int lwtunnel_valid_encap_type(u16 encap_type, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff818f0970)
Location: net/core/lwtunnel.c:145
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
**Symbols:**

```
ffffffff818f0970-ffffffff818f0a58: lwtunnel_valid_encap_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int lwtunnel_valid_encap_type(u16 encap_type, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/lwtunnel.c (0)
Location: net/core/lwtunnel.c:140
Inline: False
Direct callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
**Symbols:**

```
ffffffff8194283c-ffffffff8194284f: lwtunnel_valid_encap_type.cold (STB_LOCAL)
ffffffff81942290-ffffffff8194238b: lwtunnel_valid_encap_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int lwtunnel_valid_encap_type(u16 encap_type, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff819771d0)
Location: net/core/lwtunnel.c:140
Inline: False
Direct callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
**Symbols:**

```
ffffffff819771d0-ffffffff819772bd: lwtunnel_valid_encap_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int lwtunnel_valid_encap_type(u16 encap_type, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff81a4bfa0)
Location: net/core/lwtunnel.c:142
Inline: False
Direct callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
**Symbols:**

```
ffffffff81a4bfa0-ffffffff81a4c0a9: lwtunnel_valid_encap_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int lwtunnel_valid_encap_type(u16 encap_type, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff81a51bc0)
Location: net/core/lwtunnel.c:142
Inline: False
Direct callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
**Symbols:**

```
ffffffff81a51bc0-ffffffff81a51cdf: lwtunnel_valid_encap_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int lwtunnel_valid_encap_type(u16 encap_type, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff81a37490)
Location: net/core/lwtunnel.c:142
Inline: False
Direct callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
**Symbols:**

```
ffffffff81a37490-ffffffff81a375d4: lwtunnel_valid_encap_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int lwtunnel_valid_encap_type(u16 encap_type, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff81aed120)
Location: net/core/lwtunnel.c:147
Inline: False
Direct callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
**Symbols:**

```
ffffffff81aed120-ffffffff81aed2c5: lwtunnel_valid_encap_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int lwtunnel_valid_encap_type(u16 encap_type, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff81c6fdb0)
Location: net/core/lwtunnel.c:147
Inline: False
Direct callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
**Symbols:**

```
ffffffff81c6fdb0-ffffffff81c6ff32: lwtunnel_valid_encap_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int lwtunnel_valid_encap_type(u16 encap_type, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff81e27ce0)
Location: net/core/lwtunnel.c:150
Inline: False
Direct callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
**Symbols:**

```
ffffffff81e27ce0-ffffffff81e27e71: lwtunnel_valid_encap_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int lwtunnel_valid_encap_type(u16 encap_type, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff81e9d2f0)
Location: net/core/lwtunnel.c:150
Inline: False
Direct callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
**Symbols:**

```
ffffffff81e9d2f0-ffffffff81e9d48a: lwtunnel_valid_encap_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int lwtunnel_valid_encap_type(u16 encap_type, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff81f5fa70)
Location: net/core/lwtunnel.c:150
Inline: False
Direct callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
**Symbols:**

```
ffffffff81f5fa70-ffffffff81f5fc0a: lwtunnel_valid_encap_type (STB_GLOBAL)
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
int lwtunnel_valid_encap_type(u16 encap_type, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffff800010c1daf0)
Location: net/core/lwtunnel.c:140
Inline: False
Direct callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
**Symbols:**

```
ffff800010c1daf0-ffff800010c1dc18: lwtunnel_valid_encap_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int lwtunnel_valid_encap_type(u16 encap_type, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (c0d35780)
Location: net/core/lwtunnel.c:140
Inline: False
Direct callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
**Symbols:**

```
c0d35780-c0d358b0: lwtunnel_valid_encap_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int lwtunnel_valid_encap_type(u16 encap_type, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (c000000000d0efc0)
Location: net/core/lwtunnel.c:140
Inline: False
Direct callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
**Symbols:**

```
c000000000d0efc0-c000000000d0f18c: lwtunnel_valid_encap_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int lwtunnel_valid_encap_type(u16 encap_type, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffe0007976b4)
Location: net/core/lwtunnel.c:140
Inline: False
Direct callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
**Symbols:**

```
ffffffe0007976b4-ffffffe0007977ae: lwtunnel_valid_encap_type (STB_GLOBAL)
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
int lwtunnel_valid_encap_type(u16 encap_type, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff81917040)
Location: net/core/lwtunnel.c:140
Inline: False
Direct callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
**Symbols:**

```
ffffffff81917040-ffffffff8191712d: lwtunnel_valid_encap_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int lwtunnel_valid_encap_type(u16 encap_type, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff818d0df0)
Location: net/core/lwtunnel.c:140
Inline: False
Direct callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
**Symbols:**

```
ffffffff818d0df0-ffffffff818d0edd: lwtunnel_valid_encap_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int lwtunnel_valid_encap_type(u16 encap_type, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff819681d0)
Location: net/core/lwtunnel.c:140
Inline: False
Direct callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
**Symbols:**

```
ffffffff819681d0-ffffffff819682bd: lwtunnel_valid_encap_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int lwtunnel_valid_encap_type(u16 encap_type, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff8198a470)
Location: net/core/lwtunnel.c:140
Inline: False
Direct callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
**Symbols:**

```
ffffffff8198a470-ffffffff8198a57a: lwtunnel_valid_encap_type (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct netlink_ext_ack *extack</code>
</li>
</ul>
</details>
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
