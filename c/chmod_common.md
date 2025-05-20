# Function: <code>chmod_common</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int chmod_common(struct path *path, umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff81209ac0)
Location: fs/open.c:506
Inline: False
Direct callers:
  - fs/open.c:SyS_fchmod
  - fs/open.c:SyS_chmod
```
**Symbols:**

```
ffffffff81209ac0-ffffffff81209c3b: chmod_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int chmod_common(const struct path *path, umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8122f8f0)
Location: fs/open.c:506
Inline: False
Direct callers:
  - fs/open.c:SyS_chmod
  - fs/open.c:SyS_fchmod
```
**Symbols:**

```
ffffffff8122f8f0-ffffffff8122fa6d: chmod_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int chmod_common(const struct path *path, umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff81241e90)
Location: fs/open.c:523
Inline: False
Direct callers:
  - fs/open.c:SyS_chmod
  - fs/open.c:SyS_fchmod
```
**Symbols:**

```
ffffffff81241e90-ffffffff8124200d: chmod_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int chmod_common(const struct path *path, umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8124d070)
Location: fs/open.c:519
Inline: False
Direct callers:
  - fs/open.c:SyS_chmod
  - fs/open.c:SyS_fchmod
```
**Symbols:**

```
ffffffff8124d070-ffffffff8124d1e4: chmod_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int chmod_common(const struct path *path, umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8126efe0)
Location: fs/open.c:519
Inline: False
Direct callers:
  - fs/open.c:SyS_chmod
  - fs/open.c:SyS_fchmod
```
**Symbols:**

```
ffffffff8126efe0-ffffffff8126f157: chmod_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int chmod_common(const struct path *path, umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff81294ca0)
Location: fs/open.c:539
Inline: False
Direct callers:
  - fs/open.c:do_fchmodat
  - fs/open.c:ksys_fchmod
```
**Symbols:**

```
ffffffff81294ca0-ffffffff81294e17: chmod_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int chmod_common(const struct path *path, umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812a99d0)
Location: fs/open.c:528
Inline: False
Direct callers:
  - fs/open.c:do_fchmodat
  - fs/open.c:ksys_fchmod
```
**Symbols:**

```
ffffffff812a99d0-ffffffff812a9b47: chmod_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int chmod_common(const struct path *path, umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812c6170)
Location: fs/open.c:548
Inline: False
Direct callers:
  - fs/open.c:do_fchmodat
  - fs/open.c:ksys_fchmod
```
**Symbols:**

```
ffffffff812c6170-ffffffff812c62e5: chmod_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int chmod_common(const struct path *path, umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812d7b80)
Location: fs/open.c:548
Inline: False
Direct callers:
  - fs/open.c:do_fchmodat
  - fs/open.c:ksys_fchmod
```
**Symbols:**

```
ffffffff812d7b80-ffffffff812d7cf5: chmod_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int chmod_common(const struct path *path, umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8130d980)
Location: fs/open.c:577
Inline: False
Direct callers:
  - fs/open.c:do_fchmodat
  - fs/open.c:ksys_fchmod
```
**Symbols:**

```
ffffffff8130d980-ffffffff8130daf5: chmod_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int chmod_common(const struct path *path, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8131b0e0)
Location: fs/open.c:567
Inline: False
Direct callers:
  - fs/open.c:do_fchmodat
  - fs/open.c:__ia32_sys_fchmod
  - fs/open.c:__x64_sys_fchmod
  - fs/init.c:init_chmod
```
**Symbols:**

```
ffffffff8131b0e0-ffffffff8131b255: chmod_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int chmod_common(const struct path *path, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff813211f0)
Location: fs/open.c:568
Inline: False
Direct callers:
  - fs/open.c:do_fchmodat
  - fs/open.c:__ia32_sys_fchmod
  - fs/open.c:__x64_sys_fchmod
  - fs/init.c:init_chmod
```
**Symbols:**

```
ffffffff813211f0-ffffffff8132136a: chmod_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int chmod_common(const struct path *path, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8136e6d0)
Location: fs/open.c:565
Inline: False
Direct callers:
  - fs/open.c:do_fchmodat
  - fs/open.c:__ia32_sys_fchmod
  - fs/open.c:__x64_sys_fchmod
  - fs/init.c:init_chmod
```
**Symbols:**

```
ffffffff8136e6d0-ffffffff8136e84a: chmod_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int chmod_common(const struct path *path, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff813ece50)
Location: fs/open.c:589
Inline: False
Direct callers:
  - fs/open.c:do_fchmodat
  - fs/open.c:__ia32_sys_fchmod
  - fs/open.c:__x64_sys_fchmod
  - fs/init.c:init_chmod
```
**Symbols:**

```
ffffffff813ece50-ffffffff813ecfe7: chmod_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int chmod_common(const struct path *path, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff81475430)
Location: fs/open.c:589
Inline: False
Direct callers:
  - fs/open.c:do_fchmodat
  - fs/open.c:__ia32_sys_fchmod
  - fs/open.c:__x64_sys_fchmod
  - fs/init.c:init_chmod
```
**Symbols:**

```
ffffffff81475430-ffffffff814755ce: chmod_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int chmod_common(const struct path *path, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff814a9dc0)
Location: fs/open.c:626
Inline: False
Direct callers:
  - fs/open.c:do_fchmodat
  - fs/open.c:__ia32_sys_fchmod
  - fs/open.c:__x64_sys_fchmod
  - fs/init.c:init_chmod
```
**Symbols:**

```
ffffffff814a9dc0-ffffffff814a9f57: chmod_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int chmod_common(const struct path *path, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff814daf00)
Location: fs/open.c:631
Inline: False
Direct callers:
  - fs/open.c:__ia32_sys_chmod
  - fs/open.c:__x64_sys_chmod
  - fs/open.c:__ia32_sys_fchmodat
  - fs/open.c:__x64_sys_fchmodat
  - fs/open.c:__ia32_sys_fchmod
  - fs/open.c:__x64_sys_fchmod
  - fs/init.c:init_chmod
```
**Symbols:**

```
ffffffff814daf00-ffffffff814db097: chmod_common (STB_GLOBAL)
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
int chmod_common(const struct path *path, umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffff80001037cf78)
Location: fs/open.c:548
Inline: False
Direct callers:
  - fs/open.c:do_fchmodat
  - fs/open.c:ksys_fchmod
```
**Symbols:**

```
ffff80001037cf78-ffff80001037d0c8: chmod_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int chmod_common(const struct path *path, umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (c0567e24)
Location: fs/open.c:548
Inline: False
Direct callers:
  - fs/open.c:do_fchmodat
  - fs/open.c:ksys_fchmod
```
**Symbols:**

```
c0567e24-c0567f7c: chmod_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int chmod_common(const struct path *path, umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (c000000000472470)
Location: fs/open.c:548
Inline: False
Direct callers:
  - fs/open.c:do_fchmodat
  - fs/open.c:ksys_fchmod
```
**Symbols:**

```
c000000000472470-c00000000047264c: chmod_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int chmod_common(const struct path *path, umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffe0002534be)
Location: fs/open.c:548
Inline: False
Direct callers:
  - fs/open.c:do_fchmodat
  - fs/open.c:ksys_fchmod
```
**Symbols:**

```
ffffffe0002534be-ffffffe0002535d8: chmod_common (STB_LOCAL)
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
int chmod_common(const struct path *path, umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812d0160)
Location: fs/open.c:548
Inline: False
Direct callers:
  - fs/open.c:do_fchmodat
  - fs/open.c:ksys_fchmod
```
**Symbols:**

```
ffffffff812d0160-ffffffff812d02d5: chmod_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int chmod_common(const struct path *path, umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812c0de0)
Location: fs/open.c:548
Inline: False
Direct callers:
  - fs/open.c:do_fchmodat
  - fs/open.c:ksys_fchmod
```
**Symbols:**

```
ffffffff812c0de0-ffffffff812c0f55: chmod_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int chmod_common(const struct path *path, umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812cdf70)
Location: fs/open.c:548
Inline: False
Direct callers:
  - fs/open.c:do_fchmodat
  - fs/open.c:ksys_fchmod
```
**Symbols:**

```
ffffffff812cdf70-ffffffff812ce0e5: chmod_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int chmod_common(const struct path *path, umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812ded80)
Location: fs/open.c:548
Inline: False
Direct callers:
  - fs/open.c:do_fchmodat
  - fs/open.c:ksys_fchmod
```
**Symbols:**

```
ffffffff812ded80-ffffffff812deef5: chmod_common (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct path *path</code> ➡️ <code>const struct path *path</code>
</li>
</ul>
</details>
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
