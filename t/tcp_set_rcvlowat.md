# Function: <code>tcp_set_rcvlowat</code>

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
<summary>In <code>4.18</code>: ✅</summary>

```c
int tcp_set_rcvlowat(struct sock *sk, int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff818f6290)
Location: net/ipv4/tcp.c:1706
Inline: False
```
**Symbols:**

```
ffffffff818f6290-ffffffff818f632d: tcp_set_rcvlowat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int tcp_set_rcvlowat(struct sock *sk, int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81923e40)
Location: net/ipv4/tcp.c:1702
Inline: False
```
**Symbols:**

```
ffffffff81923e40-ffffffff81923edd: tcp_set_rcvlowat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int tcp_set_rcvlowat(struct sock *sk, int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81986610)
Location: net/ipv4/tcp.c:1692
Inline: False
```
**Symbols:**

```
ffffffff81986610-ffffffff819866ad: tcp_set_rcvlowat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int tcp_set_rcvlowat(struct sock *sk, int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff819bcd80)
Location: net/ipv4/tcp.c:1693
Inline: False
```
**Symbols:**

```
ffffffff819bcd80-ffffffff819bce1d: tcp_set_rcvlowat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tcp_set_rcvlowat(struct sock *sk, int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81aa7c40)
Location: net/ipv4/tcp.c:1700
Inline: False
```
**Symbols:**

```
ffffffff81aa7c40-ffffffff81aa7cdb: tcp_set_rcvlowat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tcp_set_rcvlowat(struct sock *sk, int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81ab21b0)
Location: net/ipv4/tcp.c:1716
Inline: False
```
**Symbols:**

```
ffffffff81ab21b0-ffffffff81ab224b: tcp_set_rcvlowat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tcp_set_rcvlowat(struct sock *sk, int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81a9d440)
Location: net/ipv4/tcp.c:1718
Inline: False
```
**Symbols:**

```
ffffffff81a9d440-ffffffff81a9d4db: tcp_set_rcvlowat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int tcp_set_rcvlowat(struct sock *sk, int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp.c (0)
Location: net/ipv4/tcp.c:1717
Inline: False
```
**Symbols:**

```
ffffffff81d3a2dd-ffffffff81d3a31d: tcp_set_rcvlowat.cold (STB_LOCAL)
ffffffff81b59300-ffffffff81b593c2: tcp_set_rcvlowat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int tcp_set_rcvlowat(struct sock *sk, int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp.c (0)
Location: net/ipv4/tcp.c:1745
Inline: False
```
**Symbols:**

```
ffffffff81f06a69-ffffffff81f06aa9: tcp_set_rcvlowat.cold (STB_LOCAL)
ffffffff81ce75a0-ffffffff81ce767a: tcp_set_rcvlowat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int tcp_set_rcvlowat(struct sock *sk, int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp.c (0)
Location: net/ipv4/tcp.c:1845
Inline: False
```
**Symbols:**

```
ffffffff820ae6bf-ffffffff820ae6ff: tcp_set_rcvlowat.cold (STB_LOCAL)
ffffffff81eaae20-ffffffff81eaaefa: tcp_set_rcvlowat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int tcp_set_rcvlowat(struct sock *sk, int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp.c (0)
Location: net/ipv4/tcp.c:1701
Inline: False
```
**Symbols:**

```
ffffffff8212fb7c-ffffffff8212fbbc: tcp_set_rcvlowat.cold (STB_LOCAL)
ffffffff81f09530-ffffffff81f0960a: tcp_set_rcvlowat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tcp_set_rcvlowat(struct sock *sk, int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81fcd820)
Location: net/ipv4/tcp.c:1703
Inline: False
```
**Symbols:**

```
ffffffff81fcd820-ffffffff81fcd8b7: tcp_set_rcvlowat (STB_GLOBAL)
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
int tcp_set_rcvlowat(struct sock *sk, int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffff800010c6f018)
Location: net/ipv4/tcp.c:1693
Inline: False
```
**Symbols:**

```
ffff800010c6f018-ffff800010c6f0c8: tcp_set_rcvlowat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tcp_set_rcvlowat(struct sock *sk, int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (c0d7dbf0)
Location: net/ipv4/tcp.c:1693
Inline: False
```
**Symbols:**

```
c0d7dbf0-c0d7dc80: tcp_set_rcvlowat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tcp_set_rcvlowat(struct sock *sk, int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (c000000000d75320)
Location: net/ipv4/tcp.c:1693
Inline: False
```
**Symbols:**

```
c000000000d75320-c000000000d75410: tcp_set_rcvlowat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tcp_set_rcvlowat(struct sock *sk, int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffe0007d3d92)
Location: net/ipv4/tcp.c:1693
Inline: False
```
**Symbols:**

```
ffffffe0007d3d92-ffffffe0007d3e40: tcp_set_rcvlowat (STB_GLOBAL)
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
int tcp_set_rcvlowat(struct sock *sk, int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff8195cbf0)
Location: net/ipv4/tcp.c:1693
Inline: False
```
**Symbols:**

```
ffffffff8195cbf0-ffffffff8195cc8d: tcp_set_rcvlowat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int tcp_set_rcvlowat(struct sock *sk, int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff819166e0)
Location: net/ipv4/tcp.c:1693
Inline: False
```
**Symbols:**

```
ffffffff819166e0-ffffffff8191677d: tcp_set_rcvlowat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int tcp_set_rcvlowat(struct sock *sk, int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff819c73c0)
Location: net/ipv4/tcp.c:1693
Inline: False
```
**Symbols:**

```
ffffffff819c73c0-ffffffff819c745d: tcp_set_rcvlowat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int tcp_set_rcvlowat(struct sock *sk, int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff819d0f10)
Location: net/ipv4/tcp.c:1693
Inline: False
```
**Symbols:**

```
ffffffff819d0f10-ffffffff819d0fad: tcp_set_rcvlowat (STB_GLOBAL)
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
