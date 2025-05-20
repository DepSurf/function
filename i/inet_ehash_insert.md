# Function: <code>inet_ehash_insert</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool inet_ehash_insert(struct sock *sk, struct sock *osk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81762c10)
Location: net/ipv4/inet_hashtables.c:410
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
```
**Symbols:**

```
ffffffff81762c10-ffffffff81762d84: inet_ehash_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool inet_ehash_insert(struct sock *sk, struct sock *osk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff817cee80)
Location: net/ipv4/inet_hashtables.c:393
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
```
**Symbols:**

```
ffffffff817cee80-ffffffff817cf057: inet_ehash_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool inet_ehash_insert(struct sock *sk, struct sock *osk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff817fec90)
Location: net/ipv4/inet_hashtables.c:395
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
```
**Symbols:**

```
ffffffff817fec90-ffffffff817fee6b: inet_ehash_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool inet_ehash_insert(struct sock *sk, struct sock *osk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff8181ef80)
Location: net/ipv4/inet_hashtables.c:392
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
```
**Symbols:**

```
ffffffff8181ef80-ffffffff8181f10b: inet_ehash_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool inet_ehash_insert(struct sock *sk, struct sock *osk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff8189df30)
Location: net/ipv4/inet_hashtables.c:399
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
```
**Symbols:**

```
ffffffff8189df30-ffffffff8189e07a: inet_ehash_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool inet_ehash_insert(struct sock *sk, struct sock *osk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff818f28e0)
Location: net/ipv4/inet_hashtables.c:513
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
```
**Symbols:**

```
ffffffff818f28e0-ffffffff818f2a2f: inet_ehash_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool inet_ehash_insert(struct sock *sk, struct sock *osk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81920350)
Location: net/ipv4/inet_hashtables.c:477
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
```
**Symbols:**

```
ffffffff81920350-ffffffff8192049f: inet_ehash_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
bool inet_ehash_insert(struct sock *sk, struct sock *osk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/inet_hashtables.c (0)
Location: net/ipv4/inet_hashtables.c:473
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
```
**Symbols:**

```
ffffffff81983654-ffffffff81983667: inet_ehash_insert.cold (STB_LOCAL)
ffffffff81982c70-ffffffff81982dc4: inet_ehash_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool inet_ehash_insert(struct sock *sk, struct sock *osk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff819b94d0)
Location: net/ipv4/inet_hashtables.c:473
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
```
**Symbols:**

```
ffffffff819b94d0-ffffffff819b962a: inet_ehash_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool inet_ehash_insert(struct sock *sk, struct sock *osk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81aa4010)
Location: net/ipv4/inet_hashtables.c:474
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
```
**Symbols:**

```
ffffffff81aa4010-ffffffff81aa417f: inet_ehash_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool inet_ehash_insert(struct sock *sk, struct sock *osk, bool *found_dup_sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81aae640)
Location: net/ipv4/inet_hashtables.c:559
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
```
**Symbols:**

```
ffffffff81aae640-ffffffff81aae7b8: inet_ehash_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool inet_ehash_insert(struct sock *sk, struct sock *osk, bool *found_dup_sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81a99720)
Location: net/ipv4/inet_hashtables.c:559
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
```
**Symbols:**

```
ffffffff81a99720-ffffffff81a99933: inet_ehash_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool inet_ehash_insert(struct sock *sk, struct sock *osk, bool *found_dup_sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81b54ba0)
Location: net/ipv4/inet_hashtables.c:561
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
```
**Symbols:**

```
ffffffff81b54ba0-ffffffff81b54db3: inet_ehash_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool inet_ehash_insert(struct sock *sk, struct sock *osk, bool *found_dup_sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81ce2790)
Location: net/ipv4/inet_hashtables.c:519
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
```
**Symbols:**

```
ffffffff81ce2790-ffffffff81ce29f5: inet_ehash_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool inet_ehash_insert(struct sock *sk, struct sock *osk, bool *found_dup_sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81ea3be0)
Location: net/ipv4/inet_hashtables.c:635
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
```
**Symbols:**

```
ffffffff81ea3be0-ffffffff81ea3eb4: inet_ehash_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool inet_ehash_insert(struct sock *sk, struct sock *osk, bool *found_dup_sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81f02460)
Location: net/ipv4/inet_hashtables.c:635
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
```
**Symbols:**

```
ffffffff81f02460-ffffffff81f026f7: inet_ehash_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool inet_ehash_insert(struct sock *sk, struct sock *osk, bool *found_dup_sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81fc6820)
Location: net/ipv4/inet_hashtables.c:656
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
```
**Symbols:**

```
ffffffff81fc6820-ffffffff81fc6ab7: inet_ehash_insert (STB_GLOBAL)
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
bool inet_ehash_insert(struct sock *sk, struct sock *osk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffff800010c6abd0)
Location: net/ipv4/inet_hashtables.c:473
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
```
**Symbols:**

```
ffff800010c6abd0-ffff800010c6ad58: inet_ehash_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool inet_ehash_insert(struct sock *sk, struct sock *osk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (c0d79c70)
Location: net/ipv4/inet_hashtables.c:473
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
```
**Symbols:**

```
c0d79c70-c0d79e48: inet_ehash_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool inet_ehash_insert(struct sock *sk, struct sock *osk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (c000000000d6fea0)
Location: net/ipv4/inet_hashtables.c:473
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
```
**Symbols:**

```
c000000000d6fea0-c000000000d700b8: inet_ehash_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool inet_ehash_insert(struct sock *sk, struct sock *osk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffe0007d0908)
Location: net/ipv4/inet_hashtables.c:473
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
```
**Symbols:**

```
ffffffe0007d0908-ffffffe0007d0a78: inet_ehash_insert (STB_GLOBAL)
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
bool inet_ehash_insert(struct sock *sk, struct sock *osk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81959340)
Location: net/ipv4/inet_hashtables.c:473
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
```
**Symbols:**

```
ffffffff81959340-ffffffff8195949a: inet_ehash_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool inet_ehash_insert(struct sock *sk, struct sock *osk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81912e30)
Location: net/ipv4/inet_hashtables.c:473
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
```
**Symbols:**

```
ffffffff81912e30-ffffffff81912f8a: inet_ehash_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool inet_ehash_insert(struct sock *sk, struct sock *osk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff819c3b10)
Location: net/ipv4/inet_hashtables.c:473
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
```
**Symbols:**

```
ffffffff819c3b10-ffffffff819c3c6a: inet_ehash_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool inet_ehash_insert(struct sock *sk, struct sock *osk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff819cd560)
Location: net/ipv4/inet_hashtables.c:473
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
```
**Symbols:**

```
ffffffff819cd560-ffffffff819cd6bb: inet_ehash_insert (STB_GLOBAL)
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
<code>bool *found_dup_sk</code>
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
