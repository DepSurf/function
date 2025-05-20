# Function: <code>inet_lhash2_bucket_sk</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct inet_listen_hashbucket *inet_lhash2_bucket_sk(struct inet_hashinfo *h, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff818f1e10)
Location: net/ipv4/inet_hashtables.c:173
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
```
**Symbols:**

```
ffffffff818f1e10-ffffffff818f1f93: inet_lhash2_bucket_sk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct inet_listen_hashbucket *inet_lhash2_bucket_sk(struct inet_hashinfo *h, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff8191fb10)
Location: net/ipv4/inet_hashtables.c:179
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
```
**Symbols:**

```
ffffffff8191fb10-ffffffff8191fc93: inet_lhash2_bucket_sk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct inet_listen_hashbucket *inet_lhash2_bucket_sk(struct inet_hashinfo *h, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81982420)
Location: net/ipv4/inet_hashtables.c:175
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
```
**Symbols:**

```
ffffffff81982420-ffffffff819825b0: inet_lhash2_bucket_sk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct inet_listen_hashbucket *inet_lhash2_bucket_sk(struct inet_hashinfo *h, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff819b8c90)
Location: net/ipv4/inet_hashtables.c:175
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
```
**Symbols:**

```
ffffffff819b8c90-ffffffff819b8e23: inet_lhash2_bucket_sk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81aa3790)
Location: net/ipv4/inet_hashtables.c:176
Inline: True
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
```
**Symbols:**

```
ffffffff81aa3790-ffffffff81aa38ee: inet_lhash2_bucket_sk.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81aaddd0)
Location: net/ipv4/inet_hashtables.c:179
Inline: True
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
```
**Symbols:**

```
ffffffff81aaddd0-ffffffff81aadf2e: inet_lhash2_bucket_sk.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81a98d90)
Location: net/ipv4/inet_hashtables.c:179
Inline: True
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
```
**Symbols:**

```
ffffffff81a98d90-ffffffff81a98f3c: inet_lhash2_bucket_sk.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct inet_listen_hashbucket *inet_lhash2_bucket_sk(struct inet_hashinfo *h, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81b54260)
Location: net/ipv4/inet_hashtables.c:179
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
```
**Symbols:**

```
ffffffff81b54260-ffffffff81b543b5: inet_lhash2_bucket_sk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct inet_listen_hashbucket *inet_lhash2_bucket_sk(struct inet_hashinfo *h, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81ce23c0)
Location: net/ipv4/inet_hashtables.c:179
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
```
**Symbols:**

```
ffffffff81ce23c0-ffffffff81ce252a: inet_lhash2_bucket_sk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct inet_listen_hashbucket *inet_lhash2_bucket_sk(struct inet_hashinfo *h, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81ea34f0)
Location: net/ipv4/inet_hashtables.c:295
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
```
**Symbols:**

```
ffffffff81ea34f0-ffffffff81ea3584: inet_lhash2_bucket_sk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct inet_listen_hashbucket *inet_lhash2_bucket_sk(struct inet_hashinfo *h, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81f01d30)
Location: net/ipv4/inet_hashtables.c:295
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
```
**Symbols:**

```
ffffffff81f01d30-ffffffff81f01dc4: inet_lhash2_bucket_sk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct inet_listen_hashbucket *inet_lhash2_bucket_sk(struct inet_hashinfo *h, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81fc5df0)
Location: net/ipv4/inet_hashtables.c:297
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
```
**Symbols:**

```
ffffffff81fc5df0-ffffffff81fc5e84: inet_lhash2_bucket_sk (STB_LOCAL)
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
struct inet_listen_hashbucket *inet_lhash2_bucket_sk(struct inet_hashinfo *h, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffff800010c6a1d0)
Location: net/ipv4/inet_hashtables.c:175
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
```
**Symbols:**

```
ffff800010c6a1d0-ffff800010c6a440: inet_lhash2_bucket_sk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct inet_listen_hashbucket *inet_lhash2_bucket_sk(struct inet_hashinfo *h, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (c0d79618)
Location: net/ipv4/inet_hashtables.c:175
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
```
**Symbols:**

```
c0d79618-c0d7980c: inet_lhash2_bucket_sk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct inet_listen_hashbucket *inet_lhash2_bucket_sk(struct inet_hashinfo *h, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (c000000000d6f600)
Location: net/ipv4/inet_hashtables.c:175
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
```
**Symbols:**

```
c000000000d6f600-c000000000d6f878: inet_lhash2_bucket_sk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct inet_listen_hashbucket *inet_lhash2_bucket_sk(struct inet_hashinfo *h, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffe0007cff6c)
Location: net/ipv4/inet_hashtables.c:175
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
```
**Symbols:**

```
ffffffe0007cff6c-ffffffe0007d0242: inet_lhash2_bucket_sk (STB_LOCAL)
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
struct inet_listen_hashbucket *inet_lhash2_bucket_sk(struct inet_hashinfo *h, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81958b00)
Location: net/ipv4/inet_hashtables.c:175
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
```
**Symbols:**

```
ffffffff81958b00-ffffffff81958c93: inet_lhash2_bucket_sk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct inet_listen_hashbucket *inet_lhash2_bucket_sk(struct inet_hashinfo *h, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff819125f0)
Location: net/ipv4/inet_hashtables.c:175
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
```
**Symbols:**

```
ffffffff819125f0-ffffffff81912783: inet_lhash2_bucket_sk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct inet_listen_hashbucket *inet_lhash2_bucket_sk(struct inet_hashinfo *h, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff819c32d0)
Location: net/ipv4/inet_hashtables.c:175
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
```
**Symbols:**

```
ffffffff819c32d0-ffffffff819c3463: inet_lhash2_bucket_sk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct inet_listen_hashbucket *inet_lhash2_bucket_sk(struct inet_hashinfo *h, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff819ccfa0)
Location: net/ipv4/inet_hashtables.c:175
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
```
**Symbols:**

```
ffffffff819ccfa0-ffffffff819cd133: inet_lhash2_bucket_sk (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
