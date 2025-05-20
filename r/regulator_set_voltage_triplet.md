# Function: <code>regulator_set_voltage_triplet</code>

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
In drivers/mmc/core/core.c (ffffffff816be13e)
Location: include/linux/regulator/consumer.h:561
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_regulator_set_voltage_if_supported
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
In drivers/mmc/core/core.c (ffffffff8171fd4e)
Location: include/linux/regulator/consumer.h:558
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_regulator_set_voltage_if_supported
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
In drivers/mmc/core/core.c (ffffffff817525ce)
Location: include/linux/regulator/consumer.h:582
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_regulator_set_voltage_if_supported
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
In drivers/mmc/core/core.c (ffffffff81770dd7)
Location: include/linux/regulator/consumer.h:583
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_regulator_set_voltage_if_supported
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
In drivers/opp/core.c (ffffffff817d3b55)
Location: include/linux/regulator/consumer.h:583
Inline: True
Inline callers:
  - drivers/opp/core.c:_set_opp_voltage
```
```
In drivers/mmc/core/core.c (ffffffff817e6b37)
Location: include/linux/regulator/consumer.h:583
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_regulator_set_voltage_if_supported
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
In drivers/opp/core.c (ffffffff8181cd5e)
Location: include/linux/regulator/consumer.h:584
Inline: True
```
```
In drivers/mmc/core/core.c (ffffffff8182fe87)
Location: include/linux/regulator/consumer.h:584
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_regulator_set_voltage_if_supported
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
In drivers/opp/core.c (ffffffff8184891e)
Location: include/linux/regulator/consumer.h:584
Inline: True
```
```
In drivers/mmc/core/core.c (ffffffff8185c107)
Location: include/linux/regulator/consumer.h:584
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_regulator_set_voltage_if_supported
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
In drivers/opp/core.c (ffffffff8188b2fa)
Location: include/linux/regulator/consumer.h:585
Inline: True
Inline callers:
  - drivers/opp/core.c:_set_opp_voltage
```
```
In drivers/mmc/core/regulator.c (ffffffff818b10b8)
Location: include/linux/regulator/consumer.h:585
Inline: True
Inline callers:
  - drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported
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
In drivers/opp/core.c (ffffffff818bd3da)
Location: include/linux/regulator/consumer.h:605
Inline: True
Inline callers:
  - drivers/opp/core.c:_set_opp_voltage
```
```
In drivers/mmc/core/regulator.c (ffffffff818e3558)
Location: include/linux/regulator/consumer.h:605
Inline: True
Inline callers:
  - drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported
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
In drivers/opp/core.c (ffffffff8198da7a)
Location: include/linux/regulator/consumer.h:605
Inline: True
Inline callers:
  - drivers/opp/core.c:_set_opp_voltage
```
```
In drivers/mmc/core/regulator.c (ffffffff819b664d)
Location: include/linux/regulator/consumer.h:605
Inline: True
Inline callers:
  - drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported
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
In drivers/opp/core.c (ffffffff819915da)
Location: include/linux/regulator/consumer.h:645
Inline: True
Inline callers:
  - drivers/opp/core.c:_set_opp_voltage
```
```
In drivers/mmc/core/regulator.c (ffffffff819b8b8d)
Location: include/linux/regulator/consumer.h:645
Inline: True
Inline callers:
  - drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported
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
In drivers/opp/core.c (ffffffff81975baa)
Location: include/linux/regulator/consumer.h:645
Inline: True
Inline callers:
  - drivers/opp/core.c:_set_opp_voltage
```
```
In drivers/mmc/core/regulator.c (ffffffff8199d2bd)
Location: include/linux/regulator/consumer.h:645
Inline: True
Inline callers:
  - drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported
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
In drivers/opp/core.c (ffffffff81a1e867)
Location: include/linux/regulator/consumer.h:644
Inline: True
Inline callers:
  - drivers/opp/core.c:_set_opp_voltage
```
```
In drivers/mmc/core/regulator.c (ffffffff81a49c3d)
Location: include/linux/regulator/consumer.h:644
Inline: True
Inline callers:
  - drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported
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
In drivers/opp/core.c (ffffffff81b8712b)
Location: include/linux/regulator/consumer.h:644
Inline: True
Inline callers:
  - drivers/opp/core.c:_set_opp_voltage
```
```
In drivers/mmc/core/regulator.c (ffffffff81bb802b)
Location: include/linux/regulator/consumer.h:644
Inline: True
Inline callers:
  - drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported
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
In drivers/opp/core.c (ffffffff81d26dec)
Location: include/linux/regulator/consumer.h:689
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_config_regulator_single
```
```
In drivers/mmc/core/regulator.c (ffffffff81d5cd0b)
Location: include/linux/regulator/consumer.h:689
Inline: True
Inline callers:
  - drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported
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
In drivers/opp/core.c (ffffffff81d8ffec)
Location: include/linux/regulator/consumer.h:689
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_config_regulator_single
```
```
In drivers/mmc/core/regulator.c (ffffffff81dc78cb)
Location: include/linux/regulator/consumer.h:689
Inline: True
Inline callers:
  - drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported
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
In drivers/opp/core.c (ffffffff81e4767c)
Location: include/linux/regulator/consumer.h:644
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_config_regulator_single
```
```
In drivers/mmc/core/regulator.c (ffffffff81e8022b)
Location: include/linux/regulator/consumer.h:644
Inline: True
Inline callers:
  - drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported
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
In drivers/opp/core.c (ffff800010b17e30)
Location: include/linux/regulator/consumer.h:605
Inline: True
Inline callers:
  - drivers/opp/core.c:_set_opp_voltage
```
```
In drivers/mmc/core/regulator.c (ffff800010b3df0c)
Location: include/linux/regulator/consumer.h:605
Inline: True
Inline callers:
  - drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported
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
In drivers/opp/core.c (c0bf2ea4)
Location: include/linux/regulator/consumer.h:605
Inline: True
Inline callers:
  - drivers/opp/core.c:_set_opp_voltage
```
```
In drivers/opp/ti-opp-supply.c (c0bf7588)
Location: include/linux/regulator/consumer.h:605
Inline: True
Inline callers:
  - drivers/opp/ti-opp-supply.c:_opp_set_voltage
```
```
In drivers/mmc/core/regulator.c (c0c18484)
Location: include/linux/regulator/consumer.h:605
Inline: True
Inline callers:
  - drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported
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
In drivers/opp/core.c (c000000000c094e0)
Location: include/linux/regulator/consumer.h:605
Inline: True
Inline callers:
  - drivers/opp/core.c:_set_opp_voltage
```
```
In drivers/mmc/core/regulator.c (c000000000c3b790)
Location: include/linux/regulator/consumer.h:605
Inline: True
Inline callers:
  - drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported
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
In drivers/opp/core.c (ffffffe000700c9e)
Location: include/linux/regulator/consumer.h:605
Inline: True
Inline callers:
  - drivers/opp/core.c:_set_opp_voltage
```
```
In drivers/mmc/core/regulator.c (ffffffe000714ecc)
Location: include/linux/regulator/consumer.h:605
Inline: True
Inline callers:
  - drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported
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
In drivers/opp/core.c (ffffffff81861afa)
Location: include/linux/regulator/consumer.h:605
Inline: True
Inline callers:
  - drivers/opp/core.c:_set_opp_voltage
```
```
In drivers/mmc/core/regulator.c (ffffffff81886f18)
Location: include/linux/regulator/consumer.h:605
Inline: True
Inline callers:
  - drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported
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
In drivers/opp/core.c (ffffffff8182a7aa)
Location: include/linux/regulator/consumer.h:605
Inline: True
Inline callers:
  - drivers/opp/core.c:_set_opp_voltage
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
In drivers/opp/core.c (ffffffff818b288a)
Location: include/linux/regulator/consumer.h:605
Inline: True
Inline callers:
  - drivers/opp/core.c:_set_opp_voltage
```
```
In drivers/mmc/core/regulator.c (ffffffff818d83b8)
Location: include/linux/regulator/consumer.h:605
Inline: True
Inline callers:
  - drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported
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
In drivers/opp/core.c (ffffffff818ceb3a)
Location: include/linux/regulator/consumer.h:605
Inline: True
Inline callers:
  - drivers/opp/core.c:_set_opp_voltage
```
```
In drivers/mmc/core/regulator.c (ffffffff818f4ed8)
Location: include/linux/regulator/consumer.h:605
Inline: True
Inline callers:
  - drivers/mmc/core/regulator.c:mmc_regulator_set_voltage_if_supported
```
</details>
</li>
</ul>

## Differences
