# Function: <code>__readq</code>

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
In drivers/video/fbdev/core/cfbfillrect.c (ffffffff8153069f)
Location: arch/x86/include/asm/io.h:98
Inline: True
```
```
In drivers/video/fbdev/core/cfbcopyarea.c (ffffffff81530db0)
Location: arch/x86/include/asm/io.h:98
Inline: True
Inline callers:
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8159a207)
Location: arch/x86/include/asm/io.h:98
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cpc_read
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
In drivers/video/fbdev/core/cfbfillrect.c (ffffffff815660ff)
Location: arch/x86/include/asm/io.h:98
Inline: True
```
```
In drivers/video/fbdev/core/cfbcopyarea.c (ffffffff8156675b)
Location: arch/x86/include/asm/io.h:98
Inline: True
Inline callers:
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
```
```
In drivers/acpi/cppc_acpi.c (ffffffff815d1b09)
Location: arch/x86/include/asm/io.h:98
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cpc_read
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
In drivers/video/fbdev/core/cfbfillrect.c (ffffffff8157db6f)
Location: arch/x86/include/asm/io.h:98
Inline: True
```
```
In drivers/video/fbdev/core/cfbcopyarea.c (ffffffff8157e1ca)
Location: arch/x86/include/asm/io.h:98
Inline: True
Inline callers:
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
```
```
In drivers/acpi/cppc_acpi.c (ffffffff815eb129)
Location: arch/x86/include/asm/io.h:98
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cpc_read
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
In drivers/video/fbdev/core/cfbfillrect.c (ffffffff815ae0f2)
Location: arch/x86/include/asm/io.h:96
Inline: True
```
```
In drivers/video/fbdev/core/cfbcopyarea.c (ffffffff815ae843)
Location: arch/x86/include/asm/io.h:96
Inline: True
Inline callers:
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8161ceed)
Location: arch/x86/include/asm/io.h:96
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cpc_read
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
In drivers/video/fbdev/core/cfbfillrect.c (ffffffff815cf072)
Location: arch/x86/include/asm/io.h:96
Inline: True
```
```
In drivers/video/fbdev/core/cfbcopyarea.c (ffffffff815cf7c3)
Location: arch/x86/include/asm/io.h:96
Inline: True
Inline callers:
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8163e99d)
Location: arch/x86/include/asm/io.h:96
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cpc_read
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
In drivers/video/fbdev/core/cfbfillrect.c (ffffffff81678a3f)
Location: arch/x86/include/asm/io.h:96
Inline: True
```
```
In drivers/video/fbdev/core/cfbcopyarea.c (ffffffff816790c2)
Location: arch/x86/include/asm/io.h:96
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffffffff816ebab7)
Location: arch/x86/include/asm/io.h:96
Inline: True
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
In drivers/video/fbdev/core/cfbfillrect.c (ffffffff81698b0f)
Location: arch/x86/include/asm/io.h:96
Inline: True
```
```
In drivers/video/fbdev/core/cfbcopyarea.c (ffffffff81699142)
Location: arch/x86/include/asm/io.h:96
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81709129)
Location: arch/x86/include/asm/io.h:96
Inline: True
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff817f847b)
Location: arch/x86/include/asm/io.h:96
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read64le_relaxed
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
In drivers/video/fbdev/core/cfbfillrect.c (ffffffff8167b92f)
Location: arch/x86/include/asm/io.h:96
Inline: True
```
```
In drivers/video/fbdev/core/cfbcopyarea.c (ffffffff8167bf50)
Location: arch/x86/include/asm/io.h:96
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffffffff816ea753)
Location: arch/x86/include/asm/io.h:96
Inline: True
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff817dcc0b)
Location: arch/x86/include/asm/io.h:96
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read64le_relaxed
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
In drivers/video/fbdev/core/cfbfillrect.c (ffffffff816f054c)
Location: arch/x86/include/asm/io.h:96
Inline: True
```
```
In drivers/video/fbdev/core/cfbcopyarea.c (ffffffff816f0d80)
Location: arch/x86/include/asm/io.h:96
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81764535)
Location: arch/x86/include/asm/io.h:96
Inline: True
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff8186860b)
Location: arch/x86/include/asm/io.h:96
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read64le_relaxed
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
In drivers/video/fbdev/core/cfbfillrect.c (ffffffff8181b9c8)
Location: arch/x86/include/asm/io.h:98
Inline: True
```
```
In drivers/video/fbdev/core/cfbcopyarea.c (ffffffff8181c6a3)
Location: arch/x86/include/asm/io.h:98
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffffffff818985f6)
Location: arch/x86/include/asm/io.h:98
Inline: True
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff819b104b)
Location: arch/x86/include/asm/io.h:98
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read64le_relaxed
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
In drivers/video/fbdev/core/cfbfillrect.c (ffffffff8194af48)
Location: arch/x86/include/asm/io.h:98
Inline: True
```
```
In drivers/video/fbdev/core/cfbcopyarea.c (ffffffff8194bcd3)
Location: arch/x86/include/asm/io.h:98
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffffffff819e0936)
Location: arch/x86/include/asm/io.h:98
Inline: True
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff81b255ee)
Location: arch/x86/include/asm/io.h:98
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_noinc_read
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
In drivers/video/fbdev/core/cfbfillrect.c (ffffffff8198f548)
Location: arch/x86/include/asm/io.h:98
Inline: True
```
```
In drivers/video/fbdev/core/cfbcopyarea.c (ffffffff81990270)
Location: arch/x86/include/asm/io.h:98
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81a28746)
Location: arch/x86/include/asm/io.h:98
Inline: True
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff81b75718)
Location: arch/x86/include/asm/io.h:98
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_noinc_read
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
In drivers/video/fbdev/core/cfbfillrect.c (ffffffff819d9468)
Location: arch/x86/include/asm/io.h:95
Inline: True
```
```
In drivers/video/fbdev/core/cfbcopyarea.c (ffffffff819da1e0)
Location: arch/x86/include/asm/io.h:95
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81a73916)
Location: arch/x86/include/asm/io.h:95
Inline: True
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
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/cfbfillrect.c (ffffffff815c3082)
Location: arch/x86/include/asm/io.h:96
Inline: True
```
```
In drivers/video/fbdev/core/cfbcopyarea.c (ffffffff815c37d3)
Location: arch/x86/include/asm/io.h:96
Inline: True
Inline callers:
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8160a3cd)
Location: arch/x86/include/asm/io.h:96
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cpc_read
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
In drivers/acpi/cppc_acpi.c (ffffffff815fc00d)
Location: arch/x86/include/asm/io.h:96
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cpc_read
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
In drivers/video/fbdev/core/cfbfillrect.c (ffffffff815c3612)
Location: arch/x86/include/asm/io.h:96
Inline: True
```
```
In drivers/video/fbdev/core/cfbcopyarea.c (ffffffff815c3d63)
Location: arch/x86/include/asm/io.h:96
Inline: True
Inline callers:
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
```
```
In drivers/acpi/cppc_acpi.c (ffffffff816327dd)
Location: arch/x86/include/asm/io.h:96
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cpc_read
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
In drivers/video/fbdev/core/cfbfillrect.c (ffffffff815dd1b2)
Location: arch/x86/include/asm/io.h:96
Inline: True
```
```
In drivers/video/fbdev/core/cfbcopyarea.c (ffffffff815dd903)
Location: arch/x86/include/asm/io.h:96
Inline: True
Inline callers:
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8164cb0d)
Location: arch/x86/include/asm/io.h:96
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cpc_read
```
</details>
</li>
</ul>

## Differences
