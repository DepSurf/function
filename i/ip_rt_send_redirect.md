# Function: <code>ip_rt_send_redirect</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ip_rt_send_redirect(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff817575b0)
Location: net/ipv4/route.c:835
Inline: False
Direct callers:
  - net/ipv4/ip_forward.c:ip_forward
```
**Symbols:**

```
ffffffff817575b0-ffffffff81757816: ip_rt_send_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void ip_rt_send_redirect(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff817c3850)
Location: net/ipv4/route.c:841
Inline: False
Direct callers:
  - net/ipv4/ip_forward.c:ip_forward
```
**Symbols:**

```
ffffffff817c3850-ffffffff817c3ab5: ip_rt_send_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ip_rt_send_redirect(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff817f3370)
Location: net/ipv4/route.c:847
Inline: False
Direct callers:
  - net/ipv4/ip_forward.c:ip_forward
```
**Symbols:**

```
ffffffff817f3370-ffffffff817f35d5: ip_rt_send_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void ip_rt_send_redirect(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81810fb0)
Location: net/ipv4/route.c:865
Inline: False
Direct callers:
  - net/ipv4/ip_forward.c:ip_forward
```
**Symbols:**

```
ffffffff81810fb0-ffffffff8181122d: ip_rt_send_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ip_rt_send_redirect(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81890590)
Location: net/ipv4/route.c:872
Inline: False
Direct callers:
  - net/ipv4/ip_forward.c:ip_forward
```
**Symbols:**

```
ffffffff81890590-ffffffff8189080d: ip_rt_send_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void ip_rt_send_redirect(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (0)
Location: net/ipv4/route.c:860
Inline: False
Direct callers:
  - net/ipv4/ip_forward.c:ip_forward
```
**Symbols:**

```
ffffffff818e76d2-ffffffff818e771b: ip_rt_send_redirect.cold.63 (STB_LOCAL)
ffffffff818e3d20-ffffffff818e3f4d: ip_rt_send_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void ip_rt_send_redirect(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (0)
Location: net/ipv4/route.c:860
Inline: False
Direct callers:
  - net/ipv4/ip_forward.c:ip_forward
```
**Symbols:**

```
ffffffff81914582-ffffffff819145cb: ip_rt_send_redirect.cold.66 (STB_LOCAL)
ffffffff81910c00-ffffffff81910e3e: ip_rt_send_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void ip_rt_send_redirect(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (0)
Location: net/ipv4/route.c:869
Inline: False
Direct callers:
  - net/ipv4/ip_forward.c:ip_forward
```
**Symbols:**

```
ffffffff81976a4d-ffffffff81976a98: ip_rt_send_redirect.cold (STB_LOCAL)
ffffffff819732f0-ffffffff81973541: ip_rt_send_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void ip_rt_send_redirect(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (0)
Location: net/ipv4/route.c:871
Inline: False
Direct callers:
  - net/ipv4/ip_forward.c:ip_forward
```
**Symbols:**

```
ffffffff819ad412-ffffffff819ad45d: ip_rt_send_redirect.cold (STB_LOCAL)
ffffffff819a9c70-ffffffff819a9ec6: ip_rt_send_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void ip_rt_send_redirect(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (0)
Location: net/ipv4/route.c:872
Inline: False
Direct callers:
  - net/ipv4/ip_forward.c:ip_forward
```
**Symbols:**

```
ffffffff81a971cb-ffffffff81a97215: ip_rt_send_redirect.cold (STB_LOCAL)
ffffffff81a94370-ffffffff81a945b1: ip_rt_send_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void ip_rt_send_redirect(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (0)
Location: net/ipv4/route.c:872
Inline: False
Direct callers:
  - net/ipv4/ip_forward.c:ip_forward
```
**Symbols:**

```
ffffffff81c324a3-ffffffff81c324ed: ip_rt_send_redirect.cold (STB_LOCAL)
ffffffff81a9e330-ffffffff81a9e57f: ip_rt_send_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void ip_rt_send_redirect(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (0)
Location: net/ipv4/route.c:856
Inline: False
Direct callers:
  - net/ipv4/ip_forward.c:ip_forward
```
**Symbols:**

```
ffffffff81c2478c-ffffffff81c247d7: ip_rt_send_redirect.cold (STB_LOCAL)
ffffffff81a89290-ffffffff81a894ea: ip_rt_send_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void ip_rt_send_redirect(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (0)
Location: net/ipv4/route.c:871
Inline: False
Direct callers:
  - net/ipv4/ip_forward.c:ip_forward
```
**Symbols:**

```
ffffffff81d39e6a-ffffffff81d39eda: ip_rt_send_redirect.cold (STB_LOCAL)
ffffffff81b43dc0-ffffffff81b4402a: ip_rt_send_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void ip_rt_send_redirect(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (0)
Location: net/ipv4/route.c:874
Inline: False
Direct callers:
  - net/ipv4/ip_forward.c:ip_forward
```
**Symbols:**

```
ffffffff81f065b2-ffffffff81f06624: ip_rt_send_redirect.cold (STB_LOCAL)
ffffffff81cd0900-ffffffff81cd0ba4: ip_rt_send_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void ip_rt_send_redirect(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (0)
Location: net/ipv4/route.c:874
Inline: False
Direct callers:
  - net/ipv4/ip_forward.c:ip_forward
```
**Symbols:**

```
ffffffff820ae147-ffffffff820ae16d: ip_rt_send_redirect.cold (STB_LOCAL)
ffffffff81e90ae0-ffffffff81e90dc6: ip_rt_send_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void ip_rt_send_redirect(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (0)
Location: net/ipv4/route.c:874
Inline: False
Direct callers:
  - net/ipv4/ip_forward.c:ip_forward
```
**Symbols:**

```
ffffffff8212f645-ffffffff8212f66b: ip_rt_send_redirect.cold (STB_LOCAL)
ffffffff81eef290-ffffffff81eef579: ip_rt_send_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void ip_rt_send_redirect(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (0)
Location: net/ipv4/route.c:874
Inline: False
Direct callers:
  - net/ipv4/ip_forward.c:ip_forward
```
**Symbols:**

```
ffffffff82211402-ffffffff82211428: ip_rt_send_redirect.cold (STB_LOCAL)
ffffffff81fb33f0-ffffffff81fb36d9: ip_rt_send_redirect (STB_GLOBAL)
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
void ip_rt_send_redirect(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffff800010c59d98)
Location: net/ipv4/route.c:871
Inline: False
Direct callers:
  - net/ipv4/ip_forward.c:ip_forward
```
**Symbols:**

```
ffff800010c59d98-ffff800010c59ff4: ip_rt_send_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ip_rt_send_redirect(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (c0d693fc)
Location: net/ipv4/route.c:871
Inline: False
Direct callers:
  - net/ipv4/ip_forward.c:ip_forward
```
**Symbols:**

```
c0d693fc-c0d6966c: ip_rt_send_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ip_rt_send_redirect(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (c000000000d5b6e0)
Location: net/ipv4/route.c:871
Inline: False
Direct callers:
  - net/ipv4/ip_forward.c:ip_forward
```
**Symbols:**

```
c000000000d5b6e0-c000000000d5ba0c: ip_rt_send_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ip_rt_send_redirect(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffe0007c3462)
Location: net/ipv4/route.c:871
Inline: False
Direct callers:
  - net/ipv4/ip_forward.c:ip_forward
```
**Symbols:**

```
ffffffe0007c3462-ffffffe0007c362e: ip_rt_send_redirect (STB_GLOBAL)
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
void ip_rt_send_redirect(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (0)
Location: net/ipv4/route.c:871
Inline: False
Direct callers:
  - net/ipv4/ip_forward.c:ip_forward
```
**Symbols:**

```
ffffffff8194d282-ffffffff8194d2cd: ip_rt_send_redirect.cold (STB_LOCAL)
ffffffff81949ae0-ffffffff81949d36: ip_rt_send_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void ip_rt_send_redirect(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (0)
Location: net/ipv4/route.c:871
Inline: False
Direct callers:
  - net/ipv4/ip_forward.c:ip_forward
```
**Symbols:**

```
ffffffff81906d72-ffffffff81906dbd: ip_rt_send_redirect.cold (STB_LOCAL)
ffffffff819035d0-ffffffff81903826: ip_rt_send_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void ip_rt_send_redirect(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (0)
Location: net/ipv4/route.c:871
Inline: False
Direct callers:
  - net/ipv4/ip_forward.c:ip_forward
```
**Symbols:**

```
ffffffff819b7a52-ffffffff819b7a9d: ip_rt_send_redirect.cold (STB_LOCAL)
ffffffff819b42b0-ffffffff819b4506: ip_rt_send_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void ip_rt_send_redirect(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (0)
Location: net/ipv4/route.c:871
Inline: False
Direct callers:
  - net/ipv4/ip_forward.c:ip_forward
```
**Symbols:**

```
ffffffff819c12c2-ffffffff819c130d: ip_rt_send_redirect.cold (STB_LOCAL)
ffffffff819bd9b0-ffffffff819bdc15: ip_rt_send_redirect (STB_GLOBAL)
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
