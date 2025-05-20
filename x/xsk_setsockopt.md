# Function: <code>xsk_setsockopt</code>

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
int xsk_setsockopt(struct socket *sock, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff819cb900)
Location: net/xdp/xsk.c:484
Inline: False
```
**Symbols:**

```
ffffffff819cb900-ffffffff819cbac9: xsk_setsockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int xsk_setsockopt(struct socket *sock, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81a04b50)
Location: net/xdp/xsk.c:497
Inline: False
```
**Symbols:**

```
ffffffff81a04b50-ffffffff81a04d1e: xsk_setsockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int xsk_setsockopt(struct socket *sock, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81a73ff0)
Location: net/xdp/xsk.c:523
Inline: False
```
**Symbols:**

```
ffffffff81a73ff0-ffffffff81a741fd: xsk_setsockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int xsk_setsockopt(struct socket *sock, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81aaabd0)
Location: net/xdp/xsk.c:733
Inline: False
```
**Symbols:**

```
ffffffff81aaabd0-ffffffff81aaae53: xsk_setsockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int xsk_setsockopt(struct socket *sock, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81ba7c80)
Location: net/xdp/xsk.c:700
Inline: False
```
**Symbols:**

```
ffffffff81ba7c80-ffffffff81ba8004: xsk_setsockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int xsk_setsockopt(struct socket *sock, int level, int optname, sockptr_t optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81bb78c0)
Location: net/xdp/xsk.c:920
Inline: False
```
**Symbols:**

```
ffffffff81bb78c0-ffffffff81bb7c4f: xsk_setsockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int xsk_setsockopt(struct socket *sock, int level, int optname, sockptr_t optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81ba6a40)
Location: net/xdp/xsk.c:1013
Inline: False
```
**Symbols:**

```
ffffffff81ba6a40-ffffffff81ba6dcc: xsk_setsockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int xsk_setsockopt(struct socket *sock, int level, int optname, sockptr_t optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81c745b0)
Location: net/xdp/xsk.c:1013
Inline: False
```
**Symbols:**

```
ffffffff81c745b0-ffffffff81c7493c: xsk_setsockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int xsk_setsockopt(struct socket *sock, int level, int optname, sockptr_t optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81e18720)
Location: net/xdp/xsk.c:1042
Inline: False
```
**Symbols:**

```
ffffffff81e18720-ffffffff81e18adf: xsk_setsockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int xsk_setsockopt(struct socket *sock, int level, int optname, sockptr_t optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81fef980)
Location: net/xdp/xsk.c:1052
Inline: False
```
**Symbols:**

```
ffffffff81fef980-ffffffff81fefd3b: xsk_setsockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int xsk_setsockopt(struct socket *sock, int level, int optname, sockptr_t optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff8206bb20)
Location: net/xdp/xsk.c:1058
Inline: False
```
**Symbols:**

```
ffffffff8206bb20-ffffffff8206bedb: xsk_setsockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int xsk_setsockopt(struct socket *sock, int level, int optname, sockptr_t optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff8213f6f0)
Location: net/xdp/xsk.c:1342
Inline: False
```
**Symbols:**

```
ffffffff8213f6f0-ffffffff8213faab: xsk_setsockopt (STB_LOCAL)
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
int xsk_setsockopt(struct socket *sock, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffff800010d7f748)
Location: net/xdp/xsk.c:733
Inline: False
```
**Symbols:**

```
ffff800010d7f748-ffff800010d7f9ac: xsk_setsockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int xsk_setsockopt(struct socket *sock, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (c0e7a3bc)
Location: net/xdp/xsk.c:733
Inline: False
```
**Symbols:**

```
c0e7a3bc-c0e7a6cc: xsk_setsockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int xsk_setsockopt(struct socket *sock, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (c000000000ebde00)
Location: net/xdp/xsk.c:733
Inline: False
```
**Symbols:**

```
c000000000ebde00-c000000000ebe174: xsk_setsockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int xsk_setsockopt(struct socket *sock, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffe0008abb56)
Location: net/xdp/xsk.c:733
Inline: False
```
**Symbols:**

```
ffffffe0008abb56-ffffffe0008abd56: xsk_setsockopt (STB_LOCAL)
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
int xsk_setsockopt(struct socket *sock, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81a49f60)
Location: net/xdp/xsk.c:733
Inline: False
```
**Symbols:**

```
ffffffff81a49f60-ffffffff81a4a1e3: xsk_setsockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int xsk_setsockopt(struct socket *sock, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81a06b50)
Location: net/xdp/xsk.c:733
Inline: False
```
**Symbols:**

```
ffffffff81a06b50-ffffffff81a06dd3: xsk_setsockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int xsk_setsockopt(struct socket *sock, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81ab5e10)
Location: net/xdp/xsk.c:733
Inline: False
```
**Symbols:**

```
ffffffff81ab5e10-ffffffff81ab6093: xsk_setsockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int xsk_setsockopt(struct socket *sock, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81ac2020)
Location: net/xdp/xsk.c:733
Inline: False
```
**Symbols:**

```
ffffffff81ac2020-ffffffff81ac22a3: xsk_setsockopt (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>char *optval</code> ➡️ <code>sockptr_t optval</code>
</li>
</ul>
</details>
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
