# Function: <code>udp_lib_get_port</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int udp_lib_get_port(struct sock *sk, short unsigned int snum, int (*saddr_comp)(const struct sock *, const struct sock *), unsigned int hash2_nulladdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81786140)
Location: net/ipv4/udp.c:208
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_v4_get_port
  - net/ipv6/udp.c:udp_v6_get_port
```
**Symbols:**

```
ffffffff81786140-ffffffff817864a8: udp_lib_get_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int udp_lib_get_port(struct sock *sk, short unsigned int snum, int (*saddr_comp)(const struct sock *, const struct sock *, bool), unsigned int hash2_nulladdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff817f47d0)
Location: net/ipv4/udp.c:239
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_v4_get_port
  - net/ipv6/udp.c:udp_v6_get_port
```
**Symbols:**

```
ffffffff817f47d0-ffffffff817f4d21: udp_lib_get_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int udp_lib_get_port(struct sock *sk, short unsigned int snum, int (*saddr_comp)(const struct sock *, const struct sock *, bool), unsigned int hash2_nulladdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff818258a0)
Location: net/ipv4/udp.c:240
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_v4_get_port
  - net/ipv6/udp.c:udp_v6_get_port
```
**Symbols:**

```
ffffffff818258a0-ffffffff81825e00: udp_lib_get_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int udp_lib_get_port(struct sock *sk, short unsigned int snum, unsigned int hash2_nulladdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff818478d0)
Location: net/ipv4/udp.c:248
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_v4_get_port
  - net/ipv6/udp.c:udp_v6_get_port
```
**Symbols:**

```
ffffffff818478d0-ffffffff81847dcb: udp_lib_get_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int udp_lib_get_port(struct sock *sk, short unsigned int snum, unsigned int hash2_nulladdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff818c7330)
Location: net/ipv4/udp.c:245
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_v4_get_port
  - net/ipv6/udp.c:udp_v6_get_port
```
**Symbols:**

```
ffffffff818c7330-ffffffff818c7825: udp_lib_get_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int udp_lib_get_port(struct sock *sk, short unsigned int snum, unsigned int hash2_nulladdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff8191e510)
Location: net/ipv4/udp.c:239
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_v4_get_port
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
```
**Symbols:**

```
ffffffff8191e510-ffffffff8191ea3b: udp_lib_get_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int udp_lib_get_port(struct sock *sk, short unsigned int snum, unsigned int hash2_nulladdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff8194d310)
Location: net/ipv4/udp.c:242
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_v4_get_port
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
```
**Symbols:**

```
ffffffff8194d310-ffffffff8194d851: udp_lib_get_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int udp_lib_get_port(struct sock *sk, short unsigned int snum, unsigned int hash2_nulladdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff819b1ac0)
Location: net/ipv4/udp.c:226
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_v4_get_port
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
```
**Symbols:**

```
ffffffff819b1ac0-ffffffff819b2050: udp_lib_get_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int udp_lib_get_port(struct sock *sk, short unsigned int snum, unsigned int hash2_nulladdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff819e8840)
Location: net/ipv4/udp.c:226
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_v4_get_port
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
```
**Symbols:**

```
ffffffff819e8840-ffffffff819e8dd6: udp_lib_get_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int udp_lib_get_port(struct sock *sk, short unsigned int snum, unsigned int hash2_nulladdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81ad6bd0)
Location: net/ipv4/udp.c:229
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_v4_get_port
  - net/ipv6/udp.c:udp_v6_get_port
```
**Symbols:**

```
ffffffff81ad6bd0-ffffffff81ad70bf: udp_lib_get_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int udp_lib_get_port(struct sock *sk, short unsigned int snum, unsigned int hash2_nulladdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81ae31b0)
Location: net/ipv4/udp.c:230
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_v4_get_port
  - net/ipv6/udp.c:udp_v6_get_port
```
**Symbols:**

```
ffffffff81ae31b0-ffffffff81ae369f: udp_lib_get_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int udp_lib_get_port(struct sock *sk, short unsigned int snum, unsigned int hash2_nulladdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81ace0c0)
Location: net/ipv4/udp.c:230
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_v4_get_port
  - net/ipv6/udp.c:udp_v6_get_port
```
**Symbols:**

```
ffffffff81ace0c0-ffffffff81ace6a8: udp_lib_get_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int udp_lib_get_port(struct sock *sk, short unsigned int snum, unsigned int hash2_nulladdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/udp.c (0)
Location: net/ipv4/udp.c:230
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_v4_get_port
  - net/ipv6/udp.c:udp_v6_get_port
```
**Symbols:**

```
ffffffff81d3c058-ffffffff81d3c098: udp_lib_get_port.cold (STB_LOCAL)
ffffffff81b8ca80-ffffffff81b8d075: udp_lib_get_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int udp_lib_get_port(struct sock *sk, short unsigned int snum, unsigned int hash2_nulladdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/udp.c (0)
Location: net/ipv4/udp.c:230
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_v4_get_port
  - net/ipv6/udp.c:udp_v6_get_port
```
**Symbols:**

```
ffffffff81f08812-ffffffff81f0883c: udp_lib_get_port.cold (STB_LOCAL)
ffffffff81d1b110-ffffffff81d1b6b1: udp_lib_get_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int udp_lib_get_port(struct sock *sk, short unsigned int snum, unsigned int hash2_nulladdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/udp.c (0)
Location: net/ipv4/udp.c:237
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_v4_get_port
  - net/ipv6/udp.c:udp_v6_get_port
```
**Symbols:**

```
ffffffff820b02ba-ffffffff820b02e8: udp_lib_get_port.cold (STB_LOCAL)
ffffffff81ee1af0-ffffffff81ee209d: udp_lib_get_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int udp_lib_get_port(struct sock *sk, short unsigned int snum, unsigned int hash2_nulladdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/udp.c (0)
Location: net/ipv4/udp.c:239
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_v4_get_port
  - net/ipv6/udp.c:udp_v6_get_port
```
**Symbols:**

```
ffffffff82131553-ffffffff82131581: udp_lib_get_port.cold (STB_LOCAL)
ffffffff81f41510-ffffffff81f41adc: udp_lib_get_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int udp_lib_get_port(struct sock *sk, short unsigned int snum, unsigned int hash2_nulladdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/udp.c (0)
Location: net/ipv4/udp.c:239
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_v4_get_port
  - net/ipv6/udp.c:udp_v6_get_port
```
**Symbols:**

```
ffffffff82212e52-ffffffff82212e80: udp_lib_get_port.cold (STB_LOCAL)
ffffffff82007170-ffffffff8200773c: udp_lib_get_port (STB_GLOBAL)
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
int udp_lib_get_port(struct sock *sk, short unsigned int snum, unsigned int hash2_nulladdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffff800010c9bd28)
Location: net/ipv4/udp.c:226
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_v4_get_port
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
```
**Symbols:**

```
ffff800010c9bd28-ffff800010c9c328: udp_lib_get_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int udp_lib_get_port(struct sock *sk, short unsigned int snum, unsigned int hash2_nulladdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (c0da84b0)
Location: net/ipv4/udp.c:226
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_v4_get_port
  - net/ipv6/udp.c:udp_v6_get_port
```
**Symbols:**

```
c0da84b0-c0da8a14: udp_lib_get_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int udp_lib_get_port(struct sock *sk, short unsigned int snum, unsigned int hash2_nulladdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (c000000000dadd90)
Location: net/ipv4/udp.c:226
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_v4_get_port
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
```
**Symbols:**

```
c000000000dadd90-c000000000dae460: udp_lib_get_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int udp_lib_get_port(struct sock *sk, short unsigned int snum, unsigned int hash2_nulladdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffe0007fadf4)
Location: net/ipv4/udp.c:226
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_v4_get_port
  - net/ipv6/udp.c:udp_v6_get_port
```
**Symbols:**

```
ffffffe0007fadf4-ffffffe0007fb2c4: udp_lib_get_port (STB_GLOBAL)
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
int udp_lib_get_port(struct sock *sk, short unsigned int snum, unsigned int hash2_nulladdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff819886b0)
Location: net/ipv4/udp.c:226
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_v4_get_port
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
```
**Symbols:**

```
ffffffff819886b0-ffffffff81988c46: udp_lib_get_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int udp_lib_get_port(struct sock *sk, short unsigned int snum, unsigned int hash2_nulladdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81942170)
Location: net/ipv4/udp.c:226
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_v4_get_port
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
```
**Symbols:**

```
ffffffff81942170-ffffffff81942706: udp_lib_get_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int udp_lib_get_port(struct sock *sk, short unsigned int snum, unsigned int hash2_nulladdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff819f2e80)
Location: net/ipv4/udp.c:226
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_v4_get_port
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
```
**Symbols:**

```
ffffffff819f2e80-ffffffff819f3416: udp_lib_get_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int udp_lib_get_port(struct sock *sk, short unsigned int snum, unsigned int hash2_nulladdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff819fb750)
Location: net/ipv4/udp.c:226
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_v4_get_port
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
```
**Symbols:**

```
ffffffff819fb750-ffffffff819fbcec: udp_lib_get_port (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int (*saddr_comp)(const struct sock *, const struct sock *)</code> ➡️ <code>int (*saddr_comp)(const struct sock *, const struct sock *, bool)</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int (*saddr_comp)(const struct sock *, const struct sock *, bool)</code>
</li>
<li>
<b>Param reordered. </b>
<code>sk, snum, saddr_comp, hash2_nulladdr</code> ➡️ <code>sk, snum, hash2_nulladdr</code>
</li>
</ul>
</details>
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
