# Function: <code>hex_byte_pack_upper</code>

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
In kernel/audit.c (ffffffff81121e66)
Location: include/linux/kernel.h:510
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_n_hex
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
In kernel/audit.c (ffffffff81129dba)
Location: include/linux/kernel.h:528
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_n_hex
```
```
In lib/vsprintf.c (ffffffff81439c8c)
Location: include/linux/kernel.h:528
Inline: True
Inline callers:
  - lib/vsprintf.c:uuid_string
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
In kernel/audit.c (ffffffff81133ada)
Location: include/linux/kernel.h:539
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_n_hex
```
```
In lib/vsprintf.c (ffffffff81456c6c)
Location: include/linux/kernel.h:539
Inline: True
Inline callers:
  - lib/vsprintf.c:uuid_string
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
In kernel/audit.c (ffffffff81134fae)
Location: include/linux/kernel.h:557
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_n_hex
```
```
In lib/vsprintf.c (ffffffff818f84ef)
Location: include/linux/kernel.h:557
Inline: True
Inline callers:
  - lib/vsprintf.c:uuid_string
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
In kernel/audit.c (ffffffff81141cfe)
Location: include/linux/kernel.h:595
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_n_hex
```
```
In lib/vsprintf.c (ffffffff8197efaf)
Location: include/linux/kernel.h:595
Inline: True
Inline callers:
  - lib/vsprintf.c:uuid_string
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
In kernel/audit.c (ffffffff811506a5)
Location: include/linux/kernel.h:625
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_n_hex
```
```
In lib/vsprintf.c (ffffffff819db52f)
Location: include/linux/kernel.h:625
Inline: True
Inline callers:
  - lib/vsprintf.c:uuid_string
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
In kernel/audit.c (ffffffff8115d352)
Location: include/linux/kernel.h:659
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_n_hex
```
```
In lib/vsprintf.c (ffffffff81a1380f)
Location: include/linux/kernel.h:659
Inline: True
Inline callers:
  - lib/vsprintf.c:uuid_string
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
In kernel/audit.c (ffffffff81169a8b)
Location: include/linux/kernel.h:619
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_n_hex
```
```
In lib/vsprintf.c (ffffffff81a82f1e)
Location: include/linux/kernel.h:619
Inline: True
Inline callers:
  - lib/vsprintf.c:uuid_string
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
In kernel/audit.c (ffffffff8117592b)
Location: include/linux/kernel.h:623
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_n_hex
```
```
In lib/vsprintf.c (ffffffff81aba12e)
Location: include/linux/kernel.h:623
Inline: True
Inline callers:
  - lib/vsprintf.c:uuid_string
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
In kernel/audit.c (ffffffff8118808b)
Location: include/linux/kernel.h:632
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_n_hex
```
```
In lib/vsprintf.c (ffffffff815f681e)
Location: include/linux/kernel.h:632
Inline: True
Inline callers:
  - lib/vsprintf.c:uuid_string
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
In kernel/audit.c (ffffffff8118541b)
Location: include/linux/kernel.h:472
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_n_hex
```
```
In lib/vsprintf.c (ffffffff8161aeae)
Location: include/linux/kernel.h:472
Inline: True
Inline callers:
  - lib/vsprintf.c:uuid_string
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
In kernel/audit.c (ffffffff8118641e)
Location: include/linux/kernel.h:482
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_n_hex
```
```
In lib/vsprintf.c (ffffffff815ff0ec)
Location: include/linux/kernel.h:482
Inline: True
Inline callers:
  - lib/vsprintf.c:uuid_string
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
In kernel/audit.c (ffffffff811ae80e)
Location: include/linux/kernel.h:273
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_n_hex
```
```
In lib/vsprintf.c (ffffffff8166ce5c)
Location: include/linux/kernel.h:273
Inline: True
Inline callers:
  - lib/vsprintf.c:uuid_string
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
In kernel/audit.c (ffffffff811e0790)
Location: include/linux/kernel.h:281
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_n_hex
```
```
In lib/vsprintf.c (ffffffff81787161)
Location: include/linux/kernel.h:281
Inline: True
Inline callers:
  - lib/vsprintf.c:uuid_string
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
In kernel/audit.c (ffffffff81226530)
Location: include/linux/kernel.h:281
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_n_hex
```
```
In lib/vsprintf.c (ffffffff82044301)
Location: include/linux/kernel.h:281
Inline: True
Inline callers:
  - lib/vsprintf.c:uuid_string
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
In kernel/audit.c (ffffffff8123cb18)
Location: include/linux/hex.h:22
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_n_hex
```
```
In lib/vsprintf.c (ffffffff820c2911)
Location: include/linux/hex.h:22
Inline: True
Inline callers:
  - lib/vsprintf.c:uuid_string
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
In kernel/audit.c (ffffffff81256a28)
Location: include/linux/hex.h:22
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_n_hex
```
```
In lib/vsprintf.c (ffffffff8219d291)
Location: include/linux/hex.h:22
Inline: True
Inline callers:
  - lib/vsprintf.c:uuid_string
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
In kernel/audit.c (ffff8000101ea7dc)
Location: include/linux/kernel.h:623
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_n_hex
```
```
In lib/vsprintf.c (ffff800010d94928)
Location: include/linux/kernel.h:623
Inline: True
Inline callers:
  - lib/vsprintf.c:uuid_string
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
In kernel/audit.c (c042a4e8)
Location: include/linux/kernel.h:623
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_n_hex
```
```
In lib/vsprintf.c (c0e90b14)
Location: include/linux/kernel.h:623
Inline: True
Inline callers:
  - lib/vsprintf.c:uuid_string
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
In kernel/audit.c (c00000000025bab4)
Location: include/linux/kernel.h:623
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_n_hex
```
```
In lib/vsprintf.c (c000000000ed9400)
Location: include/linux/kernel.h:623
Inline: True
Inline callers:
  - lib/vsprintf.c:uuid_string
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
In kernel/audit.c (ffffffe00015f1a0)
Location: include/linux/kernel.h:623
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_n_hex
```
```
In lib/vsprintf.c (ffffffe0008be730)
Location: include/linux/kernel.h:623
Inline: True
Inline callers:
  - lib/vsprintf.c:uuid_string
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
In kernel/audit.c (ffffffff8116df4b)
Location: include/linux/kernel.h:623
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_n_hex
```
```
In lib/vsprintf.c (ffffffff81a58f7e)
Location: include/linux/kernel.h:623
Inline: True
Inline callers:
  - lib/vsprintf.c:uuid_string
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
In kernel/audit.c (ffffffff811610eb)
Location: include/linux/kernel.h:623
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_n_hex
```
```
In lib/vsprintf.c (ffffffff81a1605e)
Location: include/linux/kernel.h:623
Inline: True
Inline callers:
  - lib/vsprintf.c:uuid_string
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
In kernel/audit.c (ffffffff8116bd1b)
Location: include/linux/kernel.h:623
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_n_hex
```
```
In lib/vsprintf.c (ffffffff81ac536e)
Location: include/linux/kernel.h:623
Inline: True
Inline callers:
  - lib/vsprintf.c:uuid_string
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
In kernel/audit.c (ffffffff811794db)
Location: include/linux/kernel.h:623
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_n_hex
```
```
In lib/vsprintf.c (ffffffff81ad183e)
Location: include/linux/kernel.h:623
Inline: True
Inline callers:
  - lib/vsprintf.c:uuid_string
```
</details>
</li>
</ul>

## Differences
