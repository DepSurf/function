# Function: <code>xen_hvm_early_write</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_xen.c (ffffffff815504e9)
Location: drivers/tty/hvc/hvc_xen.c:609
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xen_raw_console_write
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
In drivers/tty/hvc/hvc_xen.c (ffffffff8157cd69)
Location: drivers/tty/hvc/hvc_xen.c:609
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xen_raw_console_write
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
In drivers/tty/hvc/hvc_xen.c (ffffffff81590fd7)
Location: drivers/tty/hvc/hvc_xen.c:609
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xen_raw_console_write
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/hvc/hvc_xen.c (ffffffff815f4f40)
Location: drivers/tty/hvc/hvc_xen.c:596
Inline: True
Direct callers:
  - drivers/tty/hvc/hvc_xen.c:xen_raw_console_write
```
**Symbols:**

```
ffffffff815f4f40-ffffffff815f502a: xen_hvm_early_write.isra.4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/hvc/hvc_xen.c (ffffffff8162ec0d)
Location: drivers/tty/hvc/hvc_xen.c:596
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xen_raw_console_write
Direct callers:
  - drivers/tty/hvc/hvc_xen.c:xen_raw_console_write
```
**Symbols:**

```
ffffffff8162dca0-ffffffff8162dcd6: xen_hvm_early_write.isra.6.part.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/hvc/hvc_xen.c (ffffffff8164c1e0)
Location: drivers/tty/hvc/hvc_xen.c:596
Inline: True
Direct callers:
  - drivers/tty/hvc/hvc_xen.c:xen_raw_console_write
```
**Symbols:**

```
ffffffff8164c1e0-ffffffff8164c2c4: xen_hvm_early_write.isra.6 (STB_LOCAL)
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
In drivers/tty/hvc/hvc_xen.c (ffffffff81680fd0)
Location: drivers/tty/hvc/hvc_xen.c:596
Inline: True
Direct callers:
  - drivers/tty/hvc/hvc_xen.c:xen_raw_console_write
```
**Symbols:**

```
ffffffff81680fd0-ffffffff816810af: xen_hvm_early_write.isra.0 (STB_LOCAL)
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
In drivers/tty/hvc/hvc_xen.c (ffffffff816a3680)
Location: drivers/tty/hvc/hvc_xen.c:596
Inline: True
Direct callers:
  - drivers/tty/hvc/hvc_xen.c:xen_raw_console_write
```
**Symbols:**

```
ffffffff816a3680-ffffffff816a375f: xen_hvm_early_write.isra.0 (STB_LOCAL)
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
In drivers/tty/hvc/hvc_xen.c (ffffffff81755be0)
Location: drivers/tty/hvc/hvc_xen.c:596
Inline: True
Direct callers:
  - drivers/tty/hvc/hvc_xen.c:xen_raw_console_write
```
**Symbols:**

```
ffffffff81755be0-ffffffff81755cc6: xen_hvm_early_write.constprop.0 (STB_LOCAL)
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
In drivers/tty/hvc/hvc_xen.c (ffffffff81770e50)
Location: drivers/tty/hvc/hvc_xen.c:596
Inline: True
Direct callers:
  - drivers/tty/hvc/hvc_xen.c:xen_raw_console_write
```
**Symbols:**

```
ffffffff81770e50-ffffffff81770f36: xen_hvm_early_write.constprop.0 (STB_LOCAL)
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
In drivers/tty/hvc/hvc_xen.c (ffffffff81754910)
Location: drivers/tty/hvc/hvc_xen.c:596
Inline: True
Direct callers:
  - drivers/tty/hvc/hvc_xen.c:xen_raw_console_write
```
**Symbols:**

```
ffffffff81754910-ffffffff817549f6: xen_hvm_early_write.constprop.0 (STB_LOCAL)
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
In drivers/tty/hvc/hvc_xen.c (ffffffff817d7fd0)
Location: drivers/tty/hvc/hvc_xen.c:631
Inline: True
Direct callers:
  - drivers/tty/hvc/hvc_xen.c:xen_raw_console_write
```
**Symbols:**

```
ffffffff817d7fd0-ffffffff817d80b3: xen_hvm_early_write.constprop.0 (STB_LOCAL)
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
In drivers/tty/hvc/hvc_xen.c (ffffffff81916240)
Location: drivers/tty/hvc/hvc_xen.c:632
Inline: True
Direct callers:
  - drivers/tty/hvc/hvc_xen.c:xen_raw_console_write
```
**Symbols:**

```
ffffffff81916240-ffffffff8191635d: xen_hvm_early_write.constprop.0 (STB_LOCAL)
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
In drivers/tty/hvc/hvc_xen.c (ffffffff81a71960)
Location: drivers/tty/hvc/hvc_xen.c:644
Inline: True
Direct callers:
  - drivers/tty/hvc/hvc_xen.c:xen_raw_console_write
```
**Symbols:**

```
ffffffff81a71960-ffffffff81a71a7a: xen_hvm_early_write.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/hvc/hvc_xen.c (ffffffff81abc210)
Location: drivers/tty/hvc/hvc_xen.c:659
Inline: True
Direct callers:
  - drivers/tty/hvc/hvc_xen.c:xen_raw_console_write
```
**Symbols:**

```
ffffffff81abc210-ffffffff81abc32a: xen_hvm_early_write.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/hvc/hvc_xen.c (ffffffff81b0ef60)
Location: drivers/tty/hvc/hvc_xen.c:677
Inline: True
Direct callers:
  - drivers/tty/hvc/hvc_xen.c:xen_raw_console_write
```
**Symbols:**

```
ffffffff81b0ef60-ffffffff81b0f07a: xen_hvm_early_write.constprop.0 (STB_LOCAL)
```
</details>
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
In drivers/tty/hvc/hvc_xen.c (0)
Location: drivers/tty/hvc/hvc_xen.c:602
Inline: True
```
</details>
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/hvc/hvc_xen.c (ffffffff816690e0)
Location: drivers/tty/hvc/hvc_xen.c:596
Inline: True
Direct callers:
  - drivers/tty/hvc/hvc_xen.c:xen_raw_console_write
```
**Symbols:**

```
ffffffff816690e0-ffffffff816691bf: xen_hvm_early_write.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/hvc/hvc_xen.c (ffffffff816974c0)
Location: drivers/tty/hvc/hvc_xen.c:596
Inline: True
Direct callers:
  - drivers/tty/hvc/hvc_xen.c:xen_raw_console_write
```
**Symbols:**

```
ffffffff816974c0-ffffffff8169759f: xen_hvm_early_write.isra.0 (STB_LOCAL)
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
In drivers/tty/hvc/hvc_xen.c (ffffffff816b1b80)
Location: drivers/tty/hvc/hvc_xen.c:596
Inline: True
Direct callers:
  - drivers/tty/hvc/hvc_xen.c:xen_raw_console_write
```
**Symbols:**

```
ffffffff816b1b80-ffffffff816b1c5f: xen_hvm_early_write.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
