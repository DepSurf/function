# Function: <code>fdt_path_offset</code>

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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int fdt_path_offset(const void *fdt, const char *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_ro.c (ffff80001143e9b8)
Location: scripts/dtc/libfdt/fdt_ro.c:280
Inline: False
Direct callers:
  - arch/arm64/kernel/kaslr.c:kaslr_early_init
  - arch/arm64/kernel/kaslr.c:kaslr_early_init
  - drivers/firmware/efi/libstub/fdt.c:exit_boot_func
  - lib/fdt_ro.c:fdt_get_alias_namelen
  - lib/fdt_ro.c:fdt_path_offset_namelen
  - drivers/of/fdt.c:early_init_dt_scan_chosen_stdout
  - drivers/of/fdt.c:early_init_dt_scan_chosen_stdout
  - drivers/of/fdt.c:of_fdt_limit_memory
  - drivers/of/fdt.c:of_fdt_limit_memory
  - lib/fdt_ro.c:fdt_get_alias_namelen
  - lib/fdt_ro.c:fdt_path_offset_namelen
```
**Symbols:**

```
ffff800010d86390-ffff800010d863c8: fdt_path_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fdt_path_offset(const void *fdt, const char *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_ro.c (c0e81354)
Location: scripts/dtc/libfdt/fdt_ro.c:280
Inline: False
Direct callers:
  - drivers/of/fdt.c:early_init_dt_scan_chosen_stdout
  - drivers/of/fdt.c:early_init_dt_scan_chosen_stdout
  - drivers/of/fdt.c:of_fdt_limit_memory
  - drivers/of/fdt.c:of_fdt_limit_memory
  - lib/fdt_ro.c:fdt_get_alias_namelen
  - lib/fdt_ro.c:fdt_path_offset_namelen
```
**Symbols:**

```
c0e81354-c0e81384: fdt_path_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fdt_path_offset(const void *fdt, const char *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_ro.c (c000000000ec5bd0)
Location: scripts/dtc/libfdt/fdt_ro.c:280
Inline: False
Direct callers:
  - arch/powerpc/kernel/machine_kexec_file_64.c:setup_new_fdt
  - arch/powerpc/kernel/machine_kexec_file_64.c:setup_new_fdt
  - arch/powerpc/kernel/machine_kexec_file_64.c:setup_new_fdt
  - drivers/of/fdt.c:early_init_dt_scan_chosen_stdout
  - drivers/of/fdt.c:early_init_dt_scan_chosen_stdout
  - drivers/of/fdt.c:of_fdt_limit_memory
  - drivers/of/fdt.c:of_fdt_limit_memory
  - lib/fdt_ro.c:fdt_get_alias_namelen
  - lib/fdt_ro.c:fdt_path_offset_namelen
```
**Symbols:**

```
c000000000ec5bd0-c000000000ec5c20: fdt_path_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fdt_path_offset(const void *fdt, const char *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/fdt_ro.c (ffffffe0008b04a2)
Location: scripts/dtc/libfdt/fdt_ro.c:280
Inline: False
Direct callers:
  - drivers/of/fdt.c:early_init_dt_scan_chosen_stdout
  - drivers/of/fdt.c:early_init_dt_scan_chosen_stdout
  - drivers/of/fdt.c:of_fdt_limit_memory
  - drivers/of/fdt.c:of_fdt_limit_memory
  - lib/fdt_ro.c:fdt_get_alias_namelen
  - lib/fdt_ro.c:fdt_path_offset_namelen
```
**Symbols:**

```
ffffffe0008b04a2-ffffffe0008b04d8: fdt_path_offset (STB_GLOBAL)
```
</details>
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
<b>Arch</b>
<ul>
</ul>
