# Function: <code>sock_bindtoindex</code>

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
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int sock_bindtoindex(struct sock *sk, int ifindex, bool lock_sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819e8c8f)
Location: net/core/sock.c:597
Inline: True
Inline callers:
  - net/core/sock.c:sock_setsockopt
Direct callers:
  - net/core/filter.c:_bpf_setsockopt
```
**Symbols:**

```
ffffffff819e8160-ffffffff819e81b4: sock_bindtoindex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int sock_bindtoindex(struct sock *sk, int ifindex, bool lock_sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819e8a2c)
Location: net/core/sock.c:587
Inline: True
Inline callers:
  - net/core/sock.c:sock_setsockopt
Direct callers:
  - net/core/filter.c:_bpf_setsockopt
```
**Symbols:**

```
ffffffff819e7dd0-ffffffff819e7e24: sock_bindtoindex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int sock_bindtoindex(struct sock *sk, int ifindex, bool lock_sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819ceb98)
Location: net/core/sock.c:595
Inline: True
Inline callers:
  - net/core/sock.c:sock_setsockopt
Direct callers:
  - net/core/filter.c:_bpf_setsockopt
```
**Symbols:**

```
ffffffff819cdda0-ffffffff819cddf4: sock_bindtoindex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int sock_bindtoindex(struct sock *sk, int ifindex, bool lock_sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81a7e7ea)
Location: net/core/sock.c:614
Inline: True
Inline callers:
  - net/core/sock.c:sock_setsockopt
Direct callers:
  - net/core/filter.c:_bpf_setsockopt
```
**Symbols:**

```
ffffffff81a7d580-ffffffff81a7d612: sock_bindtoindex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int sock_bindtoindex(struct sock *sk, int ifindex, bool lock_sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81bf1a3c)
Location: net/core/sock.c:653
Inline: True
Inline callers:
  - net/core/sock.c:sock_setsockopt
Direct callers:
  - net/core/filter.c:_bpf_setsockopt
```
**Symbols:**

```
ffffffff81bf0c10-ffffffff81bf0cae: sock_bindtoindex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sock_bindtoindex(struct sock *sk, int ifindex, bool lock_sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81d9d2f0)
Location: net/core/sock.c:653
Inline: False
```
**Symbols:**

```
ffffffff81d9d2f0-ffffffff81d9d38e: sock_bindtoindex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sock_bindtoindex(struct sock *sk, int ifindex, bool lock_sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81e0bb40)
Location: net/core/sock.c:659
Inline: False
```
**Symbols:**

```
ffffffff81e0bb40-ffffffff81e0bbde: sock_bindtoindex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sock_bindtoindex(struct sock *sk, int ifindex, bool lock_sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81ec8560)
Location: net/core/sock.c:656
Inline: False
```
**Symbols:**

```
ffffffff81ec8560-ffffffff81ec85fe: sock_bindtoindex (STB_GLOBAL)
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
