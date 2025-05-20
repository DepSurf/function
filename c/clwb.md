# Function: <code>clwb</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8125e152)
Location: arch/x86/include/asm/special_insns.h:204
Inline: True
Inline callers:
  - fs/dax.c:__dax_fault
  - fs/dax.c:dax_do_io
  - fs/dax.c:dax_do_io
  - fs/dax.c:dax_do_io
  - fs/dax.c:dax_zero_page_range
  - fs/dax.c:dax_clear_blocks
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff812869aa)
Location: arch/x86/include/asm/special_insns.h:242
Inline: True
Inline callers:
  - fs/dax.c:__dax_zero_page_range
  - fs/dax.c:dax_do_io
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8129ac17)
Location: arch/x86/include/asm/special_insns.h:221
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_actor
  - fs/dax.c:__dax_zero_page_range
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff818fd726)
Location: arch/x86/include/asm/special_insns.h:225
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:memcpy_flushcache
  - arch/x86/lib/usercopy_64.c:memcpy_flushcache
  - arch/x86/lib/usercopy_64.c:__copy_user_flushcache
  - arch/x86/lib/usercopy_64.c:__copy_user_flushcache
  - arch/x86/lib/usercopy_64.c:__copy_user_flushcache
  - arch/x86/lib/usercopy_64.c:arch_wb_cache_pmem
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff81985216)
Location: arch/x86/include/asm/special_insns.h:226
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:memcpy_flushcache
  - arch/x86/lib/usercopy_64.c:memcpy_flushcache
  - arch/x86/lib/usercopy_64.c:__copy_user_flushcache
  - arch/x86/lib/usercopy_64.c:__copy_user_flushcache
  - arch/x86/lib/usercopy_64.c:__copy_user_flushcache
  - arch/x86/lib/usercopy_64.c:arch_wb_cache_pmem
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff819e15ef)
Location: arch/x86/include/asm/special_insns.h:226
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:memcpy_flushcache
  - arch/x86/lib/usercopy_64.c:memcpy_flushcache
  - arch/x86/lib/usercopy_64.c:__copy_user_flushcache
  - arch/x86/lib/usercopy_64.c:__copy_user_flushcache
  - arch/x86/lib/usercopy_64.c:__copy_user_flushcache
  - arch/x86/lib/usercopy_64.c:arch_wb_cache_pmem
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
In arch/x86/lib/usercopy_64.c (ffffffff81a1c59f)
Location: arch/x86/include/asm/special_insns.h:226
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:__memcpy_flushcache
  - arch/x86/lib/usercopy_64.c:__memcpy_flushcache
  - arch/x86/lib/usercopy_64.c:__copy_user_flushcache
  - arch/x86/lib/usercopy_64.c:__copy_user_flushcache
  - arch/x86/lib/usercopy_64.c:__copy_user_flushcache
  - arch/x86/lib/usercopy_64.c:arch_wb_cache_pmem
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
In arch/x86/lib/usercopy_64.c (ffffffff81a8c253)
Location: arch/x86/include/asm/special_insns.h:235
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:__memcpy_flushcache
  - arch/x86/lib/usercopy_64.c:__memcpy_flushcache
  - arch/x86/lib/usercopy_64.c:__copy_user_flushcache
  - arch/x86/lib/usercopy_64.c:__copy_user_flushcache
  - arch/x86/lib/usercopy_64.c:__copy_user_flushcache
  - arch/x86/lib/usercopy_64.c:arch_wb_cache_pmem
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
In arch/x86/lib/usercopy_64.c (ffffffff81ac3513)
Location: arch/x86/include/asm/special_insns.h:211
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:__memcpy_flushcache
  - arch/x86/lib/usercopy_64.c:__memcpy_flushcache
  - arch/x86/lib/usercopy_64.c:__copy_user_flushcache
  - arch/x86/lib/usercopy_64.c:__copy_user_flushcache
  - arch/x86/lib/usercopy_64.c:__copy_user_flushcache
  - arch/x86/lib/usercopy_64.c:arch_wb_cache_pmem
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff815ff9d6)
Location: arch/x86/include/asm/special_insns.h:221
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:clean_cache_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff81624906)
Location: arch/x86/include/asm/special_insns.h:223
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:clean_cache_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff816082d6)
Location: arch/x86/include/asm/special_insns.h:223
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:clean_cache_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff81676f16)
Location: arch/x86/include/asm/special_insns.h:211
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:clean_cache_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff81791ed6)
Location: arch/x86/include/asm/special_insns.h:212
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:clean_cache_range
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff8204fca6)
Location: arch/x86/include/asm/special_insns.h:212
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:clean_cache_range
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff820ce1f6)
Location: arch/x86/include/asm/special_insns.h:191
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:clean_cache_range
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff821a8a06)
Location: arch/x86/include/asm/special_insns.h:191
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:clean_cache_range
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
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff81a62363)
Location: arch/x86/include/asm/special_insns.h:211
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:__memcpy_flushcache
  - arch/x86/lib/usercopy_64.c:__memcpy_flushcache
  - arch/x86/lib/usercopy_64.c:__copy_user_flushcache
  - arch/x86/lib/usercopy_64.c:__copy_user_flushcache
  - arch/x86/lib/usercopy_64.c:__copy_user_flushcache
  - arch/x86/lib/usercopy_64.c:arch_wb_cache_pmem
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
In arch/x86/lib/usercopy_64.c (ffffffff81a1f3d3)
Location: arch/x86/include/asm/special_insns.h:211
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:__memcpy_flushcache
  - arch/x86/lib/usercopy_64.c:__memcpy_flushcache
  - arch/x86/lib/usercopy_64.c:__copy_user_flushcache
  - arch/x86/lib/usercopy_64.c:__copy_user_flushcache
  - arch/x86/lib/usercopy_64.c:__copy_user_flushcache
  - arch/x86/lib/usercopy_64.c:arch_wb_cache_pmem
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
In arch/x86/lib/usercopy_64.c (ffffffff81ace753)
Location: arch/x86/include/asm/special_insns.h:211
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:__memcpy_flushcache
  - arch/x86/lib/usercopy_64.c:__memcpy_flushcache
  - arch/x86/lib/usercopy_64.c:__copy_user_flushcache
  - arch/x86/lib/usercopy_64.c:__copy_user_flushcache
  - arch/x86/lib/usercopy_64.c:__copy_user_flushcache
  - arch/x86/lib/usercopy_64.c:arch_wb_cache_pmem
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
In arch/x86/lib/usercopy_64.c (ffffffff81adac63)
Location: arch/x86/include/asm/special_insns.h:211
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:__memcpy_flushcache
  - arch/x86/lib/usercopy_64.c:__memcpy_flushcache
  - arch/x86/lib/usercopy_64.c:__copy_user_flushcache
  - arch/x86/lib/usercopy_64.c:__copy_user_flushcache
  - arch/x86/lib/usercopy_64.c:__copy_user_flushcache
  - arch/x86/lib/usercopy_64.c:arch_wb_cache_pmem
```
</details>
</li>
</ul>

## Differences
