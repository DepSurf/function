# Function: <code>thermal_genl_cpu_capability_event</code>

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
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int thermal_genl_cpu_capability_event(int count, struct thermal_genl_cpu_caps *caps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_netlink.c (ffffffff81b4cef0)
Location: drivers/thermal/thermal_netlink.c:403
Inline: False
Direct callers:
  - drivers/thermal/intel/intel_hfi.c:hfi_update_work_fn
  - drivers/thermal/intel/intel_hfi.c:hfi_update_work_fn
```
**Symbols:**

```
ffffffff81b4cef0-ffffffff81b4cf51: thermal_genl_cpu_capability_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int thermal_genl_cpu_capability_event(int count, struct thermal_genl_cpu_caps *caps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_netlink.c (ffffffff81ce4be0)
Location: drivers/thermal/thermal_netlink.c:403
Inline: False
Direct callers:
  - drivers/thermal/intel/intel_hfi.c:hfi_update_work_fn
  - drivers/thermal/intel/intel_hfi.c:hfi_update_work_fn
```
**Symbols:**

```
ffffffff81ce4be0-ffffffff81ce4c41: thermal_genl_cpu_capability_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int thermal_genl_cpu_capability_event(int count, struct thermal_genl_cpu_caps *caps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_netlink.c (ffffffff81d4d1b0)
Location: drivers/thermal/thermal_netlink.c:403
Inline: False
Direct callers:
  - drivers/thermal/intel/intel_hfi.c:hfi_update_work_fn
  - drivers/thermal/intel/intel_hfi.c:hfi_update_work_fn
```
**Symbols:**

```
ffffffff81d4d1b0-ffffffff81d4d211: thermal_genl_cpu_capability_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int thermal_genl_cpu_capability_event(int count, struct thermal_genl_cpu_caps *caps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_netlink.c (ffffffff81e04060)
Location: drivers/thermal/thermal_netlink.c:398
Inline: False
Direct callers:
  - drivers/thermal/intel/intel_hfi.c:hfi_update_work_fn
  - drivers/thermal/intel/intel_hfi.c:hfi_update_work_fn
```
**Symbols:**

```
ffffffff81e04060-ffffffff81e040c1: thermal_genl_cpu_capability_event (STB_GLOBAL)
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
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
