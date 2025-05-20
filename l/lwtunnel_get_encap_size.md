# Function: <code>lwtunnel_get_encap_size</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int lwtunnel_get_encap_size(struct lwtunnel_state *lwtstate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff8173e0d0)
Location: net/core/lwtunnel.c:133
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv6/route.c:inet6_rt_notify
```
**Symbols:**

```
ffffffff8173e0d0-ffffffff8173e110: lwtunnel_get_encap_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int lwtunnel_get_encap_size(struct lwtunnel_state *lwtstate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff817aa940)
Location: net/core/lwtunnel.c:170
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv6/route.c:inet6_rt_notify
```
**Symbols:**

```
ffffffff817aa940-ffffffff817aa980: lwtunnel_get_encap_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int lwtunnel_get_encap_size(struct lwtunnel_state *lwtstate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff817d94c0)
Location: net/core/lwtunnel.c:241
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv6/route.c:inet6_rt_notify
```
**Symbols:**

```
ffffffff817d94c0-ffffffff817d9500: lwtunnel_get_encap_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int lwtunnel_get_encap_size(struct lwtunnel_state *lwtstate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff817f86d0)
Location: net/core/lwtunnel.c:264
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
**Symbols:**

```
ffffffff817f86d0-ffffffff817f870e: lwtunnel_get_encap_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int lwtunnel_get_encap_size(struct lwtunnel_state *lwtstate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff81875fa0)
Location: net/core/lwtunnel.c:266
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
**Symbols:**

```
ffffffff81875fa0-ffffffff81875fe1: lwtunnel_get_encap_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int lwtunnel_get_encap_size(struct lwtunnel_state *lwtstate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff818c76c0)
Location: net/core/lwtunnel.c:266
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
**Symbols:**

```
ffffffff818c76c0-ffffffff818c7703: lwtunnel_get_encap_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int lwtunnel_get_encap_size(struct lwtunnel_state *lwtstate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff818f0800)
Location: net/core/lwtunnel.c:266
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
**Symbols:**

```
ffffffff818f0800-ffffffff818f0843: lwtunnel_get_encap_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int lwtunnel_get_encap_size(struct lwtunnel_state *lwtstate);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff81942600)
Location: net/core/lwtunnel.c:262
Inline: True
Direct callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/nexthop.c:nexthop_notify
  - net/ipv6/route.c:rt6_nlmsg_size
  - net/ipv6/route.c:rt6_nlmsg_size
  - net/ipv6/route.c:rt6_nh_nlmsg_size
```
**Symbols:**

```
ffffffff81942600-ffffffff81942646: lwtunnel_get_encap_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int lwtunnel_get_encap_size(struct lwtunnel_state *lwtstate);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff81977530)
Location: net/core/lwtunnel.c:262
Inline: True
Direct callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/nexthop.c:nexthop_notify
  - net/ipv6/route.c:rt6_nlmsg_size
  - net/ipv6/route.c:rt6_nlmsg_size
  - net/ipv6/route.c:rt6_nh_nlmsg_size
```
**Symbols:**

```
ffffffff81977530-ffffffff81977576: lwtunnel_get_encap_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int lwtunnel_get_encap_size(struct lwtunnel_state *lwtstate);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff81a4c320)
Location: net/core/lwtunnel.c:264
Inline: True
Direct callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/nexthop.c:nexthop_notify
  - net/ipv6/route.c:rt6_nlmsg_size
  - net/ipv6/route.c:rt6_nlmsg_size
  - net/ipv6/route.c:rt6_nh_nlmsg_size
```
**Symbols:**

```
ffffffff81a4c320-ffffffff81a4c366: lwtunnel_get_encap_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int lwtunnel_get_encap_size(struct lwtunnel_state *lwtstate);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff81a51f80)
Location: net/core/lwtunnel.c:264
Inline: True
Direct callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/nexthop.c:nexthop_notify
  - net/ipv6/route.c:rt6_nlmsg_size
  - net/ipv6/route.c:rt6_nlmsg_size
  - net/ipv6/route.c:rt6_nh_nlmsg_size
```
**Symbols:**

```
ffffffff81a51f80-ffffffff81a51fdf: lwtunnel_get_encap_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int lwtunnel_get_encap_size(struct lwtunnel_state *lwtstate);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff81a37880)
Location: net/core/lwtunnel.c:264
Inline: True
Direct callers:
  - net/ipv4/fib_semantics.c:fib_nlmsg_size
  - net/ipv4/nexthop.c:nexthop_notify
  - net/ipv6/route.c:rt6_nlmsg_size
  - net/ipv6/route.c:rt6_nlmsg_size
  - net/ipv6/route.c:rt6_nh_nlmsg_size
```
**Symbols:**

```
ffffffff81a37880-ffffffff81a378df: lwtunnel_get_encap_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int lwtunnel_get_encap_size(struct lwtunnel_state *lwtstate);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff81aed630)
Location: net/core/lwtunnel.c:273
Inline: True
Direct callers:
  - net/ipv4/fib_semantics.c:fib_nlmsg_size
  - net/ipv4/nexthop.c:nexthop_notify
  - net/ipv6/route.c:rt6_nlmsg_size
  - net/ipv6/route.c:rt6_nlmsg_size
  - net/ipv6/route.c:rt6_nh_nlmsg_size
```
**Symbols:**

```
ffffffff81aed630-ffffffff81aed6b4: lwtunnel_get_encap_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int lwtunnel_get_encap_size(struct lwtunnel_state *lwtstate);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff81c704e0)
Location: net/core/lwtunnel.c:273
Inline: True
Direct callers:
  - net/ipv4/fib_semantics.c:fib_nlmsg_size
  - net/ipv4/nexthop.c:nexthop_notify
  - net/ipv6/route.c:rt6_nlmsg_size
  - net/ipv6/route.c:rt6_nlmsg_size
  - net/ipv6/route.c:rt6_nh_nlmsg_size
```
**Symbols:**

```
ffffffff81c704e0-ffffffff81c70586: lwtunnel_get_encap_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int lwtunnel_get_encap_size(struct lwtunnel_state *lwtstate);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff81e28490)
Location: net/core/lwtunnel.c:276
Inline: True
Direct callers:
  - net/ipv4/fib_semantics.c:fib_nlmsg_size
  - net/ipv4/nexthop.c:nexthop_notify
  - net/ipv6/route.c:rt6_nlmsg_size
  - net/ipv6/route.c:rt6_nlmsg_size
  - net/ipv6/route.c:rt6_nlmsg_size
```
**Symbols:**

```
ffffffff81e28490-ffffffff81e28536: lwtunnel_get_encap_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int lwtunnel_get_encap_size(struct lwtunnel_state *lwtstate);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff81e9dab0)
Location: net/core/lwtunnel.c:276
Inline: True
Direct callers:
  - net/ipv4/fib_semantics.c:fib_nlmsg_size
  - net/ipv4/nexthop.c:nexthop_notify
  - net/ipv6/route.c:rt6_nlmsg_size
  - net/ipv6/route.c:rt6_nlmsg_size
  - net/ipv6/route.c:rt6_nlmsg_size
```
**Symbols:**

```
ffffffff81e9dab0-ffffffff81e9db56: lwtunnel_get_encap_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int lwtunnel_get_encap_size(struct lwtunnel_state *lwtstate);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff81f60230)
Location: net/core/lwtunnel.c:276
Inline: True
Direct callers:
  - net/ipv4/fib_semantics.c:fib_nlmsg_size
  - net/ipv4/nexthop.c:nexthop_notify
  - net/ipv6/route.c:rt6_nlmsg_size
  - net/ipv6/route.c:rt6_nlmsg_size
  - net/ipv6/route.c:rt6_nlmsg_size
```
**Symbols:**

```
ffffffff81f60230-ffffffff81f602d6: lwtunnel_get_encap_size (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int lwtunnel_get_encap_size(struct lwtunnel_state *lwtstate);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffff800010c1dfd8)
Location: net/core/lwtunnel.c:262
Inline: True
Direct callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/nexthop.c:nexthop_notify
  - net/ipv6/route.c:rt6_nlmsg_size
  - net/ipv6/route.c:rt6_nlmsg_size
  - net/ipv6/route.c:rt6_nh_nlmsg_size
```
**Symbols:**

```
ffff800010c1dfd8-ffff800010c1e054: lwtunnel_get_encap_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int lwtunnel_get_encap_size(struct lwtunnel_state *lwtstate);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (c0d35b68)
Location: net/core/lwtunnel.c:262
Inline: True
Direct callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/nexthop.c:nexthop_notify
  - net/ipv6/route.c:rt6_nlmsg_size
  - net/ipv6/route.c:rt6_nlmsg_size
  - net/ipv6/route.c:rt6_nh_nlmsg_size
```
**Symbols:**

```
c0d35b68-c0d35bd8: lwtunnel_get_encap_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int lwtunnel_get_encap_size(struct lwtunnel_state *lwtstate);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (c000000000d0f6a0)
Location: net/core/lwtunnel.c:262
Inline: True
Direct callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/nexthop.c:nexthop_notify
  - net/ipv6/route.c:rt6_nlmsg_size
  - net/ipv6/route.c:rt6_nlmsg_size
  - net/ipv6/route.c:rt6_nh_nlmsg_size
```
**Symbols:**

```
c000000000d0f6a0-c000000000d0f75c: lwtunnel_get_encap_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int lwtunnel_get_encap_size(struct lwtunnel_state *lwtstate);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffe000797a42)
Location: net/core/lwtunnel.c:262
Inline: True
Direct callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/nexthop.c:nexthop_notify
  - net/ipv6/route.c:rt6_nlmsg_size
  - net/ipv6/route.c:rt6_nlmsg_size
  - net/ipv6/route.c:rt6_nh_nlmsg_size
```
**Symbols:**

```
ffffffe000797a42-ffffffe000797aa6: lwtunnel_get_encap_size (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int lwtunnel_get_encap_size(struct lwtunnel_state *lwtstate);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff819173a0)
Location: net/core/lwtunnel.c:262
Inline: True
Direct callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/nexthop.c:nexthop_notify
  - net/ipv6/route.c:rt6_nlmsg_size
  - net/ipv6/route.c:rt6_nlmsg_size
  - net/ipv6/route.c:rt6_nh_nlmsg_size
```
**Symbols:**

```
ffffffff819173a0-ffffffff819173e6: lwtunnel_get_encap_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int lwtunnel_get_encap_size(struct lwtunnel_state *lwtstate);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff818d1150)
Location: net/core/lwtunnel.c:262
Inline: True
Direct callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/nexthop.c:nexthop_notify
  - net/ipv6/route.c:rt6_nlmsg_size
  - net/ipv6/route.c:rt6_nlmsg_size
  - net/ipv6/route.c:rt6_nh_nlmsg_size
```
**Symbols:**

```
ffffffff818d1150-ffffffff818d1196: lwtunnel_get_encap_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int lwtunnel_get_encap_size(struct lwtunnel_state *lwtstate);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff81968530)
Location: net/core/lwtunnel.c:262
Inline: True
Direct callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/nexthop.c:nexthop_notify
  - net/ipv6/route.c:rt6_nlmsg_size
  - net/ipv6/route.c:rt6_nlmsg_size
  - net/ipv6/route.c:rt6_nh_nlmsg_size
```
**Symbols:**

```
ffffffff81968530-ffffffff81968576: lwtunnel_get_encap_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int lwtunnel_get_encap_size(struct lwtunnel_state *lwtstate);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff8198a870)
Location: net/core/lwtunnel.c:262
Inline: True
Direct callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/nexthop.c:nexthop_notify
  - net/ipv6/route.c:rt6_nlmsg_size
  - net/ipv6/route.c:rt6_nlmsg_size
  - net/ipv6/route.c:rt6_nh_nlmsg_size
```
**Symbols:**

```
ffffffff8198a870-ffffffff8198a8e7: lwtunnel_get_encap_size (STB_GLOBAL)
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
