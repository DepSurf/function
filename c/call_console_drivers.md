# Function: <code>call_console_drivers</code>

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
In kernel/printk/printk.c (ffffffff810d7300)
Location: kernel/printk/printk.c:1433
Inline: True
```
**Symbols:**

```
ffffffff810d7300-ffffffff810d740c: call_console_drivers.constprop.26 (STB_LOCAL)
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
In kernel/printk/printk.c (ffffffff810dc2c0)
Location: kernel/printk/printk.c:1564
Inline: True
Direct callers:
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:console_unlock
```
**Symbols:**

```
ffffffff810dc2c0-ffffffff810dc3ab: call_console_drivers.isra.13.constprop.29 (STB_LOCAL)
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
In kernel/printk/printk.c (ffffffff810e32ef)
Location: kernel/printk/printk.c:1513
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_unlock
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
In kernel/printk/printk.c (ffffffff810e28c1)
Location: kernel/printk/printk.c:1563
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_unlock
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
In kernel/printk/printk.c (ffffffff810ea75a)
Location: kernel/printk/printk.c:1551
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_unlock
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
In kernel/printk/printk.c (ffffffff810f2b82)
Location: kernel/printk/printk.c:1695
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_unlock
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
In kernel/printk/printk.c (ffffffff810fe1dc)
Location: kernel/printk/printk.c:1714
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_unlock
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff81106908)
Location: kernel/printk/printk.c:1758
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_unlock
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff81112c98)
Location: kernel/printk/printk.c:1768
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_unlock
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (ffffffff8111dee0)
Location: kernel/printk/printk.c:1796
Inline: True
Direct callers:
  - kernel/printk/printk.c:console_unlock
```
**Symbols:**

```
ffffffff8111dee0-ffffffff8111e00f: call_console_drivers.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (ffffffff811187a0)
Location: kernel/printk/printk.c:1828
Inline: True
Direct callers:
  - kernel/printk/printk.c:console_unlock
```
**Symbols:**

```
ffffffff811187a0-ffffffff81118932: call_console_drivers.constprop.0 (STB_LOCAL)
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
In kernel/printk/printk.c (ffffffff81118e30)
Location: kernel/printk/printk.c:1904
Inline: True
Direct callers:
  - kernel/printk/printk.c:console_unlock
```
**Symbols:**

```
ffffffff81118e30-ffffffff81118fc2: call_console_drivers.constprop.0 (STB_LOCAL)
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
In kernel/printk/printk.c (ffffffff81139ce0)
Location: kernel/printk/printk.c:1895
Inline: True
Direct callers:
  - kernel/printk/printk.c:console_unlock
```
**Symbols:**

```
ffffffff81139ce0-ffffffff81139e72: call_console_drivers.constprop.0 (STB_LOCAL)
```
</details>
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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffff800010174084)
Location: kernel/printk/printk.c:1768
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_unlock
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
In kernel/printk/printk.c (c03c6300)
Location: kernel/printk/printk.c:1768
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_unlock
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (c0000000001cce00)
Location: kernel/printk/printk.c:1768
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_unlock
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
In kernel/printk/printk.c (ffffffe00010f446)
Location: kernel/printk/printk.c:1768
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_unlock
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8110b278)
Location: kernel/printk/printk.c:1768
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_unlock
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
In kernel/printk/printk.c (ffffffff810fc0eb)
Location: kernel/printk/printk.c:1768
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_unlock
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff81109168)
Location: kernel/printk/printk.c:1768
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_unlock
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8111446f)
Location: kernel/printk/printk.c:1768
Inline: True
```
</details>
</li>
</ul>

## Differences
