# Function: <code>__traceiter_sock_exceed_buf_limit</code>

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
<summary>In <code>5.11</code>: ✅</summary>

```c
int __traceiter_sock_exceed_buf_limit(void *__data, struct sock *sk, struct proto *prot, long int allocated, int kind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81a44690)
Location: include/trace/events/sock.h:93
Inline: False
```
**Symbols:**

```
ffffffff81a44690-ffffffff81a446eb: __traceiter_sock_exceed_buf_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __traceiter_sock_exceed_buf_limit(void *__data, struct sock *sk, struct proto *prot, long int allocated, int kind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81a294f0)
Location: include/trace/events/sock.h:93
Inline: False
```
**Symbols:**

```
ffffffff81a294f0-ffffffff81a29549: __traceiter_sock_exceed_buf_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __traceiter_sock_exceed_buf_limit(void *__data, struct sock *sk, struct proto *prot, long int allocated, int kind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81ade2d0)
Location: include/trace/events/sock.h:93
Inline: False
```
**Symbols:**

```
ffffffff81ade2d0-ffffffff81ade329: __traceiter_sock_exceed_buf_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __traceiter_sock_exceed_buf_limit(void *__data, struct sock *sk, struct proto *prot, long int allocated, int kind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81c5fa70)
Location: include/trace/events/sock.h:93
Inline: False
```
**Symbols:**

```
ffffffff81c5fa70-ffffffff81c5fad8: __traceiter_sock_exceed_buf_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __traceiter_sock_exceed_buf_limit(void *__data, struct sock *sk, struct proto *prot, long int allocated, int kind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81e16460)
Location: include/trace/events/sock.h:93
Inline: False
```
**Symbols:**

```
ffffffff81e16460-ffffffff81e164c8: __traceiter_sock_exceed_buf_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __traceiter_sock_exceed_buf_limit(void *__data, struct sock *sk, struct proto *prot, long int allocated, int kind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81e89e50)
Location: include/trace/events/sock.h:93
Inline: False
```
**Symbols:**

```
ffffffff81e89e50-ffffffff81e89eb8: __traceiter_sock_exceed_buf_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __traceiter_sock_exceed_buf_limit(void *__data, struct sock *sk, struct proto *prot, long int allocated, int kind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81f4be60)
Location: include/trace/events/sock.h:93
Inline: False
```
**Symbols:**

```
ffffffff81f4be60-ffffffff81f4bec8: __traceiter_sock_exceed_buf_limit (STB_GLOBAL)
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
