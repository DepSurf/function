# Function: <code>udp_lib_unhash</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void udp_lib_unhash(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff817867e0)
Location: net/ipv4/udp.c:1394
Inline: False
```
**Symbols:**

```
ffffffff817867e0-ffffffff81786925: udp_lib_unhash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void udp_lib_unhash(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff817f3d50)
Location: net/ipv4/udp.c:1377
Inline: False
```
**Symbols:**

```
ffffffff817f3d50-ffffffff817f3e9b: udp_lib_unhash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void udp_lib_unhash(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81824f60)
Location: net/ipv4/udp.c:1549
Inline: False
```
**Symbols:**

```
ffffffff81824f60-ffffffff818250ab: udp_lib_unhash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void udp_lib_unhash(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81847560)
Location: net/ipv4/udp.c:1700
Inline: True
```
**Symbols:**

```
ffffffff81847560-ffffffff818476b1: udp_lib_unhash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void udp_lib_unhash(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff818c6fc0)
Location: net/ipv4/udp.c:1707
Inline: True
```
**Symbols:**

```
ffffffff818c6fc0-ffffffff818c711d: udp_lib_unhash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void udp_lib_unhash(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff8191dab0)
Location: net/ipv4/udp.c:1790
Inline: True
```
**Symbols:**

```
ffffffff8191dab0-ffffffff8191dc0c: udp_lib_unhash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void udp_lib_unhash(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff8194c030)
Location: net/ipv4/udp.c:1862
Inline: True
```
**Symbols:**

```
ffffffff8194c030-ffffffff8194c18c: udp_lib_unhash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void udp_lib_unhash(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/udp.c (ffffffff819b0840)
Location: net/ipv4/udp.c:1848
Inline: True
```
**Symbols:**

```
ffffffff819b3580-ffffffff819b3593: udp_lib_unhash.cold (STB_LOCAL)
ffffffff819b0820-ffffffff819b0973: udp_lib_unhash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void udp_lib_unhash(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff819e74b0)
Location: net/ipv4/udp.c:1884
Inline: True
```
**Symbols:**

```
ffffffff819e74b0-ffffffff819e760d: udp_lib_unhash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void udp_lib_unhash(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/udp.c (ffffffff81ad4910)
Location: net/ipv4/udp.c:1893
Inline: True
```
**Symbols:**

```
ffffffff81ad4910-ffffffff81ad4a67: udp_lib_unhash.part.0 (STB_LOCAL)
ffffffff81ad4a70-ffffffff81ad4a88: udp_lib_unhash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void udp_lib_unhash(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/udp.c (ffffffff81ae0e50)
Location: net/ipv4/udp.c:1943
Inline: True
```
**Symbols:**

```
ffffffff81ae0e50-ffffffff81ae0fa7: udp_lib_unhash.part.0 (STB_LOCAL)
ffffffff81ae0fb0-ffffffff81ae0fc8: udp_lib_unhash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void udp_lib_unhash(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/udp.c (ffffffff81acc170)
Location: net/ipv4/udp.c:1992
Inline: True
```
**Symbols:**

```
ffffffff81acc170-ffffffff81acc2c7: udp_lib_unhash.part.0 (STB_LOCAL)
ffffffff81acc2d0-ffffffff81acc2e8: udp_lib_unhash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void udp_lib_unhash(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/udp.c (ffffffff81b8aa00)
Location: net/ipv4/udp.c:2004
Inline: True
```
**Symbols:**

```
ffffffff81b8aa00-ffffffff81b8ab57: udp_lib_unhash.part.0 (STB_LOCAL)
ffffffff81b8ab60-ffffffff81b8ab78: udp_lib_unhash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void udp_lib_unhash(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81d197e0)
Location: net/ipv4/udp.c:2003
Inline: True
```
**Symbols:**

```
ffffffff81d197e0-ffffffff81d19963: udp_lib_unhash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void udp_lib_unhash(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81ee0130)
Location: net/ipv4/udp.c:2005
Inline: False
```
**Symbols:**

```
ffffffff81ee0130-ffffffff81ee02ca: udp_lib_unhash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void udp_lib_unhash(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81f3f5f0)
Location: net/ipv4/udp.c:1977
Inline: False
```
**Symbols:**

```
ffffffff81f3f5f0-ffffffff81f3f7a9: udp_lib_unhash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void udp_lib_unhash(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff82005520)
Location: net/ipv4/udp.c:1948
Inline: False
```
**Symbols:**

```
ffffffff82005520-ffffffff820056d9: udp_lib_unhash (STB_GLOBAL)
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
void udp_lib_unhash(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffff800010c9b568)
Location: net/ipv4/udp.c:1884
Inline: True
```
**Symbols:**

```
ffff800010c9b568-ffff800010c9b738: udp_lib_unhash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void udp_lib_unhash(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (c0da8354)
Location: net/ipv4/udp.c:1884
Inline: True
```
**Symbols:**

```
c0da8354-c0da84b0: udp_lib_unhash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void udp_lib_unhash(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (c000000000dac800)
Location: net/ipv4/udp.c:1884
Inline: True
```
**Symbols:**

```
c000000000dac800-c000000000dac9f0: udp_lib_unhash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void udp_lib_unhash(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffe0007f9972)
Location: net/ipv4/udp.c:1884
Inline: True
```
**Symbols:**

```
ffffffe0007f9972-ffffffe0007f9ab8: udp_lib_unhash (STB_GLOBAL)
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
void udp_lib_unhash(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81987320)
Location: net/ipv4/udp.c:1884
Inline: True
```
**Symbols:**

```
ffffffff81987320-ffffffff8198747d: udp_lib_unhash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void udp_lib_unhash(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81940de0)
Location: net/ipv4/udp.c:1884
Inline: True
```
**Symbols:**

```
ffffffff81940de0-ffffffff81940f3d: udp_lib_unhash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void udp_lib_unhash(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff819f1af0)
Location: net/ipv4/udp.c:1884
Inline: True
```
**Symbols:**

```
ffffffff819f1af0-ffffffff819f1c4d: udp_lib_unhash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void udp_lib_unhash(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff819fb3e0)
Location: net/ipv4/udp.c:1884
Inline: True
```
**Symbols:**

```
ffffffff819fb3e0-ffffffff819fb53a: udp_lib_unhash (STB_GLOBAL)
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
