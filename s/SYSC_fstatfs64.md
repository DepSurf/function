# Function: <code>SYSC_fstatfs64</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long int SYSC_fstatfs64(unsigned int fd, size_t sz, struct statfs64 *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81241d30)
Location: fs/statfs.c:202
Inline: False
Direct callers:
  - fs/statfs.c:SyS_fstatfs64
```
**Symbols:**

```
ffffffff81241d30-ffffffff81241d96: SYSC_fstatfs64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int SYSC_fstatfs64(unsigned int fd, size_t sz, struct statfs64 *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff8126a080)
Location: fs/statfs.c:202
Inline: False
Direct callers:
  - fs/statfs.c:SyS_fstatfs64
```
**Symbols:**

```
ffffffff8126a080-ffffffff8126a0e6: SYSC_fstatfs64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int SYSC_fstatfs64(unsigned int fd, size_t sz, struct statfs64 *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff8127d030)
Location: fs/statfs.c:202
Inline: False
Direct callers:
  - fs/statfs.c:SyS_fstatfs64
```
**Symbols:**

```
ffffffff8127d030-ffffffff8127d096: SYSC_fstatfs64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int SYSC_fstatfs64(unsigned int fd, size_t sz, struct statfs64 *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff8128a9e0)
Location: fs/statfs.c:205
Inline: False
Direct callers:
  - fs/statfs.c:SyS_fstatfs64
```
**Symbols:**

```
ffffffff8128a9e0-ffffffff8128aa46: SYSC_fstatfs64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int SYSC_fstatfs64(unsigned int fd, size_t sz, struct statfs64 *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff812ad700)
Location: fs/statfs.c:206
Inline: False
Direct callers:
  - fs/statfs.c:SyS_fstatfs64
```
**Symbols:**

```
ffffffff812ad700-ffffffff812ad766: SYSC_fstatfs64 (STB_LOCAL)
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
