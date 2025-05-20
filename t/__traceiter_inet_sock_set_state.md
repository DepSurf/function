# Function: <code>__traceiter_inet_sock_set_state</code>

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
int __traceiter_inet_sock_set_state(void *__data, const struct sock *sk, const int oldstate, const int newstate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81a446f0)
Location: include/trace/events/sock.h:138
Inline: False
```
**Symbols:**

```
ffffffff81a446f0-ffffffff81a44741: __traceiter_inet_sock_set_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __traceiter_inet_sock_set_state(void *__data, const struct sock *sk, const int oldstate, const int newstate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81a29550)
Location: include/trace/events/sock.h:138
Inline: False
```
**Symbols:**

```
ffffffff81a29550-ffffffff81a2959f: __traceiter_inet_sock_set_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __traceiter_inet_sock_set_state(void *__data, const struct sock *sk, const int oldstate, const int newstate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81ade330)
Location: include/trace/events/sock.h:138
Inline: False
```
**Symbols:**

```
ffffffff81ade330-ffffffff81ade37f: __traceiter_inet_sock_set_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __traceiter_inet_sock_set_state(void *__data, const struct sock *sk, const int oldstate, const int newstate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81c5fae0)
Location: include/trace/events/sock.h:140
Inline: False
```
**Symbols:**

```
ffffffff81c5fae0-ffffffff81c5fb3b: __traceiter_inet_sock_set_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __traceiter_inet_sock_set_state(void *__data, const struct sock *sk, const int oldstate, const int newstate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81e164e0)
Location: include/trace/events/sock.h:140
Inline: False
```
**Symbols:**

```
ffffffff81e164e0-ffffffff81e1653b: __traceiter_inet_sock_set_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __traceiter_inet_sock_set_state(void *__data, const struct sock *sk, const int oldstate, const int newstate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81e89ef0)
Location: include/trace/events/sock.h:140
Inline: False
```
**Symbols:**

```
ffffffff81e89ef0-ffffffff81e89f4b: __traceiter_inet_sock_set_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __traceiter_inet_sock_set_state(void *__data, const struct sock *sk, const int oldstate, const int newstate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81f4bf00)
Location: include/trace/events/sock.h:140
Inline: False
```
**Symbols:**

```
ffffffff81f4bf00-ffffffff81f4bf5b: __traceiter_inet_sock_set_state (STB_GLOBAL)
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
