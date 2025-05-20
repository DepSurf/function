# Function: <code>bpf_sock_addr_sk_lookup_udp</code>

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
u64 bpf_sock_addr_sk_lookup_udp(u64 ctx, u64 tuple, u64 len, u64 netns_id, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818d8f30)
Location: net/core/filter.c:5236
Inline: False
```
**Symbols:**

```
ffffffff818d8f30-ffffffff818d8f58: bpf_sock_addr_sk_lookup_udp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u64 bpf_sock_addr_sk_lookup_udp(u64 ctx, u64 tuple, u64 len, u64 netns_id, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81927030)
Location: net/core/filter.c:5525
Inline: False
```
**Symbols:**

```
ffffffff81927030-ffffffff8192705d: bpf_sock_addr_sk_lookup_udp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u64 bpf_sock_addr_sk_lookup_udp(u64 ctx, u64 tuple, u64 len, u64 netns_id, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff819596d0)
Location: net/core/filter.c:5533
Inline: False
```
**Symbols:**

```
ffffffff819596d0-ffffffff819596fd: bpf_sock_addr_sk_lookup_udp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u64 bpf_sock_addr_sk_lookup_udp(u64 ctx, u64 tuple, u64 len, u64 netns_id, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a2e6b0)
Location: net/core/filter.c:5659
Inline: False
```
**Symbols:**

```
ffffffff81a2e6b0-ffffffff81a2e718: bpf_sock_addr_sk_lookup_udp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u64 bpf_sock_addr_sk_lookup_udp(u64 ctx, u64 tuple, u64 len, u64 netns_id, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a30410)
Location: net/core/filter.c:6211
Inline: False
```
**Symbols:**

```
ffffffff81a30410-ffffffff81a30478: bpf_sock_addr_sk_lookup_udp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 bpf_sock_addr_sk_lookup_udp(u64 ctx, u64 tuple, u64 len, u64 netns_id, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a17380)
Location: net/core/filter.c:6313
Inline: False
```
**Symbols:**

```
ffffffff81a17380-ffffffff81a173e0: bpf_sock_addr_sk_lookup_udp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
u64 bpf_sock_addr_sk_lookup_udp(u64 ctx, u64 tuple, u64 len, u64 netns_id, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:6437
Inline: False
```
**Symbols:**

```
ffffffff81d3730f-ffffffff81d37337: bpf_sock_addr_sk_lookup_udp.cold (STB_LOCAL)
ffffffff81acaa60-ffffffff81acaacd: bpf_sock_addr_sk_lookup_udp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u64 bpf_sock_addr_sk_lookup_udp(u64 ctx, u64 tuple, u64 len, u64 netns_id, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81c48c00)
Location: net/core/filter.c:6767
Inline: False
```
**Symbols:**

```
ffffffff81c48c00-ffffffff81c48c3f: bpf_sock_addr_sk_lookup_udp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u64 bpf_sock_addr_sk_lookup_udp(u64 ctx, u64 tuple, u64 len, u64 netns_id, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81dfdf40)
Location: net/core/filter.c:6779
Inline: False
```
**Symbols:**

```
ffffffff81dfdf40-ffffffff81dfdf7f: bpf_sock_addr_sk_lookup_udp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u64 bpf_sock_addr_sk_lookup_udp(u64 ctx, u64 tuple, u64 len, u64 netns_id, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81e6edd0)
Location: net/core/filter.c:6936
Inline: False
```
**Symbols:**

```
ffffffff81e6edd0-ffffffff81e6ee0c: bpf_sock_addr_sk_lookup_udp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u64 bpf_sock_addr_sk_lookup_udp(u64 ctx, u64 tuple, u64 len, u64 netns_id, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81f2e430)
Location: net/core/filter.c:7026
Inline: False
```
**Symbols:**

```
ffffffff81f2e430-ffffffff81f2e46c: bpf_sock_addr_sk_lookup_udp (STB_GLOBAL)
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
u64 bpf_sock_addr_sk_lookup_udp(u64 ctx, u64 tuple, u64 len, u64 netns_id, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffff800010bfad70)
Location: net/core/filter.c:5533
Inline: False
```
**Symbols:**

```
ffff800010bfad70-ffff800010bfadd8: bpf_sock_addr_sk_lookup_udp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u64 bpf_sock_addr_sk_lookup_udp(u64 ctx, u64 tuple, u64 len, u64 netns_id, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c0d14788)
Location: net/core/filter.c:5533
Inline: False
```
**Symbols:**

```
c0d14788-c0d147dc: bpf_sock_addr_sk_lookup_udp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u64 bpf_sock_addr_sk_lookup_udp(u64 ctx, u64 tuple, u64 len, u64 netns_id, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c000000000ce3140)
Location: net/core/filter.c:5533
Inline: False
```
**Symbols:**

```
c000000000ce3140-c000000000ce3174: bpf_sock_addr_sk_lookup_udp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u64 bpf_sock_addr_sk_lookup_udp(u64 ctx, u64 tuple, u64 len, u64 netns_id, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffe00077c93c)
Location: net/core/filter.c:5533
Inline: False
```
**Symbols:**

```
ffffffe00077c93c-ffffffe00077c990: bpf_sock_addr_sk_lookup_udp (STB_GLOBAL)
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
u64 bpf_sock_addr_sk_lookup_udp(u64 ctx, u64 tuple, u64 len, u64 netns_id, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818f96a0)
Location: net/core/filter.c:5533
Inline: False
```
**Symbols:**

```
ffffffff818f96a0-ffffffff818f96cd: bpf_sock_addr_sk_lookup_udp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u64 bpf_sock_addr_sk_lookup_udp(u64 ctx, u64 tuple, u64 len, u64 netns_id, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818b34d0)
Location: net/core/filter.c:5533
Inline: False
```
**Symbols:**

```
ffffffff818b34d0-ffffffff818b34fd: bpf_sock_addr_sk_lookup_udp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u64 bpf_sock_addr_sk_lookup_udp(u64 ctx, u64 tuple, u64 len, u64 netns_id, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8194a6d0)
Location: net/core/filter.c:5533
Inline: False
```
**Symbols:**

```
ffffffff8194a6d0-ffffffff8194a6fd: bpf_sock_addr_sk_lookup_udp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u64 bpf_sock_addr_sk_lookup_udp(u64 ctx, u64 tuple, u64 len, u64 netns_id, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8196bfe0)
Location: net/core/filter.c:5533
Inline: False
```
**Symbols:**

```
ffffffff8196bfe0-ffffffff8196c00d: bpf_sock_addr_sk_lookup_udp (STB_GLOBAL)
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
