# Function: <code>check_data_rlimit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff81093075)
Location: include/linux/mm.h:1902
Inline: True
```
```
In mm/mmap.c (ffffffff811c6cf1)
Location: include/linux/mm.h:1902
Inline: True
Inline callers:
  - mm/mmap.c:SyS_brk
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff81096202)
Location: include/linux/mm.h:2020
Inline: True
```
```
In mm/mmap.c (ffffffff811e322d)
Location: include/linux/mm.h:2020
Inline: True
Inline callers:
  - mm/mmap.c:SyS_brk
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff8109b1c6)
Location: include/linux/mm.h:2004
Inline: True
```
```
In mm/mmap.c (ffffffff811f320d)
Location: include/linux/mm.h:2004
Inline: True
Inline callers:
  - mm/mmap.c:SyS_brk
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff81097fe7)
Location: include/linux/mm.h:2077
Inline: True
```
```
In mm/mmap.c (ffffffff811fe2a8)
Location: include/linux/mm.h:2077
Inline: True
Inline callers:
  - mm/mmap.c:SyS_brk
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff8109ecc3)
Location: include/linux/mm.h:2186
Inline: True
```
```
In mm/mmap.c (ffffffff81216858)
Location: include/linux/mm.h:2186
Inline: True
Inline callers:
  - mm/mmap.c:SyS_brk
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810a458d)
Location: include/linux/mm.h:2275
Inline: True
```
```
In mm/mmap.c (ffffffff81237628)
Location: include/linux/mm.h:2275
Inline: True
Inline callers:
  - mm/mmap.c:__ia32_sys_brk
  - mm/mmap.c:__x64_sys_brk
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810ad3ed)
Location: include/linux/mm.h:2346
Inline: True
```
```
In mm/mmap.c (ffffffff8124af06)
Location: include/linux/mm.h:2346
Inline: True
Inline callers:
  - mm/mmap.c:__ia32_sys_brk
  - mm/mmap.c:__x64_sys_brk
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810b2c1f)
Location: include/linux/mm.h:2341
Inline: True
```
```
In mm/mmap.c (ffffffff8125d2d4)
Location: include/linux/mm.h:2341
Inline: True
Inline callers:
  - mm/mmap.c:__ia32_sys_brk
  - mm/mmap.c:__x64_sys_brk
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810b920f)
Location: include/linux/mm.h:2313
Inline: True
```
```
In mm/mmap.c (ffffffff8126baa4)
Location: include/linux/mm.h:2313
Inline: True
Inline callers:
  - mm/mmap.c:__ia32_sys_brk
  - mm/mmap.c:__x64_sys_brk
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810c0e6c)
Location: include/linux/mm.h:2560
Inline: True
Inline callers:
  - kernel/sys.c:validate_prctl_map_addr
```
```
In mm/mmap.c (ffffffff8129b8de)
Location: include/linux/mm.h:2560
Inline: True
Inline callers:
  - mm/mmap.c:__do_sys_brk
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810bbfcc)
Location: include/linux/mm.h:2570
Inline: True
Inline callers:
  - kernel/sys.c:validate_prctl_map_addr
```
```
In mm/mmap.c (ffffffff812a6b1b)
Location: include/linux/mm.h:2570
Inline: True
Inline callers:
  - mm/mmap.c:__do_sys_brk
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810bd872)
Location: include/linux/mm.h:2566
Inline: True
Inline callers:
  - kernel/sys.c:validate_prctl_map_addr
```
```
In mm/mmap.c (ffffffff812acac8)
Location: include/linux/mm.h:2566
Inline: True
Inline callers:
  - mm/mmap.c:__do_sys_brk
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810d0284)
Location: include/linux/mm.h:2595
Inline: True
Inline callers:
  - kernel/sys.c:validate_prctl_map_addr
```
```
In mm/mmap.c (ffffffff812ee228)
Location: include/linux/mm.h:2595
Inline: True
Inline callers:
  - mm/mmap.c:__do_sys_brk
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810e6c76)
Location: include/linux/mm.h:2673
Inline: True
Inline callers:
  - kernel/sys.c:validate_prctl_map_addr
```
```
In mm/mmap.c (ffffffff81351617)
Location: include/linux/mm.h:2673
Inline: True
Inline callers:
  - mm/mmap.c:__do_sys_brk
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
In kernel/sys.c (ffffffff8110aae6)
Location: include/linux/mm.h:2842
Inline: True
Inline callers:
  - kernel/sys.c:validate_prctl_map_addr
```
```
In mm/mmap.c (ffffffff813caaff)
Location: include/linux/mm.h:2842
Inline: True
Inline callers:
  - mm/mmap.c:__do_sys_brk
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
In kernel/sys.c (ffffffff81116ca6)
Location: include/linux/mm.h:3150
Inline: True
Inline callers:
  - kernel/sys.c:validate_prctl_map_addr
```
```
In mm/mmap.c (ffffffff813ff3f0)
Location: include/linux/mm.h:3150
Inline: True
Inline callers:
  - mm/mmap.c:__do_sys_brk
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
In kernel/sys.c (ffffffff81120696)
Location: include/linux/mm.h:3327
Inline: True
Inline callers:
  - kernel/sys.c:validate_prctl_map_addr
```
```
In mm/mmap.c (ffffffff8142b910)
Location: include/linux/mm.h:3327
Inline: True
Inline callers:
  - mm/mmap.c:__do_sys_brk
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffff8000101146b8)
Location: include/linux/mm.h:2313
Inline: True
```
```
In mm/mmap.c (ffff8000103031e4)
Location: include/linux/mm.h:2313
Inline: True
Inline callers:
  - mm/mmap.c:__arm64_sys_brk
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sys.c (c036ae24)
Location: include/linux/mm.h:2313
Inline: True
```
```
In mm/mmap.c (c0521884)
Location: include/linux/mm.h:2313
Inline: True
Inline callers:
  - mm/mmap.c:__se_sys_brk
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sys.c (c00000000015d424)
Location: include/linux/mm.h:2313
Inline: True
```
```
In mm/mmap.c (c0000000003cfb50)
Location: include/linux/mm.h:2313
Inline: True
Inline callers:
  - mm/mmap.c:__se_sys_brk
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffe0000d2342)
Location: include/linux/mm.h:2313
Inline: True
```
```
In mm/mmap.c (ffffffe00020fdf6)
Location: include/linux/mm.h:2313
Inline: True
Inline callers:
  - mm/mmap.c:__se_sys_brk
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810b357f)
Location: include/linux/mm.h:2313
Inline: True
```
```
In mm/mmap.c (ffffffff812640f4)
Location: include/linux/mm.h:2313
Inline: True
Inline callers:
  - mm/mmap.c:__ia32_sys_brk
  - mm/mmap.c:__x64_sys_brk
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810a1eaf)
Location: include/linux/mm.h:2313
Inline: True
```
```
In mm/mmap.c (ffffffff81256514)
Location: include/linux/mm.h:2313
Inline: True
Inline callers:
  - mm/mmap.c:__ia32_sys_brk
  - mm/mmap.c:__x64_sys_brk
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810b2adf)
Location: include/linux/mm.h:2313
Inline: True
```
```
In mm/mmap.c (ffffffff81261e94)
Location: include/linux/mm.h:2313
Inline: True
Inline callers:
  - mm/mmap.c:__ia32_sys_brk
  - mm/mmap.c:__x64_sys_brk
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810bb0df)
Location: include/linux/mm.h:2313
Inline: True
```
```
In mm/mmap.c (ffffffff81271854)
Location: include/linux/mm.h:2313
Inline: True
Inline callers:
  - mm/mmap.c:__ia32_sys_brk
  - mm/mmap.c:__x64_sys_brk
```
</details>
</li>
</ul>

## Differences
