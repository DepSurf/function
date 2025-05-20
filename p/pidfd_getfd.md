# Function: <code>pidfd_getfd</code>

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
<summary>In <code>5.8</code>: ✅</summary>

```c
int pidfd_getfd(struct pid *pid, int fd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810cd8a0)
Location: kernel/pid.c:624
Inline: False
Direct callers:
  - kernel/pid.c:__ia32_sys_pidfd_getfd
  - kernel/pid.c:__x64_sys_pidfd_getfd
```
**Symbols:**

```
ffffffff810cd8a0-ffffffff810cda91: pidfd_getfd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pidfd_getfd(struct pid *pid, int fd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810c83c0)
Location: kernel/pid.c:645
Inline: False
Direct callers:
  - kernel/pid.c:__ia32_sys_pidfd_getfd
  - kernel/pid.c:__x64_sys_pidfd_getfd
```
**Symbols:**

```
ffffffff810c83c0-ffffffff810c8572: pidfd_getfd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pidfd_getfd(struct pid *pid, int fd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810c9e70)
Location: kernel/pid.c:645
Inline: False
Direct callers:
  - kernel/pid.c:__ia32_sys_pidfd_getfd
  - kernel/pid.c:__x64_sys_pidfd_getfd
```
**Symbols:**

```
ffffffff810c9e70-ffffffff810ca019: pidfd_getfd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pidfd_getfd(struct pid *pid, int fd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810dcc60)
Location: kernel/pid.c:650
Inline: False
Direct callers:
  - kernel/pid.c:__ia32_sys_pidfd_getfd
  - kernel/pid.c:__x64_sys_pidfd_getfd
```
**Symbols:**

```
ffffffff810dcc60-ffffffff810dce07: pidfd_getfd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pidfd_getfd(struct pid *pid, int fd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810f64d0)
Location: kernel/pid.c:686
Inline: False
Direct callers:
  - kernel/pid.c:__ia32_sys_pidfd_getfd
  - kernel/pid.c:__x64_sys_pidfd_getfd
```
**Symbols:**

```
ffffffff810f64d0-ffffffff810f6699: pidfd_getfd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pidfd_getfd(struct pid *pid, int fd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff81118b60)
Location: kernel/pid.c:687
Inline: False
Direct callers:
  - kernel/pid.c:__ia32_sys_pidfd_getfd
  - kernel/pid.c:__x64_sys_pidfd_getfd
```
**Symbols:**

```
ffffffff81118b60-ffffffff81118d29: pidfd_getfd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pidfd_getfd(struct pid *pid, int fd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff81126020)
Location: kernel/pid.c:688
Inline: False
Direct callers:
  - kernel/pid.c:__ia32_sys_pidfd_getfd
  - kernel/pid.c:__x64_sys_pidfd_getfd
```
**Symbols:**

```
ffffffff81126020-ffffffff811261e9: pidfd_getfd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pidfd_getfd(struct pid *pid, int fd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff81130620)
Location: kernel/pid.c:688
Inline: False
Direct callers:
  - kernel/pid.c:__ia32_sys_pidfd_getfd
  - kernel/pid.c:__x64_sys_pidfd_getfd
```
**Symbols:**

```
ffffffff81130620-ffffffff811307eb: pidfd_getfd (STB_LOCAL)
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
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
