# Function: <code>show_mem</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void show_mem(unsigned int filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/show_mem.c (ffffffff813f1630)
Location: lib/show_mem.c:12
Inline: False
Direct callers:
  - mm/oom_kill.c:dump_header
  - mm/page_alloc.c:warn_alloc_failed
  - drivers/tty/sysrq.c:sysrq_handle_showmem
  - drivers/tty/vt/keyboard.c:fn_show_mem
```
**Symbols:**

```
ffffffff813f1630-ffffffff813f171e: show_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void show_mem(unsigned int filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/show_mem.c (ffffffff81437fc0)
Location: lib/show_mem.c:12
Inline: False
Direct callers:
  - mm/page_alloc.c:warn_alloc_failed
  - drivers/tty/sysrq.c:sysrq_handle_showmem
  - drivers/tty/vt/keyboard.c:fn_show_mem
```
**Symbols:**

```
ffffffff81437fc0-ffffffff814380ac: show_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void show_mem(unsigned int filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/show_mem.c (ffffffff81454fb0)
Location: lib/show_mem.c:12
Inline: False
Direct callers:
  - mm/page_alloc.c:warn_alloc
  - drivers/tty/sysrq.c:sysrq_handle_showmem
  - drivers/tty/vt/keyboard.c:fn_show_mem
```
**Symbols:**

```
ffffffff81454fb0-ffffffff8145509c: show_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void show_mem(unsigned int filter, nodemask_t *nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/show_mem.c (ffffffff818f50e0)
Location: lib/show_mem.c:12
Inline: False
Direct callers:
  - mm/oom_kill.c:dump_header
  - mm/page_alloc.c:warn_alloc
  - drivers/tty/sysrq.c:sysrq_handle_showmem
  - drivers/tty/vt/keyboard.c:fn_show_mem
```
**Symbols:**

```
ffffffff818f50e0-ffffffff818f51d2: show_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void show_mem(unsigned int filter, nodemask_t *nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/show_mem.c (ffffffff8197bae0)
Location: lib/show_mem.c:12
Inline: False
Direct callers:
  - mm/oom_kill.c:dump_header
  - mm/page_alloc.c:warn_alloc
  - drivers/tty/sysrq.c:sysrq_handle_showmem
  - drivers/tty/vt/keyboard.c:fn_show_mem
```
**Symbols:**

```
ffffffff8197bae0-ffffffff8197bbd2: show_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void show_mem(unsigned int filter, nodemask_t *nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/show_mem.c (ffffffff819d805a)
Location: lib/show_mem.c:12
Inline: False
Direct callers:
  - mm/oom_kill.c:dump_header
  - mm/page_alloc.c:warn_alloc
  - drivers/tty/sysrq.c:sysrq_handle_showmem
  - drivers/tty/vt/keyboard.c:fn_show_mem
```
**Symbols:**

```
ffffffff819d805a-ffffffff819d8143: show_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void show_mem(unsigned int filter, nodemask_t *nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/show_mem.c (ffffffff81a1029a)
Location: lib/show_mem.c:12
Inline: False
Direct callers:
  - kernel/panic.c:panic
  - mm/oom_kill.c:dump_header
  - mm/page_alloc.c:warn_alloc
  - drivers/tty/sysrq.c:sysrq_handle_showmem
  - drivers/tty/vt/keyboard.c:fn_show_mem
```
**Symbols:**

```
ffffffff81a1029a-ffffffff81a10363: show_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void show_mem(unsigned int filter, nodemask_t *nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/show_mem.c (ffffffff81a7f824)
Location: lib/show_mem.c:12
Inline: False
Direct callers:
  - kernel/panic.c:panic
  - mm/oom_kill.c:dump_header
  - mm/page_alloc.c:warn_alloc
  - drivers/tty/sysrq.c:sysrq_handle_showmem
  - drivers/tty/vt/keyboard.c:fn_show_mem
```
**Symbols:**

```
ffffffff81a7f824-ffffffff81a7f8f1: show_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void show_mem(unsigned int filter, nodemask_t *nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/show_mem.c (ffffffff81ab6a24)
Location: lib/show_mem.c:11
Inline: False
Direct callers:
  - kernel/panic.c:panic
  - mm/oom_kill.c:dump_header
  - mm/page_alloc.c:warn_alloc
  - drivers/tty/sysrq.c:sysrq_handle_showmem
  - drivers/tty/vt/keyboard.c:fn_show_mem
```
**Symbols:**

```
ffffffff81ab6a24-ffffffff81ab6af1: show_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void show_mem(unsigned int filter, nodemask_t *nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/show_mem.c (ffffffff815f1683)
Location: lib/show_mem.c:11
Inline: False
Direct callers:
  - kernel/panic.c:panic
  - mm/oom_kill.c:dump_header
  - mm/page_alloc.c:warn_alloc
  - drivers/tty/sysrq.c:sysrq_handle_showmem
  - drivers/tty/vt/keyboard.c:fn_show_mem
```
**Symbols:**

```
ffffffff815f1683-ffffffff815f1738: show_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void show_mem(unsigned int filter, nodemask_t *nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/show_mem.c (ffffffff81bf4cd0)
Location: lib/show_mem.c:11
Inline: False
Direct callers:
  - kernel/panic.c:panic
  - mm/oom_kill.c:dump_header
  - mm/page_alloc.c:warn_alloc
  - drivers/tty/sysrq.c:sysrq_handle_showmem
  - drivers/tty/vt/keyboard.c:fn_show_mem
```
**Symbols:**

```
ffffffff81bf4cd0-ffffffff81bf4d85: show_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void show_mem(unsigned int filter, nodemask_t *nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/show_mem.c (ffffffff81be6bf3)
Location: lib/show_mem.c:11
Inline: False
Direct callers:
  - init/initramfs.c:panic_show_mem
  - kernel/panic.c:panic
  - mm/oom_kill.c:dump_header
  - mm/page_alloc.c:warn_alloc
  - drivers/tty/sysrq.c:sysrq_handle_showmem
  - drivers/tty/vt/keyboard.c:fn_show_mem
```
**Symbols:**

```
ffffffff81be6bf3-ffffffff81be6ca8: show_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void show_mem(unsigned int filter, nodemask_t *nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/show_mem.c (ffffffff81cdfa46)
Location: lib/show_mem.c:11
Inline: False
Direct callers:
  - init/initramfs.c:panic_show_mem
  - kernel/panic.c:panic
  - mm/oom_kill.c:dump_header
  - mm/page_alloc.c:warn_alloc
  - drivers/tty/sysrq.c:sysrq_handle_showmem
  - drivers/tty/vt/keyboard.c:fn_show_mem
```
**Symbols:**

```
ffffffff81cdfa46-ffffffff81cdfb21: show_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void show_mem(unsigned int filter, nodemask_t *nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/show_mem.c (ffffffff81ea6206)
Location: lib/show_mem.c:11
Inline: False
Direct callers:
  - init/initramfs.c:panic_show_mem
  - mm/oom_kill.c:dump_header
  - mm/page_alloc.c:warn_alloc
  - drivers/tty/sysrq.c:sysrq_handle_showmem
  - drivers/tty/vt/keyboard.c:fn_show_mem
```
**Symbols:**

```
ffffffff81ea6206-ffffffff81ea62ee: show_mem (STB_GLOBAL)
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
In init/initramfs.c (ffffffff810024cd)
Location: include/linux/mm.h:2753
Inline: True
Inline callers:
  - init/initramfs.c:panic_show_mem
```
```
In kernel/panic.c (ffffffff810ea134)
Location: include/linux/mm.h:2753
Inline: True
```
```
In drivers/tty/sysrq.c (ffffffff81a5a275)
Location: include/linux/mm.h:2753
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_showmem
```
```
In drivers/tty/vt/keyboard.c (ffffffff81a5fd15)
Location: include/linux/mm.h:2753
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:fn_show_mem
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
In init/initramfs.c (ffffffff8368495e)
Location: include/linux/mm.h:3072
Inline: True
Inline callers:
  - init/initramfs.c:do_populate_rootfs
  - init/initramfs.c:unpack_to_rootfs
  - init/initramfs.c:dir_add
  - init/initramfs.c:find_link
```
```
In kernel/panic.c (ffffffff810f5d39)
Location: include/linux/mm.h:3072
Inline: True
```
```
In drivers/tty/sysrq.c (ffffffff81aa48a5)
Location: include/linux/mm.h:3072
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_showmem
```
```
In drivers/tty/vt/keyboard.c (ffffffff81aaa3d5)
Location: include/linux/mm.h:3072
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:fn_show_mem
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
In init/initramfs.c (ffffffff838b3b3c)
Location: include/linux/mm.h:3198
Inline: True
Inline callers:
  - init/initramfs.c:do_populate_rootfs
  - init/initramfs.c:unpack_to_rootfs
  - init/initramfs.c:dir_add
  - init/initramfs.c:find_link
```
```
In kernel/panic.c (ffffffff810ff0e4)
Location: include/linux/mm.h:3198
Inline: True
```
```
In drivers/tty/sysrq.c (ffffffff81af72a5)
Location: include/linux/mm.h:3198
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_showmem
```
```
In drivers/tty/vt/keyboard.c (ffffffff81afce35)
Location: include/linux/mm.h:3198
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:fn_show_mem
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void show_mem(unsigned int filter, nodemask_t *nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/show_mem.c (ffff800010d9120c)
Location: lib/show_mem.c:11
Inline: False
Direct callers:
  - kernel/panic.c:panic
  - mm/oom_kill.c:dump_header
  - mm/page_alloc.c:warn_alloc
  - drivers/tty/sysrq.c:sysrq_handle_showmem
  - drivers/tty/vt/keyboard.c:fn_show_mem
```
**Symbols:**

```
ffff800010d9120c-ffff800010d912ec: show_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void show_mem(unsigned int filter, nodemask_t *nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/show_mem.c (c0e8bd98)
Location: lib/show_mem.c:11
Inline: False
Direct callers:
  - kernel/panic.c:panic
  - mm/oom_kill.c:dump_header
  - mm/page_alloc.c:warn_alloc
  - drivers/tty/sysrq.c:sysrq_handle_showmem
  - drivers/tty/vt/keyboard.c:fn_show_mem
```
**Symbols:**

```
c0e8bd98-c0e8be6c: show_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void show_mem(unsigned int filter, nodemask_t *nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/show_mem.c (c000000000ed46fc)
Location: lib/show_mem.c:11
Inline: False
Direct callers:
  - arch/powerpc/xmon/xmon.c:cmds
  - kernel/panic.c:panic
  - mm/oom_kill.c:dump_header
  - mm/page_alloc.c:warn_alloc
  - drivers/tty/sysrq.c:sysrq_handle_showmem
  - drivers/tty/vt/keyboard.c:fn_show_mem
```
**Symbols:**

```
c000000000ed46fc-c000000000ed4828: show_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void show_mem(unsigned int filter, nodemask_t *nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/show_mem.c (ffffffe0008ba086)
Location: lib/show_mem.c:11
Inline: False
Direct callers:
  - kernel/panic.c:panic
  - mm/oom_kill.c:dump_header
  - mm/page_alloc.c:warn_alloc
  - drivers/tty/sysrq.c:sysrq_handle_showmem
  - drivers/tty/vt/keyboard.c:fn_show_mem
```
**Symbols:**

```
ffffffe0008ba086-ffffffe0008ba148: show_mem (STB_GLOBAL)
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
void show_mem(unsigned int filter, nodemask_t *nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/show_mem.c (ffffffff81a55874)
Location: lib/show_mem.c:11
Inline: False
Direct callers:
  - kernel/panic.c:panic
  - mm/oom_kill.c:dump_header
  - mm/page_alloc.c:warn_alloc
  - drivers/tty/sysrq.c:sysrq_handle_showmem
  - drivers/tty/vt/keyboard.c:fn_show_mem
```
**Symbols:**

```
ffffffff81a55874-ffffffff81a55941: show_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void show_mem(unsigned int filter, nodemask_t *nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/show_mem.c (ffffffff81a12954)
Location: lib/show_mem.c:11
Inline: False
Direct callers:
  - kernel/panic.c:panic
  - mm/oom_kill.c:dump_header
  - mm/page_alloc.c:warn_alloc
  - drivers/tty/sysrq.c:sysrq_handle_showmem
  - drivers/tty/vt/keyboard.c:fn_show_mem
```
**Symbols:**

```
ffffffff81a12954-ffffffff81a12a21: show_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void show_mem(unsigned int filter, nodemask_t *nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/show_mem.c (ffffffff81ac1c64)
Location: lib/show_mem.c:11
Inline: False
Direct callers:
  - kernel/panic.c:panic
  - mm/oom_kill.c:dump_header
  - mm/page_alloc.c:warn_alloc
  - drivers/tty/sysrq.c:sysrq_handle_showmem
  - drivers/tty/vt/keyboard.c:fn_show_mem
```
**Symbols:**

```
ffffffff81ac1c64-ffffffff81ac1d31: show_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void show_mem(unsigned int filter, nodemask_t *nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/show_mem.c (ffffffff81ace134)
Location: lib/show_mem.c:11
Inline: False
Direct callers:
  - kernel/panic.c:panic
  - mm/oom_kill.c:dump_header
  - mm/page_alloc.c:warn_alloc
  - drivers/tty/sysrq.c:sysrq_handle_showmem
  - drivers/tty/vt/keyboard.c:fn_show_mem
```
**Symbols:**

```
ffffffff81ace134-ffffffff81ace201: show_mem (STB_GLOBAL)
```
</details>
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>nodemask_t *nodemask</code>
</li>
</ul>
</details>
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
