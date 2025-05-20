# Function: <code>tcp_md5_do_lookup_exact</code>

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
struct tcp_md5sig_key *tcp_md5_do_lookup_exact(const struct sock *sk, const union tcp_md5_addr *addr, int family, u8 prefixlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81838b50)
Location: net/ipv4/tcp_ipv4.c:946
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
```
**Symbols:**

```
ffffffff81838b50-ffffffff81838bd2: tcp_md5_do_lookup_exact (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct tcp_md5sig_key *tcp_md5_do_lookup_exact(const struct sock *sk, const union tcp_md5_addr *addr, int family, u8 prefixlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff818b82a0)
Location: net/ipv4/tcp_ipv4.c:950
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
```
**Symbols:**

```
ffffffff818b82a0-ffffffff818b8322: tcp_md5_do_lookup_exact (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct tcp_md5sig_key *tcp_md5_do_lookup_exact(const struct sock *sk, const union tcp_md5_addr *addr, int family, u8 prefixlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff8190dc00)
Location: net/ipv4/tcp_ipv4.c:1012
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
```
**Symbols:**

```
ffffffff8190dc00-ffffffff8190dc82: tcp_md5_do_lookup_exact (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct tcp_md5sig_key *tcp_md5_do_lookup_exact(const struct sock *sk, const union tcp_md5_addr *addr, int family, u8 prefixlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff8193bff0)
Location: net/ipv4/tcp_ipv4.c:1022
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
```
**Symbols:**

```
ffffffff8193bff0-ffffffff8193c072: tcp_md5_do_lookup_exact (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct tcp_md5sig_key *tcp_md5_do_lookup_exact(const struct sock *sk, const union tcp_md5_addr *addr, int family, u8 prefixlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff819a0420)
Location: net/ipv4/tcp_ipv4.c:1023
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
```
**Symbols:**

```
ffffffff819a0420-ffffffff819a04a1: tcp_md5_do_lookup_exact (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct tcp_md5sig_key *tcp_md5_do_lookup_exact(const struct sock *sk, const union tcp_md5_addr *addr, int family, u8 prefixlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff819d6fe0)
Location: net/ipv4/tcp_ipv4.c:1030
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
```
**Symbols:**

```
ffffffff819d6fe0-ffffffff819d7067: tcp_md5_do_lookup_exact (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct tcp_md5sig_key *tcp_md5_do_lookup_exact(const struct sock *sk, const union tcp_md5_addr *addr, int family, u8 prefixlen, int l3index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81ac3a10)
Location: net/ipv4/tcp_ipv4.c:1057
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_add
```
**Symbols:**

```
ffffffff81ac3a10-ffffffff81ac3aa2: tcp_md5_do_lookup_exact (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct tcp_md5sig_key *tcp_md5_do_lookup_exact(const struct sock *sk, const union tcp_md5_addr *addr, int family, u8 prefixlen, int l3index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81acf4a0)
Location: net/ipv4/tcp_ipv4.c:1070
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_add
```
**Symbols:**

```
ffffffff81acf4a0-ffffffff81acf532: tcp_md5_do_lookup_exact (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct tcp_md5sig_key *tcp_md5_do_lookup_exact(const struct sock *sk, const union tcp_md5_addr *addr, int family, u8 prefixlen, int l3index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81aba5f0)
Location: net/ipv4/tcp_ipv4.c:1085
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_add
```
**Symbols:**

```
ffffffff81aba5f0-ffffffff81aba682: tcp_md5_do_lookup_exact (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct tcp_md5sig_key *tcp_md5_do_lookup_exact(const struct sock *sk, const union tcp_md5_addr *addr, int family, u8 prefixlen, int l3index, u8 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81b778d0)
Location: net/ipv4/tcp_ipv4.c:1098
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_add
```
**Symbols:**

```
ffffffff81b778d0-ffffffff81b7796f: tcp_md5_do_lookup_exact (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct tcp_md5sig_key *tcp_md5_do_lookup_exact(const struct sock *sk, const union tcp_md5_addr *addr, int family, u8 prefixlen, int l3index, u8 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81d07480)
Location: net/ipv4/tcp_ipv4.c:1106
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_add
```
**Symbols:**

```
ffffffff81d07480-ffffffff81d07527: tcp_md5_do_lookup_exact (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct tcp_md5sig_key *tcp_md5_do_lookup_exact(const struct sock *sk, const union tcp_md5_addr *addr, int family, u8 prefixlen, int l3index, u8 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81ecc600)
Location: net/ipv4/tcp_ipv4.c:1117
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_add
```
**Symbols:**

```
ffffffff81ecc600-ffffffff81ecc6a7: tcp_md5_do_lookup_exact (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct tcp_md5sig_key *tcp_md5_do_lookup_exact(const struct sock *sk, const union tcp_md5_addr *addr, int family, u8 prefixlen, int l3index, u8 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81f2b2e0)
Location: net/ipv4/tcp_ipv4.c:1124
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_add
```
**Symbols:**

```
ffffffff81f2b2e0-ffffffff81f2b387: tcp_md5_do_lookup_exact (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct tcp_md5sig_key *tcp_md5_do_lookup_exact(const struct sock *sk, const union tcp_ao_addr *addr, int family, u8 prefixlen, int l3index, u8 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81feffc0)
Location: net/ipv4/tcp_ipv4.c:1284
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_add
```
**Symbols:**

```
ffffffff81feffc0-ffffffff81ff0067: tcp_md5_do_lookup_exact (STB_LOCAL)
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
struct tcp_md5sig_key *tcp_md5_do_lookup_exact(const struct sock *sk, const union tcp_md5_addr *addr, int family, u8 prefixlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffff800010c89ff8)
Location: net/ipv4/tcp_ipv4.c:1030
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
```
**Symbols:**

```
ffff800010c89ff8-ffff800010c8a0a4: tcp_md5_do_lookup_exact (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct tcp_md5sig_key *tcp_md5_do_lookup_exact(const struct sock *sk, const union tcp_md5_addr *addr, int family, u8 prefixlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (c0d99140)
Location: net/ipv4/tcp_ipv4.c:1030
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
```
**Symbols:**

```
c0d99140-c0d991c8: tcp_md5_do_lookup_exact (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct tcp_md5sig_key *tcp_md5_do_lookup_exact(const struct sock *sk, const union tcp_md5_addr *addr, int family, u8 prefixlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (c000000000d97740)
Location: net/ipv4/tcp_ipv4.c:1030
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
```
**Symbols:**

```
c000000000d97740-c000000000d97848: tcp_md5_do_lookup_exact (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct tcp_md5sig_key *tcp_md5_do_lookup_exact(const struct sock *sk, const union tcp_md5_addr *addr, int family, u8 prefixlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffe0007eb05e)
Location: net/ipv4/tcp_ipv4.c:1030
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
```
**Symbols:**

```
ffffffe0007eb05e-ffffffe0007eb0e2: tcp_md5_do_lookup_exact (STB_LOCAL)
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
struct tcp_md5sig_key *tcp_md5_do_lookup_exact(const struct sock *sk, const union tcp_md5_addr *addr, int family, u8 prefixlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81976e50)
Location: net/ipv4/tcp_ipv4.c:1030
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
```
**Symbols:**

```
ffffffff81976e50-ffffffff81976ed7: tcp_md5_do_lookup_exact (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct tcp_md5sig_key *tcp_md5_do_lookup_exact(const struct sock *sk, const union tcp_md5_addr *addr, int family, u8 prefixlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81930910)
Location: net/ipv4/tcp_ipv4.c:1030
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
```
**Symbols:**

```
ffffffff81930910-ffffffff81930997: tcp_md5_do_lookup_exact (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct tcp_md5sig_key *tcp_md5_do_lookup_exact(const struct sock *sk, const union tcp_md5_addr *addr, int family, u8 prefixlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff819e1620)
Location: net/ipv4/tcp_ipv4.c:1030
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
```
**Symbols:**

```
ffffffff819e1620-ffffffff819e16a7: tcp_md5_do_lookup_exact (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct tcp_md5sig_key *tcp_md5_do_lookup_exact(const struct sock *sk, const union tcp_md5_addr *addr, int family, u8 prefixlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff819eb350)
Location: net/ipv4/tcp_ipv4.c:1030
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
```
**Symbols:**

```
ffffffff819eb350-ffffffff819eb3d7: tcp_md5_do_lookup_exact (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int l3index</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u8 flags</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const union tcp_md5_addr *addr</code> ➡️ <code>const union tcp_ao_addr *addr</code>
</li>
</ul>
</details>
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
