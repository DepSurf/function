# Function: <code>arch___change_bit</code>

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
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff817999a2)
Location: arch/x86/include/asm/bitops.h:118
Inline: True
```
```
In drivers/input/input.c (ffffffff81827b01)
Location: arch/x86/include/asm/bitops.h:118
Inline: True
Inline callers:
  - drivers/input/input.c:input_handle_event
  - drivers/input/input.c:input_handle_event
  - drivers/input/input.c:input_handle_event
  - drivers/input/input.c:input_handle_event
```
```
In net/rfkill/input.c (ffffffff81a66594)
Location: arch/x86/include/asm/bitops.h:118
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
In drivers/net/phy/phy_device.c (ffffffff817bd4c2)
Location: arch/x86/include/asm/bitops.h:117
Inline: True
```
```
In drivers/input/input.c (ffffffff8185908f)
Location: arch/x86/include/asm/bitops.h:117
Inline: True
Inline callers:
  - drivers/input/input.c:input_handle_event
  - drivers/input/input.c:input_handle_event
  - drivers/input/input.c:input_handle_event
  - drivers/input/input.c:input_handle_event
```
```
In net/rfkill/input.c (ffffffff81a9d0b4)
Location: arch/x86/include/asm/bitops.h:117
Inline: True
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
In drivers/input/input.c (ffffffff8192b576)
Location: arch/x86/include/asm/bitops.h:117
Inline: True
Inline callers:
  - drivers/input/input.c:input_get_disposition
  - drivers/input/input.c:input_get_disposition
  - drivers/input/input.c:input_get_disposition
  - drivers/input/input.c:input_get_disposition
```
```
In net/rfkill/input.c (ffffffff81b98d31)
Location: arch/x86/include/asm/bitops.h:117
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
In drivers/input/input.c (ffffffff81932c76)
Location: arch/x86/include/asm/bitops.h:117
Inline: True
Inline callers:
  - drivers/input/input.c:input_get_disposition
  - drivers/input/input.c:input_get_disposition
  - drivers/input/input.c:input_get_disposition
  - drivers/input/input.c:input_get_disposition
```
```
In net/rfkill/input.c (ffffffff81ba8a01)
Location: arch/x86/include/asm/bitops.h:117
Inline: True
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
In drivers/input/input.c (ffffffff819151da)
Location: arch/x86/include/asm/bitops.h:117
Inline: True
Inline callers:
  - drivers/input/input.c:input_get_disposition
  - drivers/input/input.c:input_get_disposition
```
```
In net/rfkill/input.c (ffffffff81b979a1)
Location: arch/x86/include/asm/bitops.h:117
Inline: True
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
In drivers/input/input.c (ffffffff819b7384)
Location: arch/x86/include/asm/bitops.h:117
Inline: True
Inline callers:
  - drivers/input/input.c:input_get_disposition
  - drivers/input/input.c:input_get_disposition
```
```
In net/rfkill/input.c (ffffffff81c642c7)
Location: arch/x86/include/asm/bitops.h:117
Inline: True
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
In drivers/input/input.c (ffffffff81b1720e)
Location: arch/x86/include/asm/bitops.h:117
Inline: True
Inline callers:
  - drivers/input/input.c:input_get_disposition
  - drivers/input/input.c:input_get_disposition
  - drivers/input/input.c:input_get_disposition
```
```
In net/rfkill/input.c (ffffffff81e06fab)
Location: arch/x86/include/asm/bitops.h:117
Inline: True
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
In drivers/input/input.c (ffffffff81ca8c9f)
Location: arch/x86/include/asm/bitops.h:117
Inline: True
```
```
In net/rfkill/input.c (ffffffff81fdc3ab)
Location: arch/x86/include/asm/bitops.h:117
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
In drivers/input/input.c (ffffffff81d10135)
Location: arch/x86/include/asm/bitops.h:117
Inline: True
```
```
In net/rfkill/input.c (ffffffff8205808b)
Location: arch/x86/include/asm/bitops.h:117
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
In drivers/input/input.c (ffffffff81dc5d35)
Location: arch/x86/include/asm/bitops.h:116
Inline: True
```
```
In net/rfkill/input.c (ffffffff8212ab9b)
Location: arch/x86/include/asm/bitops.h:116
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
In drivers/net/phy/phy_device.c (ffffffff81781f92)
Location: arch/x86/include/asm/bitops.h:117
Inline: True
```
```
In drivers/input/input.c (ffffffff8180e09f)
Location: arch/x86/include/asm/bitops.h:117
Inline: True
Inline callers:
  - drivers/input/input.c:input_handle_event
  - drivers/input/input.c:input_handle_event
  - drivers/input/input.c:input_handle_event
  - drivers/input/input.c:input_handle_event
```
```
In net/rfkill/input.c (ffffffff81a3c444)
Location: arch/x86/include/asm/bitops.h:117
Inline: True
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
In drivers/net/phy/phy_device.c (ffffffff81761d22)
Location: arch/x86/include/asm/bitops.h:117
Inline: True
```
```
In drivers/input/input.c (ffffffff817d57ef)
Location: arch/x86/include/asm/bitops.h:117
Inline: True
Inline callers:
  - drivers/input/input.c:input_handle_event
  - drivers/input/input.c:input_handle_event
  - drivers/input/input.c:input_handle_event
  - drivers/input/input.c:input_handle_event
```
```
In net/rfkill/input.c (ffffffff819f9064)
Location: arch/x86/include/asm/bitops.h:117
Inline: True
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
In drivers/net/phy/phy_device.c (ffffffff817b2342)
Location: arch/x86/include/asm/bitops.h:117
Inline: True
```
```
In drivers/input/input.c (ffffffff8184d21f)
Location: arch/x86/include/asm/bitops.h:117
Inline: True
Inline callers:
  - drivers/input/input.c:input_handle_event
  - drivers/input/input.c:input_handle_event
  - drivers/input/input.c:input_handle_event
  - drivers/input/input.c:input_handle_event
```
```
In net/rfkill/input.c (ffffffff81aa82f4)
Location: arch/x86/include/asm/bitops.h:117
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
In drivers/net/phy/phy_device.c (ffffffff817cc2d2)
Location: arch/x86/include/asm/bitops.h:117
Inline: True
```
```
In drivers/input/input.c (ffffffff818683cb)
Location: arch/x86/include/asm/bitops.h:117
Inline: True
Inline callers:
  - drivers/input/input.c:input_handle_event
  - drivers/input/input.c:input_handle_event
  - drivers/input/input.c:input_handle_event
  - drivers/input/input.c:input_handle_event
```
```
In net/rfkill/input.c (ffffffff81ab4854)
Location: arch/x86/include/asm/bitops.h:117
Inline: True
```
</details>
</li>
</ul>

## Differences
