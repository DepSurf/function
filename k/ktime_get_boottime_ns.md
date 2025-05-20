# Function: <code>ktime_get_boottime_ns</code>

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
<summary>In <code>5.3</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u64 ktime_get_boottime_ns();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8109921b)
Location: include/linux/timekeeping.h:162
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/bpf/syscall.c (ffffffff811d5250)
Location: include/linux/timekeeping.h:162
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In kernel/events/core.c (ffffffff811fb5c0)
Location: include/linux/timekeeping.h:162
Inline: False
```
**Symbols:**

```
ffffffff811fb5c0-ffffffff811fb5d0: ktime_get_boottime_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u64 ktime_get_boottime_ns();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8109f813)
Location: include/linux/timekeeping.h:162
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/bpf/syscall.c (ffffffff811e1975)
Location: include/linux/timekeeping.h:162
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In kernel/events/core.c (ffffffff81208970)
Location: include/linux/timekeeping.h:162
Inline: False
```
**Symbols:**

```
ffffffff81208970-ffffffff81208980: ktime_get_boottime_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u64 ktime_get_boottime_ns();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a6924)
Location: include/linux/timekeeping.h:162
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/bpf/syscall.c (ffffffff81200302)
Location: include/linux/timekeeping.h:162
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In kernel/events/core.c (ffffffff812313f0)
Location: include/linux/timekeeping.h:162
Inline: False
```
**Symbols:**

```
ffffffff812313f0-ffffffff81231400: ktime_get_boottime_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u64 ktime_get_boottime_ns();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a2401)
Location: include/linux/timekeeping.h:161
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/bpf/syscall.c (ffffffff811ff758)
Location: include/linux/timekeeping.h:161
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In kernel/events/core.c (ffffffff8123b060)
Location: include/linux/timekeeping.h:161
Inline: False
```
**Symbols:**

```
ffffffff8123b060-ffffffff8123b070: ktime_get_boottime_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u64 ktime_get_boottime_ns();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a30be)
Location: include/linux/timekeeping.h:162
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/bpf/syscall.c (ffffffff81200103)
Location: include/linux/timekeeping.h:162
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In kernel/events/core.c (ffffffff8123f820)
Location: include/linux/timekeeping.h:162
Inline: False
```
**Symbols:**

```
ffffffff8123f820-ffffffff8123f830: ktime_get_boottime_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u64 ktime_get_boottime_ns();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810b484f)
Location: include/linux/timekeeping.h:162
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/bpf/syscall.c (ffffffff81231e26)
Location: include/linux/timekeeping.h:162
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In kernel/events/core.c (ffffffff8127a040)
Location: include/linux/timekeeping.h:162
Inline: False
```
**Symbols:**

```
ffffffff8127a040-ffffffff8127a050: ktime_get_boottime_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u64 ktime_get_boottime_ns();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810cad41)
Location: include/linux/timekeeping.h:162
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/bpf/syscall.c (ffffffff81275116)
Location: include/linux/timekeeping.h:162
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In kernel/events/core.c (ffffffff812cd530)
Location: include/linux/timekeeping.h:162
Inline: False
```
**Symbols:**

```
ffffffff812cd530-ffffffff812cd546: ktime_get_boottime_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u64 ktime_get_boottime_ns();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810e82d6)
Location: include/linux/timekeeping.h:162
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/bpf/syscall.c (ffffffff812ca5e3)
Location: include/linux/timekeeping.h:162
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In kernel/events/core.c (ffffffff81335450)
Location: include/linux/timekeeping.h:162
Inline: False
```
**Symbols:**

```
ffffffff81335450-ffffffff81335466: ktime_get_boottime_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u64 ktime_get_boottime_ns();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810f3f35)
Location: include/linux/timekeeping.h:162
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/bpf/syscall.c (ffffffff812f1f9d)
Location: include/linux/timekeeping.h:162
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In kernel/events/core.c (ffffffff813661a0)
Location: include/linux/timekeeping.h:162
Inline: False
```
**Symbols:**

```
ffffffff813661a0-ffffffff813661b6: ktime_get_boottime_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u64 ktime_get_boottime_ns();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810fd2f7)
Location: include/linux/timekeeping.h:163
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/bpf/syscall.c (ffffffff81310e13)
Location: include/linux/timekeeping.h:163
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In kernel/events/core.c (ffffffff8138f2c0)
Location: include/linux/timekeeping.h:163
Inline: False
```
**Symbols:**

```
ffffffff8138f2c0-ffffffff8138f2d6: ktime_get_boottime_ns (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u64 ktime_get_boottime_ns();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffff8000100f3eb0)
Location: include/linux/timekeeping.h:162
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/bpf/syscall.c (ffff8000102649c0)
Location: include/linux/timekeeping.h:162
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In kernel/events/core.c (ffff800010291d68)
Location: include/linux/timekeeping.h:162
Inline: False
```
**Symbols:**

```
ffff800010291d68-ffff800010291d80: ktime_get_boottime_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u64 ktime_get_boottime_ns();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (c03528a0)
Location: include/linux/timekeeping.h:162
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/bpf/syscall.c (c0496bd4)
Location: include/linux/timekeeping.h:162
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In kernel/events/core.c (c04c2f30)
Location: include/linux/timekeeping.h:162
Inline: False
```
**Symbols:**

```
c04c2f30-c04c2f48: ktime_get_boottime_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u64 ktime_get_boottime_ns();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (c00000000013a220)
Location: include/linux/timekeeping.h:162
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/bpf/syscall.c (c0000000003093f0)
Location: include/linux/timekeeping.h:162
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In kernel/events/core.c (c0000000003403b0)
Location: include/linux/timekeeping.h:162
Inline: False
```
**Symbols:**

```
c0000000003403b0-c0000000003403e0: ktime_get_boottime_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u64 ktime_get_boottime_ns();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffe0000c06b8)
Location: include/linux/timekeeping.h:162
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/bpf/syscall.c (ffffffe0001a0624)
Location: include/linux/timekeeping.h:162
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In kernel/events/core.c (ffffffe0001c4628)
Location: include/linux/timekeeping.h:162
Inline: False
```
**Symbols:**

```
ffffffe0001c4628-ffffffe0001c4642: ktime_get_boottime_ns (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u64 ktime_get_boottime_ns();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81099133)
Location: include/linux/timekeeping.h:162
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/bpf/syscall.c (ffffffff811d9f95)
Location: include/linux/timekeeping.h:162
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In kernel/events/core.c (ffffffff81200f90)
Location: include/linux/timekeeping.h:162
Inline: False
```
**Symbols:**

```
ffffffff81200f90-ffffffff81200fa0: ktime_get_boottime_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u64 ktime_get_boottime_ns();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81087b83)
Location: include/linux/timekeeping.h:162
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/bpf/syscall.c (ffffffff811ccd55)
Location: include/linux/timekeeping.h:162
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In kernel/events/core.c (ffffffff811f3ce0)
Location: include/linux/timekeeping.h:162
Inline: False
```
**Symbols:**

```
ffffffff811f3ce0-ffffffff811f3cf0: ktime_get_boottime_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u64 ktime_get_boottime_ns();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810990e3)
Location: include/linux/timekeeping.h:162
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/bpf/syscall.c (ffffffff811d7d65)
Location: include/linux/timekeeping.h:162
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In kernel/events/core.c (ffffffff811fed60)
Location: include/linux/timekeeping.h:162
Inline: False
```
**Symbols:**

```
ffffffff811fed60-ffffffff811fed70: ktime_get_boottime_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u64 ktime_get_boottime_ns();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a0d1c)
Location: include/linux/timekeeping.h:162
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/bpf/syscall.c (ffffffff811e6105)
Location: include/linux/timekeeping.h:162
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In kernel/events/core.c (ffffffff8120ddf0)
Location: include/linux/timekeeping.h:162
Inline: False
```
**Symbols:**

```
ffffffff8120ddf0-ffffffff8120de00: ktime_get_boottime_ns (STB_LOCAL)
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
