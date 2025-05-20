# Function: <code>genpd_present</code>

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
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff8165b96f)
Location: drivers/base/power/domain.c:849
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_syscore_switch
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
In drivers/base/power/domain.c (ffffffff8169763f)
Location: drivers/base/power/domain.c:850
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_syscore_switch
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
In drivers/base/power/domain.c (ffffffff816b831f)
Location: drivers/base/power/domain.c:929
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_syscore_switch
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
In drivers/base/power/domain.c (ffffffff816f206f)
Location: drivers/base/power/domain.c:932
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_syscore_switch
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
In drivers/base/power/domain.c (ffffffff817167ef)
Location: drivers/base/power/domain.c:927
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_syscore_switch
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
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/domain.c (ffff800010907998)
Location: drivers/base/power/domain.c:927
Inline: True
Inline callers:
  - drivers/base/power/domain.c:of_genpd_add_provider_onecell
  - drivers/base/power/domain.c:of_genpd_add_provider_simple
  - drivers/base/power/domain.c:genpd_syscore_switch
Direct callers:
  - drivers/base/power/domain.c:of_genpd_add_provider_onecell
  - drivers/base/power/domain.c:of_genpd_add_provider_simple
  - drivers/base/power/domain.c:genpd_syscore_switch
```
**Symbols:**

```
ffff800010907548-ffff8000109075bc: genpd_present.part.0 (STB_LOCAL)
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
In drivers/base/power/domain.c (c09f1d90)
Location: drivers/base/power/domain.c:927
Inline: True
Inline callers:
  - drivers/base/power/domain.c:of_genpd_add_provider_onecell
  - drivers/base/power/domain.c:of_genpd_add_provider_simple
  - drivers/base/power/domain.c:genpd_syscore_switch
Direct callers:
  - drivers/base/power/domain.c:of_genpd_add_provider_onecell
  - drivers/base/power/domain.c:of_genpd_add_provider_simple
  - drivers/base/power/domain.c:genpd_syscore_switch
```
**Symbols:**

```
c09f122c-c09f128c: genpd_present.part.0 (STB_LOCAL)
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
In drivers/base/power/domain.c (c0000000009a9ae8)
Location: drivers/base/power/domain.c:927
Inline: True
Inline callers:
  - drivers/base/power/domain.c:of_genpd_add_provider_onecell
  - drivers/base/power/domain.c:of_genpd_add_provider_simple
  - drivers/base/power/domain.c:genpd_syscore_switch
Direct callers:
  - drivers/base/power/domain.c:of_genpd_add_provider_onecell
  - drivers/base/power/domain.c:of_genpd_add_provider_simple
  - drivers/base/power/domain.c:genpd_syscore_switch
```
**Symbols:**

```
c0000000009a6e80-c0000000009a6ee8: genpd_present.part.0 (STB_LOCAL)
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
In drivers/base/power/domain.c (ffffffe00058f1c0)
Location: drivers/base/power/domain.c:927
Inline: True
Inline callers:
  - drivers/base/power/domain.c:of_genpd_add_provider_onecell
  - drivers/base/power/domain.c:of_genpd_add_provider_onecell
  - drivers/base/power/domain.c:of_genpd_add_provider_simple
  - drivers/base/power/domain.c:of_genpd_add_provider_simple
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
In drivers/base/power/domain.c (ffffffff816dcb1f)
Location: drivers/base/power/domain.c:927
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_syscore_switch
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
In drivers/base/power/domain.c (ffffffff816b719f)
Location: drivers/base/power/domain.c:927
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_syscore_switch
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
In drivers/base/power/domain.c (ffffffff8170a4af)
Location: drivers/base/power/domain.c:927
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_syscore_switch
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
In drivers/base/power/domain.c (ffffffff817251af)
Location: drivers/base/power/domain.c:927
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_syscore_switch
```
</details>
</li>
</ul>

## Differences
