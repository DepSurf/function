# Function: <code>do_futimesat</code>

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
long int do_futimesat(int dfd, const char *filename, struct timeval *utimes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/utimes.c (ffffffff812d2ee0)
Location: fs/utimes.c:187
Inline: False
Direct callers:
  - fs/utimes.c:__ia32_sys_utimes
  - fs/utimes.c:__x64_sys_utimes
  - fs/utimes.c:__ia32_sys_futimesat
  - fs/utimes.c:__x64_sys_futimesat
```
**Symbols:**

```
ffffffff812d2ee0-ffffffff812d2fb2: do_futimesat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int do_futimesat(int dfd, const char *filename, struct timeval *utimes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/utimes.c (ffffffff812e8220)
Location: fs/utimes.c:165
Inline: False
Direct callers:
  - fs/utimes.c:__ia32_sys_utimes
  - fs/utimes.c:__x64_sys_utimes
  - fs/utimes.c:__ia32_sys_futimesat
  - fs/utimes.c:__x64_sys_futimesat
```
**Symbols:**

```
ffffffff812e8220-ffffffff812e82ed: do_futimesat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int do_futimesat(int dfd, const char *filename, struct timeval *utimes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/utimes.c (ffffffff81306b20)
Location: fs/utimes.c:165
Inline: False
Direct callers:
  - fs/utimes.c:__ia32_sys_utimes
  - fs/utimes.c:__x64_sys_utimes
  - fs/utimes.c:__ia32_sys_futimesat
  - fs/utimes.c:__x64_sys_futimesat
```
**Symbols:**

```
ffffffff81306b20-ffffffff81306bf4: do_futimesat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int do_futimesat(int dfd, const char *filename, struct timeval *utimes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/utimes.c (ffffffff81319b80)
Location: fs/utimes.c:163
Inline: False
Direct callers:
  - fs/utimes.c:__ia32_sys_utimes
  - fs/utimes.c:__x64_sys_utimes
  - fs/utimes.c:__ia32_sys_futimesat
  - fs/utimes.c:__x64_sys_futimesat
```
**Symbols:**

```
ffffffff81319b80-ffffffff81319c54: do_futimesat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int do_futimesat(int dfd, const char *filename, struct __kernel_old_timeval *utimes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/utimes.c (ffffffff81353b10)
Location: fs/utimes.c:165
Inline: False
Direct callers:
  - fs/utimes.c:__ia32_sys_utimes
  - fs/utimes.c:__x64_sys_utimes
  - fs/utimes.c:__ia32_sys_futimesat
  - fs/utimes.c:__x64_sys_futimesat
```
**Symbols:**

```
ffffffff81353b10-ffffffff81353bd7: do_futimesat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int do_futimesat(int dfd, const char *filename, struct __kernel_old_timeval *utimes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/utimes.c (ffffffff81360400)
Location: fs/utimes.c:172
Inline: False
Direct callers:
  - fs/utimes.c:__ia32_sys_utimes
  - fs/utimes.c:__x64_sys_utimes
  - fs/utimes.c:__ia32_sys_futimesat
  - fs/utimes.c:__x64_sys_futimesat
```
**Symbols:**

```
ffffffff81360400-ffffffff813604c7: do_futimesat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int do_futimesat(int dfd, const char *filename, struct __kernel_old_timeval *utimes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/utimes.c (ffffffff81366eb0)
Location: fs/utimes.c:173
Inline: False
Direct callers:
  - fs/utimes.c:__ia32_sys_utimes
  - fs/utimes.c:__x64_sys_utimes
  - fs/utimes.c:__ia32_sys_futimesat
  - fs/utimes.c:__x64_sys_futimesat
```
**Symbols:**

```
ffffffff81366eb0-ffffffff81366f84: do_futimesat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int do_futimesat(int dfd, const char *filename, struct __kernel_old_timeval *utimes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/utimes.c (ffffffff813b5a00)
Location: fs/utimes.c:173
Inline: False
Direct callers:
  - fs/utimes.c:__ia32_sys_utimes
  - fs/utimes.c:__x64_sys_utimes
  - fs/utimes.c:__ia32_sys_futimesat
  - fs/utimes.c:__x64_sys_futimesat
```
**Symbols:**

```
ffffffff813b5a00-ffffffff813b5ad4: do_futimesat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int do_futimesat(int dfd, const char *filename, struct __kernel_old_timeval *utimes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/utimes.c (ffffffff8143ada0)
Location: fs/utimes.c:173
Inline: False
Direct callers:
  - fs/utimes.c:__ia32_sys_utimes
  - fs/utimes.c:__x64_sys_utimes
  - fs/utimes.c:__ia32_sys_futimesat
  - fs/utimes.c:__x64_sys_futimesat
```
**Symbols:**

```
ffffffff8143ada0-ffffffff8143aec6: do_futimesat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int do_futimesat(int dfd, const char *filename, struct __kernel_old_timeval *utimes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/utimes.c (ffffffff814c9280)
Location: fs/utimes.c:173
Inline: False
Direct callers:
  - fs/utimes.c:__ia32_sys_utimes
  - fs/utimes.c:__x64_sys_utimes
  - fs/utimes.c:__ia32_sys_futimesat
  - fs/utimes.c:__x64_sys_futimesat
```
**Symbols:**

```
ffffffff814c9280-ffffffff814c93a6: do_futimesat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int do_futimesat(int dfd, const char *filename, struct __kernel_old_timeval *utimes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/utimes.c (ffffffff814ff4c0)
Location: fs/utimes.c:174
Inline: False
Direct callers:
  - fs/utimes.c:__ia32_sys_utimes
  - fs/utimes.c:__x64_sys_utimes
  - fs/utimes.c:__ia32_sys_futimesat
  - fs/utimes.c:__x64_sys_futimesat
```
**Symbols:**

```
ffffffff814ff4c0-ffffffff814ff5e6: do_futimesat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int do_futimesat(int dfd, const char *filename, struct __kernel_old_timeval *utimes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/utimes.c (ffffffff815340e0)
Location: fs/utimes.c:174
Inline: False
Direct callers:
  - fs/utimes.c:__ia32_sys_utimes
  - fs/utimes.c:__x64_sys_utimes
  - fs/utimes.c:__ia32_sys_futimesat
  - fs/utimes.c:__x64_sys_futimesat
```
**Symbols:**

```
ffffffff815340e0-ffffffff81534206: do_futimesat (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int do_futimesat(int dfd, const char *filename, struct timeval *utimes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/utimes.c (c0000000004d35e0)
Location: fs/utimes.c:163
Inline: False
Direct callers:
  - fs/utimes.c:__se_sys_utimes
  - fs/utimes.c:__se_sys_futimesat
```
**Symbols:**

```
c0000000004d35e0-c0000000004d36d8: do_futimesat (STB_LOCAL)
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
long int do_futimesat(int dfd, const char *filename, struct timeval *utimes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/utimes.c (ffffffff81312160)
Location: fs/utimes.c:163
Inline: False
Direct callers:
  - fs/utimes.c:__ia32_sys_utimes
  - fs/utimes.c:__x64_sys_utimes
  - fs/utimes.c:__ia32_sys_futimesat
  - fs/utimes.c:__x64_sys_futimesat
```
**Symbols:**

```
ffffffff81312160-ffffffff81312234: do_futimesat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int do_futimesat(int dfd, const char *filename, struct timeval *utimes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/utimes.c (ffffffff81302d70)
Location: fs/utimes.c:163
Inline: False
Direct callers:
  - fs/utimes.c:__ia32_sys_utimes
  - fs/utimes.c:__x64_sys_utimes
  - fs/utimes.c:__ia32_sys_futimesat
  - fs/utimes.c:__x64_sys_futimesat
```
**Symbols:**

```
ffffffff81302d70-ffffffff81302e44: do_futimesat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int do_futimesat(int dfd, const char *filename, struct timeval *utimes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/utimes.c (ffffffff8130ff50)
Location: fs/utimes.c:163
Inline: False
Direct callers:
  - fs/utimes.c:__ia32_sys_utimes
  - fs/utimes.c:__x64_sys_utimes
  - fs/utimes.c:__ia32_sys_futimesat
  - fs/utimes.c:__x64_sys_futimesat
```
**Symbols:**

```
ffffffff8130ff50-ffffffff81310024: do_futimesat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int do_futimesat(int dfd, const char *filename, struct timeval *utimes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/utimes.c (ffffffff81321750)
Location: fs/utimes.c:163
Inline: False
Direct callers:
  - fs/utimes.c:__ia32_sys_utimes
  - fs/utimes.c:__x64_sys_utimes
  - fs/utimes.c:__ia32_sys_futimesat
  - fs/utimes.c:__x64_sys_futimesat
```
**Symbols:**

```
ffffffff81321750-ffffffff81321824: do_futimesat (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct timeval *utimes</code> ➡️ <code>struct __kernel_old_timeval *utimes</code>
</li>
</ul>
</details>
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
