# Function: <code>do_compat_futimesat</code>

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
long int do_compat_futimesat(unsigned int dfd, const char *filename, struct compat_timeval *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/utimes.c (ffffffff812d31a0)
Location: fs/utimes.c:263
Inline: False
Direct callers:
  - fs/utimes.c:__x32_compat_sys_utimes
  - fs/utimes.c:__ia32_compat_sys_utimes
  - fs/utimes.c:__x32_compat_sys_futimesat
  - fs/utimes.c:__ia32_compat_sys_futimesat
```
**Symbols:**

```
ffffffff812d31a0-ffffffff812d3283: do_compat_futimesat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int do_compat_futimesat(unsigned int dfd, const char *filename, struct old_timeval32 *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/utimes.c (ffffffff812e8570)
Location: fs/utimes.c:259
Inline: False
Direct callers:
  - fs/utimes.c:__x32_compat_sys_utimes
  - fs/utimes.c:__ia32_compat_sys_utimes
  - fs/utimes.c:__x32_compat_sys_futimesat
  - fs/utimes.c:__ia32_compat_sys_futimesat
```
**Symbols:**

```
ffffffff812e8570-ffffffff812e8652: do_compat_futimesat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int do_compat_futimesat(unsigned int dfd, const char *filename, struct old_timeval32 *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/utimes.c (ffffffff81306e80)
Location: fs/utimes.c:259
Inline: False
Direct callers:
  - fs/utimes.c:__ia32_sys_utimes_time32
  - fs/utimes.c:__x64_sys_utimes_time32
  - fs/utimes.c:__ia32_sys_futimesat_time32
  - fs/utimes.c:__x64_sys_futimesat_time32
```
**Symbols:**

```
ffffffff81306e80-ffffffff81306f62: do_compat_futimesat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int do_compat_futimesat(unsigned int dfd, const char *filename, struct old_timeval32 *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/utimes.c (ffffffff81319ee0)
Location: fs/utimes.c:257
Inline: False
Direct callers:
  - fs/utimes.c:__ia32_sys_utimes_time32
  - fs/utimes.c:__x64_sys_utimes_time32
  - fs/utimes.c:__ia32_sys_futimesat_time32
  - fs/utimes.c:__x64_sys_futimesat_time32
```
**Symbols:**

```
ffffffff81319ee0-ffffffff81319fc2: do_compat_futimesat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int do_compat_futimesat(unsigned int dfd, const char *filename, struct old_timeval32 *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/utimes.c (ffffffff81353e40)
Location: fs/utimes.c:259
Inline: False
Direct callers:
  - fs/utimes.c:__ia32_sys_utimes_time32
  - fs/utimes.c:__x64_sys_utimes_time32
  - fs/utimes.c:__ia32_sys_futimesat_time32
  - fs/utimes.c:__x64_sys_futimesat_time32
```
**Symbols:**

```
ffffffff81353e40-ffffffff81353f14: do_compat_futimesat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int do_compat_futimesat(unsigned int dfd, const char *filename, struct old_timeval32 *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/utimes.c (ffffffff81360730)
Location: fs/utimes.c:266
Inline: False
Direct callers:
  - fs/utimes.c:__ia32_sys_utimes_time32
  - fs/utimes.c:__x64_sys_utimes_time32
  - fs/utimes.c:__ia32_sys_futimesat_time32
  - fs/utimes.c:__x64_sys_futimesat_time32
```
**Symbols:**

```
ffffffff81360730-ffffffff81360804: do_compat_futimesat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int do_compat_futimesat(unsigned int dfd, const char *filename, struct old_timeval32 *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/utimes.c (ffffffff81367210)
Location: fs/utimes.c:267
Inline: False
Direct callers:
  - fs/utimes.c:__ia32_sys_utimes_time32
  - fs/utimes.c:__x64_sys_utimes_time32
  - fs/utimes.c:__ia32_sys_futimesat_time32
  - fs/utimes.c:__x64_sys_futimesat_time32
```
**Symbols:**

```
ffffffff81367210-ffffffff813672f2: do_compat_futimesat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int do_compat_futimesat(unsigned int dfd, const char *filename, struct old_timeval32 *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/utimes.c (ffffffff813b5d60)
Location: fs/utimes.c:267
Inline: False
Direct callers:
  - fs/utimes.c:__ia32_sys_utimes_time32
  - fs/utimes.c:__x64_sys_utimes_time32
  - fs/utimes.c:__ia32_sys_futimesat_time32
  - fs/utimes.c:__x64_sys_futimesat_time32
```
**Symbols:**

```
ffffffff813b5d60-ffffffff813b5e42: do_compat_futimesat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int do_compat_futimesat(unsigned int dfd, const char *filename, struct old_timeval32 *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/utimes.c (ffffffff8143b1f0)
Location: fs/utimes.c:267
Inline: False
Direct callers:
  - fs/utimes.c:__ia32_sys_utimes_time32
  - fs/utimes.c:__x64_sys_utimes_time32
  - fs/utimes.c:__ia32_sys_futimesat_time32
  - fs/utimes.c:__x64_sys_futimesat_time32
```
**Symbols:**

```
ffffffff8143b1f0-ffffffff8143b30e: do_compat_futimesat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int do_compat_futimesat(unsigned int dfd, const char *filename, struct old_timeval32 *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/utimes.c (ffffffff814c9750)
Location: fs/utimes.c:267
Inline: False
Direct callers:
  - fs/utimes.c:__ia32_sys_utimes_time32
  - fs/utimes.c:__x64_sys_utimes_time32
  - fs/utimes.c:__ia32_sys_futimesat_time32
  - fs/utimes.c:__x64_sys_futimesat_time32
```
**Symbols:**

```
ffffffff814c9750-ffffffff814c986e: do_compat_futimesat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int do_compat_futimesat(unsigned int dfd, const char *filename, struct old_timeval32 *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/utimes.c (ffffffff814ff990)
Location: fs/utimes.c:268
Inline: False
Direct callers:
  - fs/utimes.c:__ia32_sys_utimes_time32
  - fs/utimes.c:__x64_sys_utimes_time32
  - fs/utimes.c:__ia32_sys_futimesat_time32
  - fs/utimes.c:__x64_sys_futimesat_time32
```
**Symbols:**

```
ffffffff814ff990-ffffffff814ffaae: do_compat_futimesat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int do_compat_futimesat(unsigned int dfd, const char *filename, struct old_timeval32 *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/utimes.c (ffffffff815345b0)
Location: fs/utimes.c:268
Inline: False
Direct callers:
  - fs/utimes.c:__ia32_sys_utimes_time32
  - fs/utimes.c:__x64_sys_utimes_time32
  - fs/utimes.c:__ia32_sys_futimesat_time32
  - fs/utimes.c:__x64_sys_futimesat_time32
```
**Symbols:**

```
ffffffff815345b0-ffffffff815346ce: do_compat_futimesat (STB_LOCAL)
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
long int do_compat_futimesat(unsigned int dfd, const char *filename, struct old_timeval32 *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/utimes.c (ffff8000103d0f58)
Location: fs/utimes.c:257
Inline: False
Direct callers:
  - fs/utimes.c:__arm64_sys_utimes_time32
  - fs/utimes.c:__arm64_sys_futimesat_time32
```
**Symbols:**

```
ffff8000103d0f58-ffff8000103d14f4: do_compat_futimesat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int do_compat_futimesat(unsigned int dfd, const char *filename, struct old_timeval32 *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/utimes.c (c05abe10)
Location: fs/utimes.c:257
Inline: False
Direct callers:
  - fs/utimes.c:__se_sys_utimes_time32
  - fs/utimes.c:__se_sys_futimesat_time32
```
**Symbols:**

```
c05abe10-c05abfd4: do_compat_futimesat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int do_compat_futimesat(unsigned int dfd, const char *filename, struct old_timeval32 *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/utimes.c (c0000000004d3ba0)
Location: fs/utimes.c:257
Inline: False
Direct callers:
  - fs/utimes.c:__se_sys_utimes_time32
  - fs/utimes.c:__se_sys_futimesat_time32
```
**Symbols:**

```
c0000000004d3ba0-c0000000004d3e78: do_compat_futimesat (STB_LOCAL)
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
long int do_compat_futimesat(unsigned int dfd, const char *filename, struct old_timeval32 *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/utimes.c (ffffffff813124c0)
Location: fs/utimes.c:257
Inline: False
Direct callers:
  - fs/utimes.c:__ia32_sys_utimes_time32
  - fs/utimes.c:__x64_sys_utimes_time32
  - fs/utimes.c:__ia32_sys_futimesat_time32
  - fs/utimes.c:__x64_sys_futimesat_time32
```
**Symbols:**

```
ffffffff813124c0-ffffffff813125a2: do_compat_futimesat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int do_compat_futimesat(unsigned int dfd, const char *filename, struct old_timeval32 *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/utimes.c (ffffffff813030d0)
Location: fs/utimes.c:257
Inline: False
Direct callers:
  - fs/utimes.c:__ia32_sys_utimes_time32
  - fs/utimes.c:__x64_sys_utimes_time32
  - fs/utimes.c:__ia32_sys_futimesat_time32
  - fs/utimes.c:__x64_sys_futimesat_time32
```
**Symbols:**

```
ffffffff813030d0-ffffffff813031b2: do_compat_futimesat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int do_compat_futimesat(unsigned int dfd, const char *filename, struct old_timeval32 *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/utimes.c (ffffffff813102b0)
Location: fs/utimes.c:257
Inline: False
Direct callers:
  - fs/utimes.c:__ia32_sys_utimes_time32
  - fs/utimes.c:__x64_sys_utimes_time32
  - fs/utimes.c:__ia32_sys_futimesat_time32
  - fs/utimes.c:__x64_sys_futimesat_time32
```
**Symbols:**

```
ffffffff813102b0-ffffffff81310392: do_compat_futimesat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int do_compat_futimesat(unsigned int dfd, const char *filename, struct old_timeval32 *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/utimes.c (ffffffff81321ab0)
Location: fs/utimes.c:257
Inline: False
Direct callers:
  - fs/utimes.c:__ia32_sys_utimes_time32
  - fs/utimes.c:__x64_sys_utimes_time32
  - fs/utimes.c:__ia32_sys_futimesat_time32
  - fs/utimes.c:__x64_sys_futimesat_time32
```
**Symbols:**

```
ffffffff81321ab0-ffffffff81321b92: do_compat_futimesat (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct compat_timeval *t</code> ➡️ <code>struct old_timeval32 *t</code>
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
