# Function: <code>hub_power_on_good_delay</code>

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
In drivers/usb/core/hub.c (ffffffff81607376)
Location: drivers/usb/core/hub.h:146
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_power_on
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/port.c (ffffffff8161ece1)
Location: drivers/usb/core/hub.h:146
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_port_runtime_resume
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
In drivers/usb/core/hub.c (ffffffff8166754d)
Location: drivers/usb/core/hub.h:150
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_power_on
```
```
In drivers/usb/core/port.c (ffffffff8167f551)
Location: drivers/usb/core/hub.h:150
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_port_runtime_resume
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
In drivers/usb/core/hub.c (ffffffff8169526a)
Location: drivers/usb/core/hub.h:150
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_power_on
```
```
In drivers/usb/core/port.c (ffffffff816ad291)
Location: drivers/usb/core/hub.h:150
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_port_runtime_resume
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
In drivers/usb/core/hub.c (ffffffff816aa708)
Location: drivers/usb/core/hub.h:150
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_power_on
```
```
In drivers/usb/core/port.c (ffffffff816c2465)
Location: drivers/usb/core/hub.h:150
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_port_runtime_resume
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
In drivers/usb/core/hub.c (ffffffff8171800d)
Location: drivers/usb/core/hub.h:142
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_power_on
```
```
In drivers/usb/core/port.c (ffffffff8172e235)
Location: drivers/usb/core/hub.h:142
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_port_runtime_resume
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
In drivers/usb/core/hub.c (ffffffff81756f19)
Location: drivers/usb/core/hub.h:144
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_power_on
```
```
In drivers/usb/core/port.c (ffffffff8176d29f)
Location: drivers/usb/core/hub.h:144
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_port_runtime_resume
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
In drivers/usb/core/hub.c (ffffffff8177b3b9)
Location: drivers/usb/core/hub.h:144
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_power_on
```
```
In drivers/usb/core/port.c (ffffffff817918ef)
Location: drivers/usb/core/hub.h:144
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_port_runtime_resume
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
In drivers/usb/core/hub.c (ffffffff817babea)
Location: drivers/usb/core/hub.h:146
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_power_on
```
```
In drivers/usb/core/port.c (ffffffff817d095c)
Location: drivers/usb/core/hub.h:146
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_port_runtime_resume
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
In drivers/usb/core/hub.c (ffffffff817e7847)
Location: drivers/usb/core/hub.h:146
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_power_cycle
  - drivers/usb/core/hub.c:hub_port_power_cycle
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_power_on
```
```
In drivers/usb/core/port.c (ffffffff81801849)
Location: drivers/usb/core/hub.h:146
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_port_runtime_resume
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
In drivers/usb/core/hub.c (ffffffff818b6f15)
Location: drivers/usb/core/hub.h:146
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_power_cycle
  - drivers/usb/core/hub.c:hub_port_power_cycle
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_power_on
```
```
In drivers/usb/core/port.c (ffffffff818d2179)
Location: drivers/usb/core/hub.h:146
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_port_runtime_resume
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
In drivers/usb/core/hub.c (ffffffff818c5825)
Location: drivers/usb/core/hub.h:146
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_power_cycle
  - drivers/usb/core/hub.c:hub_port_power_cycle
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_power_on
```
```
In drivers/usb/core/port.c (ffffffff818dc559)
Location: drivers/usb/core/hub.h:146
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_port_runtime_resume
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
In drivers/usb/core/hub.c (ffffffff818a8b03)
Location: drivers/usb/core/hub.h:146
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_power_cycle
  - drivers/usb/core/hub.c:hub_port_power_cycle
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_power_on
```
```
In drivers/usb/core/port.c (ffffffff818bf739)
Location: drivers/usb/core/hub.h:146
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_port_runtime_resume
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
In drivers/usb/core/hub.c (ffffffff8193da13)
Location: drivers/usb/core/hub.h:146
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_power_cycle
  - drivers/usb/core/hub.c:hub_port_power_cycle
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_power_on
```
```
In drivers/usb/core/port.c (ffffffff81955da9)
Location: drivers/usb/core/hub.h:146
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_port_runtime_resume
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
In drivers/usb/core/hub.c (ffffffff81a95753)
Location: drivers/usb/core/hub.h:146
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_power_cycle
  - drivers/usb/core/hub.c:hub_port_power_cycle
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_power_on
```
```
In drivers/usb/core/port.c (ffffffff81aaeff1)
Location: drivers/usb/core/hub.h:146
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_port_runtime_resume
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
In drivers/usb/core/hub.c (ffffffff81c1a526)
Location: drivers/usb/core/hub.h:155
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_power_on
```
```
In drivers/usb/core/port.c (ffffffff81c36af8)
Location: drivers/usb/core/hub.h:155
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_port_runtime_resume
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
In drivers/usb/core/hub.c (ffffffff81c8154d)
Location: drivers/usb/core/hub.h:159
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_power_on
```
```
In drivers/usb/core/port.c (ffffffff81c9dde8)
Location: drivers/usb/core/hub.h:159
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_port_runtime_resume
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
In drivers/usb/core/hub.c (ffffffff81d35f0b)
Location: drivers/usb/core/hub.h:162
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_power_on
```
```
In drivers/usb/core/port.c (ffffffff81d52998)
Location: drivers/usb/core/hub.h:162
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_port_runtime_resume
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
In drivers/usb/core/hub.c (ffff800010a168f4)
Location: drivers/usb/core/hub.h:146
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_power_cycle
  - drivers/usb/core/hub.c:hub_port_power_cycle
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_power_on
```
```
In drivers/usb/core/port.c (ffff800010a35c20)
Location: drivers/usb/core/hub.h:146
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_port_runtime_resume
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
In drivers/usb/core/hub.c (c0aeeb94)
Location: drivers/usb/core/hub.h:146
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_power_cycle
  - drivers/usb/core/hub.c:hub_port_power_cycle
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_power_on
```
```
In drivers/usb/core/port.c (c0b08a18)
Location: drivers/usb/core/hub.h:146
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_port_runtime_resume
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
In drivers/usb/core/hub.c (c000000000acf310)
Location: drivers/usb/core/hub.h:146
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_power_cycle
  - drivers/usb/core/hub.c:hub_port_power_cycle
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_power_on
```
```
In drivers/usb/core/port.c (c000000000af2ff4)
Location: drivers/usb/core/hub.h:146
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_port_runtime_resume
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
In drivers/usb/core/hub.c (ffffffe00063b98a)
Location: drivers/usb/core/hub.h:146
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_power_cycle
  - drivers/usb/core/hub.c:hub_port_power_cycle
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_power_on
```
```
In drivers/usb/core/port.c (ffffffe000652b08)
Location: drivers/usb/core/hub.h:146
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_port_runtime_resume
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
In drivers/usb/core/hub.c (ffffffff8179fc27)
Location: drivers/usb/core/hub.h:146
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_power_cycle
  - drivers/usb/core/hub.c:hub_port_power_cycle
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_power_on
```
```
In drivers/usb/core/port.c (ffffffff817b9c29)
Location: drivers/usb/core/hub.h:146
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_port_runtime_resume
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
In drivers/usb/core/hub.c (ffffffff817918a7)
Location: drivers/usb/core/hub.h:146
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_power_cycle
  - drivers/usb/core/hub.c:hub_port_power_cycle
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_power_on
```
```
In drivers/usb/core/port.c (ffffffff817ab659)
Location: drivers/usb/core/hub.h:146
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_port_runtime_resume
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
In drivers/usb/core/hub.c (ffffffff817dc6c7)
Location: drivers/usb/core/hub.h:146
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_power_cycle
  - drivers/usb/core/hub.c:hub_port_power_cycle
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_power_on
```
```
In drivers/usb/core/port.c (ffffffff817f66c9)
Location: drivers/usb/core/hub.h:146
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_port_runtime_resume
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
In drivers/usb/core/hub.c (ffffffff817f6957)
Location: drivers/usb/core/hub.h:146
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_power_cycle
  - drivers/usb/core/hub.c:hub_port_power_cycle
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_power_on
```
```
In drivers/usb/core/port.c (ffffffff81810909)
Location: drivers/usb/core/hub.h:146
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
</details>
</li>
</ul>

## Differences
