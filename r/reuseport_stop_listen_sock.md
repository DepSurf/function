# Function: <code>reuseport_stop_listen_sock</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void reuseport_stop_listen_sock(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff81ad1e70)
Location: net/core/sock_reuseport.c:377
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
```
**Symbols:**

```
ffffffff81ad1e70-ffffffff81ad1f42: reuseport_stop_listen_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void reuseport_stop_listen_sock(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff81c4f850)
Location: net/core/sock_reuseport.c:377
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
```
**Symbols:**

```
ffffffff81c4f850-ffffffff81c4f944: reuseport_stop_listen_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void reuseport_stop_listen_sock(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff81e04c90)
Location: net/core/sock_reuseport.c:463
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
```
**Symbols:**

```
ffffffff81e04c90-ffffffff81e04d6f: reuseport_stop_listen_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void reuseport_stop_listen_sock(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff81e774e0)
Location: net/core/sock_reuseport.c:463
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
```
**Symbols:**

```
ffffffff81e774e0-ffffffff81e775bf: reuseport_stop_listen_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void reuseport_stop_listen_sock(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff81f374a0)
Location: net/core/sock_reuseport.c:463
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
```
**Symbols:**

```
ffffffff81f374a0-ffffffff81f3757f: reuseport_stop_listen_sock (STB_GLOBAL)
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
