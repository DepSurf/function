# Function: <code>inet_accept</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int inet_accept(struct socket *sock, struct socket *newsock, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81793890)
Location: net/ipv4/af_inet.c:667
Inline: False
```
**Symbols:**

```
ffffffff81793890-ffffffff817939b7: inet_accept (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int inet_accept(struct socket *sock, struct socket *newsock, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff818010a0)
Location: net/ipv4/af_inet.c:671
Inline: False
```
**Symbols:**

```
ffffffff818010a0-ffffffff818011c7: inet_accept (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int inet_accept(struct socket *sock, struct socket *newsock, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81832620)
Location: net/ipv4/af_inet.c:675
Inline: False
```
**Symbols:**

```
ffffffff81832620-ffffffff8183277a: inet_accept (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int inet_accept(struct socket *sock, struct socket *newsock, int flags, bool kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81853940)
Location: net/ipv4/af_inet.c:692
Inline: False
```
**Symbols:**

```
ffffffff81853940-ffffffff81853a9f: inet_accept (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int inet_accept(struct socket *sock, struct socket *newsock, int flags, bool kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff818d37c0)
Location: net/ipv4/af_inet.c:693
Inline: False
```
**Symbols:**

```
ffffffff818d37c0-ffffffff818d3925: inet_accept (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int inet_accept(struct socket *sock, struct socket *newsock, int flags, bool kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81929c90)
Location: net/ipv4/af_inet.c:729
Inline: False
```
**Symbols:**

```
ffffffff81929c90-ffffffff81929df5: inet_accept (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int inet_accept(struct socket *sock, struct socket *newsock, int flags, bool kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81959280)
Location: net/ipv4/af_inet.c:729
Inline: False
```
**Symbols:**

```
ffffffff81959280-ffffffff819593e7: inet_accept (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int inet_accept(struct socket *sock, struct socket *newsock, int flags, bool kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/af_inet.c (0)
Location: net/ipv4/af_inet.c:729
Inline: False
```
**Symbols:**

```
ffffffff819bf6c5-ffffffff819bf6eb: inet_accept.cold (STB_LOCAL)
ffffffff819bdd50-ffffffff819bdea6: inet_accept (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int inet_accept(struct socket *sock, struct socket *newsock, int flags, bool kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff819f4960)
Location: net/ipv4/af_inet.c:729
Inline: False
```
**Symbols:**

```
ffffffff819f4960-ffffffff819f4ac4: inet_accept (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int inet_accept(struct socket *sock, struct socket *newsock, int flags, bool kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81ae2690)
Location: net/ipv4/af_inet.c:732
Inline: False
```
**Symbols:**

```
ffffffff81ae2690-ffffffff81ae27ee: inet_accept (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int inet_accept(struct socket *sock, struct socket *newsock, int flags, bool kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81aef530)
Location: net/ipv4/af_inet.c:735
Inline: False
```
**Symbols:**

```
ffffffff81aef530-ffffffff81aef693: inet_accept (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int inet_accept(struct socket *sock, struct socket *newsock, int flags, bool kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81adac80)
Location: net/ipv4/af_inet.c:738
Inline: False
```
**Symbols:**

```
ffffffff81adac80-ffffffff81adade3: inet_accept (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int inet_accept(struct socket *sock, struct socket *newsock, int flags, bool kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/af_inet.c (0)
Location: net/ipv4/af_inet.c:738
Inline: False
```
**Symbols:**

```
ffffffff81d3c3d1-ffffffff81d3c3eb: inet_accept.cold (STB_LOCAL)
ffffffff81b99ef0-ffffffff81b9a05e: inet_accept (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int inet_accept(struct socket *sock, struct socket *newsock, int flags, bool kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/af_inet.c (0)
Location: net/ipv4/af_inet.c:734
Inline: False
```
**Symbols:**

```
ffffffff81f08c03-ffffffff81f08c1d: inet_accept.cold (STB_LOCAL)
ffffffff81d2bef0-ffffffff81d2c06e: inet_accept (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int inet_accept(struct socket *sock, struct socket *newsock, int flags, bool kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/af_inet.c (0)
Location: net/ipv4/af_inet.c:740
Inline: False
```
**Symbols:**

```
ffffffff820b05dc-ffffffff820b05f6: inet_accept.cold (STB_LOCAL)
ffffffff81ef3ac0-ffffffff81ef3c61: inet_accept (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int inet_accept(struct socket *sock, struct socket *newsock, int flags, bool kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81f55a70)
Location: net/ipv4/af_inet.c:754
Inline: False
```
**Symbols:**

```
ffffffff81f55a70-ffffffff81f55b12: inet_accept (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int inet_accept(struct socket *sock, struct socket *newsock, int flags, bool kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff8201bf50)
Location: net/ipv4/af_inet.c:773
Inline: False
```
**Symbols:**

```
ffffffff8201bf50-ffffffff8201bff2: inet_accept (STB_GLOBAL)
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
int inet_accept(struct socket *sock, struct socket *newsock, int flags, bool kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffff800010caa848)
Location: net/ipv4/af_inet.c:729
Inline: False
```
**Symbols:**

```
ffff800010caa848-ffff800010caaa30: inet_accept (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int inet_accept(struct socket *sock, struct socket *newsock, int flags, bool kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (c0db7174)
Location: net/ipv4/af_inet.c:729
Inline: False
```
**Symbols:**

```
c0db7174-c0db732c: inet_accept (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int inet_accept(struct socket *sock, struct socket *newsock, int flags, bool kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (c000000000dc09f0)
Location: net/ipv4/af_inet.c:729
Inline: False
```
**Symbols:**

```
c000000000dc09f0-c000000000dc0bb4: inet_accept (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int inet_accept(struct socket *sock, struct socket *newsock, int flags, bool kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffe0008055f6)
Location: net/ipv4/af_inet.c:729
Inline: False
```
**Symbols:**

```
ffffffe0008055f6-ffffffe00080571e: inet_accept (STB_GLOBAL)
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
int inet_accept(struct socket *sock, struct socket *newsock, int flags, bool kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81994700)
Location: net/ipv4/af_inet.c:729
Inline: False
```
**Symbols:**

```
ffffffff81994700-ffffffff81994864: inet_accept (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int inet_accept(struct socket *sock, struct socket *newsock, int flags, bool kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff8194e1c0)
Location: net/ipv4/af_inet.c:729
Inline: False
```
**Symbols:**

```
ffffffff8194e1c0-ffffffff8194e324: inet_accept (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int inet_accept(struct socket *sock, struct socket *newsock, int flags, bool kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff819fefa0)
Location: net/ipv4/af_inet.c:729
Inline: False
```
**Symbols:**

```
ffffffff819fefa0-ffffffff819ff104: inet_accept (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int inet_accept(struct socket *sock, struct socket *newsock, int flags, bool kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81a09070)
Location: net/ipv4/af_inet.c:729
Inline: False
```
**Symbols:**

```
ffffffff81a09070-ffffffff81a091e1: inet_accept (STB_GLOBAL)
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
