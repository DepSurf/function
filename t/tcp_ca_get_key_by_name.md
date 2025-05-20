# Function: <code>tcp_ca_get_key_by_name</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
u32 tcp_ca_get_key_by_name(const char *name, bool *ecn_ca);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (ffffffff81780400)
Location: net/ipv4/tcp_cong.c:117
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffffffff81780400-ffffffff81780442: tcp_ca_get_key_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
u32 tcp_ca_get_key_by_name(const char *name, bool *ecn_ca);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (ffffffff817ed8e0)
Location: net/ipv4/tcp_cong.c:117
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffffffff817ed8e0-ffffffff817ed922: tcp_ca_get_key_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
u32 tcp_ca_get_key_by_name(const char *name, bool *ecn_ca);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (ffffffff8181e220)
Location: net/ipv4/tcp_cong.c:118
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffffffff8181e220-ffffffff8181e262: tcp_ca_get_key_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
u32 tcp_ca_get_key_by_name(const char *name, bool *ecn_ca);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (ffffffff8183e980)
Location: net/ipv4/tcp_cong.c:118
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffffffff8183e980-ffffffff8183e9bb: tcp_ca_get_key_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u32 tcp_ca_get_key_by_name(struct net *net, const char *name, bool *ecn_ca);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (ffffffff818be1d0)
Location: net/ipv4/tcp_cong.c:120
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_metrics_match
  - net/ipv6/route.c:ip6_convert_metrics
```
**Symbols:**

```
ffffffff818be1d0-ffffffff818be20b: tcp_ca_get_key_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u32 tcp_ca_get_key_by_name(struct net *net, const char *name, bool *ecn_ca);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (ffffffff81913da0)
Location: net/ipv4/tcp_cong.c:120
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_metrics_match
  - net/ipv4/metrics.c:ip_metrics_convert
```
**Symbols:**

```
ffffffff81913da0-ffffffff81913ddb: tcp_ca_get_key_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u32 tcp_ca_get_key_by_name(struct net *net, const char *name, bool *ecn_ca);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (ffffffff81942550)
Location: net/ipv4/tcp_cong.c:120
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_metrics_match
```
**Symbols:**

```
ffffffff81942550-ffffffff8194258b: tcp_ca_get_key_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u32 tcp_ca_get_key_by_name(struct net *net, const char *name, bool *ecn_ca);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (ffffffff819a6b40)
Location: net/ipv4/tcp_cong.c:121
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_metrics_match
```
**Symbols:**

```
ffffffff819a6b40-ffffffff819a6b7d: tcp_ca_get_key_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u32 tcp_ca_get_key_by_name(struct net *net, const char *name, bool *ecn_ca);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (ffffffff819dd810)
Location: net/ipv4/tcp_cong.c:121
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_metrics_match
```
**Symbols:**

```
ffffffff819dd810-ffffffff819dd84d: tcp_ca_get_key_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u32 tcp_ca_get_key_by_name(struct net *net, const char *name, bool *ecn_ca);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (ffffffff81acaca0)
Location: net/ipv4/tcp_cong.c:121
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_metrics_match
  - net/ipv4/metrics.c:ip_metrics_convert
```
**Symbols:**

```
ffffffff81acaca0-ffffffff81acacdd: tcp_ca_get_key_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u32 tcp_ca_get_key_by_name(struct net *net, const char *name, bool *ecn_ca);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (ffffffff81ad6c40)
Location: net/ipv4/tcp_cong.c:121
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_metrics_match
  - net/ipv4/metrics.c:ip_metrics_convert
```
**Symbols:**

```
ffffffff81ad6c40-ffffffff81ad6c82: tcp_ca_get_key_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u32 tcp_ca_get_key_by_name(struct net *net, const char *name, bool *ecn_ca);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (ffffffff81ac1cd0)
Location: net/ipv4/tcp_cong.c:121
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_metrics_match
  - net/ipv4/metrics.c:ip_metrics_convert
```
**Symbols:**

```
ffffffff81ac1cd0-ffffffff81ac1d18: tcp_ca_get_key_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u32 tcp_ca_get_key_by_name(struct net *net, const char *name, bool *ecn_ca);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (ffffffff81b7f9f0)
Location: net/ipv4/tcp_cong.c:121
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_metrics_match
  - net/ipv4/metrics.c:ip_metrics_convert
```
**Symbols:**

```
ffffffff81b7f9f0-ffffffff81b7fa38: tcp_ca_get_key_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u32 tcp_ca_get_key_by_name(struct net *net, const char *name, bool *ecn_ca);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (ffffffff81d0fc90)
Location: net/ipv4/tcp_cong.c:133
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_metrics_match
  - net/ipv4/metrics.c:ip_metrics_convert
```
**Symbols:**

```
ffffffff81d0fc90-ffffffff81d0fce7: tcp_ca_get_key_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u32 tcp_ca_get_key_by_name(struct net *net, const char *name, bool *ecn_ca);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (ffffffff81ed5910)
Location: net/ipv4/tcp_cong.c:133
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_metrics_match
  - net/ipv4/metrics.c:ip_metrics_convert
```
**Symbols:**

```
ffffffff81ed5910-ffffffff81ed5967: tcp_ca_get_key_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u32 tcp_ca_get_key_by_name(struct net *net, const char *name, bool *ecn_ca);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (ffffffff81f34850)
Location: net/ipv4/tcp_cong.c:185
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_metrics_match
  - net/ipv4/metrics.c:ip_metrics_convert
```
**Symbols:**

```
ffffffff81f34850-ffffffff81f348a7: tcp_ca_get_key_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u32 tcp_ca_get_key_by_name(struct net *net, const char *name, bool *ecn_ca);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (ffffffff81ffa9d0)
Location: net/ipv4/tcp_cong.c:185
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_metrics_match
  - net/ipv4/metrics.c:ip_metrics_convert
```
**Symbols:**

```
ffffffff81ffa9d0-ffffffff81ffaa27: tcp_ca_get_key_by_name (STB_GLOBAL)
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
u32 tcp_ca_get_key_by_name(struct net *net, const char *name, bool *ecn_ca);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (ffff800010c90bc8)
Location: net/ipv4/tcp_cong.c:121
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_metrics_match
```
**Symbols:**

```
ffff800010c90bc8-ffff800010c90c14: tcp_ca_get_key_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u32 tcp_ca_get_key_by_name(struct net *net, const char *name, bool *ecn_ca);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (c0d9f96c)
Location: net/ipv4/tcp_cong.c:121
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_metrics_match
```
**Symbols:**

```
c0d9f96c-c0d9f9ac: tcp_ca_get_key_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u32 tcp_ca_get_key_by_name(struct net *net, const char *name, bool *ecn_ca);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (c000000000da0170)
Location: net/ipv4/tcp_cong.c:121
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_metrics_match
```
**Symbols:**

```
c000000000da0170-c000000000da0200: tcp_ca_get_key_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u32 tcp_ca_get_key_by_name(struct net *net, const char *name, bool *ecn_ca);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (ffffffe0007f09b2)
Location: net/ipv4/tcp_cong.c:121
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_metrics_match
```
**Symbols:**

```
ffffffe0007f09b2-ffffffe0007f09fe: tcp_ca_get_key_by_name (STB_GLOBAL)
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
u32 tcp_ca_get_key_by_name(struct net *net, const char *name, bool *ecn_ca);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (ffffffff8197d680)
Location: net/ipv4/tcp_cong.c:121
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_metrics_match
```
**Symbols:**

```
ffffffff8197d680-ffffffff8197d6bd: tcp_ca_get_key_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u32 tcp_ca_get_key_by_name(struct net *net, const char *name, bool *ecn_ca);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (ffffffff81937140)
Location: net/ipv4/tcp_cong.c:121
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_metrics_match
```
**Symbols:**

```
ffffffff81937140-ffffffff8193717d: tcp_ca_get_key_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u32 tcp_ca_get_key_by_name(struct net *net, const char *name, bool *ecn_ca);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (ffffffff819e7e50)
Location: net/ipv4/tcp_cong.c:121
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_metrics_match
```
**Symbols:**

```
ffffffff819e7e50-ffffffff819e7e8d: tcp_ca_get_key_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u32 tcp_ca_get_key_by_name(struct net *net, const char *name, bool *ecn_ca);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (ffffffff819f1bb0)
Location: net/ipv4/tcp_cong.c:121
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_metrics_match
```
**Symbols:**

```
ffffffff819f1bb0-ffffffff819f1bf2: tcp_ca_get_key_by_name (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct net *net</code>
</li>
<li>
<b>Param reordered. </b>
<code>name, ecn_ca</code> ➡️ <code>net, name, ecn_ca</code>
</li>
</ul>
</details>
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
