# Function: <code>C_SYSC_newfstatat</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long int C_SYSC_newfstatat(unsigned int dfd, const char *filename, struct compat_stat *statbuf, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/compat.c (ffffffff812637c0)
Location: fs/compat.c:187
Inline: False
Direct callers:
  - fs/compat.c:compat_SyS_newfstatat
```
**Symbols:**

```
ffffffff812637c0-ffffffff81263811: C_SYSC_newfstatat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int C_SYSC_newfstatat(unsigned int dfd, const char *filename, struct compat_stat *statbuf, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/compat.c (ffffffff8128f950)
Location: fs/compat.c:187
Inline: False
Direct callers:
  - fs/compat.c:compat_SyS_newfstatat
```
**Symbols:**

```
ffffffff8128f950-ffffffff8128f9a1: C_SYSC_newfstatat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int C_SYSC_newfstatat(unsigned int dfd, const char *filename, struct compat_stat *statbuf, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/compat.c (ffffffff812a4930)
Location: fs/compat.c:173
Inline: False
Direct callers:
  - fs/compat.c:compat_SyS_newfstatat
```
**Symbols:**

```
ffffffff812a4930-ffffffff812a4981: C_SYSC_newfstatat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int C_SYSC_newfstatat(unsigned int dfd, const char *filename, struct compat_stat *statbuf, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff81257450)
Location: fs/stat.c:638
Inline: False
Direct callers:
  - fs/stat.c:compat_SyS_newfstatat
```
**Symbols:**

```
ffffffff81257450-ffffffff812574b8: C_SYSC_newfstatat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int C_SYSC_newfstatat(unsigned int dfd, const char *filename, struct compat_stat *statbuf, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812796a0)
Location: fs/stat.c:639
Inline: False
Direct callers:
  - fs/stat.c:compat_SyS_newfstatat
```
**Symbols:**

```
ffffffff812796a0-ffffffff81279708: C_SYSC_newfstatat (STB_LOCAL)
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
