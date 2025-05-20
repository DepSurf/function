# Function: <code>rdt_domain_reconfigure_cdp</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void rdt_domain_reconfigure_cdp(struct rdt_resource *r);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81062340)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1864
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
```
**Symbols:**

```
ffffffff81062340-ffffffff81062380: rdt_domain_reconfigure_cdp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void rdt_domain_reconfigure_cdp(struct rdt_resource *r);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81060890)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1915
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
```
**Symbols:**

```
ffffffff81060890-ffffffff810608d0: rdt_domain_reconfigure_cdp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void rdt_domain_reconfigure_cdp(struct rdt_resource *r);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff810609a0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1915
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
```
**Symbols:**

```
ffffffff810609a0-ffffffff810609e0: rdt_domain_reconfigure_cdp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void rdt_domain_reconfigure_cdp(struct rdt_resource *r);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1878
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
```
**Symbols:**

```
ffffffff81c9c94c-ffffffff81c9c961: rdt_domain_reconfigure_cdp.cold (STB_LOCAL)
ffffffff81069bb0-ffffffff81069c08: rdt_domain_reconfigure_cdp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void rdt_domain_reconfigure_cdp(struct rdt_resource *r);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1878
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
```
**Symbols:**

```
ffffffff81e4bc7d-ffffffff81e4bc92: rdt_domain_reconfigure_cdp.cold (STB_LOCAL)
ffffffff81076ed0-ffffffff81076f3c: rdt_domain_reconfigure_cdp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void rdt_domain_reconfigure_cdp(struct rdt_resource *r);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1883
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
```
**Symbols:**

```
ffffffff820532f5-ffffffff8205330a: rdt_domain_reconfigure_cdp.cold (STB_LOCAL)
ffffffff81087a10-ffffffff81087a7c: rdt_domain_reconfigure_cdp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void rdt_domain_reconfigure_cdp(struct rdt_resource *r);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2160
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
```
**Symbols:**

```
ffffffff820d1917-ffffffff820d192c: rdt_domain_reconfigure_cdp.cold (STB_LOCAL)
ffffffff8108a970-ffffffff8108a9dc: rdt_domain_reconfigure_cdp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void rdt_domain_reconfigure_cdp(struct rdt_resource *r);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2251
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
```
**Symbols:**

```
ffffffff821ac551-ffffffff821ac58f: rdt_domain_reconfigure_cdp.cold (STB_LOCAL)
ffffffff81091a90-ffffffff81091b4f: rdt_domain_reconfigure_cdp (STB_GLOBAL)
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
