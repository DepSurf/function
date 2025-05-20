# Function: <code>kprobe_page_fault</code>

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
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8107f82e)
Location: include/linux/kprobes.h:462
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
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
In arch/x86/mm/fault.c (ffffffff810808be)
Location: include/linux/kprobes.h:462
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
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
In arch/x86/mm/fault.c (ffffffff8108789e)
Location: include/linux/kprobes.h:471
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:do_kern_addr_fault
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
In arch/x86/mm/fault.c (ffffffff81087ffa)
Location: include/linux/kprobes.h:511
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
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
In arch/x86/mm/fault.c (ffffffff81088aba)
Location: include/linux/kprobes.h:511
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
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
In arch/x86/mm/fault.c (ffffffff81097eea)
Location: include/linux/kprobes.h:507
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
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
In arch/x86/mm/fault.c (ffffffff810aab2a)
Location: include/linux/kprobes.h:581
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
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
In arch/x86/mm/fault.c (ffffffff810c481a)
Location: include/linux/kprobes.h:584
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
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
In arch/x86/mm/fault.c (ffffffff810c801a)
Location: include/linux/kprobes.h:584
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
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
In arch/x86/mm/fault.c (ffffffff810d04ee)
Location: include/linux/kprobes.h:578
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
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
In arch/arm64/mm/fault.c (ffff800010da8ff0)
Location: include/linux/kprobes.h:462
Inline: True
Inline callers:
  - arch/arm64/mm/fault.c:do_page_fault
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
In arch/arm/mm/fault.c (c0e9f840)
Location: include/linux/kprobes.h:462
Inline: True
Inline callers:
  - arch/arm/mm/fault.c:do_page_fault
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
In arch/powerpc/mm/fault.c (c0000000000860ec)
Location: include/linux/kprobes.h:462
Inline: True
Inline callers:
  - arch/powerpc/mm/fault.c:__do_page_fault
```
</details>
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
In arch/x86/mm/fault.c (ffffffff8107f8be)
Location: include/linux/kprobes.h:462
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
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
In arch/x86/mm/fault.c (ffffffff8106e92e)
Location: include/linux/kprobes.h:462
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
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
In arch/x86/mm/fault.c (ffffffff8107f86e)
Location: include/linux/kprobes.h:462
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
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
In arch/x86/mm/fault.c (ffffffff8108195e)
Location: include/linux/kprobes.h:462
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
```
</details>
</li>
</ul>

## Differences
