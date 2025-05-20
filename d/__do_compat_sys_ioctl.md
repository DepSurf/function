# Function: <code>__do_compat_sys_ioctl</code>

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
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/compat_ioctl.c (ffffffff81302bb2)
Location: fs/compat_ioctl.c:1405
Inline: True
Inline callers:
  - fs/compat_ioctl.c:__x32_compat_sys_ioctl
  - fs/compat_ioctl.c:__ia32_compat_sys_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/compat_ioctl.c (ffffffff81318242)
Location: fs/compat_ioctl.c:998
Inline: True
Inline callers:
  - fs/compat_ioctl.c:__x32_compat_sys_ioctl
  - fs/compat_ioctl.c:__ia32_compat_sys_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/compat_ioctl.c (ffffffff8133f8f2)
Location: fs/compat_ioctl.c:995
Inline: True
Inline callers:
  - fs/compat_ioctl.c:__x32_compat_sys_ioctl
  - fs/compat_ioctl.c:__ia32_compat_sys_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/compat_ioctl.c (ffffffff81358102)
Location: fs/compat_ioctl.c:995
Inline: True
Inline callers:
  - fs/compat_ioctl.c:__x32_compat_sys_ioctl
  - fs/compat_ioctl.c:__ia32_compat_sys_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int __do_compat_sys_ioctl(unsigned int fd, unsigned int cmd, compat_ulong_t arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff8132bff0)
Location: fs/ioctl.c:798
Inline: False
Direct callers:
  - fs/ioctl.c:__x32_compat_sys_ioctl
  - fs/ioctl.c:__ia32_compat_sys_ioctl
```
**Symbols:**

```
ffffffff8132bff0-ffffffff8132c14f: __do_compat_sys_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int __do_compat_sys_ioctl(unsigned int fd, unsigned int cmd, compat_ulong_t arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff81337670)
Location: fs/ioctl.c:793
Inline: False
Direct callers:
  - fs/ioctl.c:__x32_compat_sys_ioctl
  - fs/ioctl.c:__ia32_compat_sys_ioctl
```
**Symbols:**

```
ffffffff81337670-ffffffff813377cf: __do_compat_sys_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int __do_compat_sys_ioctl(unsigned int fd, unsigned int cmd, compat_ulong_t arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff8133dca0)
Location: fs/ioctl.c:1109
Inline: False
Direct callers:
  - fs/ioctl.c:__x32_compat_sys_ioctl
  - fs/ioctl.c:__ia32_compat_sys_ioctl
```
**Symbols:**

```
ffffffff8133dca0-ffffffff8133de26: __do_compat_sys_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int __do_compat_sys_ioctl(unsigned int fd, unsigned int cmd, compat_ulong_t arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff8138b620)
Location: fs/ioctl.c:914
Inline: False
Direct callers:
  - fs/ioctl.c:__x64_compat_sys_ioctl
  - fs/ioctl.c:__ia32_compat_sys_ioctl
```
**Symbols:**

```
ffffffff8138b620-ffffffff8138b7a6: __do_compat_sys_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int __do_compat_sys_ioctl(unsigned int fd, unsigned int cmd, compat_ulong_t arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff8140c970)
Location: fs/ioctl.c:910
Inline: False
Direct callers:
  - fs/ioctl.c:__ia32_compat_sys_ioctl
```
**Symbols:**

```
ffffffff8140c970-ffffffff8140cb14: __do_compat_sys_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int __do_compat_sys_ioctl(unsigned int fd, unsigned int cmd, compat_ulong_t arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff81497400)
Location: fs/ioctl.c:910
Inline: False
Direct callers:
  - fs/ioctl.c:__ia32_compat_sys_ioctl
```
**Symbols:**

```
ffffffff81497400-ffffffff814975a4: __do_compat_sys_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int __do_compat_sys_ioctl(unsigned int fd, unsigned int cmd, compat_ulong_t arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff814cc460)
Location: fs/ioctl.c:910
Inline: False
Direct callers:
  - fs/ioctl.c:__ia32_compat_sys_ioctl
```
**Symbols:**

```
ffffffff814cc460-ffffffff814cc627: __do_compat_sys_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int __do_compat_sys_ioctl(unsigned int fd, unsigned int cmd, compat_ulong_t arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff814fed20)
Location: fs/ioctl.c:914
Inline: False
Direct callers:
  - fs/ioctl.c:__ia32_compat_sys_ioctl
```
**Symbols:**

```
ffffffff814fed20-ffffffff814feee7: __do_compat_sys_ioctl (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/compat_ioctl.c (ffff80001041d0c8)
Location: fs/compat_ioctl.c:995
Inline: True
Inline callers:
  - fs/compat_ioctl.c:__arm64_compat_sys_ioctl
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/compat_ioctl.c (c00000000052b0e8)
Location: fs/compat_ioctl.c:995
Inline: True
Inline callers:
  - fs/compat_ioctl.c:__se_compat_sys_ioctl
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/compat_ioctl.c (ffffffff813506e2)
Location: fs/compat_ioctl.c:995
Inline: True
Inline callers:
  - fs/compat_ioctl.c:__x32_compat_sys_ioctl
  - fs/compat_ioctl.c:__ia32_compat_sys_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/compat_ioctl.c (ffffffff813413c2)
Location: fs/compat_ioctl.c:995
Inline: True
Inline callers:
  - fs/compat_ioctl.c:__x32_compat_sys_ioctl
  - fs/compat_ioctl.c:__ia32_compat_sys_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/compat_ioctl.c (ffffffff8134e1b2)
Location: fs/compat_ioctl.c:995
Inline: True
Inline callers:
  - fs/compat_ioctl.c:__x32_compat_sys_ioctl
  - fs/compat_ioctl.c:__ia32_compat_sys_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/compat_ioctl.c (ffffffff81361732)
Location: fs/compat_ioctl.c:995
Inline: True
Inline callers:
  - fs/compat_ioctl.c:__x32_compat_sys_ioctl
  - fs/compat_ioctl.c:__ia32_compat_sys_ioctl
```
</details>
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
