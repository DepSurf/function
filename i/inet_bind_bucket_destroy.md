# Function: <code>inet_bind_bucket_destroy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void inet_bind_bucket_destroy(struct kmem_cache *cachep, struct inet_bind_bucket *tb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81762477)
Location: net/ipv4/inet_hashtables.c:83
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_put_port
Direct callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_bind_unhash
```
**Symbols:**

```
ffffffff81762ba0-ffffffff81762bcc: inet_bind_bucket_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void inet_bind_bucket_destroy(struct kmem_cache *cachep, struct inet_bind_bucket *tb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff817ce817)
Location: net/ipv4/inet_hashtables.c:85
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_put_port
Direct callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_bind_unhash
```
**Symbols:**

```
ffffffff817cee10-ffffffff817cee3e: inet_bind_bucket_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void inet_bind_bucket_destroy(struct kmem_cache *cachep, struct inet_bind_bucket *tb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff817fe627)
Location: net/ipv4/inet_hashtables.c:86
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_put_port
Direct callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_bind_unhash
```
**Symbols:**

```
ffffffff817fec20-ffffffff817fec4e: inet_bind_bucket_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void inet_bind_bucket_destroy(struct kmem_cache *cachep, struct inet_bind_bucket *tb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff8181ec63)
Location: net/ipv4/inet_hashtables.c:85
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_put_port
Direct callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_bind_unhash
```
**Symbols:**

```
ffffffff8181ef10-ffffffff8181ef3f: inet_bind_bucket_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void inet_bind_bucket_destroy(struct kmem_cache *cachep, struct inet_bind_bucket *tb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff8189dc13)
Location: net/ipv4/inet_hashtables.c:85
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_put_port
Direct callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_bind_unhash
```
**Symbols:**

```
ffffffff8189dec0-ffffffff8189deef: inet_bind_bucket_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void inet_bind_bucket_destroy(struct kmem_cache *cachep, struct inet_bind_bucket *tb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff818f1dc3)
Location: net/ipv4/inet_hashtables.c:86
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_put_port
Direct callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_bind_unhash
```
**Symbols:**

```
ffffffff818f2870-ffffffff818f289e: inet_bind_bucket_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void inet_bind_bucket_destroy(struct kmem_cache *cachep, struct inet_bind_bucket *tb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff8191f953)
Location: net/ipv4/inet_hashtables.c:88
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_put_port
  - net/ipv4/inet_hashtables.c:inet_put_port
Direct callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_bind_unhash
```
**Symbols:**

```
ffffffff819202e0-ffffffff8192030e: inet_bind_bucket_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void inet_bind_bucket_destroy(struct kmem_cache *cachep, struct inet_bind_bucket *tb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff8198226d)
Location: net/ipv4/inet_hashtables.c:84
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_put_port
  - net/ipv4/inet_hashtables.c:inet_put_port
Direct callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_bind_unhash
```
**Symbols:**

```
ffffffff81982c00-ffffffff81982c2e: inet_bind_bucket_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void inet_bind_bucket_destroy(struct kmem_cache *cachep, struct inet_bind_bucket *tb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff819b8ad0)
Location: net/ipv4/inet_hashtables.c:84
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_put_port
  - net/ipv4/inet_hashtables.c:inet_put_port
Direct callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_bind_unhash
```
**Symbols:**

```
ffffffff819b9460-ffffffff819b948e: inet_bind_bucket_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void inet_bind_bucket_destroy(struct kmem_cache *cachep, struct inet_bind_bucket *tb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81aa3725)
Location: net/ipv4/inet_hashtables.c:84
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_put_port
  - net/ipv4/inet_hashtables.c:__inet_put_port
Direct callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_bind_unhash
```
**Symbols:**

```
ffffffff81aa3fa0-ffffffff81aa3fce: inet_bind_bucket_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void inet_bind_bucket_destroy(struct kmem_cache *cachep, struct inet_bind_bucket *tb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81aadd65)
Location: net/ipv4/inet_hashtables.c:87
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_put_port
  - net/ipv4/inet_hashtables.c:__inet_put_port
Direct callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_bind_unhash
```
**Symbols:**

```
ffffffff81aae5d0-ffffffff81aae5fe: inet_bind_bucket_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void inet_bind_bucket_destroy(struct kmem_cache *cachep, struct inet_bind_bucket *tb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81a98fc0)
Location: net/ipv4/inet_hashtables.c:87
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_put_port
  - net/ipv4/inet_hashtables.c:inet_put_port
Direct callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_bind_unhash
```
**Symbols:**

```
ffffffff81a996b0-ffffffff81a996de: inet_bind_bucket_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void inet_bind_bucket_destroy(struct kmem_cache *cachep, struct inet_bind_bucket *tb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81b54440)
Location: net/ipv4/inet_hashtables.c:87
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_put_port
  - net/ipv4/inet_hashtables.c:inet_put_port
Direct callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_bind_unhash
```
**Symbols:**

```
ffffffff81b54b30-ffffffff81b54b5e: inet_bind_bucket_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void inet_bind_bucket_destroy(struct kmem_cache *cachep, struct inet_bind_bucket *tb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81ce12e3)
Location: net/ipv4/inet_hashtables.c:87
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_put_port
  - net/ipv4/inet_hashtables.c:inet_put_port
Direct callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_bind_unhash
```
**Symbols:**

```
ffffffff81ce26f0-ffffffff81ce2736: inet_bind_bucket_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void inet_bind_bucket_destroy(struct kmem_cache *cachep, struct inet_bind_bucket *tb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81ea580a)
Location: net/ipv4/inet_hashtables.c:87
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:inet_put_port
  - net/ipv4/inet_hashtables.c:inet_put_port
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_timewait_sock.c:inet_twsk_bind_unhash
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
**Symbols:**

```
ffffffff81ea22f0-ffffffff81ea2320: inet_bind_bucket_destroy.part.0 (STB_LOCAL)
ffffffff81ea3970-ffffffff81ea39b6: inet_bind_bucket_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void inet_bind_bucket_destroy(struct kmem_cache *cachep, struct inet_bind_bucket *tb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81f03f91)
Location: net/ipv4/inet_hashtables.c:87
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:inet_put_port
  - net/ipv4/inet_hashtables.c:inet_put_port
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_timewait_sock.c:inet_twsk_bind_unhash
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
**Symbols:**

```
ffffffff81f00b10-ffffffff81f00b40: inet_bind_bucket_destroy.part.0 (STB_LOCAL)
ffffffff81f021f0-ffffffff81f02236: inet_bind_bucket_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void inet_bind_bucket_destroy(struct kmem_cache *cachep, struct inet_bind_bucket *tb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81fc8154)
Location: net/ipv4/inet_hashtables.c:88
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:inet_put_port
  - net/ipv4/inet_hashtables.c:inet_put_port
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_timewait_sock.c:inet_twsk_bind_unhash
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
**Symbols:**

```
ffffffff81fc4f90-ffffffff81fc4fc0: inet_bind_bucket_destroy.part.0 (STB_LOCAL)
ffffffff81fc62b0-ffffffff81fc62f6: inet_bind_bucket_destroy (STB_GLOBAL)
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
void inet_bind_bucket_destroy(struct kmem_cache *cachep, struct inet_bind_bucket *tb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffff800010c6a164)
Location: net/ipv4/inet_hashtables.c:84
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_put_port
  - net/ipv4/inet_hashtables.c:inet_put_port
Direct callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_bind_unhash
```
**Symbols:**

```
ffff800010c6ab20-ffff800010c6ab6c: inet_bind_bucket_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void inet_bind_bucket_destroy(struct kmem_cache *cachep, struct inet_bind_bucket *tb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (c0d78c04)
Location: net/ipv4/inet_hashtables.c:84
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_put_port
  - net/ipv4/inet_hashtables.c:inet_put_port
Direct callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_bind_unhash
```
**Symbols:**

```
c0d79bf4-c0d79c30: inet_bind_bucket_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void inet_bind_bucket_destroy(struct kmem_cache *cachep, struct inet_bind_bucket *tb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (c000000000d6e914)
Location: net/ipv4/inet_hashtables.c:84
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_put_port
  - net/ipv4/inet_hashtables.c:inet_put_port
Direct callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_bind_unhash
```
**Symbols:**

```
c000000000d6fe00-c000000000d6fe58: inet_bind_bucket_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void inet_bind_bucket_destroy(struct kmem_cache *cachep, struct inet_bind_bucket *tb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffe0007cfd16)
Location: net/ipv4/inet_hashtables.c:84
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_put_port
  - net/ipv4/inet_hashtables.c:inet_put_port
Direct callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_bind_unhash
```
**Symbols:**

```
ffffffe0007d087c-ffffffe0007d08bc: inet_bind_bucket_destroy (STB_GLOBAL)
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
void inet_bind_bucket_destroy(struct kmem_cache *cachep, struct inet_bind_bucket *tb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81958940)
Location: net/ipv4/inet_hashtables.c:84
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_put_port
  - net/ipv4/inet_hashtables.c:inet_put_port
Direct callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_bind_unhash
```
**Symbols:**

```
ffffffff819592d0-ffffffff819592fe: inet_bind_bucket_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void inet_bind_bucket_destroy(struct kmem_cache *cachep, struct inet_bind_bucket *tb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81912430)
Location: net/ipv4/inet_hashtables.c:84
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_put_port
  - net/ipv4/inet_hashtables.c:inet_put_port
Direct callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_bind_unhash
```
**Symbols:**

```
ffffffff81912dc0-ffffffff81912dee: inet_bind_bucket_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void inet_bind_bucket_destroy(struct kmem_cache *cachep, struct inet_bind_bucket *tb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff819c3110)
Location: net/ipv4/inet_hashtables.c:84
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_put_port
  - net/ipv4/inet_hashtables.c:inet_put_port
Direct callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_bind_unhash
```
**Symbols:**

```
ffffffff819c3aa0-ffffffff819c3ace: inet_bind_bucket_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void inet_bind_bucket_destroy(struct kmem_cache *cachep, struct inet_bind_bucket *tb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff819cc620)
Location: net/ipv4/inet_hashtables.c:84
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_put_port
  - net/ipv4/inet_hashtables.c:inet_put_port
Direct callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_bind_unhash
```
**Symbols:**

```
ffffffff819cd4f0-ffffffff819cd51e: inet_bind_bucket_destroy (STB_GLOBAL)
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
