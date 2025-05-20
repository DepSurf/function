# Function: <code>syscall_32_enter</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff81c34c60)
Location: arch/x86/entry/common.c:61
Inline: True
Inline callers:
  - arch/x86/entry/common.c:__do_fast_syscall_32
  - arch/x86/entry/common.c:do_int80_syscall_32
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
In arch/x86/entry/common.c (ffffffff81c27050)
Location: arch/x86/entry/common.c:62
Inline: True
Inline callers:
  - arch/x86/entry/common.c:__do_fast_syscall_32
  - arch/x86/entry/common.c:do_int80_syscall_32
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
In arch/x86/entry/common.c (ffffffff81d45080)
Location: arch/x86/entry/common.c:91
Inline: True
Inline callers:
  - arch/x86/entry/common.c:__do_fast_syscall_32
  - arch/x86/entry/common.c:do_int80_syscall_32
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
In arch/x86/entry/common.c (ffffffff81f13020)
Location: arch/x86/entry/common.c:91
Inline: True
Inline callers:
  - arch/x86/entry/common.c:__do_fast_syscall_32
  - arch/x86/entry/common.c:do_int80_syscall_32
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
In arch/x86/entry/common.c (ffffffff820ba040)
Location: arch/x86/entry/common.c:91
Inline: True
Inline callers:
  - arch/x86/entry/common.c:__do_fast_syscall_32
  - arch/x86/entry/common.c:do_int80_syscall_32
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
In arch/x86/entry/common.c (ffffffff82139850)
Location: arch/x86/entry/common.c:91
Inline: True
Inline callers:
  - arch/x86/entry/common.c:__do_fast_syscall_32
  - arch/x86/entry/common.c:do_int80_syscall_32
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
In arch/x86/entry/common.c (ffffffff8221b5f0)
Location: arch/x86/entry/common.c:134
Inline: True
Inline callers:
  - arch/x86/entry/common.c:__do_fast_syscall_32
  - arch/x86/entry/common.c:do_int80_emulation
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
