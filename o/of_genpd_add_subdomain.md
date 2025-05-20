# Function: <code>of_genpd_add_subdomain</code>

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
<summary>In <code>arm64</code>: ✅</summary>

```c
int of_genpd_add_subdomain(struct of_phandle_args *parent_spec, struct of_phandle_args *subdomain_spec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffff8000109087a0)
Location: drivers/base/power/domain.c:2276
Inline: False
```
**Symbols:**

```
ffff8000109087a0-ffff800010908854: of_genpd_add_subdomain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int of_genpd_add_subdomain(struct of_phandle_args *parent_spec, struct of_phandle_args *subdomain_spec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (c09f1320)
Location: drivers/base/power/domain.c:2276
Inline: False
Direct callers:
  - drivers/soc/samsung/pm_domains.c:exynos4_pm_init_power_domain
```
**Symbols:**

```
c09f1320-c09f13ac: of_genpd_add_subdomain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int of_genpd_add_subdomain(struct of_phandle_args *parent_spec, struct of_phandle_args *subdomain_spec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (c0000000009aa050)
Location: drivers/base/power/domain.c:2276
Inline: False
```
**Symbols:**

```
c0000000009aa050-c0000000009aa1a4: of_genpd_add_subdomain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int of_genpd_add_subdomain(struct of_phandle_args *parent_spec, struct of_phandle_args *subdomain_spec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffe00058eb50)
Location: drivers/base/power/domain.c:2276
Inline: False
```
**Symbols:**

```
ffffffe00058eb50-ffffffe00058ebe2: of_genpd_add_subdomain (STB_GLOBAL)
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
