# Function: <code>nla_reserve_nohdr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void *nla_reserve_nohdr(struct sk_buff *skb, int attrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff81415b10)
Location: lib/nlattr.c:409
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
**Symbols:**

```
ffffffff81415b10-ffffffff81415b40: nla_reserve_nohdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *nla_reserve_nohdr(struct sk_buff *skb, int attrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff8145d940)
Location: lib/nlattr.c:463
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
**Symbols:**

```
ffffffff8145d940-ffffffff8145d970: nla_reserve_nohdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *nla_reserve_nohdr(struct sk_buff *skb, int attrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff8147c400)
Location: lib/nlattr.c:463
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
```
**Symbols:**

```
ffffffff8147c400-ffffffff8147c430: nla_reserve_nohdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *nla_reserve_nohdr(struct sk_buff *skb, int attrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff81485810)
Location: lib/nlattr.c:466
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/ipmr.c:__ipmr_fill_mroute
  - net/ipv6/route.c:rt6_add_nexthop
  - net/ipv6/ip6mr.c:__ip6mr_fill_mroute
```
**Symbols:**

```
ffffffff81485810-ffffffff81485865: nla_reserve_nohdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *nla_reserve_nohdr(struct sk_buff *skb, int attrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff814c19a0)
Location: lib/nlattr.c:544
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/ipmr.c:__ipmr_fill_mroute
  - net/ipv6/route.c:rt6_add_nexthop
  - net/ipv6/ip6mr.c:__ip6mr_fill_mroute
```
**Symbols:**

```
ffffffff814c19a0-ffffffff814c19f5: nla_reserve_nohdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *nla_reserve_nohdr(struct sk_buff *skb, int attrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff814f2890)
Location: lib/nlattr.c:544
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/ipmr_base.c:mr_fill_mroute
  - net/ipv6/route.c:rt6_add_nexthop
```
**Symbols:**

```
ffffffff814f2890-ffffffff814f28e5: nla_reserve_nohdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *nla_reserve_nohdr(struct sk_buff *skb, int attrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff81506bc0)
Location: lib/nlattr.c:719
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/ipmr_base.c:mr_fill_mroute
  - net/ipv6/route.c:rt6_add_nexthop
```
**Symbols:**

```
ffffffff81506bc0-ffffffff81506c12: nla_reserve_nohdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *nla_reserve_nohdr(struct sk_buff *skb, int attrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff81534dc0)
Location: lib/nlattr.c:751
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_add_nexthop
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
**Symbols:**

```
ffffffff81534dc0-ffffffff81534e15: nla_reserve_nohdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *nla_reserve_nohdr(struct sk_buff *skb, int attrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff81555bf0)
Location: lib/nlattr.c:751
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_add_nexthop
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
**Symbols:**

```
ffffffff81555bf0-ffffffff81555c45: nla_reserve_nohdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *nla_reserve_nohdr(struct sk_buff *skb, int attrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff815de980)
Location: lib/nlattr.c:903
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_add_nexthop
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
**Symbols:**

```
ffffffff815de980-ffffffff815de9db: nla_reserve_nohdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *nla_reserve_nohdr(struct sk_buff *skb, int attrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff815fc020)
Location: lib/nlattr.c:969
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_add_nexthop
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
**Symbols:**

```
ffffffff815fc020-ffffffff815fc07b: nla_reserve_nohdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *nla_reserve_nohdr(struct sk_buff *skb, int attrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff815dec60)
Location: lib/nlattr.c:969
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_add_nexthop
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
**Symbols:**

```
ffffffff815dec60-ffffffff815decbb: nla_reserve_nohdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *nla_reserve_nohdr(struct sk_buff *skb, int attrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff8164a7e0)
Location: lib/nlattr.c:969
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_add_nexthop
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
**Symbols:**

```
ffffffff8164a7e0-ffffffff8164a83b: nla_reserve_nohdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *nla_reserve_nohdr(struct sk_buff *skb, int attrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff81760fc0)
Location: lib/nlattr.c:969
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_add_nexthop
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
**Symbols:**

```
ffffffff81760fc0-ffffffff81761032: nla_reserve_nohdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *nla_reserve_nohdr(struct sk_buff *skb, int attrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff8188fcc0)
Location: lib/nlattr.c:984
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_add_nexthop
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
**Symbols:**

```
ffffffff8188fcc0-ffffffff8188fd32: nla_reserve_nohdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *nla_reserve_nohdr(struct sk_buff *skb, int attrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff818d2130)
Location: lib/nlattr.c:984
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_add_nexthop
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
**Symbols:**

```
ffffffff818d2130-ffffffff818d21a2: nla_reserve_nohdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *nla_reserve_nohdr(struct sk_buff *skb, int attrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff81924100)
Location: lib/nlattr.c:1016
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_add_nexthop
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
**Symbols:**

```
ffffffff81924100-ffffffff81924172: nla_reserve_nohdr (STB_GLOBAL)
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
void *nla_reserve_nohdr(struct sk_buff *skb, int attrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffff800010662118)
Location: lib/nlattr.c:751
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_add_nexthop
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
**Symbols:**

```
ffff800010662118-ffff800010662184: nla_reserve_nohdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *nla_reserve_nohdr(struct sk_buff *skb, int attrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (c080b168)
Location: lib/nlattr.c:751
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_add_nexthop
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
**Symbols:**

```
c080b168-c080b1c4: nla_reserve_nohdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *nla_reserve_nohdr(struct sk_buff *skb, int attrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (c0000000008164d0)
Location: lib/nlattr.c:751
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_add_nexthop
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
**Symbols:**

```
c0000000008164d0-c000000000816574: nla_reserve_nohdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *nla_reserve_nohdr(struct sk_buff *skb, int attrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffe00048e904)
Location: lib/nlattr.c:751
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_add_nexthop
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
**Symbols:**

```
ffffffe00048e904-ffffffe00048e93c: nla_reserve_nohdr (STB_GLOBAL)
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
void *nla_reserve_nohdr(struct sk_buff *skb, int attrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff8154e1d0)
Location: lib/nlattr.c:751
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_add_nexthop
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
**Symbols:**

```
ffffffff8154e1d0-ffffffff8154e225: nla_reserve_nohdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *nla_reserve_nohdr(struct sk_buff *skb, int attrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff8153e4b0)
Location: lib/nlattr.c:751
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_add_nexthop
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
**Symbols:**

```
ffffffff8153e4b0-ffffffff8153e505: nla_reserve_nohdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *nla_reserve_nohdr(struct sk_buff *skb, int attrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff81549f10)
Location: lib/nlattr.c:751
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_add_nexthop
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
**Symbols:**

```
ffffffff81549f10-ffffffff81549f65: nla_reserve_nohdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *nla_reserve_nohdr(struct sk_buff *skb, int attrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff81563d60)
Location: lib/nlattr.c:751
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_add_nexthop
  - net/ipv4/ipmr_base.c:mr_fill_mroute
```
**Symbols:**

```
ffffffff81563d60-ffffffff81563db5: nla_reserve_nohdr (STB_GLOBAL)
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
