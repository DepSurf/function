# Function: <code>rockchip_pmu_set_idle_request</code>

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
int rockchip_pmu_set_idle_request(struct rockchip_pm_domain *pd, bool idle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/soc/rockchip/pm_domains.c (ffff80001081e788)
Location: drivers/soc/rockchip/pm_domains.c:152
Inline: False
Direct callers:
  - drivers/soc/rockchip/pm_domains.c:rockchip_pd_power
  - drivers/soc/rockchip/pm_domains.c:rockchip_pd_power
```
**Symbols:**

```
ffff80001081e788-ffff80001081e96c: rockchip_pmu_set_idle_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int rockchip_pmu_set_idle_request(struct rockchip_pm_domain *pd, bool idle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/soc/rockchip/pm_domains.c (c0938dd4)
Location: drivers/soc/rockchip/pm_domains.c:152
Inline: False
Direct callers:
  - drivers/soc/rockchip/pm_domains.c:rockchip_pd_power
  - drivers/soc/rockchip/pm_domains.c:rockchip_pd_power
```
**Symbols:**

```
c0938dd4-c0938f9c: rockchip_pmu_set_idle_request (STB_LOCAL)
```
</details>
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
<b>Arch</b>
<ul>
</ul>
