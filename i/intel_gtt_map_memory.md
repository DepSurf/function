# Function: <code>intel_gtt_map_memory</code>

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
In drivers/char/agp/intel-gtt.c (ffffffff81522213)
Location: drivers/char/agp/intel-gtt.c:97
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
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
In drivers/char/agp/intel-gtt.c (ffffffff81575076)
Location: drivers/char/agp/intel-gtt.c:97
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
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
In drivers/char/agp/intel-gtt.c (ffffffff815a1685)
Location: drivers/char/agp/intel-gtt.c:97
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
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
In drivers/char/agp/intel-gtt.c (ffffffff815b5e14)
Location: drivers/char/agp/intel-gtt.c:98
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
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
In drivers/char/agp/intel-gtt.c (ffffffff8161c010)
Location: drivers/char/agp/intel-gtt.c:98
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
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
In drivers/char/agp/intel-gtt.c (ffffffff81655ca8)
Location: drivers/char/agp/intel-gtt.c:98
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
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
In drivers/char/agp/intel-gtt.c (ffffffff816748a8)
Location: drivers/char/agp/intel-gtt.c:98
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
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
In drivers/char/agp/intel-gtt.c (ffffffff816a9832)
Location: drivers/char/agp/intel-gtt.c:98
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
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
In drivers/char/agp/intel-gtt.c (ffffffff816cc572)
Location: drivers/char/agp/intel-gtt.c:98
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int intel_gtt_map_memory(struct page **pages, unsigned int num_entries, struct sg_table *st);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/agp/intel-gtt.c (ffffffff81780f30)
Location: drivers/char/agp/intel-gtt.c:98
Inline: False
Direct callers:
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
```
**Symbols:**

```
ffffffff81780f30-ffffffff8178102b: intel_gtt_map_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int intel_gtt_map_memory(struct page **pages, unsigned int num_entries, struct sg_table *st);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/agp/intel-gtt.c (ffffffff81798840)
Location: drivers/char/agp/intel-gtt.c:98
Inline: False
Direct callers:
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
```
**Symbols:**

```
ffffffff81798840-ffffffff81798909: intel_gtt_map_memory (STB_LOCAL)
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
In drivers/char/agp/intel-gtt.c (ffffffff8177c2dc)
Location: drivers/char/agp/intel-gtt.c:98
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
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
In drivers/char/agp/intel-gtt.c (ffffffff8180249a)
Location: drivers/char/agp/intel-gtt.c:98
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
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
In drivers/char/agp/intel-gtt.c (ffffffff81941c5b)
Location: drivers/char/agp/intel-gtt.c:99
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
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
In drivers/char/agp/intel-gtt.c (ffffffff81aa37cb)
Location: drivers/char/agp/intel-gtt.c:99
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
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
In drivers/char/agp/intel-gtt.c (ffffffff81aef0ab)
Location: drivers/char/agp/intel-gtt.c:99
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
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
In drivers/char/agp/intel-gtt.c (ffffffff81b425eb)
Location: drivers/char/agp/intel-gtt.c:99
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
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
In drivers/char/agp/intel-gtt.c (ffffffff81691fc2)
Location: drivers/char/agp/intel-gtt.c:98
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
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
In drivers/char/agp/intel-gtt.c (ffffffff8166f9b2)
Location: drivers/char/agp/intel-gtt.c:98
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
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
In drivers/char/agp/intel-gtt.c (ffffffff816c0232)
Location: drivers/char/agp/intel-gtt.c:98
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
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
In drivers/char/agp/intel-gtt.c (ffffffff816da802)
Location: drivers/char/agp/intel-gtt.c:98
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
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
