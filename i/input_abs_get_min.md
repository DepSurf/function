# Function: <code>input_abs_get_min</code>

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
In drivers/input/mousedev.c (ffffffff8166c0d0)
Location: include/linux/input.h:459
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
```
```
In drivers/input/misc/uinput.c (ffffffff81672a8d)
Location: include/linux/input.h:459
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_write
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/input/mousedev.c (ffffffff816cc126)
Location: include/linux/input.h:459
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
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
In drivers/input/mousedev.c (ffffffff816fa0d6)
Location: include/linux/input.h:459
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
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
In drivers/input/mousedev.c (ffffffff8170fc34)
Location: include/linux/input.h:464
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
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
In drivers/input/mousedev.c (ffffffff81780eba)
Location: include/linux/input.h:468
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
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
In drivers/input/mousedev.c (ffffffff817c21d3)
Location: include/linux/input.h:468
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
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
In drivers/input/mousedev.c (ffffffff817e96d3)
Location: include/linux/input.h:468
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
```
```
In drivers/input/touchscreen/of_touchscreen.c (ffffffff817ee8cd)
Location: include/linux/input.h:468
Inline: True
Inline callers:
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
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
In drivers/input/mousedev.c (ffffffff8182a970)
Location: include/linux/input.h:465
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
```
```
In drivers/input/touchscreen/of_touchscreen.c (ffffffff8182f4cd)
Location: include/linux/input.h:465
Inline: True
Inline callers:
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
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
In drivers/input/mousedev.c (ffffffff8185c300)
Location: include/linux/input.h:486
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
```
```
In drivers/input/touchscreen/of_touchscreen.c (ffffffff81860dfd)
Location: include/linux/input.h:486
Inline: True
Inline callers:
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
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
In drivers/input/mousedev.c (ffffffff8192ef32)
Location: include/linux/input.h:487
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
```
```
In drivers/input/touchscreen/of_touchscreen.c (ffffffff819340ce)
Location: include/linux/input.h:487
Inline: True
Inline callers:
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
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
In drivers/input/mousedev.c (ffffffff819362d2)
Location: include/linux/input.h:495
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
```
```
In drivers/input/touchscreen/of_touchscreen.c (ffffffff8193b14e)
Location: include/linux/input.h:495
Inline: True
Inline callers:
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
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
In drivers/input/touchscreen.c (ffffffff819184fe)
Location: include/linux/input.h:495
Inline: True
Inline callers:
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
```
```
In drivers/input/mousedev.c (ffffffff8191913a)
Location: include/linux/input.h:495
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
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
In drivers/input/touchscreen.c (ffffffff819ba80e)
Location: include/linux/input.h:495
Inline: True
Inline callers:
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
```
```
In drivers/input/mousedev.c (ffffffff819bb4fa)
Location: include/linux/input.h:495
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
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
In drivers/input/touchscreen.c (ffffffff81b1a58e)
Location: include/linux/input.h:497
Inline: True
Inline callers:
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
```
```
In drivers/input/mousedev.c (ffffffff81b1b53c)
Location: include/linux/input.h:497
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
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
In drivers/input/touchscreen.c (ffffffff81cac2ce)
Location: include/linux/input.h:497
Inline: True
Inline callers:
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
```
```
In drivers/input/mousedev.c (ffffffff81cad347)
Location: include/linux/input.h:497
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
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
In drivers/input/touchscreen.c (ffffffff81d138ae)
Location: include/linux/input.h:497
Inline: True
Inline callers:
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
```
```
In drivers/input/mousedev.c (ffffffff81d14927)
Location: include/linux/input.h:497
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
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
In drivers/input/touchscreen.c (ffffffff81dc94de)
Location: include/linux/input.h:497
Inline: True
Inline callers:
  - drivers/input/touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen.c:touchscreen_parse_properties
```
```
In drivers/input/mousedev.c (ffffffff81dca547)
Location: include/linux/input.h:497
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
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
In drivers/input/mousedev.c (ffff800010a9cb80)
Location: include/linux/input.h:486
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
```
```
In drivers/input/touchscreen/of_touchscreen.c (ffff800010aa3778)
Location: include/linux/input.h:486
Inline: True
Inline callers:
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
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
In drivers/input/mousedev.c (c0b7dd98)
Location: include/linux/input.h:486
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
```
```
In drivers/input/touchscreen/of_touchscreen.c (c0b82fd8)
Location: include/linux/input.h:486
Inline: True
Inline callers:
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
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
In drivers/input/mousedev.c (c000000000b7c788)
Location: include/linux/input.h:486
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
```
```
In drivers/input/touchscreen/of_touchscreen.c (c000000000b843c0)
Location: include/linux/input.h:486
Inline: True
Inline callers:
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
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
In drivers/input/mousedev.c (ffffffe0006ac16a)
Location: include/linux/input.h:486
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
```
```
In drivers/input/touchscreen/of_touchscreen.c (ffffffe0006b0e80)
Location: include/linux/input.h:486
Inline: True
Inline callers:
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
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
In drivers/input/mousedev.c (ffffffff81811310)
Location: include/linux/input.h:486
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
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
In drivers/input/mousedev.c (ffffffff817d8a50)
Location: include/linux/input.h:486
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
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
In drivers/input/mousedev.c (ffffffff81850490)
Location: include/linux/input.h:486
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
```
```
In drivers/input/touchscreen/of_touchscreen.c (ffffffff81854f8d)
Location: include/linux/input.h:486
Inline: True
Inline callers:
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
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
In drivers/input/mousedev.c (ffffffff8186b610)
Location: include/linux/input.h:486
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
```
```
In drivers/input/touchscreen/of_touchscreen.c (ffffffff818700bd)
Location: include/linux/input.h:486
Inline: True
Inline callers:
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_parse_properties
```
</details>
</li>
</ul>

## Differences
