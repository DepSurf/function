# Function: <code>msg_print_ext_header</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (ffffffff810d7270)
Location: kernel/printk/printk.c:531
Inline: True
Direct callers:
  - kernel/printk/printk.c:devkmsg_read
```
**Symbols:**

```
ffffffff810d7270-ffffffff810d72fd: msg_print_ext_header.constprop.23 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (ffffffff810dc220)
Location: kernel/printk/printk.c:641
Inline: True
Direct callers:
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:devkmsg_read
```
**Symbols:**

```
ffffffff810dc220-ffffffff810dc2b3: msg_print_ext_header.constprop.28 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810e352b)
Location: kernel/printk/printk.c:639
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:devkmsg_read
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810e2b1f)
Location: kernel/printk/printk.c:688
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:devkmsg_read
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810ea9e7)
Location: kernel/printk/printk.c:687
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:devkmsg_read
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810f2de5)
Location: kernel/printk/printk.c:691
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:devkmsg_read
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
In kernel/printk/printk.c (ffffffff810fe464)
Location: kernel/printk/printk.c:687
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:devkmsg_read
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (ffffffff81105ef0)
Location: kernel/printk/printk.c:704
Inline: True
Direct callers:
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:devkmsg_read
```
**Symbols:**

```
ffffffff81105ef0-ffffffff81105f8a: msg_print_ext_header.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (ffffffff81112280)
Location: kernel/printk/printk.c:714
Inline: True
Direct callers:
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:devkmsg_read
```
**Symbols:**

```
ffffffff81112280-ffffffff8111231a: msg_print_ext_header.constprop.0 (STB_LOCAL)
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
In kernel/printk/printk.c (ffffffff8111ee03)
Location: kernel/printk/printk.c:726
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:devkmsg_read
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
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (ffff800010172988)
Location: kernel/printk/printk.c:714
Inline: True
Direct callers:
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:devkmsg_read
```
**Symbols:**

```
ffff800010172988-ffff800010172a44: msg_print_ext_header.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (c03c5734)
Location: kernel/printk/printk.c:714
Inline: True
Direct callers:
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:devkmsg_read
```
**Symbols:**

```
c03c5734-c03c5820: msg_print_ext_header.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (c0000000001cc5b0)
Location: kernel/printk/printk.c:714
Inline: True
Direct callers:
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:devkmsg_read
```
**Symbols:**

```
c0000000001cc5b0-c0000000001cc674: msg_print_ext_header.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (ffffffe00010eda8)
Location: kernel/printk/printk.c:714
Inline: True
Direct callers:
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:devkmsg_read
```
**Symbols:**

```
ffffffe00010eda8-ffffffe00010ee1e: msg_print_ext_header.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (ffffffff8110a860)
Location: kernel/printk/printk.c:714
Inline: True
Direct callers:
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:devkmsg_read
```
**Symbols:**

```
ffffffff8110a860-ffffffff8110a8fa: msg_print_ext_header.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (ffffffff810fb810)
Location: kernel/printk/printk.c:714
Inline: True
Direct callers:
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:devkmsg_read
```
**Symbols:**

```
ffffffff810fb810-ffffffff810fb8aa: msg_print_ext_header.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (ffffffff81108750)
Location: kernel/printk/printk.c:714
Inline: True
Direct callers:
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:devkmsg_read
```
**Symbols:**

```
ffffffff81108750-ffffffff811087ea: msg_print_ext_header.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (ffffffff81113af0)
Location: kernel/printk/printk.c:714
Inline: True
Direct callers:
  - kernel/printk/printk.c:devkmsg_read
```
**Symbols:**

```
ffffffff81113af0-ffffffff81113b8a: msg_print_ext_header.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
