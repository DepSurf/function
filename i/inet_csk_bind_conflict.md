# Function: <code>inet_csk_bind_conflict</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int inet_csk_bind_conflict(const struct sock *sk, const struct inet_bind_bucket *tb, bool relax);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81763a40)
Location: net/ipv4/inet_connection_sock.c:46
Inline: False
```
**Symbols:**

```
ffffffff81763a40-ffffffff81763b6a: inet_csk_bind_conflict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int inet_csk_bind_conflict(const struct sock *sk, const struct inet_bind_bucket *tb, bool relax);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff817cff10)
Location: net/ipv4/inet_connection_sock.c:47
Inline: False
```
**Symbols:**

```
ffffffff817cff10-ffffffff817d0051: inet_csk_bind_conflict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int inet_csk_bind_conflict(const struct sock *sk, const struct inet_bind_bucket *tb, bool relax, bool reuseport_ok);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff817ffd00)
Location: net/ipv4/inet_connection_sock.c:47
Inline: False
```
**Symbols:**

```
ffffffff817ffd00-ffffffff817ffe71: inet_csk_bind_conflict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int inet_csk_bind_conflict(const struct sock *sk, const struct inet_bind_bucket *tb, bool relax, bool reuseport_ok);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81820910)
Location: net/ipv4/inet_connection_sock.c:128
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
**Symbols:**

```
ffffffff81820910-ffffffff81820a64: inet_csk_bind_conflict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int inet_csk_bind_conflict(const struct sock *sk, const struct inet_bind_bucket *tb, bool relax, bool reuseport_ok);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff8189f870)
Location: net/ipv4/inet_connection_sock.c:128
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
**Symbols:**

```
ffffffff8189f870-ffffffff8189f9c4: inet_csk_bind_conflict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int inet_csk_bind_conflict(const struct sock *sk, const struct inet_bind_bucket *tb, bool relax, bool reuseport_ok);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff818f4340)
Location: net/ipv4/inet_connection_sock.c:123
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
**Symbols:**

```
ffffffff818f4340-ffffffff818f44a9: inet_csk_bind_conflict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int inet_csk_bind_conflict(const struct sock *sk, const struct inet_bind_bucket *tb, bool relax, bool reuseport_ok);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81921e50)
Location: net/ipv4/inet_connection_sock.c:132
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
**Symbols:**

```
ffffffff81921e50-ffffffff81921fb9: inet_csk_bind_conflict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int inet_csk_bind_conflict(const struct sock *sk, const struct inet_bind_bucket *tb, bool relax, bool reuseport_ok);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81984840)
Location: net/ipv4/inet_connection_sock.c:128
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
**Symbols:**

```
ffffffff81984840-ffffffff819849ab: inet_csk_bind_conflict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int inet_csk_bind_conflict(const struct sock *sk, const struct inet_bind_bucket *tb, bool relax, bool reuseport_ok);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff819baff0)
Location: net/ipv4/inet_connection_sock.c:128
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
**Symbols:**

```
ffffffff819baff0-ffffffff819bb15b: inet_csk_bind_conflict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int inet_csk_bind_conflict(const struct sock *sk, const struct inet_bind_bucket *tb, bool relax, bool reuseport_ok);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81aa5cc0)
Location: net/ipv4/inet_connection_sock.c:133
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_find_open_port
```
**Symbols:**

```
ffffffff81aa5cc0-ffffffff81aa5dfe: inet_csk_bind_conflict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int inet_csk_bind_conflict(const struct sock *sk, const struct inet_bind_bucket *tb, bool relax, bool reuseport_ok);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81ab0300)
Location: net/ipv4/inet_connection_sock.c:133
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_find_open_port
```
**Symbols:**

```
ffffffff81ab0300-ffffffff81ab043e: inet_csk_bind_conflict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int inet_csk_bind_conflict(const struct sock *sk, const struct inet_bind_bucket *tb, bool relax, bool reuseport_ok);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81a9b4e0)
Location: net/ipv4/inet_connection_sock.c:133
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_find_open_port
```
**Symbols:**

```
ffffffff81a9b4e0-ffffffff81a9b61e: inet_csk_bind_conflict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int inet_csk_bind_conflict(const struct sock *sk, const struct inet_bind_bucket *tb, bool relax, bool reuseport_ok);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81b56950)
Location: net/ipv4/inet_connection_sock.c:133
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_find_open_port
```
**Symbols:**

```
ffffffff81b56950-ffffffff81b56ab2: inet_csk_bind_conflict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int inet_csk_bind_conflict(const struct sock *sk, const struct inet_bind_bucket *tb, bool relax, bool reuseport_ok);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81ce47a0)
Location: net/ipv4/inet_connection_sock.c:133
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
**Symbols:**

```
ffffffff81ce47a0-ffffffff81ce4935: inet_csk_bind_conflict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int inet_csk_bind_conflict(const struct sock *sk, const struct inet_bind_bucket *tb, const struct inet_bind2_bucket *tb2, bool relax, bool reuseport_ok);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81ea72d0)
Location: net/ipv4/inet_connection_sock.c:214
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
**Symbols:**

```
ffffffff81ea72d0-ffffffff81ea743f: inet_csk_bind_conflict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int inet_csk_bind_conflict(const struct sock *sk, const struct inet_bind_bucket *tb, const struct inet_bind2_bucket *tb2, bool relax, bool reuseport_ok);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81f05a70)
Location: net/ipv4/inet_connection_sock.c:235
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
**Symbols:**

```
ffffffff81f05a70-ffffffff81f05bdf: inet_csk_bind_conflict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int inet_csk_bind_conflict(const struct sock *sk, const struct inet_bind_bucket *tb, const struct inet_bind2_bucket *tb2, bool relax, bool reuseport_ok);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81fca370)
Location: net/ipv4/inet_connection_sock.c:235
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
**Symbols:**

```
ffffffff81fca370-ffffffff81fca527: inet_csk_bind_conflict (STB_LOCAL)
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
In net/ipv4/inet_connection_sock.c (ffff800010c6cd68)
Location: net/ipv4/inet_connection_sock.c:128
Inline: True
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
**Symbols:**

```
ffff800010c6cd68-ffff800010c6cef0: inet_csk_bind_conflict.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int inet_csk_bind_conflict(const struct sock *sk, const struct inet_bind_bucket *tb, bool relax, bool reuseport_ok);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (c0d7ba7c)
Location: net/ipv4/inet_connection_sock.c:128
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
**Symbols:**

```
c0d7ba7c-c0d7bbe8: inet_csk_bind_conflict (STB_LOCAL)
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
In net/ipv4/inet_connection_sock.c (c000000000d726f0)
Location: net/ipv4/inet_connection_sock.c:128
Inline: True
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
**Symbols:**

```
c000000000d726f0-c000000000d72914: inet_csk_bind_conflict.isra.0 (STB_LOCAL)
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
In net/ipv4/inet_connection_sock.c (ffffffe0007d2580)
Location: net/ipv4/inet_connection_sock.c:128
Inline: True
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
**Symbols:**

```
ffffffe0007d2580-ffffffe0007d269e: inet_csk_bind_conflict.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int inet_csk_bind_conflict(const struct sock *sk, const struct inet_bind_bucket *tb, bool relax, bool reuseport_ok);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff8195ae60)
Location: net/ipv4/inet_connection_sock.c:128
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
**Symbols:**

```
ffffffff8195ae60-ffffffff8195afcb: inet_csk_bind_conflict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int inet_csk_bind_conflict(const struct sock *sk, const struct inet_bind_bucket *tb, bool relax, bool reuseport_ok);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81914950)
Location: net/ipv4/inet_connection_sock.c:128
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
**Symbols:**

```
ffffffff81914950-ffffffff81914abb: inet_csk_bind_conflict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int inet_csk_bind_conflict(const struct sock *sk, const struct inet_bind_bucket *tb, bool relax, bool reuseport_ok);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff819c5630)
Location: net/ipv4/inet_connection_sock.c:128
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
**Symbols:**

```
ffffffff819c5630-ffffffff819c579b: inet_csk_bind_conflict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int inet_csk_bind_conflict(const struct sock *sk, const struct inet_bind_bucket *tb, bool relax, bool reuseport_ok);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff819cf110)
Location: net/ipv4/inet_connection_sock.c:128
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
**Symbols:**

```
ffffffff819cf110-ffffffff819cf27b: inet_csk_bind_conflict (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool reuseport_ok</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
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
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct inet_bind2_bucket *tb2</code>
</li>
<li>
<b>Param reordered. </b>
<code>sk, tb, relax, reuseport_ok</code> ➡️ <code>sk, tb, tb2, relax, reuseport_ok</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
