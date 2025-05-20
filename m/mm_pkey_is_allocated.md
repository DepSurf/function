# Function: <code>mm_pkey_is_allocated</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff811f56e1)
Location: arch/x86/include/asm/pkeys.h:47
Inline: True
Inline callers:
  - mm/mprotect.c:SyS_pkey_free
  - mm/mprotect.c:SyS_pkey_alloc
  - mm/mprotect.c:do_mprotect_pkey
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
In mm/mprotect.c (ffffffff812004c9)
Location: arch/x86/include/asm/pkeys.h:47
Inline: True
Inline callers:
  - mm/mprotect.c:SyS_pkey_free
  - mm/mprotect.c:SyS_pkey_alloc
  - mm/mprotect.c:do_mprotect_pkey
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
In mm/mprotect.c (ffffffff81218c69)
Location: arch/x86/include/asm/pkeys.h:48
Inline: True
Inline callers:
  - mm/mprotect.c:SyS_pkey_free
  - mm/mprotect.c:SyS_pkey_alloc
  - mm/mprotect.c:do_mprotect_pkey
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
In mm/mprotect.c (ffffffff81239752)
Location: arch/x86/include/asm/pkeys.h:55
Inline: True
Inline callers:
  - mm/mprotect.c:__ia32_sys_pkey_free
  - mm/mprotect.c:__x64_sys_pkey_free
  - mm/mprotect.c:__ia32_sys_pkey_alloc
  - mm/mprotect.c:__x64_sys_pkey_alloc
  - mm/mprotect.c:do_mprotect_pkey
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
In mm/mprotect.c (ffffffff8124ddb2)
Location: arch/x86/include/asm/pkeys.h:55
Inline: True
Inline callers:
  - mm/mprotect.c:__ia32_sys_pkey_free
  - mm/mprotect.c:__ia32_sys_pkey_free
  - mm/mprotect.c:__x64_sys_pkey_free
  - mm/mprotect.c:__x64_sys_pkey_free
  - mm/mprotect.c:__ia32_sys_pkey_alloc
  - mm/mprotect.c:__ia32_sys_pkey_alloc
  - mm/mprotect.c:__x64_sys_pkey_alloc
  - mm/mprotect.c:__x64_sys_pkey_alloc
  - mm/mprotect.c:do_mprotect_pkey
  - mm/mprotect.c:do_mprotect_pkey
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
In mm/mprotect.c (ffffffff812601c2)
Location: arch/x86/include/asm/pkeys.h:55
Inline: True
Inline callers:
  - mm/mprotect.c:__ia32_sys_pkey_free
  - mm/mprotect.c:__ia32_sys_pkey_free
  - mm/mprotect.c:__x64_sys_pkey_free
  - mm/mprotect.c:__x64_sys_pkey_free
  - mm/mprotect.c:__ia32_sys_pkey_alloc
  - mm/mprotect.c:__ia32_sys_pkey_alloc
  - mm/mprotect.c:__x64_sys_pkey_alloc
  - mm/mprotect.c:__x64_sys_pkey_alloc
  - mm/mprotect.c:do_mprotect_pkey
  - mm/mprotect.c:do_mprotect_pkey
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
In mm/mprotect.c (ffffffff8126e2d2)
Location: arch/x86/include/asm/pkeys.h:55
Inline: True
Inline callers:
  - mm/mprotect.c:__ia32_sys_pkey_free
  - mm/mprotect.c:__ia32_sys_pkey_free
  - mm/mprotect.c:__x64_sys_pkey_free
  - mm/mprotect.c:__x64_sys_pkey_free
  - mm/mprotect.c:__ia32_sys_pkey_alloc
  - mm/mprotect.c:__ia32_sys_pkey_alloc
  - mm/mprotect.c:__x64_sys_pkey_alloc
  - mm/mprotect.c:__x64_sys_pkey_alloc
  - mm/mprotect.c:do_mprotect_pkey
  - mm/mprotect.c:do_mprotect_pkey
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
In mm/mprotect.c (ffffffff8129e212)
Location: arch/x86/include/asm/pkeys.h:60
Inline: True
Inline callers:
  - mm/mprotect.c:__ia32_sys_pkey_free
  - mm/mprotect.c:__ia32_sys_pkey_free
  - mm/mprotect.c:__x64_sys_pkey_free
  - mm/mprotect.c:__x64_sys_pkey_free
  - mm/mprotect.c:__ia32_sys_pkey_alloc
  - mm/mprotect.c:__ia32_sys_pkey_alloc
  - mm/mprotect.c:__x64_sys_pkey_alloc
  - mm/mprotect.c:__x64_sys_pkey_alloc
  - mm/mprotect.c:do_mprotect_pkey
  - mm/mprotect.c:do_mprotect_pkey
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
In mm/mprotect.c (ffffffff812a96b9)
Location: arch/x86/include/asm/pkeys.h:60
Inline: True
Inline callers:
  - mm/mprotect.c:__ia32_sys_pkey_free
  - mm/mprotect.c:__ia32_sys_pkey_free
  - mm/mprotect.c:__x64_sys_pkey_free
  - mm/mprotect.c:__x64_sys_pkey_free
  - mm/mprotect.c:__do_sys_pkey_alloc
  - mm/mprotect.c:__do_sys_pkey_alloc
  - mm/mprotect.c:do_mprotect_pkey
  - mm/mprotect.c:do_mprotect_pkey
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
In mm/mprotect.c (ffffffff812aeb46)
Location: arch/x86/include/asm/pkeys.h:60
Inline: True
Inline callers:
  - mm/mprotect.c:__ia32_sys_pkey_free
  - mm/mprotect.c:__ia32_sys_pkey_free
  - mm/mprotect.c:__x64_sys_pkey_free
  - mm/mprotect.c:__x64_sys_pkey_free
  - mm/mprotect.c:__do_sys_pkey_alloc
  - mm/mprotect.c:__do_sys_pkey_alloc
  - mm/mprotect.c:do_mprotect_pkey
  - mm/mprotect.c:do_mprotect_pkey
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
In mm/mprotect.c (ffffffff812f032a)
Location: arch/x86/include/asm/pkeys.h:58
Inline: True
Inline callers:
  - mm/mprotect.c:__ia32_sys_pkey_free
  - mm/mprotect.c:__ia32_sys_pkey_free
  - mm/mprotect.c:__x64_sys_pkey_free
  - mm/mprotect.c:__x64_sys_pkey_free
  - mm/mprotect.c:__do_sys_pkey_alloc
  - mm/mprotect.c:__do_sys_pkey_alloc
  - mm/mprotect.c:do_mprotect_pkey
  - mm/mprotect.c:do_mprotect_pkey
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
In mm/mprotect.c (ffffffff813536fa)
Location: arch/x86/include/asm/pkeys.h:55
Inline: True
Inline callers:
  - mm/mprotect.c:__ia32_sys_pkey_free
  - mm/mprotect.c:__ia32_sys_pkey_free
  - mm/mprotect.c:__x64_sys_pkey_free
  - mm/mprotect.c:__x64_sys_pkey_free
  - mm/mprotect.c:__do_sys_pkey_alloc
  - mm/mprotect.c:__do_sys_pkey_alloc
  - mm/mprotect.c:do_mprotect_pkey
  - mm/mprotect.c:do_mprotect_pkey
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
In mm/mprotect.c (ffffffff813cdb54)
Location: arch/x86/include/asm/pkeys.h:55
Inline: True
Inline callers:
  - mm/mprotect.c:__ia32_sys_pkey_free
  - mm/mprotect.c:__ia32_sys_pkey_free
  - mm/mprotect.c:__x64_sys_pkey_free
  - mm/mprotect.c:__x64_sys_pkey_free
  - mm/mprotect.c:__do_sys_pkey_alloc
  - mm/mprotect.c:__do_sys_pkey_alloc
  - mm/mprotect.c:do_mprotect_pkey
  - mm/mprotect.c:do_mprotect_pkey
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
In mm/mprotect.c (ffffffff8140239a)
Location: arch/x86/include/asm/pkeys.h:55
Inline: True
Inline callers:
  - mm/mprotect.c:__ia32_sys_pkey_free
  - mm/mprotect.c:__ia32_sys_pkey_free
  - mm/mprotect.c:__x64_sys_pkey_free
  - mm/mprotect.c:__x64_sys_pkey_free
  - mm/mprotect.c:__do_sys_pkey_alloc
  - mm/mprotect.c:__do_sys_pkey_alloc
  - mm/mprotect.c:do_mprotect_pkey
  - mm/mprotect.c:do_mprotect_pkey
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
In mm/mprotect.c (ffffffff8142e9ca)
Location: arch/x86/include/asm/pkeys.h:55
Inline: True
Inline callers:
  - mm/mprotect.c:__ia32_sys_pkey_free
  - mm/mprotect.c:__ia32_sys_pkey_free
  - mm/mprotect.c:__x64_sys_pkey_free
  - mm/mprotect.c:__x64_sys_pkey_free
  - mm/mprotect.c:__do_sys_pkey_alloc
  - mm/mprotect.c:__do_sys_pkey_alloc
  - mm/mprotect.c:do_mprotect_pkey
  - mm/mprotect.c:do_mprotect_pkey
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (0)
Location: include/linux/pkeys.h:21
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (0)
Location: include/linux/pkeys.h:21
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (0)
Location: include/linux/pkeys.h:21
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (0)
Location: include/linux/pkeys.h:21
Inline: True
```
</details>
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
In mm/mprotect.c (ffffffff81266922)
Location: arch/x86/include/asm/pkeys.h:55
Inline: True
Inline callers:
  - mm/mprotect.c:__ia32_sys_pkey_free
  - mm/mprotect.c:__ia32_sys_pkey_free
  - mm/mprotect.c:__x64_sys_pkey_free
  - mm/mprotect.c:__x64_sys_pkey_free
  - mm/mprotect.c:__ia32_sys_pkey_alloc
  - mm/mprotect.c:__ia32_sys_pkey_alloc
  - mm/mprotect.c:__x64_sys_pkey_alloc
  - mm/mprotect.c:__x64_sys_pkey_alloc
  - mm/mprotect.c:do_mprotect_pkey
  - mm/mprotect.c:do_mprotect_pkey
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
In mm/mprotect.c (ffffffff812593d2)
Location: arch/x86/include/asm/pkeys.h:55
Inline: True
Inline callers:
  - mm/mprotect.c:__ia32_sys_pkey_free
  - mm/mprotect.c:__ia32_sys_pkey_free
  - mm/mprotect.c:__x64_sys_pkey_free
  - mm/mprotect.c:__x64_sys_pkey_free
  - mm/mprotect.c:__ia32_sys_pkey_alloc
  - mm/mprotect.c:__ia32_sys_pkey_alloc
  - mm/mprotect.c:__x64_sys_pkey_alloc
  - mm/mprotect.c:__x64_sys_pkey_alloc
  - mm/mprotect.c:do_mprotect_pkey
  - mm/mprotect.c:do_mprotect_pkey
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
In mm/mprotect.c (ffffffff812646c2)
Location: arch/x86/include/asm/pkeys.h:55
Inline: True
Inline callers:
  - mm/mprotect.c:__ia32_sys_pkey_free
  - mm/mprotect.c:__ia32_sys_pkey_free
  - mm/mprotect.c:__x64_sys_pkey_free
  - mm/mprotect.c:__x64_sys_pkey_free
  - mm/mprotect.c:__ia32_sys_pkey_alloc
  - mm/mprotect.c:__ia32_sys_pkey_alloc
  - mm/mprotect.c:__x64_sys_pkey_alloc
  - mm/mprotect.c:__x64_sys_pkey_alloc
  - mm/mprotect.c:do_mprotect_pkey
  - mm/mprotect.c:do_mprotect_pkey
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
In mm/mprotect.c (ffffffff81274082)
Location: arch/x86/include/asm/pkeys.h:55
Inline: True
Inline callers:
  - mm/mprotect.c:__ia32_sys_pkey_free
  - mm/mprotect.c:__ia32_sys_pkey_free
  - mm/mprotect.c:__x64_sys_pkey_free
  - mm/mprotect.c:__x64_sys_pkey_free
  - mm/mprotect.c:__ia32_sys_pkey_alloc
  - mm/mprotect.c:__ia32_sys_pkey_alloc
  - mm/mprotect.c:__x64_sys_pkey_alloc
  - mm/mprotect.c:__x64_sys_pkey_alloc
  - mm/mprotect.c:do_mprotect_pkey
  - mm/mprotect.c:do_mprotect_pkey
```
</details>
</li>
</ul>

## Differences
