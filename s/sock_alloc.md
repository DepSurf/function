# Function: <code>sock_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct socket *sock_alloc();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff816fce40)
Location: net/socket.c:536
Inline: False
Direct callers:
  - net/socket.c:sock_create_lite
  - net/socket.c:__sock_create
  - net/socket.c:SYSC_accept4
```
**Symbols:**

```
ffffffff816fce40-ffffffff816fceba: sock_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct socket *sock_alloc();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff817635e0)
Location: net/socket.c:536
Inline: False
Direct callers:
  - net/socket.c:SYSC_accept4
  - net/socket.c:__sock_create
  - net/socket.c:sock_create_lite
```
**Symbols:**

```
ffffffff817635e0-ffffffff8176365a: sock_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct socket *sock_alloc();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81790620)
Location: net/socket.c:562
Inline: False
Direct callers:
  - net/socket.c:SYSC_accept4
  - net/socket.c:__sock_create
  - net/socket.c:sock_create_lite
```
**Symbols:**

```
ffffffff81790620-ffffffff8179069a: sock_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct socket *sock_alloc();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff817add20)
Location: net/socket.c:560
Inline: False
Direct callers:
  - net/socket.c:SYSC_accept4
  - net/socket.c:__sock_create
  - net/socket.c:sock_create_lite
```
**Symbols:**

```
ffffffff817add20-ffffffff817add9a: sock_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct socket *sock_alloc();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81825ba0)
Location: net/socket.c:566
Inline: False
Direct callers:
  - net/socket.c:SYSC_accept4
  - net/socket.c:__sock_create
  - net/socket.c:sock_create_lite
```
**Symbols:**

```
ffffffff81825ba0-ffffffff81825c1a: sock_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct socket *sock_alloc();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8186f700)
Location: net/socket.c:563
Inline: False
Direct callers:
  - net/socket.c:__sys_accept4
  - net/socket.c:__sock_create
  - net/socket.c:sock_create_lite
```
**Symbols:**

```
ffffffff8186f700-ffffffff8186f779: sock_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct socket *sock_alloc();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818902b0)
Location: net/socket.c:542
Inline: False
Direct callers:
  - net/socket.c:__sys_accept4
  - net/socket.c:__sock_create
  - net/socket.c:sock_create_lite
```
**Symbols:**

```
ffffffff818902b0-ffffffff81890329: sock_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct socket *sock_alloc();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818da140)
Location: net/socket.c:553
Inline: False
Direct callers:
  - net/socket.c:__sys_accept4
  - net/socket.c:__sock_create
  - net/socket.c:sock_create_lite
```
**Symbols:**

```
ffffffff818da140-ffffffff818da1b9: sock_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct socket *sock_alloc();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8190c120)
Location: net/socket.c:553
Inline: False
Direct callers:
  - net/socket.c:__sys_accept4
  - net/socket.c:__sock_create
  - net/socket.c:sock_create_lite
```
**Symbols:**

```
ffffffff8190c120-ffffffff8190c199: sock_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct socket *sock_alloc();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819de380)
Location: net/socket.c:568
Inline: False
Direct callers:
  - net/socket.c:__sys_accept4_file
  - net/socket.c:__sock_create
  - net/socket.c:sock_create_lite
```
**Symbols:**

```
ffffffff819de380-ffffffff819de3f9: sock_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct socket *sock_alloc();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819ddde0)
Location: net/socket.c:569
Inline: False
Direct callers:
  - net/socket.c:__sys_accept4_file
  - net/socket.c:__sock_create
  - net/socket.c:sock_create_lite
```
**Symbols:**

```
ffffffff819ddde0-ffffffff819dde59: sock_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct socket *sock_alloc();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819c3df0)
Location: net/socket.c:571
Inline: False
Direct callers:
  - net/socket.c:__sys_accept4_file
  - net/socket.c:__sock_create
  - net/socket.c:sock_create_lite
```
**Symbols:**

```
ffffffff819c3df0-ffffffff819c3e69: sock_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct socket *sock_alloc();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81a73170)
Location: net/socket.c:621
Inline: False
Direct callers:
  - net/socket.c:do_accept
  - net/socket.c:__sock_create
  - net/socket.c:sock_create_lite
```
**Symbols:**

```
ffffffff81a73170-ffffffff81a731e9: sock_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct socket *sock_alloc();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81be5b10)
Location: net/socket.c:622
Inline: False
Direct callers:
  - net/socket.c:do_accept
  - net/socket.c:__sock_create
  - net/socket.c:sock_create_lite
```
**Symbols:**

```
ffffffff81be5b10-ffffffff81be5b99: sock_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct socket *sock_alloc();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81d91e00)
Location: net/socket.c:624
Inline: False
Direct callers:
  - net/socket.c:do_accept
  - net/socket.c:__sock_create
  - net/socket.c:sock_create_lite
```
**Symbols:**

```
ffffffff81d91e00-ffffffff81d91e89: sock_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct socket *sock_alloc();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81e000f0)
Location: net/socket.c:627
Inline: False
Direct callers:
  - net/socket.c:do_accept
  - net/socket.c:__sock_create
  - net/socket.c:sock_create_lite
```
**Symbols:**

```
ffffffff81e000f0-ffffffff81e00179: sock_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct socket *sock_alloc();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81ebc590)
Location: net/socket.c:629
Inline: False
Direct callers:
  - net/socket.c:do_accept
  - net/socket.c:__sock_create
  - net/socket.c:sock_create_lite
```
**Symbols:**

```
ffffffff81ebc590-ffffffff81ebc619: sock_alloc (STB_GLOBAL)
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
struct socket *sock_alloc();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffff800010ba1218)
Location: net/socket.c:553
Inline: False
Direct callers:
  - net/socket.c:__sys_accept4
  - net/socket.c:__sock_create
  - net/socket.c:sock_create_lite
```
**Symbols:**

```
ffff800010ba1218-ffff800010ba12a4: sock_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct socket *sock_alloc();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (c0cc3558)
Location: net/socket.c:553
Inline: False
Direct callers:
  - net/socket.c:__sys_accept4
  - net/socket.c:__sock_create
  - net/socket.c:sock_create_lite
```
**Symbols:**

```
c0cc3558-c0cc35e0: sock_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct socket *sock_alloc();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (c000000000c756c0)
Location: net/socket.c:553
Inline: False
Direct callers:
  - net/socket.c:__sys_accept4
  - net/socket.c:__sock_create
  - net/socket.c:sock_create_lite
```
**Symbols:**

```
c000000000c756c0-c000000000c75778: sock_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct socket *sock_alloc();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffe000739280)
Location: net/socket.c:553
Inline: False
Direct callers:
  - net/socket.c:__sys_accept4
  - net/socket.c:__sock_create
  - net/socket.c:sock_create_lite
```
**Symbols:**

```
ffffffe000739280-ffffffe0007392f6: sock_alloc (STB_GLOBAL)
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
struct socket *sock_alloc();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818ac120)
Location: net/socket.c:553
Inline: False
Direct callers:
  - net/socket.c:__sys_accept4
  - net/socket.c:__sock_create
  - net/socket.c:sock_create_lite
```
**Symbols:**

```
ffffffff818ac120-ffffffff818ac199: sock_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct socket *sock_alloc();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81866070)
Location: net/socket.c:553
Inline: False
Direct callers:
  - net/socket.c:__sys_accept4
  - net/socket.c:__sock_create
  - net/socket.c:sock_create_lite
```
**Symbols:**

```
ffffffff81866070-ffffffff818660e9: sock_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct socket *sock_alloc();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818fd120)
Location: net/socket.c:553
Inline: False
Direct callers:
  - net/socket.c:__sys_accept4
  - net/socket.c:__sock_create
  - net/socket.c:sock_create_lite
```
**Symbols:**

```
ffffffff818fd120-ffffffff818fd199: sock_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct socket *sock_alloc();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8191e190)
Location: net/socket.c:553
Inline: False
Direct callers:
  - net/socket.c:__sys_accept4
  - net/socket.c:__sock_create
  - net/socket.c:sock_create_lite
```
**Symbols:**

```
ffffffff8191e190-ffffffff8191e209: sock_alloc (STB_GLOBAL)
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
