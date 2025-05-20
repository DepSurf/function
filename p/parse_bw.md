# Function: <code>parse_bw</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int parse_bw(char *buf, struct rdt_resource *r, struct rdt_domain *d);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c (ffffffff81044950)
Location: arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:59
Inline: False
```
**Symbols:**

```
ffffffff81044950-ffffffff810449f7: parse_bw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int parse_bw(char *buf, struct rdt_resource *r, struct rdt_domain *d);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c (ffffffff81048120)
Location: arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:66
Inline: False
```
**Symbols:**

```
ffffffff81048120-ffffffff81048226: parse_bw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int parse_bw(char *buf, struct rdt_resource *r, struct rdt_domain *d);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c (ffffffff8104a9c0)
Location: arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:67
Inline: False
```
**Symbols:**

```
ffffffff8104a9c0-ffffffff8104aaec: parse_bw (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int parse_bw(struct rdt_parse_data *data, struct rdt_resource *r, struct rdt_domain *d);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff81062960)
Location: arch/x86/kernel/cpu/resctrl/ctrlmondata.c:60
Inline: False
```
**Symbols:**

```
ffffffff81062960-ffffffff81062a8b: parse_bw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int parse_bw(struct rdt_parse_data *data, struct rdt_resource *r, struct rdt_domain *d);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff81063020)
Location: arch/x86/kernel/cpu/resctrl/ctrlmondata.c:60
Inline: False
```
**Symbols:**

```
ffffffff81063020-ffffffff8106314b: parse_bw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int parse_bw(struct rdt_parse_data *data, struct resctrl_schema *s, struct rdt_domain *d);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (0)
Location: arch/x86/kernel/cpu/resctrl/ctrlmondata.c:60
Inline: False
```
**Symbols:**

```
ffffffff81c9cd08-ffffffff81c9cd32: parse_bw.cold (STB_LOCAL)
ffffffff8106ceb0-ffffffff8106d011: parse_bw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int parse_bw(struct rdt_parse_data *data, struct resctrl_schema *s, struct rdt_domain *d);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (0)
Location: arch/x86/kernel/cpu/resctrl/ctrlmondata.c:60
Inline: False
```
**Symbols:**

```
ffffffff81e4c05f-ffffffff81e4c089: parse_bw.cold (STB_LOCAL)
ffffffff8107a390-ffffffff8107a4f2: parse_bw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int parse_bw(struct rdt_parse_data *data, struct resctrl_schema *s, struct rdt_domain *d);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (0)
Location: arch/x86/kernel/cpu/resctrl/ctrlmondata.c:60
Inline: False
```
**Symbols:**

```
ffffffff82053694-ffffffff820536be: parse_bw.cold (STB_LOCAL)
ffffffff8108b4b0-ffffffff8108b663: parse_bw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int parse_bw(struct rdt_parse_data *data, struct resctrl_schema *s, struct rdt_domain *d);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (0)
Location: arch/x86/kernel/cpu/resctrl/ctrlmondata.c:60
Inline: False
```
**Symbols:**

```
ffffffff820d1c87-ffffffff820d1cb1: parse_bw.cold (STB_LOCAL)
ffffffff8108e400-ffffffff8108e5b3: parse_bw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int parse_bw(struct rdt_parse_data *data, struct resctrl_schema *s, struct rdt_domain *d);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (0)
Location: arch/x86/kernel/cpu/resctrl/ctrlmondata.c:60
Inline: False
```
**Symbols:**

```
ffffffff821ac8eb-ffffffff821ac915: parse_bw.cold (STB_LOCAL)
ffffffff81095790-ffffffff81095943: parse_bw (STB_GLOBAL)
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
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
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
