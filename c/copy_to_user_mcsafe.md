# Function: <code>copy_to_user_mcsafe</code>

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
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff814c6074)
Location: arch/x86/include/asm/uaccess_64.h:50
Inline: True
Inline callers:
  - lib/iov_iter.c:copyout_mcsafe
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
In lib/iov_iter.c (ffffffff814da834)
Location: arch/x86/include/asm/uaccess_64.h:50
Inline: True
Inline callers:
  - lib/iov_iter.c:copyout_mcsafe
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
In lib/iov_iter.c (ffffffff815061a0)
Location: arch/x86/include/asm/uaccess_64.h:50
Inline: True
Inline callers:
  - lib/iov_iter.c:copyout_mcsafe
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
In lib/iov_iter.c (ffffffff815241d0)
Location: arch/x86/include/asm/uaccess_64.h:50
Inline: True
Inline callers:
  - lib/iov_iter.c:copyout_mcsafe
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
In lib/iov_iter.c (ffffffff81586e50)
Location: arch/x86/include/asm/uaccess_64.h:50
Inline: True
Inline callers:
  - lib/iov_iter.c:copyout_mcsafe
```
</details>
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (c0000000007d17b0)
Location: arch/powerpc/include/asm/uaccess.h:391
Inline: True
Inline callers:
  - lib/iov_iter.c:copyout_mcsafe
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
In lib/iov_iter.c (ffffffff8151c7b0)
Location: arch/x86/include/asm/uaccess_64.h:50
Inline: True
Inline callers:
  - lib/iov_iter.c:copyout_mcsafe
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
In lib/iov_iter.c (ffffffff8150caa0)
Location: arch/x86/include/asm/uaccess_64.h:50
Inline: True
Inline callers:
  - lib/iov_iter.c:copyout_mcsafe
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
In lib/iov_iter.c (ffffffff81518840)
Location: arch/x86/include/asm/uaccess_64.h:50
Inline: True
Inline callers:
  - lib/iov_iter.c:copyout_mcsafe
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
In lib/iov_iter.c (ffffffff81532000)
Location: arch/x86/include/asm/uaccess_64.h:50
Inline: True
Inline callers:
  - lib/iov_iter.c:copyout_mcsafe
```
</details>
</li>
</ul>

## Differences
