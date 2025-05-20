# Function: <code>inet_send_prepare</code>

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
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int inet_send_prepare(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff819bea00)
Location: net/ipv4/af_inet.c:787
Inline: True
Direct callers:
  - net/ipv4/af_inet.c:inet_sendpage
  - net/ipv4/af_inet.c:inet_sendmsg
  - net/ipv6/af_inet6.c:inet6_sendmsg
```
**Symbols:**

```
ffffffff819bea00-ffffffff819bea7a: inet_send_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int inet_send_prepare(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff819f5630)
Location: net/ipv4/af_inet.c:787
Inline: True
Direct callers:
  - net/ipv4/af_inet.c:inet_sendpage
  - net/ipv4/af_inet.c:inet_sendmsg
  - net/ipv6/af_inet6.c:inet6_sendmsg
```
**Symbols:**

```
ffffffff819f5630-ffffffff819f56aa: inet_send_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int inet_send_prepare(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81ae3cc0)
Location: net/ipv4/af_inet.c:794
Inline: True
Direct callers:
  - net/ipv4/af_inet.c:inet_sendpage
  - net/ipv4/af_inet.c:inet_sendmsg
  - net/ipv6/af_inet6.c:inet6_sendmsg
```
**Symbols:**

```
ffffffff81ae3cc0-ffffffff81ae3d3f: inet_send_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int inet_send_prepare(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81af0be0)
Location: net/ipv4/af_inet.c:797
Inline: True
Direct callers:
  - net/ipv4/af_inet.c:inet_sendpage
  - net/ipv4/af_inet.c:inet_sendmsg
  - net/ipv6/af_inet6.c:inet6_sendmsg
```
**Symbols:**

```
ffffffff81af0be0-ffffffff81af0c6d: inet_send_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int inet_send_prepare(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81adc3a0)
Location: net/ipv4/af_inet.c:801
Inline: True
Direct callers:
  - net/ipv4/af_inet.c:inet_sendpage
  - net/ipv4/af_inet.c:inet_sendmsg
  - net/ipv6/af_inet6.c:inet6_sendmsg
```
**Symbols:**

```
ffffffff81adc3a0-ffffffff81adc42d: inet_send_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int inet_send_prepare(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81b9b866)
Location: net/ipv4/af_inet.c:803
Inline: True
Direct callers:
  - net/ipv4/af_inet.c:inet_sendpage
  - net/ipv4/af_inet.c:inet_sendmsg
  - net/ipv6/af_inet6.c:inet6_sendmsg
```
**Symbols:**

```
ffffffff81d3c4fd-ffffffff81d3c511: inet_send_prepare.cold (STB_LOCAL)
ffffffff81b9b7e0-ffffffff81b9b879: inet_send_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int inet_send_prepare(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/af_inet.c (0)
Location: net/ipv4/af_inet.c:799
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_sendpage
  - net/ipv4/af_inet.c:inet_sendmsg
  - net/ipv6/af_inet6.c:inet6_sendmsg
```
**Symbols:**

```
ffffffff81f08d2e-ffffffff81f08d43: inet_send_prepare.cold (STB_LOCAL)
ffffffff81d2d660-ffffffff81d2d70f: inet_send_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int inet_send_prepare(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/af_inet.c (0)
Location: net/ipv4/af_inet.c:808
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_sendpage
  - net/ipv4/af_inet.c:inet_sendmsg
  - net/ipv6/af_inet6.c:inet6_sendmsg
```
**Symbols:**

```
ffffffff820b06a5-ffffffff820b06ba: inet_send_prepare.cold (STB_LOCAL)
ffffffff81ef5530-ffffffff81ef55df: inet_send_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int inet_send_prepare(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/af_inet.c (0)
Location: net/ipv4/af_inet.c:810
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_splice_eof
  - net/ipv4/af_inet.c:inet_sendmsg
  - net/ipv6/af_inet6.c:inet6_sendmsg
```
**Symbols:**

```
ffffffff8213190c-ffffffff82131921: inet_send_prepare.cold (STB_LOCAL)
ffffffff81f54d80-ffffffff81f54e30: inet_send_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int inet_send_prepare(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/af_inet.c (0)
Location: net/ipv4/af_inet.c:830
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_splice_eof
  - net/ipv4/af_inet.c:inet_sendmsg
  - net/ipv6/af_inet6.c:inet6_sendmsg
```
**Symbols:**

```
ffffffff8221327f-ffffffff82213294: inet_send_prepare.cold (STB_LOCAL)
ffffffff8201aff0-ffffffff8201b0a0: inet_send_prepare (STB_GLOBAL)
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
int inet_send_prepare(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffff800010cac4b0)
Location: net/ipv4/af_inet.c:787
Inline: True
Direct callers:
  - net/ipv4/af_inet.c:inet_sendpage
  - net/ipv4/af_inet.c:inet_sendmsg
  - net/ipv6/af_inet6.c:inet6_sendmsg
```
**Symbols:**

```
ffff800010cac4b0-ffff800010cac56c: inet_send_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int inet_send_prepare(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (c0db80c0)
Location: net/ipv4/af_inet.c:787
Inline: True
Direct callers:
  - net/ipv4/af_inet.c:inet_sendpage
  - net/ipv4/af_inet.c:inet_sendmsg
  - net/ipv6/af_inet6.c:inet6_sendmsg
```
**Symbols:**

```
c0db80c0-c0db8188: inet_send_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int inet_send_prepare(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (c000000000dc1950)
Location: net/ipv4/af_inet.c:787
Inline: True
Direct callers:
  - net/ipv4/af_inet.c:inet_sendpage
  - net/ipv4/af_inet.c:inet_sendmsg
  - net/ipv6/af_inet6.c:inet6_sendmsg
```
**Symbols:**

```
c000000000dc1950-c000000000dc1a34: inet_send_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int inet_send_prepare(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffe000805fe0)
Location: net/ipv4/af_inet.c:787
Inline: True
Direct callers:
  - net/ipv4/af_inet.c:inet_sendpage
  - net/ipv4/af_inet.c:inet_sendmsg
  - net/ipv6/af_inet6.c:inet6_sendmsg
```
**Symbols:**

```
ffffffe000805fe0-ffffffe000806074: inet_send_prepare (STB_GLOBAL)
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
int inet_send_prepare(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff819953d0)
Location: net/ipv4/af_inet.c:787
Inline: True
Direct callers:
  - net/ipv4/af_inet.c:inet_sendpage
  - net/ipv4/af_inet.c:inet_sendmsg
  - net/ipv6/af_inet6.c:inet6_sendmsg
```
**Symbols:**

```
ffffffff819953d0-ffffffff8199544a: inet_send_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int inet_send_prepare(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff8194ee90)
Location: net/ipv4/af_inet.c:787
Inline: True
Direct callers:
  - net/ipv4/af_inet.c:inet_sendpage
  - net/ipv4/af_inet.c:inet_sendmsg
  - net/ipv6/af_inet6.c:inet6_sendmsg
```
**Symbols:**

```
ffffffff8194ee90-ffffffff8194ef0a: inet_send_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int inet_send_prepare(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff819ffc70)
Location: net/ipv4/af_inet.c:787
Inline: True
Direct callers:
  - net/ipv4/af_inet.c:inet_sendpage
  - net/ipv4/af_inet.c:inet_sendmsg
  - net/ipv6/af_inet6.c:inet6_sendmsg
```
**Symbols:**

```
ffffffff819ffc70-ffffffff819ffcea: inet_send_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int inet_send_prepare(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81a09d80)
Location: net/ipv4/af_inet.c:787
Inline: True
Direct callers:
  - net/ipv4/af_inet.c:inet_sendpage
  - net/ipv4/af_inet.c:inet_sendmsg
  - net/ipv6/af_inet6.c:inet6_sendmsg
```
**Symbols:**

```
ffffffff81a09d80-ffffffff81a09e1b: inet_send_prepare (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
