# Function: <code>print_tainted</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
const char *print_tainted();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff81080d60)
Location: kernel/panic.c:267
Inline: False
Direct callers:
  - kernel/printk/printk.c:dump_stack_print_info
  - kernel/hung_task.c:watchdog
  - mm/slub.c:slab_bug
```
**Symbols:**

```
ffffffff81080d60-ffffffff81080e0f: print_tainted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
const char *print_tainted();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff81082be0)
Location: kernel/panic.c:316
Inline: False
Direct callers:
  - kernel/printk/printk.c:dump_stack_print_info
  - kernel/hung_task.c:watchdog
  - mm/slub.c:slab_bug
```
**Symbols:**

```
ffffffff81082be0-ffffffff81082c8b: print_tainted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
const char *print_tainted();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff81087670)
Location: kernel/panic.c:346
Inline: False
Direct callers:
  - kernel/printk/printk.c:dump_stack_print_info
  - kernel/hung_task.c:watchdog
  - mm/slub.c:slab_bug
```
**Symbols:**

```
ffffffff81087670-ffffffff81087713: print_tainted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
const char *print_tainted();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff81084500)
Location: kernel/panic.c:348
Inline: False
Direct callers:
  - kernel/printk/printk.c:dump_stack_print_info
  - kernel/hung_task.c:watchdog
  - mm/slub.c:slab_bug
```
**Symbols:**

```
ffffffff81084500-ffffffff810845a3: print_tainted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
const char *print_tainted();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff8108aee0)
Location: kernel/panic.c:353
Inline: False
Direct callers:
  - kernel/printk/printk.c:dump_stack_print_info
  - kernel/hung_task.c:watchdog
  - mm/slub.c:slab_bug
```
**Symbols:**

```
ffffffff8108aee0-ffffffff8108af82: print_tainted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
const char *print_tainted();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff8108e6c0)
Location: kernel/panic.c:340
Inline: False
Direct callers:
  - kernel/hung_task.c:watchdog
  - mm/slub.c:slab_bug
```
**Symbols:**

```
ffffffff8108e6c0-ffffffff8108e762: print_tainted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
const char *print_tainted();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff81096950)
Location: kernel/panic.c:375
Inline: False
Direct callers:
  - kernel/hung_task.c:watchdog
  - mm/slub.c:slab_bug
  - lib/dump_stack.c:dump_stack_print_info
```
**Symbols:**

```
ffffffff81096950-ffffffff810969f2: print_tainted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
const char *print_tainted();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff8109aee0)
Location: kernel/panic.c:380
Inline: False
Direct callers:
  - kernel/hung_task.c:watchdog
  - mm/slub.c:slab_bug
  - lib/dump_stack.c:dump_stack_print_info
```
**Symbols:**

```
ffffffff8109aee0-ffffffff8109af73: print_tainted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
const char *print_tainted();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff810a1400)
Location: kernel/panic.c:389
Inline: False
Direct callers:
  - kernel/hung_task.c:watchdog
  - mm/slub.c:slab_bug
  - lib/dump_stack.c:dump_stack_print_info
```
**Symbols:**

```
ffffffff810a1400-ffffffff810a1493: print_tainted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
const char *print_tainted();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff810a8270)
Location: kernel/panic.c:399
Inline: False
Direct callers:
  - kernel/hung_task.c:check_hung_task
  - mm/slub.c:slab_bug
  - lib/dump_stack.c:dump_stack_print_info
```
**Symbols:**

```
ffffffff810a8270-ffffffff810a8303: print_tainted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
const char *print_tainted();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff810a3fc0)
Location: kernel/panic.c:399
Inline: False
Direct callers:
  - kernel/hung_task.c:check_hung_task
  - mm/slub.c:slab_bug
  - lib/dump_stack.c:dump_stack_print_info
```
**Symbols:**

```
ffffffff810a3fc0-ffffffff810a4053: print_tainted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
const char *print_tainted();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff810a4c10)
Location: kernel/panic.c:399
Inline: False
Direct callers:
  - kernel/hung_task.c:check_hung_task
  - mm/slub.c:slab_bug
  - lib/dump_stack.c:dump_stack_print_info
```
**Symbols:**

```
ffffffff810a4c10-ffffffff810a4ca3: print_tainted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
const char *print_tainted();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff810b6430)
Location: kernel/panic.c:397
Inline: False
Direct callers:
  - kernel/hung_task.c:check_hung_task
  - mm/slub.c:slab_bug
  - lib/dump_stack.c:dump_stack_print_info
```
**Symbols:**

```
ffffffff810b6430-ffffffff810b64e3: print_tainted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
const char *print_tainted();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff810cc9b0)
Location: kernel/panic.c:441
Inline: False
Direct callers:
  - kernel/hung_task.c:check_hung_task
  - mm/slub.c:slab_bug
  - lib/dump_stack.c:dump_stack_print_info
```
**Symbols:**

```
ffffffff810cc9b0-ffffffff810cca7a: print_tainted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
const char *print_tainted();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff810ea840)
Location: kernel/panic.c:492
Inline: False
Direct callers:
  - kernel/hung_task.c:check_hung_task
  - mm/slub.c:slab_bug
  - lib/dump_stack.c:dump_stack_print_info
```
**Symbols:**

```
ffffffff810ea840-ffffffff810ea90a: print_tainted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
const char *print_tainted();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff810f6420)
Location: kernel/panic.c:492
Inline: False
Direct callers:
  - kernel/hung_task.c:check_hung_task
  - mm/slub.c:slab_bug
  - lib/dump_stack.c:dump_stack_print_info
```
**Symbols:**

```
ffffffff810f6420-ffffffff810f64ea: print_tainted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
const char *print_tainted();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff810ff7d0)
Location: kernel/panic.c:496
Inline: False
Direct callers:
  - kernel/hung_task.c:check_hung_task
  - mm/slub.c:slab_bug
  - lib/dump_stack.c:dump_stack_print_info
```
**Symbols:**

```
ffffffff810ff7d0-ffffffff810ff89a: print_tainted (STB_GLOBAL)
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
const char *print_tainted();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffff8000100f6558)
Location: kernel/panic.c:389
Inline: False
Direct callers:
  - kernel/hung_task.c:watchdog
  - mm/slub.c:slab_bug
  - lib/dump_stack.c:dump_stack_print_info
```
**Symbols:**

```
ffff8000100f6558-ffff8000100f6614: print_tainted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
const char *print_tainted();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (c03546b0)
Location: kernel/panic.c:389
Inline: False
Direct callers:
  - kernel/hung_task.c:watchdog
  - mm/slub.c:slab_bug
  - lib/dump_stack.c:dump_stack_print_info
```
**Symbols:**

```
c03546b0-c0354758: print_tainted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
const char *print_tainted();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (c00000000013c370)
Location: kernel/panic.c:389
Inline: False
Direct callers:
  - arch/powerpc/kernel/process.c:show_regs
  - arch/powerpc/kernel/traps.c:TAUException
  - kernel/hung_task.c:watchdog
  - mm/slub.c:slab_bug
  - lib/dump_stack.c:dump_stack_print_info
```
**Symbols:**

```
c00000000013c370-c00000000013c454: print_tainted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
const char *print_tainted();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffe0000c2242)
Location: kernel/panic.c:389
Inline: False
Direct callers:
  - kernel/hung_task.c:watchdog
  - mm/slub.c:slab_bug
  - lib/dump_stack.c:dump_stack_print_info
```
**Symbols:**

```
ffffffe0000c2242-ffffffe0000c2304: print_tainted (STB_GLOBAL)
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
const char *print_tainted();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff8109ad20)
Location: kernel/panic.c:389
Inline: False
Direct callers:
  - kernel/hung_task.c:watchdog
  - mm/slub.c:slab_bug
  - lib/dump_stack.c:dump_stack_print_info
```
**Symbols:**

```
ffffffff8109ad20-ffffffff8109adb3: print_tainted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
const char *print_tainted();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff81089760)
Location: kernel/panic.c:389
Inline: False
Direct callers:
  - kernel/hung_task.c:watchdog
  - mm/slub.c:slab_bug
  - lib/dump_stack.c:dump_stack_print_info
```
**Symbols:**

```
ffffffff81089760-ffffffff810897f3: print_tainted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
const char *print_tainted();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff8109acd0)
Location: kernel/panic.c:389
Inline: False
Direct callers:
  - kernel/hung_task.c:watchdog
  - mm/slub.c:slab_bug
  - lib/dump_stack.c:dump_stack_print_info
```
**Symbols:**

```
ffffffff8109acd0-ffffffff8109ad63: print_tainted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
const char *print_tainted();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff810a2940)
Location: kernel/panic.c:389
Inline: False
Direct callers:
  - kernel/hung_task.c:watchdog
  - mm/slub.c:slab_bug
  - lib/dump_stack.c:dump_stack_print_info
```
**Symbols:**

```
ffffffff810a2940-ffffffff810a29d3: print_tainted (STB_GLOBAL)
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
