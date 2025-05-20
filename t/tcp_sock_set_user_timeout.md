# Function: <code>tcp_sock_set_user_timeout</code>

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
void tcp_sock_set_user_timeout(struct sock *sk, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81aa7930)
Location: net/ipv4/tcp.c:2955
Inline: False
```
**Symbols:**

```
ffffffff81aa7930-ffffffff81aa795d: tcp_sock_set_user_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void tcp_sock_set_user_timeout(struct sock *sk, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81ab1fb0)
Location: net/ipv4/tcp.c:3213
Inline: False
```
**Symbols:**

```
ffffffff81ab1fb0-ffffffff81ab1fdd: tcp_sock_set_user_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void tcp_sock_set_user_timeout(struct sock *sk, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81a9d240)
Location: net/ipv4/tcp.c:3267
Inline: False
```
**Symbols:**

```
ffffffff81a9d240-ffffffff81a9d26d: tcp_sock_set_user_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void tcp_sock_set_user_timeout(struct sock *sk, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81b59110)
Location: net/ipv4/tcp.c:3291
Inline: False
```
**Symbols:**

```
ffffffff81b59110-ffffffff81b5913d: tcp_sock_set_user_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void tcp_sock_set_user_timeout(struct sock *sk, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81ce73e0)
Location: net/ipv4/tcp.c:3309
Inline: False
```
**Symbols:**

```
ffffffff81ce73e0-ffffffff81ce7415: tcp_sock_set_user_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void tcp_sock_set_user_timeout(struct sock *sk, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81eaab40)
Location: net/ipv4/tcp.c:3408
Inline: False
```
**Symbols:**

```
ffffffff81eaab40-ffffffff81eaab75: tcp_sock_set_user_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void tcp_sock_set_user_timeout(struct sock *sk, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81f09330)
Location: net/ipv4/tcp.c:3300
Inline: False
```
**Symbols:**

```
ffffffff81f09330-ffffffff81f09365: tcp_sock_set_user_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int tcp_sock_set_user_timeout(struct sock *sk, int val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81fd535d)
Location: net/ipv4/tcp.c:3304
Inline: True
Inline callers:
  - net/ipv4/tcp.c:do_tcp_setsockopt
```
**Symbols:**

```
ffffffff81fcd140-ffffffff81fcd16e: tcp_sock_set_user_timeout (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>u32 val</code> ➡️ <code>int val</code>
</li>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
</li>
</ul>
