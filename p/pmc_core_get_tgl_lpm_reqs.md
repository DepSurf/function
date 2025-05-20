# Function: <code>pmc_core_get_tgl_lpm_reqs</code>

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
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void pmc_core_get_tgl_lpm_reqs(struct platform_device *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/x86/intel_pmc_core.c (ffffffff819a86c0)
Location: drivers/platform/x86/intel_pmc_core.c:601
Inline: False
Direct callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
```
**Symbols:**

```
ffffffff819a86c0-ffffffff819a8804: pmc_core_get_tgl_lpm_reqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void pmc_core_get_tgl_lpm_reqs(struct platform_device *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/x86/intel/pmc/core.c (ffffffff81a55af0)
Location: drivers/platform/x86/intel/pmc/core.c:601
Inline: False
Direct callers:
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_probe
```
**Symbols:**

```
ffffffff81a55af0-ffffffff81a55c2e: pmc_core_get_tgl_lpm_reqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void pmc_core_get_tgl_lpm_reqs(struct platform_device *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/x86/intel/pmc/core.c (ffffffff81bc5330)
Location: drivers/platform/x86/intel/pmc/core.c:601
Inline: False
Direct callers:
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_probe
```
**Symbols:**

```
ffffffff81bc5330-ffffffff81bc5490: pmc_core_get_tgl_lpm_reqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pmc_core_get_tgl_lpm_reqs(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/x86/intel/pmc/tgl.c (ffffffff81d6f220)
Location: drivers/platform/x86/intel/pmc/tgl.c:208
Inline: False
Direct callers:
  - drivers/platform/x86/intel/pmc/tgl.c:tgl_core_configure
```
**Symbols:**

```
ffffffff81d6f220-ffffffff81d6f397: pmc_core_get_tgl_lpm_reqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pmc_core_get_tgl_lpm_reqs(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/x86/intel/pmc/tgl.c (ffffffff81ddcdd0)
Location: drivers/platform/x86/intel/pmc/tgl.c:208
Inline: False
Direct callers:
  - drivers/platform/x86/intel/pmc/tgl.c:tgl_core_init
```
**Symbols:**

```
ffffffff81ddcdd0-ffffffff81ddcf71: pmc_core_get_tgl_lpm_reqs (STB_GLOBAL)
```
</details>
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
</ul>
