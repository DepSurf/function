# Function: <code>sev_es_terminate</code>

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
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/sev-es.c (ffffffff81bd847f)
Location: arch/x86/kernel/sev-es-shared.c:27
Inline: True
Direct callers:
  - arch/x86/kernel/sev-es.c:handle_vc_boot_ghcb
  - arch/x86/kernel/sev-es.c:safe_stack_exc_vmm_communication
```
**Symbols:**

```
ffffffff81bd847f-ffffffff81bd8494: sev_es_terminate.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff81083bd0)
Location: arch/x86/kernel/sev-shared.c:27
Inline: True
Direct callers:
  - arch/x86/kernel/sev.c:handle_vc_boot_ghcb
  - arch/x86/kernel/sev.c:do_vc_no_ghcb
  - arch/x86/kernel/sev.c:kernel_exc_vmm_communication
```
**Symbols:**

```
ffffffff81083bd0-ffffffff81083be5: sev_es_terminate.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff81092990)
Location: arch/x86/kernel/sev-shared.c:27
Inline: True
Direct callers:
  - arch/x86/kernel/sev.c:handle_vc_boot_ghcb
  - arch/x86/kernel/sev.c:do_vc_no_ghcb
  - arch/x86/kernel/sev.c:kernel_exc_vmm_communication
```
**Symbols:**

```
ffffffff81092990-ffffffff810929a5: sev_es_terminate.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void sev_es_terminate(unsigned int set, unsigned int reason);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff810a3640)
Location: arch/x86/kernel/sev-shared.c:89
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:snp_abort
  - arch/x86/kernel/sev.c:handle_vc_boot_ghcb
  - arch/x86/kernel/sev.c:setup_ghcb
  - arch/x86/kernel/sev.c:early_set_pages_state
  - arch/x86/kernel/sev.c:setup_cpuid_table
  - arch/x86/kernel/sev.c:do_vc_no_ghcb
  - arch/x86/kernel/sev.c:snp_register_ghcb_early
  - arch/x86/kernel/sev.c:kernel_exc_vmm_communication
  - arch/x86/kernel/sev.c:sev_es_init_vc_handling
```
**Symbols:**

```
ffffffff810a3640-ffffffff810a3662: sev_es_terminate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void sev_es_terminate(unsigned int set, unsigned int reason);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff810bba60)
Location: arch/x86/kernel/sev-shared.c:89
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:handle_vc_boot_ghcb
  - arch/x86/kernel/sev.c:setup_ghcb
  - arch/x86/kernel/sev.c:early_set_pages_state
  - arch/x86/kernel/sev.c:setup_cpuid_table
  - arch/x86/kernel/sev.c:do_vc_no_ghcb
  - arch/x86/kernel/sev.c:snp_register_ghcb_early
  - arch/x86/kernel/sev.c:kernel_exc_vmm_communication
  - arch/x86/kernel/sev.c:snp_abort
  - arch/x86/kernel/sev.c:sev_es_init_vc_handling
```
**Symbols:**

```
ffffffff810bba60-ffffffff810bba82: sev_es_terminate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void sev_es_terminate(unsigned int set, unsigned int reason);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff810beba0)
Location: arch/x86/kernel/sev-shared.c:92
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:handle_vc_boot_ghcb
  - arch/x86/kernel/sev.c:setup_ghcb
  - arch/x86/kernel/sev.c:__set_pages_state
  - arch/x86/kernel/sev.c:early_set_pages_state
  - arch/x86/kernel/sev.c:early_set_pages_state
  - arch/x86/kernel/sev.c:early_set_pages_state
  - arch/x86/kernel/sev.c:pvalidate_pages
  - arch/x86/kernel/sev.c:setup_cpuid_table
  - arch/x86/kernel/sev.c:do_vc_no_ghcb
  - arch/x86/kernel/sev.c:snp_register_ghcb_early
  - arch/x86/kernel/sev.c:kernel_exc_vmm_communication
  - arch/x86/kernel/sev.c:snp_abort
  - arch/x86/kernel/sev.c:sev_es_init_vc_handling
```
**Symbols:**

```
ffffffff810beba0-ffffffff810bebc2: sev_es_terminate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void sev_es_terminate(unsigned int set, unsigned int reason);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff810c5d20)
Location: arch/x86/kernel/sev-shared.c:92
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:handle_vc_boot_ghcb
  - arch/x86/kernel/sev.c:setup_ghcb
  - arch/x86/kernel/sev.c:__set_pages_state
  - arch/x86/kernel/sev.c:early_set_pages_state
  - arch/x86/kernel/sev.c:early_set_pages_state
  - arch/x86/kernel/sev.c:early_set_pages_state
  - arch/x86/kernel/sev.c:pvalidate_pages
  - arch/x86/kernel/sev.c:setup_cpuid_table
  - arch/x86/kernel/sev.c:do_vc_no_ghcb
  - arch/x86/kernel/sev.c:snp_register_ghcb_early
  - arch/x86/kernel/sev.c:kernel_exc_vmm_communication
  - arch/x86/kernel/sev.c:snp_abort
  - arch/x86/kernel/sev.c:sev_es_init_vc_handling
```
**Symbols:**

```
ffffffff810c5d20-ffffffff810c5d42: sev_es_terminate (STB_LOCAL)
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
