# Function: <code>audit_set_context</code>

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
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8108c605)
Location: include/linux/audit.h:240
Inline: True
```
```
In kernel/auditsc.c (ffffffff8115738b)
Location: include/linux/audit.h:240
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_free
  - kernel/auditsc.c:audit_alloc
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
In kernel/fork.c (ffffffff8109401f)
Location: include/linux/audit.h:239
Inline: True
```
```
In kernel/auditsc.c (ffffffff8116405f)
Location: include/linux/audit.h:239
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_free
  - kernel/auditsc.c:audit_alloc
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
In kernel/fork.c (ffffffff810987b7)
Location: include/linux/audit.h:282
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/auditsc.c (ffffffff81170c64)
Location: include/linux/audit.h:282
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_free
  - kernel/auditsc.c:audit_alloc
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
In kernel/fork.c (ffffffff8109ed72)
Location: include/linux/audit.h:282
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/auditsc.c (ffffffff8117cae4)
Location: include/linux/audit.h:282
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_free
  - kernel/auditsc.c:audit_alloc
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
In kernel/fork.c (ffffffff810a63a1)
Location: include/linux/audit.h:299
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/auditsc.c (ffffffff8118fdf6)
Location: include/linux/audit.h:299
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_free
  - kernel/auditsc.c:audit_alloc
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
In kernel/fork.c (ffffffff810a1cb6)
Location: include/linux/audit.h:316
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/auditsc.c (ffffffff8118d076)
Location: include/linux/audit.h:316
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_free
  - kernel/auditsc.c:audit_alloc
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
In kernel/fork.c (ffffffff810a2b13)
Location: include/linux/audit.h:316
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/auditsc.c (ffffffff8118ded6)
Location: include/linux/audit.h:316
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_free
  - kernel/auditsc.c:audit_alloc
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
In kernel/fork.c (ffffffff810b4238)
Location: include/linux/audit.h:316
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/auditsc.c (ffffffff811b6cd6)
Location: include/linux/audit.h:316
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_free
  - kernel/auditsc.c:audit_alloc
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
In kernel/fork.c (ffffffff810ca59b)
Location: include/linux/audit.h:327
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/auditsc.c (ffffffff811e9ab6)
Location: include/linux/audit.h:327
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_free
  - kernel/auditsc.c:audit_alloc
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
In kernel/fork.c (ffffffff810e7c04)
Location: include/linux/audit.h:324
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/auditsc.c (ffffffff8122fafe)
Location: include/linux/audit.h:324
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_free
  - kernel/auditsc.c:audit_alloc
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
In kernel/fork.c (ffffffff810f3824)
Location: include/linux/audit.h:323
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/auditsc.c (ffffffff812465ee)
Location: include/linux/audit.h:323
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_free
  - kernel/auditsc.c:audit_alloc
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
In kernel/fork.c (ffffffff810fcbf5)
Location: include/linux/audit.h:322
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/auditsc.c (ffffffff8126049e)
Location: include/linux/audit.h:322
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_free
  - kernel/auditsc.c:audit_alloc
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
In kernel/fork.c (ffff8000100f38a4)
Location: include/linux/audit.h:282
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/auditsc.c (ffff8000101f19cc)
Location: include/linux/audit.h:282
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_free
  - kernel/auditsc.c:audit_alloc
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
In kernel/fork.c (c035203c)
Location: include/linux/audit.h:282
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/auditsc.c (c0431e74)
Location: include/linux/audit.h:282
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_free
  - kernel/auditsc.c:audit_alloc
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
In kernel/fork.c (c000000000139670)
Location: include/linux/audit.h:282
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/auditsc.c (c000000000265cb8)
Location: include/linux/audit.h:282
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_free
  - kernel/auditsc.c:audit_alloc
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
In kernel/fork.c (ffffffe0000c000e)
Location: include/linux/audit.h:282
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/auditsc.c (ffffffe0001652cc)
Location: include/linux/audit.h:282
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_free
  - kernel/auditsc.c:audit_alloc
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
In kernel/fork.c (ffffffff81098692)
Location: include/linux/audit.h:282
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/auditsc.c (ffffffff81175104)
Location: include/linux/audit.h:282
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_free
  - kernel/auditsc.c:audit_alloc
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
In kernel/fork.c (ffffffff810870fc)
Location: include/linux/audit.h:282
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/auditsc.c (ffffffff811682a4)
Location: include/linux/audit.h:282
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_free
  - kernel/auditsc.c:audit_alloc
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
In kernel/fork.c (ffffffff81098642)
Location: include/linux/audit.h:282
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/auditsc.c (ffffffff81172ed4)
Location: include/linux/audit.h:282
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_free
  - kernel/auditsc.c:audit_alloc
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
In kernel/fork.c (ffffffff810a0269)
Location: include/linux/audit.h:282
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/auditsc.c (ffffffff81180744)
Location: include/linux/audit.h:282
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_free
  - kernel/auditsc.c:audit_alloc
```
</details>
</li>
</ul>

## Differences
