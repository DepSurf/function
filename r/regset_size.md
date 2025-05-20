# Function: <code>regset_size</code>

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
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff812d970a)
Location: include/linux/regset.h:419
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff812dc7eb)
Location: include/linux/regset.h:419
Inline: True
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
In fs/binfmt_elf.c (ffffffff81303f9f)
Location: include/linux/regset.h:419
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff813078b0)
Location: include/linux/regset.h:419
Inline: True
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
In fs/binfmt_elf.c (ffffffff813196ef)
Location: include/linux/regset.h:419
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff8131d0c0)
Location: include/linux/regset.h:419
Inline: True
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
In fs/binfmt_elf.c (ffffffff813423b6)
Location: include/linux/regset.h:416
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff81345cfc)
Location: include/linux/regset.h:416
Inline: True
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
In fs/binfmt_elf.c (ffffffff8135a7ec)
Location: include/linux/regset.h:416
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff8135dfff)
Location: include/linux/regset.h:416
Inline: True
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
In fs/binfmt_elf.c (ffffffff8139f89b)
Location: include/linux/regset.h:416
Inline: True
Inline callers:
  - fs/binfmt_elf.c:fill_thread_core_info
  - fs/binfmt_elf.c:fill_thread_core_info
```
```
In fs/compat_binfmt_elf.c (ffffffff813a2dba)
Location: include/linux/regset.h:416
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:fill_thread_core_info
  - fs/compat_binfmt_elf.c:fill_thread_core_info
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
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffff800010420044)
Location: include/linux/regset.h:416
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffff800010423ba0)
Location: include/linux/regset.h:416
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
In fs/binfmt_elf.c (c05e85c4)
Location: include/linux/regset.h:416
Inline: True
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
In fs/binfmt_elf.c (c00000000052ef90)
Location: include/linux/regset.h:416
Inline: True
```
```
In fs/compat_binfmt_elf.c (c000000000532bc0)
Location: include/linux/regset.h:416
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
In fs/binfmt_elf.c (ffffffe0002c0f1c)
Location: include/linux/regset.h:416
Inline: True
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
In fs/binfmt_elf.c (ffffffff81352dcc)
Location: include/linux/regset.h:416
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff813565df)
Location: include/linux/regset.h:416
Inline: True
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
In fs/binfmt_elf.c (ffffffff81343aac)
Location: include/linux/regset.h:416
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff8134729f)
Location: include/linux/regset.h:416
Inline: True
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
In fs/binfmt_elf.c (ffffffff8135089c)
Location: include/linux/regset.h:416
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff813540af)
Location: include/linux/regset.h:416
Inline: True
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
In fs/binfmt_elf.c (ffffffff81363e1c)
Location: include/linux/regset.h:416
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff81367870)
Location: include/linux/regset.h:416
Inline: True
```
</details>
</li>
</ul>

## Differences
