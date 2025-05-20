# Function: <code>syscall_rollback</code>

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
In kernel/seccomp.c (ffffffff8113be16)
Location: arch/x86/include/asm/syscall.h:48
Inline: True
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
In kernel/seccomp.c (ffffffff81143c6a)
Location: arch/x86/include/asm/syscall.h:48
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
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
In kernel/seccomp.c (ffffffff8114db3a)
Location: arch/x86/include/asm/syscall.h:48
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
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
In kernel/seccomp.c (ffffffff8115028f)
Location: arch/x86/include/asm/syscall.h:48
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
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
In kernel/seccomp.c (ffffffff8115cdd2)
Location: arch/x86/include/asm/syscall.h:48
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
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
In kernel/seccomp.c (ffffffff8116b792)
Location: arch/x86/include/asm/syscall.h:52
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
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
In kernel/seccomp.c (ffffffff81178f2c)
Location: arch/x86/include/asm/syscall.h:52
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
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
In kernel/seccomp.c (ffffffff81185cd3)
Location: arch/x86/include/asm/syscall.h:49
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
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
In kernel/seccomp.c (ffffffff81191c10)
Location: arch/x86/include/asm/syscall.h:53
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
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
In kernel/seccomp.c (ffffffff811a6b0e)
Location: arch/x86/include/asm/syscall.h:44
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
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
In kernel/entry/syscall_user_dispatch.c (ffffffff8113bc9c)
Location: arch/x86/include/asm/syscall.h:44
Inline: True
Inline callers:
  - kernel/entry/syscall_user_dispatch.c:syscall_user_dispatch
```
```
In kernel/seccomp.c (ffffffff811a3fdd)
Location: arch/x86/include/asm/syscall.h:44
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
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
In kernel/entry/syscall_user_dispatch.c (ffffffff8113cf8c)
Location: arch/x86/include/asm/syscall.h:44
Inline: True
Inline callers:
  - kernel/entry/syscall_user_dispatch.c:syscall_user_dispatch
```
```
In kernel/seccomp.c (ffffffff811a4a81)
Location: arch/x86/include/asm/syscall.h:44
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
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
In kernel/entry/syscall_user_dispatch.c (ffffffff811600ac)
Location: arch/x86/include/asm/syscall.h:43
Inline: True
Inline callers:
  - kernel/entry/syscall_user_dispatch.c:syscall_user_dispatch
```
```
In kernel/seccomp.c (ffffffff811cdfd0)
Location: arch/x86/include/asm/syscall.h:43
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
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
In kernel/entry/syscall_user_dispatch.c (ffffffff8118a586)
Location: arch/x86/include/asm/syscall.h:43
Inline: True
Inline callers:
  - kernel/entry/syscall_user_dispatch.c:syscall_user_dispatch
```
```
In kernel/seccomp.c (ffffffff81202329)
Location: arch/x86/include/asm/syscall.h:43
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
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
In kernel/entry/syscall_user_dispatch.c (ffffffff811c6b26)
Location: arch/x86/include/asm/syscall.h:43
Inline: True
Inline callers:
  - kernel/entry/syscall_user_dispatch.c:syscall_user_dispatch
```
```
In kernel/seccomp.c (ffffffff8124a217)
Location: arch/x86/include/asm/syscall.h:43
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
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
In kernel/entry/syscall_user_dispatch.c (ffffffff811d9846)
Location: arch/x86/include/asm/syscall.h:43
Inline: True
Inline callers:
  - kernel/entry/syscall_user_dispatch.c:syscall_user_dispatch
```
```
In kernel/seccomp.c (ffffffff812614f4)
Location: arch/x86/include/asm/syscall.h:43
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
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
In kernel/entry/syscall_user_dispatch.c (ffffffff811ef4f6)
Location: arch/x86/include/asm/syscall.h:41
Inline: True
Inline callers:
  - kernel/entry/syscall_user_dispatch.c:syscall_user_dispatch
```
```
In kernel/seccomp.c (ffffffff8127b6f4)
Location: arch/x86/include/asm/syscall.h:41
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
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
In kernel/seccomp.c (ffff8000102094f4)
Location: arch/arm64/include/asm/syscall.h:26
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
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
In kernel/seccomp.c (c0448294)
Location: arch/arm/include/asm/syscall.h:28
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
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
In kernel/seccomp.c (c0000000002867a4)
Location: arch/powerpc/include/asm/syscall.h:32
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
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
In kernel/seccomp.c (ffffffe00016b57c)
Location: arch/riscv/include/asm/syscall.h:38
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
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
In kernel/seccomp.c (ffffffff8118a230)
Location: arch/x86/include/asm/syscall.h:53
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
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
In kernel/seccomp.c (ffffffff8117d360)
Location: arch/x86/include/asm/syscall.h:53
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
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
In kernel/seccomp.c (ffffffff81188000)
Location: arch/x86/include/asm/syscall.h:53
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
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
In kernel/seccomp.c (ffffffff81195954)
Location: arch/x86/include/asm/syscall.h:53
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
```
</details>
</li>
</ul>

## Differences
