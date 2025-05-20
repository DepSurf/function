# Function: <code>__sys_bpf</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __sys_bpf(int cmd, bpfptr_t uattr, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/syscall.c (0)
Location: kernel/bpf/syscall.c:4572
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_sys_bpf
  - kernel/bpf/syscall.c:__ia32_sys_bpf
  - kernel/bpf/syscall.c:__x64_sys_bpf
```
**Symbols:**

```
ffffffff81233680-ffffffff8123449a: __sys_bpf (STB_LOCAL)
ffffffff81cb7bb8-ffffffff81cb7bd3: __sys_bpf.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __sys_bpf(int cmd, bpfptr_t uattr, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81276a10)
Location: kernel/bpf/syscall.c:4863
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:kern_sys_bpf
  - kernel/bpf/syscall.c:bpf_sys_bpf
  - kernel/bpf/syscall.c:__ia32_sys_bpf
  - kernel/bpf/syscall.c:__x64_sys_bpf
```
**Symbols:**

```
ffffffff81276a10-ffffffff812777f0: __sys_bpf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int __sys_bpf(int cmd, bpfptr_t uattr, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/syscall.c (0)
Location: kernel/bpf/syscall.c:4915
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:kern_sys_bpf
  - kernel/bpf/syscall.c:bpf_sys_bpf
  - kernel/bpf/syscall.c:__ia32_sys_bpf
  - kernel/bpf/syscall.c:__x64_sys_bpf
```
**Symbols:**

```
ffffffff812ccbb0-ffffffff812cdb5d: __sys_bpf (STB_LOCAL)
ffffffff8205fa14-ffffffff8205fa29: __sys_bpf.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __sys_bpf(int cmd, bpfptr_t uattr, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812f45b0)
Location: kernel/bpf/syscall.c:5098
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:kern_sys_bpf
  - kernel/bpf/syscall.c:bpf_sys_bpf
  - kernel/bpf/syscall.c:__ia32_sys_bpf
  - kernel/bpf/syscall.c:__x64_sys_bpf
```
**Symbols:**

```
ffffffff812f45b0-ffffffff812f50f7: __sys_bpf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __sys_bpf(int cmd, bpfptr_t uattr, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff813134f0)
Location: kernel/bpf/syscall.c:5418
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:kern_sys_bpf
  - kernel/bpf/syscall.c:bpf_sys_bpf
  - kernel/bpf/syscall.c:__ia32_sys_bpf
  - kernel/bpf/syscall.c:__x64_sys_bpf
```
**Symbols:**

```
ffffffff813134f0-ffffffff81313ef3: __sys_bpf (STB_LOCAL)
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
