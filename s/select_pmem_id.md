# Function: <code>select_pmem_id</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff8159e639)
Location: drivers/nvdimm/namespace_devs.c:1487
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff815f45c8)
Location: drivers/nvdimm/namespace_devs.c:1529
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
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
In drivers/nvdimm/namespace_devs.c (ffffffff81621232)
Location: drivers/nvdimm/namespace_devs.c:1642
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
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
In drivers/nvdimm/namespace_devs.c (ffffffff81635c17)
Location: drivers/nvdimm/namespace_devs.c:1811
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
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
In drivers/nvdimm/namespace_devs.c (ffffffff8169ee90)
Location: drivers/nvdimm/namespace_devs.c:1820
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
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
In drivers/nvdimm/namespace_devs.c (ffffffff816daf64)
Location: drivers/nvdimm/namespace_devs.c:1815
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
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
In drivers/nvdimm/namespace_devs.c (ffffffff816fcf11)
Location: drivers/nvdimm/namespace_devs.c:1841
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
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
In drivers/nvdimm/namespace_devs.c (ffffffff817351d9)
Location: drivers/nvdimm/namespace_devs.c:1848
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
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
In drivers/nvdimm/namespace_devs.c (ffffffff81758f69)
Location: drivers/nvdimm/namespace_devs.c:1848
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int select_pmem_id(struct nd_region *nd_region, u8 *pmem_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff818174e0)
Location: drivers/nvdimm/namespace_devs.c:1891
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
```
**Symbols:**

```
ffffffff818174e0-ffffffff81817644: select_pmem_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int select_pmem_id(struct nd_region *nd_region, u8 *pmem_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81826610)
Location: drivers/nvdimm/namespace_devs.c:1891
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
```
**Symbols:**

```
ffffffff81826610-ffffffff81826774: select_pmem_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int select_pmem_id(struct nd_region *nd_region, u8 *pmem_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81809870)
Location: drivers/nvdimm/namespace_devs.c:1891
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
```
**Symbols:**

```
ffffffff81809870-ffffffff818099d4: select_pmem_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int select_pmem_id(struct nd_region *nd_region, u8 *pmem_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81893d20)
Location: drivers/nvdimm/namespace_devs.c:1884
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
```
**Symbols:**

```
ffffffff81893d20-ffffffff81893e81: select_pmem_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int select_pmem_id(struct nd_region *nd_region, const uuid_t *pmem_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (0)
Location: drivers/nvdimm/namespace_devs.c:1610
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
```
**Symbols:**

```
ffffffff819df010-ffffffff819df22e: select_pmem_id (STB_LOCAL)
ffffffff81ed36d7-ffffffff81ed37b7: select_pmem_id.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int select_pmem_id(struct nd_region *nd_region, const uuid_t *pmem_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (0)
Location: drivers/nvdimm/namespace_devs.c:1602
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
```
**Symbols:**

```
ffffffff81b5af30-ffffffff81b5b14d: select_pmem_id (STB_LOCAL)
ffffffff8209a8cb-ffffffff8209a9ab: select_pmem_id.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int select_pmem_id(struct nd_region *nd_region, const uuid_t *pmem_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (0)
Location: drivers/nvdimm/namespace_devs.c:1602
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
```
**Symbols:**

```
ffffffff81badfb0-ffffffff81bae1f4: select_pmem_id (STB_LOCAL)
ffffffff8211ba28-ffffffff8211bab6: select_pmem_id.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int select_pmem_id(struct nd_region *nd_region, const uuid_t *pmem_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (0)
Location: drivers/nvdimm/namespace_devs.c:1611
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
```
**Symbols:**

```
ffffffff81c02320-ffffffff81c02564: select_pmem_id (STB_LOCAL)
ffffffff821f98af-ffffffff821f993d: select_pmem_id.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffff80001095a684)
Location: drivers/nvdimm/namespace_devs.c:1848
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
```
</details>
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
In drivers/nvdimm/namespace_devs.c (c000000000a0a808)
Location: drivers/nvdimm/namespace_devs.c:1848
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffe0005c8fbc)
Location: drivers/nvdimm/namespace_devs.c:1848
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
```
</details>
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
In drivers/nvdimm/namespace_devs.c (ffffffff8170d659)
Location: drivers/nvdimm/namespace_devs.c:1848
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
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
In drivers/nvdimm/namespace_devs.c (ffffffff816e10d9)
Location: drivers/nvdimm/namespace_devs.c:1848
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
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
In drivers/nvdimm/namespace_devs.c (ffffffff8174c429)
Location: drivers/nvdimm/namespace_devs.c:1848
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
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
In drivers/nvdimm/namespace_devs.c (ffffffff817678a9)
Location: drivers/nvdimm/namespace_devs.c:1848
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>u8 *pmem_id</code> ➡️ <code>const uuid_t *pmem_id</code>
</li>
</ul>
</details>
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
