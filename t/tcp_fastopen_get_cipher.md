# Function: <code>tcp_fastopen_get_cipher</code>

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
int tcp_fastopen_get_cipher(struct net *net, struct inet_connection_sock *icsk, u64 *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff81acd500)
Location: net/ipv4/tcp_fastopen.c:111
Inline: False
Direct callers:
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
```
**Symbols:**

```
ffffffff81acd500-ffffffff81acd558: tcp_fastopen_get_cipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tcp_fastopen_get_cipher(struct net *net, struct inet_connection_sock *icsk, u64 *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff81ad9520)
Location: net/ipv4/tcp_fastopen.c:111
Inline: False
Direct callers:
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
```
**Symbols:**

```
ffffffff81ad9520-ffffffff81ad9583: tcp_fastopen_get_cipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tcp_fastopen_get_cipher(struct net *net, struct inet_connection_sock *icsk, u64 *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff81ac4210)
Location: net/ipv4/tcp_fastopen.c:111
Inline: False
Direct callers:
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
```
**Symbols:**

```
ffffffff81ac4210-ffffffff81ac4273: tcp_fastopen_get_cipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int tcp_fastopen_get_cipher(struct net *net, struct inet_connection_sock *icsk, u64 *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff81b82870)
Location: net/ipv4/tcp_fastopen.c:100
Inline: False
Direct callers:
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
```
**Symbols:**

```
ffffffff81b82870-ffffffff81b82946: tcp_fastopen_get_cipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int tcp_fastopen_get_cipher(struct net *net, struct inet_connection_sock *icsk, u64 *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff81d12e10)
Location: net/ipv4/tcp_fastopen.c:94
Inline: False
Direct callers:
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
```
**Symbols:**

```
ffffffff81d12e10-ffffffff81d12ef1: tcp_fastopen_get_cipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tcp_fastopen_get_cipher(struct net *net, struct inet_connection_sock *icsk, u64 *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff81ed8d60)
Location: net/ipv4/tcp_fastopen.c:94
Inline: False
Direct callers:
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
```
**Symbols:**

```
ffffffff81ed8d60-ffffffff81ed8e41: tcp_fastopen_get_cipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tcp_fastopen_get_cipher(struct net *net, struct inet_connection_sock *icsk, u64 *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff81f37e70)
Location: net/ipv4/tcp_fastopen.c:94
Inline: False
Direct callers:
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
```
**Symbols:**

```
ffffffff81f37e70-ffffffff81f37f51: tcp_fastopen_get_cipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tcp_fastopen_get_cipher(struct net *net, struct inet_connection_sock *icsk, u64 *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff81ffdf30)
Location: net/ipv4/tcp_fastopen.c:94
Inline: False
Direct callers:
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
```
**Symbols:**

```
ffffffff81ffdf30-ffffffff81ffe011: tcp_fastopen_get_cipher (STB_GLOBAL)
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
