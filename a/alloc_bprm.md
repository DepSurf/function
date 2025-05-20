# Function: <code>alloc_bprm</code>

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
struct linux_binprm *alloc_bprm(int fd, struct filename *filename);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff81328a70)
Location: fs/exec.c:1505
Inline: False
Direct callers:
  - fs/exec.c:kernel_execve
  - fs/exec.c:do_execveat_common
```
**Symbols:**

```
ffffffff81328a70-ffffffff81328be4: alloc_bprm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct linux_binprm *alloc_bprm(int fd, struct filename *filename);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff8132e8d0)
Location: fs/exec.c:1502
Inline: False
Direct callers:
  - fs/exec.c:kernel_execve
```
**Symbols:**

```
ffffffff8132e8d0-ffffffff8132ea3f: alloc_bprm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct linux_binprm *alloc_bprm(int fd, struct filename *filename);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff8137c0e0)
Location: fs/exec.c:1504
Inline: False
Direct callers:
  - fs/exec.c:kernel_execve
```
**Symbols:**

```
ffffffff8137c0e0-ffffffff8137c24f: alloc_bprm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct linux_binprm *alloc_bprm(int fd, struct filename *filename);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff813faee0)
Location: fs/exec.c:1509
Inline: False
Direct callers:
  - fs/exec.c:kernel_execve
```
**Symbols:**

```
ffffffff813faee0-ffffffff813fb1b4: alloc_bprm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct linux_binprm *alloc_bprm(int fd, struct filename *filename);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff814847e0)
Location: fs/exec.c:1508
Inline: False
Direct callers:
  - fs/exec.c:kernel_execve
```
**Symbols:**

```
ffffffff814847e0-ffffffff81484aaa: alloc_bprm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct linux_binprm *alloc_bprm(int fd, struct filename *filename);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff814b93c0)
Location: fs/exec.c:1511
Inline: False
Direct callers:
  - fs/exec.c:kernel_execve
```
**Symbols:**

```
ffffffff814b93c0-ffffffff814b96ae: alloc_bprm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct linux_binprm *alloc_bprm(int fd, struct filename *filename, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff814ebe70)
Location: fs/exec.c:1535
Inline: False
Direct callers:
  - fs/exec.c:kernel_execve
```
**Symbols:**

```
ffffffff814ebe70-ffffffff814ec1e4: alloc_bprm (STB_LOCAL)
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int flags</code>
</li>
</ul>
</details>
</li>
</ul>
