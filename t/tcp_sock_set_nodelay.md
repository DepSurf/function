# Function: <code>tcp_sock_set_nodelay</code>

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
void tcp_sock_set_nodelay(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81aa8e00)
Location: net/ipv4/tcp.c:2910
Inline: False
```
**Symbols:**

```
ffffffff81aa8e00-ffffffff81aa8e74: tcp_sock_set_nodelay (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void tcp_sock_set_nodelay(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81ab32a0)
Location: net/ipv4/tcp.c:3168
Inline: False
```
**Symbols:**

```
ffffffff81ab32a0-ffffffff81ab3314: tcp_sock_set_nodelay (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void tcp_sock_set_nodelay(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81a9e500)
Location: net/ipv4/tcp.c:3222
Inline: False
```
**Symbols:**

```
ffffffff81a9e500-ffffffff81a9e574: tcp_sock_set_nodelay (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void tcp_sock_set_nodelay(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81b5a0b0)
Location: net/ipv4/tcp.c:3246
Inline: False
```
**Symbols:**

```
ffffffff81b5a0b0-ffffffff81b5a124: tcp_sock_set_nodelay (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void tcp_sock_set_nodelay(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81ce8790)
Location: net/ipv4/tcp.c:3264
Inline: False
```
**Symbols:**

```
ffffffff81ce8790-ffffffff81ce8810: tcp_sock_set_nodelay (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void tcp_sock_set_nodelay(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81eabf20)
Location: net/ipv4/tcp.c:3363
Inline: False
```
**Symbols:**

```
ffffffff81eabf20-ffffffff81eabfa0: tcp_sock_set_nodelay (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void tcp_sock_set_nodelay(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81f0a7a0)
Location: net/ipv4/tcp.c:3255
Inline: False
```
**Symbols:**

```
ffffffff81f0a7a0-ffffffff81f0a820: tcp_sock_set_nodelay (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void tcp_sock_set_nodelay(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81fce820)
Location: net/ipv4/tcp.c:3261
Inline: False
```
**Symbols:**

```
ffffffff81fce820-ffffffff81fce8a0: tcp_sock_set_nodelay (STB_GLOBAL)
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
