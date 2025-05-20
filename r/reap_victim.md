# Function: <code>reap_victim</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff8173949a)
Location: drivers/nvdimm/label.c:753
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__pmem_label_update
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
In drivers/nvdimm/label.c (ffffffff8175d1ea)
Location: drivers/nvdimm/label.c:748
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__pmem_label_update
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
In drivers/nvdimm/label.c (ffffffff8181cb0d)
Location: drivers/nvdimm/label.c:748
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__pmem_label_update
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void reap_victim(struct nd_mapping *nd_mapping, struct nd_label_ent *victim);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff8182b8a0)
Location: drivers/nvdimm/label.c:748
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
```
**Symbols:**

```
ffffffff8182b8a0-ffffffff8182b925: reap_victim (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void reap_victim(struct nd_mapping *nd_mapping, struct nd_label_ent *victim);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff8180ebc0)
Location: drivers/nvdimm/label.c:748
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
```
**Symbols:**

```
ffffffff8180ebc0-ffffffff8180ec46: reap_victim (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void reap_victim(struct nd_mapping *nd_mapping, struct nd_label_ent *victim);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff81899190)
Location: drivers/nvdimm/label.c:764
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
```
**Symbols:**

```
ffffffff81899190-ffffffff81899213: reap_victim (STB_LOCAL)
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
In drivers/nvdimm/label.c (ffffffff819e35e5)
Location: drivers/nvdimm/label.c:808
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__pmem_label_update
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
In drivers/nvdimm/label.c (ffffffff81b5f23f)
Location: drivers/nvdimm/label.c:808
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__pmem_label_update
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
In drivers/nvdimm/label.c (ffffffff81bb27b8)
Location: drivers/nvdimm/label.c:808
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__pmem_label_update
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
In drivers/nvdimm/label.c (ffffffff81c06ca8)
Location: drivers/nvdimm/label.c:808
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__pmem_label_update
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
In drivers/nvdimm/label.c (ffff80001095e940)
Location: drivers/nvdimm/label.c:748
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__pmem_label_update
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
In drivers/nvdimm/label.c (c000000000a10ba4)
Location: drivers/nvdimm/label.c:748
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__pmem_label_update
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
In drivers/nvdimm/label.c (ffffffe0005cc828)
Location: drivers/nvdimm/label.c:748
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__pmem_label_update
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
In drivers/nvdimm/label.c (ffffffff817118da)
Location: drivers/nvdimm/label.c:748
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__pmem_label_update
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
In drivers/nvdimm/label.c (ffffffff816e535a)
Location: drivers/nvdimm/label.c:748
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__pmem_label_update
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
In drivers/nvdimm/label.c (ffffffff817506aa)
Location: drivers/nvdimm/label.c:748
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__pmem_label_update
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
In drivers/nvdimm/label.c (ffffffff8176bb2a)
Location: drivers/nvdimm/label.c:748
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__pmem_label_update
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
</ul>
