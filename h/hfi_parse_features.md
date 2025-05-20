# Function: <code>hfi_parse_features</code>

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
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/thermal/intel/intel_hfi.c (0)
Location: drivers/thermal/intel/intel_hfi.c:481
Inline: True
Inline callers:
  - drivers/thermal/intel/intel_hfi.c:intel_hfi_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int hfi_parse_features();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/intel/intel_hfi.c (ffffffff83efeba0)
Location: drivers/thermal/intel/intel_hfi.c:489
Inline: False
Direct callers:
  - drivers/thermal/intel/intel_hfi.c:intel_hfi_init
```
**Symbols:**

```
ffffffff83efeba0-ffffffff83efec86: hfi_parse_features (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int hfi_parse_features();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/intel/intel_hfi.c (ffffffff83724a10)
Location: drivers/thermal/intel/intel_hfi.c:490
Inline: False
Direct callers:
  - drivers/thermal/intel/intel_hfi.c:intel_hfi_init
```
**Symbols:**

```
ffffffff83724a10-ffffffff83724af6: hfi_parse_features (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int hfi_parse_features();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/intel/intel_hfi.c (ffffffff83958880)
Location: drivers/thermal/intel/intel_hfi.c:531
Inline: False
Direct callers:
  - drivers/thermal/intel/intel_hfi.c:intel_hfi_init
```
**Symbols:**

```
ffffffff83958880-ffffffff83958966: hfi_parse_features (STB_LOCAL)
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
