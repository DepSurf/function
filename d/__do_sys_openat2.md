# Function: <code>__do_sys_openat2</code>

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
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8130fb30)
Location: fs/open.c:1213
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_openat2
  - fs/open.c:__x64_sys_openat2
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
In fs/open.c (ffffffff8131bdf0)
Location: fs/open.c:1208
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_openat2
  - fs/open.c:__x64_sys_openat2
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
In fs/open.c (ffffffff81321f61)
Location: fs/open.c:1230
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_openat2
  - fs/open.c:__x64_sys_openat2
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
In fs/open.c (ffffffff8136f451)
Location: fs/open.c:1248
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_openat2
  - fs/open.c:__x64_sys_openat2
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int __do_sys_openat2(int dfd, const char *filename, struct open_how *how, size_t usize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff813ede50)
Location: fs/open.c:1313
Inline: False
Direct callers:
  - fs/open.c:__ia32_sys_openat2
  - fs/open.c:__x64_sys_openat2
```
**Symbols:**

```
ffffffff813ede50-ffffffff813edf6e: __do_sys_openat2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int __do_sys_openat2(int dfd, const char *filename, struct open_how *how, size_t usize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff814765e0)
Location: fs/open.c:1345
Inline: False
Direct callers:
  - fs/open.c:__ia32_sys_openat2
  - fs/open.c:__x64_sys_openat2
```
**Symbols:**

```
ffffffff814765e0-ffffffff814766fe: __do_sys_openat2 (STB_LOCAL)
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
In fs/open.c (ffffffff814aaeaf)
Location: fs/open.c:1441
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_openat2
  - fs/open.c:__x64_sys_openat2
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
In fs/open.c (ffffffff814dc34f)
Location: fs/open.c:1438
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_openat2
  - fs/open.c:__x64_sys_openat2
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
</ul>
