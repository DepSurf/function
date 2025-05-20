# Function: <code>nd_detach_and_reset</code>

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
In drivers/nvdimm/claim.c (ffffffff815a0d2b)
Location: drivers/nvdimm/claim.c:93
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:nd_namespace_store
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
In drivers/nvdimm/claim.c (ffffffff815f70d3)
Location: drivers/nvdimm/claim.c:115
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:nd_namespace_store
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
In drivers/nvdimm/claim.c (ffffffff81625343)
Location: drivers/nvdimm/claim.c:113
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:nd_namespace_store
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
In drivers/nvdimm/claim.c (ffffffff8163a369)
Location: drivers/nvdimm/claim.c:120
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:nd_namespace_store
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
In drivers/nvdimm/claim.c (ffffffff816a2f69)
Location: drivers/nvdimm/claim.c:120
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:nd_namespace_store
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
In drivers/nvdimm/claim.c (ffffffff816df0de)
Location: drivers/nvdimm/claim.c:120
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:nd_namespace_store
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
In drivers/nvdimm/claim.c (ffffffff817014bf)
Location: drivers/nvdimm/claim.c:120
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:nd_namespace_store
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
In drivers/nvdimm/claim.c (ffffffff8173b33c)
Location: drivers/nvdimm/claim.c:112
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:nd_namespace_store
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
In drivers/nvdimm/claim.c (ffffffff8175f00c)
Location: drivers/nvdimm/claim.c:112
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:nd_namespace_store
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void nd_detach_and_reset(struct device *dev, struct nd_namespace_common **_ndns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/claim.c (ffffffff8181e950)
Location: drivers/nvdimm/claim.c:112
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nd_namespace_store
```
**Symbols:**

```
ffffffff8181e950-ffffffff8181ea74: nd_detach_and_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void nd_detach_and_reset(struct device *dev, struct nd_namespace_common **_ndns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/claim.c (ffffffff8182d890)
Location: drivers/nvdimm/claim.c:113
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nd_namespace_store
```
**Symbols:**

```
ffffffff8182d890-ffffffff8182d9b4: nd_detach_and_reset (STB_LOCAL)
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
In drivers/nvdimm/claim.c (ffffffff81810c2a)
Location: drivers/nvdimm/claim.c:113
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:nd_namespace_store
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
In drivers/nvdimm/claim.c (ffffffff8189b28a)
Location: drivers/nvdimm/claim.c:113
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:nd_namespace_store
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
In drivers/nvdimm/claim.c (ffffffff819e4a17)
Location: drivers/nvdimm/claim.c:113
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:nd_namespace_store
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
In drivers/nvdimm/claim.c (ffffffff81b607b7)
Location: drivers/nvdimm/claim.c:113
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:nd_namespace_store
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
In drivers/nvdimm/claim.c (ffffffff81bb3d47)
Location: drivers/nvdimm/claim.c:113
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:nd_namespace_store
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
In drivers/nvdimm/claim.c (ffffffff81c08297)
Location: drivers/nvdimm/claim.c:113
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:nd_namespace_store
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
In drivers/nvdimm/claim.c (ffff800010960810)
Location: drivers/nvdimm/claim.c:112
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:nd_namespace_store
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
In drivers/nvdimm/claim.c (c000000000a139b8)
Location: drivers/nvdimm/claim.c:112
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:nd_namespace_store
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
In drivers/nvdimm/claim.c (ffffffe0005ce24e)
Location: drivers/nvdimm/claim.c:112
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:nd_namespace_store
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
In drivers/nvdimm/claim.c (ffffffff817136fc)
Location: drivers/nvdimm/claim.c:112
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:nd_namespace_store
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
In drivers/nvdimm/claim.c (ffffffff816e717c)
Location: drivers/nvdimm/claim.c:112
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:nd_namespace_store
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
In drivers/nvdimm/claim.c (ffffffff817524cc)
Location: drivers/nvdimm/claim.c:112
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:nd_namespace_store
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
In drivers/nvdimm/claim.c (ffffffff8176d93c)
Location: drivers/nvdimm/claim.c:112
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:nd_namespace_store
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
