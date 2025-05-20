# Function: <code>nd_pfn_validate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int nd_pfn_validate(struct nd_pfn *nd_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (ffffffff815a1980)
Location: drivers/nvdimm/pfn_devs.c:231
Inline: False
Direct callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
```
**Symbols:**

```
ffffffff815a1980-ffffffff815a1b58: nd_pfn_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int nd_pfn_validate(struct nd_pfn *nd_pfn, const char *sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (ffffffff815f8230)
Location: drivers/nvdimm/pfn_devs.c:344
Inline: False
Direct callers:
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
```
**Symbols:**

```
ffffffff815f8230-ffffffff815f8550: nd_pfn_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int nd_pfn_validate(struct nd_pfn *nd_pfn, const char *sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (ffffffff816264a0)
Location: drivers/nvdimm/pfn_devs.c:344
Inline: False
Direct callers:
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
```
**Symbols:**

```
ffffffff816264a0-ffffffff816267c0: nd_pfn_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int nd_pfn_validate(struct nd_pfn *nd_pfn, const char *sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (ffffffff8163b650)
Location: drivers/nvdimm/pfn_devs.c:344
Inline: False
Direct callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
```
**Symbols:**

```
ffffffff8163b650-ffffffff8163b970: nd_pfn_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int nd_pfn_validate(struct nd_pfn *nd_pfn, const char *sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (ffffffff816a43c0)
Location: drivers/nvdimm/pfn_devs.c:364
Inline: False
Direct callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
```
**Symbols:**

```
ffffffff816a43c0-ffffffff816a4708: nd_pfn_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int nd_pfn_validate(struct nd_pfn *nd_pfn, const char *sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (ffffffff816e05a0)
Location: drivers/nvdimm/pfn_devs.c:364
Inline: False
Direct callers:
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
```
**Symbols:**

```
ffffffff816e05a0-ffffffff816e08e5: nd_pfn_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int nd_pfn_validate(struct nd_pfn *nd_pfn, const char *sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (ffffffff81702960)
Location: drivers/nvdimm/pfn_devs.c:423
Inline: False
Direct callers:
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
```
**Symbols:**

```
ffffffff81702960-ffffffff81702e69: nd_pfn_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int nd_pfn_validate(struct nd_pfn *nd_pfn, const char *sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (0)
Location: drivers/nvdimm/pfn_devs.c:424
Inline: False
Direct callers:
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
```
**Symbols:**

```
ffffffff8173d4b0-ffffffff8173d588: nd_pfn_validate.cold (STB_LOCAL)
ffffffff8173c800-ffffffff8173cc38: nd_pfn_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int nd_pfn_validate(struct nd_pfn *nd_pfn, const char *sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (0)
Location: drivers/nvdimm/pfn_devs.c:445
Inline: False
Direct callers:
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
```
**Symbols:**

```
ffffffff817612f1-ffffffff81761407: nd_pfn_validate.cold (STB_LOCAL)
ffffffff817604f0-ffffffff81760a2a: nd_pfn_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int nd_pfn_validate(struct nd_pfn *nd_pfn, const char *sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (0)
Location: drivers/nvdimm/pfn_devs.c:446
Inline: False
Direct callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_init
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
```
**Symbols:**

```
ffffffff81820f4f-ffffffff8182107a: nd_pfn_validate.cold (STB_LOCAL)
ffffffff8181fff0-ffffffff818203e0: nd_pfn_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int nd_pfn_validate(struct nd_pfn *nd_pfn, const char *sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (0)
Location: drivers/nvdimm/pfn_devs.c:446
Inline: False
Direct callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_init
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
```
**Symbols:**

```
ffffffff81c15ea3-ffffffff81c15fce: nd_pfn_validate.cold (STB_LOCAL)
ffffffff8182ef20-ffffffff8182f310: nd_pfn_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int nd_pfn_validate(struct nd_pfn *nd_pfn, const char *sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (0)
Location: drivers/nvdimm/pfn_devs.c:446
Inline: False
Direct callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_init
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
```
**Symbols:**

```
ffffffff81c07c0c-ffffffff81c07d37: nd_pfn_validate.cold (STB_LOCAL)
ffffffff818121d0-ffffffff818125aa: nd_pfn_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int nd_pfn_validate(struct nd_pfn *nd_pfn, const char *sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (0)
Location: drivers/nvdimm/pfn_devs.c:446
Inline: False
Direct callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_init
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
```
**Symbols:**

```
ffffffff81d0b5a7-ffffffff81d0b6f2: nd_pfn_validate.cold (STB_LOCAL)
ffffffff8189c7e0-ffffffff8189cc32: nd_pfn_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int nd_pfn_validate(struct nd_pfn *nd_pfn, const char *sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (0)
Location: drivers/nvdimm/pfn_devs.c:448
Inline: False
Direct callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_init
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
```
**Symbols:**

```
ffffffff81ed446a-ffffffff81ed4576: nd_pfn_validate.cold (STB_LOCAL)
ffffffff819e60a0-ffffffff819e6503: nd_pfn_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int nd_pfn_validate(struct nd_pfn *nd_pfn, const char *sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (0)
Location: drivers/nvdimm/pfn_devs.c:450
Inline: False
Direct callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_init
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
```
**Symbols:**

```
ffffffff8209b4ab-ffffffff8209b4ce: nd_pfn_validate.cold (STB_LOCAL)
ffffffff81b62040-ffffffff81b6257b: nd_pfn_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int nd_pfn_validate(struct nd_pfn *nd_pfn, const char *sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (0)
Location: drivers/nvdimm/pfn_devs.c:450
Inline: False
Direct callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_init
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
```
**Symbols:**

```
ffffffff8211c37a-ffffffff8211c39d: nd_pfn_validate.cold (STB_LOCAL)
ffffffff81bb5640-ffffffff81bb5b7e: nd_pfn_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int nd_pfn_validate(struct nd_pfn *nd_pfn, const char *sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (0)
Location: drivers/nvdimm/pfn_devs.c:450
Inline: False
Direct callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_init
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
```
**Symbols:**

```
ffffffff821fa201-ffffffff821fa224: nd_pfn_validate.cold (STB_LOCAL)
ffffffff81c09bc0-ffffffff81c0a155: nd_pfn_validate (STB_GLOBAL)
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
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int nd_pfn_validate(struct nd_pfn *nd_pfn, const char *sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (c000000000a159b0)
Location: drivers/nvdimm/pfn_devs.c:445
Inline: False
Direct callers:
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
```
**Symbols:**

```
c000000000a159b0-c000000000a16190: nd_pfn_validate (STB_GLOBAL)
```
</details>
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
int nd_pfn_validate(struct nd_pfn *nd_pfn, const char *sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (0)
Location: drivers/nvdimm/pfn_devs.c:445
Inline: False
Direct callers:
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
```
**Symbols:**

```
ffffffff817159e1-ffffffff81715af7: nd_pfn_validate.cold (STB_LOCAL)
ffffffff81714be0-ffffffff8171511a: nd_pfn_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int nd_pfn_validate(struct nd_pfn *nd_pfn, const char *sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (0)
Location: drivers/nvdimm/pfn_devs.c:445
Inline: False
Direct callers:
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
```
**Symbols:**

```
ffffffff816e9461-ffffffff816e9577: nd_pfn_validate.cold (STB_LOCAL)
ffffffff816e8660-ffffffff816e8b9a: nd_pfn_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int nd_pfn_validate(struct nd_pfn *nd_pfn, const char *sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (0)
Location: drivers/nvdimm/pfn_devs.c:445
Inline: False
Direct callers:
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
```
**Symbols:**

```
ffffffff817547b1-ffffffff817548c7: nd_pfn_validate.cold (STB_LOCAL)
ffffffff817539b0-ffffffff81753eea: nd_pfn_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int nd_pfn_validate(struct nd_pfn *nd_pfn, const char *sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (0)
Location: drivers/nvdimm/pfn_devs.c:445
Inline: False
Direct callers:
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
```
**Symbols:**

```
ffffffff8176fc21-ffffffff8176fd37: nd_pfn_validate.cold (STB_LOCAL)
ffffffff8176ee20-ffffffff8176f35a: nd_pfn_validate (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const char *sig</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
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
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
