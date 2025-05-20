# Function: <code>info_print_ext_header</code>

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
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (ffffffff811185f0)
Location: kernel/printk/printk.c:543
Inline: True
Direct callers:
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:devkmsg_read
```
**Symbols:**

```
ffffffff811185f0-ffffffff81118689: info_print_ext_header.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (ffffffff81118c20)
Location: kernel/printk/printk.c:556
Inline: True
Direct callers:
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:devkmsg_read
```
**Symbols:**

```
ffffffff81118c20-ffffffff81118cbb: info_print_ext_header.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (ffffffff81139530)
Location: kernel/printk/printk.c:551
Inline: True
Direct callers:
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:devkmsg_read
```
**Symbols:**

```
ffffffff81139530-ffffffff811395cb: info_print_ext_header.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (ffffffff8115beb0)
Location: kernel/printk/printk.c:556
Inline: True
Direct callers:
  - kernel/printk/printk.c:devkmsg_read
```
**Symbols:**

```
ffffffff8115beb0-ffffffff8115bf70: info_print_ext_header.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (ffffffff8118e8f0)
Location: kernel/printk/printk.c:637
Inline: True
Direct callers:
  - kernel/printk/printk.c:devkmsg_read
```
**Symbols:**

```
ffffffff8118e8f0-ffffffff8118e9b0: info_print_ext_header.constprop.0 (STB_LOCAL)
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
In kernel/printk/printk.c (ffffffff811a10ce)
Location: kernel/printk/printk.c:624
Inline: True
Inline callers:
  - kernel/printk/printk.c:printk_get_next_message
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
In kernel/printk/printk.c (ffffffff811b17ee)
Location: kernel/printk/printk.c:624
Inline: True
Inline callers:
  - kernel/printk/printk.c:printk_get_next_message
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
