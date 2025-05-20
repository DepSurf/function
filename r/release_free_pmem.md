# Function: <code>release_free_pmem</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff816f5419)
Location: drivers/nvdimm/namespace_devs.c:752
Inline: True
Direct callers:
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:size_store
```
**Symbols:**

```
ffffffff816f5419-ffffffff816f5471: release_free_pmem.isra.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff815f1c60)
Location: drivers/nvdimm/namespace_devs.c:749
Inline: True
Direct callers:
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:size_store
```
**Symbols:**

```
ffffffff815f1c60-ffffffff815f1cbf: release_free_pmem.isra.10 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff8161fa70)
Location: drivers/nvdimm/namespace_devs.c:820
Inline: True
Direct callers:
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:size_store
```
**Symbols:**

```
ffffffff8161fa70-ffffffff8161facf: release_free_pmem.isra.13 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81634180)
Location: drivers/nvdimm/namespace_devs.c:839
Inline: True
Direct callers:
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:size_store
```
**Symbols:**

```
ffffffff81634180-ffffffff816341ed: release_free_pmem.isra.15 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff8169cb00)
Location: drivers/nvdimm/namespace_devs.c:839
Inline: True
Direct callers:
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:size_store
```
**Symbols:**

```
ffffffff8169cb00-ffffffff8169cb6d: release_free_pmem.isra.15 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void release_free_pmem(struct nvdimm_bus *nvdimm_bus, struct nd_mapping *nd_mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff816d9a50)
Location: drivers/nvdimm/namespace_devs.c:839
Inline: False
Direct callers:
  - drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:size_store
```
**Symbols:**

```
ffffffff816d9a50-ffffffff816d9ab9: release_free_pmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void release_free_pmem(struct nvdimm_bus *nvdimm_bus, struct nd_mapping *nd_mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff816fb9f0)
Location: drivers/nvdimm/namespace_devs.c:842
Inline: False
Direct callers:
  - drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:size_store
```
**Symbols:**

```
ffffffff816fb9f0-ffffffff816fba59: release_free_pmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void release_free_pmem(struct nvdimm_bus *nvdimm_bus, struct nd_mapping *nd_mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81735a60)
Location: drivers/nvdimm/namespace_devs.c:834
Inline: False
Direct callers:
  - drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
```
**Symbols:**

```
ffffffff81735a60-ffffffff81735aca: release_free_pmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void release_free_pmem(struct nvdimm_bus *nvdimm_bus, struct nd_mapping *nd_mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff817597e0)
Location: drivers/nvdimm/namespace_devs.c:834
Inline: False
Direct callers:
  - drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
```
**Symbols:**

```
ffffffff817597e0-ffffffff8175984a: release_free_pmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void release_free_pmem(struct nvdimm_bus *nvdimm_bus, struct nd_mapping *nd_mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81819570)
Location: drivers/nvdimm/namespace_devs.c:814
Inline: False
Direct callers:
  - drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa
  - drivers/nvdimm/namespace_devs.c:grow_dpa_allocation
  - drivers/nvdimm/namespace_devs.c:grow_dpa_allocation
```
**Symbols:**

```
ffffffff81819570-ffffffff818195d9: release_free_pmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void release_free_pmem(struct nvdimm_bus *nvdimm_bus, struct nd_mapping *nd_mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81828690)
Location: drivers/nvdimm/namespace_devs.c:814
Inline: False
Direct callers:
  - drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa
  - drivers/nvdimm/namespace_devs.c:grow_dpa_allocation
  - drivers/nvdimm/namespace_devs.c:grow_dpa_allocation
```
**Symbols:**

```
ffffffff81828690-ffffffff818286f9: release_free_pmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void release_free_pmem(struct nvdimm_bus *nvdimm_bus, struct nd_mapping *nd_mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff8180b8b0)
Location: drivers/nvdimm/namespace_devs.c:814
Inline: False
Direct callers:
  - drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa
  - drivers/nvdimm/namespace_devs.c:grow_dpa_allocation
  - drivers/nvdimm/namespace_devs.c:grow_dpa_allocation
```
**Symbols:**

```
ffffffff8180b8b0-ffffffff8180b911: release_free_pmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void release_free_pmem(struct nvdimm_bus *nvdimm_bus, struct nd_mapping *nd_mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81895ed0)
Location: drivers/nvdimm/namespace_devs.c:814
Inline: False
Direct callers:
  - drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa
  - drivers/nvdimm/namespace_devs.c:grow_dpa_allocation
  - drivers/nvdimm/namespace_devs.c:grow_dpa_allocation
```
**Symbols:**

```
ffffffff81895ed0-ffffffff81895f31: release_free_pmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void release_free_pmem(struct nvdimm_bus *nvdimm_bus, struct nd_mapping *nd_mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff819e0c10)
Location: drivers/nvdimm/namespace_devs.c:644
Inline: False
Direct callers:
  - drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa
```
**Symbols:**

```
ffffffff819e0c10-ffffffff819e0c7b: release_free_pmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void release_free_pmem(struct nvdimm_bus *nvdimm_bus, struct nd_mapping *nd_mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81b5c690)
Location: drivers/nvdimm/namespace_devs.c:641
Inline: False
Direct callers:
  - drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa
```
**Symbols:**

```
ffffffff81b5c690-ffffffff81b5c6fb: release_free_pmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void release_free_pmem(struct nvdimm_bus *nvdimm_bus, struct nd_mapping *nd_mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81bafc60)
Location: drivers/nvdimm/namespace_devs.c:641
Inline: False
Direct callers:
  - drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa
```
**Symbols:**

```
ffffffff81bafc60-ffffffff81bafccb: release_free_pmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void release_free_pmem(struct nvdimm_bus *nvdimm_bus, struct nd_mapping *nd_mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81c04090)
Location: drivers/nvdimm/namespace_devs.c:646
Inline: False
Direct callers:
  - drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa
```
**Symbols:**

```
ffffffff81c04090-ffffffff81c040fb: release_free_pmem (STB_GLOBAL)
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
void release_free_pmem(struct nvdimm_bus *nvdimm_bus, struct nd_mapping *nd_mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffff80001095afd0)
Location: drivers/nvdimm/namespace_devs.c:834
Inline: False
Direct callers:
  - drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
```
**Symbols:**

```
ffff80001095afd0-ffff80001095b05c: release_free_pmem (STB_GLOBAL)
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
void release_free_pmem(struct nvdimm_bus *nvdimm_bus, struct nd_mapping *nd_mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (c000000000a0b670)
Location: drivers/nvdimm/namespace_devs.c:834
Inline: False
Direct callers:
  - drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
```
**Symbols:**

```
c000000000a0b670-c000000000a0b8a8: release_free_pmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void release_free_pmem(struct nvdimm_bus *nvdimm_bus, struct nd_mapping *nd_mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffe0005c96b6)
Location: drivers/nvdimm/namespace_devs.c:834
Inline: False
Direct callers:
  - drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
```
**Symbols:**

```
ffffffe0005c96b6-ffffffe0005c9736: release_free_pmem (STB_GLOBAL)
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
void release_free_pmem(struct nvdimm_bus *nvdimm_bus, struct nd_mapping *nd_mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff8170ded0)
Location: drivers/nvdimm/namespace_devs.c:834
Inline: False
Direct callers:
  - drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
```
**Symbols:**

```
ffffffff8170ded0-ffffffff8170df3a: release_free_pmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void release_free_pmem(struct nvdimm_bus *nvdimm_bus, struct nd_mapping *nd_mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff816e1950)
Location: drivers/nvdimm/namespace_devs.c:834
Inline: False
Direct callers:
  - drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
```
**Symbols:**

```
ffffffff816e1950-ffffffff816e19ba: release_free_pmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void release_free_pmem(struct nvdimm_bus *nvdimm_bus, struct nd_mapping *nd_mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff8174cca0)
Location: drivers/nvdimm/namespace_devs.c:834
Inline: False
Direct callers:
  - drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
```
**Symbols:**

```
ffffffff8174cca0-ffffffff8174cd0a: release_free_pmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void release_free_pmem(struct nvdimm_bus *nvdimm_bus, struct nd_mapping *nd_mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81768120)
Location: drivers/nvdimm/namespace_devs.c:834
Inline: False
Direct callers:
  - drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
```
**Symbols:**

```
ffffffff81768120-ffffffff8176818a: release_free_pmem (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
