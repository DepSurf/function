# Function: <code>xen_raw_console_write</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void xen_raw_console_write(const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_xen.c (ffffffff814ff800)
Location: drivers/tty/hvc/hvc_xen.c:636
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_start_kernel
  - arch/x86/xen/enlighten.c:xen_start_kernel
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/mmu.c:xen_pt_check_e820
  - arch/x86/xen/mmu.c:xen_relocate_p2m
  - drivers/tty/hvc/hvc_xen.c:xen_raw_printk
```
**Symbols:**

```
ffffffff814ff800-ffffffff814ff91c: xen_raw_console_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void xen_raw_console_write(const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_xen.c (ffffffff81550460)
Location: drivers/tty/hvc/hvc_xen.c:669
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_start_kernel
  - arch/x86/xen/enlighten.c:xen_start_kernel
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/mmu.c:xen_relocate_p2m
  - arch/x86/xen/mmu.c:xen_pt_check_e820
  - drivers/tty/hvc/hvc_xen.c:xen_raw_printk
```
**Symbols:**

```
ffffffff81550460-ffffffff8155056b: xen_raw_console_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void xen_raw_console_write(const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_xen.c (ffffffff8157cce0)
Location: drivers/tty/hvc/hvc_xen.c:669
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_start_kernel
  - arch/x86/xen/enlighten.c:xen_start_kernel
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/mmu.c:xen_relocate_p2m
  - arch/x86/xen/mmu.c:xen_pt_check_e820
  - drivers/tty/hvc/hvc_xen.c:xen_raw_printk
```
**Symbols:**

```
ffffffff8157cce0-ffffffff8157cdeb: xen_raw_console_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void xen_raw_console_write(const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_xen.c (ffffffff81590f50)
Location: drivers/tty/hvc/hvc_xen.c:669
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_pt_check_e820
  - drivers/tty/hvc/hvc_xen.c:xen_raw_printk
```
**Symbols:**

```
ffffffff81590f50-ffffffff81591052: xen_raw_console_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void xen_raw_console_write(const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_xen.c (ffffffff815f5aa0)
Location: drivers/tty/hvc/hvc_xen.c:656
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_pt_check_e820
  - drivers/tty/hvc/hvc_xen.c:xen_raw_printk
```
**Symbols:**

```
ffffffff815f5aa0-ffffffff815f5aef: xen_raw_console_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void xen_raw_console_write(const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_xen.c (ffffffff8162eb90)
Location: drivers/tty/hvc/hvc_xen.c:656
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_pt_check_e820
  - drivers/tty/hvc/hvc_xen.c:xen_raw_printk
```
**Symbols:**

```
ffffffff8162eb90-ffffffff8162ec92: xen_raw_console_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void xen_raw_console_write(const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_xen.c (ffffffff8164cdd0)
Location: drivers/tty/hvc/hvc_xen.c:656
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_pt_check_e820
  - drivers/tty/hvc/hvc_xen.c:xen_raw_printk
```
**Symbols:**

```
ffffffff8164cdd0-ffffffff8164ce1f: xen_raw_console_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void xen_raw_console_write(const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_xen.c (ffffffff816818f0)
Location: drivers/tty/hvc/hvc_xen.c:656
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_pt_check_e820
  - drivers/tty/hvc/hvc_xen.c:xen_raw_printk
```
**Symbols:**

```
ffffffff816818f0-ffffffff81681942: xen_raw_console_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void xen_raw_console_write(const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_xen.c (ffffffff816a3fa0)
Location: drivers/tty/hvc/hvc_xen.c:656
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_pt_check_e820
  - drivers/tty/hvc/hvc_xen.c:xen_raw_printk
```
**Symbols:**

```
ffffffff816a3fa0-ffffffff816a3ff2: xen_raw_console_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void xen_raw_console_write(const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_xen.c (ffffffff81756790)
Location: drivers/tty/hvc/hvc_xen.c:656
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_pt_check_e820
  - drivers/tty/hvc/hvc_xen.c:xen_raw_printk
```
**Symbols:**

```
ffffffff81756790-ffffffff817567e6: xen_raw_console_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void xen_raw_console_write(const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_xen.c (ffffffff81771a00)
Location: drivers/tty/hvc/hvc_xen.c:656
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_pt_check_e820
  - drivers/tty/hvc/hvc_xen.c:xen_raw_printk
```
**Symbols:**

```
ffffffff81771a00-ffffffff81771a56: xen_raw_console_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void xen_raw_console_write(const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_xen.c (ffffffff817554c0)
Location: drivers/tty/hvc/hvc_xen.c:656
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_pt_check_e820
  - drivers/tty/hvc/hvc_xen.c:xen_raw_printk
```
**Symbols:**

```
ffffffff817554c0-ffffffff81755518: xen_raw_console_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void xen_raw_console_write(const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_xen.c (ffffffff817d8bf0)
Location: drivers/tty/hvc/hvc_xen.c:688
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_pt_check_e820
  - drivers/tty/hvc/hvc_xen.c:xen_raw_printk
```
**Symbols:**

```
ffffffff817d8bf0-ffffffff817d8c48: xen_raw_console_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void xen_raw_console_write(const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_xen.c (ffffffff81916fa0)
Location: drivers/tty/hvc/hvc_xen.c:689
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_pt_check_e820
  - drivers/tty/hvc/hvc_xen.c:xen_raw_printk
```
**Symbols:**

```
ffffffff81916fa0-ffffffff81917025: xen_raw_console_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void xen_raw_console_write(const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_xen.c (ffffffff81a723b0)
Location: drivers/tty/hvc/hvc_xen.c:701
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_pt_check_e820
  - drivers/tty/hvc/hvc_xen.c:xen_raw_printk
```
**Symbols:**

```
ffffffff81a723b0-ffffffff81a72435: xen_raw_console_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void xen_raw_console_write(const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_xen.c (ffffffff81abcc70)
Location: drivers/tty/hvc/hvc_xen.c:716
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_pt_check_e820
  - drivers/tty/hvc/hvc_xen.c:xen_raw_printk
```
**Symbols:**

```
ffffffff81abcc70-ffffffff81abccf5: xen_raw_console_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void xen_raw_console_write(const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_xen.c (ffffffff81b0fa60)
Location: drivers/tty/hvc/hvc_xen.c:734
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_pt_check_e820
  - drivers/tty/hvc/hvc_xen.c:xen_raw_printk
```
**Symbols:**

```
ffffffff81b0fa60-ffffffff81b0fae5: xen_raw_console_write (STB_GLOBAL)
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
void xen_raw_console_write(const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_xen.c (ffff80001087c358)
Location: drivers/tty/hvc/hvc_xen.c:656
Inline: False
Direct callers:
  - drivers/tty/hvc/hvc_xen.c:xen_raw_printk
```
**Symbols:**

```
ffff80001087c358-ffff80001087c3ac: xen_raw_console_write (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void xen_raw_console_write(const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_xen.c (ffffffff81669a00)
Location: drivers/tty/hvc/hvc_xen.c:656
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_pt_check_e820
  - drivers/tty/hvc/hvc_xen.c:xen_raw_printk
```
**Symbols:**

```
ffffffff81669a00-ffffffff81669a52: xen_raw_console_write (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void xen_raw_console_write(const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_xen.c (ffffffff81697de0)
Location: drivers/tty/hvc/hvc_xen.c:656
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_pt_check_e820
  - drivers/tty/hvc/hvc_xen.c:xen_raw_printk
```
**Symbols:**

```
ffffffff81697de0-ffffffff81697e32: xen_raw_console_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void xen_raw_console_write(const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_xen.c (ffffffff816b2360)
Location: drivers/tty/hvc/hvc_xen.c:656
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_pt_check_e820
  - drivers/tty/hvc/hvc_xen.c:xen_raw_printk
```
**Symbols:**

```
ffffffff816b2360-ffffffff816b23b2: xen_raw_console_write (STB_GLOBAL)
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
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
