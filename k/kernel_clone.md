# Function: <code>kernel_clone</code>

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
pid_t kernel_clone(struct kernel_clone_args *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a2f60)
Location: kernel/fork.c:2439
Inline: False
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_clone
  - kernel/fork.c:__do_sys_clone3
  - kernel/fork.c:__do_sys_clone
  - kernel/fork.c:__do_sys_vfork
  - kernel/fork.c:__do_sys_fork
  - kernel/fork.c:kernel_thread
```
**Symbols:**

```
ffffffff810a2f60-ffffffff810a3255: kernel_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
pid_t kernel_clone(struct kernel_clone_args *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a3ae0)
Location: kernel/fork.c:2471
Inline: False
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_clone
  - kernel/fork.c:__do_sys_clone3
  - kernel/fork.c:__do_sys_clone
  - kernel/fork.c:__do_sys_vfork
  - kernel/fork.c:__do_sys_fork
  - kernel/fork.c:kernel_thread
```
**Symbols:**

```
ffffffff810a3ae0-ffffffff810a3eaf: kernel_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
pid_t kernel_clone(struct kernel_clone_args *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810b5300)
Location: kernel/fork.c:2564
Inline: False
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_clone
  - kernel/fork.c:__do_sys_clone3
  - kernel/fork.c:__do_sys_clone
  - kernel/fork.c:__do_sys_vfork
  - kernel/fork.c:__do_sys_fork
  - kernel/fork.c:kernel_thread
```
**Symbols:**

```
ffffffff810b5300-ffffffff810b56cc: kernel_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
pid_t kernel_clone(struct kernel_clone_args *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810cb620)
Location: kernel/fork.c:2624
Inline: False
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_clone
  - kernel/fork.c:__do_sys_clone3
  - kernel/fork.c:__do_sys_clone
  - kernel/fork.c:__do_sys_vfork
  - kernel/fork.c:__do_sys_fork
  - kernel/fork.c:user_mode_thread
  - kernel/fork.c:kernel_thread
```
**Symbols:**

```
ffffffff810cb620-ffffffff810cba35: kernel_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
pid_t kernel_clone(struct kernel_clone_args *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810e8be0)
Location: kernel/fork.c:2649
Inline: False
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_clone
  - kernel/fork.c:__do_sys_clone3
  - kernel/fork.c:__do_sys_clone
  - kernel/fork.c:__do_sys_vfork
  - kernel/fork.c:__do_sys_fork
  - kernel/fork.c:user_mode_thread
  - kernel/fork.c:kernel_thread
```
**Symbols:**

```
ffffffff810e8be0-ffffffff810e9018: kernel_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
pid_t kernel_clone(struct kernel_clone_args *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810f47f0)
Location: kernel/fork.c:2880
Inline: False
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_clone
  - kernel/fork.c:__do_sys_clone3
  - kernel/fork.c:__do_sys_clone
  - kernel/fork.c:__do_sys_vfork
  - kernel/fork.c:__do_sys_fork
  - kernel/fork.c:user_mode_thread
  - kernel/fork.c:kernel_thread
```
**Symbols:**

```
ffffffff810f47f0-ffffffff810f4c39: kernel_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
pid_t kernel_clone(struct kernel_clone_args *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810fdb90)
Location: kernel/fork.c:2870
Inline: False
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_clone
  - kernel/fork.c:__do_sys_clone3
  - kernel/fork.c:__do_sys_clone
  - kernel/fork.c:__do_sys_vfork
  - kernel/fork.c:__do_sys_fork
  - kernel/fork.c:user_mode_thread
  - kernel/fork.c:kernel_thread
```
**Symbols:**

```
ffffffff810fdb90-ffffffff810fdfd9: kernel_clone (STB_GLOBAL)
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
