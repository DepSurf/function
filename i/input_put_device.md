# Function: <code>input_put_device</code>

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
In drivers/input/input.c (ffffffff816677c6)
Location: include/linux/input.h:342
Inline: True
Inline callers:
  - drivers/input/input.c:devm_input_device_release
  - drivers/input/input.c:input_free_device
```
```
In drivers/input/mousedev.c (ffffffff8166ba08)
Location: include/linux/input.h:342
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_free
```
```
In drivers/input/evdev.c (ffffffff8166cec8)
Location: include/linux/input.h:342
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_free
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
In drivers/input/input.c (ffffffff816c7abb)
Location: include/linux/input.h:342
Inline: True
Inline callers:
  - drivers/input/input.c:input_free_device
  - drivers/input/input.c:devm_input_device_release
```
```
In drivers/input/mousedev.c (ffffffff816cba58)
Location: include/linux/input.h:342
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_free
```
```
In drivers/input/evdev.c (ffffffff816cd208)
Location: include/linux/input.h:342
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_free
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
In drivers/input/input.c (ffffffff816f5aab)
Location: include/linux/input.h:342
Inline: True
Inline callers:
  - drivers/input/input.c:input_free_device
  - drivers/input/input.c:devm_input_device_release
```
```
In drivers/input/mousedev.c (ffffffff816f9a05)
Location: include/linux/input.h:342
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_free
```
```
In drivers/input/evdev.c (ffffffff816fb1a8)
Location: include/linux/input.h:342
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_free
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
In drivers/input/input.c (ffffffff8170b5fb)
Location: include/linux/input.h:347
Inline: True
Inline callers:
  - drivers/input/input.c:input_free_device
  - drivers/input/input.c:devm_input_device_release
```
```
In drivers/input/mousedev.c (ffffffff8170f565)
Location: include/linux/input.h:347
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_free
```
```
In drivers/input/evdev.c (ffffffff81710b88)
Location: include/linux/input.h:347
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_free
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
In drivers/input/input.c (ffffffff8177c7fb)
Location: include/linux/input.h:351
Inline: True
Inline callers:
  - drivers/input/input.c:input_free_device
  - drivers/input/input.c:devm_input_device_release
```
```
In drivers/input/mousedev.c (ffffffff817807e5)
Location: include/linux/input.h:351
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_free
```
```
In drivers/input/evdev.c (ffffffff81781e08)
Location: include/linux/input.h:351
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_free
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
In drivers/input/input.c (ffffffff817bd8ab)
Location: include/linux/input.h:351
Inline: True
Inline callers:
  - drivers/input/input.c:input_free_device
  - drivers/input/input.c:devm_input_device_release
```
```
In drivers/input/mousedev.c (ffffffff817c1865)
Location: include/linux/input.h:351
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_free
```
```
In drivers/input/evdev.c (ffffffff817c2e48)
Location: include/linux/input.h:351
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_free
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
In drivers/input/input.c (ffffffff817e4d0b)
Location: include/linux/input.h:351
Inline: True
Inline callers:
  - drivers/input/input.c:input_free_device
  - drivers/input/input.c:devm_input_device_release
```
```
In drivers/input/mousedev.c (ffffffff817e8d55)
Location: include/linux/input.h:351
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_free
```
```
In drivers/input/evdev.c (ffffffff817ea6f8)
Location: include/linux/input.h:351
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_free
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
In drivers/input/input.c (ffffffff8182575b)
Location: include/linux/input.h:348
Inline: True
Inline callers:
  - drivers/input/input.c:input_free_device
  - drivers/input/input.c:devm_input_device_release
```
```
In drivers/input/mousedev.c (ffffffff81829a86)
Location: include/linux/input.h:348
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_free
```
```
In drivers/input/evdev.c (ffffffff8182b1f9)
Location: include/linux/input.h:348
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_free
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
In drivers/input/input.c (ffffffff81856c0b)
Location: include/linux/input.h:360
Inline: True
Inline callers:
  - drivers/input/input.c:input_free_device
  - drivers/input/input.c:devm_input_device_release
```
```
In drivers/input/mousedev.c (ffffffff8185b416)
Location: include/linux/input.h:360
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_free
```
```
In drivers/input/evdev.c (ffffffff8185cb69)
Location: include/linux/input.h:360
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_free
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
In drivers/input/input.c (ffffffff81928ddb)
Location: include/linux/input.h:360
Inline: True
Inline callers:
  - drivers/input/input.c:input_free_device
  - drivers/input/input.c:devm_input_device_release
```
```
In drivers/input/mousedev.c (ffffffff8192def6)
Location: include/linux/input.h:360
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_free
```
```
In drivers/input/evdev.c (ffffffff8192f8f9)
Location: include/linux/input.h:360
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_free
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
In drivers/input/input.c (ffffffff8193033b)
Location: include/linux/input.h:368
Inline: True
Inline callers:
  - drivers/input/input.c:input_free_device
  - drivers/input/input.c:devm_input_device_release
```
```
In drivers/input/mousedev.c (ffffffff81935286)
Location: include/linux/input.h:368
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_free
```
```
In drivers/input/evdev.c (ffffffff81936c06)
Location: include/linux/input.h:368
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_free
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
In drivers/input/input.c (ffffffff8191359b)
Location: include/linux/input.h:368
Inline: True
Inline callers:
  - drivers/input/input.c:input_free_device
  - drivers/input/input.c:devm_input_device_release
```
```
In drivers/input/mousedev.c (ffffffff81918b16)
Location: include/linux/input.h:368
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_free
```
```
In drivers/input/evdev.c (ffffffff8191a486)
Location: include/linux/input.h:368
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_free
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
In drivers/input/input.c (ffffffff819b589c)
Location: include/linux/input.h:368
Inline: True
Inline callers:
  - drivers/input/input.c:input_free_device
  - drivers/input/input.c:devm_input_device_release
```
```
In drivers/input/mousedev.c (ffffffff819bae16)
Location: include/linux/input.h:368
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_free
```
```
In drivers/input/evdev.c (ffffffff819bc8a6)
Location: include/linux/input.h:368
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_free
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
In drivers/input/input.c (ffffffff81b152fc)
Location: include/linux/input.h:368
Inline: True
Inline callers:
  - drivers/input/input.c:input_free_device
  - drivers/input/input.c:devm_input_device_release
```
```
In drivers/input/mousedev.c (ffffffff81b1b115)
Location: include/linux/input.h:368
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_free
```
```
In drivers/input/evdev.c (ffffffff81b1ca25)
Location: include/linux/input.h:368
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_free
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
In drivers/input/input.c (ffffffff81ca656c)
Location: include/linux/input.h:368
Inline: True
Inline callers:
  - drivers/input/input.c:input_free_device
  - drivers/input/input.c:devm_input_device_release
```
```
In drivers/input/mousedev.c (ffffffff81caceb5)
Location: include/linux/input.h:368
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_free
```
```
In drivers/input/evdev.c (ffffffff81cae965)
Location: include/linux/input.h:368
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_free
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
In drivers/input/input.c (ffffffff81d0dcac)
Location: include/linux/input.h:368
Inline: True
Inline callers:
  - drivers/input/input.c:input_free_device
  - drivers/input/input.c:devm_input_device_release
```
```
In drivers/input/mousedev.c (ffffffff81d14495)
Location: include/linux/input.h:368
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_free
```
```
In drivers/input/evdev.c (ffffffff81d15f55)
Location: include/linux/input.h:368
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_free
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
In drivers/input/input.c (ffffffff81dc38cc)
Location: include/linux/input.h:368
Inline: True
Inline callers:
  - drivers/input/input.c:input_free_device
  - drivers/input/input.c:devm_input_device_release
```
```
In drivers/input/mousedev.c (ffffffff81dca0b5)
Location: include/linux/input.h:368
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_free
```
```
In drivers/input/evdev.c (ffffffff81dcbbd5)
Location: include/linux/input.h:368
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_free
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
In drivers/input/input.c (ffff800010a95e24)
Location: include/linux/input.h:360
Inline: True
Inline callers:
  - drivers/input/input.c:input_free_device
  - drivers/input/input.c:devm_input_device_release
```
```
In drivers/input/mousedev.c (ffff800010a9b5c0)
Location: include/linux/input.h:360
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_free
```
```
In drivers/input/evdev.c (ffff800010a9d5a0)
Location: include/linux/input.h:360
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_free
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
In drivers/input/input.c (c0b78ad0)
Location: include/linux/input.h:360
Inline: True
Inline callers:
  - drivers/input/input.c:input_free_device
  - drivers/input/input.c:devm_input_device_release
```
```
In drivers/input/mousedev.c (c0b7d484)
Location: include/linux/input.h:360
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_free
```
```
In drivers/input/evdev.c (c0b7f048)
Location: include/linux/input.h:360
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_free
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
In drivers/input/input.c (c000000000b753b4)
Location: include/linux/input.h:360
Inline: True
Inline callers:
  - drivers/input/input.c:input_free_device
  - drivers/input/input.c:devm_input_device_release
```
```
In drivers/input/mousedev.c (c000000000b7be98)
Location: include/linux/input.h:360
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_free
```
```
In drivers/input/evdev.c (c000000000b7e8a8)
Location: include/linux/input.h:360
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_free
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
In drivers/input/input.c (ffffffe0006a7812)
Location: include/linux/input.h:360
Inline: True
Inline callers:
  - drivers/input/input.c:input_free_device
  - drivers/input/input.c:devm_input_device_release
```
```
In drivers/input/mousedev.c (ffffffe0006abc7c)
Location: include/linux/input.h:360
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_free
```
```
In drivers/input/evdev.c (ffffffe0006ad510)
Location: include/linux/input.h:360
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_free
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
In drivers/input/input.c (ffffffff8180bc1b)
Location: include/linux/input.h:360
Inline: True
Inline callers:
  - drivers/input/input.c:input_free_device
  - drivers/input/input.c:devm_input_device_release
```
```
In drivers/input/mousedev.c (ffffffff81810426)
Location: include/linux/input.h:360
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_free
```
```
In drivers/input/evdev.c (ffffffff81811b79)
Location: include/linux/input.h:360
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_free
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
In drivers/input/input.c (ffffffff817d338b)
Location: include/linux/input.h:360
Inline: True
Inline callers:
  - drivers/input/input.c:input_free_device
  - drivers/input/input.c:devm_input_device_release
```
```
In drivers/input/mousedev.c (ffffffff817d7b76)
Location: include/linux/input.h:360
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_free
```
```
In drivers/input/evdev.c (ffffffff817d92b9)
Location: include/linux/input.h:360
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_free
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
In drivers/input/input.c (ffffffff8184ad9b)
Location: include/linux/input.h:360
Inline: True
Inline callers:
  - drivers/input/input.c:input_free_device
  - drivers/input/input.c:devm_input_device_release
```
```
In drivers/input/mousedev.c (ffffffff8184f5a6)
Location: include/linux/input.h:360
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_free
```
```
In drivers/input/evdev.c (ffffffff81850cf9)
Location: include/linux/input.h:360
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_free
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
In drivers/input/input.c (ffffffff81865feb)
Location: include/linux/input.h:360
Inline: True
Inline callers:
  - drivers/input/input.c:input_free_device
  - drivers/input/input.c:devm_input_device_release
```
```
In drivers/input/mousedev.c (ffffffff8186a9b6)
Location: include/linux/input.h:360
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_free
```
```
In drivers/input/evdev.c (ffffffff8186c1b9)
Location: include/linux/input.h:360
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_free
```
</details>
</li>
</ul>

## Differences
