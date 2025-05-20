# Function: <code>strchrnul</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
char *strchrnul(const char *s, int c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff813f19f0)
Location: lib/string.c:388
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - security/integrity/ima/ima_template.c:template_desc_init_fields
  - lib/bitmap.c:bitmap_parselist
```
**Symbols:**

```
ffffffff813f19f0-ffffffff813f1a18: strchrnul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
char *strchrnul(const char *s, int c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff814383b0)
Location: lib/string.c:388
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - security/integrity/ima/ima_template.c:template_desc_init_fields
  - lib/bitmap.c:bitmap_parselist
```
**Symbols:**

```
ffffffff814383b0-ffffffff814383d8: strchrnul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
char *strchrnul(const char *s, int c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff814553a0)
Location: lib/string.c:388
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - lib/bitmap.c:bitmap_parselist
```
**Symbols:**

```
ffffffff814553a0-ffffffff814553c8: strchrnul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
char *strchrnul(const char *s, int c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff818f6e60)
Location: lib/string.c:388
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - lib/bitmap.c:bitmap_parselist
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_create
```
**Symbols:**

```
ffffffff818f6e60-ffffffff818f6e88: strchrnul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
char *strchrnul(const char *s, int c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff8197d860)
Location: lib/string.c:389
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - lib/bitmap.c:bitmap_parselist
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_create
```
**Symbols:**

```
ffffffff8197d860-ffffffff8197d888: strchrnul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
char *strchrnul(const char *s, int c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff819d9d60)
Location: lib/string.c:389
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - lib/bitmap.c:bitmap_parselist
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_create
```
**Symbols:**

```
ffffffff819d9d60-ffffffff819d9d83: strchrnul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
char *strchrnul(const char *s, int c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81a11f80)
Location: lib/string.c:390
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - lib/bitmap.c:bitmap_parselist
  - drivers/pci/pci.c:pci_dev_str_match
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_create
```
**Symbols:**

```
ffffffff81a11f80-ffffffff81a11fa3: strchrnul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
char *strchrnul(const char *s, int c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81a81450)
Location: lib/string.c:426
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - mm/slub.c:kmem_cache_flags
  - drivers/pci/pci.c:pci_dev_str_match
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_create
```
**Symbols:**

```
ffffffff81a81450-ffffffff81a8146e: strchrnul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
char *strchrnul(const char *s, int c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81ab8520)
Location: lib/string.c:428
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - mm/slub.c:kmem_cache_flags
  - drivers/pci/pci.c:pci_dev_str_match
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_create
```
**Symbols:**

```
ffffffff81ab8520-ffffffff81ab853e: strchrnul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
char *strchrnul(const char *s, int c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff815f3160)
Location: lib/string.c:452
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - mm/slub.c:kmem_cache_flags
  - drivers/pci/pci.c:pci_dev_str_match_path
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_create
```
**Symbols:**

```
ffffffff815f3160-ffffffff815f317e: strchrnul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
char *strchrnul(const char *s, int c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81617810)
Location: lib/string.c:449
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - mm/slub.c:kmem_cache_flags
  - security/tomoyo/util.c:tomoyo_get_domainname
  - drivers/pci/pci.c:pci_dev_str_match_path
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_create
```
**Symbols:**

```
ffffffff81617810-ffffffff8161782e: strchrnul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
char *strchrnul(const char *s, int c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff815fae90)
Location: lib/string.c:449
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - mm/slub.c:kmem_cache_flags
  - security/tomoyo/util.c:tomoyo_get_domainname
  - drivers/pci/pci.c:pci_dev_str_match_path
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_create
```
**Symbols:**

```
ffffffff815fae90-ffffffff815faeae: strchrnul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
char *strchrnul(const char *s, int c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81668740)
Location: lib/string.c:450
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - mm/slub.c:kmem_cache_flags
  - security/tomoyo/util.c:tomoyo_get_domainname
  - drivers/pci/pci.c:pci_dev_str_match_path
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_create
```
**Symbols:**

```
ffffffff81668740-ffffffff8166875e: strchrnul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
char *strchrnul(const char *s, int c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81781d90)
Location: lib/string.c:411
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - mm/slub.c:kmem_cache_flags
  - security/tomoyo/util.c:tomoyo_get_domainname
  - security/integrity/ima/ima_template.c:template_desc_init_fields
  - drivers/pci/pci.c:pci_dev_str_match_path
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_create
```
**Symbols:**

```
ffffffff81781d90-ffffffff81781db8: strchrnul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
char *strchrnul(const char *s, int c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff8203eb30)
Location: lib/string.c:346
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - mm/slub.c:kmem_cache_flags
  - security/tomoyo/util.c:tomoyo_get_domainname
  - security/integrity/ima/ima_template.c:template_desc_init_fields
  - drivers/pci/pci.c:pci_dev_str_match_path
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_create
```
**Symbols:**

```
ffffffff8203eb30-ffffffff8203eb58: strchrnul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
char *strchrnul(const char *s, int c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff820bd030)
Location: lib/string.c:346
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - mm/slub.c:kmem_cache_flags
  - security/tomoyo/util.c:tomoyo_get_domainname
  - security/integrity/ima/ima_template.c:template_desc_init_fields
  - drivers/pci/pci.c:pci_dev_str_match_path
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_create
```
**Symbols:**

```
ffffffff820bd030-ffffffff820bd061: strchrnul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
char *strchrnul(const char *s, int c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff82197930)
Location: lib/string.c:331
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - mm/slub.c:kmem_cache_flags
  - security/tomoyo/util.c:tomoyo_get_domainname
  - security/integrity/ima/ima_template.c:template_desc_init_fields
  - drivers/pci/pci.c:pci_dev_str_match_path
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_create
  - drivers/base/property.c:fwnode_name_eq
```
**Symbols:**

```
ffffffff82197930-ffffffff82197961: strchrnul (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
char *strchrnul(const char *s, int c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffff800010d929a8)
Location: lib/string.c:428
Inline: False
Direct callers:
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - mm/slub.c:kmem_cache_flags
  - drivers/pci/pci.c:pci_dev_str_match
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_create
  - drivers/of/base.c:of_find_node_opts_by_path
  - drivers/of/base.c:__of_find_node_by_full_path
  - drivers/of/base.c:of_node_name_eq
  - drivers/of/fdt.c:early_init_dt_scan_chosen_stdout
  - lib/vsprintf.c:device_node_string
```
**Symbols:**

```
ffff800010d929a8-ffff800010d929cc: strchrnul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
char *strchrnul(const char *s, int c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (c0e8f0d4)
Location: lib/string.c:428
Inline: False
Direct callers:
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - mm/slub.c:kmem_cache_flags
  - drivers/pci/pci.c:pci_dev_str_match
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_create
  - drivers/of/base.c:of_find_node_opts_by_path
  - drivers/of/base.c:__of_find_node_by_full_path
  - drivers/of/base.c:of_node_name_eq
  - drivers/of/fdt.c:early_init_dt_scan_chosen_stdout
  - lib/vsprintf.c:device_node_string
```
**Symbols:**

```
c0e8f0d4-c0e8f110: strchrnul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
char *strchrnul(const char *s, int c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (c000000000ed6880)
Location: lib/string.c:428
Inline: False
Direct callers:
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - mm/slub.c:kmem_cache_flags
  - drivers/pci/pci.c:pci_dev_str_match
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_create
  - drivers/of/base.c:of_find_node_opts_by_path
  - drivers/of/base.c:__of_find_node_by_full_path
  - drivers/of/base.c:of_node_name_eq
  - drivers/of/fdt.c:early_init_dt_scan_chosen_stdout
  - lib/vsprintf.c:device_node_string
```
**Symbols:**

```
c000000000ed6880-c000000000ed68b8: strchrnul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
char *strchrnul(const char *s, int c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffe0008bca6e)
Location: lib/string.c:428
Inline: False
Direct callers:
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:wq_cpumask_store
  - mm/slub.c:kmem_cache_flags
  - security/integrity/ima/ima_template.c:template_desc_init_fields
  - drivers/pci/pci.c:pci_dev_str_match
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_create
  - drivers/of/base.c:of_find_node_opts_by_path
  - drivers/of/base.c:__of_find_node_by_full_path
  - drivers/of/base.c:of_node_name_eq
  - drivers/of/fdt.c:early_init_dt_scan_chosen_stdout
  - lib/vsprintf.c:device_node_string
```
**Symbols:**

```
ffffffe0008bca6e-ffffffe0008bca90: strchrnul (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
char *strchrnul(const char *s, int c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81a57370)
Location: lib/string.c:428
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - mm/slub.c:kmem_cache_flags
  - drivers/pci/pci.c:pci_dev_str_match
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_create
```
**Symbols:**

```
ffffffff81a57370-ffffffff81a5738e: strchrnul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
char *strchrnul(const char *s, int c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81a14450)
Location: lib/string.c:428
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - mm/slub.c:kmem_cache_flags
  - drivers/pci/pci.c:pci_dev_str_match
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_create
```
**Symbols:**

```
ffffffff81a14450-ffffffff81a1446e: strchrnul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
char *strchrnul(const char *s, int c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81ac3760)
Location: lib/string.c:428
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - mm/slub.c:kmem_cache_flags
  - drivers/pci/pci.c:pci_dev_str_match
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_create
```
**Symbols:**

```
ffffffff81ac3760-ffffffff81ac377e: strchrnul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
char *strchrnul(const char *s, int c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81acfc30)
Location: lib/string.c:428
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - mm/slub.c:kmem_cache_flags
  - drivers/pci/pci.c:pci_dev_str_match
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_create
```
**Symbols:**

```
ffffffff81acfc30-ffffffff81acfc4e: strchrnul (STB_GLOBAL)
```
</details>
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
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
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
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
