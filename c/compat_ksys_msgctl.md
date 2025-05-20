# Function: <code>compat_ksys_msgctl</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long int compat_ksys_msgctl(int msqid, int cmd, void *uptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff813d8f40)
Location: ipc/msg.c:682
Inline: False
Direct callers:
  - ipc/msg.c:__x32_compat_sys_msgctl
  - ipc/msg.c:__ia32_compat_sys_msgctl
  - ipc/syscall.c:__x32_compat_sys_ipc
  - ipc/syscall.c:__ia32_compat_sys_ipc
```
**Symbols:**

```
ffffffff813d8f40-ffffffff813d9111: compat_ksys_msgctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int compat_ksys_msgctl(int msqid, int cmd, void *uptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff813f3580)
Location: ipc/msg.c:692
Inline: False
Direct callers:
  - ipc/msg.c:__x32_compat_sys_msgctl
  - ipc/msg.c:__ia32_compat_sys_msgctl
  - ipc/syscall.c:__x32_compat_sys_ipc
  - ipc/syscall.c:__ia32_compat_sys_ipc
```
**Symbols:**

```
ffffffff813f3580-ffffffff813f3753: compat_ksys_msgctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int compat_ksys_msgctl(int msqid, int cmd, void *uptr, int version);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff8141f040)
Location: ipc/msg.c:704
Inline: False
Direct callers:
  - ipc/msg.c:__x32_compat_sys_old_msgctl
  - ipc/msg.c:__ia32_compat_sys_old_msgctl
  - ipc/msg.c:__x32_compat_sys_msgctl
  - ipc/msg.c:__ia32_compat_sys_msgctl
```
**Symbols:**

```
ffffffff8141f040-ffffffff8141f226: compat_ksys_msgctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int compat_ksys_msgctl(int msqid, int cmd, void *uptr, int version);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff81438e80)
Location: ipc/msg.c:705
Inline: False
Direct callers:
  - ipc/msg.c:__x32_compat_sys_old_msgctl
  - ipc/msg.c:__ia32_compat_sys_old_msgctl
  - ipc/msg.c:__x32_compat_sys_msgctl
  - ipc/msg.c:__ia32_compat_sys_msgctl
```
**Symbols:**

```
ffffffff81438e80-ffffffff8143904a: compat_ksys_msgctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int compat_ksys_msgctl(int msqid, int cmd, void *uptr, int version);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff81488f40)
Location: ipc/msg.c:724
Inline: False
Direct callers:
  - ipc/msg.c:__x32_compat_sys_old_msgctl
  - ipc/msg.c:__ia32_compat_sys_old_msgctl
  - ipc/msg.c:__x32_compat_sys_msgctl
  - ipc/msg.c:__ia32_compat_sys_msgctl
```
**Symbols:**

```
ffffffff81488f40-ffffffff81489103: compat_ksys_msgctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int compat_ksys_msgctl(int msqid, int cmd, void *uptr, int version);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff814a6560)
Location: ipc/msg.c:724
Inline: False
Direct callers:
  - ipc/msg.c:__x32_compat_sys_old_msgctl
  - ipc/msg.c:__ia32_compat_sys_old_msgctl
  - ipc/msg.c:__x32_compat_sys_msgctl
  - ipc/msg.c:__ia32_compat_sys_msgctl
```
**Symbols:**

```
ffffffff814a6560-ffffffff814a6723: compat_ksys_msgctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int compat_ksys_msgctl(int msqid, int cmd, void *uptr, int version);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff814ac4f0)
Location: ipc/msg.c:726
Inline: False
Direct callers:
  - ipc/msg.c:__x32_compat_sys_old_msgctl
  - ipc/msg.c:__ia32_compat_sys_old_msgctl
  - ipc/msg.c:__x32_compat_sys_msgctl
  - ipc/msg.c:__ia32_compat_sys_msgctl
```
**Symbols:**

```
ffffffff814ac4f0-ffffffff814ac6ad: compat_ksys_msgctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int compat_ksys_msgctl(int msqid, int cmd, void *uptr, int version);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff815049d0)
Location: ipc/msg.c:726
Inline: False
Direct callers:
  - ipc/msg.c:__x64_compat_sys_old_msgctl
  - ipc/msg.c:__ia32_compat_sys_old_msgctl
  - ipc/msg.c:__x64_compat_sys_msgctl
  - ipc/msg.c:__ia32_compat_sys_msgctl
```
**Symbols:**

```
ffffffff815049d0-ffffffff81504b8d: compat_ksys_msgctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int compat_ksys_msgctl(int msqid, int cmd, void *uptr, int version);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff81595b40)
Location: ipc/msg.c:726
Inline: False
Direct callers:
  - ipc/msg.c:__ia32_compat_sys_old_msgctl
  - ipc/msg.c:__ia32_compat_sys_msgctl
```
**Symbols:**

```
ffffffff81595b40-ffffffff81595d3c: compat_ksys_msgctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int compat_ksys_msgctl(int msqid, int cmd, void *uptr, int version);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff8163e960)
Location: ipc/msg.c:732
Inline: False
Direct callers:
  - ipc/msg.c:__ia32_compat_sys_old_msgctl
  - ipc/msg.c:__ia32_compat_sys_msgctl
```
**Symbols:**

```
ffffffff8163e960-ffffffff8163eb5c: compat_ksys_msgctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int compat_ksys_msgctl(int msqid, int cmd, void *uptr, int version);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff81676e50)
Location: ipc/msg.c:732
Inline: False
Direct callers:
  - ipc/msg.c:__ia32_compat_sys_old_msgctl
  - ipc/msg.c:__ia32_compat_sys_msgctl
```
**Symbols:**

```
ffffffff81676e50-ffffffff81677073: compat_ksys_msgctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int compat_ksys_msgctl(int msqid, int cmd, void *uptr, int version);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff816b3210)
Location: ipc/msg.c:732
Inline: False
Direct callers:
  - ipc/msg.c:__ia32_compat_sys_old_msgctl
  - ipc/msg.c:__ia32_compat_sys_msgctl
```
**Symbols:**

```
ffffffff816b3210-ffffffff816b3433: compat_ksys_msgctl (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
long int compat_ksys_msgctl(int msqid, int cmd, void *uptr, int version);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffff800010520640)
Location: ipc/msg.c:705
Inline: False
Direct callers:
  - ipc/msg.c:__arm64_compat_sys_old_msgctl
  - ipc/msg.c:__arm64_compat_sys_msgctl
```
**Symbols:**

```
ffff800010520640-ffff800010520a70: compat_ksys_msgctl (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int compat_ksys_msgctl(int msqid, int cmd, void *uptr, int version);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (c000000000669810)
Location: ipc/msg.c:705
Inline: False
Direct callers:
  - ipc/msg.c:__se_compat_sys_old_msgctl
  - ipc/msg.c:__se_compat_sys_msgctl
```
**Symbols:**

```
c000000000669810-c000000000669b98: compat_ksys_msgctl (STB_LOCAL)
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
long int compat_ksys_msgctl(int msqid, int cmd, void *uptr, int version);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff81431460)
Location: ipc/msg.c:705
Inline: False
Direct callers:
  - ipc/msg.c:__x32_compat_sys_old_msgctl
  - ipc/msg.c:__ia32_compat_sys_old_msgctl
  - ipc/msg.c:__x32_compat_sys_msgctl
  - ipc/msg.c:__ia32_compat_sys_msgctl
```
**Symbols:**

```
ffffffff81431460-ffffffff8143162a: compat_ksys_msgctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int compat_ksys_msgctl(int msqid, int cmd, void *uptr, int version);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff81421ee0)
Location: ipc/msg.c:705
Inline: False
Direct callers:
  - ipc/msg.c:__x32_compat_sys_old_msgctl
  - ipc/msg.c:__ia32_compat_sys_old_msgctl
  - ipc/msg.c:__x32_compat_sys_msgctl
  - ipc/msg.c:__ia32_compat_sys_msgctl
```
**Symbols:**

```
ffffffff81421ee0-ffffffff814220aa: compat_ksys_msgctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int compat_ksys_msgctl(int msqid, int cmd, void *uptr, int version);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff8142d600)
Location: ipc/msg.c:705
Inline: False
Direct callers:
  - ipc/msg.c:__x32_compat_sys_old_msgctl
  - ipc/msg.c:__ia32_compat_sys_old_msgctl
  - ipc/msg.c:__x32_compat_sys_msgctl
  - ipc/msg.c:__ia32_compat_sys_msgctl
```
**Symbols:**

```
ffffffff8142d600-ffffffff8142d7ca: compat_ksys_msgctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int compat_ksys_msgctl(int msqid, int cmd, void *uptr, int version);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff81444030)
Location: ipc/msg.c:705
Inline: False
Direct callers:
  - ipc/msg.c:__x32_compat_sys_old_msgctl
  - ipc/msg.c:__ia32_compat_sys_old_msgctl
  - ipc/msg.c:__x32_compat_sys_msgctl
  - ipc/msg.c:__ia32_compat_sys_msgctl
```
**Symbols:**

```
ffffffff81444030-ffffffff814441fa: compat_ksys_msgctl (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int version</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
