# Function: <code>cp_new_stat64</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
long int cp_new_stat64(struct kstat *stat, struct stat64 *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffff80001038b498)
Location: fs/stat.c:443
Inline: False
Direct callers:
  - fs/stat.c:__do_sys_fstatat64
  - fs/stat.c:__do_sys_fstat64
  - fs/stat.c:__do_sys_lstat64
  - fs/stat.c:__do_sys_stat64
```
**Symbols:**

```
ffff80001038b498-ffff80001038b60c: cp_new_stat64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int cp_new_stat64(struct kstat *stat, struct stat64 *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (c0572e18)
Location: fs/stat.c:443
Inline: False
Direct callers:
  - fs/stat.c:__do_sys_fstatat64
  - fs/stat.c:__do_sys_fstat64
  - fs/stat.c:__do_sys_lstat64
  - fs/stat.c:__do_sys_stat64
```
**Symbols:**

```
c0572e18-c0572fd8: cp_new_stat64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int cp_new_stat64(struct kstat *stat, struct stat64 *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (c000000000481fd0)
Location: fs/stat.c:443
Inline: False
Direct callers:
  - fs/stat.c:__do_sys_fstatat64
  - fs/stat.c:__do_sys_fstat64
  - fs/stat.c:__do_sys_lstat64
  - fs/stat.c:__do_sys_stat64
```
**Symbols:**

```
c000000000481fd0-c000000000482160: cp_new_stat64 (STB_LOCAL)
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
<b>Arch</b>
<ul>
</ul>
