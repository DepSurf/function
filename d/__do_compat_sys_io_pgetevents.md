# Function: <code>__do_compat_sys_io_pgetevents</code>

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
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff812f3855)
Location: fs/aio.c:1974
Inline: True
Inline callers:
  - fs/aio.c:__x32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff813088c5)
Location: fs/aio.c:2223
Inline: True
Inline callers:
  - fs/aio.c:__x32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff8132a54d)
Location: fs/aio.c:2188
Inline: True
Inline callers:
  - fs/aio.c:__x32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff8133d255)
Location: fs/aio.c:2204
Inline: True
Inline callers:
  - fs/aio.c:__x32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
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
In fs/aio.c (ffffffff81376625)
Location: fs/aio.c:2211
Inline: True
Inline callers:
  - fs/aio.c:__x32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int __do_compat_sys_io_pgetevents(compat_aio_context_t ctx_id, compat_long_t min_nr, compat_long_t nr, struct io_event *events, struct old_timespec32 *timeout, const struct __compat_aio_sigset *usig);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81384200)
Location: fs/aio.c:2209
Inline: False
Direct callers:
  - fs/aio.c:__x32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
```
**Symbols:**

```
ffffffff81384200-ffffffff81384356: __do_compat_sys_io_pgetevents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int __do_compat_sys_io_pgetevents(compat_aio_context_t ctx_id, compat_long_t min_nr, compat_long_t nr, struct io_event *events, struct old_timespec32 *timeout, const struct __compat_aio_sigset *usig);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff8138ae50)
Location: fs/aio.c:2206
Inline: False
Direct callers:
  - fs/aio.c:__x32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
```
**Symbols:**

```
ffffffff8138ae50-ffffffff8138afa6: __do_compat_sys_io_pgetevents (STB_LOCAL)
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
In fs/aio.c (ffffffff813d8735)
Location: fs/aio.c:2324
Inline: True
Inline callers:
  - fs/aio.c:__x64_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
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
In fs/aio.c (ffffffff814628f4)
Location: fs/aio.c:2348
Inline: True
Inline callers:
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
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
In fs/aio.c (ffffffff814f2f84)
Location: fs/aio.c:2349
Inline: True
Inline callers:
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
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
In fs/aio.c (ffffffff81529d34)
Location: fs/aio.c:2341
Inline: True
Inline callers:
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
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
In fs/aio.c (ffffffff8155ec04)
Location: fs/aio.c:2384
Inline: True
Inline callers:
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
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
In fs/aio.c (ffff8000103fc9ec)
Location: fs/aio.c:2204
Inline: True
Inline callers:
  - fs/aio.c:__arm64_compat_sys_io_pgetevents
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
In fs/aio.c (c000000000505738)
Location: fs/aio.c:2204
Inline: True
Inline callers:
  - fs/aio.c:__se_compat_sys_io_pgetevents
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81335835)
Location: fs/aio.c:2204
Inline: True
Inline callers:
  - fs/aio.c:__x32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81326315)
Location: fs/aio.c:2204
Inline: True
Inline callers:
  - fs/aio.c:__x32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81333305)
Location: fs/aio.c:2204
Inline: True
Inline callers:
  - fs/aio.c:__x32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff813465f5)
Location: fs/aio.c:2204
Inline: True
Inline callers:
  - fs/aio.c:__x32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
</ul>
