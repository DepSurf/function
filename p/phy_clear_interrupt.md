# Function: <code>phy_clear_interrupt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff815e997a)
Location: drivers/net/phy/phy.c:113
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_enable_interrupts
  - drivers/net/phy/phy.c:phy_disable_interrupts
  - drivers/net/phy/phy.c:phy_stop
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
In drivers/net/phy/phy.c (ffffffff816488ee)
Location: drivers/net/phy/phy.c:113
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_stop
  - drivers/net/phy/phy.c:phy_disable_interrupts
  - drivers/net/phy/phy.c:phy_enable_interrupts
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
In drivers/net/phy/phy.c (ffffffff816799ce)
Location: drivers/net/phy/phy.c:114
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_stop
  - drivers/net/phy/phy.c:phy_disable_interrupts
  - drivers/net/phy/phy.c:phy_enable_interrupts
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
In drivers/net/phy/phy.c (ffffffff8168de39)
Location: drivers/net/phy/phy.c:130
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_stop
  - drivers/net/phy/phy.c:phy_disable_interrupts
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
In drivers/net/phy/phy.c (ffffffff816f796c)
Location: drivers/net/phy/phy.c:93
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_stop
  - drivers/net/phy/phy.c:phy_disable_interrupts
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
In drivers/net/phy/phy.c (ffffffff81734995)
Location: drivers/net/phy/phy.c:93
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_enable_interrupts
  - drivers/net/phy/phy.c:phy_change
  - drivers/net/phy/phy.c:phy_disable_interrupts
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff81757ac5)
Location: drivers/net/phy/phy.c:101
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_enable_interrupts
  - drivers/net/phy/phy.c:phy_interrupt
  - drivers/net/phy/phy.c:phy_disable_interrupts
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff81794467)
Location: drivers/net/phy/phy.c:117
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_interrupt
  - drivers/net/phy/phy.c:phy_disable_interrupts
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
In drivers/net/phy/phy.c (ffffffff817b800e)
Location: drivers/net/phy/phy.c:117
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_interrupt
  - drivers/net/phy/phy.c:phy_disable_interrupts
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
In drivers/net/phy/phy.c (ffffffff818806dd)
Location: drivers/net/phy/phy.c:125
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_request_interrupt
  - drivers/net/phy/phy.c:phy_interrupt
  - drivers/net/phy/phy.c:phy_disable_interrupts
```
</details>
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffff8000109d07b4)
Location: drivers/net/phy/phy.c:117
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_interrupt
  - drivers/net/phy/phy.c:phy_disable_interrupts
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
In drivers/net/phy/phy.c (c0ab89c8)
Location: drivers/net/phy/phy.c:117
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_interrupt
  - drivers/net/phy/phy.c:phy_disable_interrupts
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
In drivers/net/phy/phy.c (c000000000a8fbf0)
Location: drivers/net/phy/phy.c:117
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_interrupt
  - drivers/net/phy/phy.c:phy_disable_interrupts
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
In drivers/net/phy/phy.c (ffffffe00061d40e)
Location: drivers/net/phy/phy.c:117
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_interrupt
  - drivers/net/phy/phy.c:phy_disable_interrupts
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
In drivers/net/phy/phy.c (ffffffff8177cade)
Location: drivers/net/phy/phy.c:117
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_interrupt
  - drivers/net/phy/phy.c:phy_disable_interrupts
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
In drivers/net/phy/phy.c (ffffffff8175c88e)
Location: drivers/net/phy/phy.c:117
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_interrupt
  - drivers/net/phy/phy.c:phy_disable_interrupts
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
In drivers/net/phy/phy.c (ffffffff817ace8e)
Location: drivers/net/phy/phy.c:117
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_interrupt
  - drivers/net/phy/phy.c:phy_disable_interrupts
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
In drivers/net/phy/phy.c (ffffffff817c6e1e)
Location: drivers/net/phy/phy.c:117
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_interrupt
  - drivers/net/phy/phy.c:phy_disable_interrupts
```
</details>
</li>
</ul>

## Differences
