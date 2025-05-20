# Function: <code>driver_match_device</code>

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
In drivers/base/bus.c (ffffffff8154a1ad)
Location: drivers/base/base.h:114
Inline: True
Inline callers:
  - drivers/base/bus.c:bind_store
```
```
In drivers/base/dd.c (ffffffff8154bf9e)
Location: drivers/base/base.h:114
Inline: True
Inline callers:
  - drivers/base/dd.c:__device_attach_driver
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
In drivers/base/bus.c (ffffffff8159bded)
Location: drivers/base/base.h:114
Inline: True
Inline callers:
  - drivers/base/bus.c:bind_store
```
```
In drivers/base/dd.c (ffffffff8159dcd8)
Location: drivers/base/base.h:114
Inline: True
Inline callers:
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach_driver
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
In drivers/base/bus.c (ffffffff815ca34d)
Location: drivers/base/base.h:117
Inline: True
Inline callers:
  - drivers/base/bus.c:bind_store
```
```
In drivers/base/dd.c (ffffffff815cc098)
Location: drivers/base/base.h:117
Inline: True
Inline callers:
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach_driver
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
In drivers/base/bus.c (ffffffff815defe7)
Location: drivers/base/base.h:117
Inline: True
Inline callers:
  - drivers/base/bus.c:bind_store
```
```
In drivers/base/dd.c (ffffffff815e0c58)
Location: drivers/base/base.h:117
Inline: True
Inline callers:
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach_driver
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
In drivers/base/bus.c (ffffffff81646017)
Location: drivers/base/base.h:118
Inline: True
Inline callers:
  - drivers/base/bus.c:bind_store
```
```
In drivers/base/dd.c (ffffffff81647d58)
Location: drivers/base/base.h:118
Inline: True
Inline callers:
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach_driver
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
In drivers/base/bus.c (ffffffff81681462)
Location: drivers/base/base.h:118
Inline: True
Inline callers:
  - drivers/base/bus.c:bind_store
```
```
In drivers/base/dd.c (ffffffff81683205)
Location: drivers/base/base.h:118
Inline: True
Inline callers:
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach_driver
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
In drivers/base/bus.c (ffffffff816a0f02)
Location: drivers/base/base.h:116
Inline: True
Inline callers:
  - drivers/base/bus.c:bind_store
```
```
In drivers/base/dd.c (ffffffff816a2f05)
Location: drivers/base/base.h:116
Inline: True
Inline callers:
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach_driver
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
In drivers/base/bus.c (ffffffff816d9df9)
Location: drivers/base/base.h:126
Inline: True
Inline callers:
  - drivers/base/bus.c:bind_store
```
```
In drivers/base/dd.c (ffffffff816dbef5)
Location: drivers/base/base.h:126
Inline: True
Inline callers:
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach_driver
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
In drivers/base/bus.c (ffffffff816fdda9)
Location: drivers/base/base.h:126
Inline: True
Inline callers:
  - drivers/base/bus.c:bind_store
```
```
In drivers/base/dd.c (ffffffff816fff25)
Location: drivers/base/base.h:126
Inline: True
Inline callers:
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach_driver
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
In drivers/base/bus.c (ffffffff817b79f3)
Location: drivers/base/base.h:137
Inline: True
Inline callers:
  - drivers/base/bus.c:bind_store
```
```
In drivers/base/dd.c (ffffffff817b9ed5)
Location: drivers/base/base.h:137
Inline: True
Inline callers:
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach_driver
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
In drivers/base/bus.c (ffffffff817cc713)
Location: drivers/base/base.h:144
Inline: True
Inline callers:
  - drivers/base/bus.c:bind_store
```
```
In drivers/base/dd.c (ffffffff817ced25)
Location: drivers/base/base.h:144
Inline: True
Inline callers:
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach_driver
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
In drivers/base/bus.c (ffffffff817b0083)
Location: drivers/base/base.h:144
Inline: True
Inline callers:
  - drivers/base/bus.c:bind_store
```
```
In drivers/base/dd.c (ffffffff817b2745)
Location: drivers/base/base.h:144
Inline: True
Inline callers:
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach_driver
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
In drivers/base/bus.c (ffffffff8183929b)
Location: drivers/base/base.h:144
Inline: True
Inline callers:
  - drivers/base/bus.c:bind_store
```
```
In drivers/base/dd.c (ffffffff8183bac5)
Location: drivers/base/base.h:144
Inline: True
Inline callers:
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach_driver
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
In drivers/base/bus.c (ffffffff8197b8cb)
Location: drivers/base/base.h:144
Inline: True
Inline callers:
  - drivers/base/bus.c:bind_store
```
```
In drivers/base/dd.c (ffffffff8197e165)
Location: drivers/base/base.h:144
Inline: True
Inline callers:
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach_driver
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
In drivers/base/bus.c (ffffffff81ae899b)
Location: drivers/base/base.h:144
Inline: True
Inline callers:
  - drivers/base/bus.c:bind_store
```
```
In drivers/base/dd.c (ffffffff81aeafc5)
Location: drivers/base/base.h:144
Inline: True
Inline callers:
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach_driver
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
In drivers/base/bus.c (ffffffff81b368fd)
Location: drivers/base/base.h:164
Inline: True
Inline callers:
  - drivers/base/bus.c:bind_store
```
```
In drivers/base/dd.c (ffffffff81b392c5)
Location: drivers/base/base.h:164
Inline: True
Inline callers:
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach_driver
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
In drivers/base/bus.c (ffffffff81b8e31d)
Location: drivers/base/base.h:164
Inline: True
Inline callers:
  - drivers/base/bus.c:bind_store
```
```
In drivers/base/dd.c (ffffffff81b90d85)
Location: drivers/base/base.h:164
Inline: True
Inline callers:
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach_driver
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
In drivers/base/bus.c (ffff8000108e8ab0)
Location: drivers/base/base.h:126
Inline: True
Inline callers:
  - drivers/base/bus.c:bind_store
```
```
In drivers/base/dd.c (ffff8000108eb238)
Location: drivers/base/base.h:126
Inline: True
Inline callers:
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach_driver
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
In drivers/base/bus.c (c09d6e04)
Location: drivers/base/base.h:126
Inline: True
Inline callers:
  - drivers/base/bus.c:bind_store
```
```
In drivers/base/dd.c (c09d9338)
Location: drivers/base/base.h:126
Inline: True
Inline callers:
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach_driver
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
In drivers/base/bus.c (c00000000097f370)
Location: drivers/base/base.h:126
Inline: True
Inline callers:
  - drivers/base/bus.c:bind_store
```
```
In drivers/base/dd.c (c0000000009827c8)
Location: drivers/base/base.h:126
Inline: True
Inline callers:
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach_driver
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
In drivers/base/bus.c (ffffffe00057ccf8)
Location: drivers/base/base.h:126
Inline: True
Inline callers:
  - drivers/base/bus.c:bind_store
```
```
In drivers/base/dd.c (ffffffe00057eed2)
Location: drivers/base/base.h:126
Inline: True
Inline callers:
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach_driver
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
In drivers/base/bus.c (ffffffff816c3599)
Location: drivers/base/base.h:126
Inline: True
Inline callers:
  - drivers/base/bus.c:bind_store
```
```
In drivers/base/dd.c (ffffffff816c5715)
Location: drivers/base/base.h:126
Inline: True
Inline callers:
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach_driver
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
In drivers/base/bus.c (ffffffff8169e849)
Location: drivers/base/base.h:126
Inline: True
Inline callers:
  - drivers/base/bus.c:bind_store
```
```
In drivers/base/dd.c (ffffffff816a0995)
Location: drivers/base/base.h:126
Inline: True
Inline callers:
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach_driver
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
In drivers/base/bus.c (ffffffff816f1a69)
Location: drivers/base/base.h:126
Inline: True
Inline callers:
  - drivers/base/bus.c:bind_store
```
```
In drivers/base/dd.c (ffffffff816f3be5)
Location: drivers/base/base.h:126
Inline: True
Inline callers:
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach_driver
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
In drivers/base/bus.c (ffffffff8170c2a9)
Location: drivers/base/base.h:126
Inline: True
Inline callers:
  - drivers/base/bus.c:bind_store
```
```
In drivers/base/dd.c (ffffffff8170e415)
Location: drivers/base/base.h:126
Inline: True
Inline callers:
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach_driver
```
</details>
</li>
</ul>

## Differences
