# Function: <code>C_SYSC_statfs64</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long int C_SYSC_statfs64(const char *pathname, compat_size_t sz, struct compat_statfs64 *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/compat.c (ffffffff81263ba0)
Location: fs/compat.c:301
Inline: False
Direct callers:
  - fs/compat.c:compat_SyS_statfs64
```
**Symbols:**

```
ffffffff81263ba0-ffffffff81263c05: C_SYSC_statfs64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int C_SYSC_statfs64(const char *pathname, compat_size_t sz, struct compat_statfs64 *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/compat.c (ffffffff8128fd30)
Location: fs/compat.c:301
Inline: False
Direct callers:
  - fs/compat.c:compat_SyS_statfs64
```
**Symbols:**

```
ffffffff8128fd30-ffffffff8128fd95: C_SYSC_statfs64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int C_SYSC_statfs64(const char *pathname, compat_size_t sz, struct compat_statfs64 *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/compat.c (ffffffff812a4d70)
Location: fs/compat.c:287
Inline: False
Direct callers:
  - fs/compat.c:compat_SyS_statfs64
```
**Symbols:**

```
ffffffff812a4d70-ffffffff812a4dd5: C_SYSC_statfs64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int C_SYSC_statfs64(const char *pathname, compat_size_t sz, struct compat_statfs64 *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff8128a8b0)
Location: fs/statfs.c:337
Inline: False
Direct callers:
  - fs/statfs.c:compat_SyS_statfs64
```
**Symbols:**

```
ffffffff8128a8b0-ffffffff8128a915: C_SYSC_statfs64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int C_SYSC_statfs64(const char *pathname, compat_size_t sz, struct compat_statfs64 *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff812ad5d0)
Location: fs/statfs.c:338
Inline: False
Direct callers:
  - fs/statfs.c:compat_SyS_statfs64
```
**Symbols:**

```
ffffffff812ad5d0-ffffffff812ad635: C_SYSC_statfs64 (STB_LOCAL)
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
