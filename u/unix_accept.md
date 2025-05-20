# Function: <code>unix_accept</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int unix_accept(struct socket *sock, struct socket *newsock, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff817bdd40)
Location: net/unix/af_unix.c:1411
Inline: False
```
**Symbols:**

```
ffffffff817bdd40-ffffffff817bde9d: unix_accept (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int unix_accept(struct socket *sock, struct socket *newsock, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff8182acb0)
Location: net/unix/af_unix.c:1399
Inline: False
```
**Symbols:**

```
ffffffff8182acb0-ffffffff8182ae0d: unix_accept (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int unix_accept(struct socket *sock, struct socket *newsock, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff8185c730)
Location: net/unix/af_unix.c:1404
Inline: False
```
**Symbols:**

```
ffffffff8185c730-ffffffff8185c898: unix_accept (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int unix_accept(struct socket *sock, struct socket *newsock, int flags, bool kern);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81880eb0)
Location: net/unix/af_unix.c:1410
Inline: False
```
**Symbols:**

```
ffffffff81880eb0-ffffffff8188101a: unix_accept (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int unix_accept(struct socket *sock, struct socket *newsock, int flags, bool kern);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81902040)
Location: net/unix/af_unix.c:1411
Inline: False
```
**Symbols:**

```
ffffffff81902040-ffffffff819021aa: unix_accept (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int unix_accept(struct socket *sock, struct socket *newsock, int flags, bool kern);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff819599b0)
Location: net/unix/af_unix.c:1401
Inline: False
```
**Symbols:**

```
ffffffff819599b0-ffffffff81959b21: unix_accept (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int unix_accept(struct socket *sock, struct socket *newsock, int flags, bool kern);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff8198e910)
Location: net/unix/af_unix.c:1422
Inline: False
```
**Symbols:**

```
ffffffff8198e910-ffffffff8198ea83: unix_accept (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int unix_accept(struct socket *sock, struct socket *newsock, int flags, bool kern);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/unix/af_unix.c (0)
Location: net/unix/af_unix.c:1419
Inline: False
```
**Symbols:**

```
ffffffff819fa070-ffffffff819fa1f1: unix_accept (STB_LOCAL)
ffffffff819fd60a-ffffffff819fd61d: unix_accept.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int unix_accept(struct socket *sock, struct socket *newsock, int flags, bool kern);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81a30cf0)
Location: net/unix/af_unix.c:1431
Inline: False
```
**Symbols:**

```
ffffffff81a30cf0-ffffffff81a30e71: unix_accept (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int unix_accept(struct socket *sock, struct socket *newsock, int flags, bool kern);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81b25120)
Location: net/unix/af_unix.c:1455
Inline: False
```
**Symbols:**

```
ffffffff81b25120-ffffffff81b252b0: unix_accept (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int unix_accept(struct socket *sock, struct socket *newsock, int flags, bool kern);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81b33c90)
Location: net/unix/af_unix.c:1446
Inline: False
```
**Symbols:**

```
ffffffff81b33c90-ffffffff81b33e20: unix_accept (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int unix_accept(struct socket *sock, struct socket *newsock, int flags, bool kern);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81b21970)
Location: net/unix/af_unix.c:1448
Inline: False
```
**Symbols:**

```
ffffffff81b21970-ffffffff81b21b00: unix_accept (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int unix_accept(struct socket *sock, struct socket *newsock, int flags, bool kern);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81be6990)
Location: net/unix/af_unix.c:1540
Inline: False
```
**Symbols:**

```
ffffffff81be6990-ffffffff81be6b20: unix_accept (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int unix_accept(struct socket *sock, struct socket *newsock, int flags, bool kern);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81d7cb30)
Location: net/unix/af_unix.c:1626
Inline: False
```
**Symbols:**

```
ffffffff81d7cb30-ffffffff81d7cca4: unix_accept (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int unix_accept(struct socket *sock, struct socket *newsock, int flags, bool kern);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81f49c50)
Location: net/unix/af_unix.c:1676
Inline: False
```
**Symbols:**

```
ffffffff81f49c50-ffffffff81f49dc4: unix_accept (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int unix_accept(struct socket *sock, struct socket *newsock, int flags, bool kern);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81fa98e0)
Location: net/unix/af_unix.c:1701
Inline: False
```
**Symbols:**

```
ffffffff81fa98e0-ffffffff81fa9a63: unix_accept (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int unix_accept(struct socket *sock, struct socket *newsock, int flags, bool kern);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff82076cf0)
Location: net/unix/af_unix.c:1693
Inline: False
```
**Symbols:**

```
ffffffff82076cf0-ffffffff82076e73: unix_accept (STB_LOCAL)
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
int unix_accept(struct socket *sock, struct socket *newsock, int flags, bool kern);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffff800010cf1468)
Location: net/unix/af_unix.c:1431
Inline: False
```
**Symbols:**

```
ffff800010cf1468-ffff800010cf16cc: unix_accept (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int unix_accept(struct socket *sock, struct socket *newsock, int flags, bool kern);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (c0df7630)
Location: net/unix/af_unix.c:1431
Inline: False
```
**Symbols:**

```
c0df7630-c0df77d4: unix_accept (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int unix_accept(struct socket *sock, struct socket *newsock, int flags, bool kern);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (c000000000e14400)
Location: net/unix/af_unix.c:1431
Inline: False
```
**Symbols:**

```
c000000000e14400-c000000000e1463c: unix_accept (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int unix_accept(struct socket *sock, struct socket *newsock, int flags, bool kern);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffe00083d64c)
Location: net/unix/af_unix.c:1431
Inline: False
```
**Symbols:**

```
ffffffe00083d64c-ffffffe00083d7ca: unix_accept (STB_LOCAL)
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
int unix_accept(struct socket *sock, struct socket *newsock, int flags, bool kern);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff819d0380)
Location: net/unix/af_unix.c:1431
Inline: False
```
**Symbols:**

```
ffffffff819d0380-ffffffff819d0501: unix_accept (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int unix_accept(struct socket *sock, struct socket *newsock, int flags, bool kern);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff8198d140)
Location: net/unix/af_unix.c:1431
Inline: False
```
**Symbols:**

```
ffffffff8198d140-ffffffff8198d2c1: unix_accept (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int unix_accept(struct socket *sock, struct socket *newsock, int flags, bool kern);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81a3ae00)
Location: net/unix/af_unix.c:1431
Inline: False
```
**Symbols:**

```
ffffffff81a3ae00-ffffffff81a3af81: unix_accept (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int unix_accept(struct socket *sock, struct socket *newsock, int flags, bool kern);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81a45c60)
Location: net/unix/af_unix.c:1431
Inline: False
```
**Symbols:**

```
ffffffff81a45c60-ffffffff81a45ddf: unix_accept (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool kern</code>
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
