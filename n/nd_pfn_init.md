# Function: <code>nd_pfn_init</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (ffffffff815f85a2)
Location: drivers/nvdimm/pfn_devs.c:556
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (ffffffff81626812)
Location: drivers/nvdimm/pfn_devs.c:556
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (ffffffff8163bc8b)
Location: drivers/nvdimm/pfn_devs.c:565
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (ffffffff816a48eb)
Location: drivers/nvdimm/pfn_devs.c:592
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (ffffffff816e093d)
Location: drivers/nvdimm/pfn_devs.c:593
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (ffffffff81702ebd)
Location: drivers/nvdimm/pfn_devs.c:685
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (ffffffff8173cc8f)
Location: drivers/nvdimm/pfn_devs.c:651
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (ffffffff81760a7f)
Location: drivers/nvdimm/pfn_devs.c:707
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int nd_pfn_init(struct nd_pfn *nd_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (0)
Location: drivers/nvdimm/pfn_devs.c:717
Inline: False
Direct callers:
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
```
**Symbols:**

```
ffffffff81820780-ffffffff81820a56: nd_pfn_init (STB_LOCAL)
ffffffff818210b4-ffffffff81821125: nd_pfn_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int nd_pfn_init(struct nd_pfn *nd_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (0)
Location: drivers/nvdimm/pfn_devs.c:718
Inline: False
Direct callers:
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
```
**Symbols:**

```
ffffffff8182f670-ffffffff8182f946: nd_pfn_init (STB_LOCAL)
ffffffff81c16008-ffffffff81c16079: nd_pfn_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int nd_pfn_init(struct nd_pfn *nd_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (0)
Location: drivers/nvdimm/pfn_devs.c:718
Inline: False
Direct callers:
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
```
**Symbols:**

```
ffffffff81812790-ffffffff81812a65: nd_pfn_init (STB_LOCAL)
ffffffff81c07d59-ffffffff81c07dca: nd_pfn_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int nd_pfn_init(struct nd_pfn *nd_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (0)
Location: drivers/nvdimm/pfn_devs.c:718
Inline: False
Direct callers:
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
```
**Symbols:**

```
ffffffff8189ce20-ffffffff8189d0f5: nd_pfn_init (STB_LOCAL)
ffffffff81d0b714-ffffffff81d0b785: nd_pfn_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int nd_pfn_init(struct nd_pfn *nd_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (0)
Location: drivers/nvdimm/pfn_devs.c:720
Inline: False
Direct callers:
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
```
**Symbols:**

```
ffffffff819e6730-ffffffff819e69fd: nd_pfn_init (STB_LOCAL)
ffffffff81ed4598-ffffffff81ed45fe: nd_pfn_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int nd_pfn_init(struct nd_pfn *nd_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (ffffffff81b62970)
Location: drivers/nvdimm/pfn_devs.c:722
Inline: False
Direct callers:
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
```
**Symbols:**

```
ffffffff81b62970-ffffffff81b62c98: nd_pfn_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int nd_pfn_init(struct nd_pfn *nd_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (ffffffff81bb5f50)
Location: drivers/nvdimm/pfn_devs.c:722
Inline: False
Direct callers:
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
```
**Symbols:**

```
ffffffff81bb5f50-ffffffff81bb6278: nd_pfn_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int nd_pfn_init(struct nd_pfn *nd_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (ffffffff81c0a540)
Location: drivers/nvdimm/pfn_devs.c:727
Inline: False
Direct callers:
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
```
**Symbols:**

```
ffffffff81c0a540-ffffffff81c0a866: nd_pfn_init (STB_LOCAL)
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
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (c000000000a161dc)
Location: drivers/nvdimm/pfn_devs.c:707
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (ffffffff8171516f)
Location: drivers/nvdimm/pfn_devs.c:707
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (ffffffff816e8bef)
Location: drivers/nvdimm/pfn_devs.c:707
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (ffffffff81753f3f)
Location: drivers/nvdimm/pfn_devs.c:707
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (ffffffff8176f3af)
Location: drivers/nvdimm/pfn_devs.c:707
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
```
</details>
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
