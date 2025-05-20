# Function: <code>vc_ghcb_invalidate</code>

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
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev-es.c (ffffffff82fd1583)
Location: arch/x86/kernel/sev-es-shared.c:64
Inline: True
Inline callers:
  - arch/x86/kernel/sev-es.c:handle_vc_boot_ghcb
  - arch/x86/kernel/sev-es.c:sev_es_ap_hlt_loop
  - arch/x86/kernel/sev-es.c:get_jump_table_addr
  - arch/x86/kernel/sev-es.c:__sev_es_nmi_complete
  - arch/x86/kernel/sev-es.c:safe_stack_exc_vmm_communication
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
In arch/x86/kernel/sev.c (ffffffff831dc232)
Location: arch/x86/kernel/sev-shared.c:64
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:handle_vc_boot_ghcb
  - arch/x86/kernel/sev.c:vc_raw_handle_exception
  - arch/x86/kernel/sev.c:sev_es_play_dead
  - arch/x86/kernel/sev.c:get_jump_table_addr
  - arch/x86/kernel/sev.c:__sev_es_nmi_complete
  - arch/x86/kernel/sev.c:__sev_put_ghcb
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff832bf2e8)
Location: arch/x86/kernel/sev-shared.c:64
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:handle_vc_boot_ghcb
  - arch/x86/kernel/sev.c:vc_raw_handle_exception
  - arch/x86/kernel/sev.c:sev_es_play_dead
  - arch/x86/kernel/sev.c:get_jump_table_addr
  - arch/x86/kernel/sev.c:__sev_es_nmi_complete
  - arch/x86/kernel/sev.c:__sev_put_ghcb
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff810a3c41)
Location: arch/x86/kernel/sev-shared.c:161
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:snp_issue_guest_request
  - arch/x86/kernel/sev.c:handle_vc_boot_ghcb
  - arch/x86/kernel/sev.c:vc_raw_handle_exception
  - arch/x86/kernel/sev.c:sev_es_play_dead
  - arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit
  - arch/x86/kernel/sev.c:get_jump_table_addr
  - arch/x86/kernel/sev.c:__sev_es_nmi_complete
  - arch/x86/kernel/sev.c:__sev_put_ghcb
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff810bc0b1)
Location: arch/x86/kernel/sev-shared.c:161
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:snp_issue_guest_request
  - arch/x86/kernel/sev.c:handle_vc_boot_ghcb
  - arch/x86/kernel/sev.c:vc_raw_handle_exception
  - arch/x86/kernel/sev.c:sev_es_play_dead
  - arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit
  - arch/x86/kernel/sev.c:get_jump_table_addr
  - arch/x86/kernel/sev.c:__sev_es_nmi_complete
  - arch/x86/kernel/sev.c:__sev_put_ghcb
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff810bf3b7)
Location: arch/x86/kernel/sev-shared.c:164
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:snp_issue_guest_request
  - arch/x86/kernel/sev.c:handle_vc_boot_ghcb
  - arch/x86/kernel/sev.c:vc_raw_handle_exception
  - arch/x86/kernel/sev.c:sev_es_play_dead
  - arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit
  - arch/x86/kernel/sev.c:get_jump_table_addr
  - arch/x86/kernel/sev.c:__sev_es_nmi_complete
  - arch/x86/kernel/sev.c:__sev_put_ghcb
  - arch/x86/kernel/sev.c:vmgexit_psc
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff810c6707)
Location: arch/x86/kernel/sev-shared.c:164
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:snp_issue_guest_request
  - arch/x86/kernel/sev.c:handle_vc_boot_ghcb
  - arch/x86/kernel/sev.c:vc_raw_handle_exception
  - arch/x86/kernel/sev.c:sev_es_play_dead
  - arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit
  - arch/x86/kernel/sev.c:get_jump_table_addr
  - arch/x86/kernel/sev.c:__sev_es_nmi_complete
  - arch/x86/kernel/sev.c:__sev_put_ghcb
  - arch/x86/kernel/sev.c:vmgexit_psc
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
