# Function: <code>bprm_execve</code>

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
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int bprm_execve(struct linux_binprm *bprm, int fd, struct filename *filename, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/exec.c (ffffffff813287d0)
Location: fs/exec.c:1796
Inline: True
Direct callers:
  - fs/exec.c:kernel_execve
  - fs/exec.c:do_execveat_common
```
**Symbols:**

```
ffffffff813287d0-ffffffff81328918: bprm_execve.part.0 (STB_LOCAL)
ffffffff81328920-ffffffff813289aa: bprm_execve (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int bprm_execve(struct linux_binprm *bprm, int fd, struct filename *filename, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/exec.c (ffffffff8132e620)
Location: fs/exec.c:1796
Inline: True
Direct callers:
  - fs/exec.c:kernel_execve
```
**Symbols:**

```
ffffffff8132e620-ffffffff8132e83c: bprm_execve.part.0 (STB_LOCAL)
ffffffff8132e840-ffffffff8132e8ca: bprm_execve (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int bprm_execve(struct linux_binprm *bprm, int fd, struct filename *filename, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/exec.c (ffffffff8137be30)
Location: fs/exec.c:1798
Inline: True
Direct callers:
  - fs/exec.c:kernel_execve
```
**Symbols:**

```
ffffffff8137be30-ffffffff8137c04c: bprm_execve.part.0 (STB_LOCAL)
ffffffff8137c050-ffffffff8137c0da: bprm_execve (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int bprm_execve(struct linux_binprm *bprm, int fd, struct filename *filename, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/exec.c (ffffffff813fc290)
Location: fs/exec.c:1803
Inline: True
Direct callers:
  - fs/exec.c:kernel_execve
```
**Symbols:**

```
ffffffff813fc290-ffffffff813fc4a5: bprm_execve.part.0 (STB_LOCAL)
ffffffff813fc4b0-ffffffff813fc545: bprm_execve (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
int bprm_execve(struct linux_binprm *bprm, int fd, struct filename *filename, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/exec.c (ffffffff81485d20)
Location: fs/exec.c:1808
Inline: True
Direct callers:
  - fs/exec.c:kernel_execve
```
**Symbols:**

```
ffffffff81485d20-ffffffff81485f35: bprm_execve.part.0 (STB_LOCAL)
ffffffff81485f50-ffffffff81485fe5: bprm_execve (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
int bprm_execve(struct linux_binprm *bprm, int fd, struct filename *filename, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/exec.c (ffffffff814b9980)
Location: fs/exec.c:1811
Inline: True
Direct callers:
  - fs/exec.c:kernel_execve
```
**Symbols:**

```
ffffffff814b9980-ffffffff814b9bcb: bprm_execve.part.0 (STB_LOCAL)
ffffffff814b9be0-ffffffff814b9c75: bprm_execve (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int bprm_execve(struct linux_binprm *bprm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/exec.c (ffffffff814eb040)
Location: fs/exec.c:1853
Inline: True
Direct callers:
  - fs/exec.c:kernel_execve
```
**Symbols:**

```
ffffffff814eb040-ffffffff814eb278: bprm_execve.part.0 (STB_LOCAL)
ffffffff814eb290-ffffffff814eb303: bprm_execve (STB_LOCAL)
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
<b>Param removed. </b>
<code>int fd</code>
</li>
<li>
<b>Param removed. </b>
<code>struct filename *filename</code>
</li>
<li>
<b>Param removed. </b>
<code>int flags</code>
</li>
</ul>
</details>
</li>
</ul>
