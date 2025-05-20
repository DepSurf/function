# Function: <code>inet_add_protocol</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int inet_add_protocol(const struct net_protocol *prot, unsigned char protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/protocol.c (ffffffff81758650)
Location: net/ipv4/protocol.c:35
Inline: False
Direct callers:
  - net/ipv4/udplite.c:udplite4_register
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_register
```
**Symbols:**

```
ffffffff81758650-ffffffff81758692: inet_add_protocol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int inet_add_protocol(const struct net_protocol *prot, unsigned char protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/protocol.c (ffffffff817c4930)
Location: net/ipv4/protocol.c:35
Inline: False
Direct callers:
  - net/ipv4/udplite.c:udplite4_register
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_register
```
**Symbols:**

```
ffffffff817c4930-ffffffff817c4972: inet_add_protocol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int inet_add_protocol(const struct net_protocol *prot, unsigned char protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/protocol.c (ffffffff817f4450)
Location: net/ipv4/protocol.c:35
Inline: False
Direct callers:
  - net/ipv4/udplite.c:udplite4_register
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_register
```
**Symbols:**

```
ffffffff817f4450-ffffffff817f4492: inet_add_protocol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int inet_add_protocol(const struct net_protocol *prot, unsigned char protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/protocol.c (ffffffff81814880)
Location: net/ipv4/protocol.c:35
Inline: False
Direct callers:
  - net/ipv4/udplite.c:udplite4_register
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_register
```
**Symbols:**

```
ffffffff81814880-ffffffff818148c2: inet_add_protocol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int inet_add_protocol(const struct net_protocol *prot, unsigned char protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/protocol.c (ffffffff81893a20)
Location: net/ipv4/protocol.c:35
Inline: False
Direct callers:
  - net/ipv4/udplite.c:udplite4_register
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_register
```
**Symbols:**

```
ffffffff81893a20-ffffffff81893a63: inet_add_protocol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int inet_add_protocol(const struct net_protocol *prot, unsigned char protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/protocol.c (0)
Location: net/ipv4/protocol.c:35
Inline: False
Direct callers:
  - net/ipv4/udplite.c:udplite4_register
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_register
```
**Symbols:**

```
ffffffff818e7d79-ffffffff818e7d93: inet_add_protocol.cold.1 (STB_LOCAL)
ffffffff818e7cd0-ffffffff818e7d00: inet_add_protocol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int inet_add_protocol(const struct net_protocol *prot, unsigned char protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/protocol.c (0)
Location: net/ipv4/protocol.c:36
Inline: False
Direct callers:
  - net/ipv4/udplite.c:udplite4_register
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_register
```
**Symbols:**

```
ffffffff81914c29-ffffffff81914c43: inet_add_protocol.cold.1 (STB_LOCAL)
ffffffff81914b80-ffffffff81914bb0: inet_add_protocol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int inet_add_protocol(const struct net_protocol *prot, unsigned char protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/protocol.c (0)
Location: net/ipv4/protocol.c:32
Inline: False
Direct callers:
  - net/ipv4/udplite.c:udplite4_register
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_register
```
**Symbols:**

```
ffffffff81977119-ffffffff81977133: inet_add_protocol.cold (STB_LOCAL)
ffffffff81977070-ffffffff819770a0: inet_add_protocol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int inet_add_protocol(const struct net_protocol *prot, unsigned char protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/protocol.c (0)
Location: net/ipv4/protocol.c:32
Inline: False
Direct callers:
  - net/ipv4/udplite.c:udplite4_register
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_register
```
**Symbols:**

```
ffffffff819adaa9-ffffffff819adac3: inet_add_protocol.cold (STB_LOCAL)
ffffffff819ada00-ffffffff819ada30: inet_add_protocol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int inet_add_protocol(const struct net_protocol *prot, unsigned char protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/protocol.c (0)
Location: net/ipv4/protocol.c:32
Inline: False
Direct callers:
  - net/ipv4/udplite.c:udplite4_register
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_register
```
**Symbols:**

```
ffffffff81a978b9-ffffffff81a978d6: inet_add_protocol.cold (STB_LOCAL)
ffffffff81a97810-ffffffff81a97840: inet_add_protocol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int inet_add_protocol(const struct net_protocol *prot, unsigned char protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/protocol.c (0)
Location: net/ipv4/protocol.c:32
Inline: False
Direct callers:
  - net/ipv4/udplite.c:udplite4_register
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_register
```
**Symbols:**

```
ffffffff81c32515-ffffffff81c32532: inet_add_protocol.cold (STB_LOCAL)
ffffffff81aa1790-ffffffff81aa17c0: inet_add_protocol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int inet_add_protocol(const struct net_protocol *prot, unsigned char protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/protocol.c (0)
Location: net/ipv4/protocol.c:32
Inline: False
Direct callers:
  - net/ipv4/udplite.c:udplite4_register
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_register
```
**Symbols:**

```
ffffffff81c247ff-ffffffff81c2481d: inet_add_protocol.cold (STB_LOCAL)
ffffffff81a8c7b0-ffffffff81a8c7d5: inet_add_protocol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int inet_add_protocol(const struct net_protocol *prot, unsigned char protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/protocol.c (ffffffff81b478d0)
Location: net/ipv4/protocol.c:32
Inline: False
Direct callers:
  - net/ipv4/udplite.c:udplite4_register
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_register
```
**Symbols:**

```
ffffffff81b478d0-ffffffff81b478f0: inet_add_protocol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int inet_add_protocol(const struct net_protocol *prot, unsigned char protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/protocol.c (ffffffff81cd4af0)
Location: net/ipv4/protocol.c:32
Inline: False
Direct callers:
  - net/ipv4/udplite.c:udplite4_register
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_register
```
**Symbols:**

```
ffffffff81cd4af0-ffffffff81cd4b18: inet_add_protocol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int inet_add_protocol(const struct net_protocol *prot, unsigned char protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/protocol.c (ffffffff81e94de0)
Location: net/ipv4/protocol.c:32
Inline: False
Direct callers:
  - net/ipv4/udplite.c:udplite4_register
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_register
```
**Symbols:**

```
ffffffff81e94de0-ffffffff81e94e08: inet_add_protocol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int inet_add_protocol(const struct net_protocol *prot, unsigned char protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/protocol.c (ffffffff81ef35b0)
Location: net/ipv4/protocol.c:32
Inline: False
Direct callers:
  - net/ipv4/udplite.c:udplite4_register
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_register
```
**Symbols:**

```
ffffffff81ef35b0-ffffffff81ef35d8: inet_add_protocol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int inet_add_protocol(const struct net_protocol *prot, unsigned char protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/protocol.c (ffffffff81fb7540)
Location: net/ipv4/protocol.c:32
Inline: False
Direct callers:
  - net/ipv4/udplite.c:udplite4_register
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_register
```
**Symbols:**

```
ffffffff81fb7540-ffffffff81fb7568: inet_add_protocol (STB_GLOBAL)
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
int inet_add_protocol(const struct net_protocol *prot, unsigned char protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/protocol.c (ffff800010c5dca8)
Location: net/ipv4/protocol.c:32
Inline: False
Direct callers:
  - net/ipv4/udplite.c:udplite4_register
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_register
```
**Symbols:**

```
ffff800010c5dca8-ffff800010c5dd30: inet_add_protocol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int inet_add_protocol(const struct net_protocol *prot, unsigned char protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/protocol.c (c0d6d128)
Location: net/ipv4/protocol.c:32
Inline: False
Direct callers:
  - net/ipv4/udplite.c:udplite4_register
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_register
```
**Symbols:**

```
c0d6d128-c0d6d1a0: inet_add_protocol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int inet_add_protocol(const struct net_protocol *prot, unsigned char protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/protocol.c (c000000000d603e0)
Location: net/ipv4/protocol.c:32
Inline: False
Direct callers:
  - net/ipv4/udplite.c:udplite4_register
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_register
```
**Symbols:**

```
c000000000d603e0-c000000000d60470: inet_add_protocol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int inet_add_protocol(const struct net_protocol *prot, unsigned char protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/protocol.c (ffffffe0007c6640)
Location: net/ipv4/protocol.c:32
Inline: False
Direct callers:
  - net/ipv4/udplite.c:udplite4_register
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_register
```
**Symbols:**

```
ffffffe0007c6640-ffffffe0007c66ac: inet_add_protocol (STB_GLOBAL)
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
int inet_add_protocol(const struct net_protocol *prot, unsigned char protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/protocol.c (0)
Location: net/ipv4/protocol.c:32
Inline: False
Direct callers:
  - net/ipv4/udplite.c:udplite4_register
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_register
```
**Symbols:**

```
ffffffff8194d919-ffffffff8194d933: inet_add_protocol.cold (STB_LOCAL)
ffffffff8194d870-ffffffff8194d8a0: inet_add_protocol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int inet_add_protocol(const struct net_protocol *prot, unsigned char protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/protocol.c (0)
Location: net/ipv4/protocol.c:32
Inline: False
Direct callers:
  - net/ipv4/udplite.c:udplite4_register
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_register
```
**Symbols:**

```
ffffffff81907409-ffffffff81907423: inet_add_protocol.cold (STB_LOCAL)
ffffffff81907360-ffffffff81907390: inet_add_protocol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int inet_add_protocol(const struct net_protocol *prot, unsigned char protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/protocol.c (0)
Location: net/ipv4/protocol.c:32
Inline: False
Direct callers:
  - net/ipv4/udplite.c:udplite4_register
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_register
```
**Symbols:**

```
ffffffff819b80e9-ffffffff819b8103: inet_add_protocol.cold (STB_LOCAL)
ffffffff819b8040-ffffffff819b8070: inet_add_protocol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int inet_add_protocol(const struct net_protocol *prot, unsigned char protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/protocol.c (0)
Location: net/ipv4/protocol.c:32
Inline: False
Direct callers:
  - net/ipv4/udplite.c:udplite4_register
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_register
```
**Symbols:**

```
ffffffff819c1949-ffffffff819c1963: inet_add_protocol.cold (STB_LOCAL)
ffffffff819c18a0-ffffffff819c18d0: inet_add_protocol (STB_GLOBAL)
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
