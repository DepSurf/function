# Function: <code>tcp_inq_hint</code>

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
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff818f7394)
Location: net/ipv4/tcp.c:1895
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff819259fb)
Location: net/ipv4/tcp.c:1904
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff819895db)
Location: net/ipv4/tcp.c:1915
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff819c0a43)
Location: net/ipv4/tcp.c:1916
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int tcp_inq_hint(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81aa8af0)
Location: net/ipv4/tcp.c:1986
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
**Symbols:**

```
ffffffff81aa8af0-ffffffff81aa8b5b: tcp_inq_hint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int tcp_inq_hint(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81ab2fa0)
Location: net/ipv4/tcp.c:2225
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
**Symbols:**

```
ffffffff81ab2fa0-ffffffff81ab300b: tcp_inq_hint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int tcp_inq_hint(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81a9e200)
Location: net/ipv4/tcp.c:2268
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
**Symbols:**

```
ffffffff81a9e200-ffffffff81a9e26b: tcp_inq_hint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int tcp_inq_hint(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81b59b50)
Location: net/ipv4/tcp.c:2268
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
**Symbols:**

```
ffffffff81b59b50-ffffffff81b59bbb: tcp_inq_hint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int tcp_inq_hint(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81ce7f10)
Location: net/ipv4/tcp.c:2295
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
```
**Symbols:**

```
ffffffff81ce7f10-ffffffff81ce7f81: tcp_inq_hint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int tcp_inq_hint(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81eac980)
Location: net/ipv4/tcp.c:2395
Inline: True
Direct callers:
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
```
**Symbols:**

```
ffffffff81eac980-ffffffff81eaca03: tcp_inq_hint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int tcp_inq_hint(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81f0b1b0)
Location: net/ipv4/tcp.c:2281
Inline: True
Direct callers:
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
```
**Symbols:**

```
ffffffff81f0b1b0-ffffffff81f0b233: tcp_inq_hint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int tcp_inq_hint(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81fcee80)
Location: net/ipv4/tcp.c:2288
Inline: True
Direct callers:
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
```
**Symbols:**

```
ffffffff81fcee80-ffffffff81fcef03: tcp_inq_hint (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffff800010c70e8c)
Location: net/ipv4/tcp.c:1916
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (c0d800d4)
Location: net/ipv4/tcp.c:1916
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (c000000000d78030)
Location: net/ipv4/tcp.c:1916
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffe0007d67e4)
Location: net/ipv4/tcp.c:1916
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff819608b3)
Location: net/ipv4/tcp.c:1916
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff8191a3a3)
Location: net/ipv4/tcp.c:1916
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff819cb083)
Location: net/ipv4/tcp.c:1916
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff819d4c13)
Location: net/ipv4/tcp.c:1916
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
</details>
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
