# Function: <code>reuseport_detach_sock</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void reuseport_detach_sock(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff8179fef0)
Location: net/core/sock_reuseport.c:144
Inline: False
Direct callers:
  - net/core/sock.c:__sk_destruct
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_lib_unhash
```
**Symbols:**

```
ffffffff8179fef0-ffffffff8179ff8e: reuseport_detach_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void reuseport_detach_sock(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff817ce8c0)
Location: net/core/sock_reuseport.c:143
Inline: False
Direct callers:
  - net/core/sock.c:__sk_destruct
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_lib_unhash
```
**Symbols:**

```
ffffffff817ce8c0-ffffffff817ce95e: reuseport_detach_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void reuseport_detach_sock(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff817edd60)
Location: net/core/sock_reuseport.c:143
Inline: False
Direct callers:
  - net/core/sock.c:__sk_destruct
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/udp.c:udp_lib_rehash
```
**Symbols:**

```
ffffffff817edd60-ffffffff817eddfe: reuseport_detach_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void reuseport_detach_sock(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff81869fa0)
Location: net/core/sock_reuseport.c:155
Inline: False
Direct callers:
  - net/core/sock.c:__sk_destruct
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/udp.c:udp_lib_rehash
```
**Symbols:**

```
ffffffff81869fa0-ffffffff8186a03e: reuseport_detach_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void reuseport_detach_sock(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff818b9c80)
Location: net/core/sock_reuseport.c:155
Inline: False
Direct callers:
  - net/core/sock.c:__sk_destruct
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/udp.c:udp_lib_rehash
```
**Symbols:**

```
ffffffff818b9c80-ffffffff818b9d1e: reuseport_detach_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void reuseport_detach_sock(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff818e0a20)
Location: net/core/sock_reuseport.c:192
Inline: False
Direct callers:
  - net/core/sock.c:__sk_destruct
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/udp.c:udp_lib_rehash
```
**Symbols:**

```
ffffffff818e0a20-ffffffff818e0ad4: reuseport_detach_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void reuseport_detach_sock(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff8192f0d0)
Location: net/core/sock_reuseport.c:194
Inline: False
Direct callers:
  - net/core/sock.c:__sk_destruct
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/udp.c:udp_lib_rehash
```
**Symbols:**

```
ffffffff8192f0d0-ffffffff8192f172: reuseport_detach_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void reuseport_detach_sock(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff81961340)
Location: net/core/sock_reuseport.c:194
Inline: False
Direct callers:
  - net/core/sock.c:sk_destruct
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/udp.c:udp_lib_rehash
```
**Symbols:**

```
ffffffff81961340-ffffffff819613e2: reuseport_detach_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void reuseport_detach_sock(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff81a34900)
Location: net/core/sock_reuseport.c:183
Inline: False
Direct callers:
  - net/core/sock.c:__sk_free
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/udp.c:udp_lib_rehash
```
**Symbols:**

```
ffffffff81a34900-ffffffff81a34997: reuseport_detach_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void reuseport_detach_sock(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff81a36c40)
Location: net/core/sock_reuseport.c:183
Inline: False
Direct callers:
  - net/core/sock.c:__sk_free
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/udp.c:udp_lib_rehash
```
**Symbols:**

```
ffffffff81a36c40-ffffffff81a36cd7: reuseport_detach_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void reuseport_detach_sock(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff81a1ddd0)
Location: net/core/sock_reuseport.c:183
Inline: False
Direct callers:
  - net/core/sock.c:__sk_free
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/udp.c:udp_lib_rehash
```
**Symbols:**

```
ffffffff81a1ddd0-ffffffff81a1de67: reuseport_detach_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void reuseport_detach_sock(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff81ad1d70)
Location: net/core/sock_reuseport.c:342
Inline: False
Direct callers:
  - net/core/sock.c:__sk_free
  - net/core/sock_reuseport.c:reuseport_stop_listen_sock
  - net/ipv4/udp.c:udp_lib_rehash
```
**Symbols:**

```
ffffffff81ad1d70-ffffffff81ad1e62: reuseport_detach_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void reuseport_detach_sock(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff81c4f750)
Location: net/core/sock_reuseport.c:342
Inline: False
Direct callers:
  - net/core/sock.c:__sk_free
  - net/core/sock_reuseport.c:reuseport_stop_listen_sock
  - net/ipv4/udp.c:udp_lib_rehash
```
**Symbols:**

```
ffffffff81c4f750-ffffffff81c4f843: reuseport_detach_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void reuseport_detach_sock(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff81e04bd0)
Location: net/core/sock_reuseport.c:428
Inline: False
Direct callers:
  - net/core/sock.c:sk_destruct
  - net/core/sock_reuseport.c:reuseport_stop_listen_sock
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_lib_unhash
```
**Symbols:**

```
ffffffff81e04bd0-ffffffff81e04c74: reuseport_detach_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void reuseport_detach_sock(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff81e77420)
Location: net/core/sock_reuseport.c:428
Inline: False
Direct callers:
  - net/core/sock.c:sk_destruct
  - net/core/sock_reuseport.c:reuseport_stop_listen_sock
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_lib_unhash
```
**Symbols:**

```
ffffffff81e77420-ffffffff81e774c4: reuseport_detach_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void reuseport_detach_sock(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff81f373e0)
Location: net/core/sock_reuseport.c:428
Inline: False
Direct callers:
  - net/core/sock.c:sk_destruct
  - net/core/sock_reuseport.c:reuseport_stop_listen_sock
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_lib_unhash
```
**Symbols:**

```
ffffffff81f373e0-ffffffff81f37484: reuseport_detach_sock (STB_GLOBAL)
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
void reuseport_detach_sock(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffff800010c05138)
Location: net/core/sock_reuseport.c:194
Inline: False
Direct callers:
  - net/core/sock.c:sk_destruct
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/udp.c:udp_lib_rehash
```
**Symbols:**

```
ffff800010c05138-ffff800010c05268: reuseport_detach_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void reuseport_detach_sock(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (c0d1e064)
Location: net/core/sock_reuseport.c:194
Inline: False
Direct callers:
  - net/core/sock.c:sk_destruct
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_lib_rehash
```
**Symbols:**

```
c0d1e064-c0d1e120: reuseport_detach_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void reuseport_detach_sock(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (c000000000ceecc0)
Location: net/core/sock_reuseport.c:194
Inline: False
Direct callers:
  - net/core/sock.c:sk_destruct
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/udp.c:udp_lib_rehash
```
**Symbols:**

```
c000000000ceecc0-c000000000ceee0c: reuseport_detach_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void reuseport_detach_sock(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffe000783828)
Location: net/core/sock_reuseport.c:194
Inline: False
Direct callers:
  - net/core/sock.c:sk_destruct
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/udp.c:udp_lib_rehash
```
**Symbols:**

```
ffffffe000783828-ffffffe0007838da: reuseport_detach_sock (STB_GLOBAL)
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
void reuseport_detach_sock(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff81901310)
Location: net/core/sock_reuseport.c:194
Inline: False
Direct callers:
  - net/core/sock.c:sk_destruct
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/udp.c:udp_lib_rehash
```
**Symbols:**

```
ffffffff81901310-ffffffff819013b2: reuseport_detach_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void reuseport_detach_sock(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff818bb140)
Location: net/core/sock_reuseport.c:194
Inline: False
Direct callers:
  - net/core/sock.c:sk_destruct
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/udp.c:udp_lib_rehash
```
**Symbols:**

```
ffffffff818bb140-ffffffff818bb1e2: reuseport_detach_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void reuseport_detach_sock(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff81952340)
Location: net/core/sock_reuseport.c:194
Inline: False
Direct callers:
  - net/core/sock.c:sk_destruct
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/udp.c:udp_lib_rehash
```
**Symbols:**

```
ffffffff81952340-ffffffff819523e2: reuseport_detach_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void reuseport_detach_sock(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff81973d80)
Location: net/core/sock_reuseport.c:194
Inline: False
Direct callers:
  - net/core/sock.c:sk_destruct
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/udp.c:udp_lib_rehash
```
**Symbols:**

```
ffffffff81973d80-ffffffff81973e22: reuseport_detach_sock (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
