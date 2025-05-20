# Function: <code>__do_sys_process_madvise</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int __do_sys_process_madvise(int pidfd, const struct iovec *vec, size_t vlen, int behavior, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff812c1940)
Location: mm/madvise.c:1161
Inline: False
Direct callers:
  - mm/madvise.c:__ia32_sys_process_madvise
  - mm/madvise.c:__x64_sys_process_madvise
```
**Symbols:**

```
ffffffff812c1940-ffffffff812c1b73: __do_sys_process_madvise (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int __do_sys_process_madvise(int pidfd, const struct iovec *vec, size_t vlen, int behavior, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff812c8840)
Location: mm/madvise.c:1162
Inline: False
Direct callers:
  - mm/madvise.c:__ia32_sys_process_madvise
  - mm/madvise.c:__x64_sys_process_madvise
```
**Symbols:**

```
ffffffff812c8840-ffffffff812c8a59: __do_sys_process_madvise (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int __do_sys_process_madvise(int pidfd, const struct iovec *vec, size_t vlen, int behavior, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff8130d810)
Location: mm/madvise.c:1231
Inline: False
Direct callers:
  - mm/madvise.c:__ia32_sys_process_madvise
  - mm/madvise.c:__x64_sys_process_madvise
```
**Symbols:**

```
ffffffff8130d810-ffffffff8130da6c: __do_sys_process_madvise (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int __do_sys_process_madvise(int pidfd, const struct iovec *vec, size_t vlen, int behavior, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff81378c90)
Location: mm/madvise.c:1426
Inline: False
Direct callers:
  - mm/madvise.c:__ia32_sys_process_madvise
  - mm/madvise.c:__x64_sys_process_madvise
```
**Symbols:**

```
ffffffff81378c90-ffffffff81378ec7: __do_sys_process_madvise (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int __do_sys_process_madvise(int pidfd, const struct iovec *vec, size_t vlen, int behavior, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff813f65f0)
Location: mm/madvise.c:1460
Inline: False
Direct callers:
  - mm/madvise.c:__ia32_sys_process_madvise
  - mm/madvise.c:__x64_sys_process_madvise
```
**Symbols:**

```
ffffffff813f65f0-ffffffff813f6830: __do_sys_process_madvise (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int __do_sys_process_madvise(int pidfd, const struct iovec *vec, size_t vlen, int behavior, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff81429510)
Location: mm/madvise.c:1463
Inline: False
Direct callers:
  - mm/madvise.c:__ia32_sys_process_madvise
  - mm/madvise.c:__x64_sys_process_madvise
```
**Symbols:**

```
ffffffff81429510-ffffffff8142975f: __do_sys_process_madvise (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int __do_sys_process_madvise(int pidfd, const struct iovec *vec, size_t vlen, int behavior, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff81462d40)
Location: mm/madvise.c:1457
Inline: False
Direct callers:
  - mm/madvise.c:__ia32_sys_process_madvise
  - mm/madvise.c:__x64_sys_process_madvise
```
**Symbols:**

```
ffffffff81462d40-ffffffff81462f8f: __do_sys_process_madvise (STB_LOCAL)
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
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
