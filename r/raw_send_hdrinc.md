# Function: <code>raw_send_hdrinc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/raw.c (ffffffff81785038)
Location: net/ipv4/raw.c:338
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/raw.c (ffffffff817f2634)
Location: net/ipv4/raw.c:340
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/raw.c (ffffffff818234a1)
Location: net/ipv4/raw.c:342
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/raw.c (ffffffff8184408c)
Location: net/ipv4/raw.c:342
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/raw.c (ffffffff818c39e8)
Location: net/ipv4/raw.c:348
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/raw.c (ffffffff81919445)
Location: net/ipv4/raw.c:348
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/raw.c (ffffffff81947f79)
Location: net/ipv4/raw.c:347
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/raw.c (ffffffff819ac1e0)
Location: net/ipv4/raw.c:343
Inline: True
Direct callers:
  - net/ipv4/raw.c:raw_sendmsg
```
**Symbols:**

```
ffffffff819ac1e0-ffffffff819ac6ad: raw_send_hdrinc.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/raw.c (ffffffff819e2c90)
Location: net/ipv4/raw.c:343
Inline: True
Direct callers:
  - net/ipv4/raw.c:raw_sendmsg
```
**Symbols:**

```
ffffffff819e2c90-ffffffff819e3179: raw_send_hdrinc.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int raw_send_hdrinc(struct sock *sk, struct flowi4 *fl4, struct msghdr *msg, size_t length, struct rtable **rtp, unsigned int flags, const struct sockcm_cookie *sockc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/raw.c (ffffffff81ad0550)
Location: net/ipv4/raw.c:343
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_sendmsg
```
**Symbols:**

```
ffffffff81ad0550-ffffffff81ad0a5f: raw_send_hdrinc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int raw_send_hdrinc(struct sock *sk, struct flowi4 *fl4, struct msghdr *msg, size_t length, struct rtable **rtp, unsigned int flags, const struct sockcm_cookie *sockc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/raw.c (ffffffff81adc560)
Location: net/ipv4/raw.c:344
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_sendmsg
```
**Symbols:**

```
ffffffff81adc560-ffffffff81adca7d: raw_send_hdrinc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int raw_send_hdrinc(struct sock *sk, struct flowi4 *fl4, struct msghdr *msg, size_t length, struct rtable **rtp, unsigned int flags, const struct sockcm_cookie *sockc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/raw.c (ffffffff81ac75b0)
Location: net/ipv4/raw.c:344
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_sendmsg
```
**Symbols:**

```
ffffffff81ac75b0-ffffffff81ac7aec: raw_send_hdrinc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int raw_send_hdrinc(struct sock *sk, struct flowi4 *fl4, struct msghdr *msg, size_t length, struct rtable **rtp, unsigned int flags, const struct sockcm_cookie *sockc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/raw.c (ffffffff81b85dd0)
Location: net/ipv4/raw.c:344
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_sendmsg
```
**Symbols:**

```
ffffffff81b85dd0-ffffffff81b86346: raw_send_hdrinc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int raw_send_hdrinc(struct sock *sk, struct flowi4 *fl4, struct msghdr *msg, size_t length, struct rtable **rtp, unsigned int flags, const struct sockcm_cookie *sockc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/raw.c (ffffffff81d16700)
Location: net/ipv4/raw.c:316
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_sendmsg
```
**Symbols:**

```
ffffffff81d16700-ffffffff81d16c96: raw_send_hdrinc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int raw_send_hdrinc(struct sock *sk, struct flowi4 *fl4, struct msghdr *msg, size_t length, struct rtable **rtp, unsigned int flags, const struct sockcm_cookie *sockc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/raw.c (ffffffff81edceb0)
Location: net/ipv4/raw.c:316
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_sendmsg
```
**Symbols:**

```
ffffffff81edceb0-ffffffff81edd455: raw_send_hdrinc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int raw_send_hdrinc(struct sock *sk, struct flowi4 *fl4, struct msghdr *msg, size_t length, struct rtable **rtp, unsigned int flags, const struct sockcm_cookie *sockc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/raw.c (ffffffff81f3c100)
Location: net/ipv4/raw.c:317
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_sendmsg
```
**Symbols:**

```
ffffffff81f3c100-ffffffff81f3c6a3: raw_send_hdrinc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int raw_send_hdrinc(struct sock *sk, struct flowi4 *fl4, struct msghdr *msg, size_t length, struct rtable **rtp, unsigned int flags, const struct sockcm_cookie *sockc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/raw.c (ffffffff82002230)
Location: net/ipv4/raw.c:319
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_sendmsg
```
**Symbols:**

```
ffffffff82002230-ffffffff820027d2: raw_send_hdrinc (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/raw.c (ffff800010c97a88)
Location: net/ipv4/raw.c:343
Inline: True
Direct callers:
  - net/ipv4/raw.c:raw_sendmsg
```
**Symbols:**

```
ffff800010c97a88-ffff800010c97f04: raw_send_hdrinc.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int raw_send_hdrinc(struct sock *sk, struct flowi4 *fl4, struct msghdr *msg, size_t length, struct rtable **rtp, unsigned int flags, const struct sockcm_cookie *sockc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/raw.c (c0da5890)
Location: net/ipv4/raw.c:343
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_sendmsg
```
**Symbols:**

```
c0da5890-c0da5d64: raw_send_hdrinc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/raw.c (c000000000da89b0)
Location: net/ipv4/raw.c:343
Inline: True
Direct callers:
  - net/ipv4/raw.c:raw_sendmsg
```
**Symbols:**

```
c000000000da89b0-c000000000da8f8c: raw_send_hdrinc.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/raw.c (ffffffe0007f5f20)
Location: net/ipv4/raw.c:343
Inline: True
Direct callers:
  - net/ipv4/raw.c:raw_sendmsg
```
**Symbols:**

```
ffffffe0007f5f20-ffffffe0007f62b0: raw_send_hdrinc.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/raw.c (ffffffff81982b00)
Location: net/ipv4/raw.c:343
Inline: True
Direct callers:
  - net/ipv4/raw.c:raw_sendmsg
```
**Symbols:**

```
ffffffff81982b00-ffffffff81982fe9: raw_send_hdrinc.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/raw.c (ffffffff8193c5c0)
Location: net/ipv4/raw.c:343
Inline: True
Direct callers:
  - net/ipv4/raw.c:raw_sendmsg
```
**Symbols:**

```
ffffffff8193c5c0-ffffffff8193caa9: raw_send_hdrinc.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/raw.c (ffffffff819ed2d0)
Location: net/ipv4/raw.c:343
Inline: True
Direct callers:
  - net/ipv4/raw.c:raw_sendmsg
```
**Symbols:**

```
ffffffff819ed2d0-ffffffff819ed7b9: raw_send_hdrinc.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/raw.c (ffffffff819f71b0)
Location: net/ipv4/raw.c:343
Inline: True
Direct callers:
  - net/ipv4/raw.c:raw_sendmsg
```
**Symbols:**

```
ffffffff819f71b0-ffffffff819f76ac: raw_send_hdrinc.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
