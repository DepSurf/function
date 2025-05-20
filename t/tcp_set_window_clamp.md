# Function: <code>tcp_set_window_clamp</code>

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
int tcp_set_window_clamp(struct sock *sk, int val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81ab9671)
Location: net/ipv4/tcp.c:3278
Inline: True
Direct callers:
  - net/core/filter.c:_bpf_setsockopt
```
**Symbols:**

```
ffffffff81aba0b0-ffffffff81aba0f2: tcp_set_window_clamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int tcp_set_window_clamp(struct sock *sk, int val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81aa48fc)
Location: net/ipv4/tcp.c:3332
Inline: True
Direct callers:
  - net/core/filter.c:_bpf_setsockopt
```
**Symbols:**

```
ffffffff81aa5340-ffffffff81aa537e: tcp_set_window_clamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int tcp_set_window_clamp(struct sock *sk, int val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81b60b34)
Location: net/ipv4/tcp.c:3356
Inline: True
Direct callers:
  - net/core/filter.c:_bpf_setsockopt
```
**Symbols:**

```
ffffffff81b61680-ffffffff81b616cf: tcp_set_window_clamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int tcp_set_window_clamp(struct sock *sk, int val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81cef6bd)
Location: net/ipv4/tcp.c:3374
Inline: True
Direct callers:
  - net/core/filter.c:_bpf_setsockopt
```
**Symbols:**

```
ffffffff81cf0090-ffffffff81cf00ef: tcp_set_window_clamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int tcp_set_window_clamp(struct sock *sk, int val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81eb2a56)
Location: net/ipv4/tcp.c:3473
Inline: True
Inline callers:
  - net/ipv4/tcp.c:do_tcp_setsockopt
```
**Symbols:**

```
ffffffff81eb25f0-ffffffff81eb264f: tcp_set_window_clamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int tcp_set_window_clamp(struct sock *sk, int val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81f11585)
Location: net/ipv4/tcp.c:3367
Inline: True
Inline callers:
  - net/ipv4/tcp.c:do_tcp_setsockopt
```
**Symbols:**

```
ffffffff81f10cf0-ffffffff81f10d4f: tcp_set_window_clamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tcp_set_window_clamp(struct sock *sk, int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81fd4ed0)
Location: net/ipv4/tcp.c:3372
Inline: False
Direct callers:
  - net/ipv4/tcp.c:do_tcp_setsockopt
```
**Symbols:**

```
ffffffff81fd4ed0-ffffffff81fd4fa7: tcp_set_window_clamp (STB_GLOBAL)
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
