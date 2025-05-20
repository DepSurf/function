# Function: <code>tcp_v4_get_syncookie</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u16 tcp_v4_get_syncookie(struct sock *sk, struct iphdr *iph, struct tcphdr *th, u32 *cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff819db1c0)
Location: net/ipv4/tcp_ipv4.c:1525
Inline: False
Direct callers:
  - net/core/filter.c:bpf_tcp_gen_syncookie
```
**Symbols:**

```
ffffffff819db1c0-ffffffff819db29a: tcp_v4_get_syncookie (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u16 tcp_v4_get_syncookie(struct sock *sk, struct iphdr *iph, struct tcphdr *th, u32 *cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81ac8250)
Location: net/ipv4/tcp_ipv4.c:1602
Inline: False
Direct callers:
  - net/core/filter.c:bpf_tcp_gen_syncookie
```
**Symbols:**

```
ffffffff81ac8250-ffffffff81ac832a: tcp_v4_get_syncookie (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u16 tcp_v4_get_syncookie(struct sock *sk, struct iphdr *iph, struct tcphdr *th, u32 *cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81ad41e0)
Location: net/ipv4/tcp_ipv4.c:1637
Inline: False
Direct callers:
  - net/core/filter.c:bpf_tcp_gen_syncookie
```
**Symbols:**

```
ffffffff81ad41e0-ffffffff81ad42c1: tcp_v4_get_syncookie (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u16 tcp_v4_get_syncookie(struct sock *sk, struct iphdr *iph, struct tcphdr *th, u32 *cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81abf280)
Location: net/ipv4/tcp_ipv4.c:1652
Inline: False
Direct callers:
  - net/core/filter.c:bpf_tcp_gen_syncookie
```
**Symbols:**

```
ffffffff81abf280-ffffffff81abf361: tcp_v4_get_syncookie (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u16 tcp_v4_get_syncookie(struct sock *sk, struct iphdr *iph, struct tcphdr *th, u32 *cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81b7cdc0)
Location: net/ipv4/tcp_ipv4.c:1671
Inline: False
Direct callers:
  - net/core/filter.c:bpf_tcp_gen_syncookie
```
**Symbols:**

```
ffffffff81b7cdc0-ffffffff81b7cea1: tcp_v4_get_syncookie (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u16 tcp_v4_get_syncookie(struct sock *sk, struct iphdr *iph, struct tcphdr *th, u32 *cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81d0cce0)
Location: net/ipv4/tcp_ipv4.c:1613
Inline: False
Direct callers:
  - net/core/filter.c:bpf_tcp_gen_syncookie
```
**Symbols:**

```
ffffffff81d0cce0-ffffffff81d0cdd5: tcp_v4_get_syncookie (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u16 tcp_v4_get_syncookie(struct sock *sk, struct iphdr *iph, struct tcphdr *th, u32 *cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81ed2730)
Location: net/ipv4/tcp_ipv4.c:1675
Inline: False
Direct callers:
  - net/core/filter.c:bpf_tcp_gen_syncookie
```
**Symbols:**

```
ffffffff81ed2730-ffffffff81ed2825: tcp_v4_get_syncookie (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u16 tcp_v4_get_syncookie(struct sock *sk, struct iphdr *iph, struct tcphdr *th, u32 *cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81f31410)
Location: net/ipv4/tcp_ipv4.c:1682
Inline: False
Direct callers:
  - net/core/filter.c:bpf_tcp_gen_syncookie
```
**Symbols:**

```
ffffffff81f31410-ffffffff81f31505: tcp_v4_get_syncookie (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u16 tcp_v4_get_syncookie(struct sock *sk, struct iphdr *iph, struct tcphdr *th, u32 *cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81ff7600)
Location: net/ipv4/tcp_ipv4.c:1860
Inline: False
Direct callers:
  - net/core/filter.c:bpf_tcp_gen_syncookie
```
**Symbols:**

```
ffffffff81ff7600-ffffffff81ff76f5: tcp_v4_get_syncookie (STB_GLOBAL)
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
u16 tcp_v4_get_syncookie(struct sock *sk, struct iphdr *iph, struct tcphdr *th, u32 *cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffff800010c8e580)
Location: net/ipv4/tcp_ipv4.c:1525
Inline: False
Direct callers:
  - net/core/filter.c:bpf_tcp_gen_syncookie
```
**Symbols:**

```
ffff800010c8e580-ffff800010c8e67c: tcp_v4_get_syncookie (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u16 tcp_v4_get_syncookie(struct sock *sk, struct iphdr *iph, struct tcphdr *th, u32 *cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (c0d9d4d4)
Location: net/ipv4/tcp_ipv4.c:1525
Inline: False
Direct callers:
  - net/core/filter.c:bpf_tcp_gen_syncookie
```
**Symbols:**

```
c0d9d4d4-c0d9d5cc: tcp_v4_get_syncookie (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u16 tcp_v4_get_syncookie(struct sock *sk, struct iphdr *iph, struct tcphdr *th, u32 *cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (c000000000d9ceb0)
Location: net/ipv4/tcp_ipv4.c:1525
Inline: False
Direct callers:
  - net/core/filter.c:bpf_tcp_gen_syncookie
```
**Symbols:**

```
c000000000d9ceb0-c000000000d9cfe4: tcp_v4_get_syncookie (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u16 tcp_v4_get_syncookie(struct sock *sk, struct iphdr *iph, struct tcphdr *th, u32 *cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffe0007ee934)
Location: net/ipv4/tcp_ipv4.c:1525
Inline: False
Direct callers:
  - net/core/filter.c:bpf_tcp_gen_syncookie
```
**Symbols:**

```
ffffffe0007ee934-ffffffe0007ee9e8: tcp_v4_get_syncookie (STB_GLOBAL)
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
u16 tcp_v4_get_syncookie(struct sock *sk, struct iphdr *iph, struct tcphdr *th, u32 *cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff8197b030)
Location: net/ipv4/tcp_ipv4.c:1525
Inline: False
Direct callers:
  - net/core/filter.c:bpf_tcp_gen_syncookie
```
**Symbols:**

```
ffffffff8197b030-ffffffff8197b10a: tcp_v4_get_syncookie (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u16 tcp_v4_get_syncookie(struct sock *sk, struct iphdr *iph, struct tcphdr *th, u32 *cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81934af0)
Location: net/ipv4/tcp_ipv4.c:1525
Inline: False
Direct callers:
  - net/core/filter.c:bpf_tcp_gen_syncookie
```
**Symbols:**

```
ffffffff81934af0-ffffffff81934bca: tcp_v4_get_syncookie (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u16 tcp_v4_get_syncookie(struct sock *sk, struct iphdr *iph, struct tcphdr *th, u32 *cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff819e5800)
Location: net/ipv4/tcp_ipv4.c:1525
Inline: False
Direct callers:
  - net/core/filter.c:bpf_tcp_gen_syncookie
```
**Symbols:**

```
ffffffff819e5800-ffffffff819e58da: tcp_v4_get_syncookie (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u16 tcp_v4_get_syncookie(struct sock *sk, struct iphdr *iph, struct tcphdr *th, u32 *cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff819ef4c0)
Location: net/ipv4/tcp_ipv4.c:1525
Inline: False
Direct callers:
  - net/core/filter.c:bpf_tcp_gen_syncookie
```
**Symbols:**

```
ffffffff819ef4c0-ffffffff819ef59a: tcp_v4_get_syncookie (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
