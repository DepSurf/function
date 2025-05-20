# Function: <code>genpd_get_from_provider</code>

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
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/domain.c (ffff80001090a3e8)
Location: drivers/base/power/domain.c:2213
Inline: True
Inline callers:
  - drivers/base/power/domain.c:__genpd_dev_pm_attach
  - drivers/base/power/domain.c:of_genpd_add_subdomain
  - drivers/base/power/domain.c:of_genpd_add_subdomain
  - drivers/base/power/domain.c:of_genpd_add_device
Direct callers:
  - drivers/base/power/domain.c:__genpd_dev_pm_attach
  - drivers/base/power/domain.c:of_genpd_add_subdomain
  - drivers/base/power/domain.c:of_genpd_add_subdomain
  - drivers/base/power/domain.c:of_genpd_add_device
```
**Symbols:**

```
ffff8000109075c0-ffff800010907670: genpd_get_from_provider.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/domain.c (c09f35a0)
Location: drivers/base/power/domain.c:2213
Inline: True
Inline callers:
  - drivers/base/power/domain.c:__genpd_dev_pm_attach
  - drivers/base/power/domain.c:of_genpd_add_subdomain
  - drivers/base/power/domain.c:of_genpd_add_subdomain
  - drivers/base/power/domain.c:of_genpd_add_device
Direct callers:
  - drivers/base/power/domain.c:__genpd_dev_pm_attach
  - drivers/base/power/domain.c:of_genpd_add_subdomain
  - drivers/base/power/domain.c:of_genpd_add_subdomain
  - drivers/base/power/domain.c:of_genpd_add_device
```
**Symbols:**

```
c09f128c-c09f1320: genpd_get_from_provider.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/domain.c (c0000000009aa7b8)
Location: drivers/base/power/domain.c:2213
Inline: True
Inline callers:
  - drivers/base/power/domain.c:__genpd_dev_pm_attach
  - drivers/base/power/domain.c:of_genpd_add_subdomain
  - drivers/base/power/domain.c:of_genpd_add_subdomain
  - drivers/base/power/domain.c:of_genpd_add_device
Direct callers:
  - drivers/base/power/domain.c:__genpd_dev_pm_attach
  - drivers/base/power/domain.c:of_genpd_add_subdomain
  - drivers/base/power/domain.c:of_genpd_add_subdomain
  - drivers/base/power/domain.c:of_genpd_add_device
```
**Symbols:**

```
c0000000009a6ef0-c0000000009a7008: genpd_get_from_provider.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/domain.c (ffffffe0005902bc)
Location: drivers/base/power/domain.c:2213
Inline: True
Inline callers:
  - drivers/base/power/domain.c:__genpd_dev_pm_attach
  - drivers/base/power/domain.c:of_genpd_add_subdomain
  - drivers/base/power/domain.c:of_genpd_add_subdomain
  - drivers/base/power/domain.c:of_genpd_add_device
Direct callers:
  - drivers/base/power/domain.c:__genpd_dev_pm_attach
  - drivers/base/power/domain.c:of_genpd_add_subdomain
  - drivers/base/power/domain.c:of_genpd_add_subdomain
  - drivers/base/power/domain.c:of_genpd_add_device
```
**Symbols:**

```
ffffffe00058eabc-ffffffe00058eb50: genpd_get_from_provider.part.0 (STB_LOCAL)
```
</details>
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
