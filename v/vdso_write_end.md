# Function: <code>vdso_write_end</code>

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
In kernel/time/vsyscall.c (ffffffff8113df2a)
Location: include/vdso/helpers.h:42
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
In kernel/time/vsyscall.c (ffffffff81149aba)
Location: include/vdso/helpers.h:42
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
In kernel/time/vsyscall.c (ffffffff811598ca)
Location: include/vdso/helpers.h:42
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
In kernel/time/vsyscall.c (ffffffff81155a35)
Location: include/vdso/helpers.h:42
Inline: True
Inline callers:
  - kernel/time/vsyscall.c:vdso_update_end
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
In kernel/time/vsyscall.c (ffffffff81156e75)
Location: include/vdso/helpers.h:42
Inline: True
Inline callers:
  - kernel/time/vsyscall.c:vdso_update_end
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
In kernel/time/vsyscall.c (ffffffff8117bc55)
Location: include/vdso/helpers.h:42
Inline: True
Inline callers:
  - kernel/time/vsyscall.c:vdso_update_end
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
In kernel/time/vsyscall.c (ffffffff811b1335)
Location: include/vdso/helpers.h:42
Inline: True
Inline callers:
  - kernel/time/vsyscall.c:vdso_update_end
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
In kernel/time/vsyscall.c (ffffffff811f1fc5)
Location: include/vdso/helpers.h:42
Inline: True
Inline callers:
  - kernel/time/vsyscall.c:vdso_update_end
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
In kernel/time/vsyscall.c (ffffffff81206775)
Location: include/vdso/helpers.h:42
Inline: True
Inline callers:
  - kernel/time/vsyscall.c:vdso_update_end
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
In kernel/time/vsyscall.c (ffffffff8121d985)
Location: include/vdso/helpers.h:42
Inline: True
Inline callers:
  - kernel/time/vsyscall.c:vdso_update_end
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
In kernel/time/vsyscall.c (ffff8000101b627c)
Location: include/vdso/helpers.h:42
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
In arch/arm/kernel/vdso.c (c0319cdc)
Location: arch/arm/kernel/vdso.c:273
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
In kernel/time/vsyscall.c (ffffffff811420da)
Location: include/vdso/helpers.h:42
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
In kernel/time/vsyscall.c (ffffffff8113543a)
Location: include/vdso/helpers.h:42
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
In kernel/time/vsyscall.c (ffffffff8113ff8a)
Location: include/vdso/helpers.h:42
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
In kernel/time/vsyscall.c (ffffffff8114caba)
Location: include/vdso/helpers.h:42
Inline: True
Inline callers:
  - kernel/time/vsyscall.c:update_vsyscall
```
</details>
</li>
</ul>

## Differences
