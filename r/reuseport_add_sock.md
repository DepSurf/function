# Function: <code>reuseport_add_sock</code>

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
int reuseport_add_sock(struct sock *sk, struct sock *sk2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff817a0340)
Location: net/core/sock_reuseport.c:96
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
ffffffff817a0340-ffffffff817a04b5: reuseport_add_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int reuseport_add_sock(struct sock *sk, struct sock *sk2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff817ced10)
Location: net/core/sock_reuseport.c:96
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
ffffffff817ced10-ffffffff817cee85: reuseport_add_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int reuseport_add_sock(struct sock *sk, struct sock *sk2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff817ee0b0)
Location: net/core/sock_reuseport.c:96
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
ffffffff817ee0b0-ffffffff817ee20f: reuseport_add_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int reuseport_add_sock(struct sock *sk, struct sock *sk2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff8186a2d0)
Location: net/core/sock_reuseport.c:113
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
ffffffff8186a2d0-ffffffff8186a44a: reuseport_add_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int reuseport_add_sock(struct sock *sk, struct sock *sk2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff818ba000)
Location: net/core/sock_reuseport.c:113
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
ffffffff818ba000-ffffffff818ba17e: reuseport_add_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int reuseport_add_sock(struct sock *sk, struct sock *sk2, bool bind_inany);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff818e0e20)
Location: net/core/sock_reuseport.c:149
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
ffffffff818e0e20-ffffffff818e0fbb: reuseport_add_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int reuseport_add_sock(struct sock *sk, struct sock *sk2, bool bind_inany);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff8192f5f0)
Location: net/core/sock_reuseport.c:151
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
ffffffff8192f5f0-ffffffff8192f7aa: reuseport_add_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int reuseport_add_sock(struct sock *sk, struct sock *sk2, bool bind_inany);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff81961860)
Location: net/core/sock_reuseport.c:151
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
ffffffff81961860-ffffffff81961a1a: reuseport_add_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int reuseport_add_sock(struct sock *sk, struct sock *sk2, bool bind_inany);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff81a34e90)
Location: net/core/sock_reuseport.c:140
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_reuseport_add_sock
  - net/ipv4/udp.c:udp_reuseport_add_sock
```
**Symbols:**

```
ffffffff81a34e90-ffffffff81a35051: reuseport_add_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int reuseport_add_sock(struct sock *sk, struct sock *sk2, bool bind_inany);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff81a371d0)
Location: net/core/sock_reuseport.c:140
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_reuseport_add_sock
  - net/ipv4/udp.c:udp_reuseport_add_sock
```
**Symbols:**

```
ffffffff81a371d0-ffffffff81a37391: reuseport_add_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int reuseport_add_sock(struct sock *sk, struct sock *sk2, bool bind_inany);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff81a1e330)
Location: net/core/sock_reuseport.c:140
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
ffffffff81a1e330-ffffffff81a1e4f1: reuseport_add_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int reuseport_add_sock(struct sock *sk, struct sock *sk2, bool bind_inany);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff81ad2450)
Location: net/core/sock_reuseport.c:235
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
ffffffff81ad2450-ffffffff81ad2594: reuseport_add_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int reuseport_add_sock(struct sock *sk, struct sock *sk2, bool bind_inany);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff81c4fe40)
Location: net/core/sock_reuseport.c:235
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
ffffffff81c4fe40-ffffffff81c4ffa0: reuseport_add_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int reuseport_add_sock(struct sock *sk, struct sock *sk2, bool bind_inany);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff81e050b0)
Location: net/core/sock_reuseport.c:321
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
ffffffff81e050b0-ffffffff81e05226: reuseport_add_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int reuseport_add_sock(struct sock *sk, struct sock *sk2, bool bind_inany);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff81e77900)
Location: net/core/sock_reuseport.c:321
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
ffffffff81e77900-ffffffff81e77a76: reuseport_add_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int reuseport_add_sock(struct sock *sk, struct sock *sk2, bool bind_inany);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff81f378c0)
Location: net/core/sock_reuseport.c:321
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
ffffffff81f378c0-ffffffff81f37a36: reuseport_add_sock (STB_GLOBAL)
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
int reuseport_add_sock(struct sock *sk, struct sock *sk2, bool bind_inany);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffff800010c05368)
Location: net/core/sock_reuseport.c:151
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
ffff800010c05368-ffff800010c055f4: reuseport_add_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int reuseport_add_sock(struct sock *sk, struct sock *sk2, bool bind_inany);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (c0d1e604)
Location: net/core/sock_reuseport.c:151
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
c0d1e604-c0d1e7c0: reuseport_add_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int reuseport_add_sock(struct sock *sk, struct sock *sk2, bool bind_inany);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (c000000000cef500)
Location: net/core/sock_reuseport.c:151
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
c000000000cef500-c000000000cef7ac: reuseport_add_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int reuseport_add_sock(struct sock *sk, struct sock *sk2, bool bind_inany);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffe000783ce4)
Location: net/core/sock_reuseport.c:151
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
ffffffe000783ce4-ffffffe000783e8c: reuseport_add_sock (STB_GLOBAL)
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
int reuseport_add_sock(struct sock *sk, struct sock *sk2, bool bind_inany);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff81901830)
Location: net/core/sock_reuseport.c:151
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
ffffffff81901830-ffffffff819019ea: reuseport_add_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int reuseport_add_sock(struct sock *sk, struct sock *sk2, bool bind_inany);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff818bb660)
Location: net/core/sock_reuseport.c:151
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
ffffffff818bb660-ffffffff818bb81a: reuseport_add_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int reuseport_add_sock(struct sock *sk, struct sock *sk2, bool bind_inany);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff81952860)
Location: net/core/sock_reuseport.c:151
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
ffffffff81952860-ffffffff81952a1a: reuseport_add_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int reuseport_add_sock(struct sock *sk, struct sock *sk2, bool bind_inany);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff819742d0)
Location: net/core/sock_reuseport.c:151
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
ffffffff819742d0-ffffffff8197448a: reuseport_add_sock (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool bind_inany</code>
</li>
</ul>
</details>
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
