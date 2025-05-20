# Function: <code>sk_ehashfn</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
u32 sk_ehashfn(const struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81762990)
Location: net/ipv4/inet_hashtables.c:43
Inline: True
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
```
**Symbols:**

```
ffffffff81762990-ffffffff817629e7: sk_ehashfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
u32 sk_ehashfn(const struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff817cec10)
Location: net/ipv4/inet_hashtables.c:45
Inline: True
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
```
**Symbols:**

```
ffffffff817cec10-ffffffff817cec67: sk_ehashfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
u32 sk_ehashfn(const struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff817fea20)
Location: net/ipv4/inet_hashtables.c:46
Inline: True
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
```
**Symbols:**

```
ffffffff817fea20-ffffffff817fea77: sk_ehashfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff8181efb2)
Location: net/ipv4/inet_hashtables.c:46
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff8189df62)
Location: net/ipv4/inet_hashtables.c:46
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff818f2912)
Location: net/ipv4/inet_hashtables.c:47
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81920382)
Location: net/ipv4/inet_hashtables.c:47
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81982ca2)
Location: net/ipv4/inet_hashtables.c:43
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff819b9502)
Location: net/ipv4/inet_hashtables.c:43
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81aa4042)
Location: net/ipv4/inet_hashtables.c:43
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81aae671)
Location: net/ipv4/inet_hashtables.c:46
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81a99751)
Location: net/ipv4/inet_hashtables.c:46
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81b54bd1)
Location: net/ipv4/inet_hashtables.c:46
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81ce27c1)
Location: net/ipv4/inet_hashtables.c:46
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81ea3c1e)
Location: net/ipv4/inet_hashtables.c:46
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81f0249e)
Location: net/ipv4/inet_hashtables.c:46
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81fc685e)
Location: net/ipv4/inet_hashtables.c:47
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffff800010c6ac04)
Location: net/ipv4/inet_hashtables.c:43
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (c0d79ca4)
Location: net/ipv4/inet_hashtables.c:43
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (c000000000d6fef4)
Location: net/ipv4/inet_hashtables.c:43
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffe0007d0936)
Location: net/ipv4/inet_hashtables.c:43
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81959372)
Location: net/ipv4/inet_hashtables.c:43
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81912e62)
Location: net/ipv4/inet_hashtables.c:43
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff819c3b42)
Location: net/ipv4/inet_hashtables.c:43
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff819cd592)
Location: net/ipv4/inet_hashtables.c:43
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
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
</ul>
