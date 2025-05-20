# Function: <code>cper_mem_err_status_str</code>

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
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
const char *cper_mem_err_status_str(u64 status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/cper.c (ffffffff81efbdc8)
Location: drivers/firmware/efi/cper.c:214
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_print_mem
Direct callers:
  - drivers/edac/ghes_edac.c:ghes_edac_report_mem_error
```
**Symbols:**

```
ffffffff81bc0c70-ffffffff81bc0ca0: cper_mem_err_status_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
const char *cper_mem_err_status_str(u64 status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/cper.c (ffffffff81d64f46)
Location: drivers/firmware/efi/cper.c:215
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_print_mem
Direct callers:
  - drivers/edac/ghes_edac.c:ghes_edac_report_mem_error
```
**Symbols:**

```
ffffffff81d64490-ffffffff81d644c0: cper_mem_err_status_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
const char *cper_mem_err_status_str(u64 status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/cper.c (ffffffff81dd0076)
Location: drivers/firmware/efi/cper.c:215
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_print_mem
Direct callers:
  - drivers/edac/ghes_edac.c:ghes_edac_report_mem_error
```
**Symbols:**

```
ffffffff81dcf5c0-ffffffff81dcf5f0: cper_mem_err_status_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
const char *cper_mem_err_status_str(u64 status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/cper.c (ffffffff81e88da6)
Location: drivers/firmware/efi/cper.c:215
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_print_mem
Direct callers:
  - drivers/edac/ghes_edac.c:ghes_edac_report_mem_error
```
**Symbols:**

```
ffffffff81e882f0-ffffffff81e88320: cper_mem_err_status_str (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
