# Function: <code>initcall_from_entry</code>

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
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff828832b9)
Location: include/linux/init.h:122
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
  - init/main.c:kernel_init_freeable
```
```
In kernel/printk/printk.c (ffffffff828ada2b)
Location: include/linux/init.h:122
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_init
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
In init/main.c (ffffffff8289a30f)
Location: include/linux/init.h:122
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
  - init/main.c:kernel_init_freeable
```
```
In kernel/printk/printk.c (ffffffff828c63e5)
Location: include/linux/init.h:122
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_init
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
In init/main.c (ffffffff8289d2f4)
Location: include/linux/init.h:122
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
  - init/main.c:kernel_init_freeable
```
```
In kernel/printk/printk.c (ffffffff828cea12)
Location: include/linux/init.h:122
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_init
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
In init/main.c (ffffffff82cc393c)
Location: include/linux/init.h:122
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
  - init/main.c:do_initcalls
```
```
In kernel/printk/printk.c (ffffffff82cefe78)
Location: include/linux/init.h:122
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_init
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
In init/main.c (ffffffff82fafa4e)
Location: include/linux/init.h:122
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
  - init/main.c:do_initcalls
```
```
In kernel/printk/printk.c (ffffffff82fdc86b)
Location: include/linux/init.h:122
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_init
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
In init/main.c (ffffffff831b9ab0)
Location: include/linux/init.h:122
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
  - init/main.c:do_initcalls
```
```
In kernel/printk/printk.c (ffffffff831e75ca)
Location: include/linux/init.h:122
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_init
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
In init/main.c (ffffffff83299e8c)
Location: include/linux/init.h:122
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
  - init/main.c:do_initcalls
```
```
In kernel/printk/printk.c (ffffffff832cb755)
Location: include/linux/init.h:122
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_init
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
In init/main.c (ffffffff8344808f)
Location: include/linux/init.h:122
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
  - init/main.c:do_initcalls
```
```
In kernel/printk/printk.c (ffffffff8347ee4d)
Location: include/linux/init.h:122
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_init
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
In init/main.c (ffffffff83e619ba)
Location: include/linux/init.h:124
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
  - init/main.c:do_initcalls
```
```
In kernel/printk/printk.c (ffffffff83eaaf98)
Location: include/linux/init.h:124
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_init
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
In init/main.c (ffffffff83681dda)
Location: include/linux/init.h:124
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
  - init/main.c:do_initcalls
```
```
In kernel/printk/printk.c (ffffffff836cff58)
Location: include/linux/init.h:124
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_init
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
In init/main.c (ffffffff838b0e0a)
Location: include/linux/init.h:121
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
  - init/main.c:do_initcalls
```
```
In kernel/printk/printk.c (ffffffff83901368)
Location: include/linux/init.h:121
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_init
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
In init/main.c (ffff8000114312c0)
Location: include/linux/init.h:122
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
  - init/main.c:kernel_init_freeable
```
```
In kernel/printk/printk.c (ffff800011446300)
Location: include/linux/init.h:122
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_init
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
In init/main.c (c15012f4)
Location: include/linux/init.h:129
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
  - init/main.c:kernel_init_freeable
```
```
In kernel/printk/printk.c (c152098c)
Location: include/linux/init.h:129
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_init
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
In init/main.c (0)
Location: include/linux/init.h:129
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/init.h:129
Inline: True
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
In init/main.c (0)
Location: include/linux/init.h:129
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/init.h:129
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
In init/main.c (ffffffff8288b2f4)
Location: include/linux/init.h:122
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
  - init/main.c:kernel_init_freeable
```
```
In kernel/printk/printk.c (ffffffff828b770a)
Location: include/linux/init.h:122
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_init
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
In init/main.c (ffffffff82889271)
Location: include/linux/init.h:122
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
  - init/main.c:kernel_init_freeable
```
```
In kernel/printk/printk.c (ffffffff828af98a)
Location: include/linux/init.h:122
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_init
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
In init/main.c (ffffffff8289e2f4)
Location: include/linux/init.h:122
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
  - init/main.c:kernel_init_freeable
```
```
In kernel/printk/printk.c (ffffffff828ca646)
Location: include/linux/init.h:122
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_init
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
In init/main.c (ffffffff8289e2f9)
Location: include/linux/init.h:122
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
  - init/main.c:kernel_init_freeable
```
```
In kernel/printk/printk.c (ffffffff828cfa11)
Location: include/linux/init.h:122
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_init
```
</details>
</li>
</ul>

## Differences
