# Function: <code>str_enabled_disabled</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
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
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff83ea536f)
Location: include/linux/string_helpers.h:126
Inline: True
Inline callers:
  - kernel/panic.c:panic_on_taint_setup
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff83eee205)
Location: include/linux/string_helpers.h:126
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81d35f73)
Location: include/linux/string_helpers.h:126
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
In kernel/panic.c (ffffffff836c970f)
Location: include/linux/string_choices.h:12
Inline: True
Inline callers:
  - kernel/panic.c:panic_on_taint_setup
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff83713e45)
Location: include/linux/string_choices.h:12
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81d9f2f0)
Location: include/linux/string_choices.h:12
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
In kernel/panic.c (ffffffff838fa35f)
Location: include/linux/string_choices.h:12
Inline: True
Inline callers:
  - kernel/panic.c:panic_on_taint_setup
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff839478a5)
Location: include/linux/string_choices.h:12
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81e57100)
Location: include/linux/string_choices.h:12
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
