# Function: <code>do_compat_signalfd4</code>

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
<summary>In <code>4.18</code>: ✅</summary>

```c
long int do_compat_signalfd4(int ufd, const compat_sigset_t *user_mask, compat_size_t sigsetsize, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/signalfd.c (ffffffff812ed530)
Location: fs/signalfd.c:334
Inline: False
Direct callers:
  - fs/signalfd.c:__x32_compat_sys_signalfd
  - fs/signalfd.c:__ia32_compat_sys_signalfd
  - fs/signalfd.c:__x32_compat_sys_signalfd4
  - fs/signalfd.c:__ia32_compat_sys_signalfd4
```
**Symbols:**

```
ffffffff812ed530-ffffffff812ed5a5: do_compat_signalfd4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int do_compat_signalfd4(int ufd, const compat_sigset_t *user_mask, compat_size_t sigsetsize, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/signalfd.c (ffffffff81301b90)
Location: fs/signalfd.c:334
Inline: False
Direct callers:
  - fs/signalfd.c:__x32_compat_sys_signalfd
  - fs/signalfd.c:__ia32_compat_sys_signalfd
  - fs/signalfd.c:__x32_compat_sys_signalfd4
  - fs/signalfd.c:__ia32_compat_sys_signalfd4
```
**Symbols:**

```
ffffffff81301b90-ffffffff81301c05: do_compat_signalfd4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int do_compat_signalfd4(int ufd, const compat_sigset_t *user_mask, compat_size_t sigsetsize, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/signalfd.c (ffffffff81323110)
Location: fs/signalfd.c:335
Inline: False
Direct callers:
  - fs/signalfd.c:__x32_compat_sys_signalfd
  - fs/signalfd.c:__ia32_compat_sys_signalfd
  - fs/signalfd.c:__x32_compat_sys_signalfd4
  - fs/signalfd.c:__ia32_compat_sys_signalfd4
```
**Symbols:**

```
ffffffff81323110-ffffffff81323189: do_compat_signalfd4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int do_compat_signalfd4(int ufd, const compat_sigset_t *user_mask, compat_size_t sigsetsize, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/signalfd.c (ffffffff81335e70)
Location: fs/signalfd.c:335
Inline: False
Direct callers:
  - fs/signalfd.c:__x32_compat_sys_signalfd
  - fs/signalfd.c:__ia32_compat_sys_signalfd
  - fs/signalfd.c:__x32_compat_sys_signalfd4
  - fs/signalfd.c:__ia32_compat_sys_signalfd4
```
**Symbols:**

```
ffffffff81335e70-ffffffff81335ee9: do_compat_signalfd4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/signalfd.c (ffffffff8136fcb5)
Location: fs/signalfd.c:337
Inline: True
Inline callers:
  - fs/signalfd.c:__x32_compat_sys_signalfd
  - fs/signalfd.c:__ia32_compat_sys_signalfd
  - fs/signalfd.c:__x32_compat_sys_signalfd4
  - fs/signalfd.c:__ia32_compat_sys_signalfd4
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/signalfd.c (ffffffff8137da15)
Location: fs/signalfd.c:337
Inline: True
Inline callers:
  - fs/signalfd.c:__x32_compat_sys_signalfd
  - fs/signalfd.c:__ia32_compat_sys_signalfd
  - fs/signalfd.c:__x32_compat_sys_signalfd4
  - fs/signalfd.c:__ia32_compat_sys_signalfd4
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
In fs/signalfd.c (ffffffff81384696)
Location: fs/signalfd.c:336
Inline: True
Inline callers:
  - fs/signalfd.c:__x32_compat_sys_signalfd
  - fs/signalfd.c:__ia32_compat_sys_signalfd
  - fs/signalfd.c:__x32_compat_sys_signalfd4
  - fs/signalfd.c:__ia32_compat_sys_signalfd4
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
In fs/signalfd.c (ffffffff813d1936)
Location: fs/signalfd.c:326
Inline: True
Inline callers:
  - fs/signalfd.c:__x64_compat_sys_signalfd
  - fs/signalfd.c:__ia32_compat_sys_signalfd
  - fs/signalfd.c:__x64_compat_sys_signalfd4
  - fs/signalfd.c:__ia32_compat_sys_signalfd4
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
In fs/signalfd.c (ffffffff8145aeb3)
Location: fs/signalfd.c:327
Inline: True
Inline callers:
  - fs/signalfd.c:__ia32_compat_sys_signalfd
  - fs/signalfd.c:__ia32_compat_sys_signalfd4
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
In fs/signalfd.c (ffffffff814ea483)
Location: fs/signalfd.c:327
Inline: True
Inline callers:
  - fs/signalfd.c:__ia32_compat_sys_signalfd
  - fs/signalfd.c:__ia32_compat_sys_signalfd4
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
In fs/signalfd.c (ffffffff81521223)
Location: fs/signalfd.c:327
Inline: True
Inline callers:
  - fs/signalfd.c:__ia32_compat_sys_signalfd
  - fs/signalfd.c:__ia32_compat_sys_signalfd4
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
In fs/signalfd.c (ffffffff81555863)
Location: fs/signalfd.c:327
Inline: True
Inline callers:
  - fs/signalfd.c:__ia32_compat_sys_signalfd
  - fs/signalfd.c:__ia32_compat_sys_signalfd4
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
In fs/signalfd.c (ffff8000103f384c)
Location: fs/signalfd.c:335
Inline: True
Inline callers:
  - fs/signalfd.c:__arm64_compat_sys_signalfd
  - fs/signalfd.c:__arm64_compat_sys_signalfd4
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/signalfd.c (c0000000004fb8e4)
Location: fs/signalfd.c:335
Inline: True
Inline callers:
  - fs/signalfd.c:__se_compat_sys_signalfd
  - fs/signalfd.c:__se_compat_sys_signalfd4
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
long int do_compat_signalfd4(int ufd, const compat_sigset_t *user_mask, compat_size_t sigsetsize, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/signalfd.c (ffffffff8132e450)
Location: fs/signalfd.c:335
Inline: False
Direct callers:
  - fs/signalfd.c:__x32_compat_sys_signalfd
  - fs/signalfd.c:__ia32_compat_sys_signalfd
  - fs/signalfd.c:__x32_compat_sys_signalfd4
  - fs/signalfd.c:__ia32_compat_sys_signalfd4
```
**Symbols:**

```
ffffffff8132e450-ffffffff8132e4c9: do_compat_signalfd4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int do_compat_signalfd4(int ufd, const compat_sigset_t *user_mask, compat_size_t sigsetsize, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/signalfd.c (ffffffff8131f0b0)
Location: fs/signalfd.c:335
Inline: False
Direct callers:
  - fs/signalfd.c:__x32_compat_sys_signalfd
  - fs/signalfd.c:__ia32_compat_sys_signalfd
  - fs/signalfd.c:__x32_compat_sys_signalfd4
  - fs/signalfd.c:__ia32_compat_sys_signalfd4
```
**Symbols:**

```
ffffffff8131f0b0-ffffffff8131f129: do_compat_signalfd4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int do_compat_signalfd4(int ufd, const compat_sigset_t *user_mask, compat_size_t sigsetsize, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/signalfd.c (ffffffff8132bf20)
Location: fs/signalfd.c:335
Inline: False
Direct callers:
  - fs/signalfd.c:__x32_compat_sys_signalfd
  - fs/signalfd.c:__ia32_compat_sys_signalfd
  - fs/signalfd.c:__x32_compat_sys_signalfd4
  - fs/signalfd.c:__ia32_compat_sys_signalfd4
```
**Symbols:**

```
ffffffff8132bf20-ffffffff8132bf99: do_compat_signalfd4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int do_compat_signalfd4(int ufd, const compat_sigset_t *user_mask, compat_size_t sigsetsize, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/signalfd.c (ffffffff8133ebc0)
Location: fs/signalfd.c:335
Inline: False
Direct callers:
  - fs/signalfd.c:__x32_compat_sys_signalfd
  - fs/signalfd.c:__ia32_compat_sys_signalfd
  - fs/signalfd.c:__x32_compat_sys_signalfd4
  - fs/signalfd.c:__ia32_compat_sys_signalfd4
```
**Symbols:**

```
ffffffff8133ebc0-ffffffff8133ec39: do_compat_signalfd4 (STB_LOCAL)
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
