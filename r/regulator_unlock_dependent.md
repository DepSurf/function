# Function: <code>regulator_unlock_dependent</code>

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
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8162413f)
Location: drivers/regulator/core.c:331
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_get_voltage
  - drivers/regulator/core.c:regulator_set_suspend_voltage
  - drivers/regulator/core.c:regulator_set_voltage
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_disable
  - drivers/regulator/core.c:regulator_enable
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
In drivers/regulator/core.c (ffffffff81659caf)
Location: drivers/regulator/core.c:313
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_get_voltage
  - drivers/regulator/core.c:regulator_set_suspend_voltage
  - drivers/regulator/core.c:regulator_set_voltage
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_disable
  - drivers/regulator/core.c:regulator_enable
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
In drivers/regulator/core.c (ffffffff8167a3ff)
Location: drivers/regulator/core.c:313
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_get_voltage
  - drivers/regulator/core.c:regulator_set_suspend_voltage
  - drivers/regulator/core.c:regulator_set_voltage
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_disable
  - drivers/regulator/core.c:regulator_enable
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
In drivers/regulator/core.c (ffffffff8172e3e2)
Location: drivers/regulator/core.c:316
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_unregister
  - drivers/regulator/core.c:regulator_bulk_disable
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/regulator/core.c:regulator_bulk_enable_async
  - drivers/regulator/core.c:regulator_set_suspend_voltage
  - drivers/regulator/core.c:regulator_set_voltage
  - drivers/regulator/core.c:regulator_is_supported_voltage
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:drms_uA_update
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
In drivers/regulator/core.c (ffffffff8174afee)
Location: drivers/regulator/core.c:315
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_unregister
  - drivers/regulator/core.c:regulator_bulk_disable
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/regulator/core.c:regulator_bulk_enable_async
  - drivers/regulator/core.c:regulator_set_suspend_voltage
  - drivers/regulator/core.c:regulator_set_voltage
  - drivers/regulator/core.c:regulator_is_supported_voltage
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:drms_uA_update
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
In drivers/regulator/core.c (ffffffff8172e6c2)
Location: drivers/regulator/core.c:315
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_unregister
  - drivers/regulator/core.c:regulator_bulk_disable
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/regulator/core.c:regulator_bulk_enable_async
  - drivers/regulator/core.c:regulator_set_suspend_voltage
  - drivers/regulator/core.c:regulator_set_voltage
  - drivers/regulator/core.c:regulator_is_supported_voltage
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:drms_uA_update
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
In drivers/regulator/core.c (ffffffff817ae2a2)
Location: drivers/regulator/core.c:305
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_unregister
  - drivers/regulator/core.c:regulator_bulk_disable
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/regulator/core.c:regulator_bulk_enable_async
  - drivers/regulator/core.c:regulator_set_suspend_voltage
  - drivers/regulator/core.c:regulator_set_voltage
  - drivers/regulator/core.c:regulator_is_supported_voltage
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:drms_uA_update
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
In drivers/regulator/core.c (ffffffff818e9296)
Location: drivers/regulator/core.c:306
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_unregister
  - drivers/regulator/core.c:regulator_bulk_disable
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/regulator/core.c:regulator_bulk_enable_async
  - drivers/regulator/core.c:regulator_set_suspend_voltage
  - drivers/regulator/core.c:regulator_set_voltage
  - drivers/regulator/core.c:regulator_is_supported_voltage
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/regulator/core.c:drms_uA_update
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
In drivers/regulator/core.c (ffffffff81a3f5d6)
Location: drivers/regulator/core.c:306
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_unregister
  - drivers/regulator/core.c:regulator_bulk_disable
  - drivers/regulator/core.c:regulator_bulk_disable
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/regulator/core.c:regulator_bulk_enable_async
  - drivers/regulator/core.c:regulator_set_suspend_voltage
  - drivers/regulator/core.c:regulator_set_voltage
  - drivers/regulator/core.c:regulator_is_supported_voltage
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:set_machine_constraints
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
In drivers/regulator/core.c (ffffffff81a891a6)
Location: drivers/regulator/core.c:371
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_unregister
  - drivers/regulator/core.c:regulator_bulk_disable
  - drivers/regulator/core.c:regulator_bulk_disable
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/regulator/core.c:regulator_bulk_enable_async
  - drivers/regulator/core.c:regulator_set_suspend_voltage
  - drivers/regulator/core.c:regulator_set_voltage
  - drivers/regulator/core.c:regulator_is_supported_voltage
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:set_machine_constraints
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
In drivers/regulator/core.c (ffffffff81adb886)
Location: drivers/regulator/core.c:373
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_unregister
  - drivers/regulator/core.c:regulator_bulk_disable
  - drivers/regulator/core.c:regulator_bulk_disable
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/regulator/core.c:regulator_bulk_enable_async
  - drivers/regulator/core.c:regulator_set_suspend_voltage
  - drivers/regulator/core.c:regulator_set_voltage
  - drivers/regulator/core.c:regulator_is_supported_voltage
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:set_machine_constraints
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
In drivers/regulator/core.c (ffff800010842724)
Location: drivers/regulator/core.c:313
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_get_voltage
  - drivers/regulator/core.c:regulator_set_suspend_voltage
  - drivers/regulator/core.c:regulator_set_voltage
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_disable
  - drivers/regulator/core.c:regulator_enable
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
In drivers/regulator/core.c (c094d2a8)
Location: drivers/regulator/core.c:313
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_get_voltage
  - drivers/regulator/core.c:regulator_set_suspend_voltage
  - drivers/regulator/core.c:regulator_set_voltage
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_disable
  - drivers/regulator/core.c:regulator_enable
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
In drivers/regulator/core.c (c0000000008de72c)
Location: drivers/regulator/core.c:313
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_get_voltage
  - drivers/regulator/core.c:regulator_set_voltage
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_disable
  - drivers/regulator/core.c:regulator_enable
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
In drivers/regulator/core.c (ffffffe000524a02)
Location: drivers/regulator/core.c:313
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_get_voltage
  - drivers/regulator/core.c:regulator_set_voltage
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_disable
  - drivers/regulator/core.c:regulator_enable
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
In drivers/regulator/core.c (ffffffff8163feff)
Location: drivers/regulator/core.c:313
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_get_voltage
  - drivers/regulator/core.c:regulator_set_suspend_voltage
  - drivers/regulator/core.c:regulator_set_voltage
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_disable
  - drivers/regulator/core.c:regulator_enable
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
In drivers/regulator/core.c (ffffffff816202df)
Location: drivers/regulator/core.c:313
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_get_voltage
  - drivers/regulator/core.c:regulator_set_suspend_voltage
  - drivers/regulator/core.c:regulator_set_voltage
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_disable
  - drivers/regulator/core.c:regulator_enable
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
In drivers/regulator/core.c (ffffffff8166e23f)
Location: drivers/regulator/core.c:313
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_get_voltage
  - drivers/regulator/core.c:regulator_set_suspend_voltage
  - drivers/regulator/core.c:regulator_set_voltage
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_disable
  - drivers/regulator/core.c:regulator_enable
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
In drivers/regulator/core.c (ffffffff8168889f)
Location: drivers/regulator/core.c:313
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_get_voltage
  - drivers/regulator/core.c:regulator_set_suspend_voltage
  - drivers/regulator/core.c:regulator_set_voltage
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_disable
  - drivers/regulator/core.c:regulator_enable
```
</details>
</li>
</ul>

## Differences
