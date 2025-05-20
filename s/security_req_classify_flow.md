# Function: <code>security_req_classify_flow</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void security_req_classify_flow(const struct request_sock *req, struct flowi *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8133ba30)
Location: security/security.c:1316
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff8133ba30-ffffffff8133ba70: security_req_classify_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void security_req_classify_flow(const struct request_sock *req, struct flowi *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81370ff0)
Location: security/security.c:1346
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff81370ff0-ffffffff81371030: security_req_classify_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void security_req_classify_flow(const struct request_sock *req, struct flowi *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81387920)
Location: security/security.c:1367
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff81387920-ffffffff81387960: security_req_classify_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void security_req_classify_flow(const struct request_sock *req, struct flowi *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8139c5c0)
Location: security/security.c:2316
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff8139c5c0-ffffffff8139c600: security_req_classify_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void security_req_classify_flow(const struct request_sock *req, struct flowi *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813c1d50)
Location: security/security.c:2177
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff813c1d50-ffffffff813c1d96: security_req_classify_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void security_req_classify_flow(const struct request_sock *req, struct flowi *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813f3300)
Location: security/security.c:1477
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff813f3300-ffffffff813f333e: security_req_classify_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void security_req_classify_flow(const struct request_sock *req, struct flowi *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8140e6d0)
Location: security/security.c:2237
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff8140e6d0-ffffffff8140e70e: security_req_classify_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void security_req_classify_flow(const struct request_sock *req, struct flowi *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143b280)
Location: security/security.c:2256
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff8143b280-ffffffff8143b2c0: security_req_classify_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void security_req_classify_flow(const struct request_sock *req, struct flowi *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81455020)
Location: security/security.c:2295
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff81455020-ffffffff8145505e: security_req_classify_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void security_req_classify_flow(const struct request_sock *req, struct flowi *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814a7880)
Location: security/security.c:2618
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff814a7880-ffffffff814a78be: security_req_classify_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void security_req_classify_flow(const struct request_sock *req, struct flowi_common *flic);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814c4e00)
Location: security/security.c:2635
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff814c4e00-ffffffff814c4e3e: security_req_classify_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void security_req_classify_flow(const struct request_sock *req, struct flowi_common *flic);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814cb2f0)
Location: security/security.c:2698
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff814cb2f0-ffffffff814cb32e: security_req_classify_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void security_req_classify_flow(const struct request_sock *req, struct flowi_common *flic);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81523ff0)
Location: security/security.c:2706
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff81523ff0-ffffffff8152402e: security_req_classify_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void security_req_classify_flow(const struct request_sock *req, struct flowi_common *flic);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815b7e90)
Location: security/security.c:2740
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff815b7e90-ffffffff815b7ed8: security_req_classify_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void security_req_classify_flow(const struct request_sock *req, struct flowi_common *flic);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81663310)
Location: security/security.c:2720
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff81663310-ffffffff81663358: security_req_classify_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void security_req_classify_flow(const struct request_sock *req, struct flowi_common *flic);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8169b810)
Location: security/security.c:4735
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff8169b810-ffffffff8169b858: security_req_classify_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void security_req_classify_flow(const struct request_sock *req, struct flowi_common *flic);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816d84b0)
Location: security/security.c:4926
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff816d84b0-ffffffff816d84f8: security_req_classify_flow (STB_GLOBAL)
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
void security_req_classify_flow(const struct request_sock *req, struct flowi *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffff800010540350)
Location: security/security.c:2295
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffff800010540350-ffff8000105403a8: security_req_classify_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void security_req_classify_flow(const struct request_sock *req, struct flowi *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c06f63d0)
Location: security/security.c:2295
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
c06f63d0-c06f6420: security_req_classify_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void security_req_classify_flow(const struct request_sock *req, struct flowi *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c000000000691bf0)
Location: security/security.c:2295
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
c000000000691bf0-c000000000691c80: security_req_classify_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void security_req_classify_flow(const struct request_sock *req, struct flowi *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffe00039d4f0)
Location: security/security.c:2295
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffe00039d4f0-ffffffe00039d530: security_req_classify_flow (STB_GLOBAL)
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
void security_req_classify_flow(const struct request_sock *req, struct flowi *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144d600)
Location: security/security.c:2295
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff8144d600-ffffffff8144d63e: security_req_classify_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void security_req_classify_flow(const struct request_sock *req, struct flowi *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143e050)
Location: security/security.c:2295
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff8143e050-ffffffff8143e08e: security_req_classify_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void security_req_classify_flow(const struct request_sock *req, struct flowi *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814496a0)
Location: security/security.c:2295
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff814496a0-ffffffff814496de: security_req_classify_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void security_req_classify_flow(const struct request_sock *req, struct flowi *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81460a70)
Location: security/security.c:2295
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/inet6_connection_sock.c:inet6_csk_route_req
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff81460a70-ffffffff81460aae: security_req_classify_flow (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct flowi_common *flic</code>
</li>
<li>
<b>Param removed. </b>
<code>struct flowi *fl</code>
</li>
</ul>
</details>
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
