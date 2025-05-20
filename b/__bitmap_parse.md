# Function: <code>__bitmap_parse</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __bitmap_parse(const char *buf, unsigned int buflen, int is_user, long unsigned int *maskp, int nmaskbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff813f9730)
Location: lib/bitmap.c:358
Inline: False
Direct callers:
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/padata.c:store_cpumask
  - lib/bitmap.c:bitmap_parse_user
  - net/core/net-sysfs.c:store_xps_map
  - net/core/net-sysfs.c:store_rps_map
```
**Symbols:**

```
ffffffff813f9730-ffffffff813f9919: __bitmap_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __bitmap_parse(const char *buf, unsigned int buflen, int is_user, long unsigned int *maskp, int nmaskbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81440750)
Location: lib/bitmap.c:360
Inline: False
Direct callers:
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/padata.c:store_cpumask
  - lib/bitmap.c:bitmap_parse_user
  - net/core/net-sysfs.c:store_xps_map
  - net/core/net-sysfs.c:store_rps_map
```
**Symbols:**

```
ffffffff81440750-ffffffff81440939: __bitmap_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __bitmap_parse(const char *buf, unsigned int buflen, int is_user, long unsigned int *maskp, int nmaskbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff8145d850)
Location: lib/bitmap.c:360
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/padata.c:store_cpumask
  - lib/bitmap.c:bitmap_parse_user
  - net/core/net-sysfs.c:store_xps_map
  - net/core/net-sysfs.c:store_rps_map
```
**Symbols:**

```
ffffffff8145d850-ffffffff8145da39: __bitmap_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __bitmap_parse(const char *buf, unsigned int buflen, int is_user, long unsigned int *maskp, int nmaskbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81462ed0)
Location: lib/bitmap.c:360
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/padata.c:store_cpumask
  - lib/bitmap.c:bitmap_parse_user
  - net/core/net-sysfs.c:store_xps_map
  - net/core/net-sysfs.c:store_rps_map
```
**Symbols:**

```
ffffffff81462ed0-ffffffff814630a3: __bitmap_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __bitmap_parse(const char *buf, unsigned int buflen, int is_user, long unsigned int *maskp, int nmaskbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff8148ede0)
Location: lib/bitmap.c:362
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/padata.c:store_cpumask
  - lib/bitmap.c:bitmap_parse_user
  - net/core/net-sysfs.c:xps_cpus_store
  - net/core/net-sysfs.c:store_rps_map
```
**Symbols:**

```
ffffffff8148ede0-ffffffff8148efb9: __bitmap_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __bitmap_parse(const char *buf, unsigned int buflen, int is_user, long unsigned int *maskp, int nmaskbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff814c3a40)
Location: lib/bitmap.c:359
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/padata.c:store_cpumask
  - lib/bitmap.c:bitmap_parse_user
  - net/core/net-sysfs.c:xps_cpus_store
  - net/core/net-sysfs.c:store_rps_map
```
**Symbols:**

```
ffffffff814c3a40-ffffffff814c3c0c: __bitmap_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __bitmap_parse(const char *buf, unsigned int buflen, int is_user, long unsigned int *maskp, int nmaskbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff814d8110)
Location: lib/bitmap.c:356
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/padata.c:store_cpumask
  - lib/bitmap.c:bitmap_parse_user
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_cpus_store
  - net/core/net-sysfs.c:store_rps_map
```
**Symbols:**

```
ffffffff814d8110-ffffffff814d82dc: __bitmap_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __bitmap_parse(const char *buf, unsigned int buflen, int is_user, long unsigned int *maskp, int nmaskbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81503dd0)
Location: lib/bitmap.c:356
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/padata.c:store_cpumask
  - lib/bitmap.c:bitmap_parse_user
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_cpus_store
  - net/core/net-sysfs.c:store_rps_map
```
**Symbols:**

```
ffffffff81503dd0-ffffffff81503fa1: __bitmap_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __bitmap_parse(const char *buf, unsigned int buflen, int is_user, long unsigned int *maskp, int nmaskbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81521d70)
Location: lib/bitmap.c:376
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/padata.c:store_cpumask
  - lib/bitmap.c:bitmap_parse_user
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_cpus_store
  - net/core/net-sysfs.c:store_rps_map
```
**Symbols:**

```
ffffffff81521d70-ffffffff81521f43: __bitmap_parse (STB_GLOBAL)
```
</details>
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
int __bitmap_parse(const char *buf, unsigned int buflen, int is_user, long unsigned int *maskp, int nmaskbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffff80001062b628)
Location: lib/bitmap.c:376
Inline: False
Direct callers:
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/padata.c:store_cpumask
  - lib/bitmap.c:bitmap_parse_user
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_cpus_store
  - net/core/net-sysfs.c:store_rps_map
```
**Symbols:**

```
ffff80001062b628-ffff80001062b95c: __bitmap_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __bitmap_parse(const char *buf, unsigned int buflen, int is_user, long unsigned int *maskp, int nmaskbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (c07d21a0)
Location: lib/bitmap.c:376
Inline: False
Direct callers:
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/padata.c:store_cpumask
  - lib/bitmap.c:bitmap_parse_user
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_cpus_store
  - net/core/net-sysfs.c:store_rps_map
```
**Symbols:**

```
c07d21a0-c07d23dc: __bitmap_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __bitmap_parse(const char *buf, unsigned int buflen, int is_user, long unsigned int *maskp, int nmaskbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (c0000000007cdc40)
Location: lib/bitmap.c:376
Inline: False
Direct callers:
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/padata.c:store_cpumask
  - lib/bitmap.c:bitmap_parse_user
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_cpus_store
  - net/core/net-sysfs.c:store_rps_map
```
**Symbols:**

```
c0000000007cdc40-c0000000007cdf50: __bitmap_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __bitmap_parse(const char *buf, unsigned int buflen, int is_user, long unsigned int *maskp, int nmaskbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffe00045ba10)
Location: lib/bitmap.c:376
Inline: False
Direct callers:
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/padata.c:store_cpumask
  - lib/bitmap.c:bitmap_parse_user
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_cpus_store
  - net/core/net-sysfs.c:store_rps_map
```
**Symbols:**

```
ffffffe00045ba10-ffffffe00045bc4c: __bitmap_parse (STB_GLOBAL)
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
int __bitmap_parse(const char *buf, unsigned int buflen, int is_user, long unsigned int *maskp, int nmaskbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff8151a350)
Location: lib/bitmap.c:376
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/padata.c:store_cpumask
  - lib/bitmap.c:bitmap_parse_user
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_cpus_store
  - net/core/net-sysfs.c:store_rps_map
```
**Symbols:**

```
ffffffff8151a350-ffffffff8151a523: __bitmap_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __bitmap_parse(const char *buf, unsigned int buflen, int is_user, long unsigned int *maskp, int nmaskbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff8150a640)
Location: lib/bitmap.c:376
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/padata.c:store_cpumask
  - lib/bitmap.c:bitmap_parse_user
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_cpus_store
  - net/core/net-sysfs.c:store_rps_map
```
**Symbols:**

```
ffffffff8150a640-ffffffff8150a813: __bitmap_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __bitmap_parse(const char *buf, unsigned int buflen, int is_user, long unsigned int *maskp, int nmaskbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff815163e0)
Location: lib/bitmap.c:376
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/padata.c:store_cpumask
  - lib/bitmap.c:bitmap_parse_user
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_cpus_store
  - net/core/net-sysfs.c:store_rps_map
```
**Symbols:**

```
ffffffff815163e0-ffffffff815165b3: __bitmap_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __bitmap_parse(const char *buf, unsigned int buflen, int is_user, long unsigned int *maskp, int nmaskbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff8152fb70)
Location: lib/bitmap.c:376
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/padata.c:store_cpumask
  - lib/bitmap.c:bitmap_parse_user
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_cpus_store
  - net/core/net-sysfs.c:store_rps_map
```
**Symbols:**

```
ffffffff8152fb70-ffffffff8152fd43: __bitmap_parse (STB_GLOBAL)
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
