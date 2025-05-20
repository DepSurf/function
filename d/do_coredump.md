# Function: <code>do_coredump</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void do_coredump(const siginfo_t *siginfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/coredump.c (ffffffff8126f010)
Location: fs/coredump.c:506
Inline: False
Direct callers:
  - kernel/signal.c:get_signal
```
**Symbols:**

```
ffffffff8126f010-ffffffff8126fe9a: do_coredump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void do_coredump(const siginfo_t *siginfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/coredump.c (ffffffff8129a7f0)
Location: fs/coredump.c:533
Inline: False
Direct callers:
  - kernel/signal.c:get_signal
```
**Symbols:**

```
ffffffff8129a7f0-ffffffff8129b6aa: do_coredump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void do_coredump(const siginfo_t *siginfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/coredump.c (ffffffff812af380)
Location: fs/coredump.c:536
Inline: False
Direct callers:
  - kernel/signal.c:get_signal
```
**Symbols:**

```
ffffffff812af380-ffffffff812b0263: do_coredump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void do_coredump(const siginfo_t *siginfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/coredump.c (ffffffff812bc7c0)
Location: fs/coredump.c:538
Inline: False
Direct callers:
  - kernel/signal.c:get_signal
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff812bc7c0-ffffffff812bd6e5: do_coredump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void do_coredump(const siginfo_t *siginfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/coredump.c (ffffffff812e00b0)
Location: fs/coredump.c:539
Inline: False
Direct callers:
  - kernel/signal.c:get_signal
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff812e00b0-ffffffff812e0fb4: do_coredump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void do_coredump(const siginfo_t *siginfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/coredump.c (0)
Location: fs/coredump.c:539
Inline: False
Direct callers:
  - kernel/signal.c:get_signal
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff8130d1c5-ffffffff8130d1e0: do_coredump.cold.15 (STB_LOCAL)
ffffffff8130c2e0-ffffffff8130d1c5: do_coredump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void do_coredump(const kernel_siginfo_t *siginfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/coredump.c (0)
Location: fs/coredump.c:539
Inline: False
Direct callers:
  - kernel/signal.c:get_signal
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff81322a91-ffffffff81322aac: do_coredump.cold.15 (STB_LOCAL)
ffffffff81321b40-ffffffff81322a91: do_coredump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void do_coredump(const kernel_siginfo_t *siginfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/coredump.c (0)
Location: fs/coredump.c:565
Inline: False
Direct callers:
  - kernel/signal.c:get_signal
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff8134a490-ffffffff8134a4c8: do_coredump.cold (STB_LOCAL)
ffffffff81349960-ffffffff8134a490: do_coredump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void do_coredump(const kernel_siginfo_t *siginfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/coredump.c (0)
Location: fs/coredump.c:565
Inline: False
Direct callers:
  - kernel/signal.c:get_signal
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff81362730-ffffffff81362768: do_coredump.cold (STB_LOCAL)
ffffffff81361c00-ffffffff81362730: do_coredump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void do_coredump(const kernel_siginfo_t *siginfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/coredump.c (0)
Location: fs/coredump.c:567
Inline: False
Direct callers:
  - kernel/signal.c:get_signal
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff813a84e4-ffffffff813a8537: do_coredump.cold (STB_LOCAL)
ffffffff813a7e90-ffffffff813a84e4: do_coredump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void do_coredump(const kernel_siginfo_t *siginfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/coredump.c (0)
Location: fs/coredump.c:577
Inline: False
Direct callers:
  - kernel/signal.c:get_signal
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff81bebaa1-ffffffff81bebaf4: do_coredump.cold (STB_LOCAL)
ffffffff813b8f10-ffffffff813b959b: do_coredump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void do_coredump(const kernel_siginfo_t *siginfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/coredump.c (0)
Location: fs/coredump.c:577
Inline: False
Direct callers:
  - kernel/signal.c:get_signal
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff81bddb03-ffffffff81bddb53: do_coredump.cold (STB_LOCAL)
ffffffff813bfe70-ffffffff813c0709: do_coredump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void do_coredump(const kernel_siginfo_t *siginfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/coredump.c (0)
Location: fs/coredump.c:577
Inline: False
Direct callers:
  - kernel/signal.c:get_signal
```
**Symbols:**

```
ffffffff81cc75c1-ffffffff81cc7649: do_coredump.cold (STB_LOCAL)
ffffffff8140fca0-ffffffff81410571: do_coredump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void do_coredump(const kernel_siginfo_t *siginfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/coredump.c (0)
Location: fs/coredump.c:511
Inline: False
Direct callers:
  - kernel/signal.c:get_signal
```
**Symbols:**

```
ffffffff81e79be7-ffffffff81e79c7e: do_coredump.cold (STB_LOCAL)
ffffffff81485630-ffffffff8148606e: do_coredump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void do_coredump(const kernel_siginfo_t *siginfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/coredump.c (ffffffff81518ca0)
Location: fs/coredump.c:517
Inline: False
Direct callers:
  - kernel/signal.c:get_signal
```
**Symbols:**

```
ffffffff81518ca0-ffffffff815197e9: do_coredump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void do_coredump(const kernel_siginfo_t *siginfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/coredump.c (ffffffff815505a0)
Location: fs/coredump.c:519
Inline: False
Direct callers:
  - kernel/signal.c:get_signal
```
**Symbols:**

```
ffffffff815505a0-ffffffff815510c2: do_coredump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void do_coredump(const kernel_siginfo_t *siginfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/coredump.c (ffffffff81586430)
Location: fs/coredump.c:519
Inline: False
Direct callers:
  - kernel/signal.c:get_signal
```
**Symbols:**

```
ffffffff81586430-ffffffff81586f53: do_coredump (STB_GLOBAL)
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
void do_coredump(const kernel_siginfo_t *siginfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/coredump.c (ffff800010428308)
Location: fs/coredump.c:565
Inline: False
Direct callers:
  - kernel/signal.c:get_signal
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffff800010428308-ffff800010428e14: do_coredump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void do_coredump(const kernel_siginfo_t *siginfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/coredump.c (c05f0f70)
Location: fs/coredump.c:565
Inline: False
Direct callers:
  - kernel/signal.c:get_signal
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
c05f0f70-c05f1b64: do_coredump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void do_coredump(const kernel_siginfo_t *siginfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/coredump.c (c000000000538480)
Location: fs/coredump.c:565
Inline: False
Direct callers:
  - kernel/signal.c:get_signal
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
c000000000538480-c0000000005391a8: do_coredump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void do_coredump(const kernel_siginfo_t *siginfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/coredump.c (ffffffe0002c658c)
Location: fs/coredump.c:565
Inline: False
Direct callers:
  - kernel/signal.c:get_signal
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffe0002c658c-ffffffe0002c6f2e: do_coredump (STB_GLOBAL)
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
void do_coredump(const kernel_siginfo_t *siginfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/coredump.c (0)
Location: fs/coredump.c:565
Inline: False
Direct callers:
  - kernel/signal.c:get_signal
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff8135ad10-ffffffff8135ad48: do_coredump.cold (STB_LOCAL)
ffffffff8135a1e0-ffffffff8135ad10: do_coredump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void do_coredump(const kernel_siginfo_t *siginfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/coredump.c (0)
Location: fs/coredump.c:565
Inline: False
Direct callers:
  - kernel/signal.c:get_signal
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff8134b9b4-ffffffff8134b9ec: do_coredump.cold (STB_LOCAL)
ffffffff8134ae90-ffffffff8134b9b4: do_coredump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void do_coredump(const kernel_siginfo_t *siginfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/coredump.c (0)
Location: fs/coredump.c:565
Inline: False
Direct callers:
  - kernel/signal.c:get_signal
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff813587e0-ffffffff81358818: do_coredump.cold (STB_LOCAL)
ffffffff81357cb0-ffffffff813587e0: do_coredump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void do_coredump(const kernel_siginfo_t *siginfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/coredump.c (0)
Location: fs/coredump.c:565
Inline: False
Direct callers:
  - kernel/signal.c:get_signal
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff8136beee-ffffffff8136bf26: do_coredump.cold (STB_LOCAL)
ffffffff8136b390-ffffffff8136beee: do_coredump (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const siginfo_t *siginfo</code> ➡️ <code>const kernel_siginfo_t *siginfo</code>
</li>
</ul>
</details>
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
