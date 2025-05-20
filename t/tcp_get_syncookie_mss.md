# Function: <code>tcp_get_syncookie_mss</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
u16 tcp_get_syncookie_mss(struct request_sock_ops *rsk_ops, const struct tcp_request_sock_ops *af_ops, struct sock *sk, struct tcphdr *th);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819c53a0)
Location: net/ipv4/tcp_input.c:6526
Inline: True
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_get_syncookie
  - net/ipv6/tcp_ipv6.c:tcp_v6_get_syncookie
```
**Symbols:**

```
ffffffff819c53a0-ffffffff819c54a3: tcp_get_syncookie_mss (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
u16 tcp_get_syncookie_mss(struct request_sock_ops *rsk_ops, const struct tcp_request_sock_ops *af_ops, struct sock *sk, struct tcphdr *th);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81ab1a29)
Location: net/ipv4/tcp_input.c:6585
Inline: True
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_get_syncookie
  - net/ipv6/tcp_ipv6.c:tcp_v6_get_syncookie
```
**Symbols:**

```
ffffffff81abacce-ffffffff81abace6: tcp_get_syncookie_mss.cold (STB_LOCAL)
ffffffff81ab1970-ffffffff81ab1aac: tcp_get_syncookie_mss (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
u16 tcp_get_syncookie_mss(struct request_sock_ops *rsk_ops, const struct tcp_request_sock_ops *af_ops, struct sock *sk, struct tcphdr *th);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81abc9e9)
Location: net/ipv4/tcp_input.c:6735
Inline: True
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_get_syncookie
  - net/ipv6/tcp_ipv6.c:tcp_v6_get_syncookie
```
**Symbols:**

```
ffffffff81c326a6-ffffffff81c326be: tcp_get_syncookie_mss.cold (STB_LOCAL)
ffffffff81abc930-ffffffff81abca6c: tcp_get_syncookie_mss (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
u16 tcp_get_syncookie_mss(struct request_sock_ops *rsk_ops, const struct tcp_request_sock_ops *af_ops, struct sock *sk, struct tcphdr *th);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81aa66e0)
Location: net/ipv4/tcp_input.c:6744
Inline: True
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_get_syncookie
  - net/ipv6/tcp_ipv6.c:tcp_v6_get_syncookie
```
**Symbols:**

```
ffffffff81aa66e0-ffffffff81aa67e5: tcp_get_syncookie_mss (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
u16 tcp_get_syncookie_mss(struct request_sock_ops *rsk_ops, const struct tcp_request_sock_ops *af_ops, struct sock *sk, struct tcphdr *th);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81b62ad0)
Location: net/ipv4/tcp_input.c:6779
Inline: True
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_get_syncookie
  - net/ipv6/tcp_ipv6.c:tcp_v6_get_syncookie
```
**Symbols:**

```
ffffffff81b62ad0-ffffffff81b62bd5: tcp_get_syncookie_mss (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u16 tcp_get_syncookie_mss(struct request_sock_ops *rsk_ops, const struct tcp_request_sock_ops *af_ops, struct sock *sk, struct tcphdr *th);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81cf10f0)
Location: net/ipv4/tcp_input.c:6865
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_get_syncookie
  - net/ipv6/tcp_ipv6.c:tcp_v6_get_syncookie
```
**Symbols:**

```
ffffffff81cf10f0-ffffffff81cf121b: tcp_get_syncookie_mss (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u16 tcp_get_syncookie_mss(struct request_sock_ops *rsk_ops, const struct tcp_request_sock_ops *af_ops, struct sock *sk, struct tcphdr *th);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81eb52e0)
Location: net/ipv4/tcp_input.c:6895
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_get_syncookie
  - net/ipv6/tcp_ipv6.c:tcp_v6_get_syncookie
```
**Symbols:**

```
ffffffff81eb52e0-ffffffff81eb5388: tcp_get_syncookie_mss (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u16 tcp_get_syncookie_mss(struct request_sock_ops *rsk_ops, const struct tcp_request_sock_ops *af_ops, struct sock *sk, struct tcphdr *th);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81f13710)
Location: net/ipv4/tcp_input.c:6902
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_get_syncookie
  - net/ipv6/tcp_ipv6.c:tcp_v6_get_syncookie
```
**Symbols:**

```
ffffffff81f13710-ffffffff81f137b8: tcp_get_syncookie_mss (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u16 tcp_get_syncookie_mss(struct request_sock_ops *rsk_ops, const struct tcp_request_sock_ops *af_ops, struct sock *sk, struct tcphdr *th);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81fd7bf0)
Location: net/ipv4/tcp_input.c:7062
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_get_syncookie
  - net/ipv6/tcp_ipv6.c:tcp_v6_get_syncookie
```
**Symbols:**

```
ffffffff81fd7bf0-ffffffff81fd7c98: tcp_get_syncookie_mss (STB_GLOBAL)
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
u16 tcp_get_syncookie_mss(struct request_sock_ops *rsk_ops, const struct tcp_request_sock_ops *af_ops, struct sock *sk, struct tcphdr *th);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffff800010c79380)
Location: net/ipv4/tcp_input.c:6526
Inline: True
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_get_syncookie
  - net/ipv6/tcp_ipv6.c:tcp_v6_get_syncookie
```
**Symbols:**

```
ffff800010c79380-ffff800010c794d4: tcp_get_syncookie_mss (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
u16 tcp_get_syncookie_mss(struct request_sock_ops *rsk_ops, const struct tcp_request_sock_ops *af_ops, struct sock *sk, struct tcphdr *th);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (c0d86e4c)
Location: net/ipv4/tcp_input.c:6526
Inline: True
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_get_syncookie
  - net/ipv6/tcp_ipv6.c:tcp_v6_get_syncookie
```
**Symbols:**

```
c0d86e4c-c0d86f98: tcp_get_syncookie_mss (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
u16 tcp_get_syncookie_mss(struct request_sock_ops *rsk_ops, const struct tcp_request_sock_ops *af_ops, struct sock *sk, struct tcphdr *th);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (c000000000d80710)
Location: net/ipv4/tcp_input.c:6526
Inline: True
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_get_syncookie
  - net/ipv6/tcp_ipv6.c:tcp_v6_get_syncookie
```
**Symbols:**

```
c000000000d80710-c000000000d80920: tcp_get_syncookie_mss (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
u16 tcp_get_syncookie_mss(struct request_sock_ops *rsk_ops, const struct tcp_request_sock_ops *af_ops, struct sock *sk, struct tcphdr *th);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffe0007db070)
Location: net/ipv4/tcp_input.c:6526
Inline: True
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_get_syncookie
  - net/ipv6/tcp_ipv6.c:tcp_v6_get_syncookie
```
**Symbols:**

```
ffffffe0007db070-ffffffe0007db1ae: tcp_get_syncookie_mss (STB_GLOBAL)
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
u16 tcp_get_syncookie_mss(struct request_sock_ops *rsk_ops, const struct tcp_request_sock_ops *af_ops, struct sock *sk, struct tcphdr *th);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81965210)
Location: net/ipv4/tcp_input.c:6526
Inline: True
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_get_syncookie
  - net/ipv6/tcp_ipv6.c:tcp_v6_get_syncookie
```
**Symbols:**

```
ffffffff81965210-ffffffff81965313: tcp_get_syncookie_mss (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
u16 tcp_get_syncookie_mss(struct request_sock_ops *rsk_ops, const struct tcp_request_sock_ops *af_ops, struct sock *sk, struct tcphdr *th);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8191ed00)
Location: net/ipv4/tcp_input.c:6526
Inline: True
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_get_syncookie
  - net/ipv6/tcp_ipv6.c:tcp_v6_get_syncookie
```
**Symbols:**

```
ffffffff8191ed00-ffffffff8191ee03: tcp_get_syncookie_mss (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
u16 tcp_get_syncookie_mss(struct request_sock_ops *rsk_ops, const struct tcp_request_sock_ops *af_ops, struct sock *sk, struct tcphdr *th);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819cf9e0)
Location: net/ipv4/tcp_input.c:6526
Inline: True
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_get_syncookie
  - net/ipv6/tcp_ipv6.c:tcp_v6_get_syncookie
```
**Symbols:**

```
ffffffff819cf9e0-ffffffff819cfae3: tcp_get_syncookie_mss (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
u16 tcp_get_syncookie_mss(struct request_sock_ops *rsk_ops, const struct tcp_request_sock_ops *af_ops, struct sock *sk, struct tcphdr *th);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819d9570)
Location: net/ipv4/tcp_input.c:6526
Inline: True
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_get_syncookie
  - net/ipv6/tcp_ipv6.c:tcp_v6_get_syncookie
```
**Symbols:**

```
ffffffff819d9570-ffffffff819d9673: tcp_get_syncookie_mss (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
