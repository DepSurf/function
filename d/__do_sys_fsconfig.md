# Function: <code>__do_sys_fsconfig</code>

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
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fsopen.c (ffffffff8130b8d1)
Location: fs/fsopen.c:314
Inline: True
Inline callers:
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
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
In fs/fsopen.c (ffffffff8131e8e1)
Location: fs/fsopen.c:314
Inline: True
Inline callers:
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int __do_sys_fsconfig(int fd, unsigned int cmd, const char *_key, const void *_value, int aux);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fsopen.c (ffffffff813586d0)
Location: fs/fsopen.c:314
Inline: False
Direct callers:
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
```
**Symbols:**

```
ffffffff813586d0-ffffffff81358c7a: __do_sys_fsconfig (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int __do_sys_fsconfig(int fd, unsigned int cmd, const char *_key, const void *_value, int aux);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fsopen.c (ffffffff81365050)
Location: fs/fsopen.c:314
Inline: False
Direct callers:
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
```
**Symbols:**

```
ffffffff81365050-ffffffff813655fa: __do_sys_fsconfig (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int __do_sys_fsconfig(int fd, unsigned int cmd, const char *_key, const void *_value, int aux);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fsopen.c (ffffffff8136baa0)
Location: fs/fsopen.c:314
Inline: False
Direct callers:
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
```
**Symbols:**

```
ffffffff8136baa0-ffffffff8136c047: __do_sys_fsconfig (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int __do_sys_fsconfig(int fd, unsigned int cmd, const char *_key, const void *_value, int aux);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fsopen.c (ffffffff813ba770)
Location: fs/fsopen.c:314
Inline: False
Direct callers:
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
```
**Symbols:**

```
ffffffff813ba770-ffffffff813bad17: __do_sys_fsconfig (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int __do_sys_fsconfig(int fd, unsigned int cmd, const char *_key, const void *_value, int aux);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fsopen.c (ffffffff814404a0)
Location: fs/fsopen.c:314
Inline: False
Direct callers:
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
```
**Symbols:**

```
ffffffff814404a0-ffffffff81440ad6: __do_sys_fsconfig (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int __do_sys_fsconfig(int fd, unsigned int cmd, const char *_key, const void *_value, int aux);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fsopen.c (ffffffff814cf370)
Location: fs/fsopen.c:314
Inline: False
Direct callers:
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
```
**Symbols:**

```
ffffffff814cf370-ffffffff814cf9a6: __do_sys_fsconfig (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int __do_sys_fsconfig(int fd, unsigned int cmd, const char *_key, const void *_value, int aux);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fsopen.c (ffffffff815055e0)
Location: fs/fsopen.c:314
Inline: False
Direct callers:
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
```
**Symbols:**

```
ffffffff815055e0-ffffffff81505c69: __do_sys_fsconfig (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int __do_sys_fsconfig(int fd, unsigned int cmd, const char *_key, const void *_value, int aux);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fsopen.c (ffffffff8153a3b0)
Location: fs/fsopen.c:349
Inline: False
Direct callers:
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
```
**Symbols:**

```
ffffffff8153a3b0-ffffffff8153a9d0: __do_sys_fsconfig (STB_LOCAL)
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
In fs/fsopen.c (ffff8000103d6ae8)
Location: fs/fsopen.c:314
Inline: True
Inline callers:
  - fs/fsopen.c:__arm64_sys_fsconfig
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fsopen.c (c05b0af0)
Location: fs/fsopen.c:314
Inline: True
Inline callers:
  - fs/fsopen.c:__se_sys_fsconfig
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fsopen.c (c0000000004daeb8)
Location: fs/fsopen.c:314
Inline: True
Inline callers:
  - fs/fsopen.c:__se_sys_fsconfig
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fsopen.c (ffffffe000290a1a)
Location: fs/fsopen.c:314
Inline: True
Inline callers:
  - fs/fsopen.c:__se_sys_fsconfig
```
</details>
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
In fs/fsopen.c (ffffffff81316ec1)
Location: fs/fsopen.c:314
Inline: True
Inline callers:
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
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
In fs/fsopen.c (ffffffff81307ab1)
Location: fs/fsopen.c:314
Inline: True
Inline callers:
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
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
In fs/fsopen.c (ffffffff81314991)
Location: fs/fsopen.c:314
Inline: True
Inline callers:
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
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
In fs/fsopen.c (ffffffff81326501)
Location: fs/fsopen.c:314
Inline: True
Inline callers:
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
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
