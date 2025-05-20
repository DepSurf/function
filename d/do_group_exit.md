# Function: <code>do_group_exit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void do_group_exit(int exit_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810843e0)
Location: kernel/exit.c:855
Inline: False
Direct callers:
  - kernel/exit.c:SyS_exit_group
  - kernel/signal.c:get_signal
```
**Symbols:**

```
ffffffff810843e0-ffffffff81084484: do_group_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void do_group_exit(int exit_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff81087540)
Location: kernel/exit.c:930
Inline: False
Direct callers:
  - kernel/exit.c:SyS_exit_group
  - kernel/signal.c:get_signal
```
**Symbols:**

```
ffffffff81087540-ffffffff810875e7: do_group_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void do_group_exit(int exit_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff8108c4a0)
Location: kernel/exit.c:920
Inline: False
Direct callers:
  - kernel/exit.c:SyS_exit_group
  - kernel/signal.c:get_signal
```
**Symbols:**

```
ffffffff8108c4a0-ffffffff8108c547: do_group_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void do_group_exit(int exit_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff81089610)
Location: kernel/exit.c:946
Inline: False
Direct callers:
  - kernel/exit.c:SyS_exit_group
  - kernel/signal.c:get_signal
```
**Symbols:**

```
ffffffff81089610-ffffffff810896b7: do_group_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void do_group_exit(int exit_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff81090390)
Location: kernel/exit.c:945
Inline: False
Direct callers:
  - kernel/exit.c:SyS_exit_group
  - kernel/signal.c:get_signal
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff81090390-ffffffff81090437: do_group_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void do_group_exit(int exit_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff81093e50)
Location: kernel/exit.c:945
Inline: False
Direct callers:
  - kernel/exit.c:__ia32_sys_exit_group
  - kernel/exit.c:__x64_sys_exit_group
  - kernel/signal.c:get_signal
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff81093e50-ffffffff81093ef7: do_group_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void do_group_exit(int exit_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff8109c1d0)
Location: kernel/exit.c:956
Inline: False
Direct callers:
  - kernel/exit.c:__ia32_sys_exit_group
  - kernel/exit.c:__x64_sys_exit_group
  - kernel/signal.c:get_signal
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff8109c1d0-ffffffff8109c277: do_group_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void do_group_exit(int exit_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810a07f0)
Location: kernel/exit.c:960
Inline: False
Direct callers:
  - kernel/exit.c:__ia32_sys_exit_group
  - kernel/exit.c:__x64_sys_exit_group
  - kernel/signal.c:get_signal
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff810a07f0-ffffffff810a089d: do_group_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void do_group_exit(int exit_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810a6dd0)
Location: kernel/exit.c:876
Inline: False
Direct callers:
  - kernel/exit.c:__ia32_sys_exit_group
  - kernel/exit.c:__x64_sys_exit_group
  - kernel/signal.c:get_signal
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff810a6dd0-ffffffff810a6e7d: do_group_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void do_group_exit(int exit_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810ae520)
Location: kernel/exit.c:880
Inline: False
Direct callers:
  - kernel/exit.c:__ia32_sys_exit_group
  - kernel/exit.c:__x64_sys_exit_group
  - kernel/signal.c:get_signal
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff810ae520-ffffffff810ae5c5: do_group_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void do_group_exit(int exit_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810a9b70)
Location: kernel/exit.c:899
Inline: False
Direct callers:
  - kernel/exit.c:__ia32_sys_exit_group
  - kernel/exit.c:__x64_sys_exit_group
  - kernel/signal.c:get_signal
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff810a9b70-ffffffff810a9c15: do_group_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void do_group_exit(int exit_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810aaba0)
Location: kernel/exit.c:899
Inline: False
Direct callers:
  - kernel/exit.c:__ia32_sys_exit_group
  - kernel/exit.c:__x64_sys_exit_group
  - kernel/signal.c:get_signal
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff810aaba0-ffffffff810aac45: do_group_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void do_group_exit(int exit_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810bc6c0)
Location: kernel/exit.c:899
Inline: False
Direct callers:
  - kernel/exit.c:__ia32_sys_exit_group
  - kernel/exit.c:__x64_sys_exit_group
  - kernel/signal.c:get_signal
```
**Symbols:**

```
ffffffff810bc6c0-ffffffff810bc765: do_group_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void do_group_exit(int exit_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810d3460)
Location: kernel/exit.c:900
Inline: False
Direct callers:
  - kernel/exit.c:__ia32_sys_exit_group
  - kernel/exit.c:__x64_sys_exit_group
  - kernel/signal.c:get_signal
```
**Symbols:**

```
ffffffff810d3460-ffffffff810d34fe: do_group_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void do_group_exit(int exit_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810f20d0)
Location: kernel/exit.c:994
Inline: False
Direct callers:
  - kernel/exit.c:__ia32_sys_exit_group
  - kernel/exit.c:__x64_sys_exit_group
  - kernel/signal.c:get_signal
```
**Symbols:**

```
ffffffff810f20d0-ffffffff810f215b: do_group_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void do_group_exit(int exit_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810fe050)
Location: kernel/exit.c:999
Inline: False
Direct callers:
  - kernel/exit.c:__ia32_sys_exit_group
  - kernel/exit.c:__x64_sys_exit_group
  - kernel/signal.c:get_signal
```
**Symbols:**

```
ffffffff810fe050-ffffffff810fe0db: do_group_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void do_group_exit(int exit_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff81106cf0)
Location: kernel/exit.c:995
Inline: False
Direct callers:
  - kernel/exit.c:__ia32_sys_exit_group
  - kernel/exit.c:__x64_sys_exit_group
  - kernel/signal.c:get_signal
```
**Symbols:**

```
ffffffff81106cf0-ffffffff81106d7b: do_group_exit (STB_GLOBAL)
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
void do_group_exit(int exit_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffff8000100fdcc0)
Location: kernel/exit.c:876
Inline: False
Direct callers:
  - kernel/exit.c:__arm64_sys_exit_group
  - kernel/signal.c:get_signal
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffff8000100fdcc0-ffff8000100fdd6c: do_group_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void do_group_exit(int exit_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (c035af0c)
Location: kernel/exit.c:876
Inline: False
Direct callers:
  - kernel/exit.c:__se_sys_exit_group
  - kernel/signal.c:get_signal
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
c035af0c-c035afe8: do_group_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void do_group_exit(int exit_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (c000000000144da0)
Location: kernel/exit.c:876
Inline: False
Direct callers:
  - kernel/exit.c:__se_sys_exit_group
  - kernel/signal.c:get_signal
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
c000000000144da0-c000000000144eb8: do_group_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void do_group_exit(int exit_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffe0000c6444)
Location: kernel/exit.c:876
Inline: False
Direct callers:
  - kernel/exit.c:__se_sys_exit_group
  - kernel/signal.c:get_signal
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffe0000c6444-ffffffe0000c64d8: do_group_exit (STB_GLOBAL)
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
void do_group_exit(int exit_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810a06f0)
Location: kernel/exit.c:876
Inline: False
Direct callers:
  - kernel/exit.c:__ia32_sys_exit_group
  - kernel/exit.c:__x64_sys_exit_group
  - kernel/signal.c:get_signal
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff810a06f0-ffffffff810a079d: do_group_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void do_group_exit(int exit_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff8108f110)
Location: kernel/exit.c:876
Inline: False
Direct callers:
  - kernel/exit.c:__ia32_sys_exit_group
  - kernel/exit.c:__x64_sys_exit_group
  - kernel/signal.c:get_signal
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff8108f110-ffffffff8108f1b3: do_group_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void do_group_exit(int exit_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810a06a0)
Location: kernel/exit.c:876
Inline: False
Direct callers:
  - kernel/exit.c:__ia32_sys_exit_group
  - kernel/exit.c:__x64_sys_exit_group
  - kernel/signal.c:get_signal
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff810a06a0-ffffffff810a074d: do_group_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void do_group_exit(int exit_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810a8630)
Location: kernel/exit.c:876
Inline: False
Direct callers:
  - kernel/exit.c:__ia32_sys_exit_group
  - kernel/exit.c:__x64_sys_exit_group
  - kernel/signal.c:get_signal
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff810a8630-ffffffff810a86d0: do_group_exit (STB_GLOBAL)
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
