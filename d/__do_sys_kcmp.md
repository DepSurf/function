# Function: <code>__do_sys_kcmp</code>

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
In kernel/kcmp.c (ffffffff8110eac2)
Location: kernel/kcmp.c:152
Inline: True
Inline callers:
  - kernel/kcmp.c:__ia32_sys_kcmp
  - kernel/kcmp.c:__x64_sys_kcmp
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
In kernel/kcmp.c (ffffffff8111a042)
Location: kernel/kcmp.c:152
Inline: True
Inline callers:
  - kernel/kcmp.c:__ia32_sys_kcmp
  - kernel/kcmp.c:__x64_sys_kcmp
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int __do_sys_kcmp(pid_t pid1, pid_t pid2, int type, long unsigned int idx1, long unsigned int idx2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kcmp.c (ffffffff81124910)
Location: kernel/kcmp.c:152
Inline: False
Direct callers:
  - kernel/kcmp.c:__ia32_sys_kcmp
  - kernel/kcmp.c:__x64_sys_kcmp
```
**Symbols:**

```
ffffffff81124910-ffffffff81124db9: __do_sys_kcmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int __do_sys_kcmp(pid_t pid1, pid_t pid2, int type, long unsigned int idx1, long unsigned int idx2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kcmp.c (ffffffff811308d0)
Location: kernel/kcmp.c:152
Inline: False
Direct callers:
  - kernel/kcmp.c:__ia32_sys_kcmp
  - kernel/kcmp.c:__x64_sys_kcmp
```
**Symbols:**

```
ffffffff811308d0-ffffffff81130d79: __do_sys_kcmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int __do_sys_kcmp(pid_t pid1, pid_t pid2, int type, long unsigned int idx1, long unsigned int idx2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kcmp.c (ffffffff8113fcf0)
Location: kernel/kcmp.c:152
Inline: False
Direct callers:
  - kernel/kcmp.c:__ia32_sys_kcmp
  - kernel/kcmp.c:__x64_sys_kcmp
```
**Symbols:**

```
ffffffff8113fcf0-ffffffff8114012f: __do_sys_kcmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int __do_sys_kcmp(pid_t pid1, pid_t pid2, int type, long unsigned int idx1, long unsigned int idx2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kcmp.c (ffffffff8113c030)
Location: kernel/kcmp.c:135
Inline: False
Direct callers:
  - kernel/kcmp.c:__ia32_sys_kcmp
  - kernel/kcmp.c:__x64_sys_kcmp
```
**Symbols:**

```
ffffffff8113c030-ffffffff8113c495: __do_sys_kcmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int __do_sys_kcmp(pid_t pid1, pid_t pid2, int type, long unsigned int idx1, long unsigned int idx2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kcmp.c (ffffffff8113d1d0)
Location: kernel/kcmp.c:135
Inline: False
Direct callers:
  - kernel/kcmp.c:__ia32_sys_kcmp
  - kernel/kcmp.c:__x64_sys_kcmp
```
**Symbols:**

```
ffffffff8113d1d0-ffffffff8113d703: __do_sys_kcmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int __do_sys_kcmp(pid_t pid1, pid_t pid2, int type, long unsigned int idx1, long unsigned int idx2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kcmp.c (ffffffff81160350)
Location: kernel/kcmp.c:135
Inline: False
Direct callers:
  - kernel/kcmp.c:__ia32_sys_kcmp
  - kernel/kcmp.c:__x64_sys_kcmp
```
**Symbols:**

```
ffffffff81160350-ffffffff81160883: __do_sys_kcmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int __do_sys_kcmp(pid_t pid1, pid_t pid2, int type, long unsigned int idx1, long unsigned int idx2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kcmp.c (ffffffff811930a0)
Location: kernel/kcmp.c:135
Inline: False
Direct callers:
  - kernel/kcmp.c:__ia32_sys_kcmp
  - kernel/kcmp.c:__x64_sys_kcmp
```
**Symbols:**

```
ffffffff811930a0-ffffffff811935e1: __do_sys_kcmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int __do_sys_kcmp(pid_t pid1, pid_t pid2, int type, long unsigned int idx1, long unsigned int idx2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kcmp.c (ffffffff811d08e0)
Location: kernel/kcmp.c:135
Inline: False
Direct callers:
  - kernel/kcmp.c:__ia32_sys_kcmp
  - kernel/kcmp.c:__x64_sys_kcmp
```
**Symbols:**

```
ffffffff811d08e0-ffffffff811d0e21: __do_sys_kcmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int __do_sys_kcmp(pid_t pid1, pid_t pid2, int type, long unsigned int idx1, long unsigned int idx2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kcmp.c (ffffffff811e4b60)
Location: kernel/kcmp.c:135
Inline: False
Direct callers:
  - kernel/kcmp.c:__ia32_sys_kcmp
  - kernel/kcmp.c:__x64_sys_kcmp
```
**Symbols:**

```
ffffffff811e4b60-ffffffff811e509a: __do_sys_kcmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int __do_sys_kcmp(pid_t pid1, pid_t pid2, int type, long unsigned int idx1, long unsigned int idx2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kcmp.c (ffffffff811fa8b0)
Location: kernel/kcmp.c:137
Inline: False
Direct callers:
  - kernel/kcmp.c:__ia32_sys_kcmp
  - kernel/kcmp.c:__x64_sys_kcmp
```
**Symbols:**

```
ffffffff811fa8b0-ffffffff811fae44: __do_sys_kcmp (STB_LOCAL)
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
In kernel/kcmp.c (ffff800010197c50)
Location: kernel/kcmp.c:152
Inline: True
Inline callers:
  - kernel/kcmp.c:__arm64_sys_kcmp
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
In kernel/kcmp.c (c03e2ba0)
Location: kernel/kcmp.c:152
Inline: True
Inline callers:
  - kernel/kcmp.c:__se_sys_kcmp
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
In kernel/kcmp.c (c0000000001f7858)
Location: kernel/kcmp.c:152
Inline: True
Inline callers:
  - kernel/kcmp.c:__se_sys_kcmp
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
In kernel/kcmp.c (ffffffe0001289f6)
Location: kernel/kcmp.c:152
Inline: True
Inline callers:
  - kernel/kcmp.c:__se_sys_kcmp
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
long int __do_sys_kcmp(pid_t pid1, pid_t pid2, int type, long unsigned int idx1, long unsigned int idx2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kcmp.c (ffffffff81129080)
Location: kernel/kcmp.c:152
Inline: False
Direct callers:
  - kernel/kcmp.c:__ia32_sys_kcmp
  - kernel/kcmp.c:__x64_sys_kcmp
```
**Symbols:**

```
ffffffff81129080-ffffffff81129529: __do_sys_kcmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int __do_sys_kcmp(pid_t pid1, pid_t pid2, int type, long unsigned int idx1, long unsigned int idx2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kcmp.c (ffffffff8111b910)
Location: kernel/kcmp.c:152
Inline: False
Direct callers:
  - kernel/kcmp.c:__ia32_sys_kcmp
  - kernel/kcmp.c:__x64_sys_kcmp
```
**Symbols:**

```
ffffffff8111b910-ffffffff8111bdb9: __do_sys_kcmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int __do_sys_kcmp(pid_t pid1, pid_t pid2, int type, long unsigned int idx1, long unsigned int idx2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kcmp.c (ffffffff81126da0)
Location: kernel/kcmp.c:152
Inline: False
Direct callers:
  - kernel/kcmp.c:__ia32_sys_kcmp
  - kernel/kcmp.c:__x64_sys_kcmp
```
**Symbols:**

```
ffffffff81126da0-ffffffff81127249: __do_sys_kcmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int __do_sys_kcmp(pid_t pid1, pid_t pid2, int type, long unsigned int idx1, long unsigned int idx2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kcmp.c (ffffffff811333f0)
Location: kernel/kcmp.c:152
Inline: False
Direct callers:
  - kernel/kcmp.c:__ia32_sys_kcmp
  - kernel/kcmp.c:__x64_sys_kcmp
```
**Symbols:**

```
ffffffff811333f0-ffffffff811338a1: __do_sys_kcmp (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
