# Function: <code>inet_bind_bucket_create</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct inet_bind_bucket *inet_bind_bucket_create(struct kmem_cache *cachep, struct net *net, struct inet_bind_hashbucket *head, const short unsigned int snum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff817629f0)
Location: net/ipv4/inet_hashtables.c:61
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
**Symbols:**

```
ffffffff817629f0-ffffffff81762a5d: inet_bind_bucket_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct inet_bind_bucket *inet_bind_bucket_create(struct kmem_cache *cachep, struct net *net, struct inet_bind_hashbucket *head, const short unsigned int snum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff817cec70)
Location: net/ipv4/inet_hashtables.c:63
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
**Symbols:**

```
ffffffff817cec70-ffffffff817cecdd: inet_bind_bucket_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct inet_bind_bucket *inet_bind_bucket_create(struct kmem_cache *cachep, struct net *net, struct inet_bind_hashbucket *head, const short unsigned int snum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff817fea80)
Location: net/ipv4/inet_hashtables.c:64
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
**Symbols:**

```
ffffffff817fea80-ffffffff817feaed: inet_bind_bucket_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct inet_bind_bucket *inet_bind_bucket_create(struct kmem_cache *cachep, struct net *net, struct inet_bind_hashbucket *head, const short unsigned int snum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff8181ed60)
Location: net/ipv4/inet_hashtables.c:64
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
**Symbols:**

```
ffffffff8181ed60-ffffffff8181edc4: inet_bind_bucket_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct inet_bind_bucket *inet_bind_bucket_create(struct kmem_cache *cachep, struct net *net, struct inet_bind_hashbucket *head, const short unsigned int snum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff8189dd10)
Location: net/ipv4/inet_hashtables.c:64
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
**Symbols:**

```
ffffffff8189dd10-ffffffff8189dd74: inet_bind_bucket_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct inet_bind_bucket *inet_bind_bucket_create(struct kmem_cache *cachep, struct net *net, struct inet_bind_hashbucket *head, const short unsigned int snum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff818f26d0)
Location: net/ipv4/inet_hashtables.c:65
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
**Symbols:**

```
ffffffff818f26d0-ffffffff818f2734: inet_bind_bucket_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct inet_bind_bucket *inet_bind_bucket_create(struct kmem_cache *cachep, struct net *net, struct inet_bind_hashbucket *head, const short unsigned int snum, int l3mdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff819200d0)
Location: net/ipv4/inet_hashtables.c:65
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
**Symbols:**

```
ffffffff819200d0-ffffffff8192013f: inet_bind_bucket_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct inet_bind_bucket *inet_bind_bucket_create(struct kmem_cache *cachep, struct net *net, struct inet_bind_hashbucket *head, const short unsigned int snum, int l3mdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff819829f0)
Location: net/ipv4/inet_hashtables.c:61
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
**Symbols:**

```
ffffffff819829f0-ffffffff81982a5d: inet_bind_bucket_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct inet_bind_bucket *inet_bind_bucket_create(struct kmem_cache *cachep, struct net *net, struct inet_bind_hashbucket *head, const short unsigned int snum, int l3mdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff819b9250)
Location: net/ipv4/inet_hashtables.c:61
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
**Symbols:**

```
ffffffff819b9250-ffffffff819b92bd: inet_bind_bucket_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct inet_bind_bucket *inet_bind_bucket_create(struct kmem_cache *cachep, struct net *net, struct inet_bind_hashbucket *head, const short unsigned int snum, int l3mdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81aa4715)
Location: net/ipv4/inet_hashtables.c:61
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
**Symbols:**

```
ffffffff81aa3f30-ffffffff81aa3f9d: inet_bind_bucket_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct inet_bind_bucket *inet_bind_bucket_create(struct kmem_cache *cachep, struct net *net, struct inet_bind_hashbucket *head, const short unsigned int snum, int l3mdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81aaed65)
Location: net/ipv4/inet_hashtables.c:64
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
**Symbols:**

```
ffffffff81aae560-ffffffff81aae5cd: inet_bind_bucket_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct inet_bind_bucket *inet_bind_bucket_create(struct kmem_cache *cachep, struct net *net, struct inet_bind_hashbucket *head, const short unsigned int snum, int l3mdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81a9a000)
Location: net/ipv4/inet_hashtables.c:64
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
**Symbols:**

```
ffffffff81a99640-ffffffff81a996ad: inet_bind_bucket_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct inet_bind_bucket *inet_bind_bucket_create(struct kmem_cache *cachep, struct net *net, struct inet_bind_hashbucket *head, const short unsigned int snum, int l3mdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81b55470)
Location: net/ipv4/inet_hashtables.c:64
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
**Symbols:**

```
ffffffff81b54ac0-ffffffff81b54b2d: inet_bind_bucket_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct inet_bind_bucket *inet_bind_bucket_create(struct kmem_cache *cachep, struct net *net, struct inet_bind_hashbucket *head, const short unsigned int snum, int l3mdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81ce2fb0)
Location: net/ipv4/inet_hashtables.c:64
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
**Symbols:**

```
ffffffff81ce2660-ffffffff81ce26e1: inet_bind_bucket_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct inet_bind_bucket *inet_bind_bucket_create(struct kmem_cache *cachep, struct net *net, struct inet_bind_hashbucket *head, const short unsigned int snum, int l3mdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81ea5349)
Location: net/ipv4/inet_hashtables.c:64
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
**Symbols:**

```
ffffffff81ea38d0-ffffffff81ea3951: inet_bind_bucket_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct inet_bind_bucket *inet_bind_bucket_create(struct kmem_cache *cachep, struct net *net, struct inet_bind_hashbucket *head, const short unsigned int snum, int l3mdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81f03ad8)
Location: net/ipv4/inet_hashtables.c:64
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
**Symbols:**

```
ffffffff81f02160-ffffffff81f021dc: inet_bind_bucket_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct inet_bind_bucket *inet_bind_bucket_create(struct kmem_cache *cachep, struct net *net, struct inet_bind_hashbucket *head, const short unsigned int snum, int l3mdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81fc7d83)
Location: net/ipv4/inet_hashtables.c:65
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
**Symbols:**

```
ffffffff81fc6220-ffffffff81fc629c: inet_bind_bucket_create (STB_GLOBAL)
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
struct inet_bind_bucket *inet_bind_bucket_create(struct kmem_cache *cachep, struct net *net, struct inet_bind_hashbucket *head, const short unsigned int snum, int l3mdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffff800010c6a8e0)
Location: net/ipv4/inet_hashtables.c:61
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
**Symbols:**

```
ffff800010c6a8e0-ffff800010c6a968: inet_bind_bucket_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct inet_bind_bucket *inet_bind_bucket_create(struct kmem_cache *cachep, struct net *net, struct inet_bind_hashbucket *head, const short unsigned int snum, int l3mdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (c0d799c0)
Location: net/ipv4/inet_hashtables.c:61
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
**Symbols:**

```
c0d799c0-c0d79a30: inet_bind_bucket_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct inet_bind_bucket *inet_bind_bucket_create(struct kmem_cache *cachep, struct net *net, struct inet_bind_hashbucket *head, const short unsigned int snum, int l3mdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (c000000000d6fa90)
Location: net/ipv4/inet_hashtables.c:61
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
**Symbols:**

```
c000000000d6fa90-c000000000d6fb3c: inet_bind_bucket_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct inet_bind_bucket *inet_bind_bucket_create(struct kmem_cache *cachep, struct net *net, struct inet_bind_hashbucket *head, const short unsigned int snum, int l3mdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffe0007d062c)
Location: net/ipv4/inet_hashtables.c:61
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
**Symbols:**

```
ffffffe0007d062c-ffffffe0007d069e: inet_bind_bucket_create (STB_GLOBAL)
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
struct inet_bind_bucket *inet_bind_bucket_create(struct kmem_cache *cachep, struct net *net, struct inet_bind_hashbucket *head, const short unsigned int snum, int l3mdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff819590c0)
Location: net/ipv4/inet_hashtables.c:61
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
**Symbols:**

```
ffffffff819590c0-ffffffff8195912d: inet_bind_bucket_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct inet_bind_bucket *inet_bind_bucket_create(struct kmem_cache *cachep, struct net *net, struct inet_bind_hashbucket *head, const short unsigned int snum, int l3mdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81912bb0)
Location: net/ipv4/inet_hashtables.c:61
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
**Symbols:**

```
ffffffff81912bb0-ffffffff81912c1d: inet_bind_bucket_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct inet_bind_bucket *inet_bind_bucket_create(struct kmem_cache *cachep, struct net *net, struct inet_bind_hashbucket *head, const short unsigned int snum, int l3mdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff819c3890)
Location: net/ipv4/inet_hashtables.c:61
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
**Symbols:**

```
ffffffff819c3890-ffffffff819c38fd: inet_bind_bucket_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct inet_bind_bucket *inet_bind_bucket_create(struct kmem_cache *cachep, struct net *net, struct inet_bind_hashbucket *head, const short unsigned int snum, int l3mdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff819cd2b0)
Location: net/ipv4/inet_hashtables.c:61
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
**Symbols:**

```
ffffffff819cd2b0-ffffffff819cd31d: inet_bind_bucket_create (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int l3mdev</code>
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
