# Function: <code>unix_peer_get</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct sock *unix_peer_get(struct sock *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff817bd4f0)
Location: net/unix/af_unix.c:199
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_getname
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
**Symbols:**

```
ffffffff817bd4f0-ffffffff817bd534: unix_peer_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct sock *unix_peer_get(struct sock *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff8182a460)
Location: net/unix/af_unix.c:199
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_getname
```
**Symbols:**

```
ffffffff8182a460-ffffffff8182a4a4: unix_peer_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct sock *unix_peer_get(struct sock *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff8185bed0)
Location: net/unix/af_unix.c:199
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_getname
```
**Symbols:**

```
ffffffff8185bed0-ffffffff8185bf14: unix_peer_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct sock *unix_peer_get(struct sock *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff818805b0)
Location: net/unix/af_unix.c:200
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_getname
```
**Symbols:**

```
ffffffff818805b0-ffffffff818805f4: unix_peer_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct sock *unix_peer_get(struct sock *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81901740)
Location: net/unix/af_unix.c:200
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_getname
```
**Symbols:**

```
ffffffff81901740-ffffffff8190178a: unix_peer_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct sock *unix_peer_get(struct sock *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81959530)
Location: net/unix/af_unix.c:200
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_getname
```
**Symbols:**

```
ffffffff81959530-ffffffff8195957a: unix_peer_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct sock *unix_peer_get(struct sock *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff8198e250)
Location: net/unix/af_unix.c:200
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_getname
```
**Symbols:**

```
ffffffff8198e250-ffffffff8198e29a: unix_peer_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct sock *unix_peer_get(struct sock *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff819f98d0)
Location: net/unix/af_unix.c:197
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_getname
```
**Symbols:**

```
ffffffff819f98d0-ffffffff819f991a: unix_peer_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct sock *unix_peer_get(struct sock *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81a30470)
Location: net/unix/af_unix.c:197
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_getname
```
**Symbols:**

```
ffffffff81a30470-ffffffff81a304ba: unix_peer_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct sock *unix_peer_get(struct sock *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81b28976)
Location: net/unix/af_unix.c:203
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_getname
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
```
**Symbols:**

```
ffffffff81b24200-ffffffff81b24279: unix_peer_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct sock *unix_peer_get(struct sock *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81b36bb2)
Location: net/unix/af_unix.c:203
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_getname
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
```
**Symbols:**

```
ffffffff81b32b90-ffffffff81b32c09: unix_peer_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct sock *unix_peer_get(struct sock *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81b24767)
Location: net/unix/af_unix.c:203
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_getname
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
```
**Symbols:**

```
ffffffff81b20940-ffffffff81b209b9: unix_peer_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct sock *unix_peer_get(struct sock *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81be97a7)
Location: net/unix/af_unix.c:204
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_getname
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
```
**Symbols:**

```
ffffffff81be5820-ffffffff81be5899: unix_peer_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct sock *unix_peer_get(struct sock *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81d82292)
Location: net/unix/af_unix.c:231
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_getname
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
```
**Symbols:**

```
ffffffff81d7dc70-ffffffff81d7dceb: unix_peer_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct sock *unix_peer_get(struct sock *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81f4f7d5)
Location: net/unix/af_unix.c:237
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_getname
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
```
**Symbols:**

```
ffffffff81f4aef0-ffffffff81f4af6b: unix_peer_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct sock *unix_peer_get(struct sock *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81faf0cb)
Location: net/unix/af_unix.c:238
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_getname
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
```
**Symbols:**

```
ffffffff81faaba0-ffffffff81faac1b: unix_peer_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct sock *unix_peer_get(struct sock *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff8207c63e)
Location: net/unix/af_unix.c:237
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_getname
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
```
**Symbols:**

```
ffffffff82077f90-ffffffff8207800b: unix_peer_get (STB_GLOBAL)
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
struct sock *unix_peer_get(struct sock *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffff800010cefaa0)
Location: net/unix/af_unix.c:197
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_getname
```
**Symbols:**

```
ffff800010cefaa0-ffff800010cefb30: unix_peer_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct sock *unix_peer_get(struct sock *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (c0df6b18)
Location: net/unix/af_unix.c:197
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_getname
```
**Symbols:**

```
c0df6b18-c0df6b70: unix_peer_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct sock *unix_peer_get(struct sock *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (c000000000e154d0)
Location: net/unix/af_unix.c:197
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_getname
```
**Symbols:**

```
c000000000e154d0-c000000000e15598: unix_peer_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct sock *unix_peer_get(struct sock *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffe00083c600)
Location: net/unix/af_unix.c:197
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_getname
```
**Symbols:**

```
ffffffe00083c600-ffffffe00083c67c: unix_peer_get (STB_GLOBAL)
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
struct sock *unix_peer_get(struct sock *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff819cfb00)
Location: net/unix/af_unix.c:197
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_getname
```
**Symbols:**

```
ffffffff819cfb00-ffffffff819cfb4a: unix_peer_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct sock *unix_peer_get(struct sock *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff8198c8c0)
Location: net/unix/af_unix.c:197
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_getname
```
**Symbols:**

```
ffffffff8198c8c0-ffffffff8198c90a: unix_peer_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct sock *unix_peer_get(struct sock *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81a3a580)
Location: net/unix/af_unix.c:197
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_getname
```
**Symbols:**

```
ffffffff81a3a580-ffffffff81a3a5ca: unix_peer_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct sock *unix_peer_get(struct sock *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81a452c0)
Location: net/unix/af_unix.c:197
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_getname
```
**Symbols:**

```
ffffffff81a452c0-ffffffff81a4530d: unix_peer_get (STB_GLOBAL)
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
