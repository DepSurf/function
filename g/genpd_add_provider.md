# Function: <code>genpd_add_provider</code>

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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int genpd_add_provider(struct device_node *np, genpd_xlate_t xlate, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffff800010907758)
Location: drivers/base/power/domain.c:2002
Inline: True
Direct callers:
  - drivers/base/power/domain.c:of_genpd_add_provider_onecell
  - drivers/base/power/domain.c:of_genpd_add_provider_onecell
  - drivers/base/power/domain.c:of_genpd_add_provider_simple
```
**Symbols:**

```
ffff800010907758-ffff800010907834: genpd_add_provider (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int genpd_add_provider(struct device_node *np, genpd_xlate_t xlate, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (c09f1b44)
Location: drivers/base/power/domain.c:2002
Inline: True
Direct callers:
  - drivers/base/power/domain.c:of_genpd_add_provider_onecell
  - drivers/base/power/domain.c:of_genpd_add_provider_onecell
  - drivers/base/power/domain.c:of_genpd_add_provider_simple
```
**Symbols:**

```
c09f1b44-c09f1c00: genpd_add_provider (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int genpd_add_provider(struct device_node *np, genpd_xlate_t xlate, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (c0000000009a9780)
Location: drivers/base/power/domain.c:2002
Inline: True
Direct callers:
  - drivers/base/power/domain.c:of_genpd_add_provider_onecell
  - drivers/base/power/domain.c:of_genpd_add_provider_onecell
  - drivers/base/power/domain.c:of_genpd_add_provider_simple
```
**Symbols:**

```
c0000000009a9780-c0000000009a98d0: genpd_add_provider (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int genpd_add_provider(struct device_node *np, genpd_xlate_t xlate, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffe00058ecf2)
Location: drivers/base/power/domain.c:2002
Inline: True
Direct callers:
  - drivers/base/power/domain.c:of_genpd_add_provider_onecell
  - drivers/base/power/domain.c:of_genpd_add_provider_onecell
  - drivers/base/power/domain.c:of_genpd_add_provider_simple
```
**Symbols:**

```
ffffffe00058ecf2-ffffffe00058edcc: genpd_add_provider (STB_LOCAL)
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
<b>Arch</b>
<ul>
</ul>
