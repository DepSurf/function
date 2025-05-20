# Function: <code>vc_handle_exitcode</code>

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
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
enum es_result vc_handle_exitcode(struct es_em_ctxt *ctxt, struct ghcb *ghcb, long unsigned int exit_code);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/sev-es.c (0)
Location: arch/x86/kernel/sev-es.c:1156
Inline: False
Direct callers:
  - arch/x86/kernel/sev-es.c:handle_vc_boot_ghcb
  - arch/x86/kernel/sev-es.c:safe_stack_exc_vmm_communication
```
**Symbols:**

```
ffffffff81083eb0-ffffffff8108422e: vc_handle_exitcode (STB_LOCAL)
ffffffff81bd8494-ffffffff81bd84aa: vc_handle_exitcode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
enum es_result vc_handle_exitcode(struct es_em_ctxt *ctxt, struct ghcb *ghcb, long unsigned int exit_code);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/sev.c (0)
Location: arch/x86/kernel/sev.c:1227
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:handle_vc_boot_ghcb
  - arch/x86/kernel/sev.c:vc_raw_handle_exception
```
**Symbols:**

```
ffffffff81084510-ffffffff81084b0a: vc_handle_exitcode (STB_LOCAL)
ffffffff81bca2bc-ffffffff81bca2d2: vc_handle_exitcode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
enum es_result vc_handle_exitcode(struct es_em_ctxt *ctxt, struct ghcb *ghcb, long unsigned int exit_code);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/sev.c (0)
Location: arch/x86/kernel/sev.c:1223
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:handle_vc_boot_ghcb
  - arch/x86/kernel/sev.c:vc_raw_handle_exception
```
**Symbols:**

```
ffffffff810936d0-ffffffff81093cca: vc_handle_exitcode (STB_LOCAL)
ffffffff81c9f6ff-ffffffff81c9f715: vc_handle_exitcode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
enum es_result vc_handle_exitcode(struct es_em_ctxt *ctxt, struct ghcb *ghcb, long unsigned int exit_code);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/sev.c (0)
Location: arch/x86/kernel/sev.c:1756
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:handle_vc_boot_ghcb
  - arch/x86/kernel/sev.c:vc_raw_handle_exception
```
**Symbols:**

```
ffffffff810a5930-ffffffff810a5f8f: vc_handle_exitcode (STB_LOCAL)
ffffffff81e4ef28-ffffffff81e4ef39: vc_handle_exitcode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
enum es_result vc_handle_exitcode(struct es_em_ctxt *ctxt, struct ghcb *ghcb, long unsigned int exit_code);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff810be1a0)
Location: arch/x86/kernel/sev.c:1756
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:handle_vc_boot_ghcb
  - arch/x86/kernel/sev.c:vc_raw_handle_exception
```
**Symbols:**

```
ffffffff810be1a0-ffffffff810be6bd: vc_handle_exitcode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
enum es_result vc_handle_exitcode(struct es_em_ctxt *ctxt, struct ghcb *ghcb, long unsigned int exit_code);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff810c1830)
Location: arch/x86/kernel/sev.c:1713
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:handle_vc_boot_ghcb
  - arch/x86/kernel/sev.c:vc_raw_handle_exception
```
**Symbols:**

```
ffffffff810c1830-ffffffff810c1d30: vc_handle_exitcode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
enum es_result vc_handle_exitcode(struct es_em_ctxt *ctxt, struct ghcb *ghcb, long unsigned int exit_code);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff810c8cb0)
Location: arch/x86/kernel/sev.c:1751
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:handle_vc_boot_ghcb
  - arch/x86/kernel/sev.c:vc_raw_handle_exception
```
**Symbols:**

```
ffffffff810c8cb0-ffffffff810c91e9: vc_handle_exitcode (STB_LOCAL)
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
