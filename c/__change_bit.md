# Function: <code>__change_bit</code>

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
In drivers/input/input.c (ffffffff81669e20)
Location: arch/x86/include/asm/bitops.h:169
Inline: True
Inline callers:
  - drivers/input/input.c:input_handle_event
  - drivers/input/input.c:input_handle_event
  - drivers/input/input.c:input_handle_event
  - drivers/input/input.c:input_handle_event
```
```
In net/rfkill/input.c (ffffffff818126d7)
Location: arch/x86/include/asm/bitops.h:169
Inline: True
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
In drivers/input/input.c (ffffffff816c9f8f)
Location: arch/x86/include/asm/bitops.h:169
Inline: True
Inline callers:
  - drivers/input/input.c:input_handle_event
  - drivers/input/input.c:input_handle_event
  - drivers/input/input.c:input_handle_event
  - drivers/input/input.c:input_handle_event
```
```
In net/rfkill/input.c (ffffffff818855b7)
Location: arch/x86/include/asm/bitops.h:169
Inline: True
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
In drivers/input/input.c (ffffffff816f7f6f)
Location: arch/x86/include/asm/bitops.h:182
Inline: True
Inline callers:
  - drivers/input/input.c:input_handle_event
  - drivers/input/input.c:input_handle_event
  - drivers/input/input.c:input_handle_event
  - drivers/input/input.c:input_handle_event
```
```
In net/rfkill/input.c (ffffffff818b9e27)
Location: arch/x86/include/asm/bitops.h:182
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
In drivers/input/input.c (ffffffff8170d924)
Location: arch/x86/include/asm/bitops.h:182
Inline: True
Inline callers:
  - drivers/input/input.c:input_handle_event
  - drivers/input/input.c:input_handle_event
  - drivers/input/input.c:input_handle_event
  - drivers/input/input.c:input_handle_event
```
```
In net/rfkill/input.c (ffffffff818e0837)
Location: arch/x86/include/asm/bitops.h:182
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
In drivers/input/input.c (ffffffff8177eb6d)
Location: arch/x86/include/asm/bitops.h:183
Inline: True
Inline callers:
  - drivers/input/input.c:input_handle_event
  - drivers/input/input.c:input_handle_event
  - drivers/input/input.c:input_handle_event
  - drivers/input/input.c:input_handle_event
```
```
In net/rfkill/input.c (ffffffff81966547)
Location: arch/x86/include/asm/bitops.h:183
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
In drivers/input/input.c (ffffffff817bfbf1)
Location: arch/x86/include/asm/bitops.h:183
Inline: True
Inline callers:
  - drivers/input/input.c:input_handle_event
  - drivers/input/input.c:input_handle_event
  - drivers/input/input.c:input_handle_event
  - drivers/input/input.c:input_handle_event
```
```
In net/rfkill/input.c (ffffffff819bfe22)
Location: arch/x86/include/asm/bitops.h:183
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
In drivers/net/phy/phy_device.c (ffffffff8175c50d)
Location: arch/x86/include/asm/bitops.h:183
Inline: True
```
```
In drivers/input/input.c (ffffffff817e6f5b)
Location: arch/x86/include/asm/bitops.h:183
Inline: True
Inline callers:
  - drivers/input/input.c:input_handle_event
  - drivers/input/input.c:input_handle_event
  - drivers/input/input.c:input_handle_event
  - drivers/input/input.c:input_handle_event
```
```
In net/rfkill/input.c (ffffffff819f7052)
Location: arch/x86/include/asm/bitops.h:183
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
In drivers/net/phy/phy_device.c (ffffffff817999a2)
Location: include/asm-generic/bitops-instrumented.h:128
Inline: True
```
```
In drivers/input/input.c (ffffffff81827b01)
Location: include/asm-generic/bitops-instrumented.h:128
Inline: True
Inline callers:
  - drivers/input/input.c:input_handle_event
  - drivers/input/input.c:input_handle_event
  - drivers/input/input.c:input_handle_event
  - drivers/input/input.c:input_handle_event
```
```
In net/rfkill/input.c (ffffffff81a66594)
Location: include/asm-generic/bitops-instrumented.h:128
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
Location: include/asm-generic/bitops-instrumented.h:128
Inline: True
```
```
In drivers/input/input.c (ffffffff8185908f)
Location: include/asm-generic/bitops-instrumented.h:128
Inline: True
Inline callers:
  - drivers/input/input.c:input_handle_event
  - drivers/input/input.c:input_handle_event
  - drivers/input/input.c:input_handle_event
  - drivers/input/input.c:input_handle_event
```
```
In net/rfkill/input.c (ffffffff81a9d0b4)
Location: include/asm-generic/bitops-instrumented.h:128
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
Location: include/asm-generic/bitops/instrumented-non-atomic.h:55
Inline: True
Inline callers:
  - drivers/input/input.c:input_get_disposition
  - drivers/input/input.c:input_get_disposition
  - drivers/input/input.c:input_get_disposition
  - drivers/input/input.c:input_get_disposition
```
```
In net/rfkill/input.c (ffffffff81b98d31)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:55
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
Location: include/asm-generic/bitops/instrumented-non-atomic.h:55
Inline: True
Inline callers:
  - drivers/input/input.c:input_get_disposition
  - drivers/input/input.c:input_get_disposition
  - drivers/input/input.c:input_get_disposition
  - drivers/input/input.c:input_get_disposition
```
```
In net/rfkill/input.c (ffffffff81ba8a01)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:55
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
Location: include/asm-generic/bitops/instrumented-non-atomic.h:55
Inline: True
Inline callers:
  - drivers/input/input.c:input_get_disposition
  - drivers/input/input.c:input_get_disposition
```
```
In net/rfkill/input.c (ffffffff81b979a1)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:55
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
Location: include/asm-generic/bitops/instrumented-non-atomic.h:55
Inline: True
Inline callers:
  - drivers/input/input.c:input_get_disposition
  - drivers/input/input.c:input_get_disposition
```
```
In net/rfkill/input.c (ffffffff81c642c7)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:55
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
Location: include/asm-generic/bitops/instrumented-non-atomic.h:55
Inline: True
Inline callers:
  - drivers/input/input.c:input_get_disposition
  - drivers/input/input.c:input_get_disposition
  - drivers/input/input.c:input_get_disposition
```
```
In net/rfkill/input.c (ffffffff81e06fab)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:55
Inline: True
```
</details>
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
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (0)
Location: include/asm-generic/bitops/non-atomic.h:41
Inline: True
```
```
In drivers/input/input.c (ffff800010a980c4)
Location: include/asm-generic/bitops/non-atomic.h:41
Inline: True
Inline callers:
  - drivers/input/input.c:input_handle_event
  - drivers/input/input.c:input_handle_event
  - drivers/input/input.c:input_handle_event
  - drivers/input/input.c:input_handle_event
```
```
In net/rfkill/input.c (0)
Location: include/asm-generic/bitops/non-atomic.h:41
Inline: True
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
In drivers/net/phy/phy_device.c (c0abde04)
Location: include/asm-generic/bitops/non-atomic.h:41
Inline: True
```
```
In drivers/input/input.c (c0b7ae00)
Location: include/asm-generic/bitops/non-atomic.h:41
Inline: True
Inline callers:
  - drivers/input/input.c:input_handle_event
  - drivers/input/input.c:input_handle_event
  - drivers/input/input.c:input_handle_event
  - drivers/input/input.c:input_handle_event
```
```
In net/rfkill/input.c (c0e6b7a4)
Location: include/asm-generic/bitops/non-atomic.h:41
Inline: True
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
In drivers/net/phy/phy_device.c (c000000000a97c24)
Location: include/asm-generic/bitops/non-atomic.h:41
Inline: True
```
```
In drivers/input/input.c (c000000000b78bc4)
Location: include/asm-generic/bitops/non-atomic.h:41
Inline: True
Inline callers:
  - drivers/input/input.c:input_handle_event
  - drivers/input/input.c:input_handle_event
  - drivers/input/input.c:input_handle_event
  - drivers/input/input.c:input_handle_event
```
```
In net/rfkill/input.c (c000000000eab7e0)
Location: include/asm-generic/bitops/non-atomic.h:41
Inline: True
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
In drivers/net/phy/phy_device.c (ffffffe000621f16)
Location: include/asm-generic/bitops/non-atomic.h:41
Inline: True
```
```
In drivers/input/input.c (ffffffe0006a9dca)
Location: include/asm-generic/bitops/non-atomic.h:41
Inline: True
Inline callers:
  - drivers/input/input.c:input_handle_event
  - drivers/input/input.c:input_handle_event
  - drivers/input/input.c:input_handle_event
  - drivers/input/input.c:input_handle_event
```
```
In net/rfkill/input.c (ffffffe00089f884)
Location: include/asm-generic/bitops/non-atomic.h:41
Inline: True
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
In drivers/net/phy/phy_device.c (ffffffff81781f92)
Location: include/asm-generic/bitops-instrumented.h:128
Inline: True
```
```
In drivers/input/input.c (ffffffff8180e09f)
Location: include/asm-generic/bitops-instrumented.h:128
Inline: True
Inline callers:
  - drivers/input/input.c:input_handle_event
  - drivers/input/input.c:input_handle_event
  - drivers/input/input.c:input_handle_event
  - drivers/input/input.c:input_handle_event
```
```
In net/rfkill/input.c (ffffffff81a3c444)
Location: include/asm-generic/bitops-instrumented.h:128
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
Location: include/asm-generic/bitops-instrumented.h:128
Inline: True
```
```
In drivers/input/input.c (ffffffff817d57ef)
Location: include/asm-generic/bitops-instrumented.h:128
Inline: True
Inline callers:
  - drivers/input/input.c:input_handle_event
  - drivers/input/input.c:input_handle_event
  - drivers/input/input.c:input_handle_event
  - drivers/input/input.c:input_handle_event
```
```
In net/rfkill/input.c (ffffffff819f9064)
Location: include/asm-generic/bitops-instrumented.h:128
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
Location: include/asm-generic/bitops-instrumented.h:128
Inline: True
```
```
In drivers/input/input.c (ffffffff8184d21f)
Location: include/asm-generic/bitops-instrumented.h:128
Inline: True
Inline callers:
  - drivers/input/input.c:input_handle_event
  - drivers/input/input.c:input_handle_event
  - drivers/input/input.c:input_handle_event
  - drivers/input/input.c:input_handle_event
```
```
In net/rfkill/input.c (ffffffff81aa82f4)
Location: include/asm-generic/bitops-instrumented.h:128
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
Location: include/asm-generic/bitops-instrumented.h:128
Inline: True
```
```
In drivers/input/input.c (ffffffff818683cb)
Location: include/asm-generic/bitops-instrumented.h:128
Inline: True
Inline callers:
  - drivers/input/input.c:input_handle_event
  - drivers/input/input.c:input_handle_event
  - drivers/input/input.c:input_handle_event
  - drivers/input/input.c:input_handle_event
```
```
In net/rfkill/input.c (ffffffff81ab4854)
Location: include/asm-generic/bitops-instrumented.h:128
Inline: True
```
</details>
</li>
</ul>

## Differences
