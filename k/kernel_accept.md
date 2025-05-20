# Function: <code>kernel_accept</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int kernel_accept(struct socket *sock, struct socket **newsock, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff816fde40)
Location: net/socket.c:3181
Inline: True
```
**Symbols:**

```
ffffffff816fde40-ffffffff816fdedc: kernel_accept (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int kernel_accept(struct socket *sock, struct socket **newsock, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81764950)
Location: net/socket.c:3183
Inline: True
```
**Symbols:**

```
ffffffff81764950-ffffffff817649ec: kernel_accept (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int kernel_accept(struct socket *sock, struct socket **newsock, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff817919d0)
Location: net/socket.c:3231
Inline: True
```
**Symbols:**

```
ffffffff817919d0-ffffffff81791a6c: kernel_accept (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int kernel_accept(struct socket *sock, struct socket **newsock, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff817ae8e0)
Location: net/socket.c:3281
Inline: False
```
**Symbols:**

```
ffffffff817ae8e0-ffffffff817ae981: kernel_accept (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int kernel_accept(struct socket *sock, struct socket **newsock, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818269c0)
Location: net/socket.c:3283
Inline: False
```
**Symbols:**

```
ffffffff818269c0-ffffffff81826a67: kernel_accept (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int kernel_accept(struct socket *sock, struct socket **newsock, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81870030)
Location: net/socket.c:3249
Inline: False
```
**Symbols:**

```
ffffffff81870030-ffffffff818700d5: kernel_accept (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int kernel_accept(struct socket *sock, struct socket **newsock, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81890c00)
Location: net/socket.c:3315
Inline: False
```
**Symbols:**

```
ffffffff81890c00-ffffffff81890ca5: kernel_accept (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int kernel_accept(struct socket *sock, struct socket **newsock, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818dab10)
Location: net/socket.c:3527
Inline: False
```
**Symbols:**

```
ffffffff818dab10-ffffffff818dabb4: kernel_accept (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int kernel_accept(struct socket *sock, struct socket **newsock, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8190cc60)
Location: net/socket.c:3608
Inline: False
```
**Symbols:**

```
ffffffff8190cc60-ffffffff8190cd04: kernel_accept (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int kernel_accept(struct socket *sock, struct socket **newsock, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819de9d0)
Location: net/socket.c:3552
Inline: False
```
**Symbols:**

```
ffffffff819de9d0-ffffffff819dea74: kernel_accept (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int kernel_accept(struct socket *sock, struct socket **newsock, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819de410)
Location: net/socket.c:3544
Inline: False
```
**Symbols:**

```
ffffffff819de410-ffffffff819de4b4: kernel_accept (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int kernel_accept(struct socket *sock, struct socket **newsock, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819c4420)
Location: net/socket.c:3530
Inline: False
```
**Symbols:**

```
ffffffff819c4420-ffffffff819c44c4: kernel_accept (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int kernel_accept(struct socket *sock, struct socket **newsock, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81a73490)
Location: net/socket.c:3415
Inline: False
```
**Symbols:**

```
ffffffff81a73490-ffffffff81a73534: kernel_accept (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int kernel_accept(struct socket *sock, struct socket **newsock, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81be5f90)
Location: net/socket.c:3475
Inline: False
```
**Symbols:**

```
ffffffff81be5f90-ffffffff81be604d: kernel_accept (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int kernel_accept(struct socket *sock, struct socket **newsock, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81d921d0)
Location: net/socket.c:3463
Inline: False
```
**Symbols:**

```
ffffffff81d921d0-ffffffff81d9228d: kernel_accept (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int kernel_accept(struct socket *sock, struct socket **newsock, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81e00590)
Location: net/socket.c:3504
Inline: False
```
**Symbols:**

```
ffffffff81e00590-ffffffff81e00647: kernel_accept (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int kernel_accept(struct socket *sock, struct socket **newsock, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81ebcaf0)
Location: net/socket.c:3579
Inline: False
```
**Symbols:**

```
ffffffff81ebcaf0-ffffffff81ebcba7: kernel_accept (STB_GLOBAL)
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
int kernel_accept(struct socket *sock, struct socket **newsock, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffff800010ba1b98)
Location: net/socket.c:3608
Inline: False
```
**Symbols:**

```
ffff800010ba1b98-ffff800010ba1c50: kernel_accept (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int kernel_accept(struct socket *sock, struct socket **newsock, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (c0cc3bc8)
Location: net/socket.c:3608
Inline: False
```
**Symbols:**

```
c0cc3bc8-c0cc3c70: kernel_accept (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int kernel_accept(struct socket *sock, struct socket **newsock, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (c000000000c76320)
Location: net/socket.c:3608
Inline: False
```
**Symbols:**

```
c000000000c76320-c000000000c76438: kernel_accept (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int kernel_accept(struct socket *sock, struct socket **newsock, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffe000739c72)
Location: net/socket.c:3608
Inline: False
```
**Symbols:**

```
ffffffe000739c72-ffffffe000739d0a: kernel_accept (STB_GLOBAL)
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
int kernel_accept(struct socket *sock, struct socket **newsock, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818acc60)
Location: net/socket.c:3608
Inline: False
```
**Symbols:**

```
ffffffff818acc60-ffffffff818acd04: kernel_accept (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int kernel_accept(struct socket *sock, struct socket **newsock, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81866bb0)
Location: net/socket.c:3608
Inline: False
```
**Symbols:**

```
ffffffff81866bb0-ffffffff81866c54: kernel_accept (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int kernel_accept(struct socket *sock, struct socket **newsock, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818fdc60)
Location: net/socket.c:3608
Inline: False
```
**Symbols:**

```
ffffffff818fdc60-ffffffff818fdd04: kernel_accept (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int kernel_accept(struct socket *sock, struct socket **newsock, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8191ecf0)
Location: net/socket.c:3608
Inline: False
```
**Symbols:**

```
ffffffff8191ecf0-ffffffff8191ed94: kernel_accept (STB_GLOBAL)
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
