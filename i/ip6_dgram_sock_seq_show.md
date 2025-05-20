# Function: <code>ip6_dgram_sock_seq_show</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ip6_dgram_sock_seq_show(struct seq_file *seq, struct sock *sp, __u16 srcp, __u16 destp, int bucket);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/datagram.c (ffffffff817f5ad0)
Location: net/ipv6/datagram.c:962
Inline: False
Direct callers:
  - net/ipv6/udp.c:udp6_seq_show
  - net/ipv6/raw.c:raw6_seq_show
  - net/ipv6/ping.c:ping_v6_seq_show
```
**Symbols:**

```
ffffffff817f5ad0-ffffffff817f5bed: ip6_dgram_sock_seq_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void ip6_dgram_sock_seq_show(struct seq_file *seq, struct sock *sp, __u16 srcp, __u16 destp, int bucket);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/datagram.c (ffffffff81864ba0)
Location: net/ipv6/datagram.c:1012
Inline: False
Direct callers:
  - net/ipv6/udp.c:udp6_seq_show
  - net/ipv6/raw.c:raw6_seq_show
  - net/ipv6/ping.c:ping_v6_seq_show
```
**Symbols:**

```
ffffffff81864ba0-ffffffff81864ccb: ip6_dgram_sock_seq_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ip6_dgram_sock_seq_show(struct seq_file *seq, struct sock *sp, __u16 srcp, __u16 destp, int bucket);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/datagram.c (ffffffff81897280)
Location: net/ipv6/datagram.c:1024
Inline: False
Direct callers:
  - net/ipv6/udp.c:udp6_seq_show
  - net/ipv6/raw.c:raw6_seq_show
  - net/ipv6/ping.c:ping_v6_seq_show
```
**Symbols:**

```
ffffffff81897280-ffffffff818973ab: ip6_dgram_sock_seq_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void ip6_dgram_sock_seq_show(struct seq_file *seq, struct sock *sp, __u16 srcp, __u16 destp, int bucket);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/datagram.c (ffffffff818bd6e0)
Location: net/ipv6/datagram.c:1022
Inline: False
Direct callers:
  - net/ipv6/udp.c:udp6_seq_show
  - net/ipv6/raw.c:raw6_seq_show
  - net/ipv6/ping.c:ping_v6_seq_show
```
**Symbols:**

```
ffffffff818bd6e0-ffffffff818bd7be: ip6_dgram_sock_seq_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ip6_dgram_sock_seq_show(struct seq_file *seq, struct sock *sp, __u16 srcp, __u16 destp, int bucket);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/datagram.c (ffffffff81940800)
Location: net/ipv6/datagram.c:1029
Inline: False
Direct callers:
  - net/ipv6/udp.c:udp6_seq_show
  - net/ipv6/raw.c:raw6_seq_show
  - net/ipv6/ping.c:ping_v6_seq_show
```
**Symbols:**

```
ffffffff81940800-ffffffff819408de: ip6_dgram_sock_seq_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/raw.c (ffffffff8198713f)
Location: include/net/transp_v6.h:51
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_seq_show
```
```
In net/ipv6/ping.c (ffffffff819957c1)
Location: include/net/transp_v6.h:51
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_seq_show
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/raw.c (ffffffff819bda5f)
Location: include/net/transp_v6.h:50
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_seq_show
```
```
In net/ipv6/ping.c (ffffffff819cc0a1)
Location: include/net/transp_v6.h:50
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_seq_show
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/raw.c (ffffffff81a2c54f)
Location: include/net/transp_v6.h:50
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_seq_show
```
```
In net/ipv6/ping.c (ffffffff81a3ab81)
Location: include/net/transp_v6.h:50
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_seq_show
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/raw.c (ffffffff81a6308f)
Location: include/net/transp_v6.h:50
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_seq_show
```
```
In net/ipv6/ping.c (ffffffff81a71801)
Location: include/net/transp_v6.h:50
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_seq_show
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/raw.c (ffffffff81b5bb2f)
Location: include/net/transp_v6.h:50
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_seq_show
```
```
In net/ipv6/ping.c (ffffffff81b6b101)
Location: include/net/transp_v6.h:50
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_seq_show
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/raw.c (ffffffff81b6a36f)
Location: include/net/transp_v6.h:50
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_seq_show
```
```
In net/ipv6/ping.c (ffffffff81b79b81)
Location: include/net/transp_v6.h:50
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_seq_show
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/raw.c (ffffffff81b5869f)
Location: include/net/transp_v6.h:50
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_seq_show
```
```
In net/ipv6/ping.c (ffffffff81b686a1)
Location: include/net/transp_v6.h:50
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_seq_show
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/raw.c (ffffffff81c1fa2f)
Location: include/net/transp_v6.h:50
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_seq_show
```
```
In net/ipv6/ping.c (ffffffff81c30361)
Location: include/net/transp_v6.h:50
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_seq_show
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/raw.c (ffffffff81dbc6af)
Location: include/net/transp_v6.h:50
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_seq_show
```
```
In net/ipv6/ping.c (ffffffff81dcd9c1)
Location: include/net/transp_v6.h:50
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_seq_show
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/raw.c (ffffffff81f8c66f)
Location: include/net/transp_v6.h:52
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_seq_show
```
```
In net/ipv6/ping.c (ffffffff81f9eb71)
Location: include/net/transp_v6.h:52
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_seq_show
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/raw.c (ffffffff81feceef)
Location: include/net/transp_v6.h:52
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_seq_show
```
```
In net/ipv6/ping.c (ffffffff81fff631)
Location: include/net/transp_v6.h:52
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_seq_show
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/raw.c (ffffffff820baaef)
Location: include/net/transp_v6.h:50
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_seq_show
```
```
In net/ipv6/ping.c (ffffffff820ce341)
Location: include/net/transp_v6.h:50
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_seq_show
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/raw.c (ffff800010d28394)
Location: include/net/transp_v6.h:50
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_seq_show
```
```
In net/ipv6/ping.c (ffff800010d3a228)
Location: include/net/transp_v6.h:50
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_seq_show
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/raw.c (c0e2ce18)
Location: include/net/transp_v6.h:50
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_seq_show
```
```
In net/ipv6/ping.c (c0e3c758)
Location: include/net/transp_v6.h:50
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_seq_show
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/raw.c (c000000000e596c4)
Location: include/net/transp_v6.h:50
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_seq_show
```
```
In net/ipv6/ping.c (c000000000e6d424)
Location: include/net/transp_v6.h:50
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_seq_show
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/raw.c (ffffffe000869c30)
Location: include/net/transp_v6.h:50
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_seq_show
```
```
In net/ipv6/ping.c (ffffffe000876ed0)
Location: include/net/transp_v6.h:50
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_seq_show
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/raw.c (ffffffff81a0271f)
Location: include/net/transp_v6.h:50
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_seq_show
```
```
In net/ipv6/ping.c (ffffffff81a10e91)
Location: include/net/transp_v6.h:50
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_seq_show
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/raw.c (ffffffff819bf4df)
Location: include/net/transp_v6.h:50
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_seq_show
```
```
In net/ipv6/ping.c (ffffffff819cdc51)
Location: include/net/transp_v6.h:50
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_seq_show
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/raw.c (ffffffff81a6d19f)
Location: include/net/transp_v6.h:50
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_seq_show
```
```
In net/ipv6/ping.c (ffffffff81a7b911)
Location: include/net/transp_v6.h:50
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_seq_show
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/raw.c (ffffffff81a797bf)
Location: include/net/transp_v6.h:50
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_seq_show
```
```
In net/ipv6/ping.c (ffffffff81a88161)
Location: include/net/transp_v6.h:50
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_seq_show
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
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
</ul>
