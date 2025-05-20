# Function: <code>warn_slowpath_fmt_taint</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void warn_slowpath_fmt_taint(const char *file, int line, unsigned int taint, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff81081020)
Location: kernel/panic.c:477
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_parse_one_andd
  - drivers/iommu/dmar.c:warn_invalid_dmar
  - drivers/iommu/dmar.c:dmar_parse_one_rhsa
  - drivers/iommu/intel-iommu.c:quirk_ioat_snb_local_iommu
```
**Symbols:**

```
ffffffff81081020-ffffffff8108108b: warn_slowpath_fmt_taint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void warn_slowpath_fmt_taint(const char *file, int line, unsigned int taint, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff81082f00)
Location: kernel/panic.c:538
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_parse_one_rhsa
  - drivers/iommu/dmar.c:dmar_parse_one_andd
  - drivers/iommu/intel-iommu.c:quirk_ioat_snb_local_iommu
```
**Symbols:**

```
ffffffff81082f00-ffffffff81082f6e: warn_slowpath_fmt_taint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void warn_slowpath_fmt_taint(const char *file, int line, unsigned int taint, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff81087990)
Location: kernel/panic.c:568
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_parse_one_rhsa
  - drivers/iommu/dmar.c:dmar_parse_one_andd
  - drivers/iommu/intel-iommu.c:quirk_ioat_snb_local_iommu
```
**Symbols:**

```
ffffffff81087990-ffffffff810879fe: warn_slowpath_fmt_taint (STB_GLOBAL)
```
</details>
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
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
</ul>
