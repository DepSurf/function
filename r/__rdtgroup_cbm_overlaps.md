# Function: <code>__rdtgroup_cbm_overlaps</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool __rdtgroup_cbm_overlaps(struct rdt_resource *r, struct rdt_domain *d, long unsigned int cbm, int closid, bool exclusive);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff810578f0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1064
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_overlaps
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_overlaps
```
**Symbols:**

```
ffffffff810578f0-ffffffff81057a32: __rdtgroup_cbm_overlaps (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool __rdtgroup_cbm_overlaps(struct rdt_resource *r, struct rdt_domain *d, long unsigned int cbm, int closid, bool exclusive);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105ab60)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1062
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_overlaps
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_overlaps
```
**Symbols:**

```
ffffffff8105ab60-ffffffff8105ac89: __rdtgroup_cbm_overlaps (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool __rdtgroup_cbm_overlaps(struct rdt_resource *r, struct rdt_domain *d, long unsigned int cbm, int closid, bool exclusive);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105b450)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1060
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_overlaps
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_overlaps
```
**Symbols:**

```
ffffffff8105b450-ffffffff8105b579: __rdtgroup_cbm_overlaps (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool __rdtgroup_cbm_overlaps(struct rdt_resource *r, struct rdt_domain *d, long unsigned int cbm, int closid, bool exclusive);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff810607d0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1151
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_overlaps
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_overlaps
```
**Symbols:**

```
ffffffff810607d0-ffffffff810608f9: __rdtgroup_cbm_overlaps (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool __rdtgroup_cbm_overlaps(struct rdt_resource *r, struct rdt_domain *d, long unsigned int cbm, int closid, bool exclusive);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105ea10)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1173
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_overlaps
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_overlaps
```
**Symbols:**

```
ffffffff8105ea10-ffffffff8105eb39: __rdtgroup_cbm_overlaps (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool __rdtgroup_cbm_overlaps(struct rdt_resource *r, struct rdt_domain *d, long unsigned int cbm, int closid, bool exclusive);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105f230)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1173
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_overlaps
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_overlaps
```
**Symbols:**

```
ffffffff8105f230-ffffffff8105f359: __rdtgroup_cbm_overlaps (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool __rdtgroup_cbm_overlaps(struct rdt_resource *r, struct rdt_domain *d, long unsigned int cbm, int closid, enum resctrl_conf_type type, bool exclusive);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1128
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_overlaps
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_overlaps
```
**Symbols:**

```
ffffffff81068ba0-ffffffff81068ce5: __rdtgroup_cbm_overlaps (STB_LOCAL)
ffffffff81c9c84b-ffffffff81c9c86a: __rdtgroup_cbm_overlaps.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool __rdtgroup_cbm_overlaps(struct rdt_resource *r, struct rdt_domain *d, long unsigned int cbm, int closid, enum resctrl_conf_type type, bool exclusive);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1128
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_overlaps
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_overlaps
```
**Symbols:**

```
ffffffff81075d00-ffffffff81075e5f: __rdtgroup_cbm_overlaps (STB_LOCAL)
ffffffff81e4bb78-ffffffff81e4bb97: __rdtgroup_cbm_overlaps.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool __rdtgroup_cbm_overlaps(struct rdt_resource *r, struct rdt_domain *d, long unsigned int cbm, int closid, enum resctrl_conf_type type, bool exclusive);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1125
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_overlaps
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_overlaps
```
**Symbols:**

```
ffffffff81085d60-ffffffff81085ebf: __rdtgroup_cbm_overlaps (STB_LOCAL)
ffffffff82053192-ffffffff820531b1: __rdtgroup_cbm_overlaps.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool __rdtgroup_cbm_overlaps(struct rdt_resource *r, struct rdt_domain *d, long unsigned int cbm, int closid, enum resctrl_conf_type type, bool exclusive);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1140
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_overlaps
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_overlaps
```
**Symbols:**

```
ffffffff81088a00-ffffffff81088b5f: __rdtgroup_cbm_overlaps (STB_LOCAL)
ffffffff820d174d-ffffffff820d176c: __rdtgroup_cbm_overlaps.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool __rdtgroup_cbm_overlaps(struct rdt_resource *r, struct rdt_domain *d, long unsigned int cbm, int closid, enum resctrl_conf_type type, bool exclusive);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1208
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_overlaps
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_overlaps
```
**Symbols:**

```
ffffffff8108fae0-ffffffff8108fc3f: __rdtgroup_cbm_overlaps (STB_LOCAL)
ffffffff821ac39c-ffffffff821ac3bb: __rdtgroup_cbm_overlaps.cold (STB_LOCAL)
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
bool __rdtgroup_cbm_overlaps(struct rdt_resource *r, struct rdt_domain *d, long unsigned int cbm, int closid, bool exclusive);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105afd0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1060
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_overlaps
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_overlaps
```
**Symbols:**

```
ffffffff8105afd0-ffffffff8105b0f9: __rdtgroup_cbm_overlaps (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool __rdtgroup_cbm_overlaps(struct rdt_resource *r, struct rdt_domain *d, long unsigned int cbm, int closid, bool exclusive);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8104b160)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1060
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_overlaps
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_overlaps
```
**Symbols:**

```
ffffffff8104b160-ffffffff8104b289: __rdtgroup_cbm_overlaps (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool __rdtgroup_cbm_overlaps(struct rdt_resource *r, struct rdt_domain *d, long unsigned int cbm, int closid, bool exclusive);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105b400)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1060
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_overlaps
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_overlaps
```
**Symbols:**

```
ffffffff8105b400-ffffffff8105b529: __rdtgroup_cbm_overlaps (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool __rdtgroup_cbm_overlaps(struct rdt_resource *r, struct rdt_domain *d, long unsigned int cbm, int closid, bool exclusive);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105c8c0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1060
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_overlaps
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_overlaps
```
**Symbols:**

```
ffffffff8105c8c0-ffffffff8105c9e9: __rdtgroup_cbm_overlaps (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum resctrl_conf_type type</code>
</li>
<li>
<b>Param reordered. </b>
<code>r, d, cbm, closid, exclusive</code> ➡️ <code>r, d, cbm, closid, type, exclusive</code>
</li>
</ul>
</details>
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
