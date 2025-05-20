# Function: <code>hub_is_port_power_switchable</code>

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
In drivers/usb/core/hub.c (ffffffff816072d6)
Location: drivers/usb/core/hub.h:124
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_power_on
  - drivers/usb/core/hub.c:hub_port_connect
```
```
In drivers/usb/core/port.c (ffffffff8161f539)
Location: drivers/usb/core/hub.h:124
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
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
In drivers/usb/core/hub.c (ffffffff81669605)
Location: drivers/usb/core/hub.h:128
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_power_on
```
```
In drivers/usb/core/port.c (ffffffff8167feec)
Location: drivers/usb/core/hub.h:128
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
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
In drivers/usb/core/hub.c (ffffffff81697335)
Location: drivers/usb/core/hub.h:128
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_power_on
```
```
In drivers/usb/core/port.c (ffffffff816adc29)
Location: drivers/usb/core/hub.h:128
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
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
In drivers/usb/core/hub.c (ffffffff816ac6e7)
Location: drivers/usb/core/hub.h:128
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_power_on
```
```
In drivers/usb/core/port.c (ffffffff816c2dd6)
Location: drivers/usb/core/hub.h:128
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
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
In drivers/usb/core/hub.c (ffffffff81717b97)
Location: drivers/usb/core/hub.h:120
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_power_on
```
```
In drivers/usb/core/port.c (ffffffff8172eba6)
Location: drivers/usb/core/hub.h:120
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
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
In drivers/usb/core/hub.c (ffffffff81756a3c)
Location: drivers/usb/core/hub.h:122
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_power_on
```
```
In drivers/usb/core/port.c (ffffffff8176dcc5)
Location: drivers/usb/core/hub.h:122
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
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
In drivers/usb/core/hub.c (ffffffff8177aedc)
Location: drivers/usb/core/hub.h:122
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_power_on
```
```
In drivers/usb/core/port.c (ffffffff81792345)
Location: drivers/usb/core/hub.h:122
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
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
In drivers/usb/core/hub.c (ffffffff817b8a47)
Location: drivers/usb/core/hub.h:124
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_power_on
```
```
In drivers/usb/core/port.c (ffffffff817d0c90)
Location: drivers/usb/core/hub.h:124
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
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
In drivers/usb/core/hub.c (ffffffff817e9297)
Location: drivers/usb/core/hub.h:124
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_power_on
```
```
In drivers/usb/core/port.c (ffffffff81801b90)
Location: drivers/usb/core/hub.h:124
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
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
In drivers/usb/core/hub.c (ffffffff818b85c7)
Location: drivers/usb/core/hub.h:124
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_power_on
```
```
In drivers/usb/core/port.c (ffffffff818d2415)
Location: drivers/usb/core/hub.h:124
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
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
In drivers/usb/core/hub.c (ffffffff818c6ec3)
Location: drivers/usb/core/hub.h:124
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_power_on
```
```
In drivers/usb/core/port.c (ffffffff818dc7f5)
Location: drivers/usb/core/hub.h:124
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
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
In drivers/usb/core/hub.c (ffffffff818aa25b)
Location: drivers/usb/core/hub.h:124
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_power_on
```
```
In drivers/usb/core/port.c (ffffffff818bfa84)
Location: drivers/usb/core/hub.h:124
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
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
In drivers/usb/core/hub.c (ffffffff8193f14b)
Location: drivers/usb/core/hub.h:124
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_power_on
```
```
In drivers/usb/core/port.c (ffffffff819560f4)
Location: drivers/usb/core/hub.h:124
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
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
In drivers/usb/core/hub.c (ffffffff81a971da)
Location: drivers/usb/core/hub.h:124
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_power_on
```
```
In drivers/usb/core/port.c (ffffffff81aafc86)
Location: drivers/usb/core/hub.h:124
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
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
In drivers/usb/core/hub.c (ffffffff81c19d93)
Location: drivers/usb/core/hub.h:133
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_power_on
```
```
In drivers/usb/core/port.c (ffffffff81c37ca6)
Location: drivers/usb/core/hub.h:133
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
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
In drivers/usb/core/hub.c (ffffffff81c80db3)
Location: drivers/usb/core/hub.h:137
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_power_on
```
```
In drivers/usb/core/port.c (ffffffff81c9f036)
Location: drivers/usb/core/hub.h:137
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
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
In drivers/usb/core/hub.c (ffffffff81d3577d)
Location: drivers/usb/core/hub.h:140
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_power_on
```
```
In drivers/usb/core/port.c (ffffffff81d53c84)
Location: drivers/usb/core/hub.h:140
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
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
In drivers/usb/core/hub.c (ffff800010a18b60)
Location: drivers/usb/core/hub.h:124
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_power_on
```
```
In drivers/usb/core/port.c (ffff800010a35ff0)
Location: drivers/usb/core/hub.h:124
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
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
In drivers/usb/core/hub.c (c0af0e00)
Location: drivers/usb/core/hub.h:124
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_power_on
```
```
In drivers/usb/core/port.c (c0b0950c)
Location: drivers/usb/core/hub.h:124
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
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
In drivers/usb/core/hub.c (c000000000ad1a4c)
Location: drivers/usb/core/hub.h:124
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_power_on
```
```
In drivers/usb/core/port.c (c000000000af408c)
Location: drivers/usb/core/hub.h:124
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
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
In drivers/usb/core/hub.c (ffffffe00063d5ba)
Location: drivers/usb/core/hub.h:124
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_power_on
```
```
In drivers/usb/core/port.c (ffffffe000653528)
Location: drivers/usb/core/hub.h:124
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
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
In drivers/usb/core/hub.c (ffffffff817a1677)
Location: drivers/usb/core/hub.h:124
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_power_on
```
```
In drivers/usb/core/port.c (ffffffff817b9f70)
Location: drivers/usb/core/hub.h:124
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
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
In drivers/usb/core/hub.c (ffffffff817934b7)
Location: drivers/usb/core/hub.h:124
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_power_on
```
```
In drivers/usb/core/port.c (ffffffff817ab9a0)
Location: drivers/usb/core/hub.h:124
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
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
In drivers/usb/core/hub.c (ffffffff817de117)
Location: drivers/usb/core/hub.h:124
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_power_on
```
```
In drivers/usb/core/port.c (ffffffff817f6a10)
Location: drivers/usb/core/hub.h:124
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
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
In drivers/usb/core/hub.c (ffffffff817f83f2)
Location: drivers/usb/core/hub.h:124
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_power_on
```
```
In drivers/usb/core/port.c (ffffffff81810c50)
Location: drivers/usb/core/hub.h:124
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
```
</details>
</li>
</ul>

## Differences
