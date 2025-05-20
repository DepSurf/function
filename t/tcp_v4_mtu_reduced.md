# Function: <code>tcp_v4_mtu_reduced</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void tcp_v4_mtu_reduced(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff8177cc40)
Location: net/ipv4/tcp_ipv4.c:272
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
**Symbols:**

```
ffffffff8177cc40-ffffffff8177ccec: tcp_v4_mtu_reduced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void tcp_v4_mtu_reduced(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff817e7cf0)
Location: net/ipv4/tcp_ipv4.c:271
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
**Symbols:**

```
ffffffff817e7cf0-ffffffff817e7d9c: tcp_v4_mtu_reduced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tcp_v4_mtu_reduced(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff8181bd4a)
Location: net/ipv4/tcp_ipv4.c:270
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
**Symbols:**

```
ffffffff818198c0-ffffffff8181996c: tcp_v4_mtu_reduced.part.29 (STB_LOCAL)
ffffffff81819970-ffffffff8181998f: tcp_v4_mtu_reduced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tcp_v4_mtu_reduced(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff8183c409)
Location: net/ipv4/tcp_ipv4.c:282
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
**Symbols:**

```
ffffffff81839b10-ffffffff81839bbc: tcp_v4_mtu_reduced.part.28 (STB_LOCAL)
ffffffff81839bc0-ffffffff81839be0: tcp_v4_mtu_reduced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tcp_v4_mtu_reduced(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff818bbb36)
Location: net/ipv4/tcp_ipv4.c:282
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
**Symbols:**

```
ffffffff818bad80-ffffffff818bae38: tcp_v4_mtu_reduced.part.24 (STB_LOCAL)
ffffffff818bae40-ffffffff818bae60: tcp_v4_mtu_reduced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tcp_v4_mtu_reduced(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81911560)
Location: net/ipv4/tcp_ipv4.c:339
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
**Symbols:**

```
ffffffff8190f7f0-ffffffff8190f8ac: tcp_v4_mtu_reduced.part.28 (STB_LOCAL)
ffffffff8190f8b0-ffffffff8190f8cf: tcp_v4_mtu_reduced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tcp_v4_mtu_reduced(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff8193fdab)
Location: net/ipv4/tcp_ipv4.c:340
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
**Symbols:**

```
ffffffff8193dc10-ffffffff8193dccc: tcp_v4_mtu_reduced.part.35 (STB_LOCAL)
ffffffff8193dcd0-ffffffff8193dcef: tcp_v4_mtu_reduced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tcp_v4_mtu_reduced(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff819a42a6)
Location: net/ipv4/tcp_ipv4.c:335
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
**Symbols:**

```
ffffffff819a2030-ffffffff819a20e9: tcp_v4_mtu_reduced.part.0 (STB_LOCAL)
ffffffff819a20f0-ffffffff819a210f: tcp_v4_mtu_reduced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tcp_v4_mtu_reduced(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff819daec6)
Location: net/ipv4/tcp_ipv4.c:338
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
**Symbols:**

```
ffffffff819d7a60-ffffffff819d7b19: tcp_v4_mtu_reduced.part.0 (STB_LOCAL)
ffffffff819d7b20-ffffffff819d7b3f: tcp_v4_mtu_reduced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tcp_v4_mtu_reduced(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81ac80b7)
Location: net/ipv4/tcp_ipv4.c:336
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
**Symbols:**

```
ffffffff81ac5120-ffffffff81ac51d9: tcp_v4_mtu_reduced.part.0 (STB_LOCAL)
ffffffff81ac51e0-ffffffff81ac51ff: tcp_v4_mtu_reduced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tcp_v4_mtu_reduced(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81ad3f17)
Location: net/ipv4/tcp_ipv4.c:337
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
**Symbols:**

```
ffffffff81ad0ab0-ffffffff81ad0b69: tcp_v4_mtu_reduced.part.0 (STB_LOCAL)
ffffffff81ad0b70-ffffffff81ad0b8f: tcp_v4_mtu_reduced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void tcp_v4_mtu_reduced(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81abcfb0)
Location: net/ipv4/tcp_ipv4.c:337
Inline: True
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
**Symbols:**

```
ffffffff81abcfb0-ffffffff81abd0cc: tcp_v4_mtu_reduced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tcp_v4_mtu_reduced(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81b79e72)
Location: net/ipv4/tcp_ipv4.c:337
Inline: True
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
**Symbols:**

```
ffffffff81d3b6c1-ffffffff81d3b6db: tcp_v4_mtu_reduced.cold (STB_LOCAL)
ffffffff81b79e40-ffffffff81b79f68: tcp_v4_mtu_reduced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tcp_v4_mtu_reduced(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81d0a140)
Location: net/ipv4/tcp_ipv4.c:338
Inline: True
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
**Symbols:**

```
ffffffff81f07f91-ffffffff81f07fab: tcp_v4_mtu_reduced.cold (STB_LOCAL)
ffffffff81d0a100-ffffffff81d0a23d: tcp_v4_mtu_reduced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tcp_v4_mtu_reduced(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81ecf5a0)
Location: net/ipv4/tcp_ipv4.c:347
Inline: True
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
**Symbols:**

```
ffffffff820afa3a-ffffffff820afa54: tcp_v4_mtu_reduced.cold (STB_LOCAL)
ffffffff81ecf560-ffffffff81ecf69d: tcp_v4_mtu_reduced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tcp_v4_mtu_reduced(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81f2e25c)
Location: net/ipv4/tcp_ipv4.c:348
Inline: True
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
**Symbols:**

```
ffffffff82130db6-ffffffff82130dcf: tcp_v4_mtu_reduced.cold (STB_LOCAL)
ffffffff81f2e220-ffffffff81f2e359: tcp_v4_mtu_reduced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tcp_v4_mtu_reduced(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81ff30ba)
Location: net/ipv4/tcp_ipv4.c:350
Inline: True
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
**Symbols:**

```
ffffffff822125c0-ffffffff822125d9: tcp_v4_mtu_reduced.cold (STB_LOCAL)
ffffffff81ff3080-ffffffff81ff31b8: tcp_v4_mtu_reduced (STB_GLOBAL)
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
void tcp_v4_mtu_reduced(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffff800010c8e25c)
Location: net/ipv4/tcp_ipv4.c:338
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
**Symbols:**

```
ffff800010c8a938-ffff800010c8aa1c: tcp_v4_mtu_reduced.part.0 (STB_LOCAL)
ffff800010c8aa20-ffff800010c8aa5c: tcp_v4_mtu_reduced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tcp_v4_mtu_reduced(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_ipv4.c (c0d9d098)
Location: net/ipv4/tcp_ipv4.c:338
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
**Symbols:**

```
c0d9ba2c-c0d9baf8: tcp_v4_mtu_reduced.part.0 (STB_LOCAL)
c0d9baf8-c0d9bb28: tcp_v4_mtu_reduced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tcp_v4_mtu_reduced(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_ipv4.c (c000000000d9cc6c)
Location: net/ipv4/tcp_ipv4.c:338
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
**Symbols:**

```
c000000000d99140-c000000000d99290: tcp_v4_mtu_reduced.part.0 (STB_LOCAL)
c000000000d99290-c000000000d992b8: tcp_v4_mtu_reduced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tcp_v4_mtu_reduced(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffe0007ee67e)
Location: net/ipv4/tcp_ipv4.c:338
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
**Symbols:**

```
ffffffe0007ebb44-ffffffe0007ebc14: tcp_v4_mtu_reduced.part.0 (STB_LOCAL)
ffffffe0007ebc14-ffffffe0007ebc4e: tcp_v4_mtu_reduced (STB_GLOBAL)
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
void tcp_v4_mtu_reduced(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff8197ad36)
Location: net/ipv4/tcp_ipv4.c:338
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
**Symbols:**

```
ffffffff819778d0-ffffffff81977989: tcp_v4_mtu_reduced.part.0 (STB_LOCAL)
ffffffff81977990-ffffffff819779af: tcp_v4_mtu_reduced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tcp_v4_mtu_reduced(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff819347f6)
Location: net/ipv4/tcp_ipv4.c:338
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
**Symbols:**

```
ffffffff81931390-ffffffff81931449: tcp_v4_mtu_reduced.part.0 (STB_LOCAL)
ffffffff81931450-ffffffff8193146f: tcp_v4_mtu_reduced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tcp_v4_mtu_reduced(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff819e5506)
Location: net/ipv4/tcp_ipv4.c:338
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
**Symbols:**

```
ffffffff819e20a0-ffffffff819e2159: tcp_v4_mtu_reduced.part.0 (STB_LOCAL)
ffffffff819e2160-ffffffff819e217f: tcp_v4_mtu_reduced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tcp_v4_mtu_reduced(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff819ef1b4)
Location: net/ipv4/tcp_ipv4.c:338
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
**Symbols:**

```
ffffffff819ebdf0-ffffffff819ebea9: tcp_v4_mtu_reduced.part.0 (STB_LOCAL)
ffffffff819ebeb0-ffffffff819ebecf: tcp_v4_mtu_reduced (STB_GLOBAL)
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
