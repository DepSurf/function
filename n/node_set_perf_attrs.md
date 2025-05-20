# Function: <code>node_set_perf_attrs</code>

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
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void node_set_perf_attrs(unsigned int nid, struct node_hmem_attrs *hmem_attrs, unsigned int access);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/node.c (0)
Location: drivers/base/node.c:184
Inline: False
Direct callers:
  - drivers/acpi/hmat/hmat.c:hmat_init
```
**Symbols:**

```
ffffffff816f827e-ffffffff816f8292: node_set_perf_attrs.cold (STB_LOCAL)
ffffffff816f79f0-ffffffff816f7a82: node_set_perf_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void node_set_perf_attrs(unsigned int nid, struct node_hmem_attrs *hmem_attrs, unsigned int access);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/node.c (0)
Location: drivers/base/node.c:184
Inline: False
```
**Symbols:**

```
ffffffff8171c67e-ffffffff8171c692: node_set_perf_attrs.cold (STB_LOCAL)
ffffffff8171be50-ffffffff8171bee2: node_set_perf_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void node_set_perf_attrs(unsigned int nid, struct node_hmem_attrs *hmem_attrs, unsigned int access);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/node.c (0)
Location: drivers/base/node.c:184
Inline: False
```
**Symbols:**

```
ffffffff817d87b1-ffffffff817d87c5: node_set_perf_attrs.cold (STB_LOCAL)
ffffffff817d7ff0-ffffffff817d807d: node_set_perf_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void node_set_perf_attrs(unsigned int nid, struct node_hmem_attrs *hmem_attrs, unsigned int access);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/node.c (0)
Location: drivers/base/node.c:189
Inline: False
```
**Symbols:**

```
ffffffff81c0f30d-ffffffff81c0f321: node_set_perf_attrs.cold (STB_LOCAL)
ffffffff817ec970-ffffffff817eca32: node_set_perf_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void node_set_perf_attrs(unsigned int nid, struct node_hmem_attrs *hmem_attrs, unsigned int access);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/node.c (0)
Location: drivers/base/node.c:189
Inline: False
```
**Symbols:**

```
ffffffff81c01466-ffffffff81c0147a: node_set_perf_attrs.cold (STB_LOCAL)
ffffffff817d1190-ffffffff817d121d: node_set_perf_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void node_set_perf_attrs(unsigned int nid, struct node_hmem_attrs *hmem_attrs, unsigned int access);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/node.c (0)
Location: drivers/base/node.c:193
Inline: False
```
**Symbols:**

```
ffffffff81d04413-ffffffff81d04427: node_set_perf_attrs.cold (STB_LOCAL)
ffffffff8185bc20-ffffffff8185bcec: node_set_perf_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void node_set_perf_attrs(unsigned int nid, struct node_hmem_attrs *hmem_attrs, unsigned int access);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/node.c (0)
Location: drivers/base/node.c:193
Inline: False
```
**Symbols:**

```
ffffffff81eccdaf-ffffffff81eccdc3: node_set_perf_attrs.cold (STB_LOCAL)
ffffffff819a2cd0-ffffffff819a2db6: node_set_perf_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void node_set_perf_attrs(unsigned int nid, struct node_hmem_attrs *hmem_attrs, unsigned int access);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/node.c (ffffffff81b14c00)
Location: drivers/base/node.c:194
Inline: False
```
**Symbols:**

```
ffffffff81b14c00-ffffffff81b14cf3: node_set_perf_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void node_set_perf_attrs(unsigned int nid, struct node_hmem_attrs *hmem_attrs, unsigned int access);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/node.c (ffffffff81b63970)
Location: drivers/base/node.c:194
Inline: False
```
**Symbols:**

```
ffffffff81b63970-ffffffff81b63a63: node_set_perf_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void node_set_perf_attrs(unsigned int nid, struct access_coordinate *coord, unsigned int access);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/node.c (ffffffff81bb74b0)
Location: drivers/base/node.c:193
Inline: False
Direct callers:
  - drivers/acpi/numa/hmat.c:hmat_register_target
  - drivers/acpi/numa/hmat.c:hmat_register_target
```
**Symbols:**

```
ffffffff81bb74b0-ffffffff81bb75a3: node_set_perf_attrs (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void node_set_perf_attrs(unsigned int nid, struct node_hmem_attrs *hmem_attrs, unsigned int access);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/node.c (ffff80001090f918)
Location: drivers/base/node.c:184
Inline: False
```
**Symbols:**

```
ffff80001090f918-ffff80001090fa08: node_set_perf_attrs (STB_GLOBAL)
```
</details>
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void node_set_perf_attrs(unsigned int nid, struct node_hmem_attrs *hmem_attrs, unsigned int access);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/node.c (0)
Location: drivers/base/node.c:184
Inline: False
```
**Symbols:**

```
ffffffff816e29ae-ffffffff816e29c2: node_set_perf_attrs.cold (STB_LOCAL)
ffffffff816e2180-ffffffff816e2212: node_set_perf_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void node_set_perf_attrs(unsigned int nid, struct node_hmem_attrs *hmem_attrs, unsigned int access);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/node.c (0)
Location: drivers/base/node.c:184
Inline: False
```
**Symbols:**

```
ffffffff816bcfee-ffffffff816bd002: node_set_perf_attrs.cold (STB_LOCAL)
ffffffff816bc7c0-ffffffff816bc852: node_set_perf_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void node_set_perf_attrs(unsigned int nid, struct node_hmem_attrs *hmem_attrs, unsigned int access);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/node.c (0)
Location: drivers/base/node.c:184
Inline: False
```
**Symbols:**

```
ffffffff8172ac9e-ffffffff8172acb2: node_set_perf_attrs.cold (STB_LOCAL)
ffffffff8172a470-ffffffff8172a502: node_set_perf_attrs (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct access_coordinate *coord</code>
</li>
<li>
<b>Param removed. </b>
<code>struct node_hmem_attrs *hmem_attrs</code>
</li>
</ul>
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
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
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
