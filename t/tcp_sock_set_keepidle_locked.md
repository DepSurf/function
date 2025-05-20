# Function: <code>tcp_sock_set_keepidle_locked</code>

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
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int tcp_sock_set_keepidle_locked(struct sock *sk, int val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81ab92b0)
Location: net/ipv4/tcp.c:3221
Inline: True
Direct callers:
  - net/core/filter.c:_bpf_setsockopt
  - net/ipv4/tcp.c:tcp_sock_set_keepidle
```
**Symbols:**

```
ffffffff81ab92b0-ffffffff81ab9334: tcp_sock_set_keepidle_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int tcp_sock_set_keepidle_locked(struct sock *sk, int val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81aa4540)
Location: net/ipv4/tcp.c:3275
Inline: True
Direct callers:
  - net/core/filter.c:_bpf_setsockopt
  - net/ipv4/tcp.c:tcp_sock_set_keepidle
```
**Symbols:**

```
ffffffff81aa4540-ffffffff81aa45c7: tcp_sock_set_keepidle_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tcp_sock_set_keepidle_locked(struct sock *sk, int val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81b60774)
Location: net/ipv4/tcp.c:3299
Inline: True
Direct callers:
  - net/core/filter.c:_bpf_setsockopt
  - net/ipv4/tcp.c:tcp_sock_set_keepidle
```
**Symbols:**

```
ffffffff81d3a6b5-ffffffff81d3a6d5: tcp_sock_set_keepidle_locked.cold (STB_LOCAL)
ffffffff81b60740-ffffffff81b607e9: tcp_sock_set_keepidle_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int tcp_sock_set_keepidle_locked(struct sock *sk, int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp.c (0)
Location: net/ipv4/tcp.c:3317
Inline: False
Direct callers:
  - net/core/filter.c:_bpf_setsockopt
  - net/ipv4/tcp.c:tcp_sock_set_keepidle
```
**Symbols:**

```
ffffffff81f06eef-ffffffff81f06f09: tcp_sock_set_keepidle_locked.cold (STB_LOCAL)
ffffffff81cef200-ffffffff81cef2a8: tcp_sock_set_keepidle_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int tcp_sock_set_keepidle_locked(struct sock *sk, int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp.c (0)
Location: net/ipv4/tcp.c:3416
Inline: False
Direct callers:
  - net/ipv4/tcp.c:do_tcp_setsockopt
  - net/ipv4/tcp.c:tcp_sock_set_keepidle
```
**Symbols:**

```
ffffffff820ae9c8-ffffffff820ae9e2: tcp_sock_set_keepidle_locked.cold (STB_LOCAL)
ffffffff81eb24e0-ffffffff81eb2588: tcp_sock_set_keepidle_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int tcp_sock_set_keepidle_locked(struct sock *sk, int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp.c (0)
Location: net/ipv4/tcp.c:3308
Inline: False
Direct callers:
  - net/ipv4/tcp.c:do_tcp_setsockopt
  - net/ipv4/tcp.c:tcp_sock_set_keepidle
```
**Symbols:**

```
ffffffff8212fe66-ffffffff8212fe85: tcp_sock_set_keepidle_locked.cold (STB_LOCAL)
ffffffff81f10bd0-ffffffff81f10c82: tcp_sock_set_keepidle_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int tcp_sock_set_keepidle_locked(struct sock *sk, int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp.c (0)
Location: net/ipv4/tcp.c:3317
Inline: False
Direct callers:
  - net/ipv4/tcp.c:do_tcp_setsockopt
  - net/ipv4/tcp.c:tcp_sock_set_keepidle
```
**Symbols:**

```
ffffffff82211b52-ffffffff82211b71: tcp_sock_set_keepidle_locked.cold (STB_LOCAL)
ffffffff81fd4db0-ffffffff81fd4e62: tcp_sock_set_keepidle_locked (STB_GLOBAL)
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
