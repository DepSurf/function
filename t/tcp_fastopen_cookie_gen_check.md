# Function: <code>tcp_fastopen_cookie_gen_check</code>

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
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff819a90ae)
Location: net/ipv4/tcp_fastopen.c:204
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
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
In net/ipv4/tcp_fastopen.c (ffffffff819dfe80)
Location: net/ipv4/tcp_fastopen.c:204
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tcp_fastopen_cookie_gen_check(struct sock *sk, struct request_sock *req, struct sk_buff *syn, struct tcp_fastopen_cookie *orig, struct tcp_fastopen_cookie *valid_foc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff81accee0)
Location: net/ipv4/tcp_fastopen.c:227
Inline: False
Direct callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
**Symbols:**

```
ffffffff81accee0-ffffffff81acd04b: tcp_fastopen_cookie_gen_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tcp_fastopen_cookie_gen_check(struct sock *sk, struct request_sock *req, struct sk_buff *syn, struct tcp_fastopen_cookie *orig, struct tcp_fastopen_cookie *valid_foc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff81ad8ee0)
Location: net/ipv4/tcp_fastopen.c:227
Inline: False
Direct callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
**Symbols:**

```
ffffffff81ad8ee0-ffffffff81ad9058: tcp_fastopen_cookie_gen_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff81ac436c)
Location: net/ipv4/tcp_fastopen.c:227
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
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
In net/ipv4/tcp_fastopen.c (ffffffff81b82aa2)
Location: net/ipv4/tcp_fastopen.c:216
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
In net/ipv4/tcp_fastopen.c (ffffffff81d1309b)
Location: net/ipv4/tcp_fastopen.c:210
Inline: True
Inline callers:
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
In net/ipv4/tcp_fastopen.c (ffffffff81ed900b)
Location: net/ipv4/tcp_fastopen.c:210
Inline: True
Inline callers:
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
In net/ipv4/tcp_fastopen.c (ffffffff81f3810e)
Location: net/ipv4/tcp_fastopen.c:210
Inline: True
Inline callers:
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
In net/ipv4/tcp_fastopen.c (ffffffff81ffe1ce)
Location: net/ipv4/tcp_fastopen.c:210
Inline: True
Inline callers:
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
In net/ipv4/tcp_fastopen.c (ffff800010c93a90)
Location: net/ipv4/tcp_fastopen.c:204
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
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
In net/ipv4/tcp_fastopen.c (c0da2180)
Location: net/ipv4/tcp_fastopen.c:204
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
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
In net/ipv4/tcp_fastopen.c (c000000000da3f24)
Location: net/ipv4/tcp_fastopen.c:204
Inline: True
Inline callers:
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
In net/ipv4/tcp_fastopen.c (ffffffe0007f307c)
Location: net/ipv4/tcp_fastopen.c:204
Inline: True
Inline callers:
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
In net/ipv4/tcp_fastopen.c (ffffffff8197fcf0)
Location: net/ipv4/tcp_fastopen.c:204
Inline: True
Inline callers:
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
In net/ipv4/tcp_fastopen.c (ffffffff819397b0)
Location: net/ipv4/tcp_fastopen.c:204
Inline: True
Inline callers:
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
In net/ipv4/tcp_fastopen.c (ffffffff819ea4c0)
Location: net/ipv4/tcp_fastopen.c:204
Inline: True
Inline callers:
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
In net/ipv4/tcp_fastopen.c (ffffffff819f42fe)
Location: net/ipv4/tcp_fastopen.c:204
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
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
</ul>
