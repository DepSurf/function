# Function: <code>C_SYSC_fstatfs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long int C_SYSC_fstatfs(unsigned int fd, struct compat_statfs *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/compat.c (ffffffff81263c10)
Location: fs/compat.c:259
Inline: False
Direct callers:
  - fs/compat.c:compat_SyS_fstatfs
```
**Symbols:**

```
ffffffff81263c10-ffffffff81263c67: C_SYSC_fstatfs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int C_SYSC_fstatfs(unsigned int fd, struct compat_statfs *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/compat.c (ffffffff8128fda0)
Location: fs/compat.c:259
Inline: False
Direct callers:
  - fs/compat.c:compat_SyS_fstatfs
```
**Symbols:**

```
ffffffff8128fda0-ffffffff8128fdf7: C_SYSC_fstatfs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int C_SYSC_fstatfs(unsigned int fd, struct compat_statfs *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/compat.c (ffffffff812a4de0)
Location: fs/compat.c:245
Inline: False
Direct callers:
  - fs/compat.c:compat_SyS_fstatfs
```
**Symbols:**

```
ffffffff812a4de0-ffffffff812a4e37: C_SYSC_fstatfs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int C_SYSC_fstatfs(unsigned int fd, struct compat_statfs *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff8128aa50)
Location: fs/statfs.c:294
Inline: False
Direct callers:
  - fs/statfs.c:compat_SyS_fstatfs
```
**Symbols:**

```
ffffffff8128aa50-ffffffff8128aaa7: C_SYSC_fstatfs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int C_SYSC_fstatfs(unsigned int fd, struct compat_statfs *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff812ad770)
Location: fs/statfs.c:295
Inline: False
Direct callers:
  - fs/statfs.c:compat_SyS_fstatfs
```
**Symbols:**

```
ffffffff812ad770-ffffffff812ad7c7: C_SYSC_fstatfs (STB_LOCAL)
```
</details>
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
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
</ul>
