# Function: <code>vc_decode_insn</code>

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
<summary>In <code>5.11</code>: ✅</summary>

```c
enum es_result vc_decode_insn(struct es_em_ctxt *ctxt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev-es.c (ffffffff81082ae0)
Location: arch/x86/kernel/sev-es.c:254
Inline: False
Direct callers:
  - arch/x86/kernel/sev-es.c:safe_stack_exc_vmm_communication
```
**Symbols:**

```
ffffffff81082ae0-ffffffff81082bed: vc_decode_insn (STB_LOCAL)
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
In arch/x86/kernel/sev.c (ffffffff810833c8)
Location: arch/x86/kernel/sev.c:309
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:vc_init_em_ctxt
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
In arch/x86/kernel/sev.c (ffffffff810924d8)
Location: arch/x86/kernel/sev.c:285
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:vc_init_em_ctxt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
enum es_result vc_decode_insn(struct es_em_ctxt *ctxt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff810a3780)
Location: arch/x86/kernel/sev.c:315
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:handle_vc_boot_ghcb
  - arch/x86/kernel/sev.c:vc_raw_handle_exception
```
**Symbols:**

```
ffffffff810a3780-ffffffff810a38bd: vc_decode_insn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
enum es_result vc_decode_insn(struct es_em_ctxt *ctxt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff810bbbc0)
Location: arch/x86/kernel/sev.c:315
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:handle_vc_boot_ghcb
  - arch/x86/kernel/sev.c:vc_raw_handle_exception
```
**Symbols:**

```
ffffffff810bbbc0-ffffffff810bbcfd: vc_decode_insn (STB_LOCAL)
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
In arch/x86/kernel/sev.c (ffffffff810beee6)
Location: arch/x86/kernel/sev.c:327
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:vc_init_em_ctxt
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
In arch/x86/kernel/sev.c (ffffffff810c61a6)
Location: arch/x86/kernel/sev.c:327
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:vc_init_em_ctxt
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
</ul>
