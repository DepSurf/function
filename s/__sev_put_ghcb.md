# Function: <code>__sev_put_ghcb</code>

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
void __sev_put_ghcb(struct ghcb_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff81c2a540)
Location: arch/x86/kernel/sev.c:491
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:vc_raw_handle_exception
  - arch/x86/kernel/sev.c:sev_es_play_dead
  - arch/x86/kernel/sev.c:get_jump_table_addr
  - arch/x86/kernel/sev.c:get_jump_table_addr
  - arch/x86/kernel/sev.c:__sev_es_nmi_complete
```
**Symbols:**

```
ffffffff81c2a540-ffffffff81c2a5d2: __sev_put_ghcb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __sev_put_ghcb(struct ghcb_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff81d48a20)
Location: arch/x86/kernel/sev.c:488
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:vc_raw_handle_exception
  - arch/x86/kernel/sev.c:sev_es_play_dead
  - arch/x86/kernel/sev.c:get_jump_table_addr
  - arch/x86/kernel/sev.c:get_jump_table_addr
  - arch/x86/kernel/sev.c:__sev_es_nmi_complete
```
**Symbols:**

```
ffffffff81d48a20-ffffffff81d48ab2: __sev_put_ghcb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __sev_put_ghcb(struct ghcb_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff81f17cc0)
Location: arch/x86/kernel/sev.c:518
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:snp_issue_guest_request
  - arch/x86/kernel/sev.c:vc_raw_handle_exception
  - arch/x86/kernel/sev.c:sev_es_play_dead
  - arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit
  - arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit
  - arch/x86/kernel/sev.c:vmgexit_psc
  - arch/x86/kernel/sev.c:get_jump_table_addr
  - arch/x86/kernel/sev.c:__sev_es_nmi_complete
```
**Symbols:**

```
ffffffff81f17cc0-ffffffff81f17d74: __sev_put_ghcb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __sev_put_ghcb(struct ghcb_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff820bf460)
Location: arch/x86/kernel/sev.c:518
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:snp_issue_guest_request
  - arch/x86/kernel/sev.c:vc_raw_handle_exception
  - arch/x86/kernel/sev.c:sev_es_play_dead
  - arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit
  - arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit
  - arch/x86/kernel/sev.c:vmgexit_psc
  - arch/x86/kernel/sev.c:get_jump_table_addr
  - arch/x86/kernel/sev.c:__sev_es_nmi_complete
```
**Symbols:**

```
ffffffff820bf460-ffffffff820bf51a: __sev_put_ghcb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __sev_put_ghcb(struct ghcb_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff82141160)
Location: arch/x86/kernel/sev.c:530
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:snp_issue_guest_request
  - arch/x86/kernel/sev.c:vc_raw_handle_exception
  - arch/x86/kernel/sev.c:sev_es_play_dead
  - arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit
  - arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit
  - arch/x86/kernel/sev.c:__set_pages_state
  - arch/x86/kernel/sev.c:get_jump_table_addr
  - arch/x86/kernel/sev.c:__sev_es_nmi_complete
```
**Symbols:**

```
ffffffff82141160-ffffffff8214121a: __sev_put_ghcb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __sev_put_ghcb(struct ghcb_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff82223070)
Location: arch/x86/kernel/sev.c:557
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:snp_issue_guest_request
  - arch/x86/kernel/sev.c:vc_raw_handle_exception
  - arch/x86/kernel/sev.c:sev_es_play_dead
  - arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit
  - arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit
  - arch/x86/kernel/sev.c:__set_pages_state
  - arch/x86/kernel/sev.c:get_jump_table_addr
  - arch/x86/kernel/sev.c:__sev_es_nmi_complete
```
**Symbols:**

```
ffffffff82223070-ffffffff8222312a: __sev_put_ghcb (STB_LOCAL)
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
