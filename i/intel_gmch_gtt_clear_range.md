# Function: <code>intel_gmch_gtt_clear_range</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void intel_gmch_gtt_clear_range(unsigned int first_entry, unsigned int num_entries);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/agp/intel-gtt.c (ffffffff81aa3881)
Location: drivers/char/agp/intel-gtt.c:949
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
```
**Symbols:**

```
ffffffff81aa2450-ffffffff81aa249e: intel_gmch_gtt_clear_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void intel_gmch_gtt_clear_range(unsigned int first_entry, unsigned int num_entries);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/agp/intel-gtt.c (ffffffff81aef161)
Location: drivers/char/agp/intel-gtt.c:949
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
```
**Symbols:**

```
ffffffff81aedd30-ffffffff81aedd7e: intel_gmch_gtt_clear_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void intel_gmch_gtt_clear_range(unsigned int first_entry, unsigned int num_entries);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/agp/intel-gtt.c (ffffffff81b426a1)
Location: drivers/char/agp/intel-gtt.c:949
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
```
**Symbols:**

```
ffffffff81b41270-ffffffff81b412be: intel_gmch_gtt_clear_range (STB_GLOBAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
