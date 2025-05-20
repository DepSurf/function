# Function: <code>__do_sys_prlimit64</code>

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
In kernel/sys.c (ffffffff810a7918)
Location: kernel/sys.c:1630
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_prlimit64
  - kernel/sys.c:__x64_sys_prlimit64
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
In kernel/sys.c (ffffffff810b0628)
Location: kernel/sys.c:1631
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_prlimit64
  - kernel/sys.c:__x64_sys_prlimit64
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
In kernel/sys.c (ffffffff810b600e)
Location: kernel/sys.c:1631
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_prlimit64
  - kernel/sys.c:__x64_sys_prlimit64
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
In kernel/sys.c (ffffffff810bc5ce)
Location: kernel/sys.c:1621
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_prlimit64
  - kernel/sys.c:__x64_sys_prlimit64
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int __do_sys_prlimit64(pid_t pid, unsigned int resource, const struct rlimit64 *new_rlim, struct rlimit64 *old_rlim);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810c3f30)
Location: kernel/sys.c:1637
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_prlimit64
  - kernel/sys.c:__x64_sys_prlimit64
```
**Symbols:**

```
ffffffff810c3f30-ffffffff810c412f: __do_sys_prlimit64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int __do_sys_prlimit64(pid_t pid, unsigned int resource, const struct rlimit64 *new_rlim, struct rlimit64 *old_rlim);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810bf320)
Location: kernel/sys.c:1638
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_prlimit64
  - kernel/sys.c:__x64_sys_prlimit64
```
**Symbols:**

```
ffffffff810bf320-ffffffff810bf52d: __do_sys_prlimit64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int __do_sys_prlimit64(pid_t pid, unsigned int resource, const struct rlimit64 *new_rlim, struct rlimit64 *old_rlim);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810c0cb0)
Location: kernel/sys.c:1655
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_prlimit64
  - kernel/sys.c:__x64_sys_prlimit64
```
**Symbols:**

```
ffffffff810c0cb0-ffffffff810c0f57: __do_sys_prlimit64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int __do_sys_prlimit64(pid_t pid, unsigned int resource, const struct rlimit64 *new_rlim, struct rlimit64 *old_rlim);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810d37a0)
Location: kernel/sys.c:1664
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_prlimit64
  - kernel/sys.c:__x64_sys_prlimit64
```
**Symbols:**

```
ffffffff810d37a0-ffffffff810d3a47: __do_sys_prlimit64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int __do_sys_prlimit64(pid_t pid, unsigned int resource, const struct rlimit64 *new_rlim, struct rlimit64 *old_rlim);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810e98e0)
Location: kernel/sys.c:1676
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_prlimit64
  - kernel/sys.c:__x64_sys_prlimit64
```
**Symbols:**

```
ffffffff810e98e0-ffffffff810e9bd6: __do_sys_prlimit64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int __do_sys_prlimit64(pid_t pid, unsigned int resource, const struct rlimit64 *new_rlim, struct rlimit64 *old_rlim);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff8110b580)
Location: kernel/sys.c:1681
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_prlimit64
  - kernel/sys.c:__x64_sys_prlimit64
```
**Symbols:**

```
ffffffff8110b580-ffffffff8110b876: __do_sys_prlimit64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int __do_sys_prlimit64(pid_t pid, unsigned int resource, const struct rlimit64 *new_rlim, struct rlimit64 *old_rlim);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff81117910)
Location: kernel/sys.c:1699
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_prlimit64
  - kernel/sys.c:__x64_sys_prlimit64
```
**Symbols:**

```
ffffffff81117910-ffffffff81117c06: __do_sys_prlimit64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int __do_sys_prlimit64(pid_t pid, unsigned int resource, const struct rlimit64 *new_rlim, struct rlimit64 *old_rlim);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff81121300)
Location: kernel/sys.c:1699
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_prlimit64
  - kernel/sys.c:__x64_sys_prlimit64
```
**Symbols:**

```
ffffffff81121300-ffffffff811215f6: __do_sys_prlimit64 (STB_LOCAL)
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
In kernel/sys.c (ffff800010119370)
Location: kernel/sys.c:1621
Inline: True
Inline callers:
  - kernel/sys.c:__arm64_sys_prlimit64
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
In kernel/sys.c (c036da30)
Location: kernel/sys.c:1621
Inline: True
Inline callers:
  - kernel/sys.c:__se_sys_prlimit64
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
In kernel/sys.c (c000000000160d70)
Location: kernel/sys.c:1621
Inline: True
Inline callers:
  - kernel/sys.c:__se_sys_prlimit64
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
In kernel/sys.c (ffffffe0000d4430)
Location: kernel/sys.c:1621
Inline: True
Inline callers:
  - kernel/sys.c:__se_sys_prlimit64
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
In kernel/sys.c (ffffffff810b693e)
Location: kernel/sys.c:1621
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_prlimit64
  - kernel/sys.c:__x64_sys_prlimit64
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
In kernel/sys.c (ffffffff810a527e)
Location: kernel/sys.c:1621
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_prlimit64
  - kernel/sys.c:__x64_sys_prlimit64
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
In kernel/sys.c (ffffffff810b5e9e)
Location: kernel/sys.c:1621
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_prlimit64
  - kernel/sys.c:__x64_sys_prlimit64
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
In kernel/sys.c (ffffffff810be1f8)
Location: kernel/sys.c:1621
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_prlimit64
  - kernel/sys.c:__x64_sys_prlimit64
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
