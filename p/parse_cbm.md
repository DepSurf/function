# Function: <code>parse_cbm</code>

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
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_schemata.c (ffffffff81044bc0)
Location: arch/x86/kernel/cpu/intel_rdt_schemata.c:59
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_schemata.c:rdtgroup_schemata_write
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int parse_cbm(char *buf, struct rdt_resource *r, struct rdt_domain *d);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c (ffffffff81044a00)
Location: arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:110
Inline: False
```
**Symbols:**

```
ffffffff81044a00-ffffffff81044ae5: parse_cbm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int parse_cbm(char *buf, struct rdt_resource *r, struct rdt_domain *d);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c (ffffffff81048230)
Location: arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:128
Inline: False
```
**Symbols:**

```
ffffffff81048230-ffffffff81048394: parse_cbm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int parse_cbm(char *buf, struct rdt_resource *r, struct rdt_domain *d);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c (ffffffff8104aaf0)
Location: arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:129
Inline: False
```
**Symbols:**

```
ffffffff8104aaf0-ffffffff8104ac5b: parse_cbm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int parse_cbm(struct rdt_parse_data *data, struct rdt_resource *r, struct rdt_domain *d);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff8105b120)
Location: arch/x86/kernel/cpu/resctrl/ctrlmondata.c:202
Inline: False
```
**Symbols:**

```
ffffffff8105b120-ffffffff8105b2b7: parse_cbm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int parse_cbm(struct rdt_parse_data *data, struct rdt_resource *r, struct rdt_domain *d);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff8105e490)
Location: arch/x86/kernel/cpu/resctrl/ctrlmondata.c:194
Inline: False
```
**Symbols:**

```
ffffffff8105e490-ffffffff8105e623: parse_cbm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int parse_cbm(struct rdt_parse_data *data, struct rdt_resource *r, struct rdt_domain *d);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff8105ed10)
Location: arch/x86/kernel/cpu/resctrl/ctrlmondata.c:194
Inline: False
```
**Symbols:**

```
ffffffff8105ed10-ffffffff8105eea3: parse_cbm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int parse_cbm(struct rdt_parse_data *data, struct rdt_resource *r, struct rdt_domain *d);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff81064870)
Location: arch/x86/kernel/cpu/resctrl/ctrlmondata.c:194
Inline: False
```
**Symbols:**

```
ffffffff81064870-ffffffff81064a03: parse_cbm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int parse_cbm(struct rdt_parse_data *data, struct rdt_resource *r, struct rdt_domain *d);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff81062a90)
Location: arch/x86/kernel/cpu/resctrl/ctrlmondata.c:128
Inline: False
```
**Symbols:**

```
ffffffff81062a90-ffffffff81062c18: parse_cbm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int parse_cbm(struct rdt_parse_data *data, struct rdt_resource *r, struct rdt_domain *d);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff81063150)
Location: arch/x86/kernel/cpu/resctrl/ctrlmondata.c:128
Inline: False
```
**Symbols:**

```
ffffffff81063150-ffffffff810632e1: parse_cbm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int parse_cbm(struct rdt_parse_data *data, struct resctrl_schema *s, struct rdt_domain *d);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (0)
Location: arch/x86/kernel/cpu/resctrl/ctrlmondata.c:131
Inline: False
```
**Symbols:**

```
ffffffff81c9cd32-ffffffff81c9cd4f: parse_cbm.cold (STB_LOCAL)
ffffffff8106d020-ffffffff8106d1d6: parse_cbm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int parse_cbm(struct rdt_parse_data *data, struct resctrl_schema *s, struct rdt_domain *d);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (0)
Location: arch/x86/kernel/cpu/resctrl/ctrlmondata.c:131
Inline: False
```
**Symbols:**

```
ffffffff81e4c089-ffffffff81e4c0ac: parse_cbm.cold (STB_LOCAL)
ffffffff8107a500-ffffffff8107a6a4: parse_cbm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int parse_cbm(struct rdt_parse_data *data, struct resctrl_schema *s, struct rdt_domain *d);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (0)
Location: arch/x86/kernel/cpu/resctrl/ctrlmondata.c:137
Inline: False
```
**Symbols:**

```
ffffffff820536be-ffffffff820536e1: parse_cbm.cold (STB_LOCAL)
ffffffff8108b680-ffffffff8108b84a: parse_cbm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int parse_cbm(struct rdt_parse_data *data, struct resctrl_schema *s, struct rdt_domain *d);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (0)
Location: arch/x86/kernel/cpu/resctrl/ctrlmondata.c:137
Inline: False
```
**Symbols:**

```
ffffffff820d1cb1-ffffffff820d1cd4: parse_cbm.cold (STB_LOCAL)
ffffffff8108e5d0-ffffffff8108e79a: parse_cbm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int parse_cbm(struct rdt_parse_data *data, struct resctrl_schema *s, struct rdt_domain *d);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (0)
Location: arch/x86/kernel/cpu/resctrl/ctrlmondata.c:139
Inline: False
```
**Symbols:**

```
ffffffff821ac915-ffffffff821ac938: parse_cbm.cold (STB_LOCAL)
ffffffff81095960-ffffffff81095b2a: parse_cbm (STB_GLOBAL)
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
int parse_cbm(struct rdt_parse_data *data, struct rdt_resource *r, struct rdt_domain *d);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff8105e890)
Location: arch/x86/kernel/cpu/resctrl/ctrlmondata.c:194
Inline: False
```
**Symbols:**

```
ffffffff8105e890-ffffffff8105ea23: parse_cbm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int parse_cbm(struct rdt_parse_data *data, struct rdt_resource *r, struct rdt_domain *d);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff8104ebc0)
Location: arch/x86/kernel/cpu/resctrl/ctrlmondata.c:194
Inline: False
```
**Symbols:**

```
ffffffff8104ebc0-ffffffff8104ed53: parse_cbm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int parse_cbm(struct rdt_parse_data *data, struct rdt_resource *r, struct rdt_domain *d);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff8105ecc0)
Location: arch/x86/kernel/cpu/resctrl/ctrlmondata.c:194
Inline: False
```
**Symbols:**

```
ffffffff8105ecc0-ffffffff8105ee53: parse_cbm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int parse_cbm(struct rdt_parse_data *data, struct rdt_resource *r, struct rdt_domain *d);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff81060200)
Location: arch/x86/kernel/cpu/resctrl/ctrlmondata.c:194
Inline: False
```
**Symbols:**

```
ffffffff81060200-ffffffff81060393: parse_cbm (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct rdt_parse_data *data</code>
</li>
<li>
<b>Param removed. </b>
<code>char *buf</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct resctrl_schema *s</code>
</li>
<li>
<b>Param removed. </b>
<code>struct rdt_resource *r</code>
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
