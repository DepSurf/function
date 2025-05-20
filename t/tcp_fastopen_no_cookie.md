# Function: <code>tcp_fastopen_no_cookie</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool tcp_fastopen_no_cookie(const struct sock *sk, const struct dst_entry *dst, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff818c0420)
Location: net/ipv4/tcp_fastopen.c:312
Inline: False
Direct callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
**Symbols:**

```
ffffffff818c0420-ffffffff818c045c: tcp_fastopen_no_cookie (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool tcp_fastopen_no_cookie(const struct sock *sk, const struct dst_entry *dst, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff81915f70)
Location: net/ipv4/tcp_fastopen.c:312
Inline: False
Direct callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
**Symbols:**

```
ffffffff81915f70-ffffffff81915fae: tcp_fastopen_no_cookie (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool tcp_fastopen_no_cookie(const struct sock *sk, const struct dst_entry *dst, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff81944710)
Location: net/ipv4/tcp_fastopen.c:312
Inline: False
Direct callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
**Symbols:**

```
ffffffff81944710-ffffffff8194474e: tcp_fastopen_no_cookie (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool tcp_fastopen_no_cookie(const struct sock *sk, const struct dst_entry *dst, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff819a8d00)
Location: net/ipv4/tcp_fastopen.c:325
Inline: False
Direct callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
**Symbols:**

```
ffffffff819a8d00-ffffffff819a8d3e: tcp_fastopen_no_cookie (STB_LOCAL)
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
In net/ipv4/tcp_fastopen.c (ffffffff819e0202)
Location: net/ipv4/tcp_fastopen.c:325
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool tcp_fastopen_no_cookie(const struct sock *sk, const struct dst_entry *dst, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff81accc40)
Location: net/ipv4/tcp_fastopen.c:348
Inline: False
Direct callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
**Symbols:**

```
ffffffff81accc40-ffffffff81accc7e: tcp_fastopen_no_cookie (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool tcp_fastopen_no_cookie(const struct sock *sk, const struct dst_entry *dst, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff81ad8c40)
Location: net/ipv4/tcp_fastopen.c:348
Inline: False
Direct callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
**Symbols:**

```
ffffffff81ad8c40-ffffffff81ad8c7e: tcp_fastopen_no_cookie (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool tcp_fastopen_no_cookie(const struct sock *sk, const struct dst_entry *dst, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff81ac3cb0)
Location: net/ipv4/tcp_fastopen.c:348
Inline: False
Direct callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
**Symbols:**

```
ffffffff81ac3cb0-ffffffff81ac3cee: tcp_fastopen_no_cookie (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff81b82a29)
Location: net/ipv4/tcp_fastopen.c:337
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff81d13655)
Location: net/ipv4/tcp_fastopen.c:331
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff81ed95f5)
Location: net/ipv4/tcp_fastopen.c:332
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff81f386d5)
Location: net/ipv4/tcp_fastopen.c:334
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff81ffe795)
Location: net/ipv4/tcp_fastopen.c:334
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
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
In net/ipv4/tcp_fastopen.c (ffff800010c93dfc)
Location: net/ipv4/tcp_fastopen.c:325
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool tcp_fastopen_no_cookie(const struct sock *sk, const struct dst_entry *dst, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (c0da1d34)
Location: net/ipv4/tcp_fastopen.c:325
Inline: False
Direct callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
**Symbols:**

```
c0da1d34-c0da1d94: tcp_fastopen_no_cookie (STB_LOCAL)
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
In net/ipv4/tcp_fastopen.c (c000000000da43d0)
Location: net/ipv4/tcp_fastopen.c:325
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
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
In net/ipv4/tcp_fastopen.c (ffffffe0007f33b4)
Location: net/ipv4/tcp_fastopen.c:325
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
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
In net/ipv4/tcp_fastopen.c (ffffffff81980072)
Location: net/ipv4/tcp_fastopen.c:325
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
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
In net/ipv4/tcp_fastopen.c (ffffffff81939b32)
Location: net/ipv4/tcp_fastopen.c:325
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
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
In net/ipv4/tcp_fastopen.c (ffffffff819ea842)
Location: net/ipv4/tcp_fastopen.c:325
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
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
In net/ipv4/tcp_fastopen.c (ffffffff819f46b2)
Location: net/ipv4/tcp_fastopen.c:325
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
