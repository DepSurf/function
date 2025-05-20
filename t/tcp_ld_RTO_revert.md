# Function: <code>tcp_ld_RTO_revert</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tcp_ld_RTO_revert(struct sock *sk, u32 seq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81ac7ed2)
Location: net/ipv4/tcp_ipv4.c:407
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
**Symbols:**

```
ffffffff81ac4f80-ffffffff81ac50dc: tcp_ld_RTO_revert.part.0 (STB_LOCAL)
ffffffff81ac50e0-ffffffff81ac5115: tcp_ld_RTO_revert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tcp_ld_RTO_revert(struct sock *sk, u32 seq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81ad3d32)
Location: net/ipv4/tcp_ipv4.c:408
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
**Symbols:**

```
ffffffff81ad0910-ffffffff81ad0a6c: tcp_ld_RTO_revert.part.0 (STB_LOCAL)
ffffffff81ad0a70-ffffffff81ad0aa5: tcp_ld_RTO_revert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tcp_ld_RTO_revert(struct sock *sk, u32 seq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81abedf4)
Location: net/ipv4/tcp_ipv4.c:408
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
**Symbols:**

```
ffffffff81abb9f0-ffffffff81abbb49: tcp_ld_RTO_revert.part.0 (STB_LOCAL)
ffffffff81abbb50-ffffffff81abbb85: tcp_ld_RTO_revert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tcp_ld_RTO_revert(struct sock *sk, u32 seq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81b7c934)
Location: net/ipv4/tcp_ipv4.c:408
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
**Symbols:**

```
ffffffff81b78bb0-ffffffff81b78d1c: tcp_ld_RTO_revert.part.0 (STB_LOCAL)
ffffffff81d3b64c-ffffffff81d3b671: tcp_ld_RTO_revert.part.0.cold (STB_LOCAL)
ffffffff81b78d20-ffffffff81b78d55: tcp_ld_RTO_revert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tcp_ld_RTO_revert(struct sock *sk, u32 seq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81d0c897)
Location: net/ipv4/tcp_ipv4.c:409
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
**Symbols:**

```
ffffffff81d089d0-ffffffff81d08b5d: tcp_ld_RTO_revert.part.0 (STB_LOCAL)
ffffffff81f07f2c-ffffffff81f07f4d: tcp_ld_RTO_revert.part.0.cold (STB_LOCAL)
ffffffff81d08b60-ffffffff81d08ba9: tcp_ld_RTO_revert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tcp_ld_RTO_revert(struct sock *sk, u32 seq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81ed22cc)
Location: net/ipv4/tcp_ipv4.c:418
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
**Symbols:**

```
ffffffff81ecdb10-ffffffff81ecdc9d: tcp_ld_RTO_revert.part.0 (STB_LOCAL)
ffffffff820af9d5-ffffffff820af9f6: tcp_ld_RTO_revert.part.0.cold (STB_LOCAL)
ffffffff81ecdcb0-ffffffff81ecdcf9: tcp_ld_RTO_revert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tcp_ld_RTO_revert(struct sock *sk, u32 seq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81f30fec)
Location: net/ipv4/tcp_ipv4.c:419
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
**Symbols:**

```
ffffffff81f2c7e0-ffffffff81f2c973: tcp_ld_RTO_revert.part.0 (STB_LOCAL)
ffffffff82130d51-ffffffff82130d72: tcp_ld_RTO_revert.part.0.cold (STB_LOCAL)
ffffffff81f2c990-ffffffff81f2c9d9: tcp_ld_RTO_revert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tcp_ld_RTO_revert(struct sock *sk, u32 seq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81ff6f46)
Location: net/ipv4/tcp_ipv4.c:421
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
**Symbols:**

```
ffffffff81ff16f0-ffffffff81ff1883: tcp_ld_RTO_revert.part.0 (STB_LOCAL)
ffffffff82212549-ffffffff8221256a: tcp_ld_RTO_revert.part.0.cold (STB_LOCAL)
ffffffff81ff18a0-ffffffff81ff18e9: tcp_ld_RTO_revert (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
