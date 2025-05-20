# Function: <code>udp_gro_complete</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int udp_gro_complete(struct sk_buff *skb, int nhoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff8178b870)
Location: net/ipv4/udp_offload.c:379
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv6/udp_offload.c:udp6_gro_complete
```
**Symbols:**

```
ffffffff8178b870-ffffffff8178b92a: udp_gro_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int udp_gro_complete(struct sk_buff *skb, int nhoff, udp_lookup_t lookup);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff817f83b0)
Location: net/ipv4/udp_offload.c:339
Inline: True
Direct callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv6/udp_offload.c:udp6_gro_complete
```
**Symbols:**

```
ffffffff817f83b0-ffffffff817f8437: udp_gro_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int udp_gro_complete(struct sk_buff *skb, int nhoff, udp_lookup_t lookup);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff81829260)
Location: net/ipv4/udp_offload.c:335
Inline: True
Direct callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv6/udp_offload.c:udp6_gro_complete
```
**Symbols:**

```
ffffffff81829260-ffffffff818292e7: udp_gro_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int udp_gro_complete(struct sk_buff *skb, int nhoff, udp_lookup_t lookup);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff8184aa20)
Location: net/ipv4/udp_offload.c:338
Inline: True
Direct callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv6/udp_offload.c:udp6_gro_complete
```
**Symbols:**

```
ffffffff8184aa20-ffffffff8184aaa8: udp_gro_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int udp_gro_complete(struct sk_buff *skb, int nhoff, udp_lookup_t lookup);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff818ca6c0)
Location: net/ipv4/udp_offload.c:330
Inline: True
Direct callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv6/udp_offload.c:udp6_gro_complete
```
**Symbols:**

```
ffffffff818ca6c0-ffffffff818ca74d: udp_gro_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int udp_gro_complete(struct sk_buff *skb, int nhoff, udp_lookup_t lookup);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff81920230)
Location: net/ipv4/udp_offload.c:429
Inline: True
Direct callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv6/udp_offload.c:udp6_gro_complete
```
**Symbols:**

```
ffffffff81920230-ffffffff819202bd: udp_gro_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int udp_gro_complete(struct sk_buff *skb, int nhoff, udp_lookup_t lookup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff8194ee90)
Location: net/ipv4/udp_offload.c:498
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv6/udp_offload.c:udp6_gro_complete
```
**Symbols:**

```
ffffffff8194ee90-ffffffff8194efd3: udp_gro_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int udp_gro_complete(struct sk_buff *skb, int nhoff, udp_lookup_t lookup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff819b3680)
Location: net/ipv4/udp_offload.c:507
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv6/udp_offload.c:udp6_gro_complete
```
**Symbols:**

```
ffffffff819b3680-ffffffff819b37cb: udp_gro_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int udp_gro_complete(struct sk_buff *skb, int nhoff, udp_lookup_t lookup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff819ea3b0)
Location: net/ipv4/udp_offload.c:507
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv6/udp_offload.c:udp6_gro_complete
```
**Symbols:**

```
ffffffff819ea3b0-ffffffff819ea4fb: udp_gro_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int udp_gro_complete(struct sk_buff *skb, int nhoff, udp_lookup_t lookup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff81ad7ec0)
Location: net/ipv4/udp_offload.c:549
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv6/udp_offload.c:udp6_gro_complete
```
**Symbols:**

```
ffffffff81ad7ec0-ffffffff81ad7ffd: udp_gro_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int udp_gro_complete(struct sk_buff *skb, int nhoff, udp_lookup_t lookup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff81ae4720)
Location: net/ipv4/udp_offload.c:624
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv6/udp_offload.c:udp6_gro_complete
```
**Symbols:**

```
ffffffff81ae4720-ffffffff81ae4869: udp_gro_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int udp_gro_complete(struct sk_buff *skb, int nhoff, udp_lookup_t lookup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff81acf940)
Location: net/ipv4/udp_offload.c:634
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv6/udp_offload.c:udp6_gro_complete
```
**Symbols:**

```
ffffffff81acf940-ffffffff81acfaab: udp_gro_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int udp_gro_complete(struct sk_buff *skb, int nhoff, udp_lookup_t lookup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff81b8e360)
Location: net/ipv4/udp_offload.c:634
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv6/udp_offload.c:udp6_gro_complete
```
**Symbols:**

```
ffffffff81b8e360-ffffffff81b8e4cb: udp_gro_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int udp_gro_complete(struct sk_buff *skb, int nhoff, udp_lookup_t lookup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff81d1f590)
Location: net/ipv4/udp_offload.c:660
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv6/udp_offload.c:udp6_gro_complete
```
**Symbols:**

```
ffffffff81d1f590-ffffffff81d1f6ed: udp_gro_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int udp_gro_complete(struct sk_buff *skb, int nhoff, udp_lookup_t lookup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff81ee6760)
Location: net/ipv4/udp_offload.c:662
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv6/udp_offload.c:udp6_gro_complete
```
**Symbols:**

```
ffffffff81ee6760-ffffffff81ee68bd: udp_gro_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int udp_gro_complete(struct sk_buff *skb, int nhoff, udp_lookup_t lookup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff81f45fa0)
Location: net/ipv4/udp_offload.c:672
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv6/udp_offload.c:udp6_gro_complete
```
**Symbols:**

```
ffffffff81f45fa0-ffffffff81f460fd: udp_gro_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int udp_gro_complete(struct sk_buff *skb, int nhoff, udp_lookup_t lookup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff8200c0e0)
Location: net/ipv4/udp_offload.c:672
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv6/udp_offload.c:udp6_gro_complete
```
**Symbols:**

```
ffffffff8200c0e0-ffffffff8200c23d: udp_gro_complete (STB_GLOBAL)
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
int udp_gro_complete(struct sk_buff *skb, int nhoff, udp_lookup_t lookup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffff800010c9ff68)
Location: net/ipv4/udp_offload.c:507
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv6/udp_offload.c:udp6_gro_complete
```
**Symbols:**

```
ffff800010c9ff68-ffff800010ca0094: udp_gro_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int udp_gro_complete(struct sk_buff *skb, int nhoff, udp_lookup_t lookup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (c0dacf0c)
Location: net/ipv4/udp_offload.c:507
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv6/udp_offload.c:udp6_gro_complete
```
**Symbols:**

```
c0dacf0c-c0dad008: udp_gro_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int udp_gro_complete(struct sk_buff *skb, int nhoff, udp_lookup_t lookup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (c000000000db29c0)
Location: net/ipv4/udp_offload.c:507
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv6/udp_offload.c:udp6_gro_complete
  - net/ipv6/udp_offload.c:udp6_gro_complete
```
**Symbols:**

```
c000000000db29c0-c000000000db2b38: udp_gro_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int udp_gro_complete(struct sk_buff *skb, int nhoff, udp_lookup_t lookup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffe0007fc6f0)
Location: net/ipv4/udp_offload.c:507
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv6/udp_offload.c:udp6_gro_complete
```
**Symbols:**

```
ffffffe0007fc6f0-ffffffe0007fc7f0: udp_gro_complete (STB_GLOBAL)
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
int udp_gro_complete(struct sk_buff *skb, int nhoff, udp_lookup_t lookup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff8198a220)
Location: net/ipv4/udp_offload.c:507
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv6/udp_offload.c:udp6_gro_complete
```
**Symbols:**

```
ffffffff8198a220-ffffffff8198a36b: udp_gro_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int udp_gro_complete(struct sk_buff *skb, int nhoff, udp_lookup_t lookup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff81943ce0)
Location: net/ipv4/udp_offload.c:507
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv6/udp_offload.c:udp6_gro_complete
```
**Symbols:**

```
ffffffff81943ce0-ffffffff81943e2b: udp_gro_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int udp_gro_complete(struct sk_buff *skb, int nhoff, udp_lookup_t lookup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff819f49f0)
Location: net/ipv4/udp_offload.c:507
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv6/udp_offload.c:udp6_gro_complete
```
**Symbols:**

```
ffffffff819f49f0-ffffffff819f4b3b: udp_gro_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int udp_gro_complete(struct sk_buff *skb, int nhoff, udp_lookup_t lookup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff819febb0)
Location: net/ipv4/udp_offload.c:507
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv6/udp_offload.c:udp6_gro_complete
```
**Symbols:**

```
ffffffff819febb0-ffffffff819fed0a: udp_gro_complete (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>udp_lookup_t lookup</code>
</li>
</ul>
</details>
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
