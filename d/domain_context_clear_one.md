# Function: <code>domain_context_clear_one</code>

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
In drivers/iommu/intel-iommu.c (ffffffff8153851e)
Location: drivers/iommu/intel-iommu.c:2257
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:domain_context_clear_one_cb
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
In drivers/iommu/intel-iommu.c (ffffffff8158ceee)
Location: drivers/iommu/intel-iommu.c:2301
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:domain_context_clear_one_cb
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
In drivers/iommu/intel-iommu.c (ffffffff815ba56e)
Location: drivers/iommu/intel-iommu.c:2344
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:domain_context_clear_one_cb
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
In drivers/iommu/intel-iommu.c (ffffffff815d04c5)
Location: drivers/iommu/intel-iommu.c:2352
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:domain_context_clear_one_cb
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
In drivers/iommu/intel-iommu.c (ffffffff81637255)
Location: drivers/iommu/intel-iommu.c:2356
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:domain_context_clear_one_cb
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
In drivers/iommu/intel-iommu.c (ffffffff81672ce5)
Location: drivers/iommu/intel-iommu.c:2413
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:domain_context_clear_one_cb
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
In drivers/iommu/intel-iommu.c (ffffffff81691205)
Location: drivers/iommu/intel-iommu.c:2382
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:domain_context_clear_one_cb
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
In drivers/iommu/intel-iommu.c (ffffffff816c91b5)
Location: drivers/iommu/intel-iommu.c:2361
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:domain_context_clear_one_cb
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
In drivers/iommu/intel-iommu.c (ffffffff816ec185)
Location: drivers/iommu/intel-iommu.c:2372
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:domain_context_clear_one_cb
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817a4405)
Location: drivers/iommu/intel/iommu.c:2391
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:domain_context_clear_one_cb
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817b0db5)
Location: drivers/iommu/intel/iommu.c:2419
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:domain_context_clear_one_cb
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void domain_context_clear_one(struct device_domain_info *info, u8 bus, u8 devfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81793840)
Location: drivers/iommu/intel/iommu.c:2437
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:domain_context_clear_one_cb
```
**Symbols:**

```
ffffffff81793840-ffffffff81793a0a: domain_context_clear_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void domain_context_clear_one(struct device_domain_info *info, u8 bus, u8 devfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff8181b6a0)
Location: drivers/iommu/intel/iommu.c:2427
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:domain_context_clear_one_cb
```
**Symbols:**

```
ffffffff8181b6a0-ffffffff8181b8a7: domain_context_clear_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void domain_context_clear_one(struct device_domain_info *info, u8 bus, u8 devfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff8195c440)
Location: drivers/iommu/intel/iommu.c:2320
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:domain_context_clear_one_cb
```
**Symbols:**

```
ffffffff8195c440-ffffffff8195c629: domain_context_clear_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void domain_context_clear_one(struct device_domain_info *info, u8 bus, u8 devfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81ac3fb0)
Location: drivers/iommu/intel/iommu.c:2280
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:domain_context_clear_one_cb
```
**Symbols:**

```
ffffffff81ac3fb0-ffffffff81ac41ac: domain_context_clear_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void domain_context_clear_one(struct device_domain_info *info, u8 bus, u8 devfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81b10960)
Location: drivers/iommu/intel/iommu.c:2246
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:domain_context_clear_one_cb
```
**Symbols:**

```
ffffffff81b10960-ffffffff81b10b64: domain_context_clear_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void domain_context_clear_one(struct device_domain_info *info, u8 bus, u8 devfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81b65430)
Location: drivers/iommu/intel/iommu.c:2167
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_release_device
  - drivers/iommu/intel/iommu.c:device_block_translation
  - drivers/iommu/intel/iommu.c:domain_context_clear_one_cb
```
**Symbols:**

```
ffffffff81b65430-ffffffff81b65637: domain_context_clear_one (STB_LOCAL)
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816b1ab5)
Location: drivers/iommu/intel-iommu.c:2372
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:domain_context_clear_one_cb
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
In drivers/iommu/intel-iommu.c (ffffffff8168f5b5)
Location: drivers/iommu/intel-iommu.c:2372
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:domain_context_clear_one_cb
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
In drivers/iommu/intel-iommu.c (ffffffff816dfe45)
Location: drivers/iommu/intel-iommu.c:2372
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:domain_context_clear_one_cb
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
In drivers/iommu/intel-iommu.c (ffffffff816fa455)
Location: drivers/iommu/intel-iommu.c:2372
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:domain_context_clear_one_cb
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
