# Function: <code>tcp_v6_get_syncookie</code>

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
u16 tcp_v6_get_syncookie(struct sock *sk, struct ipv6hdr *iph, struct tcphdr *th, u32 *cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff81a71560)
Location: net/ipv6/tcp_ipv6.c:1073
Inline: False
Direct callers:
  - net/core/filter.c:bpf_tcp_gen_syncookie
```
**Symbols:**

```
ffffffff81a71560-ffffffff81a7163a: tcp_v6_get_syncookie (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u16 tcp_v6_get_syncookie(struct sock *sk, struct ipv6hdr *iph, struct tcphdr *th, u32 *cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff81b6ae50)
Location: net/ipv6/tcp_ipv6.c:1139
Inline: False
Direct callers:
  - net/core/filter.c:bpf_tcp_gen_syncookie
```
**Symbols:**

```
ffffffff81b6ae50-ffffffff81b6af2a: tcp_v6_get_syncookie (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u16 tcp_v6_get_syncookie(struct sock *sk, struct ipv6hdr *iph, struct tcphdr *th, u32 *cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff81b79910)
Location: net/ipv6/tcp_ipv6.c:1155
Inline: False
Direct callers:
  - net/core/filter.c:bpf_tcp_gen_syncookie
```
**Symbols:**

```
ffffffff81b79910-ffffffff81b799f1: tcp_v6_get_syncookie (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u16 tcp_v6_get_syncookie(struct sock *sk, struct ipv6hdr *iph, struct tcphdr *th, u32 *cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff81b68430)
Location: net/ipv6/tcp_ipv6.c:1182
Inline: False
Direct callers:
  - net/core/filter.c:bpf_tcp_gen_syncookie
```
**Symbols:**

```
ffffffff81b68430-ffffffff81b68511: tcp_v6_get_syncookie (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u16 tcp_v6_get_syncookie(struct sock *sk, struct ipv6hdr *iph, struct tcphdr *th, u32 *cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff81c300f0)
Location: net/ipv6/tcp_ipv6.c:1185
Inline: False
Direct callers:
  - net/core/filter.c:bpf_tcp_gen_syncookie
```
**Symbols:**

```
ffffffff81c300f0-ffffffff81c301d1: tcp_v6_get_syncookie (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u16 tcp_v6_get_syncookie(struct sock *sk, struct ipv6hdr *iph, struct tcphdr *th, u32 *cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff81dcd4d0)
Location: net/ipv6/tcp_ipv6.c:1136
Inline: False
Direct callers:
  - net/core/filter.c:bpf_tcp_gen_syncookie
```
**Symbols:**

```
ffffffff81dcd4d0-ffffffff81dcd5c5: tcp_v6_get_syncookie (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u16 tcp_v6_get_syncookie(struct sock *sk, struct ipv6hdr *iph, struct tcphdr *th, u32 *cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff81f9e5c0)
Location: net/ipv6/tcp_ipv6.c:1150
Inline: False
Direct callers:
  - net/core/filter.c:bpf_tcp_gen_syncookie
```
**Symbols:**

```
ffffffff81f9e5c0-ffffffff81f9e6b5: tcp_v6_get_syncookie (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u16 tcp_v6_get_syncookie(struct sock *sk, struct ipv6hdr *iph, struct tcphdr *th, u32 *cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff81fff080)
Location: net/ipv6/tcp_ipv6.c:1148
Inline: False
Direct callers:
  - net/core/filter.c:bpf_tcp_gen_syncookie
```
**Symbols:**

```
ffffffff81fff080-ffffffff81fff175: tcp_v6_get_syncookie (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u16 tcp_v6_get_syncookie(struct sock *sk, struct ipv6hdr *iph, struct tcphdr *th, u32 *cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff820cdd90)
Location: net/ipv6/tcp_ipv6.c:1300
Inline: False
Direct callers:
  - net/core/filter.c:bpf_tcp_gen_syncookie
```
**Symbols:**

```
ffffffff820cdd90-ffffffff820cde85: tcp_v6_get_syncookie (STB_GLOBAL)
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
u16 tcp_v6_get_syncookie(struct sock *sk, struct ipv6hdr *iph, struct tcphdr *th, u32 *cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffff800010d39dd8)
Location: net/ipv6/tcp_ipv6.c:1073
Inline: False
Direct callers:
  - net/core/filter.c:bpf_tcp_gen_syncookie
```
**Symbols:**

```
ffff800010d39dd8-ffff800010d39ed4: tcp_v6_get_syncookie (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u16 tcp_v6_get_syncookie(struct sock *sk, struct ipv6hdr *iph, struct tcphdr *th, u32 *cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (c0e3c478)
Location: net/ipv6/tcp_ipv6.c:1073
Inline: False
Direct callers:
  - net/core/filter.c:bpf_tcp_gen_syncookie
```
**Symbols:**

```
c0e3c478-c0e3c570: tcp_v6_get_syncookie (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u16 tcp_v6_get_syncookie(struct sock *sk, struct ipv6hdr *iph, struct tcphdr *th, u32 *cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (c000000000e6d070)
Location: net/ipv6/tcp_ipv6.c:1073
Inline: False
Direct callers:
  - net/core/filter.c:bpf_tcp_gen_syncookie
```
**Symbols:**

```
c000000000e6d070-c000000000e6d1a4: tcp_v6_get_syncookie (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u16 tcp_v6_get_syncookie(struct sock *sk, struct ipv6hdr *iph, struct tcphdr *th, u32 *cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffe000876c1c)
Location: net/ipv6/tcp_ipv6.c:1073
Inline: False
Direct callers:
  - net/core/filter.c:bpf_tcp_gen_syncookie
```
**Symbols:**

```
ffffffe000876c1c-ffffffe000876cd0: tcp_v6_get_syncookie (STB_GLOBAL)
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
u16 tcp_v6_get_syncookie(struct sock *sk, struct ipv6hdr *iph, struct tcphdr *th, u32 *cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff81a10bf0)
Location: net/ipv6/tcp_ipv6.c:1073
Inline: False
Direct callers:
  - net/core/filter.c:bpf_tcp_gen_syncookie
```
**Symbols:**

```
ffffffff81a10bf0-ffffffff81a10cca: tcp_v6_get_syncookie (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u16 tcp_v6_get_syncookie(struct sock *sk, struct ipv6hdr *iph, struct tcphdr *th, u32 *cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff819cd9b0)
Location: net/ipv6/tcp_ipv6.c:1073
Inline: False
Direct callers:
  - net/core/filter.c:bpf_tcp_gen_syncookie
```
**Symbols:**

```
ffffffff819cd9b0-ffffffff819cda8a: tcp_v6_get_syncookie (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u16 tcp_v6_get_syncookie(struct sock *sk, struct ipv6hdr *iph, struct tcphdr *th, u32 *cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff81a7b670)
Location: net/ipv6/tcp_ipv6.c:1073
Inline: False
Direct callers:
  - net/core/filter.c:bpf_tcp_gen_syncookie
```
**Symbols:**

```
ffffffff81a7b670-ffffffff81a7b74a: tcp_v6_get_syncookie (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u16 tcp_v6_get_syncookie(struct sock *sk, struct ipv6hdr *iph, struct tcphdr *th, u32 *cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff81a87ec0)
Location: net/ipv6/tcp_ipv6.c:1073
Inline: False
Direct callers:
  - net/core/filter.c:bpf_tcp_gen_syncookie
```
**Symbols:**

```
ffffffff81a87ec0-ffffffff81a87f9a: tcp_v6_get_syncookie (STB_GLOBAL)
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
