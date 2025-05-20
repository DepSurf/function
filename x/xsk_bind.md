# Function: <code>xsk_bind</code>

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
int xsk_bind(struct socket *sock, struct sockaddr *addr, int addr_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff819cbb60)
Location: net/xdp/xsk.c:378
Inline: False
```
**Symbols:**

```
ffffffff819cbb60-ffffffff819cbe4a: xsk_bind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int xsk_bind(struct socket *sock, struct sockaddr *addr, int addr_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81a04db0)
Location: net/xdp/xsk.c:396
Inline: False
```
**Symbols:**

```
ffffffff81a04db0-ffffffff81a0505c: xsk_bind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int xsk_bind(struct socket *sock, struct sockaddr *addr, int addr_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81a74290)
Location: net/xdp/xsk.c:415
Inline: False
```
**Symbols:**

```
ffffffff81a74290-ffffffff81a745b8: xsk_bind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int xsk_bind(struct socket *sock, struct sockaddr *addr, int addr_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81aab420)
Location: net/xdp/xsk.c:609
Inline: False
```
**Symbols:**

```
ffffffff81aab420-ffffffff81aab7d1: xsk_bind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int xsk_bind(struct socket *sock, struct sockaddr *addr, int addr_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81ba6a40)
Location: net/xdp/xsk.c:585
Inline: False
```
**Symbols:**

```
ffffffff81ba6a40-ffffffff81ba6d11: xsk_bind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int xsk_bind(struct socket *sock, struct sockaddr *addr, int addr_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81bb5c70)
Location: net/xdp/xsk.c:764
Inline: False
```
**Symbols:**

```
ffffffff81bb5c70-ffffffff81bb60ab: xsk_bind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int xsk_bind(struct socket *sock, struct sockaddr *addr, int addr_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81ba4c50)
Location: net/xdp/xsk.c:857
Inline: False
```
**Symbols:**

```
ffffffff81ba4c50-ffffffff81ba508f: xsk_bind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int xsk_bind(struct socket *sock, struct sockaddr *addr, int addr_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xdp/xsk.c (0)
Location: net/xdp/xsk.c:857
Inline: False
```
**Symbols:**

```
ffffffff81c727e0-ffffffff81c72c2b: xsk_bind (STB_LOCAL)
ffffffff81d42fb1-ffffffff81d42fcd: xsk_bind.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int xsk_bind(struct socket *sock, struct sockaddr *addr, int addr_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xdp/xsk.c (0)
Location: net/xdp/xsk.c:873
Inline: False
```
**Symbols:**

```
ffffffff81e16680-ffffffff81e16b10: xsk_bind (STB_LOCAL)
ffffffff81f0f959-ffffffff81f0f975: xsk_bind.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int xsk_bind(struct socket *sock, struct sockaddr *addr, int addr_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xdp/xsk.c (0)
Location: net/xdp/xsk.c:883
Inline: False
```
**Symbols:**

```
ffffffff81fed710-ffffffff81fedb9c: xsk_bind (STB_LOCAL)
ffffffff820b5cef-ffffffff820b5d0b: xsk_bind.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int xsk_bind(struct socket *sock, struct sockaddr *addr, int addr_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xdp/xsk.c (0)
Location: net/xdp/xsk.c:883
Inline: False
```
**Symbols:**

```
ffffffff82069860-ffffffff82069d00: xsk_bind (STB_LOCAL)
ffffffff82137236-ffffffff82137252: xsk_bind.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int xsk_bind(struct socket *sock, struct sockaddr *addr, int addr_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xdp/xsk.c (0)
Location: net/xdp/xsk.c:1158
Inline: False
```
**Symbols:**

```
ffffffff8213cc00-ffffffff8213d0b1: xsk_bind (STB_LOCAL)
ffffffff82219098-ffffffff822190bc: xsk_bind.cold (STB_LOCAL)
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
int xsk_bind(struct socket *sock, struct sockaddr *addr, int addr_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffff800010d7e998)
Location: net/xdp/xsk.c:609
Inline: False
```
**Symbols:**

```
ffff800010d7e998-ffff800010d7ecc0: xsk_bind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int xsk_bind(struct socket *sock, struct sockaddr *addr, int addr_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (c0e78cd4)
Location: net/xdp/xsk.c:609
Inline: False
```
**Symbols:**

```
c0e78cd4-c0e78ff8: xsk_bind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int xsk_bind(struct socket *sock, struct sockaddr *addr, int addr_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (c000000000ebe180)
Location: net/xdp/xsk.c:609
Inline: False
```
**Symbols:**

```
c000000000ebe180-c000000000ebe5bc: xsk_bind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int xsk_bind(struct socket *sock, struct sockaddr *addr, int addr_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffe0008abd56)
Location: net/xdp/xsk.c:609
Inline: False
```
**Symbols:**

```
ffffffe0008abd56-ffffffe0008ac00a: xsk_bind (STB_LOCAL)
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
int xsk_bind(struct socket *sock, struct sockaddr *addr, int addr_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81a4a7b0)
Location: net/xdp/xsk.c:609
Inline: False
```
**Symbols:**

```
ffffffff81a4a7b0-ffffffff81a4ab61: xsk_bind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int xsk_bind(struct socket *sock, struct sockaddr *addr, int addr_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81a073a0)
Location: net/xdp/xsk.c:609
Inline: False
```
**Symbols:**

```
ffffffff81a073a0-ffffffff81a07751: xsk_bind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int xsk_bind(struct socket *sock, struct sockaddr *addr, int addr_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81ab6660)
Location: net/xdp/xsk.c:609
Inline: False
```
**Symbols:**

```
ffffffff81ab6660-ffffffff81ab6a11: xsk_bind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int xsk_bind(struct socket *sock, struct sockaddr *addr, int addr_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81ac26c0)
Location: net/xdp/xsk.c:609
Inline: False
```
**Symbols:**

```
ffffffff81ac26c0-ffffffff81ac2a71: xsk_bind (STB_LOCAL)
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
