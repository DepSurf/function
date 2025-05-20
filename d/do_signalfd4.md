# Function: <code>do_signalfd4</code>

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
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int do_signalfd4(int ufd, sigset_t *mask, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/signalfd.c (ffffffff812ed2c0)
Location: fs/signalfd.c:262
Inline: True
Direct callers:
  - fs/signalfd.c:do_compat_signalfd4
  - fs/signalfd.c:__ia32_sys_signalfd
  - fs/signalfd.c:__x64_sys_signalfd
  - fs/signalfd.c:__ia32_sys_signalfd4
  - fs/signalfd.c:__x64_sys_signalfd4
```
**Symbols:**

```
ffffffff812ed2c0-ffffffff812ed435: do_signalfd4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int do_signalfd4(int ufd, sigset_t *mask, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/signalfd.c (ffffffff81301920)
Location: fs/signalfd.c:262
Inline: True
Direct callers:
  - fs/signalfd.c:do_compat_signalfd4
  - fs/signalfd.c:__ia32_sys_signalfd
  - fs/signalfd.c:__x64_sys_signalfd
  - fs/signalfd.c:__ia32_sys_signalfd4
  - fs/signalfd.c:__x64_sys_signalfd4
```
**Symbols:**

```
ffffffff81301920-ffffffff81301a95: do_signalfd4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int do_signalfd4(int ufd, sigset_t *mask, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/signalfd.c (ffffffff81322e90)
Location: fs/signalfd.c:263
Inline: True
Direct callers:
  - fs/signalfd.c:do_compat_signalfd4
  - fs/signalfd.c:__ia32_sys_signalfd
  - fs/signalfd.c:__x64_sys_signalfd
  - fs/signalfd.c:__ia32_sys_signalfd4
  - fs/signalfd.c:__x64_sys_signalfd4
```
**Symbols:**

```
ffffffff81322e90-ffffffff81323018: do_signalfd4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int do_signalfd4(int ufd, sigset_t *mask, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/signalfd.c (ffffffff81335bf0)
Location: fs/signalfd.c:263
Inline: True
Direct callers:
  - fs/signalfd.c:do_compat_signalfd4
  - fs/signalfd.c:__ia32_sys_signalfd
  - fs/signalfd.c:__x64_sys_signalfd
  - fs/signalfd.c:__ia32_sys_signalfd4
  - fs/signalfd.c:__x64_sys_signalfd4
```
**Symbols:**

```
ffffffff81335bf0-ffffffff81335d78: do_signalfd4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int do_signalfd4(int ufd, sigset_t *mask, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/signalfd.c (ffffffff8136f880)
Location: fs/signalfd.c:263
Inline: False
Direct callers:
  - fs/signalfd.c:__x32_compat_sys_signalfd
  - fs/signalfd.c:__ia32_compat_sys_signalfd
  - fs/signalfd.c:__x32_compat_sys_signalfd4
  - fs/signalfd.c:__ia32_compat_sys_signalfd4
  - fs/signalfd.c:__ia32_sys_signalfd
  - fs/signalfd.c:__x64_sys_signalfd
  - fs/signalfd.c:__ia32_sys_signalfd4
  - fs/signalfd.c:__x64_sys_signalfd4
```
**Symbols:**

```
ffffffff8136f880-ffffffff8136f9e4: do_signalfd4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int do_signalfd4(int ufd, sigset_t *mask, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/signalfd.c (ffffffff8137d5e0)
Location: fs/signalfd.c:263
Inline: False
Direct callers:
  - fs/signalfd.c:__x32_compat_sys_signalfd
  - fs/signalfd.c:__ia32_compat_sys_signalfd
  - fs/signalfd.c:__x32_compat_sys_signalfd4
  - fs/signalfd.c:__ia32_compat_sys_signalfd4
  - fs/signalfd.c:__ia32_sys_signalfd
  - fs/signalfd.c:__x64_sys_signalfd
  - fs/signalfd.c:__ia32_sys_signalfd4
  - fs/signalfd.c:__x64_sys_signalfd4
```
**Symbols:**

```
ffffffff8137d5e0-ffffffff8137d744: do_signalfd4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int do_signalfd4(int ufd, sigset_t *mask, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/signalfd.c (ffffffff81384260)
Location: fs/signalfd.c:262
Inline: False
Direct callers:
  - fs/signalfd.c:__x32_compat_sys_signalfd
  - fs/signalfd.c:__ia32_compat_sys_signalfd
  - fs/signalfd.c:__x32_compat_sys_signalfd4
  - fs/signalfd.c:__ia32_compat_sys_signalfd4
  - fs/signalfd.c:__ia32_sys_signalfd
  - fs/signalfd.c:__x64_sys_signalfd
  - fs/signalfd.c:__ia32_sys_signalfd4
  - fs/signalfd.c:__x64_sys_signalfd4
```
**Symbols:**

```
ffffffff81384260-ffffffff813843c4: do_signalfd4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int do_signalfd4(int ufd, sigset_t *mask, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/signalfd.c (ffffffff813d1500)
Location: fs/signalfd.c:252
Inline: False
Direct callers:
  - fs/signalfd.c:__x64_compat_sys_signalfd
  - fs/signalfd.c:__ia32_compat_sys_signalfd
  - fs/signalfd.c:__x64_compat_sys_signalfd4
  - fs/signalfd.c:__ia32_compat_sys_signalfd4
  - fs/signalfd.c:__ia32_sys_signalfd
  - fs/signalfd.c:__x64_sys_signalfd
  - fs/signalfd.c:__ia32_sys_signalfd4
  - fs/signalfd.c:__x64_sys_signalfd4
```
**Symbols:**

```
ffffffff813d1500-ffffffff813d1664: do_signalfd4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int do_signalfd4(int ufd, sigset_t *mask, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/signalfd.c (ffffffff8145a7a0)
Location: fs/signalfd.c:253
Inline: False
Direct callers:
  - fs/signalfd.c:__ia32_compat_sys_signalfd
  - fs/signalfd.c:__ia32_compat_sys_signalfd4
  - fs/signalfd.c:__ia32_sys_signalfd
  - fs/signalfd.c:__x64_sys_signalfd
  - fs/signalfd.c:__ia32_sys_signalfd4
  - fs/signalfd.c:__x64_sys_signalfd4
```
**Symbols:**

```
ffffffff8145a7a0-ffffffff8145a922: do_signalfd4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int do_signalfd4(int ufd, sigset_t *mask, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/signalfd.c (ffffffff814e9cf0)
Location: fs/signalfd.c:253
Inline: False
Direct callers:
  - fs/signalfd.c:__ia32_compat_sys_signalfd
  - fs/signalfd.c:__ia32_compat_sys_signalfd4
  - fs/signalfd.c:__ia32_sys_signalfd
  - fs/signalfd.c:__x64_sys_signalfd
  - fs/signalfd.c:__ia32_sys_signalfd4
  - fs/signalfd.c:__x64_sys_signalfd4
```
**Symbols:**

```
ffffffff814e9cf0-ffffffff814e9e72: do_signalfd4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int do_signalfd4(int ufd, sigset_t *mask, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/signalfd.c (ffffffff81520a90)
Location: fs/signalfd.c:253
Inline: False
Direct callers:
  - fs/signalfd.c:__ia32_compat_sys_signalfd
  - fs/signalfd.c:__ia32_compat_sys_signalfd4
  - fs/signalfd.c:__ia32_sys_signalfd
  - fs/signalfd.c:__x64_sys_signalfd
  - fs/signalfd.c:__ia32_sys_signalfd4
  - fs/signalfd.c:__x64_sys_signalfd4
```
**Symbols:**

```
ffffffff81520a90-ffffffff81520c15: do_signalfd4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int do_signalfd4(int ufd, sigset_t *mask, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/signalfd.c (ffffffff815550a0)
Location: fs/signalfd.c:253
Inline: False
Direct callers:
  - fs/signalfd.c:__ia32_compat_sys_signalfd
  - fs/signalfd.c:__ia32_compat_sys_signalfd4
  - fs/signalfd.c:__ia32_sys_signalfd
  - fs/signalfd.c:__x64_sys_signalfd
  - fs/signalfd.c:__ia32_sys_signalfd4
  - fs/signalfd.c:__x64_sys_signalfd4
```
**Symbols:**

```
ffffffff815550a0-ffffffff81555258: do_signalfd4 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int do_signalfd4(int ufd, sigset_t *mask, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/signalfd.c (ffff8000103f3588)
Location: fs/signalfd.c:263
Inline: True
Direct callers:
  - fs/signalfd.c:__arm64_compat_sys_signalfd
  - fs/signalfd.c:__arm64_compat_sys_signalfd4
  - fs/signalfd.c:__arm64_sys_signalfd
  - fs/signalfd.c:__arm64_sys_signalfd4
```
**Symbols:**

```
ffff8000103f3588-ffff8000103f3780: do_signalfd4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int do_signalfd4(int ufd, sigset_t *mask, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/signalfd.c (c05c8990)
Location: fs/signalfd.c:263
Inline: False
Direct callers:
  - fs/signalfd.c:__se_sys_signalfd
  - fs/signalfd.c:__se_sys_signalfd4
```
**Symbols:**

```
c05c8990-c05c8b30: do_signalfd4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int do_signalfd4(int ufd, sigset_t *mask, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/signalfd.c (c0000000004fb490)
Location: fs/signalfd.c:263
Inline: True
Direct callers:
  - fs/signalfd.c:__se_compat_sys_signalfd
  - fs/signalfd.c:__se_compat_sys_signalfd4
  - fs/signalfd.c:__se_sys_signalfd
  - fs/signalfd.c:__se_sys_signalfd4
```
**Symbols:**

```
c0000000004fb490-c0000000004fb734: do_signalfd4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int do_signalfd4(int ufd, sigset_t *mask, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/signalfd.c (ffffffe0002a4f72)
Location: fs/signalfd.c:263
Inline: True
Direct callers:
  - fs/signalfd.c:__se_sys_signalfd
  - fs/signalfd.c:__se_sys_signalfd4
```
**Symbols:**

```
ffffffe0002a4f72-ffffffe0002a50f8: do_signalfd4 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int do_signalfd4(int ufd, sigset_t *mask, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/signalfd.c (ffffffff8132e1d0)
Location: fs/signalfd.c:263
Inline: True
Direct callers:
  - fs/signalfd.c:do_compat_signalfd4
  - fs/signalfd.c:__ia32_sys_signalfd
  - fs/signalfd.c:__x64_sys_signalfd
  - fs/signalfd.c:__ia32_sys_signalfd4
  - fs/signalfd.c:__x64_sys_signalfd4
```
**Symbols:**

```
ffffffff8132e1d0-ffffffff8132e358: do_signalfd4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int do_signalfd4(int ufd, sigset_t *mask, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/signalfd.c (ffffffff8131ee30)
Location: fs/signalfd.c:263
Inline: True
Direct callers:
  - fs/signalfd.c:do_compat_signalfd4
  - fs/signalfd.c:__ia32_sys_signalfd
  - fs/signalfd.c:__x64_sys_signalfd
  - fs/signalfd.c:__ia32_sys_signalfd4
  - fs/signalfd.c:__x64_sys_signalfd4
```
**Symbols:**

```
ffffffff8131ee30-ffffffff8131efb2: do_signalfd4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int do_signalfd4(int ufd, sigset_t *mask, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/signalfd.c (ffffffff8132bca0)
Location: fs/signalfd.c:263
Inline: True
Direct callers:
  - fs/signalfd.c:do_compat_signalfd4
  - fs/signalfd.c:__ia32_sys_signalfd
  - fs/signalfd.c:__x64_sys_signalfd
  - fs/signalfd.c:__ia32_sys_signalfd4
  - fs/signalfd.c:__x64_sys_signalfd4
```
**Symbols:**

```
ffffffff8132bca0-ffffffff8132be28: do_signalfd4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int do_signalfd4(int ufd, sigset_t *mask, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/signalfd.c (ffffffff8133e950)
Location: fs/signalfd.c:263
Inline: True
Direct callers:
  - fs/signalfd.c:do_compat_signalfd4
  - fs/signalfd.c:__ia32_sys_signalfd
  - fs/signalfd.c:__x64_sys_signalfd
  - fs/signalfd.c:__ia32_sys_signalfd4
  - fs/signalfd.c:__x64_sys_signalfd4
```
**Symbols:**

```
ffffffff8133e950-ffffffff8133eacf: do_signalfd4 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
