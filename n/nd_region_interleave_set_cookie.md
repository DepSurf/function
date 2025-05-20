# Function: <code>nd_region_interleave_set_cookie</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
u64 nd_region_interleave_set_cookie(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff8159ab50)
Location: drivers/nvdimm/region_devs.c:373
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
```
**Symbols:**

```
ffffffff8159ab50-ffffffff8159ab6e: nd_region_interleave_set_cookie (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
u64 nd_region_interleave_set_cookie(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff815f0b30)
Location: drivers/nvdimm/region_devs.c:485
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
```
**Symbols:**

```
ffffffff815f0b30-ffffffff815f0b4e: nd_region_interleave_set_cookie (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
u64 nd_region_interleave_set_cookie(struct nd_region *nd_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff8161daf0)
Location: drivers/nvdimm/region_devs.c:499
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
```
**Symbols:**

```
ffffffff8161daf0-ffffffff8161db0e: nd_region_interleave_set_cookie (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
u64 nd_region_interleave_set_cookie(struct nd_region *nd_region, struct nd_namespace_index *nsindex);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff8163127f)
Location: drivers/nvdimm/region_devs.c:599
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:set_cookie_show
Direct callers:
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
```
**Symbols:**

```
ffffffff81631f70-ffffffff81631fa0: nd_region_interleave_set_cookie (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
u64 nd_region_interleave_set_cookie(struct nd_region *nd_region, struct nd_namespace_index *nsindex);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81699aaf)
Location: drivers/nvdimm/region_devs.c:618
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:set_cookie_show
Direct callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
```
**Symbols:**

```
ffffffff8169a8d0-ffffffff8169a900: nd_region_interleave_set_cookie (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
u64 nd_region_interleave_set_cookie(struct nd_region *nd_region, struct nd_namespace_index *nsindex);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff816d5d4e)
Location: drivers/nvdimm/region_devs.c:657
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:set_cookie_show
Direct callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/label.c:__pmem_label_update
```
**Symbols:**

```
ffffffff816d6c90-ffffffff816d6cc2: nd_region_interleave_set_cookie (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
u64 nd_region_interleave_set_cookie(struct nd_region *nd_region, struct nd_namespace_index *nsindex);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff816f7a6e)
Location: drivers/nvdimm/region_devs.c:685
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:set_cookie_show
Direct callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/label.c:__pmem_label_update
```
**Symbols:**

```
ffffffff816f8ae0-ffffffff816f8b12: nd_region_interleave_set_cookie (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
u64 nd_region_interleave_set_cookie(struct nd_region *nd_region, struct nd_namespace_index *nsindex);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81731177)
Location: drivers/nvdimm/region_devs.c:683
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:set_cookie_show
Direct callers:
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/label.c:__pmem_label_update
```
**Symbols:**

```
ffffffff817321d0-ffffffff81732202: nd_region_interleave_set_cookie (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
u64 nd_region_interleave_set_cookie(struct nd_region *nd_region, struct nd_namespace_index *nsindex);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81755277)
Location: drivers/nvdimm/region_devs.c:683
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:set_cookie_show
Direct callers:
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/label.c:__pmem_label_update
```
**Symbols:**

```
ffffffff81756350-ffffffff81756382: nd_region_interleave_set_cookie (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
u64 nd_region_interleave_set_cookie(struct nd_region *nd_region, struct nd_namespace_index *nsindex);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81815354)
Location: drivers/nvdimm/region_devs.c:857
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:set_cookie_show
Direct callers:
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/label.c:__pmem_label_update
```
**Symbols:**

```
ffffffff81815930-ffffffff81815962: nd_region_interleave_set_cookie (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
u64 nd_region_interleave_set_cookie(struct nd_region *nd_region, struct nd_namespace_index *nsindex);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81824544)
Location: drivers/nvdimm/region_devs.c:857
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:set_cookie_show
Direct callers:
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/label.c:__pmem_label_update
```
**Symbols:**

```
ffffffff81824b20-ffffffff81824b52: nd_region_interleave_set_cookie (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
u64 nd_region_interleave_set_cookie(struct nd_region *nd_region, struct nd_namespace_index *nsindex);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81807774)
Location: drivers/nvdimm/region_devs.c:864
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:set_cookie_show
Direct callers:
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/label.c:__pmem_label_update
```
**Symbols:**

```
ffffffff81807eb0-ffffffff81807ee2: nd_region_interleave_set_cookie (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
u64 nd_region_interleave_set_cookie(struct nd_region *nd_region, struct nd_namespace_index *nsindex);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81891134)
Location: drivers/nvdimm/region_devs.c:864
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:set_cookie_show
Direct callers:
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/label.c:__pmem_label_update
```
**Symbols:**

```
ffffffff81892650-ffffffff81892682: nd_region_interleave_set_cookie (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
u64 nd_region_interleave_set_cookie(struct nd_region *nd_region, struct nd_namespace_index *nsindex);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff819da28f)
Location: drivers/nvdimm/region_devs.c:807
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:set_cookie_show
Direct callers:
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/label.c:__pmem_label_update
```
**Symbols:**

```
ffffffff819dc830-ffffffff819dc87a: nd_region_interleave_set_cookie (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
u64 nd_region_interleave_set_cookie(struct nd_region *nd_region, struct nd_namespace_index *nsindex);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81b5555f)
Location: drivers/nvdimm/region_devs.c:852
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:set_cookie_show
Direct callers:
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/label.c:__pmem_label_update
```
**Symbols:**

```
ffffffff81b57e80-ffffffff81b57eca: nd_region_interleave_set_cookie (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
u64 nd_region_interleave_set_cookie(struct nd_region *nd_region, struct nd_namespace_index *nsindex);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81ba8aaf)
Location: drivers/nvdimm/region_devs.c:852
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:set_cookie_show
Direct callers:
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/label.c:__pmem_label_update
```
**Symbols:**

```
ffffffff81bab3f0-ffffffff81bab43a: nd_region_interleave_set_cookie (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
u64 nd_region_interleave_set_cookie(struct nd_region *nd_region, struct nd_namespace_index *nsindex);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81bfcc4f)
Location: drivers/nvdimm/region_devs.c:853
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:set_cookie_show
Direct callers:
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/label.c:__pmem_label_update
```
**Symbols:**

```
ffffffff81bff730-ffffffff81bff77a: nd_region_interleave_set_cookie (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
u64 nd_region_interleave_set_cookie(struct nd_region *nd_region, struct nd_namespace_index *nsindex);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffff800010956398)
Location: drivers/nvdimm/region_devs.c:683
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:set_cookie_show
Direct callers:
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/label.c:__pmem_label_update
```
**Symbols:**

```
ffff800010957788-ffff8000109577f0: nd_region_interleave_set_cookie (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
u64 nd_region_interleave_set_cookie(struct nd_region *nd_region, struct nd_namespace_index *nsindex);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (c000000000a03f10)
Location: drivers/nvdimm/region_devs.c:683
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:set_cookie_show
Direct callers:
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/label.c:__pmem_label_update
```
**Symbols:**

```
c000000000a05870-c000000000a058c8: nd_region_interleave_set_cookie (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
u64 nd_region_interleave_set_cookie(struct nd_region *nd_region, struct nd_namespace_index *nsindex);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffe0005c5726)
Location: drivers/nvdimm/region_devs.c:683
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:set_cookie_show
Direct callers:
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/label.c:__pmem_label_update
```
**Symbols:**

```
ffffffe0005c6736-ffffffe0005c6792: nd_region_interleave_set_cookie (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
u64 nd_region_interleave_set_cookie(struct nd_region *nd_region, struct nd_namespace_index *nsindex);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81709967)
Location: drivers/nvdimm/region_devs.c:683
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:set_cookie_show
Direct callers:
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/label.c:__pmem_label_update
```
**Symbols:**

```
ffffffff8170aa40-ffffffff8170aa72: nd_region_interleave_set_cookie (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
u64 nd_region_interleave_set_cookie(struct nd_region *nd_region, struct nd_namespace_index *nsindex);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff816dd3e7)
Location: drivers/nvdimm/region_devs.c:683
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:set_cookie_show
Direct callers:
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/label.c:__pmem_label_update
```
**Symbols:**

```
ffffffff816de4c0-ffffffff816de4f2: nd_region_interleave_set_cookie (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
u64 nd_region_interleave_set_cookie(struct nd_region *nd_region, struct nd_namespace_index *nsindex);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81748737)
Location: drivers/nvdimm/region_devs.c:683
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:set_cookie_show
Direct callers:
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/label.c:__pmem_label_update
```
**Symbols:**

```
ffffffff81749810-ffffffff81749842: nd_region_interleave_set_cookie (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
u64 nd_region_interleave_set_cookie(struct nd_region *nd_region, struct nd_namespace_index *nsindex);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81763bb7)
Location: drivers/nvdimm/region_devs.c:683
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:set_cookie_show
Direct callers:
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/label.c:__pmem_label_update
```
**Symbols:**

```
ffffffff81764c90-ffffffff81764cc2: nd_region_interleave_set_cookie (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct nd_namespace_index *nsindex</code>
</li>
</ul>
</details>
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
