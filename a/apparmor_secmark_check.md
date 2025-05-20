# Function: <code>apparmor_secmark_check</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int apparmor_secmark_check(struct aa_label *label, char *op, u32 request, u32 secid, struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff8150f4e0)
Location: security/apparmor/net.c:312
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_inet_conn_request
  - security/apparmor/lsm.c:apparmor_socket_sock_rcv_skb
```
**Symbols:**

```
ffffffff8150f4e0-ffffffff8150f75e: apparmor_secmark_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int apparmor_secmark_check(struct aa_label *label, char *op, u32 request, u32 secid, const struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff8152c320)
Location: security/apparmor/net.c:314
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_inet_conn_request
  - security/apparmor/lsm.c:apparmor_socket_sock_rcv_skb
```
**Symbols:**

```
ffffffff8152c320-ffffffff8152c59e: apparmor_secmark_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int apparmor_secmark_check(struct aa_label *label, char *op, u32 request, u32 secid, const struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff815325c0)
Location: security/apparmor/net.c:314
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_inet_conn_request
  - security/apparmor/lsm.c:apparmor_socket_sock_rcv_skb
```
**Symbols:**

```
ffffffff815325c0-ffffffff815328da: apparmor_secmark_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int apparmor_secmark_check(struct aa_label *label, char *op, u32 request, u32 secid, const struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff81590b40)
Location: security/apparmor/net.c:314
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_inet_conn_request
  - security/apparmor/lsm.c:apparmor_socket_sock_rcv_skb
```
**Symbols:**

```
ffffffff81590b40-ffffffff81590e5a: apparmor_secmark_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int apparmor_secmark_check(struct aa_label *label, char *op, u32 request, u32 secid, const struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff81631d00)
Location: security/apparmor/net.c:317
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_ip_postroute
  - security/apparmor/lsm.c:apparmor_inet_conn_request
  - security/apparmor/lsm.c:apparmor_socket_sock_rcv_skb
```
**Symbols:**

```
ffffffff81631d00-ffffffff8163206f: apparmor_secmark_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int apparmor_secmark_check(struct aa_label *label, char *op, u32 request, u32 secid, const struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff816e6aa0)
Location: security/apparmor/net.c:323
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_ip_postroute
  - security/apparmor/lsm.c:apparmor_inet_conn_request
  - security/apparmor/lsm.c:apparmor_socket_sock_rcv_skb
```
**Symbols:**

```
ffffffff816e6aa0-ffffffff816e6df1: apparmor_secmark_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int apparmor_secmark_check(struct aa_label *label, char *op, u32 request, u32 secid, const struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff81720200)
Location: security/apparmor/net.c:323
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_ip_postroute
  - security/apparmor/lsm.c:apparmor_inet_conn_request
  - security/apparmor/lsm.c:apparmor_socket_sock_rcv_skb
```
**Symbols:**

```
ffffffff81720200-ffffffff8172053a: apparmor_secmark_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int apparmor_secmark_check(struct aa_label *label, char *op, u32 request, u32 secid, const struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff8175ec80)
Location: security/apparmor/net.c:326
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_ip_postroute
  - security/apparmor/lsm.c:apparmor_inet_conn_request
  - security/apparmor/lsm.c:apparmor_socket_sock_rcv_skb
```
**Symbols:**

```
ffffffff8175ec80-ffffffff8175efba: apparmor_secmark_check (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct sock *sk</code> ➡️ <code>const struct sock *sk</code>
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
