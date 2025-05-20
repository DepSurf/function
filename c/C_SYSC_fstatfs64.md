# Function: <code>C_SYSC_fstatfs64</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long int C_SYSC_fstatfs64(unsigned int fd, compat_size_t sz, struct compat_statfs64 *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/compat.c (ffffffff81263c70)
Location: fs/compat.c:315
Inline: False
Direct callers:
  - fs/compat.c:compat_SyS_fstatfs64
```
**Symbols:**

```
ffffffff81263c70-ffffffff81263cd5: C_SYSC_fstatfs64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int C_SYSC_fstatfs64(unsigned int fd, compat_size_t sz, struct compat_statfs64 *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/compat.c (ffffffff8128fe00)
Location: fs/compat.c:315
Inline: False
Direct callers:
  - fs/compat.c:compat_SyS_fstatfs64
```
**Symbols:**

```
ffffffff8128fe00-ffffffff8128fe65: C_SYSC_fstatfs64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int C_SYSC_fstatfs64(unsigned int fd, compat_size_t sz, struct compat_statfs64 *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/compat.c (ffffffff812a4e40)
Location: fs/compat.c:301
Inline: False
Direct callers:
  - fs/compat.c:compat_SyS_fstatfs64
```
**Symbols:**

```
ffffffff812a4e40-ffffffff812a4ea5: C_SYSC_fstatfs64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int C_SYSC_fstatfs64(unsigned int fd, compat_size_t sz, struct compat_statfs64 *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff8128aab0)
Location: fs/statfs.c:351
Inline: False
Direct callers:
  - fs/statfs.c:compat_SyS_fstatfs64
```
**Symbols:**

```
ffffffff8128aab0-ffffffff8128ab15: C_SYSC_fstatfs64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int C_SYSC_fstatfs64(unsigned int fd, compat_size_t sz, struct compat_statfs64 *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff812ad7d0)
Location: fs/statfs.c:352
Inline: False
Direct callers:
  - fs/statfs.c:compat_SyS_fstatfs64
```
**Symbols:**

```
ffffffff812ad7d0-ffffffff812ad835: C_SYSC_fstatfs64 (STB_LOCAL)
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
