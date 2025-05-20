# Function: <code>tcp_fastopen_active_should_disable</code>

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
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool tcp_fastopen_active_should_disable(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff81841442)
Location: net/ipv4/tcp_fastopen.c:431
Inline: True
```
**Symbols:**

```
ffffffff81841640-ffffffff81841694: tcp_fastopen_active_should_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool tcp_fastopen_active_should_disable(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff818c0c66)
Location: net/ipv4/tcp_fastopen.c:473
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check
```
**Symbols:**

```
ffffffff818c0e50-ffffffff818c0ea8: tcp_fastopen_active_should_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool tcp_fastopen_active_should_disable(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff81916747)
Location: net/ipv4/tcp_fastopen.c:466
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check
```
**Symbols:**

```
ffffffff81916920-ffffffff81916978: tcp_fastopen_active_should_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool tcp_fastopen_active_should_disable(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff81944ee7)
Location: net/ipv4/tcp_fastopen.c:466
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check
```
**Symbols:**

```
ffffffff819450d0-ffffffff81945128: tcp_fastopen_active_should_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool tcp_fastopen_active_should_disable(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff819a9517)
Location: net/ipv4/tcp_fastopen.c:493
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check
```
**Symbols:**

```
ffffffff819a9700-ffffffff819a975e: tcp_fastopen_active_should_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool tcp_fastopen_active_should_disable(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff819e01b7)
Location: net/ipv4/tcp_fastopen.c:493
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check
```
**Symbols:**

```
ffffffff819e03c0-ffffffff819e041e: tcp_fastopen_active_should_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool tcp_fastopen_active_should_disable(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff81acd7a7)
Location: net/ipv4/tcp_fastopen.c:519
Inline: True
```
**Symbols:**

```
ffffffff81acd9a0-ffffffff81acd9fe: tcp_fastopen_active_should_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool tcp_fastopen_active_should_disable(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff81ad97e7)
Location: net/ipv4/tcp_fastopen.c:519
Inline: True
```
**Symbols:**

```
ffffffff81ad99e0-ffffffff81ad9a3e: tcp_fastopen_active_should_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool tcp_fastopen_active_should_disable(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff81ac4870)
Location: net/ipv4/tcp_fastopen.c:529
Inline: False
```
**Symbols:**

```
ffffffff81ac4870-ffffffff81ac48db: tcp_fastopen_active_should_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool tcp_fastopen_active_should_disable(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_fastopen.c (0)
Location: net/ipv4/tcp_fastopen.c:517
Inline: False
```
**Symbols:**

```
ffffffff81d3be75-ffffffff81d3be94: tcp_fastopen_active_should_disable.cold (STB_LOCAL)
ffffffff81b82fb0-ffffffff81b83030: tcp_fastopen_active_should_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool tcp_fastopen_active_should_disable(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_fastopen.c (0)
Location: net/ipv4/tcp_fastopen.c:511
Inline: False
Direct callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check
```
**Symbols:**

```
ffffffff81f08692-ffffffff81f086b1: tcp_fastopen_active_should_disable.cold (STB_LOCAL)
ffffffff81d13570-ffffffff81d13602: tcp_fastopen_active_should_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool tcp_fastopen_active_should_disable(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_fastopen.c (0)
Location: net/ipv4/tcp_fastopen.c:512
Inline: False
Direct callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check
```
**Symbols:**

```
ffffffff820b0173-ffffffff820b0192: tcp_fastopen_active_should_disable.cold (STB_LOCAL)
ffffffff81ed9500-ffffffff81ed9592: tcp_fastopen_active_should_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool tcp_fastopen_active_should_disable(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_fastopen.c (0)
Location: net/ipv4/tcp_fastopen.c:514
Inline: False
Direct callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check
```
**Symbols:**

```
ffffffff821313ff-ffffffff8213141e: tcp_fastopen_active_should_disable.cold (STB_LOCAL)
ffffffff81f385e0-ffffffff81f38672: tcp_fastopen_active_should_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool tcp_fastopen_active_should_disable(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_fastopen.c (0)
Location: net/ipv4/tcp_fastopen.c:514
Inline: False
Direct callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check
```
**Symbols:**

```
ffffffff82212d43-ffffffff82212d62: tcp_fastopen_active_should_disable.cold (STB_LOCAL)
ffffffff81ffe6a0-ffffffff81ffe732: tcp_fastopen_active_should_disable (STB_GLOBAL)
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
bool tcp_fastopen_active_should_disable(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffff800010c93da4)
Location: net/ipv4/tcp_fastopen.c:493
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check
```
**Symbols:**

```
ffff800010c93fe0-ffff800010c94060: tcp_fastopen_active_should_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool tcp_fastopen_active_should_disable(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (c0da260c)
Location: net/ipv4/tcp_fastopen.c:493
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check
```
**Symbols:**

```
c0da2820-c0da28a4: tcp_fastopen_active_should_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool tcp_fastopen_active_should_disable(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (c000000000da4374)
Location: net/ipv4/tcp_fastopen.c:493
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check
```
**Symbols:**

```
c000000000da4690-c000000000da4748: tcp_fastopen_active_should_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool tcp_fastopen_active_should_disable(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffe0007f3368)
Location: net/ipv4/tcp_fastopen.c:493
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check
```
**Symbols:**

```
ffffffe0007f3562-ffffffe0007f35d8: tcp_fastopen_active_should_disable (STB_GLOBAL)
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
bool tcp_fastopen_active_should_disable(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff81980027)
Location: net/ipv4/tcp_fastopen.c:493
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check
```
**Symbols:**

```
ffffffff81980230-ffffffff8198028e: tcp_fastopen_active_should_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool tcp_fastopen_active_should_disable(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff81939ae7)
Location: net/ipv4/tcp_fastopen.c:493
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check
```
**Symbols:**

```
ffffffff81939cf0-ffffffff81939d4e: tcp_fastopen_active_should_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool tcp_fastopen_active_should_disable(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff819ea7f7)
Location: net/ipv4/tcp_fastopen.c:493
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check
```
**Symbols:**

```
ffffffff819eaa00-ffffffff819eaa5e: tcp_fastopen_active_should_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool tcp_fastopen_active_should_disable(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff819f4667)
Location: net/ipv4/tcp_fastopen.c:493
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check
```
**Symbols:**

```
ffffffff819f4870-ffffffff819f48ce: tcp_fastopen_active_should_disable (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
