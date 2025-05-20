# Function: <code>printk_get_level</code>

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
In kernel/printk/printk.c (ffffffff810d8694)
Location: include/linux/printk.h:13
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_emit
```
```
In kernel/debug/kdb/kdb_io.c (ffffffff81131ffd)
Location: include/linux/printk.h:13
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
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
In kernel/printk/printk.c (ffffffff810dd17d)
Location: include/linux/printk.h:13
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_emit
```
```
In kernel/debug/kdb/kdb_io.c (ffffffff8113a382)
Location: include/linux/printk.h:13
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
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
In kernel/printk/printk.c (ffffffff810e3777)
Location: include/linux/printk.h:15
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_emit
```
```
In kernel/printk/nmi.c (ffffffff810e5786)
Location: include/linux/printk.h:15
Inline: True
Inline callers:
  - kernel/printk/nmi.c:__printk_nmi_flush
```
```
In kernel/debug/kdb/kdb_io.c (ffffffff81144148)
Location: include/linux/printk.h:15
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
```
```
In drivers/acpi/osl.c (ffffffff814ea2ca)
Location: include/linux/printk.h:15
Inline: True
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
In kernel/printk/printk.c (ffffffff810e3555)
Location: include/linux/printk.h:15
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_emit
```
```
In kernel/printk/printk_safe.c (ffffffff810e4c07)
Location: include/linux/printk.h:15
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:__printk_safe_flush
```
```
In kernel/debug/kdb/kdb_io.c (ffffffff81145e40)
Location: include/linux/printk.h:15
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
```
```
In drivers/acpi/osl.c (ffffffff814f607b)
Location: include/linux/printk.h:15
Inline: True
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
In kernel/printk/printk.c (ffffffff810eb215)
Location: include/linux/printk.h:16
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_emit
```
```
In kernel/printk/printk_safe.c (ffffffff810ecea7)
Location: include/linux/printk.h:16
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:__printk_safe_flush
```
```
In kernel/debug/kdb/kdb_io.c (ffffffff81152780)
Location: include/linux/printk.h:16
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
```
```
In drivers/acpi/osl.c (ffffffff8153714e)
Location: include/linux/printk.h:16
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
In kernel/printk/printk.c (ffffffff810f42f7)
Location: include/linux/printk.h:16
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_store
```
```
In kernel/printk/printk_safe.c (ffffffff810f5298)
Location: include/linux/printk.h:16
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:__printk_safe_flush
```
```
In kernel/debug/kdb/kdb_io.c (ffffffff81161387)
Location: include/linux/printk.h:16
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
```
```
In drivers/acpi/osl.c (ffffffff8156d848)
Location: include/linux/printk.h:16
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
In kernel/printk/printk.c (ffffffff810ffaa7)
Location: include/linux/printk.h:16
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_store
```
```
In kernel/printk/printk_safe.c (ffffffff81100a46)
Location: include/linux/printk.h:16
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:__printk_safe_flush
```
```
In kernel/debug/kdb/kdb_io.c (ffffffff8116e1b7)
Location: include/linux/printk.h:16
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
```
```
In drivers/acpi/osl.c (ffffffff81585408)
Location: include/linux/printk.h:16
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
In kernel/printk/printk.c (ffffffff811081f7)
Location: include/linux/printk.h:16
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_store
```
```
In kernel/printk/printk_safe.c (ffffffff8110922a)
Location: include/linux/printk.h:16
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:__printk_safe_flush
```
```
In kernel/debug/kdb/kdb_io.c (ffffffff8117afe5)
Location: include/linux/printk.h:16
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
```
```
In drivers/acpi/osl.c (ffffffff815b6073)
Location: include/linux/printk.h:16
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
In kernel/printk/printk.c (ffffffff811145d7)
Location: include/linux/printk.h:16
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_store
```
```
In kernel/printk/printk_safe.c (ffffffff8111560a)
Location: include/linux/printk.h:16
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:__printk_safe_flush
```
```
In kernel/debug/kdb/kdb_io.c (ffffffff81186e75)
Location: include/linux/printk.h:16
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
```
```
In drivers/acpi/osl.c (ffffffff815d72a3)
Location: include/linux/printk.h:16
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (ffffffff81120047)
Location: include/linux/printk.h:16
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_store
```
```
In kernel/printk/printk_safe.c (ffffffff81120e92)
Location: include/linux/printk.h:16
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:printk_safe_flush_buffer
  - kernel/printk/printk_safe.c:printk_safe_flush_buffer
```
```
In kernel/debug/kdb/kdb_io.c (ffffffff8119b6d0)
Location: include/linux/printk.h:16
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
Direct callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
```
```
In drivers/acpi/osl.c (ffffffff81680f2d)
Location: include/linux/printk.h:16
Inline: True
```
**Symbols:**

```
ffffffff8119b1b0-ffffffff8119b1d3: printk_get_level.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (ffffffff81117955)
Location: include/linux/printk.h:19
Inline: True
Inline callers:
  - kernel/printk/printk.c:parse_prefix
```
```
In kernel/printk/printk_safe.c (ffffffff8111baf2)
Location: include/linux/printk.h:19
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:printk_safe_flush_buffer
  - kernel/printk/printk_safe.c:printk_safe_flush_buffer
```
```
In kernel/debug/kdb/kdb_io.c (ffffffff81198850)
Location: include/linux/printk.h:19
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
Direct callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
```
```
In drivers/acpi/osl.c (ffffffff81c00895)
Location: include/linux/printk.h:19
Inline: True
```
**Symbols:**

```
ffffffff81198340-ffffffff81198363: printk_get_level.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (ffffffff81118045)
Location: include/linux/printk.h:19
Inline: True
Inline callers:
  - kernel/printk/printk.c:parse_prefix
```
```
In kernel/printk/printk_safe.c (ffffffff8111bfb9)
Location: include/linux/printk.h:19
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:__printk_safe_flush
```
```
In kernel/debug/kdb/kdb_io.c (ffffffff811996a0)
Location: include/linux/printk.h:19
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
Direct callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
```
```
In drivers/acpi/osl.c (ffffffff81bf2381)
Location: include/linux/printk.h:19
Inline: True
```
**Symbols:**

```
ffffffff81199190-ffffffff811991b3: printk_get_level.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (ffffffff8113b4a5)
Location: include/linux/printk.h:20
Inline: True
Inline callers:
  - kernel/printk/printk.c:printk_parse_prefix
```
```
In kernel/debug/kdb/kdb_io.c (ffffffff811c3480)
Location: include/linux/printk.h:20
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
Direct callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
```
```
In drivers/acpi/osl.c (ffffffff81ceec0f)
Location: include/linux/printk.h:20
Inline: True
```
**Symbols:**

```
ffffffff811c2f70-ffffffff811c2f93: printk_get_level.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (ffffffff8115e525)
Location: include/linux/printk.h:19
Inline: True
Inline callers:
  - kernel/printk/printk.c:printk_parse_prefix
```
```
In kernel/debug/kdb/kdb_io.c (ffffffff811f6cdc)
Location: include/linux/printk.h:19
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
Direct callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
```
```
In drivers/acpi/osl.c (ffffffff81eb6371)
Location: include/linux/printk.h:19
Inline: True
```
**Symbols:**

```
ffffffff811f6770-ffffffff811f679f: printk_get_level.part.0 (STB_LOCAL)
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
In kernel/printk/printk.c (ffffffff81191445)
Location: include/linux/printk.h:19
Inline: True
Inline callers:
  - kernel/printk/printk.c:printk_parse_prefix
```
```
In kernel/debug/kdb/kdb_io.c (ffffffff8123df4f)
Location: include/linux/printk.h:19
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
```
```
In drivers/acpi/osl.c (ffffffff81954f0a)
Location: include/linux/printk.h:19
Inline: True
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
In kernel/printk/printk.c (ffffffff811a2d45)
Location: include/linux/printk.h:19
Inline: True
Inline callers:
  - kernel/printk/printk.c:printk_parse_prefix
```
```
In kernel/debug/kdb/kdb_io.c (ffffffff81254faf)
Location: include/linux/printk.h:19
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
```
```
In drivers/acpi/osl.c (ffffffff8199b30a)
Location: include/linux/printk.h:19
Inline: True
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
In kernel/printk/printk.c (ffffffff811b0c05)
Location: include/linux/printk.h:19
Inline: True
Inline callers:
  - kernel/printk/printk.c:printk_parse_prefix
```
```
In kernel/debug/kdb/kdb_io.c (ffffffff8126ee2f)
Location: include/linux/printk.h:19
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
```
```
In drivers/acpi/osl.c (ffffffff819e37fa)
Location: include/linux/printk.h:19
Inline: True
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
In kernel/printk/printk.c (ffff8000101755b0)
Location: include/linux/printk.h:16
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_store
```
```
In kernel/printk/printk_safe.c (ffff800010176a04)
Location: include/linux/printk.h:16
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:__printk_safe_flush
```
```
In kernel/debug/kdb/kdb_io.c (ffff8000101fcf44)
Location: include/linux/printk.h:16
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
```
```
In drivers/acpi/osl.c (ffff800010764838)
Location: include/linux/printk.h:16
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_vprintf
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
In kernel/printk/printk.c (c03c7868)
Location: include/linux/printk.h:16
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_store
```
```
In kernel/printk/printk_safe.c (c03c8994)
Location: include/linux/printk.h:16
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:__printk_safe_flush
```
```
In kernel/debug/kdb/kdb_io.c (c043d050)
Location: include/linux/printk.h:16
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
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
In kernel/printk/printk.c (c0000000001ced18)
Location: include/linux/printk.h:16
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_store
```
```
In kernel/printk/printk_safe.c (c0000000001d03b8)
Location: include/linux/printk.h:16
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:__printk_safe_flush
```
```
In kernel/debug/kdb/kdb_io.c (c000000000275664)
Location: include/linux/printk.h:16
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
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
In kernel/printk/printk.c (ffffffe000110de4)
Location: include/linux/printk.h:16
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_store
```
```
In kernel/printk/printk_safe.c (ffffffe000111cac)
Location: include/linux/printk.h:16
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:__printk_safe_flush
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
In kernel/printk/printk.c (ffffffff8110cbb7)
Location: include/linux/printk.h:16
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_store
```
```
In kernel/printk/printk_safe.c (ffffffff8110dbea)
Location: include/linux/printk.h:16
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:__printk_safe_flush
```
```
In kernel/debug/kdb/kdb_io.c (ffffffff8117f495)
Location: include/linux/printk.h:16
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
```
```
In drivers/acpi/osl.c (ffffffff815ca778)
Location: include/linux/printk.h:16
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_vprintf
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
In kernel/printk/printk.c (ffffffff810fd987)
Location: include/linux/printk.h:16
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_store
```
```
In kernel/printk/printk_safe.c (ffffffff810fe94a)
Location: include/linux/printk.h:16
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:__printk_safe_flush
```
```
In kernel/debug/kdb/kdb_io.c (ffffffff811725d8)
Location: include/linux/printk.h:16
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
```
```
In drivers/acpi/osl.c (ffffffff815b37f8)
Location: include/linux/printk.h:16
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_vprintf
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
In kernel/printk/printk.c (ffffffff8110aaa7)
Location: include/linux/printk.h:16
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_store
```
```
In kernel/printk/printk_safe.c (ffffffff8110bada)
Location: include/linux/printk.h:16
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:__printk_safe_flush
```
```
In kernel/debug/kdb/kdb_io.c (ffffffff8117d265)
Location: include/linux/printk.h:16
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
```
```
In drivers/acpi/osl.c (ffffffff815cb583)
Location: include/linux/printk.h:16
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
In kernel/printk/printk.c (ffffffff81115eb7)
Location: include/linux/printk.h:16
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_store
```
```
In kernel/printk/printk_safe.c (ffffffff81116fea)
Location: include/linux/printk.h:16
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:__printk_safe_flush
```
```
In kernel/debug/kdb/kdb_io.c (ffffffff8118ab85)
Location: include/linux/printk.h:16
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
```
```
In drivers/acpi/osl.c (ffffffff815e5423)
Location: include/linux/printk.h:16
Inline: True
```
</details>
</li>
</ul>

## Differences
