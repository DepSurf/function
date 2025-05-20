# Function: <code>irq_settings_no_debug</code>

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
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/handle.c (ffffffff8113ec17)
Location: kernel/irq/settings.h:185
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_irq_event
```
```
In kernel/irq/chip.c (ffffffff811431dc)
Location: kernel/irq/settings.h:185
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_nested_irq
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
In kernel/irq/handle.c (ffffffff81162224)
Location: kernel/irq/settings.h:185
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_irq_event
```
```
In kernel/irq/chip.c (ffffffff81166a83)
Location: kernel/irq/settings.h:185
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_nested_irq
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
In kernel/irq/handle.c (ffffffff81195cc4)
Location: kernel/irq/settings.h:185
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_irq_event
```
```
In kernel/irq/chip.c (ffffffff8119ad63)
Location: kernel/irq/settings.h:185
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_nested_irq
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
In kernel/irq/handle.c (ffffffff811a7684)
Location: kernel/irq/settings.h:185
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_irq_event
```
```
In kernel/irq/chip.c (ffffffff811acac3)
Location: kernel/irq/settings.h:185
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_nested_irq
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
In kernel/irq/handle.c (ffffffff811b71e4)
Location: kernel/irq/settings.h:185
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_irq_event
```
```
In kernel/irq/chip.c (ffffffff811bc6bb)
Location: kernel/irq/settings.h:185
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_nested_irq
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
