# Function: <code>reuseport_alloc</code>

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
int reuseport_alloc(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff817a0280)
Location: net/core/sock_reuseport.c:31
Inline: False
Direct callers:
  - net/core/filter.c:__reuseport_attach_prog
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
ffffffff817a0280-ffffffff817a0335: reuseport_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int reuseport_alloc(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff817cec50)
Location: net/core/sock_reuseport.c:31
Inline: False
Direct callers:
  - net/core/filter.c:__reuseport_attach_prog
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
ffffffff817cec50-ffffffff817ced05: reuseport_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int reuseport_alloc(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff817ee000)
Location: net/core/sock_reuseport.c:31
Inline: False
Direct callers:
  - net/core/filter.c:__reuseport_attach_prog
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
ffffffff817ee000-ffffffff817ee0a7: reuseport_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int reuseport_alloc(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff8186a240)
Location: net/core/sock_reuseport.c:32
Inline: False
Direct callers:
  - net/core/filter.c:__reuseport_attach_prog
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
ffffffff8186a240-ffffffff8186a2c9: reuseport_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int reuseport_alloc(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff818b9f70)
Location: net/core/sock_reuseport.c:32
Inline: False
Direct callers:
  - net/core/filter.c:__reuseport_attach_prog
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
ffffffff818b9f70-ffffffff818b9ff9: reuseport_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int reuseport_alloc(struct sock *sk, bool bind_inany);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff818e0cf0)
Location: net/core/sock_reuseport.c:55
Inline: False
Direct callers:
  - net/core/sock_reuseport.c:reuseport_attach_prog
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
ffffffff818e0cf0-ffffffff818e0d91: reuseport_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int reuseport_alloc(struct sock *sk, bool bind_inany);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff8192f4b0)
Location: net/core/sock_reuseport.c:55
Inline: False
Direct callers:
  - net/core/sock_reuseport.c:reuseport_attach_prog
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
ffffffff8192f4b0-ffffffff8192f563: reuseport_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int reuseport_alloc(struct sock *sk, bool bind_inany);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff81961720)
Location: net/core/sock_reuseport.c:55
Inline: False
Direct callers:
  - net/core/sock_reuseport.c:reuseport_attach_prog
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
ffffffff81961720-ffffffff819617d3: reuseport_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int reuseport_alloc(struct sock *sk, bool bind_inany);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff81a34d40)
Location: net/core/sock_reuseport.c:36
Inline: False
Direct callers:
  - net/core/sock_reuseport.c:reuseport_attach_prog
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/ipv4/inet_hashtables.c:inet_reuseport_add_sock
  - net/ipv4/udp.c:udp_reuseport_add_sock
```
**Symbols:**

```
ffffffff81a34d40-ffffffff81a34e0c: reuseport_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int reuseport_alloc(struct sock *sk, bool bind_inany);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff81a37080)
Location: net/core/sock_reuseport.c:36
Inline: False
Direct callers:
  - net/core/sock_reuseport.c:reuseport_attach_prog
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/ipv4/inet_hashtables.c:inet_reuseport_add_sock
  - net/ipv4/udp.c:udp_reuseport_add_sock
```
**Symbols:**

```
ffffffff81a37080-ffffffff81a3714c: reuseport_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int reuseport_alloc(struct sock *sk, bool bind_inany);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff81a1e1e0)
Location: net/core/sock_reuseport.c:36
Inline: False
Direct callers:
  - net/core/sock_reuseport.c:reuseport_attach_prog
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
ffffffff81a1e1e0-ffffffff81a1e2ac: reuseport_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int reuseport_alloc(struct sock *sk, bool bind_inany);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff81ad22e0)
Location: net/core/sock_reuseport.c:105
Inline: False
Direct callers:
  - net/core/sock_reuseport.c:reuseport_attach_prog
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
ffffffff81ad22e0-ffffffff81ad23c8: reuseport_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int reuseport_alloc(struct sock *sk, bool bind_inany);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff81c4fcc0)
Location: net/core/sock_reuseport.c:105
Inline: False
Direct callers:
  - net/core/sock_reuseport.c:reuseport_attach_prog
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
ffffffff81c4fcc0-ffffffff81c4fdb2: reuseport_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int reuseport_alloc(struct sock *sk, bool bind_inany);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff81e04f00)
Location: net/core/sock_reuseport.c:189
Inline: False
Direct callers:
  - net/core/sock_reuseport.c:reuseport_attach_prog
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
ffffffff81e04f00-ffffffff81e05008: reuseport_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int reuseport_alloc(struct sock *sk, bool bind_inany);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff81e77750)
Location: net/core/sock_reuseport.c:189
Inline: False
Direct callers:
  - net/core/sock_reuseport.c:reuseport_attach_prog
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
ffffffff81e77750-ffffffff81e77858: reuseport_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int reuseport_alloc(struct sock *sk, bool bind_inany);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff81f37710)
Location: net/core/sock_reuseport.c:189
Inline: False
Direct callers:
  - net/core/sock_reuseport.c:reuseport_attach_prog
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
ffffffff81f37710-ffffffff81f37818: reuseport_alloc (STB_GLOBAL)
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
int reuseport_alloc(struct sock *sk, bool bind_inany);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffff800010c05000)
Location: net/core/sock_reuseport.c:55
Inline: False
Direct callers:
  - net/core/sock_reuseport.c:reuseport_attach_prog
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
ffff800010c05000-ffff800010c05134: reuseport_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int reuseport_alloc(struct sock *sk, bool bind_inany);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (c0d1e4b8)
Location: net/core/sock_reuseport.c:55
Inline: False
Direct callers:
  - net/core/sock_reuseport.c:reuseport_attach_prog
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
c0d1e4b8-c0d1e574: reuseport_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int reuseport_alloc(struct sock *sk, bool bind_inany);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (c000000000cef310)
Location: net/core/sock_reuseport.c:55
Inline: False
Direct callers:
  - net/core/sock_reuseport.c:reuseport_attach_prog
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
c000000000cef310-c000000000cef424: reuseport_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int reuseport_alloc(struct sock *sk, bool bind_inany);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffe000783b9c)
Location: net/core/sock_reuseport.c:55
Inline: False
Direct callers:
  - net/core/sock_reuseport.c:reuseport_attach_prog
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
ffffffe000783b9c-ffffffe000783c5e: reuseport_alloc (STB_GLOBAL)
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
int reuseport_alloc(struct sock *sk, bool bind_inany);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff819016f0)
Location: net/core/sock_reuseport.c:55
Inline: False
Direct callers:
  - net/core/sock_reuseport.c:reuseport_attach_prog
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
ffffffff819016f0-ffffffff819017a3: reuseport_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int reuseport_alloc(struct sock *sk, bool bind_inany);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff818bb520)
Location: net/core/sock_reuseport.c:55
Inline: False
Direct callers:
  - net/core/sock_reuseport.c:reuseport_attach_prog
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
ffffffff818bb520-ffffffff818bb5d3: reuseport_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int reuseport_alloc(struct sock *sk, bool bind_inany);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff81952720)
Location: net/core/sock_reuseport.c:55
Inline: False
Direct callers:
  - net/core/sock_reuseport.c:reuseport_attach_prog
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
ffffffff81952720-ffffffff819527d3: reuseport_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int reuseport_alloc(struct sock *sk, bool bind_inany);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff81974190)
Location: net/core/sock_reuseport.c:55
Inline: False
Direct callers:
  - net/core/sock_reuseport.c:reuseport_attach_prog
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
ffffffff81974190-ffffffff81974243: reuseport_alloc (STB_GLOBAL)
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
