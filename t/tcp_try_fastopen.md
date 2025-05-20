# Function: <code>tcp_try_fastopen</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct sock *tcp_try_fastopen(struct sock *sk, struct sk_buff *skb, struct request_sock *req, struct tcp_fastopen_cookie *foc, struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff817828a0)
Location: net/ipv4/tcp_fastopen.c:256
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
**Symbols:**

```
ffffffff817828a0-ffffffff81782ebe: tcp_try_fastopen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct sock *tcp_try_fastopen(struct sock *sk, struct sk_buff *skb, struct request_sock *req, struct tcp_fastopen_cookie *foc, struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff817eff50)
Location: net/ipv4/tcp_fastopen.c:277
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
**Symbols:**

```
ffffffff817eff50-ffffffff817f044d: tcp_try_fastopen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct sock *tcp_try_fastopen(struct sock *sk, struct sk_buff *skb, struct request_sock *req, struct tcp_fastopen_cookie *foc, struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff81820960)
Location: net/ipv4/tcp_fastopen.c:278
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
**Symbols:**

```
ffffffff81820960-ffffffff81820e9b: tcp_try_fastopen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct sock *tcp_try_fastopen(struct sock *sk, struct sk_buff *skb, struct request_sock *req, struct tcp_fastopen_cookie *foc, struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff81840e70)
Location: net/ipv4/tcp_fastopen.c:279
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
**Symbols:**

```
ffffffff81840e70-ffffffff818413df: tcp_try_fastopen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct sock *tcp_try_fastopen(struct sock *sk, struct sk_buff *skb, struct request_sock *req, struct tcp_fastopen_cookie *foc, const struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff818c06c0)
Location: net/ipv4/tcp_fastopen.c:325
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
**Symbols:**

```
ffffffff818c06c0-ffffffff818c0bf8: tcp_try_fastopen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct sock *tcp_try_fastopen(struct sock *sk, struct sk_buff *skb, struct request_sock *req, struct tcp_fastopen_cookie *foc, const struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff81916200)
Location: net/ipv4/tcp_fastopen.c:325
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
**Symbols:**

```
ffffffff81916200-ffffffff8191672a: tcp_try_fastopen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct sock *tcp_try_fastopen(struct sock *sk, struct sk_buff *skb, struct request_sock *req, struct tcp_fastopen_cookie *foc, const struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff819449a0)
Location: net/ipv4/tcp_fastopen.c:325
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
**Symbols:**

```
ffffffff819449a0-ffffffff81944eca: tcp_try_fastopen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct sock *tcp_try_fastopen(struct sock *sk, struct sk_buff *skb, struct request_sock *req, struct tcp_fastopen_cookie *foc, const struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff819a8fe0)
Location: net/ipv4/tcp_fastopen.c:338
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
**Symbols:**

```
ffffffff819a8fe0-ffffffff819a94ff: tcp_try_fastopen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct sock *tcp_try_fastopen(struct sock *sk, struct sk_buff *skb, struct request_sock *req, struct tcp_fastopen_cookie *foc, const struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff819dfc40)
Location: net/ipv4/tcp_fastopen.c:338
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
**Symbols:**

```
ffffffff819dfc40-ffffffff819e0194: tcp_try_fastopen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct sock *tcp_try_fastopen(struct sock *sk, struct sk_buff *skb, struct request_sock *req, struct tcp_fastopen_cookie *foc, const struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff81acd580)
Location: net/ipv4/tcp_fastopen.c:361
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
**Symbols:**

```
ffffffff81acd580-ffffffff81acd78e: tcp_try_fastopen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct sock *tcp_try_fastopen(struct sock *sk, struct sk_buff *skb, struct request_sock *req, struct tcp_fastopen_cookie *foc, const struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff81ad95b0)
Location: net/ipv4/tcp_fastopen.c:361
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
**Symbols:**

```
ffffffff81ad95b0-ffffffff81ad97c3: tcp_try_fastopen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct sock *tcp_try_fastopen(struct sock *sk, struct sk_buff *skb, struct request_sock *req, struct tcp_fastopen_cookie *foc, const struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff81ac42a0)
Location: net/ipv4/tcp_fastopen.c:361
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
**Symbols:**

```
ffffffff81ac42a0-ffffffff81ac4823: tcp_try_fastopen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct sock *tcp_try_fastopen(struct sock *sk, struct sk_buff *skb, struct request_sock *req, struct tcp_fastopen_cookie *foc, const struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_fastopen.c (0)
Location: net/ipv4/tcp_fastopen.c:350
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
**Symbols:**

```
ffffffff81d3be43-ffffffff81d3be75: tcp_try_fastopen.cold (STB_LOCAL)
ffffffff81b82970-ffffffff81b82f6c: tcp_try_fastopen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct sock *tcp_try_fastopen(struct sock *sk, struct sk_buff *skb, struct request_sock *req, struct tcp_fastopen_cookie *foc, const struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_fastopen.c (0)
Location: net/ipv4/tcp_fastopen.c:344
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
**Symbols:**

```
ffffffff81f08660-ffffffff81f08692: tcp_try_fastopen.cold (STB_LOCAL)
ffffffff81d12f30-ffffffff81d1351a: tcp_try_fastopen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct sock *tcp_try_fastopen(struct sock *sk, struct sk_buff *skb, struct request_sock *req, struct tcp_fastopen_cookie *foc, const struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_fastopen.c (0)
Location: net/ipv4/tcp_fastopen.c:345
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
**Symbols:**

```
ffffffff820b0141-ffffffff820b0173: tcp_try_fastopen.cold (STB_LOCAL)
ffffffff81ed8ea0-ffffffff81ed948a: tcp_try_fastopen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct sock *tcp_try_fastopen(struct sock *sk, struct sk_buff *skb, struct request_sock *req, struct tcp_fastopen_cookie *foc, const struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_fastopen.c (0)
Location: net/ipv4/tcp_fastopen.c:347
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
**Symbols:**

```
ffffffff821313cb-ffffffff821313ff: tcp_try_fastopen.cold (STB_LOCAL)
ffffffff81f37fb0-ffffffff81f3856b: tcp_try_fastopen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct sock *tcp_try_fastopen(struct sock *sk, struct sk_buff *skb, struct request_sock *req, struct tcp_fastopen_cookie *foc, const struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_fastopen.c (0)
Location: net/ipv4/tcp_fastopen.c:347
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
**Symbols:**

```
ffffffff82212d0f-ffffffff82212d43: tcp_try_fastopen.cold (STB_LOCAL)
ffffffff81ffe070-ffffffff81ffe62b: tcp_try_fastopen (STB_GLOBAL)
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
struct sock *tcp_try_fastopen(struct sock *sk, struct sk_buff *skb, struct request_sock *req, struct tcp_fastopen_cookie *foc, const struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffff800010c937f8)
Location: net/ipv4/tcp_fastopen.c:338
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
**Symbols:**

```
ffff800010c937f8-ffff800010c93d70: tcp_try_fastopen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct sock *tcp_try_fastopen(struct sock *sk, struct sk_buff *skb, struct request_sock *req, struct tcp_fastopen_cookie *foc, const struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (c0da2088)
Location: net/ipv4/tcp_fastopen.c:338
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
**Symbols:**

```
c0da2088-c0da25ec: tcp_try_fastopen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct sock *tcp_try_fastopen(struct sock *sk, struct sk_buff *skb, struct request_sock *req, struct tcp_fastopen_cookie *foc, const struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (c000000000da3c50)
Location: net/ipv4/tcp_fastopen.c:338
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
**Symbols:**

```
c000000000da3c50-c000000000da4334: tcp_try_fastopen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct sock *tcp_try_fastopen(struct sock *sk, struct sk_buff *skb, struct request_sock *req, struct tcp_fastopen_cookie *foc, const struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffe0007f2e60)
Location: net/ipv4/tcp_fastopen.c:338
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
**Symbols:**

```
ffffffe0007f2e60-ffffffe0007f333c: tcp_try_fastopen (STB_GLOBAL)
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
struct sock *tcp_try_fastopen(struct sock *sk, struct sk_buff *skb, struct request_sock *req, struct tcp_fastopen_cookie *foc, const struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff8197fab0)
Location: net/ipv4/tcp_fastopen.c:338
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
**Symbols:**

```
ffffffff8197fab0-ffffffff81980004: tcp_try_fastopen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct sock *tcp_try_fastopen(struct sock *sk, struct sk_buff *skb, struct request_sock *req, struct tcp_fastopen_cookie *foc, const struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff81939570)
Location: net/ipv4/tcp_fastopen.c:338
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
**Symbols:**

```
ffffffff81939570-ffffffff81939ac4: tcp_try_fastopen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct sock *tcp_try_fastopen(struct sock *sk, struct sk_buff *skb, struct request_sock *req, struct tcp_fastopen_cookie *foc, const struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff819ea280)
Location: net/ipv4/tcp_fastopen.c:338
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
**Symbols:**

```
ffffffff819ea280-ffffffff819ea7d4: tcp_try_fastopen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct sock *tcp_try_fastopen(struct sock *sk, struct sk_buff *skb, struct request_sock *req, struct tcp_fastopen_cookie *foc, const struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff819f40c0)
Location: net/ipv4/tcp_fastopen.c:338
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
**Symbols:**

```
ffffffff819f40c0-ffffffff819f4642: tcp_try_fastopen (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct dst_entry *dst</code> ➡️ <code>const struct dst_entry *dst</code>
</li>
</ul>
</details>
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
