# Function: <code>inet_csk_update_pmtu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct dst_entry *inet_csk_update_pmtu(struct sock *sk, u32 mtu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81764830)
Location: net/ipv4/inet_connection_sock.c:947
Inline: True
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_mtu_reduced
```
**Symbols:**

```
ffffffff81764830-ffffffff8176489c: inet_csk_update_pmtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct dst_entry *inet_csk_update_pmtu(struct sock *sk, u32 mtu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff817d0d70)
Location: net/ipv4/inet_connection_sock.c:947
Inline: True
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_mtu_reduced
```
**Symbols:**

```
ffffffff817d0d70-ffffffff817d0ddc: inet_csk_update_pmtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct dst_entry *inet_csk_update_pmtu(struct sock *sk, u32 mtu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81800c30)
Location: net/ipv4/inet_connection_sock.c:951
Inline: True
```
**Symbols:**

```
ffffffff81800c30-ffffffff81800c9c: inet_csk_update_pmtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct dst_entry *inet_csk_update_pmtu(struct sock *sk, u32 mtu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81820820)
Location: net/ipv4/inet_connection_sock.c:1077
Inline: True
```
**Symbols:**

```
ffffffff81820820-ffffffff8182088f: inet_csk_update_pmtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct dst_entry *inet_csk_update_pmtu(struct sock *sk, u32 mtu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff8189f9d0)
Location: net/ipv4/inet_connection_sock.c:1075
Inline: True
```
**Symbols:**

```
ffffffff8189f9d0-ffffffff8189fa44: inet_csk_update_pmtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct dst_entry *inet_csk_update_pmtu(struct sock *sk, u32 mtu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff818f4240)
Location: net/ipv4/inet_connection_sock.c:1070
Inline: True
```
**Symbols:**

```
ffffffff818f4240-ffffffff818f42b4: inet_csk_update_pmtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct dst_entry *inet_csk_update_pmtu(struct sock *sk, u32 mtu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81921d50)
Location: net/ipv4/inet_connection_sock.c:1088
Inline: True
```
**Symbols:**

```
ffffffff81921d50-ffffffff81921dc4: inet_csk_update_pmtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct dst_entry *inet_csk_update_pmtu(struct sock *sk, u32 mtu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81984730)
Location: net/ipv4/inet_connection_sock.c:1079
Inline: True
```
**Symbols:**

```
ffffffff81984730-ffffffff819847a9: inet_csk_update_pmtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct dst_entry *inet_csk_update_pmtu(struct sock *sk, u32 mtu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff819baee0)
Location: net/ipv4/inet_connection_sock.c:1099
Inline: True
```
**Symbols:**

```
ffffffff819baee0-ffffffff819baf5f: inet_csk_update_pmtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct dst_entry *inet_csk_update_pmtu(struct sock *sk, u32 mtu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81aa57b0)
Location: net/ipv4/inet_connection_sock.c:1130
Inline: False
```
**Symbols:**

```
ffffffff81aa57b0-ffffffff81aa582f: inet_csk_update_pmtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct dst_entry *inet_csk_update_pmtu(struct sock *sk, u32 mtu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81aafdd0)
Location: net/ipv4/inet_connection_sock.c:1099
Inline: False
```
**Symbols:**

```
ffffffff81aafdd0-ffffffff81aafe4f: inet_csk_update_pmtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct dst_entry *inet_csk_update_pmtu(struct sock *sk, u32 mtu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81a9b0e0)
Location: net/ipv4/inet_connection_sock.c:1099
Inline: False
```
**Symbols:**

```
ffffffff81a9b0e0-ffffffff81a9b15f: inet_csk_update_pmtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct dst_entry *inet_csk_update_pmtu(struct sock *sk, u32 mtu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81b56550)
Location: net/ipv4/inet_connection_sock.c:1278
Inline: False
```
**Symbols:**

```
ffffffff81b56550-ffffffff81b565cf: inet_csk_update_pmtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct dst_entry *inet_csk_update_pmtu(struct sock *sk, u32 mtu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81ce4630)
Location: net/ipv4/inet_connection_sock.c:1283
Inline: False
```
**Symbols:**

```
ffffffff81ce4630-ffffffff81ce46cf: inet_csk_update_pmtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct dst_entry *inet_csk_update_pmtu(struct sock *sk, u32 mtu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81ea75f0)
Location: net/ipv4/inet_connection_sock.c:1458
Inline: False
```
**Symbols:**

```
ffffffff81ea75f0-ffffffff81ea768f: inet_csk_update_pmtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct dst_entry *inet_csk_update_pmtu(struct sock *sk, u32 mtu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81f05d90)
Location: net/ipv4/inet_connection_sock.c:1480
Inline: False
```
**Symbols:**

```
ffffffff81f05d90-ffffffff81f05e2f: inet_csk_update_pmtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct dst_entry *inet_csk_update_pmtu(struct sock *sk, u32 mtu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81fc9f10)
Location: net/ipv4/inet_connection_sock.c:1480
Inline: False
```
**Symbols:**

```
ffffffff81fc9f10-ffffffff81fc9faf: inet_csk_update_pmtu (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct dst_entry *inet_csk_update_pmtu(struct sock *sk, u32 mtu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffff800010c6cb48)
Location: net/ipv4/inet_connection_sock.c:1099
Inline: True
```
**Symbols:**

```
ffff800010c6cb48-ffff800010c6cbd8: inet_csk_update_pmtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct dst_entry *inet_csk_update_pmtu(struct sock *sk, u32 mtu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (c0d7b864)
Location: net/ipv4/inet_connection_sock.c:1099
Inline: True
```
**Symbols:**

```
c0d7b864-c0d7b8fc: inet_csk_update_pmtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct dst_entry *inet_csk_update_pmtu(struct sock *sk, u32 mtu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (c000000000d72510)
Location: net/ipv4/inet_connection_sock.c:1099
Inline: True
```
**Symbols:**

```
c000000000d72510-c000000000d72624: inet_csk_update_pmtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct dst_entry *inet_csk_update_pmtu(struct sock *sk, u32 mtu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffe0007d2468)
Location: net/ipv4/inet_connection_sock.c:1099
Inline: True
```
**Symbols:**

```
ffffffe0007d2468-ffffffe0007d24e4: inet_csk_update_pmtu (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct dst_entry *inet_csk_update_pmtu(struct sock *sk, u32 mtu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff8195ad50)
Location: net/ipv4/inet_connection_sock.c:1099
Inline: True
```
**Symbols:**

```
ffffffff8195ad50-ffffffff8195adcf: inet_csk_update_pmtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct dst_entry *inet_csk_update_pmtu(struct sock *sk, u32 mtu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81914840)
Location: net/ipv4/inet_connection_sock.c:1099
Inline: True
```
**Symbols:**

```
ffffffff81914840-ffffffff819148bf: inet_csk_update_pmtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct dst_entry *inet_csk_update_pmtu(struct sock *sk, u32 mtu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff819c5520)
Location: net/ipv4/inet_connection_sock.c:1099
Inline: True
```
**Symbols:**

```
ffffffff819c5520-ffffffff819c559f: inet_csk_update_pmtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct dst_entry *inet_csk_update_pmtu(struct sock *sk, u32 mtu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff819cf000)
Location: net/ipv4/inet_connection_sock.c:1099
Inline: True
```
**Symbols:**

```
ffffffff819cf000-ffffffff819cf07f: inet_csk_update_pmtu (STB_GLOBAL)
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
