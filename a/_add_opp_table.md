# Function: <code>_add_opp_table</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct opp_table *_add_opp_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81994a9a)
Location: drivers/opp/core.c:1196
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_add
  - drivers/opp/core.c:dev_pm_opp_attach_genpd
  - drivers/opp/core.c:dev_pm_opp_set_clkname
  - drivers/opp/core.c:dev_pm_opp_set_regulators
  - drivers/opp/core.c:dev_pm_opp_set_prop_name
  - drivers/opp/core.c:dev_pm_opp_set_supported_hw
```
**Symbols:**

```
ffffffff819946a0-ffffffff819946b2: _add_opp_table (STB_GLOBAL)
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
In drivers/opp/core.c (ffffffff819799cf)
Location: drivers/opp/core.c:1350
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_add
  - drivers/opp/core.c:dev_pm_opp_attach_genpd
  - drivers/opp/core.c:dev_pm_opp_set_clkname
  - drivers/opp/core.c:dev_pm_opp_set_regulators
  - drivers/opp/core.c:dev_pm_opp_set_prop_name
  - drivers/opp/core.c:dev_pm_opp_set_supported_hw
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
In drivers/opp/core.c (ffffffff81a229df)
Location: drivers/opp/core.c:1360
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_add
  - drivers/opp/core.c:dev_pm_opp_attach_genpd
  - drivers/opp/core.c:dev_pm_opp_set_clkname
  - drivers/opp/core.c:dev_pm_opp_set_regulators
  - drivers/opp/core.c:dev_pm_opp_set_prop_name
  - drivers/opp/core.c:dev_pm_opp_set_supported_hw
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
In drivers/opp/core.c (ffffffff81b8baaf)
Location: drivers/opp/core.c:1505
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_add
  - drivers/opp/core.c:dev_pm_opp_attach_genpd
  - drivers/opp/core.c:dev_pm_opp_set_clkname
  - drivers/opp/core.c:dev_pm_opp_set_regulators
  - drivers/opp/core.c:dev_pm_opp_set_prop_name
  - drivers/opp/core.c:dev_pm_opp_set_supported_hw
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
In drivers/opp/core.c (ffffffff81d2b23f)
Location: drivers/opp/core.c:1477
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_add
  - drivers/opp/core.c:dev_pm_opp_set_config
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
In drivers/opp/core.c (ffffffff81d944bf)
Location: drivers/opp/core.c:1493
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_add
  - drivers/opp/core.c:dev_pm_opp_set_config
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
In drivers/opp/core.c (ffffffff81e4bfda)
Location: drivers/opp/core.c:1604
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_add_dynamic
  - drivers/opp/core.c:dev_pm_opp_set_config
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
