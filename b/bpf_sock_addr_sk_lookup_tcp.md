# Function: <code>bpf_sock_addr_sk_lookup_tcp</code>

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
u64 bpf_sock_addr_sk_lookup_tcp(u64 ctx, u64 tuple, u64 len, u64 netns_id, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818d8f00)
Location: net/core/filter.c:5218
Inline: False
```
**Symbols:**

```
ffffffff818d8f00-ffffffff818d8f28: bpf_sock_addr_sk_lookup_tcp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u64 bpf_sock_addr_sk_lookup_tcp(u64 ctx, u64 tuple, u64 len, u64 netns_id, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81927060)
Location: net/core/filter.c:5506
Inline: False
```
**Symbols:**

```
ffffffff81927060-ffffffff8192708d: bpf_sock_addr_sk_lookup_tcp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u64 bpf_sock_addr_sk_lookup_tcp(u64 ctx, u64 tuple, u64 len, u64 netns_id, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81959700)
Location: net/core/filter.c:5514
Inline: False
```
**Symbols:**

```
ffffffff81959700-ffffffff8195972d: bpf_sock_addr_sk_lookup_tcp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u64 bpf_sock_addr_sk_lookup_tcp(u64 ctx, u64 tuple, u64 len, u64 netns_id, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a2e640)
Location: net/core/filter.c:5640
Inline: False
```
**Symbols:**

```
ffffffff81a2e640-ffffffff81a2e6a8: bpf_sock_addr_sk_lookup_tcp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u64 bpf_sock_addr_sk_lookup_tcp(u64 ctx, u64 tuple, u64 len, u64 netns_id, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a303a0)
Location: net/core/filter.c:6192
Inline: False
```
**Symbols:**

```
ffffffff81a303a0-ffffffff81a30408: bpf_sock_addr_sk_lookup_tcp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 bpf_sock_addr_sk_lookup_tcp(u64 ctx, u64 tuple, u64 len, u64 netns_id, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a17320)
Location: net/core/filter.c:6294
Inline: False
```
**Symbols:**

```
ffffffff81a17320-ffffffff81a17380: bpf_sock_addr_sk_lookup_tcp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
u64 bpf_sock_addr_sk_lookup_tcp(u64 ctx, u64 tuple, u64 len, u64 netns_id, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:6418
Inline: False
```
**Symbols:**

```
ffffffff81d37337-ffffffff81d3735f: bpf_sock_addr_sk_lookup_tcp.cold (STB_LOCAL)
ffffffff81acaad0-ffffffff81acab3d: bpf_sock_addr_sk_lookup_tcp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u64 bpf_sock_addr_sk_lookup_tcp(u64 ctx, u64 tuple, u64 len, u64 netns_id, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81c48c40)
Location: net/core/filter.c:6748
Inline: False
```
**Symbols:**

```
ffffffff81c48c40-ffffffff81c48c7f: bpf_sock_addr_sk_lookup_tcp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u64 bpf_sock_addr_sk_lookup_tcp(u64 ctx, u64 tuple, u64 len, u64 netns_id, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81dfdf90)
Location: net/core/filter.c:6760
Inline: False
```
**Symbols:**

```
ffffffff81dfdf90-ffffffff81dfdfcf: bpf_sock_addr_sk_lookup_tcp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u64 bpf_sock_addr_sk_lookup_tcp(u64 ctx, u64 tuple, u64 len, u64 netns_id, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81e6ed80)
Location: net/core/filter.c:6917
Inline: False
```
**Symbols:**

```
ffffffff81e6ed80-ffffffff81e6edbc: bpf_sock_addr_sk_lookup_tcp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u64 bpf_sock_addr_sk_lookup_tcp(u64 ctx, u64 tuple, u64 len, u64 netns_id, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81f2e3e0)
Location: net/core/filter.c:7007
Inline: False
```
**Symbols:**

```
ffffffff81f2e3e0-ffffffff81f2e41c: bpf_sock_addr_sk_lookup_tcp (STB_GLOBAL)
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
u64 bpf_sock_addr_sk_lookup_tcp(u64 ctx, u64 tuple, u64 len, u64 netns_id, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffff800010bfadd8)
Location: net/core/filter.c:5514
Inline: False
```
**Symbols:**

```
ffff800010bfadd8-ffff800010bfae40: bpf_sock_addr_sk_lookup_tcp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u64 bpf_sock_addr_sk_lookup_tcp(u64 ctx, u64 tuple, u64 len, u64 netns_id, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c0d147dc)
Location: net/core/filter.c:5514
Inline: False
```
**Symbols:**

```
c0d147dc-c0d14830: bpf_sock_addr_sk_lookup_tcp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u64 bpf_sock_addr_sk_lookup_tcp(u64 ctx, u64 tuple, u64 len, u64 netns_id, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c000000000ce3180)
Location: net/core/filter.c:5514
Inline: False
```
**Symbols:**

```
c000000000ce3180-c000000000ce31b4: bpf_sock_addr_sk_lookup_tcp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u64 bpf_sock_addr_sk_lookup_tcp(u64 ctx, u64 tuple, u64 len, u64 netns_id, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffe00077c990)
Location: net/core/filter.c:5514
Inline: False
```
**Symbols:**

```
ffffffe00077c990-ffffffe00077c9e4: bpf_sock_addr_sk_lookup_tcp (STB_GLOBAL)
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
u64 bpf_sock_addr_sk_lookup_tcp(u64 ctx, u64 tuple, u64 len, u64 netns_id, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818f96d0)
Location: net/core/filter.c:5514
Inline: False
```
**Symbols:**

```
ffffffff818f96d0-ffffffff818f96fd: bpf_sock_addr_sk_lookup_tcp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u64 bpf_sock_addr_sk_lookup_tcp(u64 ctx, u64 tuple, u64 len, u64 netns_id, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818b3500)
Location: net/core/filter.c:5514
Inline: False
```
**Symbols:**

```
ffffffff818b3500-ffffffff818b352d: bpf_sock_addr_sk_lookup_tcp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u64 bpf_sock_addr_sk_lookup_tcp(u64 ctx, u64 tuple, u64 len, u64 netns_id, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8194a700)
Location: net/core/filter.c:5514
Inline: False
```
**Symbols:**

```
ffffffff8194a700-ffffffff8194a72d: bpf_sock_addr_sk_lookup_tcp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u64 bpf_sock_addr_sk_lookup_tcp(u64 ctx, u64 tuple, u64 len, u64 netns_id, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8196c010)
Location: net/core/filter.c:5514
Inline: False
```
**Symbols:**

```
ffffffff8196c010-ffffffff8196c03d: bpf_sock_addr_sk_lookup_tcp (STB_GLOBAL)
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
