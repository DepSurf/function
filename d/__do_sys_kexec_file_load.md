# Function: <code>__do_sys_kexec_file_load</code>

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
In kernel/kexec_file.c (ffffffff81139992)
Location: kernel/kexec_file.c:320
Inline: True
Inline callers:
  - kernel/kexec_file.c:__ia32_sys_kexec_file_load
  - kernel/kexec_file.c:__x64_sys_kexec_file_load
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
In kernel/kexec_file.c (ffffffff81145262)
Location: kernel/kexec_file.c:319
Inline: True
Inline callers:
  - kernel/kexec_file.c:__ia32_sys_kexec_file_load
  - kernel/kexec_file.c:__x64_sys_kexec_file_load
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
In kernel/kexec_file.c (ffffffff81150652)
Location: kernel/kexec_file.c:365
Inline: True
Inline callers:
  - kernel/kexec_file.c:__ia32_sys_kexec_file_load
  - kernel/kexec_file.c:__x64_sys_kexec_file_load
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
In kernel/kexec_file.c (ffffffff8115c2e2)
Location: kernel/kexec_file.c:370
Inline: True
Inline callers:
  - kernel/kexec_file.c:__ia32_sys_kexec_file_load
  - kernel/kexec_file.c:__x64_sys_kexec_file_load
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int __do_sys_kexec_file_load(int kernel_fd, int initrd_fd, long unsigned int cmdline_len, const char *cmdline_ptr, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff8116d200)
Location: kernel/kexec_file.c:348
Inline: False
Direct callers:
  - kernel/kexec_file.c:__ia32_sys_kexec_file_load
  - kernel/kexec_file.c:__x64_sys_kexec_file_load
```
**Symbols:**

```
ffffffff8116d200-ffffffff8116d48e: __do_sys_kexec_file_load (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int __do_sys_kexec_file_load(int kernel_fd, int initrd_fd, long unsigned int cmdline_len, const char *cmdline_ptr, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff81169880)
Location: kernel/kexec_file.c:354
Inline: False
Direct callers:
  - kernel/kexec_file.c:__ia32_sys_kexec_file_load
  - kernel/kexec_file.c:__x64_sys_kexec_file_load
```
**Symbols:**

```
ffffffff81169880-ffffffff81169b0e: __do_sys_kexec_file_load (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int __do_sys_kexec_file_load(int kernel_fd, int initrd_fd, long unsigned int cmdline_len, const char *cmdline_ptr, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff8116a580)
Location: kernel/kexec_file.c:354
Inline: False
Direct callers:
  - kernel/kexec_file.c:__ia32_sys_kexec_file_load
  - kernel/kexec_file.c:__x64_sys_kexec_file_load
```
**Symbols:**

```
ffffffff8116a580-ffffffff8116a80a: __do_sys_kexec_file_load (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int __do_sys_kexec_file_load(int kernel_fd, int initrd_fd, long unsigned int cmdline_len, const char *cmdline_ptr, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff81190170)
Location: kernel/kexec_file.c:354
Inline: False
Direct callers:
  - kernel/kexec_file.c:__ia32_sys_kexec_file_load
  - kernel/kexec_file.c:__x64_sys_kexec_file_load
```
**Symbols:**

```
ffffffff81190170-ffffffff8119043a: __do_sys_kexec_file_load (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int __do_sys_kexec_file_load(int kernel_fd, int initrd_fd, long unsigned int cmdline_len, const char *cmdline_ptr, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff811bf9b0)
Location: kernel/kexec_file.c:321
Inline: False
Direct callers:
  - kernel/kexec_file.c:__ia32_sys_kexec_file_load
  - kernel/kexec_file.c:__x64_sys_kexec_file_load
```
**Symbols:**

```
ffffffff811bf9b0-ffffffff811bfc91: __do_sys_kexec_file_load (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int __do_sys_kexec_file_load(int kernel_fd, int initrd_fd, long unsigned int cmdline_len, const char *cmdline_ptr, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff81201ce0)
Location: kernel/kexec_file.c:325
Inline: False
Direct callers:
  - kernel/kexec_file.c:__ia32_sys_kexec_file_load
  - kernel/kexec_file.c:__x64_sys_kexec_file_load
```
**Symbols:**

```
ffffffff81201ce0-ffffffff81201fc5: __do_sys_kexec_file_load (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int __do_sys_kexec_file_load(int kernel_fd, int initrd_fd, long unsigned int cmdline_len, const char *cmdline_ptr, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff812170b0)
Location: kernel/kexec_file.c:325
Inline: False
Direct callers:
  - kernel/kexec_file.c:__ia32_sys_kexec_file_load
  - kernel/kexec_file.c:__x64_sys_kexec_file_load
```
**Symbols:**

```
ffffffff812170b0-ffffffff812173a7: __do_sys_kexec_file_load (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
long int __do_sys_kexec_file_load(int kernel_fd, int initrd_fd, long unsigned int cmdline_len, const char *cmdline_ptr, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kexec_file.c (0)
Location: kernel/kexec_file.c:330
Inline: False
Direct callers:
  - kernel/kexec_file.c:__ia32_sys_kexec_file_load
  - kernel/kexec_file.c:__x64_sys_kexec_file_load
```
**Symbols:**

```
ffffffff8122efc0-ffffffff8122f3f4: __do_sys_kexec_file_load (STB_LOCAL)
ffffffff821b6488-ffffffff821b650b: __do_sys_kexec_file_load.cold (STB_LOCAL)
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
In kernel/kexec_file.c (ffff8000101cad94)
Location: kernel/kexec_file.c:370
Inline: True
Inline callers:
  - kernel/kexec_file.c:__arm64_sys_kexec_file_load
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
In kernel/kexec_file.c (c00000000023484c)
Location: kernel/kexec_file.c:370
Inline: True
Inline callers:
  - kernel/kexec_file.c:__se_sys_kexec_file_load
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
In kernel/kexec_file.c (ffffffff81154902)
Location: kernel/kexec_file.c:370
Inline: True
Inline callers:
  - kernel/kexec_file.c:__ia32_sys_kexec_file_load
  - kernel/kexec_file.c:__x64_sys_kexec_file_load
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
In kernel/kexec_file.c (ffffffff81147c22)
Location: kernel/kexec_file.c:370
Inline: True
Inline callers:
  - kernel/kexec_file.c:__ia32_sys_kexec_file_load
  - kernel/kexec_file.c:__x64_sys_kexec_file_load
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
In kernel/kexec_file.c (ffffffff811526e2)
Location: kernel/kexec_file.c:370
Inline: True
Inline callers:
  - kernel/kexec_file.c:__ia32_sys_kexec_file_load
  - kernel/kexec_file.c:__x64_sys_kexec_file_load
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
In kernel/kexec_file.c (ffffffff8115f5d2)
Location: kernel/kexec_file.c:370
Inline: True
Inline callers:
  - kernel/kexec_file.c:__ia32_sys_kexec_file_load
  - kernel/kexec_file.c:__x64_sys_kexec_file_load
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
