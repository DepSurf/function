# Function: <code>trace_initcall_level</code>

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
<summary>In <code>4.18</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void trace_initcall_level(const char *level);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff810029ce)
Location: include/trace/events/initcall.h:10
Inline: True
Direct callers:
  - init/main.c:kernel_init_freeable
  - init/main.c:kernel_init_freeable
```
```
In kernel/printk/printk.c (ffffffff826f6a8f)
Location: include/trace/events/initcall.h:10
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_init
```
```
In security/security.c (ffffffff82715e61)
Location: include/trace/events/initcall.h:10
Inline: True
Inline callers:
  - security/security.c:security_init
```
**Symbols:**

```
ffffffff810029ce-ffffffff81002a1c: trace_initcall_level (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void trace_initcall_level(const char *level);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff810029e5)
Location: include/trace/events/initcall.h:10
Inline: True
Direct callers:
  - init/main.c:kernel_init_freeable
  - init/main.c:kernel_init_freeable
```
```
In kernel/printk/printk.c (ffffffff828ad9bf)
Location: include/trace/events/initcall.h:10
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_init
```
**Symbols:**

```
ffffffff810029e5-ffffffff81002a33: trace_initcall_level (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void trace_initcall_level(const char *level);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff81002b11)
Location: include/trace/events/initcall.h:10
Inline: True
Direct callers:
  - init/main.c:kernel_init_freeable
  - init/main.c:kernel_init_freeable
```
```
In kernel/printk/printk.c (ffffffff828c637a)
Location: include/trace/events/initcall.h:10
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_init
```
**Symbols:**

```
ffffffff81002b11-ffffffff81002b5f: trace_initcall_level (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void trace_initcall_level(const char *level);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff81002b11)
Location: include/trace/events/initcall.h:10
Inline: True
Direct callers:
  - init/main.c:kernel_init_freeable
  - init/main.c:kernel_init_freeable
```
```
In kernel/printk/printk.c (ffffffff828ce9a7)
Location: include/trace/events/initcall.h:10
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_init
```
**Symbols:**

```
ffffffff81002b11-ffffffff81002b5f: trace_initcall_level (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void trace_initcall_level(const char *level);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff81003c0e)
Location: include/trace/events/initcall.h:10
Inline: True
Direct callers:
  - init/main.c:kernel_init_freeable
  - init/main.c:do_initcalls
```
```
In kernel/printk/printk.c (ffffffff82cefe0f)
Location: include/trace/events/initcall.h:10
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_init
```
**Symbols:**

```
ffffffff81003c0e-ffffffff81003c61: trace_initcall_level (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void trace_initcall_level(const char *level);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff81bd17ed)
Location: include/trace/events/initcall.h:10
Inline: True
Direct callers:
  - init/main.c:kernel_init_freeable
  - init/main.c:do_initcalls
```
```
In kernel/printk/printk.c (ffffffff82fdc80e)
Location: include/trace/events/initcall.h:10
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_init
```
**Symbols:**

```
ffffffff81bd17ed-ffffffff81bd1831: trace_initcall_level (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void trace_initcall_level(const char *level);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff81bc37fd)
Location: include/trace/events/initcall.h:10
Inline: True
Direct callers:
  - init/main.c:kernel_init_freeable
  - init/main.c:do_initcalls
```
```
In kernel/printk/printk.c (ffffffff831e756d)
Location: include/trace/events/initcall.h:10
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_init
```
**Symbols:**

```
ffffffff81bc37fd-ffffffff81bc3841: trace_initcall_level (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void trace_initcall_level(const char *level);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff81c94866)
Location: include/trace/events/initcall.h:10
Inline: True
Direct callers:
  - init/main.c:kernel_init_freeable
  - init/main.c:do_initcalls
```
```
In kernel/printk/printk.c (ffffffff832cb6fb)
Location: include/trace/events/initcall.h:10
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_init
```
**Symbols:**

```
ffffffff81c94866-ffffffff81c948a7: trace_initcall_level (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void trace_initcall_level(const char *level);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff81e439c8)
Location: include/trace/events/initcall.h:10
Inline: True
Direct callers:
  - init/main.c:kernel_init_freeable
  - init/main.c:do_initcalls
```
```
In kernel/printk/printk.c (ffffffff8347edf4)
Location: include/trace/events/initcall.h:10
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_init
```
**Symbols:**

```
ffffffff81e439c8-ffffffff81e43a27: trace_initcall_level (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff83e619a3)
Location: include/trace/events/initcall.h:10
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
  - init/main.c:kernel_init_freeable
  - init/main.c:do_initcalls
  - init/main.c:do_initcalls
```
```
In kernel/printk/printk.c (ffffffff83eaaf81)
Location: include/trace/events/initcall.h:10
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff83681dc3)
Location: include/trace/events/initcall.h:10
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
  - init/main.c:kernel_init_freeable
  - init/main.c:do_initcalls
  - init/main.c:do_initcalls
```
```
In kernel/printk/printk.c (ffffffff836cff41)
Location: include/trace/events/initcall.h:10
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff838b0df3)
Location: include/trace/events/initcall.h:10
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
  - init/main.c:kernel_init_freeable
  - init/main.c:do_initcalls
  - init/main.c:do_initcalls
```
```
In kernel/printk/printk.c (ffffffff83901351)
Location: include/trace/events/initcall.h:10
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_init
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
void trace_initcall_level(const char *level);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/main.c (ffff800010085194)
Location: include/trace/events/initcall.h:10
Inline: True
Direct callers:
  - init/main.c:kernel_init_freeable
  - init/main.c:kernel_init_freeable
```
```
In kernel/printk/printk.c (ffff800011446244)
Location: include/trace/events/initcall.h:10
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_init
```
**Symbols:**

```
ffff800010085194-ffff80001008520c: trace_initcall_level (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void trace_initcall_level(const char *level);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/main.c (c0303944)
Location: include/trace/events/initcall.h:10
Inline: True
Direct callers:
  - init/main.c:kernel_init_freeable
  - init/main.c:kernel_init_freeable
```
```
In kernel/printk/printk.c (c15208e0)
Location: include/trace/events/initcall.h:10
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_init
```
**Symbols:**

```
c0303944-c03039d0: trace_initcall_level (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void trace_initcall_level(const char *level);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/main.c (c000000000010520)
Location: include/trace/events/initcall.h:10
Inline: True
Direct callers:
  - init/main.c:kernel_init_freeable
  - init/main.c:kernel_init_freeable
```
```
In kernel/printk/printk.c (c00000000136af7c)
Location: include/trace/events/initcall.h:10
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_init
```
**Symbols:**

```
c000000000010520-c0000000000105c0: trace_initcall_level (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void trace_initcall_level(const char *level);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffe0000b459e)
Location: include/trace/events/initcall.h:10
Inline: True
Direct callers:
  - init/main.c:kernel_init_freeable
  - init/main.c:kernel_init_freeable
```
```
In kernel/printk/printk.c (ffffffe000007e3e)
Location: include/trace/events/initcall.h:10
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_init
```
**Symbols:**

```
ffffffe0000b459e-ffffffe0000b4600: trace_initcall_level (STB_LOCAL)
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
void trace_initcall_level(const char *level);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff81002b11)
Location: include/trace/events/initcall.h:10
Inline: True
Direct callers:
  - init/main.c:kernel_init_freeable
  - init/main.c:kernel_init_freeable
```
```
In kernel/printk/printk.c (ffffffff828b769f)
Location: include/trace/events/initcall.h:10
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_init
```
**Symbols:**

```
ffffffff81002b11-ffffffff81002b5f: trace_initcall_level (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void trace_initcall_level(const char *level);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff81000fe4)
Location: include/trace/events/initcall.h:10
Inline: True
Direct callers:
  - init/main.c:kernel_init_freeable
  - init/main.c:kernel_init_freeable
```
```
In kernel/printk/printk.c (ffffffff828af91f)
Location: include/trace/events/initcall.h:10
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_init
```
**Symbols:**

```
ffffffff81000fe4-ffffffff81001032: trace_initcall_level (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void trace_initcall_level(const char *level);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff81002b11)
Location: include/trace/events/initcall.h:10
Inline: True
Direct callers:
  - init/main.c:kernel_init_freeable
  - init/main.c:kernel_init_freeable
```
```
In kernel/printk/printk.c (ffffffff828ca5db)
Location: include/trace/events/initcall.h:10
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_init
```
**Symbols:**

```
ffffffff81002b11-ffffffff81002b5f: trace_initcall_level (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void trace_initcall_level(const char *level);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff81002b41)
Location: include/trace/events/initcall.h:10
Inline: True
Direct callers:
  - init/main.c:kernel_init_freeable
  - init/main.c:kernel_init_freeable
```
```
In kernel/printk/printk.c (ffffffff828cf98d)
Location: include/trace/events/initcall.h:10
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_init
```
**Symbols:**

```
ffffffff81002b41-ffffffff81002ba4: trace_initcall_level (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
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
