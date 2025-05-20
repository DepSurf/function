# Function: <code>secure_tcpv6_seq</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
u32 secure_tcpv6_seq(const __be32 *saddr, const __be32 *daddr, __be16 sport, __be16 dport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/secure_seq.c (ffffffff817c3fa0)
Location: net/core/secure_seq.c:74
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_seq
```
**Symbols:**

```
ffffffff817c3fa0-ffffffff817c407b: secure_tcpv6_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u32 secure_tcpv6_seq(const __be32 *saddr, const __be32 *daddr, __be16 sport, __be16 dport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/secure_seq.c (ffffffff8183da70)
Location: net/core/secure_seq.c:74
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_seq
```
**Symbols:**

```
ffffffff8183da70-ffffffff8183db4b: secure_tcpv6_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u32 secure_tcpv6_seq(const __be32 *saddr, const __be32 *daddr, __be16 sport, __be16 dport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/secure_seq.c (ffffffff81888280)
Location: net/core/secure_seq.c:74
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_seq
```
**Symbols:**

```
ffffffff81888280-ffffffff81888354: secure_tcpv6_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u32 secure_tcpv6_seq(const __be32 *saddr, const __be32 *daddr, __be16 sport, __be16 dport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/secure_seq.c (ffffffff818a8e50)
Location: net/core/secure_seq.c:74
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_seq
```
**Symbols:**

```
ffffffff818a8e50-ffffffff818a8f24: secure_tcpv6_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u32 secure_tcpv6_seq(const __be32 *saddr, const __be32 *daddr, __be16 sport, __be16 dport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/secure_seq.c (ffffffff818f44f0)
Location: net/core/secure_seq.c:75
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_seq
```
**Symbols:**

```
ffffffff818f44f0-ffffffff818f45c4: secure_tcpv6_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u32 secure_tcpv6_seq(const __be32 *saddr, const __be32 *daddr, __be16 sport, __be16 dport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/secure_seq.c (ffffffff819264a0)
Location: net/core/secure_seq.c:75
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_seq
```
**Symbols:**

```
ffffffff819264a0-ffffffff81926574: secure_tcpv6_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u32 secure_tcpv6_seq(const __be32 *saddr, const __be32 *daddr, __be16 sport, __be16 dport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/secure_seq.c (ffffffff819fa470)
Location: net/core/secure_seq.c:74
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_seq
```
**Symbols:**

```
ffffffff819fa470-ffffffff819fa53c: secure_tcpv6_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u32 secure_tcpv6_seq(const __be32 *saddr, const __be32 *daddr, __be16 sport, __be16 dport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/secure_seq.c (ffffffff819fa060)
Location: net/core/secure_seq.c:74
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_seq
```
**Symbols:**

```
ffffffff819fa060-ffffffff819fa12c: secure_tcpv6_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u32 secure_tcpv6_seq(const __be32 *saddr, const __be32 *daddr, __be16 sport, __be16 dport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/secure_seq.c (ffffffff819e0230)
Location: net/core/secure_seq.c:74
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_seq
```
**Symbols:**

```
ffffffff819e0230-ffffffff819e0306: secure_tcpv6_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u32 secure_tcpv6_seq(const __be32 *saddr, const __be32 *daddr, __be16 sport, __be16 dport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/secure_seq.c (ffffffff81a903b0)
Location: net/core/secure_seq.c:74
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_seq
```
**Symbols:**

```
ffffffff81a903b0-ffffffff81a90483: secure_tcpv6_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u32 secure_tcpv6_seq(const __be32 *saddr, const __be32 *daddr, __be16 sport, __be16 dport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/secure_seq.c (ffffffff81c06240)
Location: net/core/secure_seq.c:76
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_seq
```
**Symbols:**

```
ffffffff81c06240-ffffffff81c06334: secure_tcpv6_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u32 secure_tcpv6_seq(const __be32 *saddr, const __be32 *daddr, __be16 sport, __be16 dport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/secure_seq.c (ffffffff81db5b70)
Location: net/core/secure_seq.c:76
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_seq
```
**Symbols:**

```
ffffffff81db5b70-ffffffff81db5c64: secure_tcpv6_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u32 secure_tcpv6_seq(const __be32 *saddr, const __be32 *daddr, __be16 sport, __be16 dport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/secure_seq.c (ffffffff81e26140)
Location: net/core/secure_seq.c:76
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_seq
```
**Symbols:**

```
ffffffff81e26140-ffffffff81e26234: secure_tcpv6_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u32 secure_tcpv6_seq(const __be32 *saddr, const __be32 *daddr, __be16 sport, __be16 dport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/secure_seq.c (ffffffff81ee40d0)
Location: net/core/secure_seq.c:76
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_seq
```
**Symbols:**

```
ffffffff81ee40d0-ffffffff81ee41c4: secure_tcpv6_seq (STB_GLOBAL)
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
u32 secure_tcpv6_seq(const __be32 *saddr, const __be32 *daddr, __be16 sport, __be16 dport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/secure_seq.c (ffff800010bc2730)
Location: net/core/secure_seq.c:75
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_seq
```
**Symbols:**

```
ffff800010bc2730-ffff800010bc2828: secure_tcpv6_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u32 secure_tcpv6_seq(const __be32 *saddr, const __be32 *daddr, __be16 sport, __be16 dport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/secure_seq.c (c0cddab8)
Location: net/core/secure_seq.c:75
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_seq
```
**Symbols:**

```
c0cddab8-c0cddbb4: secure_tcpv6_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u32 secure_tcpv6_seq(const __be32 *saddr, const __be32 *daddr, __be16 sport, __be16 dport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/secure_seq.c (c000000000c9c640)
Location: net/core/secure_seq.c:75
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_seq
```
**Symbols:**

```
c000000000c9c640-c000000000c9c77c: secure_tcpv6_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u32 secure_tcpv6_seq(const __be32 *saddr, const __be32 *daddr, __be16 sport, __be16 dport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/secure_seq.c (ffffffe00074f5b6)
Location: net/core/secure_seq.c:75
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_seq
```
**Symbols:**

```
ffffffe00074f5b6-ffffffe00074f6a2: secure_tcpv6_seq (STB_GLOBAL)
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
u32 secure_tcpv6_seq(const __be32 *saddr, const __be32 *daddr, __be16 sport, __be16 dport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/secure_seq.c (ffffffff818c64a0)
Location: net/core/secure_seq.c:75
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_seq
```
**Symbols:**

```
ffffffff818c64a0-ffffffff818c6574: secure_tcpv6_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u32 secure_tcpv6_seq(const __be32 *saddr, const __be32 *daddr, __be16 sport, __be16 dport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/secure_seq.c (ffffffff818803e0)
Location: net/core/secure_seq.c:75
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_seq
```
**Symbols:**

```
ffffffff818803e0-ffffffff818804b4: secure_tcpv6_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u32 secure_tcpv6_seq(const __be32 *saddr, const __be32 *daddr, __be16 sport, __be16 dport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/secure_seq.c (ffffffff819174a0)
Location: net/core/secure_seq.c:75
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_seq
```
**Symbols:**

```
ffffffff819174a0-ffffffff81917574: secure_tcpv6_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u32 secure_tcpv6_seq(const __be32 *saddr, const __be32 *daddr, __be16 sport, __be16 dport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/secure_seq.c (ffffffff819386b0)
Location: net/core/secure_seq.c:75
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_seq
```
**Symbols:**

```
ffffffff819386b0-ffffffff81938784: secure_tcpv6_seq (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
