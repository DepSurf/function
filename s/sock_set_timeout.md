# Function: <code>sock_set_timeout</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int sock_set_timeout(long int *timeo_p, char *optval, int optlen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff817015a0)
Location: net/core/sock.c:383
Inline: True
Direct callers:
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
```
**Symbols:**

```
ffffffff817015a0-ffffffff817016ce: sock_set_timeout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int sock_set_timeout(long int *timeo_p, char *optval, int optlen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff817686a0)
Location: net/core/sock.c:344
Inline: True
Direct callers:
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
```
**Symbols:**

```
ffffffff817686a0-ffffffff817687ce: sock_set_timeout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int sock_set_timeout(long int *timeo_p, char *optval, int optlen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff817956f0)
Location: net/core/sock.c:344
Inline: True
Direct callers:
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
```
**Symbols:**

```
ffffffff817956f0-ffffffff8179581e: sock_set_timeout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int sock_set_timeout(long int *timeo_p, char *optval, int optlen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff817b33c0)
Location: net/core/sock.c:386
Inline: True
Direct callers:
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
```
**Symbols:**

```
ffffffff817b33c0-ffffffff817b34e5: sock_set_timeout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int sock_set_timeout(long int *timeo_p, char *optval, int optlen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff8182b780)
Location: net/core/sock.c:376
Inline: True
Direct callers:
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
```
**Symbols:**

```
ffffffff8182b780-ffffffff8182b8a5: sock_set_timeout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int sock_set_timeout(long int *timeo_p, char *optval, int optlen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/sock.c (0)
Location: net/core/sock.c:382
Inline: True
Direct callers:
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
```
**Symbols:**

```
ffffffff81875ca0-ffffffff81875d98: sock_set_timeout (STB_LOCAL)
ffffffff81879850-ffffffff81879887: sock_set_timeout.cold.64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int sock_set_timeout(long int *timeo_p, char *optval, int optlen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/sock.c (ffffffff818966c0)
Location: net/core/sock.c:338
Inline: True
Direct callers:
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
```
**Symbols:**

```
ffffffff81896600-ffffffff818966f8: sock_set_timeout (STB_LOCAL)
ffffffff8189a4a0-ffffffff8189a4d7: sock_set_timeout.cold.63 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int sock_set_timeout(long int *timeo_p, char *optval, int optlen, bool old_timeval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/sock.c (0)
Location: net/core/sock.c:366
Inline: False
Direct callers:
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
```
**Symbols:**

```
ffffffff818df880-ffffffff818dfa4d: sock_set_timeout (STB_LOCAL)
ffffffff818e4aa1-ffffffff818e4ad8: sock_set_timeout.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int sock_set_timeout(long int *timeo_p, char *optval, int optlen, bool old_timeval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/sock.c (0)
Location: net/core/sock.c:366
Inline: False
Direct callers:
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
```
**Symbols:**

```
ffffffff81911a50-ffffffff81911c1d: sock_set_timeout (STB_LOCAL)
ffffffff81916c79-ffffffff81916cb0: sock_set_timeout.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int sock_set_timeout(long int *timeo_p, char *optval, int optlen, bool old_timeval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/sock.c (0)
Location: net/core/sock.c:363
Inline: False
Direct callers:
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
```
**Symbols:**

```
ffffffff819e38f0-ffffffff819e3abc: sock_set_timeout (STB_LOCAL)
ffffffff819e9604-ffffffff819e963b: sock_set_timeout.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int sock_set_timeout(long int *timeo_p, sockptr_t optval, int optlen, bool old_timeval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/sock.c (0)
Location: net/core/sock.c:364
Inline: False
Direct callers:
  - net/core/sock.c:sock_setsockopt
```
**Symbols:**

```
ffffffff819e6aa0-ffffffff819e6cd3: sock_set_timeout (STB_LOCAL)
ffffffff81c30445-ffffffff81c3047c: sock_set_timeout.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int sock_set_timeout(long int *timeo_p, sockptr_t optval, int optlen, bool old_timeval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/sock.c (0)
Location: net/core/sock.c:364
Inline: False
Direct callers:
  - net/core/sock.c:sock_setsockopt
```
**Symbols:**

```
ffffffff819cc8a0-ffffffff819ccad3: sock_set_timeout (STB_LOCAL)
ffffffff81c2271d-ffffffff81c22754: sock_set_timeout.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int sock_set_timeout(long int *timeo_p, sockptr_t optval, int optlen, bool old_timeval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/sock.c (0)
Location: net/core/sock.c:383
Inline: False
Direct callers:
  - net/core/sock.c:sock_setsockopt
```
**Symbols:**

```
ffffffff81a7bfe0-ffffffff81a7c213: sock_set_timeout (STB_LOCAL)
ffffffff81d34b6e-ffffffff81d34ba5: sock_set_timeout.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int sock_set_timeout(long int *timeo_p, sockptr_t optval, int optlen, bool old_timeval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/sock.c (0)
Location: net/core/sock.c:423
Inline: False
Direct callers:
  - net/core/sock.c:sock_setsockopt
```
**Symbols:**

```
ffffffff81bf0330-ffffffff81bf0434: sock_set_timeout (STB_LOCAL)
ffffffff81f01085-ffffffff81f010ba: sock_set_timeout.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sock_set_timeout(long int *timeo_p, sockptr_t optval, int optlen, bool old_timeval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81d9bdc0)
Location: net/core/sock.c:423
Inline: False
Direct callers:
  - net/core/sock.c:sk_setsockopt
```
**Symbols:**

```
ffffffff81d9bdc0-ffffffff81d9befb: sock_set_timeout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sock_set_timeout(long int *timeo_p, sockptr_t optval, int optlen, bool old_timeval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81e0a600)
Location: net/core/sock.c:427
Inline: False
Direct callers:
  - net/core/sock.c:sk_setsockopt
```
**Symbols:**

```
ffffffff81e0a600-ffffffff81e0a734: sock_set_timeout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sock_set_timeout(long int *timeo_p, sockptr_t optval, int optlen, bool old_timeval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81ec6ff0)
Location: net/core/sock.c:424
Inline: False
Direct callers:
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
```
**Symbols:**

```
ffffffff81ec6ff0-ffffffff81ec712f: sock_set_timeout (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int sock_set_timeout(long int *timeo_p, char *optval, int optlen, bool old_timeval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffff800010babf50)
Location: net/core/sock.c:366
Inline: False
Direct callers:
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
```
**Symbols:**

```
ffff800010babf50-ffff800010bac144: sock_set_timeout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sock_set_timeout(long int *timeo_p, char *optval, int optlen, bool old_timeval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (c0ccac08)
Location: net/core/sock.c:366
Inline: False
Direct callers:
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
```
**Symbols:**

```
c0ccac08-c0ccae4c: sock_set_timeout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sock_set_timeout(long int *timeo_p, char *optval, int optlen, bool old_timeval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (c000000000c7e880)
Location: net/core/sock.c:366
Inline: False
Direct callers:
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
```
**Symbols:**

```
c000000000c7e880-c000000000c7eb3c: sock_set_timeout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int sock_set_timeout(long int *timeo_p, char *optval, int optlen, bool old_timeval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffe00073cafc)
Location: net/core/sock.c:366
Inline: False
Direct callers:
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
```
**Symbols:**

```
ffffffe00073cafc-ffffffe00073cc48: sock_set_timeout (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int sock_set_timeout(long int *timeo_p, char *optval, int optlen, bool old_timeval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/sock.c (0)
Location: net/core/sock.c:366
Inline: False
Direct callers:
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
```
**Symbols:**

```
ffffffff818b1a50-ffffffff818b1c1d: sock_set_timeout (STB_LOCAL)
ffffffff818b6c79-ffffffff818b6cb0: sock_set_timeout.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int sock_set_timeout(long int *timeo_p, char *optval, int optlen, bool old_timeval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/sock.c (0)
Location: net/core/sock.c:366
Inline: False
Direct callers:
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
```
**Symbols:**

```
ffffffff8186b9a0-ffffffff8186bb6d: sock_set_timeout (STB_LOCAL)
ffffffff81870bc9-ffffffff81870c00: sock_set_timeout.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int sock_set_timeout(long int *timeo_p, char *optval, int optlen, bool old_timeval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/sock.c (0)
Location: net/core/sock.c:366
Inline: False
Direct callers:
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
```
**Symbols:**

```
ffffffff81902a50-ffffffff81902c1d: sock_set_timeout (STB_LOCAL)
ffffffff81907c79-ffffffff81907cb0: sock_set_timeout.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int sock_set_timeout(long int *timeo_p, char *optval, int optlen, bool old_timeval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/sock.c (0)
Location: net/core/sock.c:366
Inline: False
Direct callers:
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
```
**Symbols:**

```
ffffffff819239f0-ffffffff81923bc1: sock_set_timeout (STB_LOCAL)
ffffffff81928caa-ffffffff81928ce1: sock_set_timeout.cold (STB_LOCAL)
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
No changes between <code>4.8</code> and <code>4.10</code> ✅
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool old_timeval</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>char *optval</code> ➡️ <code>sockptr_t optval</code>
</li>
</ul>
</details>
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
