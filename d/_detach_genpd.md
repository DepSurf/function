# Function: <code>_detach_genpd</code>

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
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (ffffffff81d2a03b)
Location: drivers/opp/core.c:2296
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_set_config
  - drivers/opp/core.c:_opp_clear_config
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_set_config
  - drivers/opp/core.c:dev_pm_opp_set_config
  - drivers/opp/core.c:dev_pm_opp_set_config
  - drivers/opp/core.c:_opp_clear_config
```
**Symbols:**

```
ffffffff81d27070-ffffffff81d270f3: _detach_genpd.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (ffffffff81d93212)
Location: drivers/opp/core.c:2304
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_set_config
  - drivers/opp/core.c:_opp_clear_config
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_set_config
  - drivers/opp/core.c:dev_pm_opp_set_config
  - drivers/opp/core.c:dev_pm_opp_set_config
  - drivers/opp/core.c:_opp_clear_config
```
**Symbols:**

```
ffffffff81d90270-ffffffff81d902f3: _detach_genpd.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
