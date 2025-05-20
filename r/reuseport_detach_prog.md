# Function: <code>reuseport_detach_prog</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int reuseport_detach_prog(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff8192f430)
Location: net/core/sock_reuseport.c:347
Inline: True
Direct callers:
  - net/core/sock.c:sock_setsockopt
```
**Symbols:**

```
ffffffff8192f430-ffffffff8192f49f: reuseport_detach_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int reuseport_detach_prog(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff819616a0)
Location: net/core/sock_reuseport.c:347
Inline: True
Direct callers:
  - net/core/sock.c:sock_setsockopt
```
**Symbols:**

```
ffffffff819616a0-ffffffff8196170f: reuseport_detach_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int reuseport_detach_prog(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff81a34c90)
Location: net/core/sock_reuseport.c:339
Inline: True
Direct callers:
  - net/core/sock.c:sock_setsockopt
```
**Symbols:**

```
ffffffff81a34c90-ffffffff81a34cff: reuseport_detach_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int reuseport_detach_prog(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff81a36fd0)
Location: net/core/sock_reuseport.c:339
Inline: True
Direct callers:
  - net/core/sock.c:sock_setsockopt
```
**Symbols:**

```
ffffffff81a36fd0-ffffffff81a3703f: reuseport_detach_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int reuseport_detach_prog(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff81a1e130)
Location: net/core/sock_reuseport.c:339
Inline: True
Direct callers:
  - net/core/sock.c:sock_setsockopt
```
**Symbols:**

```
ffffffff81a1e130-ffffffff81a1e19f: reuseport_detach_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int reuseport_detach_prog(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff81ad1830)
Location: net/core/sock_reuseport.c:616
Inline: False
Direct callers:
  - net/core/sock.c:sock_setsockopt
```
**Symbols:**

```
ffffffff81ad1830-ffffffff81ad18bd: reuseport_detach_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int reuseport_detach_prog(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff81c4f140)
Location: net/core/sock_reuseport.c:616
Inline: False
Direct callers:
  - net/core/sock.c:sock_setsockopt
```
**Symbols:**

```
ffffffff81c4f140-ffffffff81c4f1d2: reuseport_detach_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int reuseport_detach_prog(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff81e042b0)
Location: net/core/sock_reuseport.c:716
Inline: False
Direct callers:
  - net/core/sock.c:sk_setsockopt
```
**Symbols:**

```
ffffffff81e042b0-ffffffff81e04342: reuseport_detach_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int reuseport_detach_prog(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff81e76b00)
Location: net/core/sock_reuseport.c:716
Inline: False
Direct callers:
  - net/core/sock.c:sk_setsockopt
```
**Symbols:**

```
ffffffff81e76b00-ffffffff81e76b92: reuseport_detach_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int reuseport_detach_prog(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff81f36ac0)
Location: net/core/sock_reuseport.c:716
Inline: False
Direct callers:
  - net/core/sock.c:sk_setsockopt
```
**Symbols:**

```
ffffffff81f36ac0-ffffffff81f36b52: reuseport_detach_prog (STB_GLOBAL)
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
int reuseport_detach_prog(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffff800010c04f00)
Location: net/core/sock_reuseport.c:347
Inline: True
Direct callers:
  - net/core/sock.c:sock_setsockopt
```
**Symbols:**

```
ffff800010c04f00-ffff800010c04ffc: reuseport_detach_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int reuseport_detach_prog(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (c0d1e434)
Location: net/core/sock_reuseport.c:347
Inline: True
Direct callers:
  - net/core/sock.c:sock_setsockopt
```
**Symbols:**

```
c0d1e434-c0d1e4b8: reuseport_detach_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int reuseport_detach_prog(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (c000000000cef210)
Location: net/core/sock_reuseport.c:347
Inline: True
Direct callers:
  - net/core/sock.c:sock_setsockopt
```
**Symbols:**

```
c000000000cef210-c000000000cef2d8: reuseport_detach_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int reuseport_detach_prog(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffe000783b24)
Location: net/core/sock_reuseport.c:347
Inline: True
Direct callers:
  - net/core/sock.c:sock_setsockopt
```
**Symbols:**

```
ffffffe000783b24-ffffffe000783b9c: reuseport_detach_prog (STB_GLOBAL)
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
int reuseport_detach_prog(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff81901670)
Location: net/core/sock_reuseport.c:347
Inline: True
Direct callers:
  - net/core/sock.c:sock_setsockopt
```
**Symbols:**

```
ffffffff81901670-ffffffff819016df: reuseport_detach_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int reuseport_detach_prog(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff818bb4a0)
Location: net/core/sock_reuseport.c:347
Inline: True
Direct callers:
  - net/core/sock.c:sock_setsockopt
```
**Symbols:**

```
ffffffff818bb4a0-ffffffff818bb50f: reuseport_detach_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int reuseport_detach_prog(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff819526a0)
Location: net/core/sock_reuseport.c:347
Inline: True
Direct callers:
  - net/core/sock.c:sock_setsockopt
```
**Symbols:**

```
ffffffff819526a0-ffffffff8195270f: reuseport_detach_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int reuseport_detach_prog(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff81974110)
Location: net/core/sock_reuseport.c:347
Inline: True
Direct callers:
  - net/core/sock.c:sock_setsockopt
```
**Symbols:**

```
ffffffff81974110-ffffffff8197417f: reuseport_detach_prog (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
