# Function: <code>prctl_set_seccomp</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long int prctl_set_seccomp(long unsigned int seccomp_mode, char *filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff8113c030)
Location: kernel/seccomp.c:845
Inline: False
Direct callers:
  - kernel/sys.c:SyS_prctl
```
**Symbols:**

```
ffffffff8113c030-ffffffff8113c063: prctl_set_seccomp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int prctl_set_seccomp(long unsigned int seccomp_mode, char *filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff81144550)
Location: kernel/seccomp.c:810
Inline: False
Direct callers:
  - kernel/sys.c:SyS_prctl
```
**Symbols:**

```
ffffffff81144550-ffffffff81144592: prctl_set_seccomp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int prctl_set_seccomp(long unsigned int seccomp_mode, char *filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff8114e3f0)
Location: kernel/seccomp.c:809
Inline: False
Direct callers:
  - kernel/sys.c:SyS_prctl
```
**Symbols:**

```
ffffffff8114e3f0-ffffffff8114e432: prctl_set_seccomp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int prctl_set_seccomp(long unsigned int seccomp_mode, char *filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff81150ac0)
Location: kernel/seccomp.c:929
Inline: False
Direct callers:
  - kernel/sys.c:SyS_prctl
```
**Symbols:**

```
ffffffff81150ac0-ffffffff81150b02: prctl_set_seccomp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int prctl_set_seccomp(long unsigned int seccomp_mode, char *filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff8115d2c0)
Location: kernel/seccomp.c:953
Inline: False
Direct callers:
  - kernel/sys.c:SyS_prctl
```
**Symbols:**

```
ffffffff8115d2c0-ffffffff8115d302: prctl_set_seccomp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long int prctl_set_seccomp(long unsigned int seccomp_mode, char *filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff8116c120)
Location: kernel/seccomp.c:959
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
```
**Symbols:**

```
ffffffff8116c120-ffffffff8116c162: prctl_set_seccomp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int prctl_set_seccomp(long unsigned int seccomp_mode, void *filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff81179b40)
Location: kernel/seccomp.c:1403
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
```
**Symbols:**

```
ffffffff81179b40-ffffffff81179b82: prctl_set_seccomp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int prctl_set_seccomp(long unsigned int seccomp_mode, void *filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff81186930)
Location: kernel/seccomp.c:1418
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
```
**Symbols:**

```
ffffffff81186930-ffffffff8118696f: prctl_set_seccomp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int prctl_set_seccomp(long unsigned int seccomp_mode, void *filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff811928b0)
Location: kernel/seccomp.c:1441
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
```
**Symbols:**

```
ffffffff811928b0-ffffffff811928ef: prctl_set_seccomp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int prctl_set_seccomp(long unsigned int seccomp_mode, void *filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff811a76f0)
Location: kernel/seccomp.c:1462
Inline: False
Direct callers:
  - kernel/sys.c:__do_sys_prctl
```
**Symbols:**

```
ffffffff811a76f0-ffffffff811a772f: prctl_set_seccomp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int prctl_set_seccomp(long unsigned int seccomp_mode, void *filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff811a4ea0)
Location: kernel/seccomp.c:1953
Inline: False
Direct callers:
  - kernel/sys.c:__do_sys_prctl
```
**Symbols:**

```
ffffffff811a4ea0-ffffffff811a4edf: prctl_set_seccomp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int prctl_set_seccomp(long unsigned int seccomp_mode, void *filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff811a5b00)
Location: kernel/seccomp.c:2001
Inline: False
Direct callers:
  - kernel/sys.c:__do_sys_prctl
```
**Symbols:**

```
ffffffff811a5b00-ffffffff811a5b3f: prctl_set_seccomp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int prctl_set_seccomp(long unsigned int seccomp_mode, void *filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff811cf280)
Location: kernel/seccomp.c:1983
Inline: False
Direct callers:
  - kernel/sys.c:__do_sys_prctl
```
**Symbols:**

```
ffffffff811cf280-ffffffff811cf2bf: prctl_set_seccomp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int prctl_set_seccomp(long unsigned int seccomp_mode, void *filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff812033f0)
Location: kernel/seccomp.c:2020
Inline: False
Direct callers:
  - kernel/sys.c:__do_sys_prctl
```
**Symbols:**

```
ffffffff812033f0-ffffffff81203450: prctl_set_seccomp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int prctl_set_seccomp(long unsigned int seccomp_mode, void *filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff8124b2d0)
Location: kernel/seccomp.c:2020
Inline: False
Direct callers:
  - kernel/sys.c:__do_sys_prctl
```
**Symbols:**

```
ffffffff8124b2d0-ffffffff8124b330: prctl_set_seccomp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int prctl_set_seccomp(long unsigned int seccomp_mode, void *filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff812625f0)
Location: kernel/seccomp.c:2020
Inline: False
Direct callers:
  - kernel/sys.c:__do_sys_prctl
```
**Symbols:**

```
ffffffff812625f0-ffffffff81262650: prctl_set_seccomp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int prctl_set_seccomp(long unsigned int seccomp_mode, void *filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff8127c830)
Location: kernel/seccomp.c:2084
Inline: False
Direct callers:
  - kernel/sys.c:__do_sys_prctl
```
**Symbols:**

```
ffffffff8127c830-ffffffff8127c890: prctl_set_seccomp (STB_GLOBAL)
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
long int prctl_set_seccomp(long unsigned int seccomp_mode, void *filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffff80001020a238)
Location: kernel/seccomp.c:1441
Inline: False
Direct callers:
  - kernel/sys.c:__arm64_sys_prctl
```
**Symbols:**

```
ffff80001020a238-ffff80001020a290: prctl_set_seccomp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int prctl_set_seccomp(long unsigned int seccomp_mode, void *filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (c04490d8)
Location: kernel/seccomp.c:1441
Inline: False
Direct callers:
  - kernel/sys.c:__se_sys_prctl
```
**Symbols:**

```
c04490d8-c0449120: prctl_set_seccomp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int prctl_set_seccomp(long unsigned int seccomp_mode, void *filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (c0000000002876c0)
Location: kernel/seccomp.c:1441
Inline: False
Direct callers:
  - kernel/sys.c:__se_sys_prctl
```
**Symbols:**

```
c0000000002876c0-c000000000287710: prctl_set_seccomp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int prctl_set_seccomp(long unsigned int seccomp_mode, void *filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffe00016c08e)
Location: kernel/seccomp.c:1441
Inline: False
Direct callers:
  - kernel/sys.c:__se_sys_prctl
```
**Symbols:**

```
ffffffe00016c08e-ffffffe00016c0d6: prctl_set_seccomp (STB_GLOBAL)
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
long int prctl_set_seccomp(long unsigned int seccomp_mode, void *filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff8118aed0)
Location: kernel/seccomp.c:1441
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
```
**Symbols:**

```
ffffffff8118aed0-ffffffff8118af0f: prctl_set_seccomp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int prctl_set_seccomp(long unsigned int seccomp_mode, void *filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff8117dff0)
Location: kernel/seccomp.c:1441
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
```
**Symbols:**

```
ffffffff8117dff0-ffffffff8117e02f: prctl_set_seccomp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int prctl_set_seccomp(long unsigned int seccomp_mode, void *filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff81188ca0)
Location: kernel/seccomp.c:1441
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
```
**Symbols:**

```
ffffffff81188ca0-ffffffff81188cdf: prctl_set_seccomp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int prctl_set_seccomp(long unsigned int seccomp_mode, void *filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff81196610)
Location: kernel/seccomp.c:1441
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
```
**Symbols:**

```
ffffffff81196610-ffffffff8119664f: prctl_set_seccomp (STB_GLOBAL)
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
<code>char *filter</code> ➡️ <code>void *filter</code>
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
