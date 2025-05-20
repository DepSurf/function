# Function: <code>do_io_getevents</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int do_io_getevents(aio_context_t ctx_id, long int min_nr, long int nr, struct io_event *events, struct timespec *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff812c9f20)
Location: fs/aio.c:1835
Inline: False
Direct callers:
  - fs/aio.c:compat_SyS_io_getevents
  - fs/aio.c:SyS_io_getevents
```
**Symbols:**

```
ffffffff812c9f20-ffffffff812c9fe3: do_io_getevents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long int do_io_getevents(aio_context_t ctx_id, long int min_nr, long int nr, struct io_event *events, struct timespec64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff812f3160)
Location: fs/aio.c:1850
Inline: False
Direct callers:
  - fs/aio.c:__x32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__x32_compat_sys_io_getevents
  - fs/aio.c:__ia32_compat_sys_io_getevents
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_getevents
  - fs/aio.c:__x64_sys_io_getevents
```
**Symbols:**

```
ffffffff812f3160-ffffffff812f3223: do_io_getevents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int do_io_getevents(aio_context_t ctx_id, long int min_nr, long int nr, struct io_event *events, struct timespec64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81308160)
Location: fs/aio.c:2067
Inline: False
Direct callers:
  - fs/aio.c:__x32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__x32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__x32_compat_sys_io_getevents
  - fs/aio.c:__ia32_compat_sys_io_getevents
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_getevents
  - fs/aio.c:__x64_sys_io_getevents
```
**Symbols:**

```
ffffffff81308160-ffffffff81308223: do_io_getevents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int do_io_getevents(aio_context_t ctx_id, long int min_nr, long int nr, struct io_event *events, struct timespec64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81329c20)
Location: fs/aio.c:2028
Inline: False
Direct callers:
  - fs/aio.c:__x32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__x32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_getevents_time32
  - fs/aio.c:__x64_sys_io_getevents_time32
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_getevents
  - fs/aio.c:__x64_sys_io_getevents
```
**Symbols:**

```
ffffffff81329c20-ffffffff81329cf5: do_io_getevents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int do_io_getevents(aio_context_t ctx_id, long int min_nr, long int nr, struct io_event *events, struct timespec64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff8133ca80)
Location: fs/aio.c:2044
Inline: False
Direct callers:
  - fs/aio.c:__x32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__x32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_getevents_time32
  - fs/aio.c:__x64_sys_io_getevents_time32
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_getevents
  - fs/aio.c:__x64_sys_io_getevents
```
**Symbols:**

```
ffffffff8133ca80-ffffffff8133cb55: do_io_getevents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int do_io_getevents(aio_context_t ctx_id, long int min_nr, long int nr, struct io_event *events, struct timespec64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81375e50)
Location: fs/aio.c:2051
Inline: False
Direct callers:
  - fs/aio.c:__x32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__x32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_getevents_time32
  - fs/aio.c:__x64_sys_io_getevents_time32
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_getevents
  - fs/aio.c:__x64_sys_io_getevents
```
**Symbols:**

```
ffffffff81375e50-ffffffff81375f25: do_io_getevents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int do_io_getevents(aio_context_t ctx_id, long int min_nr, long int nr, struct io_event *events, struct timespec64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81383dd0)
Location: fs/aio.c:2049
Inline: False
Direct callers:
  - fs/aio.c:__do_compat_sys_io_pgetevents_time64
  - fs/aio.c:__do_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_getevents_time32
  - fs/aio.c:__x64_sys_io_getevents_time32
  - fs/aio.c:__do_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_getevents
  - fs/aio.c:__x64_sys_io_getevents
```
**Symbols:**

```
ffffffff81383dd0-ffffffff81383ea5: do_io_getevents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int do_io_getevents(aio_context_t ctx_id, long int min_nr, long int nr, struct io_event *events, struct timespec64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff8138aa20)
Location: fs/aio.c:2046
Inline: False
Direct callers:
  - fs/aio.c:__do_compat_sys_io_pgetevents_time64
  - fs/aio.c:__do_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_getevents_time32
  - fs/aio.c:__x64_sys_io_getevents_time32
  - fs/aio.c:__do_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_getevents
  - fs/aio.c:__x64_sys_io_getevents
```
**Symbols:**

```
ffffffff8138aa20-ffffffff8138aaf5: do_io_getevents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int do_io_getevents(aio_context_t ctx_id, long int min_nr, long int nr, struct io_event *events, struct timespec64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff813d7d30)
Location: fs/aio.c:2164
Inline: False
Direct callers:
  - fs/aio.c:__x64_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__x64_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_getevents_time32
  - fs/aio.c:__x64_sys_io_getevents_time32
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_getevents
  - fs/aio.c:__x64_sys_io_getevents
```
**Symbols:**

```
ffffffff813d7d30-ffffffff813d7e05: do_io_getevents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int do_io_getevents(aio_context_t ctx_id, long int min_nr, long int nr, struct io_event *events, struct timespec64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81462450)
Location: fs/aio.c:2188
Inline: False
Direct callers:
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_getevents_time32
  - fs/aio.c:__x64_sys_io_getevents_time32
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_getevents
  - fs/aio.c:__x64_sys_io_getevents
```
**Symbols:**

```
ffffffff81462450-ffffffff81462545: do_io_getevents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int do_io_getevents(aio_context_t ctx_id, long int min_nr, long int nr, struct io_event *events, struct timespec64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff814f2aa0)
Location: fs/aio.c:2189
Inline: False
Direct callers:
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_getevents_time32
  - fs/aio.c:__x64_sys_io_getevents_time32
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_getevents
  - fs/aio.c:__x64_sys_io_getevents
```
**Symbols:**

```
ffffffff814f2aa0-ffffffff814f2b95: do_io_getevents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int do_io_getevents(aio_context_t ctx_id, long int min_nr, long int nr, struct io_event *events, struct timespec64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81529850)
Location: fs/aio.c:2181
Inline: False
Direct callers:
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_getevents_time32
  - fs/aio.c:__x64_sys_io_getevents_time32
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_getevents
  - fs/aio.c:__x64_sys_io_getevents
```
**Symbols:**

```
ffffffff81529850-ffffffff81529945: do_io_getevents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int do_io_getevents(aio_context_t ctx_id, long int min_nr, long int nr, struct io_event *events, struct timespec64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff8155e720)
Location: fs/aio.c:2224
Inline: False
Direct callers:
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_getevents_time32
  - fs/aio.c:__x64_sys_io_getevents_time32
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_getevents
  - fs/aio.c:__x64_sys_io_getevents
```
**Symbols:**

```
ffffffff8155e720-ffffffff8155e815: do_io_getevents (STB_LOCAL)
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
long int do_io_getevents(aio_context_t ctx_id, long int min_nr, long int nr, struct io_event *events, struct timespec64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffff8000103fc470)
Location: fs/aio.c:2044
Inline: False
Direct callers:
  - fs/aio.c:__arm64_compat_sys_io_pgetevents_time64
  - fs/aio.c:__arm64_compat_sys_io_pgetevents
  - fs/aio.c:__arm64_sys_io_getevents_time32
  - fs/aio.c:__arm64_sys_io_pgetevents
  - fs/aio.c:__arm64_sys_io_getevents
```
**Symbols:**

```
ffff8000103fc470-ffff8000103fc59c: do_io_getevents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int do_io_getevents(aio_context_t ctx_id, long int min_nr, long int nr, struct io_event *events, struct timespec64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (c05cfa20)
Location: fs/aio.c:2044
Inline: False
Direct callers:
  - fs/aio.c:__se_sys_io_getevents_time32
  - fs/aio.c:__se_sys_io_pgetevents_time32
  - fs/aio.c:__se_sys_io_pgetevents
```
**Symbols:**

```
c05cfa20-c05cfc98: do_io_getevents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int do_io_getevents(aio_context_t ctx_id, long int min_nr, long int nr, struct io_event *events, struct timespec64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (c0000000005051a0)
Location: fs/aio.c:2044
Inline: False
Direct callers:
  - fs/aio.c:__se_compat_sys_io_pgetevents_time64
  - fs/aio.c:__se_compat_sys_io_pgetevents
  - fs/aio.c:__se_sys_io_getevents_time32
  - fs/aio.c:__se_sys_io_pgetevents
  - fs/aio.c:__se_sys_io_getevents
```
**Symbols:**

```
c0000000005051a0-c000000000505330: do_io_getevents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int do_io_getevents(aio_context_t ctx_id, long int min_nr, long int nr, struct io_event *events, struct timespec64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffe0002aa0fc)
Location: fs/aio.c:2044
Inline: False
Direct callers:
  - fs/aio.c:__se_sys_io_pgetevents
  - fs/aio.c:__se_sys_io_getevents
```
**Symbols:**

```
ffffffe0002aa0fc-ffffffe0002aa1e2: do_io_getevents (STB_LOCAL)
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
long int do_io_getevents(aio_context_t ctx_id, long int min_nr, long int nr, struct io_event *events, struct timespec64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81335060)
Location: fs/aio.c:2044
Inline: False
Direct callers:
  - fs/aio.c:__x32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__x32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_getevents_time32
  - fs/aio.c:__x64_sys_io_getevents_time32
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_getevents
  - fs/aio.c:__x64_sys_io_getevents
```
**Symbols:**

```
ffffffff81335060-ffffffff81335135: do_io_getevents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int do_io_getevents(aio_context_t ctx_id, long int min_nr, long int nr, struct io_event *events, struct timespec64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff813259f0)
Location: fs/aio.c:2044
Inline: False
Direct callers:
  - fs/aio.c:__x32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__x32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_getevents_time32
  - fs/aio.c:__x64_sys_io_getevents_time32
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_getevents
  - fs/aio.c:__x64_sys_io_getevents
```
**Symbols:**

```
ffffffff813259f0-ffffffff81325ac5: do_io_getevents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int do_io_getevents(aio_context_t ctx_id, long int min_nr, long int nr, struct io_event *events, struct timespec64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81332b30)
Location: fs/aio.c:2044
Inline: False
Direct callers:
  - fs/aio.c:__x32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__x32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_getevents_time32
  - fs/aio.c:__x64_sys_io_getevents_time32
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_getevents
  - fs/aio.c:__x64_sys_io_getevents
```
**Symbols:**

```
ffffffff81332b30-ffffffff81332c05: do_io_getevents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int do_io_getevents(aio_context_t ctx_id, long int min_nr, long int nr, struct io_event *events, struct timespec64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81345cc0)
Location: fs/aio.c:2044
Inline: False
Direct callers:
  - fs/aio.c:__x32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__x32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_getevents_time32
  - fs/aio.c:__x64_sys_io_getevents_time32
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_getevents
  - fs/aio.c:__x64_sys_io_getevents
```
**Symbols:**

```
ffffffff81345cc0-ffffffff81345dac: do_io_getevents (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct timespec *ts</code> ➡️ <code>struct timespec64 *ts</code>
</li>
</ul>
</details>
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
