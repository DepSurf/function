# Function: <code>sock_get_timeout</code>

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
<summary>In <code>5.3</code>: ✅</summary>

```c
int sock_get_timeout(long int timeo, void *optval, bool old_timeval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff818df190)
Location: net/core/sock.c:333
Inline: False
Direct callers:
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
```
**Symbols:**

```
ffffffff818df190-ffffffff818df259: sock_get_timeout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int sock_get_timeout(long int timeo, void *optval, bool old_timeval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81911360)
Location: net/core/sock.c:333
Inline: False
Direct callers:
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
```
**Symbols:**

```
ffffffff81911360-ffffffff81911429: sock_get_timeout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int sock_get_timeout(long int timeo, void *optval, bool old_timeval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819e4f50)
Location: net/core/sock.c:333
Inline: False
Direct callers:
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
```
**Symbols:**

```
ffffffff819e4f50-ffffffff819e501c: sock_get_timeout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sock_get_timeout(long int timeo, void *optval, bool old_timeval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819e4820)
Location: net/core/sock.c:334
Inline: False
Direct callers:
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
```
**Symbols:**

```
ffffffff819e4820-ffffffff819e48ec: sock_get_timeout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sock_get_timeout(long int timeo, void *optval, bool old_timeval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819ca8a0)
Location: net/core/sock.c:334
Inline: False
Direct callers:
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
```
**Symbols:**

```
ffffffff819ca8a0-ffffffff819ca96f: sock_get_timeout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int sock_get_timeout(long int timeo, void *optval, bool old_timeval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81a79ed0)
Location: net/core/sock.c:353
Inline: False
Direct callers:
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
```
**Symbols:**

```
ffffffff81a79ed0-ffffffff81a79f9f: sock_get_timeout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int sock_get_timeout(long int timeo, void *optval, bool old_timeval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81bf28dd)
Location: net/core/sock.c:359
Inline: True
Inline callers:
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
```
**Symbols:**

```
ffffffff81beb770-ffffffff81beb832: sock_get_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int sock_get_timeout(long int timeo, void *optval, bool old_timeval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81da0076)
Location: net/core/sock.c:359
Inline: True
Inline callers:
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
```
**Symbols:**

```
ffffffff81d98150-ffffffff81d98212: sock_get_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int sock_get_timeout(long int timeo, void *optval, bool old_timeval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81e0f485)
Location: net/core/sock.c:363
Inline: True
Inline callers:
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
```
**Symbols:**

```
ffffffff81e067c0-ffffffff81e06882: sock_get_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int sock_get_timeout(long int timeo, void *optval, bool old_timeval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81ecb33a)
Location: net/core/sock.c:360
Inline: True
Inline callers:
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
```
**Symbols:**

```
ffffffff81ec3080-ffffffff81ec3142: sock_get_timeout (STB_GLOBAL)
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
In net/core/sock.c (ffff800010baf204)
Location: net/core/sock.c:333
Inline: True
Inline callers:
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
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
In net/core/sock.c (c0cccd14)
Location: net/core/sock.c:333
Inline: True
Inline callers:
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
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
In net/core/sock.c (c000000000c84fd4)
Location: net/core/sock.c:333
Inline: True
Inline callers:
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
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
In net/core/sock.c (ffffffe000740bde)
Location: net/core/sock.c:333
Inline: True
Inline callers:
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
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
int sock_get_timeout(long int timeo, void *optval, bool old_timeval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff818b1360)
Location: net/core/sock.c:333
Inline: False
Direct callers:
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
```
**Symbols:**

```
ffffffff818b1360-ffffffff818b1429: sock_get_timeout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int sock_get_timeout(long int timeo, void *optval, bool old_timeval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff8186b2b0)
Location: net/core/sock.c:333
Inline: False
Direct callers:
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
```
**Symbols:**

```
ffffffff8186b2b0-ffffffff8186b379: sock_get_timeout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int sock_get_timeout(long int timeo, void *optval, bool old_timeval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81902360)
Location: net/core/sock.c:333
Inline: False
Direct callers:
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
```
**Symbols:**

```
ffffffff81902360-ffffffff81902429: sock_get_timeout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int sock_get_timeout(long int timeo, void *optval, bool old_timeval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81923300)
Location: net/core/sock.c:333
Inline: False
Direct callers:
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
```
**Symbols:**

```
ffffffff81923300-ffffffff819233c9: sock_get_timeout (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
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
