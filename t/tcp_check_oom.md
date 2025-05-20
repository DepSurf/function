# Function: <code>tcp_check_oom</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool tcp_check_oom(struct sock *sk, int shift);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff8176a160)
Location: net/ipv4/tcp.c:2004
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
```
**Symbols:**

```
ffffffff8176a160-ffffffff8176a2ab: tcp_check_oom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool tcp_check_oom(struct sock *sk, int shift);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff817d6c00)
Location: net/ipv4/tcp.c:2013
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
```
**Symbols:**

```
ffffffff817d6c00-ffffffff817d6d19: tcp_check_oom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool tcp_check_oom(struct sock *sk, int shift);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81806c20)
Location: net/ipv4/tcp.c:2051
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
```
**Symbols:**

```
ffffffff81806c20-ffffffff81806d39: tcp_check_oom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool tcp_check_oom(struct sock *sk, int shift);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81827230)
Location: net/ipv4/tcp.c:2095
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_close
```
**Symbols:**

```
ffffffff81827230-ffffffff8182734c: tcp_check_oom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool tcp_check_oom(struct sock *sk, int shift);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff818a6030)
Location: net/ipv4/tcp.c:2135
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_close
```
**Symbols:**

```
ffffffff818a6030-ffffffff818a614c: tcp_check_oom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
bool tcp_check_oom(struct sock *sk, int shift);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp.c (0)
Location: net/ipv4/tcp.c:2304
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
```
**Symbols:**

```
ffffffff818fc157-ffffffff818fc199: tcp_check_oom.cold.55 (STB_LOCAL)
ffffffff818fb0d0-ffffffff818fb1be: tcp_check_oom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
bool tcp_check_oom(struct sock *sk, int shift);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp.c (0)
Location: net/ipv4/tcp.c:2311
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
```
**Symbols:**

```
ffffffff8192a197-ffffffff8192a1d4: tcp_check_oom.cold.60 (STB_LOCAL)
ffffffff81929000-ffffffff81929106: tcp_check_oom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
bool tcp_check_oom(struct sock *sk, int shift);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp.c (0)
Location: net/ipv4/tcp.c:2322
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
```
**Symbols:**

```
ffffffff8198d3c2-ffffffff8198d400: tcp_check_oom.cold (STB_LOCAL)
ffffffff8198bf10-ffffffff8198c016: tcp_check_oom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
bool tcp_check_oom(struct sock *sk, int shift);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp.c (0)
Location: net/ipv4/tcp.c:2321
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
```
**Symbols:**

```
ffffffff819c3d42-ffffffff819c3d80: tcp_check_oom.cold (STB_LOCAL)
ffffffff819c2860-ffffffff819c2966: tcp_check_oom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
bool tcp_check_oom(struct sock *sk, int shift);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp.c (0)
Location: net/ipv4/tcp.c:2393
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp_timer.c:tcp_out_of_resources
```
**Symbols:**

```
ffffffff81aaf512-ffffffff81aaf54a: tcp_check_oom.cold (STB_LOCAL)
ffffffff81aade10-ffffffff81aadef3: tcp_check_oom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
bool tcp_check_oom(struct sock *sk, int shift);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp.c (0)
Location: net/ipv4/tcp.c:2641
Inline: False
Direct callers:
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp_timer.c:tcp_out_of_resources
```
**Symbols:**

```
ffffffff81c325e7-ffffffff81c3261f: tcp_check_oom.cold (STB_LOCAL)
ffffffff81ab80a0-ffffffff81ab8183: tcp_check_oom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
bool tcp_check_oom(struct sock *sk, int shift);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp.c (0)
Location: net/ipv4/tcp.c:2695
Inline: False
Direct callers:
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp_timer.c:tcp_out_of_resources
```
**Symbols:**

```
ffffffff81c248d4-ffffffff81c2490c: tcp_check_oom.cold (STB_LOCAL)
ffffffff81aa33e0-ffffffff81aa34be: tcp_check_oom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool tcp_check_oom(struct sock *sk, int shift);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp.c (0)
Location: net/ipv4/tcp.c:2720
Inline: False
Direct callers:
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp_timer.c:tcp_out_of_resources
```
**Symbols:**

```
ffffffff81d3a5c5-ffffffff81d3a622: tcp_check_oom.cold (STB_LOCAL)
ffffffff81b5f5b0-ffffffff81b5f65e: tcp_check_oom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool tcp_check_oom(struct sock *sk, int shift);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp.c (0)
Location: net/ipv4/tcp.c:2748
Inline: False
Direct callers:
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp_timer.c:tcp_out_of_resources
```
**Symbols:**

```
ffffffff81f06df6-ffffffff81f06e49: tcp_check_oom.cold (STB_LOCAL)
ffffffff81cee020-ffffffff81cee0cb: tcp_check_oom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool tcp_check_oom(struct sock *sk, int shift);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp.c (0)
Location: net/ipv4/tcp.c:2848
Inline: False
Direct callers:
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp_timer.c:tcp_out_of_resources
```
**Symbols:**

```
ffffffff820ae942-ffffffff820ae962: tcp_check_oom.cold (STB_LOCAL)
ffffffff81eb12c0-ffffffff81eb138e: tcp_check_oom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool tcp_check_oom(struct sock *sk, int shift);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp.c (0)
Location: net/ipv4/tcp.c:2734
Inline: False
Direct callers:
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp_timer.c:tcp_out_of_resources
```
**Symbols:**

```
ffffffff8212fded-ffffffff8212fe0d: tcp_check_oom.cold (STB_LOCAL)
ffffffff81f0f950-ffffffff81f0fa1e: tcp_check_oom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool tcp_check_oom(struct sock *sk, int shift);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp.c (0)
Location: net/ipv4/tcp.c:2746
Inline: False
Direct callers:
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp_timer.c:tcp_out_of_resources
```
**Symbols:**

```
ffffffff82211ad9-ffffffff82211af9: tcp_check_oom.cold (STB_LOCAL)
ffffffff81fd3b40-ffffffff81fd3c0e: tcp_check_oom (STB_GLOBAL)
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
bool tcp_check_oom(struct sock *sk, int shift);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffff800010c75560)
Location: net/ipv4/tcp.c:2321
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_close
```
**Symbols:**

```
ffff800010c75560-ffff800010c756b4: tcp_check_oom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool tcp_check_oom(struct sock *sk, int shift);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (c0d83c9c)
Location: net/ipv4/tcp.c:2321
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_close
```
**Symbols:**

```
c0d83c9c-c0d83df8: tcp_check_oom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool tcp_check_oom(struct sock *sk, int shift);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (c000000000d7cc10)
Location: net/ipv4/tcp.c:2321
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_close
```
**Symbols:**

```
c000000000d7cc10-c000000000d7ce48: tcp_check_oom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool tcp_check_oom(struct sock *sk, int shift);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffe0007d8824)
Location: net/ipv4/tcp.c:2321
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
```
**Symbols:**

```
ffffffe0007d8824-ffffffe0007d8940: tcp_check_oom (STB_GLOBAL)
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
bool tcp_check_oom(struct sock *sk, int shift);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp.c (0)
Location: net/ipv4/tcp.c:2321
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
```
**Symbols:**

```
ffffffff81963bb2-ffffffff81963bf0: tcp_check_oom.cold (STB_LOCAL)
ffffffff819626d0-ffffffff819627d6: tcp_check_oom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
bool tcp_check_oom(struct sock *sk, int shift);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp.c (0)
Location: net/ipv4/tcp.c:2321
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
```
**Symbols:**

```
ffffffff8191d6a2-ffffffff8191d6e0: tcp_check_oom.cold (STB_LOCAL)
ffffffff8191c1c0-ffffffff8191c2c6: tcp_check_oom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
bool tcp_check_oom(struct sock *sk, int shift);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp.c (0)
Location: net/ipv4/tcp.c:2321
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
```
**Symbols:**

```
ffffffff819ce382-ffffffff819ce3c0: tcp_check_oom.cold (STB_LOCAL)
ffffffff819ccea0-ffffffff819ccfa6: tcp_check_oom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
bool tcp_check_oom(struct sock *sk, int shift);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp.c (0)
Location: net/ipv4/tcp.c:2321
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
```
**Symbols:**

```
ffffffff819d7f12-ffffffff819d7f50: tcp_check_oom.cold (STB_LOCAL)
ffffffff819d6a30-ffffffff819d6b36: tcp_check_oom (STB_GLOBAL)
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
