# Function: <code>l3_qos_cfg_update</code>

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
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void l3_qos_cfg_update(void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff810434d0)
Location: arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:592
Inline: True
```
**Symbols:**

```
ffffffff810434d0-ffffffff810434ec: l3_qos_cfg_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void l3_qos_cfg_update(void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81041b90)
Location: arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:925
Inline: True
```
**Symbols:**

```
ffffffff81041b90-ffffffff81041bac: l3_qos_cfg_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void l3_qos_cfg_update(void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81045ad0)
Location: arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:993
Inline: True
```
**Symbols:**

```
ffffffff81045ad0-ffffffff81045aec: l3_qos_cfg_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void l3_qos_cfg_update(void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81047e30)
Location: arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:995
Inline: False
```
**Symbols:**

```
ffffffff81047e30-ffffffff81047e4c: l3_qos_cfg_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void l3_qos_cfg_update(void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81057a40)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1721
Inline: False
```
**Symbols:**

```
ffffffff81057a40-ffffffff81057a5c: l3_qos_cfg_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void l3_qos_cfg_update(void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81059500)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1719
Inline: False
```
**Symbols:**

```
ffffffff81059500-ffffffff8105951c: l3_qos_cfg_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void l3_qos_cfg_update(void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105b580)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1717
Inline: False
```
**Symbols:**

```
ffffffff8105b580-ffffffff8105b59c: l3_qos_cfg_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void l3_qos_cfg_update(void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff810603d0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1808
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_domain_reconfigure_cdp
```
**Symbols:**

```
ffffffff810603d0-ffffffff810603ec: l3_qos_cfg_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void l3_qos_cfg_update(void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105e560)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1854
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_domain_reconfigure_cdp
```
**Symbols:**

```
ffffffff8105e560-ffffffff8105e57c: l3_qos_cfg_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void l3_qos_cfg_update(void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105ef50)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1854
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_domain_reconfigure_cdp
```
**Symbols:**

```
ffffffff8105ef50-ffffffff8105ef6c: l3_qos_cfg_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void l3_qos_cfg_update(void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1817
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_domain_reconfigure_cdp
```
**Symbols:**

```
ffffffff81068860-ffffffff81068890: l3_qos_cfg_update (STB_LOCAL)
ffffffff81c9c80a-ffffffff81c9c81e: l3_qos_cfg_update.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void l3_qos_cfg_update(void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1817
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_domain_reconfigure_cdp
```
**Symbols:**

```
ffffffff81075990-ffffffff810759d9: l3_qos_cfg_update (STB_LOCAL)
ffffffff81e4bb4b-ffffffff81e4bb5f: l3_qos_cfg_update.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void l3_qos_cfg_update(void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1822
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_domain_reconfigure_cdp
```
**Symbols:**

```
ffffffff810859a0-ffffffff810859e9: l3_qos_cfg_update (STB_LOCAL)
ffffffff82053151-ffffffff82053165: l3_qos_cfg_update.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void l3_qos_cfg_update(void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2103
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_domain_reconfigure_cdp
```
**Symbols:**

```
ffffffff81088ce0-ffffffff81088d29: l3_qos_cfg_update (STB_LOCAL)
ffffffff820d1780-ffffffff820d1794: l3_qos_cfg_update.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void l3_qos_cfg_update(void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81091ae1)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2194
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_domain_reconfigure_cdp
```
**Symbols:**

```
ffffffff81090110-ffffffff81090159: l3_qos_cfg_update (STB_LOCAL)
ffffffff821ac3da-ffffffff821ac3ee: l3_qos_cfg_update.cold (STB_LOCAL)
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
void l3_qos_cfg_update(void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105b100)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1717
Inline: False
```
**Symbols:**

```
ffffffff8105b100-ffffffff8105b11c: l3_qos_cfg_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void l3_qos_cfg_update(void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8104b750)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1717
Inline: False
```
**Symbols:**

```
ffffffff8104b750-ffffffff8104b77c: l3_qos_cfg_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void l3_qos_cfg_update(void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105b530)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1717
Inline: False
```
**Symbols:**

```
ffffffff8105b530-ffffffff8105b54c: l3_qos_cfg_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void l3_qos_cfg_update(void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105c9f0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1717
Inline: False
```
**Symbols:**

```
ffffffff8105c9f0-ffffffff8105ca0c: l3_qos_cfg_update (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
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
