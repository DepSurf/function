# Function: <code>tcp_rate_check_app_limited</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void tcp_rate_check_app_limited(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_rate.c (ffffffff81821150)
Location: net/ipv4/tcp_rate.c:172
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg
```
**Symbols:**

```
ffffffff81821150-ffffffff818211bb: tcp_rate_check_app_limited (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void tcp_rate_check_app_limited(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_rate.c (ffffffff818417a0)
Location: net/ipv4/tcp_rate.c:173
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg
```
**Symbols:**

```
ffffffff818417a0-ffffffff8184180b: tcp_rate_check_app_limited (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void tcp_rate_check_app_limited(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_rate.c (ffffffff818c0fc0)
Location: net/ipv4/tcp_rate.c:177
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
**Symbols:**

```
ffffffff818c0fc0-ffffffff818c102b: tcp_rate_check_app_limited (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void tcp_rate_check_app_limited(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_rate.c (ffffffff81916b10)
Location: net/ipv4/tcp_rate.c:177
Inline: True
Direct callers:
  - kernel/bpf/sockmap.c:bpf_tcp_push
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
**Symbols:**

```
ffffffff81916b10-ffffffff81916b7b: tcp_rate_check_app_limited (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void tcp_rate_check_app_limited(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_rate.c (ffffffff819452c0)
Location: net/ipv4/tcp_rate.c:182
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
**Symbols:**

```
ffffffff819452c0-ffffffff8194532b: tcp_rate_check_app_limited (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void tcp_rate_check_app_limited(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_rate.c (ffffffff819a98c0)
Location: net/ipv4/tcp_rate.c:183
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
**Symbols:**

```
ffffffff819a98c0-ffffffff819a992b: tcp_rate_check_app_limited (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void tcp_rate_check_app_limited(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_rate.c (ffffffff819e0580)
Location: net/ipv4/tcp_rate.c:183
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
**Symbols:**

```
ffffffff819e0580-ffffffff819e05eb: tcp_rate_check_app_limited (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void tcp_rate_check_app_limited(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_rate.c (ffffffff81acdb50)
Location: net/ipv4/tcp_rate.c:183
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/xfrm/espintcp.c:espintcp_sendmsg
```
**Symbols:**

```
ffffffff81acdb50-ffffffff81acdbbb: tcp_rate_check_app_limited (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void tcp_rate_check_app_limited(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_rate.c (ffffffff81ad9bb0)
Location: net/ipv4/tcp_rate.c:183
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/xfrm/espintcp.c:espintcp_sendmsg
```
**Symbols:**

```
ffffffff81ad9bb0-ffffffff81ad9c1b: tcp_rate_check_app_limited (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void tcp_rate_check_app_limited(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_rate.c (ffffffff81ac4c00)
Location: net/ipv4/tcp_rate.c:183
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/xfrm/espintcp.c:espintcp_sendmsg
```
**Symbols:**

```
ffffffff81ac4c00-ffffffff81ac4c6b: tcp_rate_check_app_limited (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void tcp_rate_check_app_limited(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_rate.c (ffffffff81b833b0)
Location: net/ipv4/tcp_rate.c:183
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/xfrm/espintcp.c:espintcp_sendmsg
```
**Symbols:**

```
ffffffff81b833b0-ffffffff81b8341b: tcp_rate_check_app_limited (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void tcp_rate_check_app_limited(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_rate.c (ffffffff81d139c0)
Location: net/ipv4/tcp_rate.c:194
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/xfrm/espintcp.c:espintcp_sendmsg
```
**Symbols:**

```
ffffffff81d139c0-ffffffff81d13a37: tcp_rate_check_app_limited (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void tcp_rate_check_app_limited(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_rate.c (ffffffff81ed99a0)
Location: net/ipv4/tcp_rate.c:194
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/xfrm/espintcp.c:espintcp_sendmsg
```
**Symbols:**

```
ffffffff81ed99a0-ffffffff81ed9a17: tcp_rate_check_app_limited (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void tcp_rate_check_app_limited(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_rate.c (ffffffff81f38a80)
Location: net/ipv4/tcp_rate.c:194
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/xfrm/espintcp.c:espintcp_sendmsg
```
**Symbols:**

```
ffffffff81f38a80-ffffffff81f38af7: tcp_rate_check_app_limited (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void tcp_rate_check_app_limited(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_rate.c (ffffffff81ffeb60)
Location: net/ipv4/tcp_rate.c:194
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/xfrm/espintcp.c:espintcp_sendmsg
```
**Symbols:**

```
ffffffff81ffeb60-ffffffff81ffebd7: tcp_rate_check_app_limited (STB_GLOBAL)
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
void tcp_rate_check_app_limited(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_rate.c (ffff800010c94290)
Location: net/ipv4/tcp_rate.c:183
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
**Symbols:**

```
ffff800010c94290-ffff800010c9431c: tcp_rate_check_app_limited (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void tcp_rate_check_app_limited(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_rate.c (c0da2a20)
Location: net/ipv4/tcp_rate.c:183
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
**Symbols:**

```
c0da2a20-c0da2aa0: tcp_rate_check_app_limited (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void tcp_rate_check_app_limited(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_rate.c (c000000000da4970)
Location: net/ipv4/tcp_rate.c:183
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
**Symbols:**

```
c000000000da4970-c000000000da49f8: tcp_rate_check_app_limited (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void tcp_rate_check_app_limited(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_rate.c (ffffffe0007f378c)
Location: net/ipv4/tcp_rate.c:183
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
**Symbols:**

```
ffffffe0007f378c-ffffffe0007f3806: tcp_rate_check_app_limited (STB_GLOBAL)
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
void tcp_rate_check_app_limited(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_rate.c (ffffffff819803f0)
Location: net/ipv4/tcp_rate.c:183
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
**Symbols:**

```
ffffffff819803f0-ffffffff8198045b: tcp_rate_check_app_limited (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void tcp_rate_check_app_limited(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_rate.c (ffffffff81939eb0)
Location: net/ipv4/tcp_rate.c:183
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
**Symbols:**

```
ffffffff81939eb0-ffffffff81939f1b: tcp_rate_check_app_limited (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void tcp_rate_check_app_limited(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_rate.c (ffffffff819eabc0)
Location: net/ipv4/tcp_rate.c:183
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
**Symbols:**

```
ffffffff819eabc0-ffffffff819eac2b: tcp_rate_check_app_limited (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void tcp_rate_check_app_limited(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_rate.c (ffffffff819f4a40)
Location: net/ipv4/tcp_rate.c:183
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
**Symbols:**

```
ffffffff819f4a40-ffffffff819f4aab: tcp_rate_check_app_limited (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
