# Function: <code>ip_mtu_from_fib_result</code>

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
u32 ip_mtu_from_fib_result(struct fib_result *res, __be32 daddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff818e4130)
Location: net/ipv4/route.c:1350
Inline: False
Direct callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
**Symbols:**

```
ffffffff818e4130-ffffffff818e41f4: ip_mtu_from_fib_result (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u32 ip_mtu_from_fib_result(struct fib_result *res, __be32 daddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81911040)
Location: net/ipv4/route.c:1353
Inline: False
Direct callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
**Symbols:**

```
ffffffff81911040-ffffffff81911104: ip_mtu_from_fib_result (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u32 ip_mtu_from_fib_result(struct fib_result *res, __be32 daddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81973700)
Location: net/ipv4/route.c:1391
Inline: False
Direct callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
**Symbols:**

```
ffffffff81973700-ffffffff8197379c: ip_mtu_from_fib_result (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u32 ip_mtu_from_fib_result(struct fib_result *res, __be32 daddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff819aa080)
Location: net/ipv4/route.c:1393
Inline: False
Direct callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
**Symbols:**

```
ffffffff819aa080-ffffffff819aa11c: ip_mtu_from_fib_result (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u32 ip_mtu_from_fib_result(struct fib_result *res, __be32 daddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81a94770)
Location: net/ipv4/route.c:1397
Inline: False
Direct callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
**Symbols:**

```
ffffffff81a94770-ffffffff81a9480c: ip_mtu_from_fib_result (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u32 ip_mtu_from_fib_result(struct fib_result *res, __be32 daddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81a9e760)
Location: net/ipv4/route.c:1403
Inline: False
Direct callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
**Symbols:**

```
ffffffff81a9e760-ffffffff81a9e80f: ip_mtu_from_fib_result (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u32 ip_mtu_from_fib_result(struct fib_result *res, __be32 daddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81a896d0)
Location: net/ipv4/route.c:1391
Inline: False
Direct callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
**Symbols:**

```
ffffffff81a896d0-ffffffff81a89765: ip_mtu_from_fib_result (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u32 ip_mtu_from_fib_result(struct fib_result *res, __be32 daddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81b44220)
Location: net/ipv4/route.c:1387
Inline: False
Direct callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
**Symbols:**

```
ffffffff81b44220-ffffffff81b442b5: ip_mtu_from_fib_result (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u32 ip_mtu_from_fib_result(struct fib_result *res, __be32 daddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81cd0da0)
Location: net/ipv4/route.c:1394
Inline: False
Direct callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
**Symbols:**

```
ffffffff81cd0da0-ffffffff81cd0e63: ip_mtu_from_fib_result (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u32 ip_mtu_from_fib_result(struct fib_result *res, __be32 daddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81e90fe0)
Location: net/ipv4/route.c:1394
Inline: False
Direct callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
**Symbols:**

```
ffffffff81e90fe0-ffffffff81e910a3: ip_mtu_from_fib_result (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u32 ip_mtu_from_fib_result(struct fib_result *res, __be32 daddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81eef790)
Location: net/ipv4/route.c:1394
Inline: False
Direct callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
**Symbols:**

```
ffffffff81eef790-ffffffff81eef853: ip_mtu_from_fib_result (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u32 ip_mtu_from_fib_result(struct fib_result *res, __be32 daddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81fb38f0)
Location: net/ipv4/route.c:1396
Inline: False
Direct callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
**Symbols:**

```
ffffffff81fb38f0-ffffffff81fb39b0: ip_mtu_from_fib_result (STB_GLOBAL)
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
u32 ip_mtu_from_fib_result(struct fib_result *res, __be32 daddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffff800010c5a1a0)
Location: net/ipv4/route.c:1393
Inline: False
Direct callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
**Symbols:**

```
ffff800010c5a1a0-ffff800010c5a25c: ip_mtu_from_fib_result (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u32 ip_mtu_from_fib_result(struct fib_result *res, __be32 daddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (c0d69810)
Location: net/ipv4/route.c:1393
Inline: False
Direct callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
**Symbols:**

```
c0d69810-c0d698dc: ip_mtu_from_fib_result (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u32 ip_mtu_from_fib_result(struct fib_result *res, __be32 daddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (c000000000d5bc50)
Location: net/ipv4/route.c:1393
Inline: False
Direct callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
**Symbols:**

```
c000000000d5bc50-c000000000d5bd78: ip_mtu_from_fib_result (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u32 ip_mtu_from_fib_result(struct fib_result *res, __be32 daddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffe0007c37a8)
Location: net/ipv4/route.c:1393
Inline: False
Direct callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
**Symbols:**

```
ffffffe0007c37a8-ffffffe0007c386a: ip_mtu_from_fib_result (STB_GLOBAL)
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
u32 ip_mtu_from_fib_result(struct fib_result *res, __be32 daddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81949ef0)
Location: net/ipv4/route.c:1393
Inline: False
Direct callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
**Symbols:**

```
ffffffff81949ef0-ffffffff81949f8c: ip_mtu_from_fib_result (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u32 ip_mtu_from_fib_result(struct fib_result *res, __be32 daddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff819039e0)
Location: net/ipv4/route.c:1393
Inline: False
Direct callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
**Symbols:**

```
ffffffff819039e0-ffffffff81903a7c: ip_mtu_from_fib_result (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u32 ip_mtu_from_fib_result(struct fib_result *res, __be32 daddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff819b46c0)
Location: net/ipv4/route.c:1393
Inline: False
Direct callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
**Symbols:**

```
ffffffff819b46c0-ffffffff819b475c: ip_mtu_from_fib_result (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u32 ip_mtu_from_fib_result(struct fib_result *res, __be32 daddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff819bde00)
Location: net/ipv4/route.c:1393
Inline: False
Direct callers:
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
**Symbols:**

```
ffffffff819bde00-ffffffff819bde9c: ip_mtu_from_fib_result (STB_GLOBAL)
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
