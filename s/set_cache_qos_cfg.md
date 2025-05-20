# Function: <code>set_cache_qos_cfg</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int set_cache_qos_cfg(int level, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81048000)
Location: arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:1014
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:cdp_disable_all
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:cdp_disable_all
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:cdp_enable
```
**Symbols:**

```
ffffffff81048000-ffffffff81048115: set_cache_qos_cfg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int set_cache_qos_cfg(int level, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff810564d0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1740
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cdp_disable_all
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cdp_disable_all
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cdp_enable
```
**Symbols:**

```
ffffffff810564d0-ffffffff810565e5: set_cache_qos_cfg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int set_cache_qos_cfg(int level, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff810595a0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1738
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cdp_disable_all
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cdp_disable_all
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cdp_enable
```
**Symbols:**

```
ffffffff810595a0-ffffffff810596b3: set_cache_qos_cfg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int set_cache_qos_cfg(int level, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81059e70)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1736
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cdp_disable_all
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cdp_disable_all
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cdp_enable
```
**Symbols:**

```
ffffffff81059e70-ffffffff81059f85: set_cache_qos_cfg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int set_cache_qos_cfg(int level, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81060d00)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1827
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
```
**Symbols:**

```
ffffffff81060d00-ffffffff81060e10: set_cache_qos_cfg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int set_cache_qos_cfg(int level, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105e5a0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1873
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
```
**Symbols:**

```
ffffffff8105e5a0-ffffffff8105e6fe: set_cache_qos_cfg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int set_cache_qos_cfg(int level, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105e970)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1873
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
```
**Symbols:**

```
ffffffff8105e970-ffffffff8105eace: set_cache_qos_cfg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int set_cache_qos_cfg(int level, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1836
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_arch_set_cdp_enabled
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_arch_set_cdp_enabled
```
**Symbols:**

```
ffffffff81068430-ffffffff810685a0: set_cache_qos_cfg (STB_LOCAL)
ffffffff81c9c7db-ffffffff81c9c7f6: set_cache_qos_cfg.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int set_cache_qos_cfg(int level, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1836
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_arch_set_cdp_enabled
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_arch_set_cdp_enabled
```
**Symbols:**

```
ffffffff81075470-ffffffff8107560c: set_cache_qos_cfg (STB_LOCAL)
ffffffff81e4bb0e-ffffffff81e4bb23: set_cache_qos_cfg.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int set_cache_qos_cfg(int level, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1841
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_arch_set_cdp_enabled
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_arch_set_cdp_enabled
```
**Symbols:**

```
ffffffff81085ed0-ffffffff81086078: set_cache_qos_cfg (STB_LOCAL)
ffffffff820531b1-ffffffff820531c6: set_cache_qos_cfg.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int set_cache_qos_cfg(int level, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2122
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_arch_set_cdp_enabled
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_arch_set_cdp_enabled
```
**Symbols:**

```
ffffffff81088580-ffffffff810886fb: set_cache_qos_cfg (STB_LOCAL)
ffffffff820d1720-ffffffff820d1734: set_cache_qos_cfg.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int set_cache_qos_cfg(int level, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2213
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_arch_set_cdp_enabled
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_arch_set_cdp_enabled
```
**Symbols:**

```
ffffffff8108f660-ffffffff8108f7db: set_cache_qos_cfg (STB_LOCAL)
ffffffff821ac36f-ffffffff821ac383: set_cache_qos_cfg.cold (STB_LOCAL)
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int set_cache_qos_cfg(int level, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff810599f0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1736
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cdp_disable_all
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cdp_disable_all
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cdp_enable
```
**Symbols:**

```
ffffffff810599f0-ffffffff81059b05: set_cache_qos_cfg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int set_cache_qos_cfg(int level, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81049b60)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1736
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cdp_disable_all
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cdp_disable_all
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cdp_enable
```
**Symbols:**

```
ffffffff81049b60-ffffffff81049c75: set_cache_qos_cfg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int set_cache_qos_cfg(int level, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81059e20)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1736
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cdp_disable_all
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cdp_disable_all
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cdp_enable
```
**Symbols:**

```
ffffffff81059e20-ffffffff81059f35: set_cache_qos_cfg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int set_cache_qos_cfg(int level, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105b340)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1736
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cdp_disable_all
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cdp_disable_all
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cdp_enable
```
**Symbols:**

```
ffffffff8105b340-ffffffff8105b46c: set_cache_qos_cfg (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
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
<b>Arch</b>
<ul>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
