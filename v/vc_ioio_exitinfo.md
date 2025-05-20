# Function: <code>vc_ioio_exitinfo</code>

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
enum es_result vc_ioio_exitinfo(struct es_em_ctxt *ctxt, u64 *exitinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev-es.c (ffffffff81082d10)
Location: arch/x86/kernel/sev-es-shared.c:282
Inline: False
Direct callers:
  - arch/x86/kernel/sev-es.c:vc_handle_ioio
```
**Symbols:**

```
ffffffff81082d10-ffffffff81082eba: vc_ioio_exitinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
enum es_result vc_ioio_exitinfo(struct es_em_ctxt *ctxt, u64 *exitinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff810834b0)
Location: arch/x86/kernel/sev-shared.c:275
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:vc_handle_ioio
```
**Symbols:**

```
ffffffff810834b0-ffffffff81083646: vc_ioio_exitinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
enum es_result vc_ioio_exitinfo(struct es_em_ctxt *ctxt, u64 *exitinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff810925f0)
Location: arch/x86/kernel/sev-shared.c:277
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:vc_handle_ioio
```
**Symbols:**

```
ffffffff810925f0-ffffffff81092786: vc_ioio_exitinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
enum es_result vc_ioio_exitinfo(struct es_em_ctxt *ctxt, u64 *exitinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff810a38c0)
Location: arch/x86/kernel/sev-shared.c:653
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:vc_handle_ioio
```
**Symbols:**

```
ffffffff810a38c0-ffffffff810a3a6a: vc_ioio_exitinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
enum es_result vc_ioio_exitinfo(struct es_em_ctxt *ctxt, u64 *exitinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff810bbd10)
Location: arch/x86/kernel/sev-shared.c:653
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:vc_handle_ioio
```
**Symbols:**

```
ffffffff810bbd10-ffffffff810bbeba: vc_ioio_exitinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
enum es_result vc_ioio_exitinfo(struct es_em_ctxt *ctxt, u64 *exitinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff810bf010)
Location: arch/x86/kernel/sev-shared.c:656
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:vc_handle_ioio
```
**Symbols:**

```
ffffffff810bf010-ffffffff810bf1cf: vc_ioio_exitinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
enum es_result vc_ioio_exitinfo(struct es_em_ctxt *ctxt, u64 *exitinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff810c62d0)
Location: arch/x86/kernel/sev-shared.c:723
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:vc_handle_ioio
```
**Symbols:**

```
ffffffff810c62d0-ffffffff810c6520: vc_ioio_exitinfo (STB_LOCAL)
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
