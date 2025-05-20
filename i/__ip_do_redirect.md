# Function: <code>__ip_do_redirect</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __ip_do_redirect(struct rtable *rt, struct sk_buff *skb, struct flowi4 *fl4, bool kill_route);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff817549b0)
Location: net/ipv4/route.c:705
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_do_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_sk_redirect
```
**Symbols:**

```
ffffffff817549b0-ffffffff81754c89: __ip_do_redirect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __ip_do_redirect(struct rtable *rt, struct sk_buff *skb, struct flowi4 *fl4, bool kill_route);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff817c0b30)
Location: net/ipv4/route.c:711
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ip_do_redirect
```
**Symbols:**

```
ffffffff817c0b30-ffffffff817c0e07: __ip_do_redirect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __ip_do_redirect(struct rtable *rt, struct sk_buff *skb, struct flowi4 *fl4, bool kill_route);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff817f0010)
Location: net/ipv4/route.c:714
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ip_do_redirect
```
**Symbols:**

```
ffffffff817f0010-ffffffff817f0454: __ip_do_redirect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __ip_do_redirect(struct rtable *rt, struct sk_buff *skb, struct flowi4 *fl4, bool kill_route);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff818100c0)
Location: net/ipv4/route.c:732
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ip_do_redirect
```
**Symbols:**

```
ffffffff818100c0-ffffffff818104db: __ip_do_redirect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __ip_do_redirect(struct rtable *rt, struct sk_buff *skb, struct flowi4 *fl4, bool kill_route);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff8188f790)
Location: net/ipv4/route.c:739
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ip_do_redirect
```
**Symbols:**

```
ffffffff8188f790-ffffffff8188fa7b: __ip_do_redirect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void __ip_do_redirect(struct rtable *rt, struct sk_buff *skb, struct flowi4 *fl4, bool kill_route);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (0)
Location: net/ipv4/route.c:726
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ip_do_redirect
```
**Symbols:**

```
ffffffff818e3530-ffffffff818e396a: __ip_do_redirect (STB_LOCAL)
ffffffff818e76ae-ffffffff818e76d2: __ip_do_redirect.cold.62 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void __ip_do_redirect(struct rtable *rt, struct sk_buff *skb, struct flowi4 *fl4, bool kill_route);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (0)
Location: net/ipv4/route.c:726
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ip_do_redirect
```
**Symbols:**

```
ffffffff819103e0-ffffffff81910814: __ip_do_redirect (STB_LOCAL)
ffffffff8191455e-ffffffff81914582: __ip_do_redirect.cold.65 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void __ip_do_redirect(struct rtable *rt, struct sk_buff *skb, struct flowi4 *fl4, bool kill_route);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (0)
Location: net/ipv4/route.c:735
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ip_do_redirect
```
**Symbols:**

```
ffffffff81972e30-ffffffff8197322c: __ip_do_redirect (STB_LOCAL)
ffffffff81976a29-ffffffff81976a4d: __ip_do_redirect.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void __ip_do_redirect(struct rtable *rt, struct sk_buff *skb, struct flowi4 *fl4, bool kill_route);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (0)
Location: net/ipv4/route.c:737
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ip_do_redirect
```
**Symbols:**

```
ffffffff819a97a0-ffffffff819a9ba2: __ip_do_redirect (STB_LOCAL)
ffffffff819ad3ee-ffffffff819ad412: __ip_do_redirect.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void __ip_do_redirect(struct rtable *rt, struct sk_buff *skb, struct flowi4 *fl4, bool kill_route);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (0)
Location: net/ipv4/route.c:736
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ip_do_redirect
```
**Symbols:**

```
ffffffff81a92bd0-ffffffff81a93067: __ip_do_redirect (STB_LOCAL)
ffffffff81a97191-ffffffff81a971b5: __ip_do_redirect.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void __ip_do_redirect(struct rtable *rt, struct sk_buff *skb, struct flowi4 *fl4, bool kill_route);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (0)
Location: net/ipv4/route.c:736
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ip_do_redirect
```
**Symbols:**

```
ffffffff81a9ca70-ffffffff81a9cef6: __ip_do_redirect (STB_LOCAL)
ffffffff81c32469-ffffffff81c3248d: __ip_do_redirect.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void __ip_do_redirect(struct rtable *rt, struct sk_buff *skb, struct flowi4 *fl4, bool kill_route);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (0)
Location: net/ipv4/route.c:720
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ip_do_redirect
```
**Symbols:**

```
ffffffff81a87b30-ffffffff81a87ff9: __ip_do_redirect (STB_LOCAL)
ffffffff81c24752-ffffffff81c24776: __ip_do_redirect.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __ip_do_redirect(struct rtable *rt, struct sk_buff *skb, struct flowi4 *fl4, bool kill_route);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (0)
Location: net/ipv4/route.c:735
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ip_do_redirect
```
**Symbols:**

```
ffffffff81b42060-ffffffff81b4258f: __ip_do_redirect (STB_LOCAL)
ffffffff81d39d1b-ffffffff81d39daf: __ip_do_redirect.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __ip_do_redirect(struct rtable *rt, struct sk_buff *skb, struct flowi4 *fl4, bool kill_route);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (0)
Location: net/ipv4/route.c:738
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ip_do_redirect
```
**Symbols:**

```
ffffffff81ccea40-ffffffff81ccef52: __ip_do_redirect (STB_LOCAL)
ffffffff81f0645e-ffffffff81f064f7: __ip_do_redirect.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void __ip_do_redirect(struct rtable *rt, struct sk_buff *skb, struct flowi4 *fl4, bool kill_route);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (0)
Location: net/ipv4/route.c:738
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ip_do_redirect
```
**Symbols:**

```
ffffffff81e8ec80-ffffffff81e8f1bd: __ip_do_redirect (STB_LOCAL)
ffffffff820ae028-ffffffff820ae09d: __ip_do_redirect.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void __ip_do_redirect(struct rtable *rt, struct sk_buff *skb, struct flowi4 *fl4, bool kill_route);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (0)
Location: net/ipv4/route.c:738
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ip_do_redirect
```
**Symbols:**

```
ffffffff81eed380-ffffffff81eed8a9: __ip_do_redirect (STB_LOCAL)
ffffffff8212f525-ffffffff8212f59a: __ip_do_redirect.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void __ip_do_redirect(struct rtable *rt, struct sk_buff *skb, struct flowi4 *fl4, bool kill_route);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (0)
Location: net/ipv4/route.c:738
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ip_do_redirect
```
**Symbols:**

```
ffffffff81fb1440-ffffffff81fb1a10: __ip_do_redirect (STB_LOCAL)
ffffffff822112ca-ffffffff82211357: __ip_do_redirect.cold (STB_LOCAL)
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
void __ip_do_redirect(struct rtable *rt, struct sk_buff *skb, struct flowi4 *fl4, bool kill_route);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffff800010c593a8)
Location: net/ipv4/route.c:737
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ip_do_redirect
```
**Symbols:**

```
ffff800010c593a8-ffff800010c59778: __ip_do_redirect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __ip_do_redirect(struct rtable *rt, struct sk_buff *skb, struct flowi4 *fl4, bool kill_route);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (c0d68eec)
Location: net/ipv4/route.c:737
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ip_do_redirect
```
**Symbols:**

```
c0d68eec-c0d6931c: __ip_do_redirect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __ip_do_redirect(struct rtable *rt, struct sk_buff *skb, struct flowi4 *fl4, bool kill_route);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (c000000000d5b090)
Location: net/ipv4/route.c:737
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ip_do_redirect
```
**Symbols:**

```
c000000000d5b090-c000000000d5b600: __ip_do_redirect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __ip_do_redirect(struct rtable *rt, struct sk_buff *skb, struct flowi4 *fl4, bool kill_route);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffe0007c309a)
Location: net/ipv4/route.c:737
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ip_do_redirect
```
**Symbols:**

```
ffffffe0007c309a-ffffffe0007c33ca: __ip_do_redirect (STB_LOCAL)
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
void __ip_do_redirect(struct rtable *rt, struct sk_buff *skb, struct flowi4 *fl4, bool kill_route);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (0)
Location: net/ipv4/route.c:737
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ip_do_redirect
```
**Symbols:**

```
ffffffff81949610-ffffffff81949a12: __ip_do_redirect (STB_LOCAL)
ffffffff8194d25e-ffffffff8194d282: __ip_do_redirect.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void __ip_do_redirect(struct rtable *rt, struct sk_buff *skb, struct flowi4 *fl4, bool kill_route);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (0)
Location: net/ipv4/route.c:737
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ip_do_redirect
```
**Symbols:**

```
ffffffff81903100-ffffffff81903502: __ip_do_redirect (STB_LOCAL)
ffffffff81906d4e-ffffffff81906d72: __ip_do_redirect.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void __ip_do_redirect(struct rtable *rt, struct sk_buff *skb, struct flowi4 *fl4, bool kill_route);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (0)
Location: net/ipv4/route.c:737
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ip_do_redirect
```
**Symbols:**

```
ffffffff819b3de0-ffffffff819b41e2: __ip_do_redirect (STB_LOCAL)
ffffffff819b7a2e-ffffffff819b7a52: __ip_do_redirect.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void __ip_do_redirect(struct rtable *rt, struct sk_buff *skb, struct flowi4 *fl4, bool kill_route);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (0)
Location: net/ipv4/route.c:737
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ip_do_redirect
```
**Symbols:**

```
ffffffff819bd4d0-ffffffff819bd8eb: __ip_do_redirect (STB_LOCAL)
ffffffff819c129e-ffffffff819c12c2: __ip_do_redirect.cold (STB_LOCAL)
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
