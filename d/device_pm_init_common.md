# Function: <code>device_pm_init_common</code>

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
In drivers/base/core.c (ffffffff81546763)
Location: drivers/base/power/power.h:3
Inline: True
Inline callers:
  - drivers/base/core.c:device_initialize
```
```
In drivers/base/platform.c (ffffffff81facad3)
Location: drivers/base/power/power.h:3
Inline: True
Inline callers:
  - drivers/base/platform.c:early_platform_add_devices
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
In drivers/base/core.c (ffffffff815983e3)
Location: drivers/base/power/power.h:3
Inline: True
Inline callers:
  - drivers/base/core.c:device_initialize
```
```
In drivers/base/platform.c (ffffffff81fd94e7)
Location: drivers/base/power/power.h:3
Inline: True
Inline callers:
  - drivers/base/platform.c:early_platform_add_devices
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
In drivers/base/core.c (ffffffff815c5f33)
Location: drivers/base/power/power.h:3
Inline: True
Inline callers:
  - drivers/base/core.c:device_initialize
```
```
In drivers/base/platform.c (ffffffff820171a0)
Location: drivers/base/power/power.h:3
Inline: True
Inline callers:
  - drivers/base/platform.c:early_platform_add_devices
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
In drivers/base/core.c (ffffffff815dada3)
Location: drivers/base/power/power.h:3
Inline: True
Inline callers:
  - drivers/base/core.c:device_initialize
```
```
In drivers/base/platform.c (ffffffff820f8f10)
Location: drivers/base/power/power.h:3
Inline: True
Inline callers:
  - drivers/base/platform.c:early_platform_add_devices
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
In drivers/base/core.c (ffffffff81641d63)
Location: drivers/base/power/power.h:4
Inline: True
Inline callers:
  - drivers/base/core.c:device_initialize
```
```
In drivers/base/platform.c (ffffffff827025c4)
Location: drivers/base/power/power.h:4
Inline: True
Inline callers:
  - drivers/base/platform.c:early_platform_add_devices
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
In drivers/base/core.c (ffffffff8167cff3)
Location: drivers/base/power/power.h:4
Inline: True
Inline callers:
  - drivers/base/core.c:device_initialize
```
```
In drivers/base/platform.c (ffffffff8272c2fd)
Location: drivers/base/power/power.h:4
Inline: True
Inline callers:
  - drivers/base/platform.c:early_platform_add_devices
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
In drivers/base/core.c (ffffffff8169c983)
Location: drivers/base/power/power.h:4
Inline: True
Inline callers:
  - drivers/base/core.c:device_initialize
```
```
In drivers/base/platform.c (ffffffff828e4c59)
Location: drivers/base/power/power.h:4
Inline: True
Inline callers:
  - drivers/base/platform.c:early_platform_add_devices
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
In drivers/base/core.c (ffffffff816d5732)
Location: drivers/base/power/power.h:4
Inline: True
Inline callers:
  - drivers/base/core.c:device_initialize
```
```
In drivers/base/platform.c (ffffffff828ff3a1)
Location: drivers/base/power/power.h:4
Inline: True
Inline callers:
  - drivers/base/platform.c:early_platform_add_devices
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
In drivers/base/core.c (ffffffff816f9522)
Location: drivers/base/power/power.h:4
Inline: True
Inline callers:
  - drivers/base/core.c:device_initialize
```
```
In drivers/base/platform.c (ffffffff82908544)
Location: drivers/base/power/power.h:4
Inline: True
Inline callers:
  - drivers/base/platform.c:early_platform_add_devices
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
In drivers/base/core.c (ffffffff817b23f2)
Location: drivers/base/power/power.h:4
Inline: True
Inline callers:
  - drivers/base/core.c:device_initialize
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817c6e52)
Location: drivers/base/power/power.h:4
Inline: True
Inline callers:
  - drivers/base/core.c:device_initialize
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817aa312)
Location: drivers/base/power/power.h:4
Inline: True
Inline callers:
  - drivers/base/core.c:device_initialize
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff818334f2)
Location: drivers/base/power/power.h:4
Inline: True
Inline callers:
  - drivers/base/core.c:device_initialize
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81974c32)
Location: drivers/base/power/power.h:4
Inline: True
Inline callers:
  - drivers/base/core.c:device_initialize
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81ae0362)
Location: drivers/base/power/power.h:4
Inline: True
Inline callers:
  - drivers/base/core.c:device_initialize
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
In drivers/base/core.c (ffffffff81b2e582)
Location: drivers/base/power/power.h:4
Inline: True
Inline callers:
  - drivers/base/core.c:device_initialize
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
In drivers/base/core.c (ffffffff81b85d82)
Location: drivers/base/power/power.h:4
Inline: True
Inline callers:
  - drivers/base/core.c:device_initialize
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
In drivers/base/core.c (ffff8000108e37bc)
Location: drivers/base/power/power.h:4
Inline: True
Inline callers:
  - drivers/base/core.c:device_initialize
```
```
In drivers/base/platform.c (ffff800011496ec4)
Location: drivers/base/power/power.h:4
Inline: True
Inline callers:
  - drivers/base/platform.c:early_platform_add_devices
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
In drivers/base/core.c (c09d21e8)
Location: drivers/base/power/power.h:4
Inline: True
Inline callers:
  - drivers/base/core.c:device_initialize
```
```
In drivers/base/platform.c (c1597d18)
Location: drivers/base/power/power.h:4
Inline: True
Inline callers:
  - drivers/base/platform.c:early_platform_add_devices
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
In drivers/base/core.c (c0000000009788b8)
Location: drivers/base/power/power.h:4
Inline: True
Inline callers:
  - drivers/base/core.c:device_initialize
```
```
In drivers/base/platform.c (c0000000013aa508)
Location: drivers/base/power/power.h:4
Inline: True
Inline callers:
  - drivers/base/platform.c:early_platform_add_devices
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
In drivers/base/core.c (ffffffe000578aea)
Location: drivers/base/power/power.h:4
Inline: True
Inline callers:
  - drivers/base/core.c:device_initialize
```
```
In drivers/base/platform.c (ffffffe000030a88)
Location: drivers/base/power/power.h:4
Inline: True
Inline callers:
  - drivers/base/platform.c:early_platform_add_devices
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
In drivers/base/core.c (ffffffff816bed12)
Location: drivers/base/power/power.h:4
Inline: True
Inline callers:
  - drivers/base/core.c:device_initialize
```
```
In drivers/base/platform.c (ffffffff828efd15)
Location: drivers/base/power/power.h:4
Inline: True
Inline callers:
  - drivers/base/platform.c:early_platform_add_devices
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
In drivers/base/core.c (ffffffff81699fc2)
Location: drivers/base/power/power.h:4
Inline: True
Inline callers:
  - drivers/base/core.c:device_initialize
```
```
In drivers/base/platform.c (ffffffff828e71a1)
Location: drivers/base/power/power.h:4
Inline: True
Inline callers:
  - drivers/base/platform.c:early_platform_add_devices
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
In drivers/base/core.c (ffffffff816ed1e2)
Location: drivers/base/power/power.h:4
Inline: True
Inline callers:
  - drivers/base/core.c:device_initialize
```
```
In drivers/base/platform.c (ffffffff82903867)
Location: drivers/base/power/power.h:4
Inline: True
Inline callers:
  - drivers/base/platform.c:early_platform_add_devices
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
In drivers/base/core.c (ffffffff81707a22)
Location: drivers/base/power/power.h:4
Inline: True
Inline callers:
  - drivers/base/core.c:device_initialize
```
```
In drivers/base/platform.c (ffffffff829095a6)
Location: drivers/base/power/power.h:4
Inline: True
Inline callers:
  - drivers/base/platform.c:early_platform_add_devices
```
</details>
</li>
</ul>

## Differences
