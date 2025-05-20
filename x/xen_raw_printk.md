# Function: <code>xen_raw_printk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void xen_raw_printk(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_xen.c (ffffffff814ff920)
Location: drivers/tty/hvc/hvc_xen.c:656
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_start_kernel
```
**Symbols:**

```
ffffffff814ff920-ffffffff814ff9aa: xen_raw_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void xen_raw_printk(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_xen.c (ffffffff81550570)
Location: drivers/tty/hvc/hvc_xen.c:682
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_start_kernel
```
**Symbols:**

```
ffffffff81550570-ffffffff815505fa: xen_raw_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void xen_raw_printk(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_xen.c (ffffffff8157cdf0)
Location: drivers/tty/hvc/hvc_xen.c:682
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_start_kernel
  - arch/x86/xen/smp.c:xen_smp_prepare_cpus
```
**Symbols:**

```
ffffffff8157cdf0-ffffffff8157ce7a: xen_raw_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void xen_raw_printk(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_xen.c (ffffffff81591060)
Location: drivers/tty/hvc/hvc_xen.c:682
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pvh.c:xen_prepare_pvh
  - arch/x86/xen/enlighten_pvh.c:xen_prepare_pvh
  - arch/x86/xen/enlighten_pvh.c:xen_prepare_pvh
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
```
**Symbols:**

```
ffffffff81591060-ffffffff815910e9: xen_raw_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void xen_raw_printk(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_xen.c (ffffffff815f5af0)
Location: drivers/tty/hvc/hvc_xen.c:669
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pvh.c:xen_prepare_pvh
  - arch/x86/xen/enlighten_pvh.c:xen_prepare_pvh
  - arch/x86/xen/enlighten_pvh.c:xen_prepare_pvh
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
```
**Symbols:**

```
ffffffff815f5af0-ffffffff815f5b79: xen_raw_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void xen_raw_printk(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_xen.c (ffffffff8162eca0)
Location: drivers/tty/hvc/hvc_xen.c:669
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pvh.c:xen_prepare_pvh
  - arch/x86/xen/enlighten_pvh.c:xen_prepare_pvh
  - arch/x86/xen/enlighten_pvh.c:xen_prepare_pvh
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
```
**Symbols:**

```
ffffffff8162eca0-ffffffff8162ed2a: xen_raw_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void xen_raw_printk(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_xen.c (ffffffff8164ce20)
Location: drivers/tty/hvc/hvc_xen.c:669
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pvh.c:mem_map_via_hcall
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh
  - arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh
  - arch/x86/platform/pvh/enlighten.c:xen_pvh_init
  - arch/x86/platform/pvh/enlighten.c:mem_map_via_hcall
```
**Symbols:**

```
ffffffff8164ce20-ffffffff8164ceaa: xen_raw_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void xen_raw_printk(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_xen.c (ffffffff81681950)
Location: drivers/tty/hvc/hvc_xen.c:669
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pvh.c:mem_map_via_hcall
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh
  - arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh
  - arch/x86/platform/pvh/enlighten.c:xen_pvh_init
  - arch/x86/platform/pvh/enlighten.c:mem_map_via_hcall
```
**Symbols:**

```
ffffffff81681950-ffffffff816819da: xen_raw_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void xen_raw_printk(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_xen.c (ffffffff816a4000)
Location: drivers/tty/hvc/hvc_xen.c:669
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pvh.c:mem_map_via_hcall
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh
  - arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh
  - arch/x86/platform/pvh/enlighten.c:xen_pvh_init
  - arch/x86/platform/pvh/enlighten.c:mem_map_via_hcall
```
**Symbols:**

```
ffffffff816a4000-ffffffff816a408a: xen_raw_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void xen_raw_printk(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_xen.c (ffffffff817567f0)
Location: drivers/tty/hvc/hvc_xen.c:669
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pvh.c:mem_map_via_hcall
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh
  - arch/x86/platform/pvh/enlighten.c:xen_pvh_init
  - arch/x86/platform/pvh/enlighten.c:init_pvh_bootparams
  - arch/x86/platform/pvh/enlighten.c:mem_map_via_hcall
```
**Symbols:**

```
ffffffff817567f0-ffffffff8175687a: xen_raw_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void xen_raw_printk(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_xen.c (ffffffff81771a60)
Location: drivers/tty/hvc/hvc_xen.c:669
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pvh.c:mem_map_via_hcall
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh
  - arch/x86/platform/pvh/enlighten.c:xen_pvh_init
  - arch/x86/platform/pvh/enlighten.c:init_pvh_bootparams
  - arch/x86/platform/pvh/enlighten.c:mem_map_via_hcall
```
**Symbols:**

```
ffffffff81771a60-ffffffff81771aea: xen_raw_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void xen_raw_printk(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_xen.c (ffffffff81755520)
Location: drivers/tty/hvc/hvc_xen.c:669
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pvh.c:mem_map_via_hcall
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh
  - arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh
  - arch/x86/platform/pvh/enlighten.c:xen_pvh_init
  - arch/x86/platform/pvh/enlighten.c:mem_map_via_hcall
```
**Symbols:**

```
ffffffff81755520-ffffffff817555aa: xen_raw_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void xen_raw_printk(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_xen.c (ffffffff817d8c50)
Location: drivers/tty/hvc/hvc_xen.c:701
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pvh.c:mem_map_via_hcall
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh
  - arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh
  - arch/x86/platform/pvh/enlighten.c:mem_map_via_hcall
  - arch/x86/platform/pvh/enlighten.c:xen_pvh_init
```
**Symbols:**

```
ffffffff817d8c50-ffffffff817d8cda: xen_raw_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void xen_raw_printk(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_xen.c (ffffffff81917030)
Location: drivers/tty/hvc/hvc_xen.c:702
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pvh.c:mem_map_via_hcall
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh
  - arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh
  - arch/x86/platform/pvh/enlighten.c:mem_map_via_hcall
  - arch/x86/platform/pvh/enlighten.c:xen_pvh_init
```
**Symbols:**

```
ffffffff81917030-ffffffff819170d6: xen_raw_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void xen_raw_printk(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_xen.c (ffffffff81a72450)
Location: drivers/tty/hvc/hvc_xen.c:714
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pvh.c:mem_map_via_hcall
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh
  - arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh
  - arch/x86/platform/pvh/enlighten.c:mem_map_via_hcall
  - arch/x86/platform/pvh/enlighten.c:xen_pvh_init
```
**Symbols:**

```
ffffffff81a72450-ffffffff81a724f6: xen_raw_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void xen_raw_printk(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_xen.c (ffffffff81abcd10)
Location: drivers/tty/hvc/hvc_xen.c:729
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pvh.c:mem_map_via_hcall
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh
  - arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh
  - arch/x86/platform/pvh/enlighten.c:mem_map_via_hcall
  - arch/x86/platform/pvh/enlighten.c:xen_pvh_init
```
**Symbols:**

```
ffffffff81abcd10-ffffffff81abcdb6: xen_raw_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void xen_raw_printk(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_xen.c (ffffffff81b0fb00)
Location: drivers/tty/hvc/hvc_xen.c:747
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pvh.c:mem_map_via_hcall
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh
  - arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh
  - arch/x86/platform/pvh/enlighten.c:mem_map_via_hcall
  - arch/x86/platform/pvh/enlighten.c:xen_pvh_init
```
**Symbols:**

```
ffffffff81b0fb00-ffffffff81b0fba6: xen_raw_printk (STB_GLOBAL)
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
void xen_raw_printk(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_xen.c (ffff80001087c3b0)
Location: drivers/tty/hvc/hvc_xen.c:669
Inline: False
```
**Symbols:**

```
ffff80001087c3b0-ffff80001087c458: xen_raw_printk (STB_GLOBAL)
```
</details>
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
<summary>In <code>aws</code>: ✅</summary>

```c
void xen_raw_printk(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_xen.c (ffffffff81669a60)
Location: drivers/tty/hvc/hvc_xen.c:669
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pvh.c:mem_map_via_hcall
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh
  - arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh
  - arch/x86/platform/pvh/enlighten.c:xen_pvh_init
  - arch/x86/platform/pvh/enlighten.c:mem_map_via_hcall
```
**Symbols:**

```
ffffffff81669a60-ffffffff81669aea: xen_raw_printk (STB_GLOBAL)
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
In arch/x86/platform/pvh/enlighten.c (0)
Location: include/xen/hvc-console.h:16
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void xen_raw_printk(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_xen.c (ffffffff81697e40)
Location: drivers/tty/hvc/hvc_xen.c:669
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pvh.c:mem_map_via_hcall
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh
  - arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh
  - arch/x86/platform/pvh/enlighten.c:xen_pvh_init
  - arch/x86/platform/pvh/enlighten.c:mem_map_via_hcall
```
**Symbols:**

```
ffffffff81697e40-ffffffff81697eca: xen_raw_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void xen_raw_printk(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_xen.c (ffffffff816b23c0)
Location: drivers/tty/hvc/hvc_xen.c:669
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pvh.c:mem_map_via_hcall
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh
  - arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh
  - arch/x86/platform/pvh/enlighten.c:xen_pvh_init
  - arch/x86/platform/pvh/enlighten.c:mem_map_via_hcall
```
**Symbols:**

```
ffffffff816b23c0-ffffffff816b244a: xen_raw_printk (STB_GLOBAL)
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
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
