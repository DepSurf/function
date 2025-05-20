# Function: <code>tcp_peek_len</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int tcp_peek_len(struct socket *sock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81804c10)
Location: net/ipv4/tcp.c:1605
Inline: False
```
**Symbols:**

```
ffffffff81804c10-ffffffff81804c85: tcp_peek_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int tcp_peek_len(struct socket *sock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81824f80)
Location: net/ipv4/tcp.c:1649
Inline: False
```
**Symbols:**

```
ffffffff81824f80-ffffffff81824fe1: tcp_peek_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int tcp_peek_len(struct socket *sock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff818a38f0)
Location: net/ipv4/tcp.c:1713
Inline: False
```
**Symbols:**

```
ffffffff818a38f0-ffffffff818a3951: tcp_peek_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int tcp_peek_len(struct socket *sock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff818f8c50)
Location: net/ipv4/tcp.c:1699
Inline: False
```
**Symbols:**

```
ffffffff818f8c50-ffffffff818f8cb1: tcp_peek_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int tcp_peek_len(struct socket *sock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81926a70)
Location: net/ipv4/tcp.c:1695
Inline: False
```
**Symbols:**

```
ffffffff81926a70-ffffffff81926ad1: tcp_peek_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int tcp_peek_len(struct socket *sock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81987910)
Location: net/ipv4/tcp.c:1685
Inline: False
```
**Symbols:**

```
ffffffff81987910-ffffffff8198797d: tcp_peek_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int tcp_peek_len(struct socket *sock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff819be0e0)
Location: net/ipv4/tcp.c:1686
Inline: False
```
**Symbols:**

```
ffffffff819be0e0-ffffffff819be14d: tcp_peek_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tcp_peek_len(struct socket *sock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81aa8e80)
Location: net/ipv4/tcp.c:1693
Inline: False
```
**Symbols:**

```
ffffffff81aa8e80-ffffffff81aa8ef0: tcp_peek_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tcp_peek_len(struct socket *sock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81ab3320)
Location: net/ipv4/tcp.c:1709
Inline: False
```
**Symbols:**

```
ffffffff81ab3320-ffffffff81ab3390: tcp_peek_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tcp_peek_len(struct socket *sock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81a9e580)
Location: net/ipv4/tcp.c:1711
Inline: False
```
**Symbols:**

```
ffffffff81a9e580-ffffffff81a9e5f0: tcp_peek_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int tcp_peek_len(struct socket *sock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp.c (0)
Location: net/ipv4/tcp.c:1710
Inline: False
```
**Symbols:**

```
ffffffff81d3a3e6-ffffffff81d3a400: tcp_peek_len.cold (STB_LOCAL)
ffffffff81b5a280-ffffffff81b5a2fa: tcp_peek_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int tcp_peek_len(struct socket *sock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp.c (0)
Location: net/ipv4/tcp.c:1738
Inline: False
```
**Symbols:**

```
ffffffff81f06c77-ffffffff81f06c91: tcp_peek_len.cold (STB_LOCAL)
ffffffff81ce95a0-ffffffff81ce9623: tcp_peek_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int tcp_peek_len(struct socket *sock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp.c (0)
Location: net/ipv4/tcp.c:1838
Inline: False
```
**Symbols:**

```
ffffffff820ae7e3-ffffffff820ae7fd: tcp_peek_len.cold (STB_LOCAL)
ffffffff81eace00-ffffffff81eace92: tcp_peek_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int tcp_peek_len(struct socket *sock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp.c (0)
Location: net/ipv4/tcp.c:1694
Inline: False
```
**Symbols:**

```
ffffffff8212fc91-ffffffff8212fcaa: tcp_peek_len.cold (STB_LOCAL)
ffffffff81f0b530-ffffffff81f0b5be: tcp_peek_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int tcp_peek_len(struct socket *sock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp.c (0)
Location: net/ipv4/tcp.c:1696
Inline: False
```
**Symbols:**

```
ffffffff8221197d-ffffffff82211996: tcp_peek_len.cold (STB_LOCAL)
ffffffff81fcf070-ffffffff81fcf0fe: tcp_peek_len (STB_GLOBAL)
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
int tcp_peek_len(struct socket *sock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffff800010c6fce0)
Location: net/ipv4/tcp.c:1686
Inline: False
```
**Symbols:**

```
ffff800010c6fce0-ffff800010c6fd70: tcp_peek_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tcp_peek_len(struct socket *sock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (c0d7f0e0)
Location: net/ipv4/tcp.c:1686
Inline: False
```
**Symbols:**

```
c0d7f0e0-c0d7f16c: tcp_peek_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tcp_peek_len(struct socket *sock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (c000000000d76e40)
Location: net/ipv4/tcp.c:1686
Inline: False
```
**Symbols:**

```
c000000000d76e40-c000000000d76ee0: tcp_peek_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tcp_peek_len(struct socket *sock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffe0007d4f7c)
Location: net/ipv4/tcp.c:1686
Inline: False
```
**Symbols:**

```
ffffffe0007d4f7c-ffffffe0007d4fec: tcp_peek_len (STB_GLOBAL)
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
int tcp_peek_len(struct socket *sock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff8195df50)
Location: net/ipv4/tcp.c:1686
Inline: False
```
**Symbols:**

```
ffffffff8195df50-ffffffff8195dfbd: tcp_peek_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int tcp_peek_len(struct socket *sock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81917a40)
Location: net/ipv4/tcp.c:1686
Inline: False
```
**Symbols:**

```
ffffffff81917a40-ffffffff81917aad: tcp_peek_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int tcp_peek_len(struct socket *sock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff819c8720)
Location: net/ipv4/tcp.c:1686
Inline: False
```
**Symbols:**

```
ffffffff819c8720-ffffffff819c878d: tcp_peek_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int tcp_peek_len(struct socket *sock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff819d2270)
Location: net/ipv4/tcp.c:1686
Inline: False
```
**Symbols:**

```
ffffffff819d2270-ffffffff819d22dd: tcp_peek_len (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
