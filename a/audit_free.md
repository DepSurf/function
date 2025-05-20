# Function: <code>audit_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8107ed28)
Location: include/linux/audit.h:151
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff810839e8)
Location: include/linux/audit.h:151
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81080a37)
Location: include/linux/audit.h:254
Inline: True
```
```
In kernel/exit.c (ffffffff81086b03)
Location: include/linux/audit.h:254
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810853c6)
Location: include/linux/audit.h:254
Inline: True
```
```
In kernel/exit.c (ffffffff8108ba6c)
Location: include/linux/audit.h:254
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810822be)
Location: include/linux/audit.h:253
Inline: True
```
```
In kernel/exit.c (ffffffff81088bed)
Location: include/linux/audit.h:253
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81088b2f)
Location: include/linux/audit.h:245
Inline: True
```
```
In kernel/exit.c (ffffffff8108f930)
Location: include/linux/audit.h:245
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
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
In kernel/fork.c (ffffffff8108c927)
Location: include/linux/audit.h:255
Inline: True
```
```
In kernel/exit.c (ffffffff810934a0)
Location: include/linux/audit.h:255
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
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
In kernel/fork.c (ffffffff81094496)
Location: include/linux/audit.h:254
Inline: True
```
```
In kernel/exit.c (ffffffff8109b75f)
Location: include/linux/audit.h:254
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
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
In kernel/fork.c (ffffffff810988dd)
Location: include/linux/audit.h:297
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff8109fdd3)
Location: include/linux/audit.h:297
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
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
In kernel/fork.c (ffffffff8109ee98)
Location: include/linux/audit.h:297
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff810a6459)
Location: include/linux/audit.h:297
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
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
In kernel/fork.c (ffffffff810a64c3)
Location: include/linux/audit.h:314
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff810ae219)
Location: include/linux/audit.h:314
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
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
In kernel/fork.c (ffffffff810a1e08)
Location: include/linux/audit.h:331
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff810a98cc)
Location: include/linux/audit.h:331
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
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
In kernel/fork.c (ffffffff810a2c45)
Location: include/linux/audit.h:331
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff810aa8fd)
Location: include/linux/audit.h:331
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
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
In kernel/fork.c (ffffffff810b4384)
Location: include/linux/audit.h:331
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff810bc424)
Location: include/linux/audit.h:331
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
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
In kernel/fork.c (ffffffff810ca6f2)
Location: include/linux/audit.h:342
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff810d2f13)
Location: include/linux/audit.h:342
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In io_uring/io_uring.c (ffffffff81e92cbd)
Location: include/linux/audit.h:342
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_sq_thread
```
```
In io_uring/io-wq.c (ffffffff816db284)
Location: include/linux/audit.h:342
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wqe_worker
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
In kernel/fork.c (ffffffff810e7d5b)
Location: include/linux/audit.h:339
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff810f1a4e)
Location: include/linux/audit.h:339
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
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
In kernel/fork.c (ffffffff810f3993)
Location: include/linux/audit.h:338
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff810fd9d1)
Location: include/linux/audit.h:338
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
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
In kernel/fork.c (ffffffff810fcd64)
Location: include/linux/audit.h:337
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff8110684c)
Location: include/linux/audit.h:337
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
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
In kernel/fork.c (ffff8000100f4378)
Location: include/linux/audit.h:297
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffff8000100fd3cc)
Location: include/linux/audit.h:297
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
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
In kernel/fork.c (c03521fc)
Location: include/linux/audit.h:297
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (c035a4d8)
Location: include/linux/audit.h:297
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
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
In kernel/fork.c (c00000000013978c)
Location: include/linux/audit.h:297
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (c000000000144258)
Location: include/linux/audit.h:297
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
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
In kernel/fork.c (ffffffe0000c00ba)
Location: include/linux/audit.h:297
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffe0000c5c4a)
Location: include/linux/audit.h:297
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
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
In kernel/fork.c (ffffffff810987b8)
Location: include/linux/audit.h:297
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff8109fd79)
Location: include/linux/audit.h:297
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
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
In kernel/fork.c (ffffffff81087222)
Location: include/linux/audit.h:297
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff8108e7a9)
Location: include/linux/audit.h:297
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
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
In kernel/fork.c (ffffffff81098768)
Location: include/linux/audit.h:297
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff8109fd29)
Location: include/linux/audit.h:297
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
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
In kernel/fork.c (ffffffff810a038f)
Location: include/linux/audit.h:297
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff810a7c99)
Location: include/linux/audit.h:297
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
</details>
</li>
</ul>

## Differences
