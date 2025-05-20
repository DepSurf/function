# Function: <code>vdso_write_begin</code>

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
In kernel/time/vsyscall.c (ffffffff8113dd05)
Location: include/vdso/helpers.h:30
Inline: True
Inline callers:
  - kernel/time/vsyscall.c:update_vsyscall
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
In kernel/time/vsyscall.c (ffffffff81149895)
Location: include/vdso/helpers.h:30
Inline: True
Inline callers:
  - kernel/time/vsyscall.c:update_vsyscall
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
In kernel/time/vsyscall.c (ffffffff81159805)
Location: include/vdso/helpers.h:30
Inline: True
Inline callers:
  - kernel/time/vsyscall.c:update_vsyscall
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
In kernel/time/vsyscall.c (ffffffff81155a05)
Location: include/vdso/helpers.h:30
Inline: True
Inline callers:
  - kernel/time/vsyscall.c:vdso_update_begin
  - kernel/time/vsyscall.c:update_vsyscall
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
In kernel/time/vsyscall.c (ffffffff81156e45)
Location: include/vdso/helpers.h:30
Inline: True
Inline callers:
  - kernel/time/vsyscall.c:vdso_update_begin
  - kernel/time/vsyscall.c:update_vsyscall
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
In kernel/time/vsyscall.c (ffffffff8117bc25)
Location: include/vdso/helpers.h:30
Inline: True
Inline callers:
  - kernel/time/vsyscall.c:vdso_update_begin
  - kernel/time/vsyscall.c:update_vsyscall
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
In kernel/time/vsyscall.c (ffffffff811b12f5)
Location: include/vdso/helpers.h:30
Inline: True
Inline callers:
  - kernel/time/vsyscall.c:vdso_update_begin
  - kernel/time/vsyscall.c:update_vsyscall
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
In kernel/time/vsyscall.c (ffffffff811f1f75)
Location: include/vdso/helpers.h:30
Inline: True
Inline callers:
  - kernel/time/vsyscall.c:vdso_update_begin
  - kernel/time/vsyscall.c:update_vsyscall
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
In kernel/time/vsyscall.c (ffffffff81206725)
Location: include/vdso/helpers.h:30
Inline: True
Inline callers:
  - kernel/time/vsyscall.c:vdso_update_begin
  - kernel/time/vsyscall.c:update_vsyscall
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
In kernel/time/vsyscall.c (ffffffff8121d935)
Location: include/vdso/helpers.h:30
Inline: True
Inline callers:
  - kernel/time/vsyscall.c:vdso_update_begin
  - kernel/time/vsyscall.c:update_vsyscall
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
In kernel/time/vsyscall.c (ffff8000101b6088)
Location: include/vdso/helpers.h:30
Inline: True
Inline callers:
  - kernel/time/vsyscall.c:update_vsyscall
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
In arch/arm/kernel/vdso.c (c0319c4c)
Location: arch/arm/kernel/vdso.c:267
Inline: True
Inline callers:
  - arch/arm/kernel/vdso.c:update_vsyscall
```
</details>
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
In kernel/time/vsyscall.c (ffffffff81141eb5)
Location: include/vdso/helpers.h:30
Inline: True
Inline callers:
  - kernel/time/vsyscall.c:update_vsyscall
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
In kernel/time/vsyscall.c (ffffffff81135215)
Location: include/vdso/helpers.h:30
Inline: True
Inline callers:
  - kernel/time/vsyscall.c:update_vsyscall
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
In kernel/time/vsyscall.c (ffffffff8113fd65)
Location: include/vdso/helpers.h:30
Inline: True
Inline callers:
  - kernel/time/vsyscall.c:update_vsyscall
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
In kernel/time/vsyscall.c (ffffffff8114c895)
Location: include/vdso/helpers.h:30
Inline: True
Inline callers:
  - kernel/time/vsyscall.c:update_vsyscall
```
</details>
</li>
</ul>

## Differences
