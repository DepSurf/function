# Function: <code>vc_handle_ioio</code>

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
enum es_result vc_handle_ioio(struct ghcb *ghcb, struct es_em_ctxt *ctxt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev-es.c (ffffffff81083160)
Location: arch/x86/kernel/sev-es-shared.c:369
Inline: False
Direct callers:
  - arch/x86/kernel/sev-es.c:vc_handle_exitcode
```
**Symbols:**

```
ffffffff81083160-ffffffff8108353d: vc_handle_ioio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
enum es_result vc_handle_ioio(struct ghcb *ghcb, struct es_em_ctxt *ctxt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff810837f0)
Location: arch/x86/kernel/sev-shared.c:362
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:vc_handle_exitcode
```
**Symbols:**

```
ffffffff810837f0-ffffffff81083bca: vc_handle_ioio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
enum es_result vc_handle_ioio(struct ghcb *ghcb, struct es_em_ctxt *ctxt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff810929b0)
Location: arch/x86/kernel/sev-shared.c:364
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:vc_handle_exitcode
```
**Symbols:**

```
ffffffff810929b0-ffffffff81092d8e: vc_handle_ioio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
enum es_result vc_handle_ioio(struct ghcb *ghcb, struct es_em_ctxt *ctxt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff810a4420)
Location: arch/x86/kernel/sev-shared.c:740
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:vc_handle_exitcode
```
**Symbols:**

```
ffffffff810a4420-ffffffff810a4841: vc_handle_ioio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
enum es_result vc_handle_ioio(struct ghcb *ghcb, struct es_em_ctxt *ctxt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff810bc930)
Location: arch/x86/kernel/sev-shared.c:740
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:vc_handle_exitcode
```
**Symbols:**

```
ffffffff810bc930-ffffffff810bcd51: vc_handle_ioio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
enum es_result vc_handle_ioio(struct ghcb *ghcb, struct es_em_ctxt *ctxt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff810bfc60)
Location: arch/x86/kernel/sev-shared.c:743
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:vc_handle_exitcode
```
**Symbols:**

```
ffffffff810bfc60-ffffffff810c007b: vc_handle_ioio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
enum es_result vc_handle_ioio(struct ghcb *ghcb, struct es_em_ctxt *ctxt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff810c6fb0)
Location: arch/x86/kernel/sev-shared.c:818
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:vc_handle_exitcode
```
**Symbols:**

```
ffffffff810c6fb0-ffffffff810c7465: vc_handle_ioio (STB_LOCAL)
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
