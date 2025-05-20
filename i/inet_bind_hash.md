# Function: <code>inet_bind_hash</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void inet_bind_hash(struct sock *sk, struct inet_bind_bucket *tb, const short unsigned int snum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81762b03)
Location: net/ipv4/inet_hashtables.c:91
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
**Symbols:**

```
ffffffff81762bd0-ffffffff81762c0b: inet_bind_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void inet_bind_hash(struct sock *sk, struct inet_bind_bucket *tb, const short unsigned int snum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff817cf5a1)
Location: net/ipv4/inet_hashtables.c:93
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
**Symbols:**

```
ffffffff817cee40-ffffffff817cee7b: inet_bind_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void inet_bind_hash(struct sock *sk, struct inet_bind_bucket *tb, const short unsigned int snum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff817ff391)
Location: net/ipv4/inet_hashtables.c:94
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
**Symbols:**

```
ffffffff817fec50-ffffffff817fec8b: inet_bind_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void inet_bind_hash(struct sock *sk, struct inet_bind_bucket *tb, const short unsigned int snum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff8181f5df)
Location: net/ipv4/inet_hashtables.c:93
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
**Symbols:**

```
ffffffff8181ef40-ffffffff8181ef77: inet_bind_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void inet_bind_hash(struct sock *sk, struct inet_bind_bucket *tb, const short unsigned int snum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff8189e542)
Location: net/ipv4/inet_hashtables.c:93
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
**Symbols:**

```
ffffffff8189def0-ffffffff8189df27: inet_bind_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void inet_bind_hash(struct sock *sk, struct inet_bind_bucket *tb, const short unsigned int snum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff818f3084)
Location: net/ipv4/inet_hashtables.c:94
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
**Symbols:**

```
ffffffff818f28a0-ffffffff818f28d7: inet_bind_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void inet_bind_hash(struct sock *sk, struct inet_bind_bucket *tb, const short unsigned int snum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81920ab5)
Location: net/ipv4/inet_hashtables.c:96
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
**Symbols:**

```
ffffffff81920310-ffffffff81920347: inet_bind_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void inet_bind_hash(struct sock *sk, struct inet_bind_bucket *tb, const short unsigned int snum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff8198335d)
Location: net/ipv4/inet_hashtables.c:92
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
**Symbols:**

```
ffffffff81982c30-ffffffff81982c67: inet_bind_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void inet_bind_hash(struct sock *sk, struct inet_bind_bucket *tb, const short unsigned int snum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff819b9bd0)
Location: net/ipv4/inet_hashtables.c:92
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
**Symbols:**

```
ffffffff819b9490-ffffffff819b94c7: inet_bind_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void inet_bind_hash(struct sock *sk, struct inet_bind_bucket *tb, const short unsigned int snum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81aa478e)
Location: net/ipv4/inet_hashtables.c:92
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
**Symbols:**

```
ffffffff81aa3fd0-ffffffff81aa4007: inet_bind_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void inet_bind_hash(struct sock *sk, struct inet_bind_bucket *tb, const short unsigned int snum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81aaedde)
Location: net/ipv4/inet_hashtables.c:95
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
**Symbols:**

```
ffffffff81aae600-ffffffff81aae637: inet_bind_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void inet_bind_hash(struct sock *sk, struct inet_bind_bucket *tb, const short unsigned int snum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81a9a08f)
Location: net/ipv4/inet_hashtables.c:95
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
**Symbols:**

```
ffffffff81a996e0-ffffffff81a99717: inet_bind_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void inet_bind_hash(struct sock *sk, struct inet_bind_bucket *tb, const short unsigned int snum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81b55500)
Location: net/ipv4/inet_hashtables.c:95
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
**Symbols:**

```
ffffffff81b54b60-ffffffff81b54b97: inet_bind_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void inet_bind_hash(struct sock *sk, struct inet_bind_bucket *tb, const short unsigned int snum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81ce304e)
Location: net/ipv4/inet_hashtables.c:95
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
**Symbols:**

```
ffffffff81ce2740-ffffffff81ce2783: inet_bind_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void inet_bind_hash(struct sock *sk, struct inet_bind_bucket *tb, struct inet_bind2_bucket *tb2, short unsigned int port);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81ea54b3)
Location: net/ipv4/inet_hashtables.c:161
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
**Symbols:**

```
ffffffff81ea3b50-ffffffff81ea3bc9: inet_bind_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void inet_bind_hash(struct sock *sk, struct inet_bind_bucket *tb, struct inet_bind2_bucket *tb2, short unsigned int port);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81f03c3a)
Location: net/ipv4/inet_hashtables.c:161
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
**Symbols:**

```
ffffffff81f023d0-ffffffff81f02449: inet_bind_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void inet_bind_hash(struct sock *sk, struct inet_bind_bucket *tb, struct inet_bind2_bucket *tb2, short unsigned int port);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81fc7ef1)
Location: net/ipv4/inet_hashtables.c:166
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
**Symbols:**

```
ffffffff81fc64e0-ffffffff81fc652c: inet_bind_hash (STB_GLOBAL)
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
void inet_bind_hash(struct sock *sk, struct inet_bind_bucket *tb, const short unsigned int snum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffff800010c6b470)
Location: net/ipv4/inet_hashtables.c:92
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
**Symbols:**

```
ffff800010c6ab70-ffff800010c6abcc: inet_bind_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void inet_bind_hash(struct sock *sk, struct inet_bind_bucket *tb, const short unsigned int snum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (c0d7a514)
Location: net/ipv4/inet_hashtables.c:92
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
**Symbols:**

```
c0d79c30-c0d79c70: inet_bind_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void inet_bind_hash(struct sock *sk, struct inet_bind_bucket *tb, const short unsigned int snum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (c000000000d708a4)
Location: net/ipv4/inet_hashtables.c:92
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
**Symbols:**

```
c000000000d6fe60-c000000000d6fe98: inet_bind_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void inet_bind_hash(struct sock *sk, struct inet_bind_bucket *tb, const short unsigned int snum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffe0007d1066)
Location: net/ipv4/inet_hashtables.c:92
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
**Symbols:**

```
ffffffe0007d08bc-ffffffe0007d0908: inet_bind_hash (STB_GLOBAL)
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
void inet_bind_hash(struct sock *sk, struct inet_bind_bucket *tb, const short unsigned int snum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81959a40)
Location: net/ipv4/inet_hashtables.c:92
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
**Symbols:**

```
ffffffff81959300-ffffffff81959337: inet_bind_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void inet_bind_hash(struct sock *sk, struct inet_bind_bucket *tb, const short unsigned int snum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81913530)
Location: net/ipv4/inet_hashtables.c:92
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
**Symbols:**

```
ffffffff81912df0-ffffffff81912e27: inet_bind_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void inet_bind_hash(struct sock *sk, struct inet_bind_bucket *tb, const short unsigned int snum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff819c4210)
Location: net/ipv4/inet_hashtables.c:92
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
**Symbols:**

```
ffffffff819c3ad0-ffffffff819c3b07: inet_bind_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void inet_bind_hash(struct sock *sk, struct inet_bind_bucket *tb, const short unsigned int snum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff819cdc82)
Location: net/ipv4/inet_hashtables.c:92
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
**Symbols:**

```
ffffffff819cd520-ffffffff819cd557: inet_bind_hash (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct inet_bind2_bucket *tb2</code>
</li>
<li>
<b>Param added. </b>
<code>short unsigned int port</code>
</li>
<li>
<b>Param removed. </b>
<code>const short unsigned int snum</code>
</li>
</ul>
</details>
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
