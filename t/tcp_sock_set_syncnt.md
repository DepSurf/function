# Function: <code>tcp_sock_set_syncnt</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tcp_sock_set_syncnt(struct sock *sk, int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81aa78f0)
Location: net/ipv4/tcp.c:2943
Inline: False
```
**Symbols:**

```
ffffffff81aa78f0-ffffffff81aa792d: tcp_sock_set_syncnt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tcp_sock_set_syncnt(struct sock *sk, int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81ab1f70)
Location: net/ipv4/tcp.c:3201
Inline: False
```
**Symbols:**

```
ffffffff81ab1f70-ffffffff81ab1fad: tcp_sock_set_syncnt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tcp_sock_set_syncnt(struct sock *sk, int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81a9d200)
Location: net/ipv4/tcp.c:3255
Inline: False
```
**Symbols:**

```
ffffffff81a9d200-ffffffff81a9d23d: tcp_sock_set_syncnt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int tcp_sock_set_syncnt(struct sock *sk, int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81b590d0)
Location: net/ipv4/tcp.c:3279
Inline: False
```
**Symbols:**

```
ffffffff81b590d0-ffffffff81b5910d: tcp_sock_set_syncnt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int tcp_sock_set_syncnt(struct sock *sk, int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81ce7390)
Location: net/ipv4/tcp.c:3297
Inline: False
```
**Symbols:**

```
ffffffff81ce7390-ffffffff81ce73dd: tcp_sock_set_syncnt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tcp_sock_set_syncnt(struct sock *sk, int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81eaaae0)
Location: net/ipv4/tcp.c:3396
Inline: False
```
**Symbols:**

```
ffffffff81eaaae0-ffffffff81eaab2d: tcp_sock_set_syncnt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tcp_sock_set_syncnt(struct sock *sk, int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81f092d0)
Location: net/ipv4/tcp.c:3288
Inline: False
```
**Symbols:**

```
ffffffff81f092d0-ffffffff81f0931d: tcp_sock_set_syncnt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int tcp_sock_set_syncnt(struct sock *sk, int val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81fd5519)
Location: net/ipv4/tcp.c:3294
Inline: True
Inline callers:
  - net/ipv4/tcp.c:do_tcp_setsockopt
```
**Symbols:**

```
ffffffff81fcd0f0-ffffffff81fcd123: tcp_sock_set_syncnt (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
