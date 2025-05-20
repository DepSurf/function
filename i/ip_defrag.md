# Function: <code>ip_defrag</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ip_defrag(struct net *net, struct sk_buff *skb, u32 user);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_fragment.c (ffffffff81759750)
Location: net/ipv4/ip_fragment.c:657
Inline: False
Direct callers:
  - net/ipv4/ip_input.c:ip_call_ra_chain
  - net/ipv4/ip_input.c:ip_local_deliver
```
**Symbols:**

```
ffffffff81759750-ffffffff8175a406: ip_defrag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ip_defrag(struct net *net, struct sk_buff *skb, u32 user);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_fragment.c (ffffffff817c5b30)
Location: net/ipv4/ip_fragment.c:655
Inline: False
Direct callers:
  - net/ipv4/ip_input.c:ip_local_deliver
  - net/ipv4/ip_input.c:ip_call_ra_chain
```
**Symbols:**

```
ffffffff817c5b30-ffffffff817c686d: ip_defrag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ip_defrag(struct net *net, struct sk_buff *skb, u32 user);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_fragment.c (ffffffff817f5630)
Location: net/ipv4/ip_fragment.c:655
Inline: False
Direct callers:
  - net/ipv4/ip_input.c:ip_local_deliver
  - net/ipv4/ip_input.c:ip_call_ra_chain
```
**Symbols:**

```
ffffffff817f5630-ffffffff817f636e: ip_defrag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ip_defrag(struct net *net, struct sk_buff *skb, u32 user);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_fragment.c (ffffffff81815ad0)
Location: net/ipv4/ip_fragment.c:664
Inline: False
Direct callers:
  - net/ipv4/ip_input.c:ip_local_deliver
  - net/ipv4/ip_input.c:ip_call_ra_chain
```
**Symbols:**

```
ffffffff81815ad0-ffffffff81816783: ip_defrag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ip_defrag(struct net *net, struct sk_buff *skb, u32 user);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_fragment.c (ffffffff81894ca0)
Location: net/ipv4/ip_fragment.c:666
Inline: False
Direct callers:
  - net/ipv4/ip_input.c:ip_local_deliver
  - net/ipv4/ip_input.c:ip_call_ra_chain
```
**Symbols:**

```
ffffffff81894ca0-ffffffff81895927: ip_defrag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int ip_defrag(struct net *net, struct sk_buff *skb, u32 user);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_fragment.c (0)
Location: net/ipv4/ip_fragment.c:607
Inline: False
Direct callers:
  - net/ipv4/ip_input.c:ip_local_deliver
  - net/ipv4/ip_input.c:ip_call_ra_chain
```
**Symbols:**

```
ffffffff818e9df2-ffffffff818e9e0e: ip_defrag.cold.15 (STB_LOCAL)
ffffffff818e8da0-ffffffff818e9b34: ip_defrag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int ip_defrag(struct net *net, struct sk_buff *skb, u32 user);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_fragment.c (0)
Location: net/ipv4/ip_fragment.c:685
Inline: False
Direct callers:
  - net/ipv4/ip_input.c:ip_local_deliver
  - net/ipv4/ip_input.c:ip_call_ra_chain
```
**Symbols:**

```
ffffffff819171e3-ffffffff8191721e: ip_defrag.cold.17 (STB_LOCAL)
ffffffff81915f80-ffffffff81916d53: ip_defrag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ip_defrag(struct net *net, struct sk_buff *skb, u32 user);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_fragment.c (ffffffff81978be0)
Location: net/ipv4/ip_fragment.c:474
Inline: False
Direct callers:
  - net/ipv4/ip_input.c:ip_local_deliver
  - net/ipv4/ip_input.c:ip_call_ra_chain
```
**Symbols:**

```
ffffffff81978be0-ffffffff81978d3b: ip_defrag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ip_defrag(struct net *net, struct sk_buff *skb, u32 user);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_fragment.c (ffffffff819af550)
Location: net/ipv4/ip_fragment.c:474
Inline: False
Direct callers:
  - net/ipv4/ip_input.c:ip_local_deliver
  - net/ipv4/ip_input.c:ip_call_ra_chain
```
**Symbols:**

```
ffffffff819af550-ffffffff819af6ab: ip_defrag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ip_defrag(struct net *net, struct sk_buff *skb, u32 user);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_fragment.c (ffffffff81a993d0)
Location: net/ipv4/ip_fragment.c:474
Inline: False
Direct callers:
  - net/ipv4/ip_input.c:ip_local_deliver
  - net/ipv4/ip_input.c:ip_call_ra_chain
```
**Symbols:**

```
ffffffff81a993d0-ffffffff81a9954b: ip_defrag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ip_defrag(struct net *net, struct sk_buff *skb, u32 user);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_fragment.c (ffffffff81aa3340)
Location: net/ipv4/ip_fragment.c:474
Inline: False
Direct callers:
  - net/ipv4/ip_input.c:ip_local_deliver
  - net/ipv4/ip_input.c:ip_call_ra_chain
```
**Symbols:**

```
ffffffff81aa3340-ffffffff81aa34bb: ip_defrag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ip_defrag(struct net *net, struct sk_buff *skb, u32 user);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_fragment.c (ffffffff81a8e4b0)
Location: net/ipv4/ip_fragment.c:474
Inline: False
Direct callers:
  - net/ipv4/ip_input.c:ip_local_deliver
  - net/ipv4/ip_input.c:ip_call_ra_chain
```
**Symbols:**

```
ffffffff81a8e4b0-ffffffff81a8e628: ip_defrag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ip_defrag(struct net *net, struct sk_buff *skb, u32 user);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_fragment.c (ffffffff81b496a0)
Location: net/ipv4/ip_fragment.c:475
Inline: False
Direct callers:
  - net/ipv4/ip_input.c:ip_local_deliver
  - net/ipv4/ip_input.c:ip_call_ra_chain
```
**Symbols:**

```
ffffffff81b496a0-ffffffff81b49818: ip_defrag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ip_defrag(struct net *net, struct sk_buff *skb, u32 user);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_fragment.c (ffffffff81cd6c90)
Location: net/ipv4/ip_fragment.c:476
Inline: False
Direct callers:
  - net/ipv4/ip_input.c:ip_local_deliver
  - net/ipv4/ip_input.c:ip_call_ra_chain
  - net/ipv4/ip_fragment.c:ip_check_defrag
```
**Symbols:**

```
ffffffff81cd6c90-ffffffff81cd6e0f: ip_defrag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ip_defrag(struct net *net, struct sk_buff *skb, u32 user);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_fragment.c (ffffffff81e97220)
Location: net/ipv4/ip_fragment.c:483
Inline: False
Direct callers:
  - net/ipv4/ip_input.c:ip_local_deliver
  - net/ipv4/ip_input.c:ip_call_ra_chain
  - net/ipv4/ip_fragment.c:ip_check_defrag
```
**Symbols:**

```
ffffffff81e97220-ffffffff81e9739f: ip_defrag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ip_defrag(struct net *net, struct sk_buff *skb, u32 user);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_fragment.c (ffffffff81ef5a50)
Location: net/ipv4/ip_fragment.c:483
Inline: False
Direct callers:
  - net/ipv4/ip_input.c:ip_local_deliver
  - net/ipv4/ip_input.c:ip_call_ra_chain
  - net/ipv4/ip_fragment.c:ip_check_defrag
```
**Symbols:**

```
ffffffff81ef5a50-ffffffff81ef5bcf: ip_defrag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ip_defrag(struct net *net, struct sk_buff *skb, u32 user);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_fragment.c (ffffffff81fb9a00)
Location: net/ipv4/ip_fragment.c:483
Inline: False
Direct callers:
  - net/ipv4/ip_input.c:ip_local_deliver
  - net/ipv4/ip_input.c:ip_call_ra_chain
  - net/ipv4/ip_fragment.c:ip_check_defrag
```
**Symbols:**

```
ffffffff81fb9a00-ffffffff81fb9b7f: ip_defrag (STB_GLOBAL)
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
int ip_defrag(struct net *net, struct sk_buff *skb, u32 user);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_fragment.c (ffff800010c5fd38)
Location: net/ipv4/ip_fragment.c:474
Inline: False
Direct callers:
  - net/ipv4/ip_input.c:ip_local_deliver
  - net/ipv4/ip_input.c:ip_call_ra_chain
```
**Symbols:**

```
ffff800010c5fd38-ffff800010c5fee4: ip_defrag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ip_defrag(struct net *net, struct sk_buff *skb, u32 user);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_fragment.c (c0d6f4a8)
Location: net/ipv4/ip_fragment.c:474
Inline: False
Direct callers:
  - net/ipv4/ip_input.c:ip_local_deliver
  - net/ipv4/ip_input.c:ip_call_ra_chain
```
**Symbols:**

```
c0d6f4a8-c0d6f6d4: ip_defrag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ip_defrag(struct net *net, struct sk_buff *skb, u32 user);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_fragment.c (c000000000d62a90)
Location: net/ipv4/ip_fragment.c:474
Inline: False
Direct callers:
  - net/ipv4/ip_input.c:ip_local_deliver
  - net/ipv4/ip_input.c:ip_call_ra_chain
```
**Symbols:**

```
c000000000d62a90-c000000000d62c94: ip_defrag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ip_defrag(struct net *net, struct sk_buff *skb, u32 user);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_fragment.c (ffffffe0007c7e70)
Location: net/ipv4/ip_fragment.c:474
Inline: False
Direct callers:
  - net/ipv4/ip_input.c:ip_local_deliver
  - net/ipv4/ip_input.c:ip_call_ra_chain
```
**Symbols:**

```
ffffffe0007c7e70-ffffffe0007c7fce: ip_defrag (STB_GLOBAL)
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
int ip_defrag(struct net *net, struct sk_buff *skb, u32 user);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_fragment.c (ffffffff8194f3c0)
Location: net/ipv4/ip_fragment.c:474
Inline: False
Direct callers:
  - net/ipv4/ip_input.c:ip_local_deliver
  - net/ipv4/ip_input.c:ip_call_ra_chain
```
**Symbols:**

```
ffffffff8194f3c0-ffffffff8194f51b: ip_defrag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ip_defrag(struct net *net, struct sk_buff *skb, u32 user);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_fragment.c (ffffffff81908eb0)
Location: net/ipv4/ip_fragment.c:474
Inline: False
Direct callers:
  - net/ipv4/ip_input.c:ip_local_deliver
  - net/ipv4/ip_input.c:ip_call_ra_chain
```
**Symbols:**

```
ffffffff81908eb0-ffffffff8190900b: ip_defrag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ip_defrag(struct net *net, struct sk_buff *skb, u32 user);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_fragment.c (ffffffff819b9b90)
Location: net/ipv4/ip_fragment.c:474
Inline: False
Direct callers:
  - net/ipv4/ip_input.c:ip_local_deliver
  - net/ipv4/ip_input.c:ip_call_ra_chain
```
**Symbols:**

```
ffffffff819b9b90-ffffffff819b9ceb: ip_defrag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ip_defrag(struct net *net, struct sk_buff *skb, u32 user);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_fragment.c (ffffffff819c35d0)
Location: net/ipv4/ip_fragment.c:474
Inline: False
Direct callers:
  - net/ipv4/ip_input.c:ip_local_deliver
  - net/ipv4/ip_input.c:ip_call_ra_chain
```
**Symbols:**

```
ffffffff819c35d0-ffffffff819c3729: ip_defrag (STB_GLOBAL)
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
