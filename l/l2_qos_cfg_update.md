# Function: <code>l2_qos_cfg_update</code>

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
void l2_qos_cfg_update(void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff810473a0)
Location: arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:1002
Inline: False
```
**Symbols:**

```
ffffffff810473a0-ffffffff810473bc: l2_qos_cfg_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void l2_qos_cfg_update(void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff810563b0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1728
Inline: False
```
**Symbols:**

```
ffffffff810563b0-ffffffff810563cc: l2_qos_cfg_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void l2_qos_cfg_update(void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105ac90)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1726
Inline: False
```
**Symbols:**

```
ffffffff8105ac90-ffffffff8105acac: l2_qos_cfg_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void l2_qos_cfg_update(void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81059dd0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1724
Inline: False
```
**Symbols:**

```
ffffffff81059dd0-ffffffff81059dec: l2_qos_cfg_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void l2_qos_cfg_update(void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff810603f0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1815
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_domain_reconfigure_cdp
```
**Symbols:**

```
ffffffff810603f0-ffffffff8106040c: l2_qos_cfg_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void l2_qos_cfg_update(void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105e580)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1861
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_domain_reconfigure_cdp
```
**Symbols:**

```
ffffffff8105e580-ffffffff8105e59c: l2_qos_cfg_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void l2_qos_cfg_update(void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105ef70)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1861
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_domain_reconfigure_cdp
```
**Symbols:**

```
ffffffff8105ef70-ffffffff8105ef8c: l2_qos_cfg_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void l2_qos_cfg_update(void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1824
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_domain_reconfigure_cdp
```
**Symbols:**

```
ffffffff81068890-ffffffff810688c0: l2_qos_cfg_update (STB_LOCAL)
ffffffff81c9c81e-ffffffff81c9c832: l2_qos_cfg_update.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void l2_qos_cfg_update(void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1824
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_domain_reconfigure_cdp
```
**Symbols:**

```
ffffffff81075940-ffffffff81075989: l2_qos_cfg_update (STB_LOCAL)
ffffffff81e4bb37-ffffffff81e4bb4b: l2_qos_cfg_update.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void l2_qos_cfg_update(void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1829
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_domain_reconfigure_cdp
```
**Symbols:**

```
ffffffff81085a00-ffffffff81085a49: l2_qos_cfg_update (STB_LOCAL)
ffffffff82053165-ffffffff82053179: l2_qos_cfg_update.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void l2_qos_cfg_update(void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2110
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_domain_reconfigure_cdp
```
**Symbols:**

```
ffffffff81088c80-ffffffff81088cc9: l2_qos_cfg_update (STB_LOCAL)
ffffffff820d176c-ffffffff820d1780: l2_qos_cfg_update.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void l2_qos_cfg_update(void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81091b23)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2201
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_domain_reconfigure_cdp
```
**Symbols:**

```
ffffffff81090170-ffffffff810901b9: l2_qos_cfg_update (STB_LOCAL)
ffffffff821ac3ee-ffffffff821ac402: l2_qos_cfg_update.cold (STB_LOCAL)
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
void l2_qos_cfg_update(void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81059950)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1724
Inline: False
```
**Symbols:**

```
ffffffff81059950-ffffffff8105996c: l2_qos_cfg_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void l2_qos_cfg_update(void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8104b780)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1724
Inline: False
```
**Symbols:**

```
ffffffff8104b780-ffffffff8104b7ac: l2_qos_cfg_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void l2_qos_cfg_update(void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81059d80)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1724
Inline: False
```
**Symbols:**

```
ffffffff81059d80-ffffffff81059d9c: l2_qos_cfg_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void l2_qos_cfg_update(void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105b220)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1724
Inline: False
```
**Symbols:**

```
ffffffff8105b220-ffffffff8105b23c: l2_qos_cfg_update (STB_LOCAL)
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
