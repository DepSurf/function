# Function: <code>init_dpa_allocation</code>

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
In drivers/nvdimm/namespace_devs.c (ffffffff8159c13a)
Location: drivers/nvdimm/namespace_devs.c:491
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_allocate
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
In drivers/nvdimm/namespace_devs.c (ffffffff815f1e5e)
Location: drivers/nvdimm/namespace_devs.c:488
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_allocate
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
In drivers/nvdimm/namespace_devs.c (ffffffff8161f8f2)
Location: drivers/nvdimm/namespace_devs.c:507
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_allocate
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
In drivers/nvdimm/namespace_devs.c (ffffffff8163409c)
Location: drivers/nvdimm/namespace_devs.c:526
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_allocate
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
In drivers/nvdimm/namespace_devs.c (ffffffff8169ca1c)
Location: drivers/nvdimm/namespace_devs.c:526
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_allocate
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
In drivers/nvdimm/namespace_devs.c (ffffffff816d8949)
Location: drivers/nvdimm/namespace_devs.c:526
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_allocate
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
In drivers/nvdimm/namespace_devs.c (ffffffff816fabf7)
Location: drivers/nvdimm/namespace_devs.c:529
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_allocate
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
In drivers/nvdimm/namespace_devs.c (ffffffff81734873)
Location: drivers/nvdimm/namespace_devs.c:521
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_allocate
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
In drivers/nvdimm/namespace_devs.c (ffffffff817585c3)
Location: drivers/nvdimm/namespace_devs.c:521
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_allocate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
resource_size_t init_dpa_allocation(struct nd_label_id *label_id, struct nd_region *nd_region, struct nd_mapping *nd_mapping, resource_size_t n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81817280)
Location: drivers/nvdimm/namespace_devs.c:496
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:scan_allocate
```
**Symbols:**

```
ffffffff81817280-ffffffff81817383: init_dpa_allocation (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
resource_size_t init_dpa_allocation(struct nd_label_id *label_id, struct nd_region *nd_region, struct nd_mapping *nd_mapping, resource_size_t n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff818263b0)
Location: drivers/nvdimm/namespace_devs.c:496
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:scan_allocate
```
**Symbols:**

```
ffffffff818263b0-ffffffff818264b3: init_dpa_allocation (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff8180a0d0)
Location: drivers/nvdimm/namespace_devs.c:496
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_allocate
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
In drivers/nvdimm/namespace_devs.c (ffffffff81894a00)
Location: drivers/nvdimm/namespace_devs.c:496
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_allocate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff819de8f4)
Location: drivers/nvdimm/namespace_devs.c:360
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_allocate
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81b5a214)
Location: drivers/nvdimm/namespace_devs.c:357
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_allocate
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81bad7f9)
Location: drivers/nvdimm/namespace_devs.c:357
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_allocate
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81c01b39)
Location: drivers/nvdimm/namespace_devs.c:362
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_allocate
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
In drivers/nvdimm/namespace_devs.c (ffff800010959c5c)
Location: drivers/nvdimm/namespace_devs.c:521
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_allocate
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
In drivers/nvdimm/namespace_devs.c (c000000000a09b10)
Location: drivers/nvdimm/namespace_devs.c:521
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_allocate
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
In drivers/nvdimm/namespace_devs.c (ffffffe0005c8a5c)
Location: drivers/nvdimm/namespace_devs.c:521
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_allocate
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
In drivers/nvdimm/namespace_devs.c (ffffffff8170ccb3)
Location: drivers/nvdimm/namespace_devs.c:521
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_allocate
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
In drivers/nvdimm/namespace_devs.c (ffffffff816e0733)
Location: drivers/nvdimm/namespace_devs.c:521
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_allocate
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
In drivers/nvdimm/namespace_devs.c (ffffffff8174ba83)
Location: drivers/nvdimm/namespace_devs.c:521
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_allocate
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
In drivers/nvdimm/namespace_devs.c (ffffffff81766f03)
Location: drivers/nvdimm/namespace_devs.c:521
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_allocate
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
</ul>
