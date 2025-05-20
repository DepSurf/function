# Function: <code>to_nvdimm_cclass</code>

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
enum nvdimm_claim_class to_nvdimm_cclass(guid_t *guid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff816393b0)
Location: drivers/nvdimm/label.c:578
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:create_namespace_blk
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
```
**Symbols:**

```
ffffffff816393b0-ffffffff81639451: to_nvdimm_cclass (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
enum nvdimm_claim_class to_nvdimm_cclass(guid_t *guid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff816a1a80)
Location: drivers/nvdimm/label.c:580
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
**Symbols:**

```
ffffffff816a1a80-ffffffff816a1b21: to_nvdimm_cclass (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
enum nvdimm_claim_class to_nvdimm_cclass(guid_t *guid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff816de210)
Location: drivers/nvdimm/label.c:589
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
**Symbols:**

```
ffffffff816de210-ffffffff816de2b1: to_nvdimm_cclass (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
enum nvdimm_claim_class to_nvdimm_cclass(guid_t *guid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff81700570)
Location: drivers/nvdimm/label.c:719
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
**Symbols:**

```
ffffffff81700570-ffffffff81700611: to_nvdimm_cclass (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
enum nvdimm_claim_class to_nvdimm_cclass(guid_t *guid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff8173a340)
Location: drivers/nvdimm/label.c:716
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
```
**Symbols:**

```
ffffffff8173a340-ffffffff8173a3e1: to_nvdimm_cclass (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
enum nvdimm_claim_class to_nvdimm_cclass(guid_t *guid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff8175e0b0)
Location: drivers/nvdimm/label.c:711
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
```
**Symbols:**

```
ffffffff8175e0b0-ffffffff8175e151: to_nvdimm_cclass (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
enum nvdimm_claim_class to_nvdimm_cclass(guid_t *guid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff8181da50)
Location: drivers/nvdimm/label.c:711
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:create_namespace_blk
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
```
**Symbols:**

```
ffffffff8181da50-ffffffff8181daf1: to_nvdimm_cclass (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
enum nvdimm_claim_class to_nvdimm_cclass(guid_t *guid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff8182cb70)
Location: drivers/nvdimm/label.c:711
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:create_namespace_blk
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
```
**Symbols:**

```
ffffffff8182cb70-ffffffff8182cc11: to_nvdimm_cclass (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
enum nvdimm_claim_class to_nvdimm_cclass(guid_t *guid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff8180fec0)
Location: drivers/nvdimm/label.c:711
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:create_namespace_blk
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
```
**Symbols:**

```
ffffffff8180fec0-ffffffff8180ff61: to_nvdimm_cclass (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff8189a49b)
Location: drivers/nvdimm/label.c:727
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nsl_get_claim_class
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
enum nvdimm_claim_class to_nvdimm_cclass(guid_t *guid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffff80001095f6a0)
Location: drivers/nvdimm/label.c:711
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
```
**Symbols:**

```
ffff80001095f6a0-ffff80001095f79c: to_nvdimm_cclass (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
enum nvdimm_claim_class to_nvdimm_cclass(guid_t *guid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (c000000000a12050)
Location: drivers/nvdimm/label.c:711
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
```
**Symbols:**

```
c000000000a12050-c000000000a121b8: to_nvdimm_cclass (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
enum nvdimm_claim_class to_nvdimm_cclass(guid_t *guid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffe0005cd402)
Location: drivers/nvdimm/label.c:711
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
```
**Symbols:**

```
ffffffe0005cd402-ffffffe0005cd4a2: to_nvdimm_cclass (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
enum nvdimm_claim_class to_nvdimm_cclass(guid_t *guid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff817127a0)
Location: drivers/nvdimm/label.c:711
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
```
**Symbols:**

```
ffffffff817127a0-ffffffff81712841: to_nvdimm_cclass (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
enum nvdimm_claim_class to_nvdimm_cclass(guid_t *guid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff816e6220)
Location: drivers/nvdimm/label.c:711
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
```
**Symbols:**

```
ffffffff816e6220-ffffffff816e62c1: to_nvdimm_cclass (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
enum nvdimm_claim_class to_nvdimm_cclass(guid_t *guid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff81751570)
Location: drivers/nvdimm/label.c:711
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
```
**Symbols:**

```
ffffffff81751570-ffffffff81751611: to_nvdimm_cclass (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
enum nvdimm_claim_class to_nvdimm_cclass(guid_t *guid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff8176c9f0)
Location: drivers/nvdimm/label.c:711
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
```
**Symbols:**

```
ffffffff8176c9f0-ffffffff8176ca91: to_nvdimm_cclass (STB_GLOBAL)
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
