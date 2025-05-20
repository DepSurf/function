# Function: <code>udp_sendmsg</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int udp_sendmsg(struct sock *sk, struct msghdr *msg, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81787600)
Location: net/ipv4/udp.c:879
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv6/udp.c:udpv6_sendmsg
```
**Symbols:**

```
ffffffff81787600-ffffffff817880b3: udp_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int udp_sendmsg(struct sock *sk, struct msghdr *msg, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff817f4d30)
Location: net/ipv4/udp.c:872
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv6/udp.c:udpv6_sendmsg
```
**Symbols:**

```
ffffffff817f4d30-ffffffff817f576e: udp_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int udp_sendmsg(struct sock *sk, struct msghdr *msg, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81825e00)
Location: net/ipv4/udp.c:874
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv6/udp.c:udpv6_sendmsg
```
**Symbols:**

```
ffffffff81825e00-ffffffff818267d9: udp_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int udp_sendmsg(struct sock *sk, struct msghdr *msg, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81846590)
Location: net/ipv4/udp.c:862
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv6/udp.c:udpv6_sendmsg
```
**Symbols:**

```
ffffffff81846590-ffffffff81846fbe: udp_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int udp_sendmsg(struct sock *sk, struct msghdr *msg, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff818c5fc0)
Location: net/ipv4/udp.c:866
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv6/udp.c:udpv6_sendmsg
```
**Symbols:**

```
ffffffff818c5fc0-ffffffff818c6a20: udp_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int udp_sendmsg(struct sock *sk, struct msghdr *msg, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/udp.c (0)
Location: net/ipv4/udp.c:898
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv6/udp.c:udpv6_sendmsg
```
**Symbols:**

```
ffffffff81920137-ffffffff81920143: udp_sendmsg.cold.62 (STB_LOCAL)
ffffffff8191b700-ffffffff8191c3e6: udp_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int udp_sendmsg(struct sock *sk, struct msghdr *msg, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/udp.c (0)
Location: net/ipv4/udp.c:975
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv6/udp.c:udpv6_sendmsg
```
**Symbols:**

```
ffffffff8194ed97-ffffffff8194eda3: udp_sendmsg.cold.75 (STB_LOCAL)
ffffffff81949c90-ffffffff8194a9bb: udp_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int udp_sendmsg(struct sock *sk, struct msghdr *msg, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/udp.c (0)
Location: net/ipv4/udp.c:962
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/af_inet.c:inet_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
```
**Symbols:**

```
ffffffff819b3537-ffffffff819b3580: udp_sendmsg.cold (STB_LOCAL)
ffffffff819ae320-ffffffff819af051: udp_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int udp_sendmsg(struct sock *sk, struct msghdr *msg, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/udp.c (0)
Location: net/ipv4/udp.c:965
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/af_inet.c:inet_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
```
**Symbols:**

```
ffffffff819ea2b7-ffffffff819ea2c3: udp_sendmsg.cold (STB_LOCAL)
ffffffff819e5030-ffffffff819e5d6f: udp_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int udp_sendmsg(struct sock *sk, struct msghdr *msg, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/udp.c (0)
Location: net/ipv4/udp.c:971
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/af_inet.c:inet_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
```
**Symbols:**

```
ffffffff81ad7dc8-ffffffff81ad7dd4: udp_sendmsg.cold (STB_LOCAL)
ffffffff81ad4e80-ffffffff81ad5bcb: udp_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int udp_sendmsg(struct sock *sk, struct msghdr *msg, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/udp.c (0)
Location: net/ipv4/udp.c:1021
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/af_inet.c:inet_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
```
**Symbols:**

```
ffffffff81c327f4-ffffffff81c32800: udp_sendmsg.cold (STB_LOCAL)
ffffffff81ae13c0-ffffffff81ae21a4: udp_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int udp_sendmsg(struct sock *sk, struct msghdr *msg, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/udp.c (0)
Location: net/ipv4/udp.c:1040
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/af_inet.c:inet_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
```
**Symbols:**

```
ffffffff81c24ac6-ffffffff81c24ad2: udp_sendmsg.cold (STB_LOCAL)
ffffffff81acaf90-ffffffff81acbdfc: udp_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int udp_sendmsg(struct sock *sk, struct msghdr *msg, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/udp.c (0)
Location: net/ipv4/udp.c:1041
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/af_inet.c:inet_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
```
**Symbols:**

```
ffffffff81d3bfb5-ffffffff81d3bfc1: udp_sendmsg.cold (STB_LOCAL)
ffffffff81b89820-ffffffff81b8a68c: udp_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int udp_sendmsg(struct sock *sk, struct msghdr *msg, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/udp.c (0)
Location: net/ipv4/udp.c:1041
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/af_inet.c:inet_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
```
**Symbols:**

```
ffffffff81f088a5-ffffffff81f088b1: udp_sendmsg.cold (STB_LOCAL)
ffffffff81d1d150-ffffffff81d1e089: udp_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int udp_sendmsg(struct sock *sk, struct msghdr *msg, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81ee4270)
Location: net/ipv4/udp.c:1052
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/af_inet.c:inet_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
```
**Symbols:**

```
ffffffff81ee4270-ffffffff81ee50e7: udp_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int udp_sendmsg(struct sock *sk, struct msghdr *msg, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81f43bb0)
Location: net/ipv4/udp.c:1067
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
```
**Symbols:**

```
ffffffff81f43bb0-ffffffff81f44ad2: udp_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int udp_sendmsg(struct sock *sk, struct msghdr *msg, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff82009b30)
Location: net/ipv4/udp.c:1038
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
```
**Symbols:**

```
ffffffff82009b30-ffffffff8200ab2b: udp_sendmsg (STB_GLOBAL)
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
int udp_sendmsg(struct sock *sk, struct msghdr *msg, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffff800010c9dd20)
Location: net/ipv4/udp.c:965
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv6/udp.c:udpv6_sendmsg
```
**Symbols:**

```
ffff800010c9dd20-ffff800010c9e640: udp_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int udp_sendmsg(struct sock *sk, struct msghdr *msg, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (c0da8a14)
Location: net/ipv4/udp.c:965
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv6/udp.c:udpv6_sendmsg
```
**Symbols:**

```
c0da8a14-c0da94c0: udp_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int udp_sendmsg(struct sock *sk, struct msghdr *msg, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (c000000000dafc10)
Location: net/ipv4/udp.c:965
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv6/udp.c:udpv6_sendmsg
```
**Symbols:**

```
c000000000dafc10-c000000000db08ec: udp_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int udp_sendmsg(struct sock *sk, struct msghdr *msg, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffe0007f7c6c)
Location: net/ipv4/udp.c:965
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv6/udp.c:udpv6_sendmsg
```
**Symbols:**

```
ffffffe0007f7c6c-ffffffe0007f84be: udp_sendmsg (STB_GLOBAL)
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
int udp_sendmsg(struct sock *sk, struct msghdr *msg, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/udp.c (0)
Location: net/ipv4/udp.c:965
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/af_inet.c:inet_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
```
**Symbols:**

```
ffffffff8198a127-ffffffff8198a133: udp_sendmsg.cold (STB_LOCAL)
ffffffff81984ea0-ffffffff81985bdf: udp_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int udp_sendmsg(struct sock *sk, struct msghdr *msg, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/udp.c (0)
Location: net/ipv4/udp.c:965
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/af_inet.c:inet_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
```
**Symbols:**

```
ffffffff81943be7-ffffffff81943bf3: udp_sendmsg.cold (STB_LOCAL)
ffffffff8193e960-ffffffff8193f69f: udp_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int udp_sendmsg(struct sock *sk, struct msghdr *msg, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/udp.c (0)
Location: net/ipv4/udp.c:965
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/af_inet.c:inet_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
```
**Symbols:**

```
ffffffff819f48f7-ffffffff819f4903: udp_sendmsg.cold (STB_LOCAL)
ffffffff819ef670-ffffffff819f03af: udp_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int udp_sendmsg(struct sock *sk, struct msghdr *msg, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/udp.c (0)
Location: net/ipv4/udp.c:965
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/af_inet.c:inet_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
```
**Symbols:**

```
ffffffff819feab7-ffffffff819feac3: udp_sendmsg.cold (STB_LOCAL)
ffffffff819f9e60-ffffffff819fad25: udp_sendmsg (STB_GLOBAL)
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
