# Function: <code>tcp_set_keepalive</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void tcp_set_keepalive(struct sock *sk, int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_timer.c (ffffffff8177a8d0)
Location: net/ipv4/tcp_timer.c:562
Inline: False
Direct callers:
  - net/core/sock.c:sock_setsockopt
```
**Symbols:**

```
ffffffff8177a8d0-ffffffff8177a913: tcp_set_keepalive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void tcp_set_keepalive(struct sock *sk, int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_timer.c (ffffffff817e7ba0)
Location: net/ipv4/tcp_timer.c:606
Inline: False
Direct callers:
  - net/core/sock.c:sock_setsockopt
```
**Symbols:**

```
ffffffff817e7ba0-ffffffff817e7be9: tcp_set_keepalive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void tcp_set_keepalive(struct sock *sk, int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_timer.c (ffffffff81818360)
Location: net/ipv4/tcp_timer.c:612
Inline: False
Direct callers:
  - net/core/sock.c:sock_setsockopt
```
**Symbols:**

```
ffffffff81818360-ffffffff818183a9: tcp_set_keepalive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void tcp_set_keepalive(struct sock *sk, int val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_timer.c (ffffffff81837a10)
Location: net/ipv4/tcp_timer.c:609
Inline: True
```
**Symbols:**

```
ffffffff81837a10-ffffffff81837a59: tcp_set_keepalive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void tcp_set_keepalive(struct sock *sk, int val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_timer.c (ffffffff818b7190)
Location: net/ipv4/tcp_timer.c:619
Inline: True
```
**Symbols:**

```
ffffffff818b7190-ffffffff818b71d9: tcp_set_keepalive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void tcp_set_keepalive(struct sock *sk, int val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_timer.c (ffffffff8190ca50)
Location: net/ipv4/tcp_timer.c:611
Inline: True
```
**Symbols:**

```
ffffffff8190ca50-ffffffff8190ca98: tcp_set_keepalive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void tcp_set_keepalive(struct sock *sk, int val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_timer.c (ffffffff8193ad90)
Location: net/ipv4/tcp_timer.c:638
Inline: True
```
**Symbols:**

```
ffffffff8193ad90-ffffffff8193add8: tcp_set_keepalive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void tcp_set_keepalive(struct sock *sk, int val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_timer.c (ffffffff8199f110)
Location: net/ipv4/tcp_timer.c:630
Inline: True
```
**Symbols:**

```
ffffffff8199f110-ffffffff8199f158: tcp_set_keepalive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void tcp_set_keepalive(struct sock *sk, int val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_timer.c (ffffffff819d5b50)
Location: net/ipv4/tcp_timer.c:637
Inline: True
```
**Symbols:**

```
ffffffff819d5b50-ffffffff819d5b98: tcp_set_keepalive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void tcp_set_keepalive(struct sock *sk, int val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_timer.c (ffffffff81ac2190)
Location: net/ipv4/tcp_timer.c:649
Inline: True
```
**Symbols:**

```
ffffffff81ac2190-ffffffff81ac21d8: tcp_set_keepalive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void tcp_set_keepalive(struct sock *sk, int val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_timer.c (ffffffff81acdbc0)
Location: net/ipv4/tcp_timer.c:660
Inline: True
```
**Symbols:**

```
ffffffff81acdbc0-ffffffff81acdc08: tcp_set_keepalive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void tcp_set_keepalive(struct sock *sk, int val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_timer.c (ffffffff81ab8d70)
Location: net/ipv4/tcp_timer.c:660
Inline: True
```
**Symbols:**

```
ffffffff81ab8d70-ffffffff81ab8db8: tcp_set_keepalive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tcp_set_keepalive(struct sock *sk, int val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_timer.c (ffffffff81b75fbd)
Location: net/ipv4/tcp_timer.c:660
Inline: True
```
**Symbols:**

```
ffffffff81d3b459-ffffffff81d3b473: tcp_set_keepalive.cold (STB_LOCAL)
ffffffff81b75f90-ffffffff81b76000: tcp_set_keepalive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tcp_set_keepalive(struct sock *sk, int val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_timer.c (ffffffff81d0590b)
Location: net/ipv4/tcp_timer.c:664
Inline: True
```
**Symbols:**

```
ffffffff81f07d42-ffffffff81f07d5c: tcp_set_keepalive.cold (STB_LOCAL)
ffffffff81d058d0-ffffffff81d05961: tcp_set_keepalive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tcp_set_keepalive(struct sock *sk, int val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_timer.c (ffffffff81ecaa4b)
Location: net/ipv4/tcp_timer.c:655
Inline: True
```
**Symbols:**

```
ffffffff820af78d-ffffffff820af7a7: tcp_set_keepalive.cold (STB_LOCAL)
ffffffff81ecaa10-ffffffff81ecaa97: tcp_set_keepalive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tcp_set_keepalive(struct sock *sk, int val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_timer.c (ffffffff81f29775)
Location: net/ipv4/tcp_timer.c:692
Inline: True
```
**Symbols:**

```
ffffffff82130bc2-ffffffff82130bdb: tcp_set_keepalive.cold (STB_LOCAL)
ffffffff81f29740-ffffffff81f297bd: tcp_set_keepalive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tcp_set_keepalive(struct sock *sk, int val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_timer.c (ffffffff81fee2f5)
Location: net/ipv4/tcp_timer.c:728
Inline: True
```
**Symbols:**

```
ffffffff82212396-ffffffff822123af: tcp_set_keepalive.cold (STB_LOCAL)
ffffffff81fee2c0-ffffffff81fee33d: tcp_set_keepalive (STB_GLOBAL)
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
void tcp_set_keepalive(struct sock *sk, int val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_timer.c (ffff800010c88520)
Location: net/ipv4/tcp_timer.c:637
Inline: True
```
**Symbols:**

```
ffff800010c88520-ffff800010c88598: tcp_set_keepalive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void tcp_set_keepalive(struct sock *sk, int val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_timer.c (c0d97a70)
Location: net/ipv4/tcp_timer.c:637
Inline: True
```
**Symbols:**

```
c0d97a70-c0d97acc: tcp_set_keepalive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void tcp_set_keepalive(struct sock *sk, int val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_timer.c (c000000000d95a10)
Location: net/ipv4/tcp_timer.c:637
Inline: True
```
**Symbols:**

```
c000000000d95a10-c000000000d95abc: tcp_set_keepalive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void tcp_set_keepalive(struct sock *sk, int val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_timer.c (ffffffe0007e9aca)
Location: net/ipv4/tcp_timer.c:637
Inline: True
```
**Symbols:**

```
ffffffe0007e9aca-ffffffe0007e9b40: tcp_set_keepalive (STB_GLOBAL)
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
void tcp_set_keepalive(struct sock *sk, int val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_timer.c (ffffffff819759c0)
Location: net/ipv4/tcp_timer.c:637
Inline: True
```
**Symbols:**

```
ffffffff819759c0-ffffffff81975a08: tcp_set_keepalive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void tcp_set_keepalive(struct sock *sk, int val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_timer.c (ffffffff8192f480)
Location: net/ipv4/tcp_timer.c:637
Inline: True
```
**Symbols:**

```
ffffffff8192f480-ffffffff8192f4c8: tcp_set_keepalive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void tcp_set_keepalive(struct sock *sk, int val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_timer.c (ffffffff819e0190)
Location: net/ipv4/tcp_timer.c:637
Inline: True
```
**Symbols:**

```
ffffffff819e0190-ffffffff819e01d8: tcp_set_keepalive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void tcp_set_keepalive(struct sock *sk, int val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_timer.c (ffffffff819e9e50)
Location: net/ipv4/tcp_timer.c:637
Inline: True
```
**Symbols:**

```
ffffffff819e9e50-ffffffff819e9e98: tcp_set_keepalive (STB_GLOBAL)
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
