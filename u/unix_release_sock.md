# Function: <code>unix_release_sock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void unix_release_sock(struct sock *sk, int embrion);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff817bfd00)
Location: net/unix/af_unix.c:510
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_release
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
```
**Symbols:**

```
ffffffff817bfd00-ffffffff817bffe2: unix_release_sock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void unix_release_sock(struct sock *sk, int embrion);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff8182d110)
Location: net/unix/af_unix.c:510
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_release
  - net/unix/af_unix.c:unix_release_sock
```
**Symbols:**

```
ffffffff8182d110-ffffffff8182d3d4: unix_release_sock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void unix_release_sock(struct sock *sk, int embrion);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff8185ebf0)
Location: net/unix/af_unix.c:510
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_release
  - net/unix/af_unix.c:unix_release_sock
```
**Symbols:**

```
ffffffff8185ebf0-ffffffff8185eeb4: unix_release_sock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void unix_release_sock(struct sock *sk, int embrion);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81882e90)
Location: net/unix/af_unix.c:511
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_release
  - net/unix/af_unix.c:unix_release_sock
```
**Symbols:**

```
ffffffff81882e90-ffffffff81883142: unix_release_sock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void unix_release_sock(struct sock *sk, int embrion);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81904850)
Location: net/unix/af_unix.c:511
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_release
  - net/unix/af_unix.c:unix_release_sock
```
**Symbols:**

```
ffffffff81904850-ffffffff81904b1f: unix_release_sock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void unix_release_sock(struct sock *sk, int embrion);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff8195a080)
Location: net/unix/af_unix.c:511
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_release
  - net/unix/af_unix.c:unix_release_sock
```
**Symbols:**

```
ffffffff8195a080-ffffffff8195a359: unix_release_sock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void unix_release_sock(struct sock *sk, int embrion);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff8198ebe0)
Location: net/unix/af_unix.c:518
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_release
  - net/unix/af_unix.c:unix_release_sock
```
**Symbols:**

```
ffffffff8198ebe0-ffffffff8198eeb8: unix_release_sock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void unix_release_sock(struct sock *sk, int embrion);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/unix/af_unix.c (0)
Location: net/unix/af_unix.c:515
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_release
  - net/unix/af_unix.c:unix_release_sock
```
**Symbols:**

```
ffffffff819fa200-ffffffff819fa4d2: unix_release_sock (STB_LOCAL)
ffffffff819fd61d-ffffffff819fd630: unix_release_sock.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void unix_release_sock(struct sock *sk, int embrion);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81a30e80)
Location: net/unix/af_unix.c:515
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_release
  - net/unix/af_unix.c:unix_release_sock
```
**Symbols:**

```
ffffffff81a30e80-ffffffff81a31159: unix_release_sock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void unix_release_sock(struct sock *sk, int embrion);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81b255b0)
Location: net/unix/af_unix.c:519
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_release
  - net/unix/af_unix.c:unix_release_sock
```
**Symbols:**

```
ffffffff81b255b0-ffffffff81b2595b: unix_release_sock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void unix_release_sock(struct sock *sk, int embrion);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81b33fc0)
Location: net/unix/af_unix.c:519
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_release
  - net/unix/af_unix.c:unix_release_sock
```
**Symbols:**

```
ffffffff81b33fc0-ffffffff81b3436e: unix_release_sock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void unix_release_sock(struct sock *sk, int embrion);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81b21b00)
Location: net/unix/af_unix.c:519
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_release
  - net/unix/af_unix.c:unix_release_sock
```
**Symbols:**

```
ffffffff81b21b00-ffffffff81b21e98: unix_release_sock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void unix_release_sock(struct sock *sk, int embrion);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81be7030)
Location: net/unix/af_unix.c:534
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_release
  - net/unix/af_unix.c:unix_release_sock
```
**Symbols:**

```
ffffffff81be7030-ffffffff81be73c8: unix_release_sock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void unix_release_sock(struct sock *sk, int embrion);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81d7e630)
Location: net/unix/af_unix.c:576
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_release
  - net/unix/af_unix.c:unix_release_sock
```
**Symbols:**

```
ffffffff81d7e630-ffffffff81d7ea25: unix_release_sock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void unix_release_sock(struct sock *sk, int embrion);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81f4b6e0)
Location: net/unix/af_unix.c:591
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_release
  - net/unix/af_unix.c:unix_release_sock
```
**Symbols:**

```
ffffffff81f4b6e0-ffffffff81f4bb55: unix_release_sock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void unix_release_sock(struct sock *sk, int embrion);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81fab480)
Location: net/unix/af_unix.c:604
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_release
  - net/unix/af_unix.c:unix_release_sock
```
**Symbols:**

```
ffffffff81fab480-ffffffff81fab90a: unix_release_sock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void unix_release_sock(struct sock *sk, int embrion);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff82078870)
Location: net/unix/af_unix.c:603
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_release
  - net/unix/af_unix.c:unix_release_sock
```
**Symbols:**

```
ffffffff82078870-ffffffff82078cfa: unix_release_sock (STB_LOCAL)
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
void unix_release_sock(struct sock *sk, int embrion);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffff800010cf1080)
Location: net/unix/af_unix.c:515
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_release
  - net/unix/af_unix.c:unix_release_sock
```
**Symbols:**

```
ffff800010cf1080-ffff800010cf1424: unix_release_sock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void unix_release_sock(struct sock *sk, int embrion);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (c0df8184)
Location: net/unix/af_unix.c:515
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_release
  - net/unix/af_unix.c:unix_release_sock
```
**Symbols:**

```
c0df8184-c0df845c: unix_release_sock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void unix_release_sock(struct sock *sk, int embrion);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (c000000000e16030)
Location: net/unix/af_unix.c:515
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_release
  - net/unix/af_unix.c:unix_release_sock
```
**Symbols:**

```
c000000000e16030-c000000000e16424: unix_release_sock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void unix_release_sock(struct sock *sk, int embrion);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffe00083d35e)
Location: net/unix/af_unix.c:515
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_release
  - net/unix/af_unix.c:unix_release_sock
```
**Symbols:**

```
ffffffe00083d35e-ffffffe00083d618: unix_release_sock (STB_LOCAL)
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
void unix_release_sock(struct sock *sk, int embrion);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff819d0510)
Location: net/unix/af_unix.c:515
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_release
  - net/unix/af_unix.c:unix_release_sock
```
**Symbols:**

```
ffffffff819d0510-ffffffff819d07e9: unix_release_sock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void unix_release_sock(struct sock *sk, int embrion);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff8198d2d0)
Location: net/unix/af_unix.c:515
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_release
  - net/unix/af_unix.c:unix_release_sock
```
**Symbols:**

```
ffffffff8198d2d0-ffffffff8198d5a9: unix_release_sock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void unix_release_sock(struct sock *sk, int embrion);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81a3af90)
Location: net/unix/af_unix.c:515
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_release
  - net/unix/af_unix.c:unix_release_sock
```
**Symbols:**

```
ffffffff81a3af90-ffffffff81a3b269: unix_release_sock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void unix_release_sock(struct sock *sk, int embrion);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81a48770)
Location: net/unix/af_unix.c:515
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_release
  - net/unix/af_unix.c:unix_release_sock
```
**Symbols:**

```
ffffffff81a48770-ffffffff81a48a4d: unix_release_sock (STB_LOCAL)
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
