# Function: <code>dname_to_vma_addr</code>

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
In fs/proc/base.c (ffffffff8127c88b)
Location: fs/proc/base.c:1835
Inline: True
Inline callers:
  - fs/proc/base.c:proc_map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:proc_map_files_lookup
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
In fs/proc/base.c (ffffffff812aaaf3)
Location: fs/proc/base.c:1856
Inline: True
Inline callers:
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
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
In fs/proc/base.c (ffffffff812c0403)
Location: fs/proc/base.c:1876
Inline: True
Inline callers:
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
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
In fs/proc/base.c (ffffffff812cd762)
Location: fs/proc/base.c:1917
Inline: True
Inline callers:
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
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
In fs/proc/base.c (ffffffff812f2002)
Location: fs/proc/base.c:1918
Inline: True
Inline callers:
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/base.c (ffffffff8131bd00)
Location: fs/proc/base.c:1895
Inline: True
Direct callers:
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
```
**Symbols:**

```
ffffffff8131bd00-ffffffff8131bdb7: dname_to_vma_addr.isra.22 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/base.c (ffffffff81332e90)
Location: fs/proc/base.c:1909
Inline: True
Direct callers:
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
```
**Symbols:**

```
ffffffff81332e90-ffffffff81332f47: dname_to_vma_addr.isra.22 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/base.c (ffffffff8135adf0)
Location: fs/proc/base.c:1922
Inline: True
Direct callers:
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
```
**Symbols:**

```
ffffffff8135adf0-ffffffff8135aea7: dname_to_vma_addr.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/base.c (ffffffff81373000)
Location: fs/proc/base.c:1922
Inline: True
Direct callers:
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
```
**Symbols:**

```
ffffffff81373000-ffffffff813730b7: dname_to_vma_addr.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/base.c (ffffffff813bb390)
Location: fs/proc/base.c:2055
Inline: True
Direct callers:
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
```
**Symbols:**

```
ffffffff813bb390-ffffffff813bb447: dname_to_vma_addr.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/base.c (ffffffff813ccf20)
Location: fs/proc/base.c:2069
Inline: True
Direct callers:
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
```
**Symbols:**

```
ffffffff813ccf20-ffffffff813ccfd7: dname_to_vma_addr.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/base.c (ffffffff813d3df0)
Location: fs/proc/base.c:2068
Inline: True
Direct callers:
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
```
**Symbols:**

```
ffffffff813d3df0-ffffffff813d3ea7: dname_to_vma_addr.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/base.c (ffffffff81425500)
Location: fs/proc/base.c:2074
Inline: True
Direct callers:
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
```
**Symbols:**

```
ffffffff81425500-ffffffff814255b7: dname_to_vma_addr.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/base.c (ffffffff8149e860)
Location: fs/proc/base.c:2103
Inline: True
Direct callers:
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
```
**Symbols:**

```
ffffffff8149e860-ffffffff8149e935: dname_to_vma_addr.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/base.c (ffffffff81533570)
Location: fs/proc/base.c:2104
Inline: True
Direct callers:
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
```
**Symbols:**

```
ffffffff81533570-ffffffff81533645: dname_to_vma_addr.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/base.c (ffffffff8156b760)
Location: fs/proc/base.c:2104
Inline: True
Direct callers:
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
```
**Symbols:**

```
ffffffff8156b760-ffffffff8156b835: dname_to_vma_addr.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/base.c (ffffffff815a4170)
Location: fs/proc/base.c:2098
Inline: True
Direct callers:
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
```
**Symbols:**

```
ffffffff815a4170-ffffffff815a4245: dname_to_vma_addr.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/base.c (ffff80001043d538)
Location: fs/proc/base.c:1922
Inline: True
Direct callers:
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
```
**Symbols:**

```
ffff80001043d538-ffff80001043d61c: dname_to_vma_addr.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dname_to_vma_addr(struct dentry *dentry, long unsigned int *start, long unsigned int *end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (c0603324)
Location: fs/proc/base.c:1922
Inline: False
Direct callers:
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
```
**Symbols:**

```
c0603324-c0603444: dname_to_vma_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dname_to_vma_addr(struct dentry *dentry, long unsigned int *start, long unsigned int *end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (c000000000551540)
Location: fs/proc/base.c:1922
Inline: False
Direct callers:
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
```
**Symbols:**

```
c000000000551540-c000000000551688: dname_to_vma_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int dname_to_vma_addr(struct dentry *dentry, long unsigned int *start, long unsigned int *end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffe0002d61a2)
Location: fs/proc/base.c:1922
Inline: False
Direct callers:
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
```
**Symbols:**

```
ffffffe0002d61a2-ffffffe0002d626e: dname_to_vma_addr (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/base.c (ffffffff8136b5e0)
Location: fs/proc/base.c:1922
Inline: True
Direct callers:
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
```
**Symbols:**

```
ffffffff8136b5e0-ffffffff8136b697: dname_to_vma_addr.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/base.c (ffffffff8135c070)
Location: fs/proc/base.c:1922
Inline: True
Direct callers:
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
```
**Symbols:**

```
ffffffff8135c070-ffffffff8135c127: dname_to_vma_addr.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/base.c (ffffffff813690b0)
Location: fs/proc/base.c:1922
Inline: True
Direct callers:
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
```
**Symbols:**

```
ffffffff813690b0-ffffffff81369167: dname_to_vma_addr.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/base.c (ffffffff8137c920)
Location: fs/proc/base.c:1922
Inline: True
Direct callers:
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
```
**Symbols:**

```
ffffffff8137c920-ffffffff8137c9d7: dname_to_vma_addr.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
