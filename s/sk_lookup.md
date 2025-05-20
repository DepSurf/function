# Function: <code>sk_lookup</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct sock *sk_lookup(struct net *net, struct bpf_sock_tuple *tuple, int dif, int sdif, u8 family, u8 proto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818d8b50)
Location: net/core/filter.c:5018
Inline: False
Direct callers:
  - net/core/filter.c:__bpf_sk_lookup
  - net/core/filter.c:__bpf_sk_lookup
```
**Symbols:**

```
ffffffff818d8b50-ffffffff818d8d20: sk_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct sock *sk_lookup(struct net *net, struct bpf_sock_tuple *tuple, int dif, int sdif, u8 family, u8 proto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81926b60)
Location: net/core/filter.c:5198
Inline: False
Direct callers:
  - net/core/filter.c:__bpf_skc_lookup
  - net/core/filter.c:__bpf_skc_lookup
```
**Symbols:**

```
ffffffff81926b60-ffffffff81926d1f: sk_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct sock *sk_lookup(struct net *net, struct bpf_sock_tuple *tuple, int dif, int sdif, u8 family, u8 proto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81959220)
Location: net/core/filter.c:5207
Inline: False
Direct callers:
  - net/core/filter.c:__bpf_skc_lookup
  - net/core/filter.c:__bpf_skc_lookup
```
**Symbols:**

```
ffffffff81959220-ffffffff819593df: sk_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct sock *sk_lookup(struct net *net, struct bpf_sock_tuple *tuple, int dif, int sdif, u8 family, u8 proto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a2bbe0)
Location: net/core/filter.c:5334
Inline: False
Direct callers:
  - net/core/filter.c:__bpf_skc_lookup
  - net/core/filter.c:__bpf_skc_lookup
```
**Symbols:**

```
ffffffff81a2bbe0-ffffffff81a2bd99: sk_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct sock *sk_lookup(struct net *net, struct bpf_sock_tuple *tuple, int dif, int sdif, u8 family, u8 proto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a2cd90)
Location: net/core/filter.c:5886
Inline: False
Direct callers:
  - net/core/filter.c:__bpf_skc_lookup
  - net/core/filter.c:__bpf_skc_lookup
```
**Symbols:**

```
ffffffff81a2cd90-ffffffff81a2cf49: sk_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct sock *sk_lookup(struct net *net, struct bpf_sock_tuple *tuple, int dif, int sdif, u8 family, u8 proto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a142d0)
Location: net/core/filter.c:5988
Inline: False
Direct callers:
  - net/core/filter.c:__bpf_skc_lookup
  - net/core/filter.c:__bpf_skc_lookup
```
**Symbols:**

```
ffffffff81a142d0-ffffffff81a14489: sk_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct sock *sk_lookup(struct net *net, struct bpf_sock_tuple *tuple, int dif, int sdif, u8 family, u8 proto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:6112
Inline: False
Direct callers:
  - net/core/filter.c:__bpf_skc_lookup
  - net/core/filter.c:__bpf_skc_lookup
```
**Symbols:**

```
ffffffff81ac5ba0-ffffffff81ac5d65: sk_lookup (STB_LOCAL)
ffffffff81d37079-ffffffff81d3708d: sk_lookup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct sock *sk_lookup(struct net *net, struct bpf_sock_tuple *tuple, int dif, int sdif, u8 family, u8 proto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:6420
Inline: False
Direct callers:
  - net/core/filter.c:__bpf_skc_lookup
  - net/core/filter.c:__bpf_skc_lookup
  - net/core/filter.c:__bpf_skc_lookup
  - net/core/filter.c:__bpf_skc_lookup
```
**Symbols:**

```
ffffffff81c40c50-ffffffff81c40e2f: sk_lookup (STB_LOCAL)
ffffffff81f039e1-ffffffff81f039f5: sk_lookup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct sock *sk_lookup(struct net *net, struct bpf_sock_tuple *tuple, int dif, int sdif, u8 family, u8 proto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:6434
Inline: False
Direct callers:
  - net/core/filter.c:__bpf_skc_lookup
  - net/core/filter.c:__bpf_skc_lookup
  - net/core/filter.c:__bpf_skc_lookup
  - net/core/filter.c:__bpf_skc_lookup
```
**Symbols:**

```
ffffffff81df6360-ffffffff81df6537: sk_lookup (STB_LOCAL)
ffffffff820ac080-ffffffff820ac094: sk_lookup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct sock *sk_lookup(struct net *net, struct bpf_sock_tuple *tuple, int dif, int sdif, u8 family, u8 proto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:6513
Inline: False
Direct callers:
  - net/core/filter.c:__bpf_skc_lookup
  - net/core/filter.c:__bpf_skc_lookup
```
**Symbols:**

```
ffffffff81e67c70-ffffffff81e67e47: sk_lookup (STB_LOCAL)
ffffffff8212d7d1-ffffffff8212d7e5: sk_lookup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct sock *sk_lookup(struct net *net, struct bpf_sock_tuple *tuple, int dif, int sdif, u8 family, u8 proto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:6603
Inline: False
Direct callers:
  - net/core/filter.c:__bpf_skc_lookup
  - net/core/filter.c:__bpf_skc_lookup
```
**Symbols:**

```
ffffffff81f26e40-ffffffff81f27017: sk_lookup (STB_LOCAL)
ffffffff8220f516-ffffffff8220f52a: sk_lookup.cold (STB_LOCAL)
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
struct sock *sk_lookup(struct net *net, struct bpf_sock_tuple *tuple, int dif, int sdif, u8 family, u8 proto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffff800010bfa670)
Location: net/core/filter.c:5207
Inline: False
Direct callers:
  - net/core/filter.c:__bpf_skc_lookup
  - net/core/filter.c:__bpf_skc_lookup
```
**Symbols:**

```
ffff800010bfa670-ffff800010bfa8a8: sk_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct sock *sk_lookup(struct net *net, struct bpf_sock_tuple *tuple, int dif, int sdif, u8 family, u8 proto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c0d14170)
Location: net/core/filter.c:5207
Inline: False
Direct callers:
  - net/core/filter.c:__bpf_skc_lookup
  - net/core/filter.c:__bpf_skc_lookup
```
**Symbols:**

```
c0d14170-c0d14388: sk_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct sock *sk_lookup(struct net *net, struct bpf_sock_tuple *tuple, int dif, int sdif, u8 family, u8 proto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c000000000ce29d0)
Location: net/core/filter.c:5207
Inline: False
Direct callers:
  - net/core/filter.c:__bpf_skc_lookup
  - net/core/filter.c:__bpf_skc_lookup
```
**Symbols:**

```
c000000000ce29d0-c000000000ce2cd0: sk_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct sock *sk_lookup(struct net *net, struct bpf_sock_tuple *tuple, int dif, int sdif, u8 family, u8 proto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffe00077c408)
Location: net/core/filter.c:5207
Inline: False
Direct callers:
  - net/core/filter.c:__bpf_skc_lookup
  - net/core/filter.c:__bpf_skc_lookup
```
**Symbols:**

```
ffffffe00077c408-ffffffe00077c5ae: sk_lookup (STB_LOCAL)
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
struct sock *sk_lookup(struct net *net, struct bpf_sock_tuple *tuple, int dif, int sdif, u8 family, u8 proto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818f91f0)
Location: net/core/filter.c:5207
Inline: False
Direct callers:
  - net/core/filter.c:__bpf_skc_lookup
  - net/core/filter.c:__bpf_skc_lookup
```
**Symbols:**

```
ffffffff818f91f0-ffffffff818f93af: sk_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct sock *sk_lookup(struct net *net, struct bpf_sock_tuple *tuple, int dif, int sdif, u8 family, u8 proto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818b3020)
Location: net/core/filter.c:5207
Inline: False
Direct callers:
  - net/core/filter.c:__bpf_skc_lookup
  - net/core/filter.c:__bpf_skc_lookup
```
**Symbols:**

```
ffffffff818b3020-ffffffff818b31df: sk_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct sock *sk_lookup(struct net *net, struct bpf_sock_tuple *tuple, int dif, int sdif, u8 family, u8 proto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8194a220)
Location: net/core/filter.c:5207
Inline: False
Direct callers:
  - net/core/filter.c:__bpf_skc_lookup
  - net/core/filter.c:__bpf_skc_lookup
```
**Symbols:**

```
ffffffff8194a220-ffffffff8194a3df: sk_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct sock *sk_lookup(struct net *net, struct bpf_sock_tuple *tuple, int dif, int sdif, u8 family, u8 proto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8196bb30)
Location: net/core/filter.c:5207
Inline: False
Direct callers:
  - net/core/filter.c:__bpf_skc_lookup
  - net/core/filter.c:__bpf_skc_lookup
```
**Symbols:**

```
ffffffff8196bb30-ffffffff8196bcef: sk_lookup (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
