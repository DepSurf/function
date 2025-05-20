# Function: <code>__tcp_fastopen_cookie_gen_cipher</code>

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
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff819a8d40)
Location: net/ipv4/tcp_fastopen.c:111
Inline: True
Direct callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
**Symbols:**

```
ffffffff819a8d40-ffffffff819a8de0: __tcp_fastopen_cookie_gen_cipher.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff819df9a0)
Location: net/ipv4/tcp_fastopen.c:111
Inline: True
Direct callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
**Symbols:**

```
ffffffff819df9a0-ffffffff819dfa40: __tcp_fastopen_cookie_gen_cipher.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff81accf6f)
Location: net/ipv4/tcp_fastopen.c:134
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_gen_check
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_gen_check
Direct callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
**Symbols:**

```
ffffffff81acce50-ffffffff81acced4: __tcp_fastopen_cookie_gen_cipher.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff81ad8f6e)
Location: net/ipv4/tcp_fastopen.c:134
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_gen_check
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_gen_check
Direct callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
**Symbols:**

```
ffffffff81ad8e50-ffffffff81ad8ed4: __tcp_fastopen_cookie_gen_cipher.isra.0 (STB_LOCAL)
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
In net/ipv4/tcp_fastopen.c (ffffffff81ac43d7)
Location: net/ipv4/tcp_fastopen.c:134
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
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
In net/ipv4/tcp_fastopen.c (ffffffff81b82b11)
Location: net/ipv4/tcp_fastopen.c:123
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
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
In net/ipv4/tcp_fastopen.c (ffffffff81d13116)
Location: net/ipv4/tcp_fastopen.c:117
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
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
In net/ipv4/tcp_fastopen.c (ffffffff81ed9086)
Location: net/ipv4/tcp_fastopen.c:117
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
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
In net/ipv4/tcp_fastopen.c (ffffffff81f38187)
Location: net/ipv4/tcp_fastopen.c:117
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
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
In net/ipv4/tcp_fastopen.c (ffffffff81ffe247)
Location: net/ipv4/tcp_fastopen.c:117
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffff800010c93288)
Location: net/ipv4/tcp_fastopen.c:111
Inline: True
Direct callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
**Symbols:**

```
ffff800010c93288-ffff800010c93364: __tcp_fastopen_cookie_gen_cipher.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool __tcp_fastopen_cookie_gen_cipher(struct request_sock *req, struct sk_buff *syn, const siphash_key_t *key, struct tcp_fastopen_cookie *foc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (c0da1d94)
Location: net/ipv4/tcp_fastopen.c:111
Inline: True
Direct callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
**Symbols:**

```
c0da1d94-c0da1e48: __tcp_fastopen_cookie_gen_cipher (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_fastopen.c (c000000000da3810)
Location: net/ipv4/tcp_fastopen.c:111
Inline: True
Direct callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
**Symbols:**

```
c000000000da3810-c000000000da38e4: __tcp_fastopen_cookie_gen_cipher.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffe0007f2a30)
Location: net/ipv4/tcp_fastopen.c:111
Inline: True
Direct callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
**Symbols:**

```
ffffffe0007f2a30-ffffffe0007f2af0: __tcp_fastopen_cookie_gen_cipher.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff8197f810)
Location: net/ipv4/tcp_fastopen.c:111
Inline: True
Direct callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
**Symbols:**

```
ffffffff8197f810-ffffffff8197f8b0: __tcp_fastopen_cookie_gen_cipher.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff819392d0)
Location: net/ipv4/tcp_fastopen.c:111
Inline: True
Direct callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
**Symbols:**

```
ffffffff819392d0-ffffffff81939370: __tcp_fastopen_cookie_gen_cipher.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff819e9fe0)
Location: net/ipv4/tcp_fastopen.c:111
Inline: True
Direct callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
**Symbols:**

```
ffffffff819e9fe0-ffffffff819ea080: __tcp_fastopen_cookie_gen_cipher.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff819f3e10)
Location: net/ipv4/tcp_fastopen.c:111
Inline: True
Direct callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
**Symbols:**

```
ffffffff819f3e10-ffffffff819f3eb0: __tcp_fastopen_cookie_gen_cipher.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
