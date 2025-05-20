# Function: <code>devlink_port_type_warn_schedule</code>

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
In net/core/devlink.c (ffffffff8194d476)
Location: net/core/devlink.c:5603
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_port_type_clear
  - net/core/devlink.c:devlink_port_type_clear
  - net/core/devlink.c:devlink_port_register
  - net/core/devlink.c:devlink_port_register
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
In net/core/devlink.c (ffffffff81982dc6)
Location: net/core/devlink.c:6300
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_port_type_clear
  - net/core/devlink.c:devlink_port_type_clear
  - net/core/devlink.c:devlink_port_register
  - net/core/devlink.c:devlink_port_register
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
In net/core/devlink.c (ffffffff81a5ae66)
Location: net/core/devlink.c:7236
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_port_type_clear
  - net/core/devlink.c:devlink_port_register
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
In net/core/devlink.c (ffffffff81a66706)
Location: net/core/devlink.c:8110
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_port_type_clear
  - net/core/devlink.c:devlink_port_register
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
In net/core/devlink.c (ffffffff81a46c56)
Location: net/core/devlink.c:8329
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_port_type_clear
  - net/core/devlink.c:devlink_port_register
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
In net/core/devlink.c (ffffffff81b01a56)
Location: net/core/devlink.c:9071
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_port_type_clear
  - net/core/devlink.c:devlink_port_register
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
In net/core/devlink.c (ffffffff81c81096)
Location: net/core/devlink.c:9658
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_port_type_clear
  - net/core/devlink.c:devlink_port_type_clear
  - net/core/devlink.c:devl_port_register
  - net/core/devlink.c:devl_port_register
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
In net/core/devlink.c (ffffffff81e3e0b6)
Location: net/core/devlink.c:10194
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_port_type_set
  - net/core/devlink.c:__devlink_port_type_set
  - net/core/devlink.c:devl_port_register
  - net/core/devlink.c:devl_port_register
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
In net/devlink/leftover.c (ffffffff8203dc92)
Location: net/devlink/leftover.c:6759
Inline: True
Inline callers:
  - net/devlink/leftover.c:__devlink_port_type_set
  - net/devlink/leftover.c:__devlink_port_type_set
  - net/devlink/leftover.c:devl_port_register_with_ops
  - net/devlink/leftover.c:devl_port_register_with_ops
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
In net/devlink/port.c (ffffffff82107514)
Location: net/devlink/port.c:938
Inline: True
Inline callers:
  - net/devlink/port.c:__devlink_port_type_set
  - net/devlink/port.c:__devlink_port_type_set
  - net/devlink/port.c:devl_port_register_with_ops
  - net/devlink/port.c:devl_port_register_with_ops
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
In net/core/devlink.c (ffff800010c2afa0)
Location: net/core/devlink.c:6300
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_port_type_clear
  - net/core/devlink.c:devlink_port_type_clear
  - net/core/devlink.c:devlink_port_register
  - net/core/devlink.c:devlink_port_register
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
In net/core/devlink.c (c0d4238c)
Location: net/core/devlink.c:6300
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_port_type_clear
  - net/core/devlink.c:devlink_port_type_clear
  - net/core/devlink.c:devlink_port_register
  - net/core/devlink.c:devlink_port_register
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
In net/core/devlink.c (c000000000d20530)
Location: net/core/devlink.c:6300
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_port_type_clear
  - net/core/devlink.c:devlink_port_type_clear
  - net/core/devlink.c:devlink_port_register
  - net/core/devlink.c:devlink_port_register
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
In net/core/devlink.c (ffffffe0007a2500)
Location: net/core/devlink.c:6300
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_port_type_clear
  - net/core/devlink.c:devlink_port_type_clear
  - net/core/devlink.c:devlink_port_register
  - net/core/devlink.c:devlink_port_register
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
In net/core/devlink.c (ffffffff81922c36)
Location: net/core/devlink.c:6300
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_port_type_clear
  - net/core/devlink.c:devlink_port_type_clear
  - net/core/devlink.c:devlink_port_register
  - net/core/devlink.c:devlink_port_register
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
In net/core/devlink.c (ffffffff818dc9e6)
Location: net/core/devlink.c:6300
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_port_type_clear
  - net/core/devlink.c:devlink_port_type_clear
  - net/core/devlink.c:devlink_port_register
  - net/core/devlink.c:devlink_port_register
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
In net/core/devlink.c (ffffffff81973dc6)
Location: net/core/devlink.c:6300
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_port_type_clear
  - net/core/devlink.c:devlink_port_type_clear
  - net/core/devlink.c:devlink_port_register
  - net/core/devlink.c:devlink_port_register
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
In net/core/devlink.c (ffffffff819962b6)
Location: net/core/devlink.c:6300
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_port_type_clear
  - net/core/devlink.c:devlink_port_type_clear
  - net/core/devlink.c:devlink_port_register
  - net/core/devlink.c:devlink_port_register
```
</details>
</li>
</ul>

## Differences
