# Function: <code>__tcp_send_ack</code>

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
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __tcp_send_ack(struct sock *sk, u32 rcv_nxt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff8190c233)
Location: net/ipv4/tcp_output.c:3585
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
Direct callers:
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
```
**Symbols:**

```
ffffffff8190a7d0-ffffffff8190a8cf: __tcp_send_ack.part.46 (STB_LOCAL)
ffffffff8190a8d0-ffffffff8190a8e9: __tcp_send_ack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __tcp_send_ack(struct sock *sk, u32 rcv_nxt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff8193a503)
Location: net/ipv4/tcp_output.c:3617
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
Direct callers:
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
```
**Symbols:**

```
ffffffff81938a70-ffffffff81938b6f: __tcp_send_ack.part.48 (STB_LOCAL)
ffffffff81938b70-ffffffff81938b89: __tcp_send_ack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __tcp_send_ack(struct sock *sk, u32 rcv_nxt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff8199e851)
Location: net/ipv4/tcp_output.c:3652
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
Direct callers:
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
```
**Symbols:**

```
ffffffff8199b9b0-ffffffff8199bac1: __tcp_send_ack.part.0 (STB_LOCAL)
ffffffff8199bad0-ffffffff8199bae9: __tcp_send_ack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __tcp_send_ack(struct sock *sk, u32 rcv_nxt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff819d5361)
Location: net/ipv4/tcp_output.c:3684
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
Direct callers:
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
```
**Symbols:**

```
ffffffff819d23d0-ffffffff819d24e1: __tcp_send_ack.part.0 (STB_LOCAL)
ffffffff819d24f0-ffffffff819d2509: __tcp_send_ack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __tcp_send_ack(struct sock *sk, u32 rcv_nxt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81ac1cab)
Location: net/ipv4/tcp_output.c:3757
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
Direct callers:
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_send_ack
```
**Symbols:**

```
ffffffff81abf130-ffffffff81abf241: __tcp_send_ack.part.0 (STB_LOCAL)
ffffffff81abf250-ffffffff81abf269: __tcp_send_ack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __tcp_send_ack(struct sock *sk, u32 rcv_nxt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81acd710)
Location: net/ipv4/tcp_output.c:3936
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
Direct callers:
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_send_ack
```
**Symbols:**

```
ffffffff81acaa90-ffffffff81acac34: __tcp_send_ack.part.0 (STB_LOCAL)
ffffffff81acac40-ffffffff81acac59: __tcp_send_ack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __tcp_send_ack(struct sock *sk, u32 rcv_nxt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81ab88db)
Location: net/ipv4/tcp_output.c:3933
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
Direct callers:
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_send_ack
```
**Symbols:**

```
ffffffff81ab5a80-ffffffff81ab5c25: __tcp_send_ack.part.0 (STB_LOCAL)
ffffffff81ab5c30-ffffffff81ab5c49: __tcp_send_ack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __tcp_send_ack(struct sock *sk, u32 rcv_nxt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81b75afb)
Location: net/ipv4/tcp_output.c:3934
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
Direct callers:
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_send_ack
```
**Symbols:**

```
ffffffff81b72ac0-ffffffff81b72c75: __tcp_send_ack.part.0 (STB_LOCAL)
ffffffff81d3b2bf-ffffffff81d3b2df: __tcp_send_ack.part.0.cold (STB_LOCAL)
ffffffff81b72c80-ffffffff81b72c99: __tcp_send_ack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __tcp_send_ack(struct sock *sk, u32 rcv_nxt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81d053cc)
Location: net/ipv4/tcp_output.c:3943
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
Direct callers:
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_send_ack
```
**Symbols:**

```
ffffffff81d02180-ffffffff81d02344: __tcp_send_ack.part.0 (STB_LOCAL)
ffffffff81f07be2-ffffffff81f07c02: __tcp_send_ack.part.0.cold (STB_LOCAL)
ffffffff81d02350-ffffffff81d0237d: __tcp_send_ack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __tcp_send_ack(struct sock *sk, u32 rcv_nxt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81eca49c)
Location: net/ipv4/tcp_output.c:3945
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
Direct callers:
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_send_ack
```
**Symbols:**

```
ffffffff81ec7330-ffffffff81ec74f4: __tcp_send_ack.part.0 (STB_LOCAL)
ffffffff820af674-ffffffff820af694: __tcp_send_ack.part.0.cold (STB_LOCAL)
ffffffff81ec7510-ffffffff81ec753d: __tcp_send_ack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __tcp_send_ack(struct sock *sk, u32 rcv_nxt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81f28fdc)
Location: net/ipv4/tcp_output.c:4034
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
Direct callers:
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_send_ack
```
**Symbols:**

```
ffffffff81f25c10-ffffffff81f25dd0: __tcp_send_ack.part.0 (STB_LOCAL)
ffffffff82130a40-ffffffff82130a6f: __tcp_send_ack.part.0.cold (STB_LOCAL)
ffffffff81f25de0-ffffffff81f25e0d: __tcp_send_ack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __tcp_send_ack(struct sock *sk, u32 rcv_nxt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81fedb1f)
Location: net/ipv4/tcp_output.c:4194
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
  - net/ipv4/tcp_output.c:tcp_release_cb
Direct callers:
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_send_ack
```
**Symbols:**

```
ffffffff81fea5d0-ffffffff81fea78a: __tcp_send_ack.part.0 (STB_LOCAL)
ffffffff82212214-ffffffff82212243: __tcp_send_ack.part.0.cold (STB_LOCAL)
ffffffff81fea7a0-ffffffff81fea7cd: __tcp_send_ack (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __tcp_send_ack(struct sock *sk, u32 rcv_nxt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (ffff800010c87fa4)
Location: net/ipv4/tcp_output.c:3684
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
Direct callers:
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
```
**Symbols:**

```
ffff800010c84f68-ffff800010c85088: __tcp_send_ack.part.0 (STB_LOCAL)
ffff800010c85088-ffff800010c850cc: __tcp_send_ack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __tcp_send_ack(struct sock *sk, u32 rcv_nxt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (c0d972fc)
Location: net/ipv4/tcp_output.c:3684
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
Direct callers:
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
```
**Symbols:**

```
c0d9425c-c0d94380: __tcp_send_ack.part.0 (STB_LOCAL)
c0d94380-c0d943a8: __tcp_send_ack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __tcp_send_ack(struct sock *sk, u32 rcv_nxt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (c000000000d94dc0)
Location: net/ipv4/tcp_output.c:3684
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
Direct callers:
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
```
**Symbols:**

```
c000000000d90f80-c000000000d910f0: __tcp_send_ack.part.0 (STB_LOCAL)
c000000000d910f0-c000000000d91110: __tcp_send_ack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __tcp_send_ack(struct sock *sk, u32 rcv_nxt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffe0007e9240)
Location: net/ipv4/tcp_output.c:3684
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
Direct callers:
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
```
**Symbols:**

```
ffffffe0007e68e2-ffffffe0007e69ea: __tcp_send_ack.part.0 (STB_LOCAL)
ffffffe0007e69ea-ffffffe0007e6a2a: __tcp_send_ack (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __tcp_send_ack(struct sock *sk, u32 rcv_nxt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff819751d1)
Location: net/ipv4/tcp_output.c:3684
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
Direct callers:
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
```
**Symbols:**

```
ffffffff81972240-ffffffff81972351: __tcp_send_ack.part.0 (STB_LOCAL)
ffffffff81972360-ffffffff81972379: __tcp_send_ack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __tcp_send_ack(struct sock *sk, u32 rcv_nxt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff8192ec91)
Location: net/ipv4/tcp_output.c:3684
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
Direct callers:
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
```
**Symbols:**

```
ffffffff8192bd10-ffffffff8192be21: __tcp_send_ack.part.0 (STB_LOCAL)
ffffffff8192be30-ffffffff8192be49: __tcp_send_ack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __tcp_send_ack(struct sock *sk, u32 rcv_nxt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff819df9a1)
Location: net/ipv4/tcp_output.c:3684
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
Direct callers:
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
```
**Symbols:**

```
ffffffff819dca10-ffffffff819dcb21: __tcp_send_ack.part.0 (STB_LOCAL)
ffffffff819dcb30-ffffffff819dcb49: __tcp_send_ack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __tcp_send_ack(struct sock *sk, u32 rcv_nxt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff819e9657)
Location: net/ipv4/tcp_output.c:3684
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
Direct callers:
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
```
**Symbols:**

```
ffffffff819e6690-ffffffff819e67a4: __tcp_send_ack.part.0 (STB_LOCAL)
ffffffff819e67b0-ffffffff819e67c9: __tcp_send_ack (STB_GLOBAL)
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
