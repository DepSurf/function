# Function: <code>ktime_get_boot_ns</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u64 ktime_get_boot_ns();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8107eb34)
Location: include/linux/timekeeping.h:219
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/events/core.c (ffffffff81179810)
Location: include/linux/timekeeping.h:219
Inline: False
```
**Symbols:**

```
ffffffff81179810-ffffffff81179820: ktime_get_boot_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u64 ktime_get_boot_ns();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81080809)
Location: include/linux/timekeeping.h:235
Inline: True
```
```
In kernel/events/core.c (ffffffff8118a0b0)
Location: include/linux/timekeeping.h:235
Inline: False
```
**Symbols:**

```
ffffffff8118a0b0-ffffffff8118a0c0: ktime_get_boot_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u64 ktime_get_boot_ns();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810850d9)
Location: include/linux/timekeeping.h:235
Inline: True
```
```
In kernel/events/core.c (ffffffff811994a0)
Location: include/linux/timekeeping.h:235
Inline: False
```
**Symbols:**

```
ffffffff811994a0-ffffffff811994b0: ktime_get_boot_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u64 ktime_get_boot_ns();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81082006)
Location: include/linux/timekeeping.h:224
Inline: True
```
```
In kernel/events/core.c (ffffffff811a13f0)
Location: include/linux/timekeeping.h:224
Inline: False
```
**Symbols:**

```
ffffffff811a13f0-ffffffff811a1400: ktime_get_boot_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u64 ktime_get_boot_ns();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81088876)
Location: include/linux/timekeeping.h:104
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffff8119f9f8)
Location: include/linux/timekeeping.h:104
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In kernel/events/core.c (ffffffff811b4f70)
Location: include/linux/timekeeping.h:104
Inline: False
```
**Symbols:**

```
ffffffff811b4f70-ffffffff811b4f80: ktime_get_boot_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u64 ktime_get_boot_ns();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8108c5eb)
Location: include/linux/timekeeping.h:119
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffff811b5e83)
Location: include/linux/timekeeping.h:119
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In kernel/events/core.c (ffffffff811d3dd0)
Location: include/linux/timekeeping.h:119
Inline: False
```
**Symbols:**

```
ffffffff811d3dd0-ffffffff811d3de0: ktime_get_boot_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u64 ktime_get_boot_ns();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81094a66)
Location: include/linux/timekeeping.h:134
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffff811c3ac2)
Location: include/linux/timekeeping.h:134
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In kernel/events/core.c (ffffffff811e42d0)
Location: include/linux/timekeeping.h:134
Inline: False
```
**Symbols:**

```
ffffffff811e42d0-ffffffff811e42e0: ktime_get_boot_ns (STB_LOCAL)
```
</details>
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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
</ul>
