# Function: <code>async_schedule_dev</code>

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
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff816dc024)
Location: include/linux/async.h:88
Inline: True
Inline callers:
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach
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
In drivers/base/dd.c (ffffffff81700054)
Location: include/linux/async.h:88
Inline: True
Inline callers:
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach
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
In drivers/base/dd.c (ffffffff817ba004)
Location: include/linux/async.h:88
Inline: True
Inline callers:
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach
```
```
In drivers/base/power/main.c (ffffffff817caa51)
Location: include/linux/async.h:88
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
In drivers/base/dd.c (ffffffff817cee54)
Location: include/linux/async.h:88
Inline: True
Inline callers:
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach
```
```
In drivers/base/power/main.c (ffffffff817df501)
Location: include/linux/async.h:88
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
In drivers/base/dd.c (ffffffff817b2865)
Location: include/linux/async.h:88
Inline: True
Inline callers:
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach
```
```
In drivers/base/power/main.c (ffffffff817c38e1)
Location: include/linux/async.h:88
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
In drivers/base/dd.c (ffffffff8183bc78)
Location: include/linux/async.h:88
Inline: True
Inline callers:
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach
```
```
In drivers/base/power/main.c (ffffffff8184dc71)
Location: include/linux/async.h:88
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
In drivers/base/dd.c (ffffffff8197e329)
Location: include/linux/async.h:88
Inline: True
Inline callers:
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach
```
```
In drivers/base/power/main.c (ffffffff81993300)
Location: include/linux/async.h:88
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
In drivers/base/dd.c (ffffffff81aeb1a5)
Location: include/linux/async.h:88
Inline: True
Inline callers:
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach
```
```
In drivers/base/power/main.c (ffffffff81b039b0)
Location: include/linux/async.h:88
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
In drivers/base/dd.c (ffffffff81b394a5)
Location: include/linux/async.h:88
Inline: True
Inline callers:
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach
```
```
In drivers/base/power/main.c (ffffffff81b51a10)
Location: include/linux/async.h:88
Inline: True
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
In drivers/base/dd.c (ffffffff81b90f65)
Location: include/linux/async.h:88
Inline: True
Inline callers:
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach
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
In drivers/base/dd.c (ffff8000108eb380)
Location: include/linux/async.h:88
Inline: True
Inline callers:
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach
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
In drivers/base/dd.c (c09d944c)
Location: include/linux/async.h:88
Inline: True
Inline callers:
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach
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
In drivers/base/dd.c (c000000000982970)
Location: include/linux/async.h:88
Inline: True
Inline callers:
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach
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
In drivers/base/dd.c (ffffffe00057efae)
Location: include/linux/async.h:88
Inline: True
Inline callers:
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach
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
In drivers/base/dd.c (ffffffff816c5844)
Location: include/linux/async.h:88
Inline: True
Inline callers:
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach
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
In drivers/base/dd.c (ffffffff816a0ac4)
Location: include/linux/async.h:88
Inline: True
Inline callers:
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach
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
In drivers/base/dd.c (ffffffff816f3d14)
Location: include/linux/async.h:88
Inline: True
Inline callers:
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach
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
In drivers/base/dd.c (ffffffff8170e544)
Location: include/linux/async.h:88
Inline: True
Inline callers:
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach
```
</details>
</li>
</ul>

## Differences
