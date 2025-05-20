# Function: <code>skx_iio_get_topology</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int skx_iio_get_topology(struct intel_uncore_type *type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101f860)
Location: arch/x86/events/intel/uncore_snbep.c:3706
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_snbep.c:skx_iio_set_mapping
```
**Symbols:**

```
ffffffff8101f860-ffffffff8101f9e2: skx_iio_get_topology (STB_LOCAL)
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
In arch/x86/events/intel/uncore_snbep.c (ffffffff810207e8)
Location: arch/x86/events/intel/uncore_snbep.c:3736
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:skx_iio_set_mapping
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int skx_iio_get_topology(struct intel_uncore_type *type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snbep.c (ffffffff81023f40)
Location: arch/x86/events/intel/uncore_snbep.c:3767
Inline: True
```
**Symbols:**

```
ffffffff81023f40-ffffffff81024108: skx_iio_get_topology (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int skx_iio_get_topology(struct intel_uncore_type *type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snbep.c (ffffffff81027ef0)
Location: arch/x86/events/intel/uncore_snbep.c:3767
Inline: True
```
**Symbols:**

```
ffffffff81027ef0-ffffffff810280c2: skx_iio_get_topology (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int skx_iio_get_topology(struct intel_uncore_type *type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8102dc90)
Location: arch/x86/events/intel/uncore_snbep.c:3899
Inline: False
```
**Symbols:**

```
ffffffff8102dc90-ffffffff8102dcaf: skx_iio_get_topology (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int skx_iio_get_topology(struct intel_uncore_type *type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8102ca30)
Location: arch/x86/events/intel/uncore_snbep.c:3889
Inline: False
```
**Symbols:**

```
ffffffff8102ca30-ffffffff8102ca4f: skx_iio_get_topology (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int skx_iio_get_topology(struct intel_uncore_type *type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snbep.c (ffffffff81032b90)
Location: arch/x86/events/intel/uncore_snbep.c:3897
Inline: False
```
**Symbols:**

```
ffffffff81032b90-ffffffff81032baf: skx_iio_get_topology (STB_LOCAL)
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
