# Function: <code>xfrm_sk_policy_lookup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct xfrm_policy *xfrm_sk_policy_lookup(const struct sock *sk, int dir, const struct flowi *fl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff817b5980)
Location: net/xfrm/xfrm_policy.c:1218
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
```
**Symbols:**

```
ffffffff817b5980-ffffffff817b5a2e: xfrm_sk_policy_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct xfrm_policy *xfrm_sk_policy_lookup(const struct sock *sk, int dir, const struct flowi *fl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff818229a0)
Location: net/xfrm/xfrm_policy.c:1222
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_lookup
```
**Symbols:**

```
ffffffff818229a0-ffffffff81822a4e: xfrm_sk_policy_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct xfrm_policy *xfrm_sk_policy_lookup(const struct sock *sk, int dir, const struct flowi *fl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff818542a0)
Location: net/xfrm/xfrm_policy.c:1250
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_lookup
```
**Symbols:**

```
ffffffff818542a0-ffffffff81854381: xfrm_sk_policy_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct xfrm_policy *xfrm_sk_policy_lookup(const struct sock *sk, int dir, const struct flowi *fl, u16 family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81877d30)
Location: net/xfrm/xfrm_policy.c:1245
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_lookup
```
**Symbols:**

```
ffffffff81877d30-ffffffff81877df6: xfrm_sk_policy_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct xfrm_policy *xfrm_sk_policy_lookup(const struct sock *sk, int dir, const struct flowi *fl, u16 family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff818f7ab0)
Location: net/xfrm/xfrm_policy.c:1161
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_lookup
```
**Symbols:**

```
ffffffff818f7ab0-ffffffff818f7ba7: xfrm_sk_policy_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct xfrm_policy *xfrm_sk_policy_lookup(const struct sock *sk, int dir, const struct flowi *fl, u16 family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff8194e440)
Location: net/xfrm/xfrm_policy.c:1161
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_lookup
```
**Symbols:**

```
ffffffff8194e440-ffffffff8194e537: xfrm_sk_policy_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct xfrm_policy *xfrm_sk_policy_lookup(const struct sock *sk, int dir, const struct flowi *fl, u16 family, u32 if_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81981750)
Location: net/xfrm/xfrm_policy.c:2149
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
```
**Symbols:**

```
ffffffff81981750-ffffffff81981854: xfrm_sk_policy_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct xfrm_policy *xfrm_sk_policy_lookup(const struct sock *sk, int dir, const struct flowi *fl, u16 family, u32 if_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff819eb4f0)
Location: net/xfrm/xfrm_policy.c:2155
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
```
**Symbols:**

```
ffffffff819eb4f0-ffffffff819eb5df: xfrm_sk_policy_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct xfrm_policy *xfrm_sk_policy_lookup(const struct sock *sk, int dir, const struct flowi *fl, u16 family, u32 if_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81a224f0)
Location: net/xfrm/xfrm_policy.c:2157
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
```
**Symbols:**

```
ffffffff81a224f0-ffffffff81a225df: xfrm_sk_policy_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct xfrm_policy *xfrm_sk_policy_lookup(const struct sock *sk, int dir, const struct flowi *fl, u16 family, u32 if_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81b144e0)
Location: net/xfrm/xfrm_policy.c:2148
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
```
**Symbols:**

```
ffffffff81b144e0-ffffffff81b145bd: xfrm_sk_policy_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct xfrm_policy *xfrm_sk_policy_lookup(const struct sock *sk, int dir, const struct flowi *fl, u16 family, u32 if_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81b22880)
Location: net/xfrm/xfrm_policy.c:2158
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
```
**Symbols:**

```
ffffffff81b22880-ffffffff81b22966: xfrm_sk_policy_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct xfrm_policy *xfrm_sk_policy_lookup(const struct sock *sk, int dir, const struct flowi *fl, u16 family, u32 if_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81b10480)
Location: net/xfrm/xfrm_policy.c:2157
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
```
**Symbols:**

```
ffffffff81b10480-ffffffff81b1055e: xfrm_sk_policy_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct xfrm_policy *xfrm_sk_policy_lookup(const struct sock *sk, int dir, const struct flowi *fl, u16 family, u32 if_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81bd3da0)
Location: net/xfrm/xfrm_policy.c:2158
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
```
**Symbols:**

```
ffffffff81bd3da0-ffffffff81bd3e94: xfrm_sk_policy_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct xfrm_policy *xfrm_sk_policy_lookup(const struct sock *sk, int dir, const struct flowi *fl, u16 family, u32 if_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81d6a270)
Location: net/xfrm/xfrm_policy.c:2158
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
```
**Symbols:**

```
ffffffff81d6a270-ffffffff81d6a383: xfrm_sk_policy_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct xfrm_policy *xfrm_sk_policy_lookup(const struct sock *sk, int dir, const struct flowi *fl, u16 family, u32 if_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81f355b0)
Location: net/xfrm/xfrm_policy.c:2231
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
```
**Symbols:**

```
ffffffff81f355b0-ffffffff81f356c3: xfrm_sk_policy_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct xfrm_policy *xfrm_sk_policy_lookup(const struct sock *sk, int dir, const struct flowi *fl, u16 family, u32 if_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81f95160)
Location: net/xfrm/xfrm_policy.c:2233
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
```
**Symbols:**

```
ffffffff81f95160-ffffffff81f9526f: xfrm_sk_policy_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct xfrm_policy *xfrm_sk_policy_lookup(const struct sock *sk, int dir, const struct flowi *fl, u16 family, u32 if_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff82062550)
Location: net/xfrm/xfrm_policy.c:2253
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
```
**Symbols:**

```
ffffffff82062550-ffffffff8206265f: xfrm_sk_policy_lookup (STB_LOCAL)
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
struct xfrm_policy *xfrm_sk_policy_lookup(const struct sock *sk, int dir, const struct flowi *fl, u16 family, u32 if_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffff800010cdf658)
Location: net/xfrm/xfrm_policy.c:2157
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
```
**Symbols:**

```
ffff800010cdf658-ffff800010cdf754: xfrm_sk_policy_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct xfrm_policy *xfrm_sk_policy_lookup(const struct sock *sk, int dir, const struct flowi *fl, u16 family, u32 if_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (c0de8b40)
Location: net/xfrm/xfrm_policy.c:2157
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
```
**Symbols:**

```
c0de8b40-c0de8c18: xfrm_sk_policy_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct xfrm_policy *xfrm_sk_policy_lookup(const struct sock *sk, int dir, const struct flowi *fl, u16 family, u32 if_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (c000000000e01480)
Location: net/xfrm/xfrm_policy.c:2157
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
```
**Symbols:**

```
c000000000e01480-c000000000e01614: xfrm_sk_policy_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct xfrm_policy *xfrm_sk_policy_lookup(const struct sock *sk, int dir, const struct flowi *fl, u16 family, u32 if_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffe00082e4f0)
Location: net/xfrm/xfrm_policy.c:2157
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
```
**Symbols:**

```
ffffffe00082e4f0-ffffffe00082e5c8: xfrm_sk_policy_lookup (STB_LOCAL)
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
struct xfrm_policy *xfrm_sk_policy_lookup(const struct sock *sk, int dir, const struct flowi *fl, u16 family, u32 if_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff819c1b80)
Location: net/xfrm/xfrm_policy.c:2157
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
```
**Symbols:**

```
ffffffff819c1b80-ffffffff819c1c6f: xfrm_sk_policy_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct xfrm_policy *xfrm_sk_policy_lookup(const struct sock *sk, int dir, const struct flowi *fl, u16 family, u32 if_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff8197e970)
Location: net/xfrm/xfrm_policy.c:2157
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
```
**Symbols:**

```
ffffffff8197e970-ffffffff8197ea5f: xfrm_sk_policy_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct xfrm_policy *xfrm_sk_policy_lookup(const struct sock *sk, int dir, const struct flowi *fl, u16 family, u32 if_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81a2c600)
Location: net/xfrm/xfrm_policy.c:2157
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
```
**Symbols:**

```
ffffffff81a2c600-ffffffff81a2c6ef: xfrm_sk_policy_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct xfrm_policy *xfrm_sk_policy_lookup(const struct sock *sk, int dir, const struct flowi *fl, u16 family, u32 if_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81a37cd0)
Location: net/xfrm/xfrm_policy.c:2157
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
```
**Symbols:**

```
ffffffff81a37cd0-ffffffff81a37dcc: xfrm_sk_policy_lookup (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u16 family</code>
</li>
</ul>
</details>
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
<code>u32 if_id</code>
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
