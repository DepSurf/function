# Function: <code>of_reset_control_get_exclusive</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffff817be050)
Location: include/linux/reset.h:228
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:mdiobus_register_device
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
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
In drivers/net/phy/mdio_bus.c (ffff8000109d6fcc)
Location: include/linux/reset.h:228
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:mdiobus_register_device
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
In arch/arm/mach-meson/platsmp.c (c03302b8)
Location: include/linux/reset.h:228
Inline: True
Inline callers:
  - arch/arm/mach-meson/platsmp.c:meson_smp_get_core_reset
```
```
In arch/arm/mach-rockchip/platsmp.c (c0349368)
Location: include/linux/reset.h:228
Inline: True
Inline callers:
  - arch/arm/mach-rockchip/platsmp.c:pmu_set_power_domain
```
```
In drivers/net/phy/mdio_bus.c (c0abe78c)
Location: include/linux/reset.h:228
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:mdiobus_register_device
```
```
In drivers/clocksource/dw_apb_timer_of.c (c15aac18)
Location: include/linux/reset.h:228
Inline: True
Inline callers:
  - drivers/clocksource/dw_apb_timer_of.c:timer_get_base_and_rate
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
In drivers/net/phy/mdio_bus.c (c000000000a987c8)
Location: include/linux/reset.h:228
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:mdiobus_register_device
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
In drivers/net/phy/mdio_bus.c (ffffffe000622e54)
Location: include/linux/reset.h:228
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:mdiobus_register_device
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
In drivers/net/phy/mdio_bus.c (ffffffff81782b20)
Location: include/linux/reset.h:228
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:mdiobus_register_device
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
In drivers/net/phy/mdio_bus.c (ffffffff817628b0)
Location: include/linux/reset.h:228
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:mdiobus_register_device
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
In drivers/net/phy/mdio_bus.c (ffffffff817b2ed0)
Location: include/linux/reset.h:228
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:mdiobus_register_device
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
In drivers/net/phy/mdio_bus.c (ffffffff817cce80)
Location: include/linux/reset.h:228
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:mdiobus_register_device
```
</details>
</li>
</ul>

## Differences
