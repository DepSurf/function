# Function: <code>__do_sys_setns</code>

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
In kernel/nsproxy.c (ffffffff810b46c6)
Location: kernel/nsproxy.c:237
Inline: True
Inline callers:
  - kernel/nsproxy.c:__ia32_sys_setns
  - kernel/nsproxy.c:__x64_sys_setns
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
In kernel/nsproxy.c (ffffffff810bd816)
Location: kernel/nsproxy.c:237
Inline: True
Inline callers:
  - kernel/nsproxy.c:__ia32_sys_setns
  - kernel/nsproxy.c:__x64_sys_setns
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
In kernel/nsproxy.c (ffffffff810c3866)
Location: kernel/nsproxy.c:233
Inline: True
Inline callers:
  - kernel/nsproxy.c:__ia32_sys_setns
  - kernel/nsproxy.c:__x64_sys_setns
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
In kernel/nsproxy.c (ffffffff810cc976)
Location: kernel/nsproxy.c:233
Inline: True
Inline callers:
  - kernel/nsproxy.c:__ia32_sys_setns
  - kernel/nsproxy.c:__x64_sys_setns
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int __do_sys_setns(int fd, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (ffffffff810d6430)
Location: kernel/nsproxy.c:515
Inline: False
Direct callers:
  - kernel/nsproxy.c:__ia32_sys_setns
  - kernel/nsproxy.c:__x64_sys_setns
```
**Symbols:**

```
ffffffff810d6430-ffffffff810d66bd: __do_sys_setns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int __do_sys_setns(int fd, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (ffffffff810d0fd0)
Location: kernel/nsproxy.c:527
Inline: False
Direct callers:
  - kernel/nsproxy.c:__ia32_sys_setns
  - kernel/nsproxy.c:__x64_sys_setns
```
**Symbols:**

```
ffffffff810d0fd0-ffffffff810d1287: __do_sys_setns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int __do_sys_setns(int fd, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (ffffffff810d2bb0)
Location: kernel/nsproxy.c:527
Inline: False
Direct callers:
  - kernel/nsproxy.c:__ia32_sys_setns
  - kernel/nsproxy.c:__x64_sys_setns
```
**Symbols:**

```
ffffffff810d2bb0-ffffffff810d2e67: __do_sys_setns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int __do_sys_setns(int fd, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (ffffffff810e5cf0)
Location: kernel/nsproxy.c:527
Inline: False
Direct callers:
  - kernel/nsproxy.c:__ia32_sys_setns
  - kernel/nsproxy.c:__x64_sys_setns
```
**Symbols:**

```
ffffffff810e5cf0-ffffffff810e5fa7: __do_sys_setns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int __do_sys_setns(int fd, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (ffffffff810ffb50)
Location: kernel/nsproxy.c:527
Inline: False
Direct callers:
  - kernel/nsproxy.c:__ia32_sys_setns
  - kernel/nsproxy.c:__x64_sys_setns
```
**Symbols:**

```
ffffffff810ffb50-ffffffff810ffe12: __do_sys_setns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int __do_sys_setns(int fd, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (ffffffff811248c0)
Location: kernel/nsproxy.c:546
Inline: False
Direct callers:
  - kernel/nsproxy.c:__ia32_sys_setns
  - kernel/nsproxy.c:__x64_sys_setns
```
**Symbols:**

```
ffffffff811248c0-ffffffff81124b82: __do_sys_setns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int __do_sys_setns(int fd, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (ffffffff81131bc0)
Location: kernel/nsproxy.c:546
Inline: False
Direct callers:
  - kernel/nsproxy.c:__ia32_sys_setns
  - kernel/nsproxy.c:__x64_sys_setns
```
**Symbols:**

```
ffffffff81131bc0-ffffffff81131ecd: __do_sys_setns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int __do_sys_setns(int fd, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/nsproxy.c (ffffffff8113c9f0)
Location: kernel/nsproxy.c:546
Inline: False
Direct callers:
  - kernel/nsproxy.c:__ia32_sys_setns
  - kernel/nsproxy.c:__x64_sys_setns
```
**Symbols:**

```
ffffffff8113c9f0-ffffffff8113ccfd: __do_sys_setns (STB_LOCAL)
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
In kernel/nsproxy.c (ffff80001012b750)
Location: kernel/nsproxy.c:233
Inline: True
Inline callers:
  - kernel/nsproxy.c:__arm64_sys_setns
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
In kernel/nsproxy.c (c037bcac)
Location: kernel/nsproxy.c:233
Inline: True
Inline callers:
  - kernel/nsproxy.c:__se_sys_setns
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
In kernel/nsproxy.c (c000000000174308)
Location: kernel/nsproxy.c:233
Inline: True
Inline callers:
  - kernel/nsproxy.c:__se_sys_setns
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
In kernel/nsproxy.c (ffffffe0000e053e)
Location: kernel/nsproxy.c:233
Inline: True
Inline callers:
  - kernel/nsproxy.c:__se_sys_setns
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
In kernel/nsproxy.c (ffffffff810c6cf6)
Location: kernel/nsproxy.c:233
Inline: True
Inline callers:
  - kernel/nsproxy.c:__ia32_sys_setns
  - kernel/nsproxy.c:__x64_sys_setns
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
In kernel/nsproxy.c (ffffffff810b5516)
Location: kernel/nsproxy.c:233
Inline: True
Inline callers:
  - kernel/nsproxy.c:__ia32_sys_setns
  - kernel/nsproxy.c:__x64_sys_setns
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
In kernel/nsproxy.c (ffffffff810c6246)
Location: kernel/nsproxy.c:233
Inline: True
Inline callers:
  - kernel/nsproxy.c:__ia32_sys_setns
  - kernel/nsproxy.c:__x64_sys_setns
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
In kernel/nsproxy.c (ffffffff810ce696)
Location: kernel/nsproxy.c:233
Inline: True
Inline callers:
  - kernel/nsproxy.c:__ia32_sys_setns
  - kernel/nsproxy.c:__x64_sys_setns
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
