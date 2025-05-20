# Function: <code>xsk_getsockopt</code>

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
int xsk_getsockopt(struct socket *sock, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff819cb6c0)
Location: net/xdp/xsk.c:566
Inline: False
```
**Symbols:**

```
ffffffff819cb6c0-ffffffff819cb8a1: xsk_getsockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int xsk_getsockopt(struct socket *sock, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81a04910)
Location: net/xdp/xsk.c:579
Inline: False
```
**Symbols:**

```
ffffffff81a04910-ffffffff81a04af1: xsk_getsockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int xsk_getsockopt(struct socket *sock, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81a73d20)
Location: net/xdp/xsk.c:613
Inline: False
```
**Symbols:**

```
ffffffff81a73d20-ffffffff81a73f9c: xsk_getsockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int xsk_getsockopt(struct socket *sock, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81aaa800)
Location: net/xdp/xsk.c:846
Inline: False
```
**Symbols:**

```
ffffffff81aaa800-ffffffff81aaab79: xsk_getsockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int xsk_getsockopt(struct socket *sock, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81ba66c0)
Location: net/xdp/xsk.c:815
Inline: False
```
**Symbols:**

```
ffffffff81ba66c0-ffffffff81ba6a39: xsk_getsockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int xsk_getsockopt(struct socket *sock, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81bb5880)
Location: net/xdp/xsk.c:1035
Inline: False
```
**Symbols:**

```
ffffffff81bb5880-ffffffff81bb5c62: xsk_getsockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int xsk_getsockopt(struct socket *sock, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81ba4860)
Location: net/xdp/xsk.c:1128
Inline: False
```
**Symbols:**

```
ffffffff81ba4860-ffffffff81ba4c42: xsk_getsockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int xsk_getsockopt(struct socket *sock, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xdp/xsk.c (0)
Location: net/xdp/xsk.c:1128
Inline: False
```
**Symbols:**

```
ffffffff81c723f0-ffffffff81c727de: xsk_getsockopt (STB_LOCAL)
ffffffff81d42f9d-ffffffff81d42fb1: xsk_getsockopt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int xsk_getsockopt(struct socket *sock, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xdp/xsk.c (0)
Location: net/xdp/xsk.c:1157
Inline: False
```
**Symbols:**

```
ffffffff81e16220-ffffffff81e1667f: xsk_getsockopt (STB_LOCAL)
ffffffff81f0f944-ffffffff81f0f959: xsk_getsockopt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int xsk_getsockopt(struct socket *sock, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xdp/xsk.c (0)
Location: net/xdp/xsk.c:1167
Inline: False
```
**Symbols:**

```
ffffffff81fed2a0-ffffffff81fed6ff: xsk_getsockopt (STB_LOCAL)
ffffffff820b5cda-ffffffff820b5cef: xsk_getsockopt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int xsk_getsockopt(struct socket *sock, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xdp/xsk.c (0)
Location: net/xdp/xsk.c:1173
Inline: False
```
**Symbols:**

```
ffffffff82069440-ffffffff82069845: xsk_getsockopt (STB_LOCAL)
ffffffff82137221-ffffffff82137236: xsk_getsockopt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int xsk_getsockopt(struct socket *sock, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xdp/xsk.c (0)
Location: net/xdp/xsk.c:1459
Inline: False
```
**Symbols:**

```
ffffffff8213c7e0-ffffffff8213cbe5: xsk_getsockopt (STB_LOCAL)
ffffffff82219083-ffffffff82219098: xsk_getsockopt.cold (STB_LOCAL)
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
int xsk_getsockopt(struct socket *sock, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffff800010d7f9b0)
Location: net/xdp/xsk.c:846
Inline: False
```
**Symbols:**

```
ffff800010d7f9b0-ffff800010d802e8: xsk_getsockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int xsk_getsockopt(struct socket *sock, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (c0e79f98)
Location: net/xdp/xsk.c:846
Inline: False
```
**Symbols:**

```
c0e79f98-c0e7a3bc: xsk_getsockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int xsk_getsockopt(struct socket *sock, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (c000000000ebf4d0)
Location: net/xdp/xsk.c:846
Inline: False
```
**Symbols:**

```
c000000000ebf4d0-c000000000ebf9f0: xsk_getsockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int xsk_getsockopt(struct socket *sock, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffe0008ab884)
Location: net/xdp/xsk.c:846
Inline: False
```
**Symbols:**

```
ffffffe0008ab884-ffffffe0008abae6: xsk_getsockopt (STB_LOCAL)
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
int xsk_getsockopt(struct socket *sock, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81a49b90)
Location: net/xdp/xsk.c:846
Inline: False
```
**Symbols:**

```
ffffffff81a49b90-ffffffff81a49f09: xsk_getsockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int xsk_getsockopt(struct socket *sock, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81a06780)
Location: net/xdp/xsk.c:846
Inline: False
```
**Symbols:**

```
ffffffff81a06780-ffffffff81a06af9: xsk_getsockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int xsk_getsockopt(struct socket *sock, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81ab5a40)
Location: net/xdp/xsk.c:846
Inline: False
```
**Symbols:**

```
ffffffff81ab5a40-ffffffff81ab5db9: xsk_getsockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int xsk_getsockopt(struct socket *sock, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81ac1c50)
Location: net/xdp/xsk.c:846
Inline: False
```
**Symbols:**

```
ffffffff81ac1c50-ffffffff81ac1fc9: xsk_getsockopt (STB_LOCAL)
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
