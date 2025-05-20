# Function: <code>vc_write_mem</code>

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
enum es_result vc_write_mem(struct es_em_ctxt *ctxt, char *dst, char *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev-es.c (ffffffff81083010)
Location: arch/x86/kernel/sev-es.c:289
Inline: False
Direct callers:
  - arch/x86/kernel/sev-es.c:vc_handle_mmio_movs
  - arch/x86/kernel/sev-es.c:vc_handle_ioio
```
**Symbols:**

```
ffffffff81083010-ffffffff8108315e: vc_write_mem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
enum es_result vc_write_mem(struct es_em_ctxt *ctxt, char *dst, char *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff81083740)
Location: arch/x86/kernel/sev.c:317
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:vc_handle_mmio
  - arch/x86/kernel/sev.c:vc_handle_ioio
```
**Symbols:**

```
ffffffff81083740-ffffffff810837e8: vc_write_mem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
enum es_result vc_write_mem(struct es_em_ctxt *ctxt, char *dst, char *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/sev.c (0)
Location: arch/x86/kernel/sev.c:293
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:vc_handle_mmio
  - arch/x86/kernel/sev.c:vc_handle_ioio
```
**Symbols:**

```
ffffffff81092890-ffffffff8109298d: vc_write_mem (STB_LOCAL)
ffffffff81c9f6a0-ffffffff81c9f6bc: vc_write_mem.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
enum es_result vc_write_mem(struct es_em_ctxt *ctxt, char *dst, char *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/sev.c (0)
Location: arch/x86/kernel/sev.c:323
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:vc_handle_mmio
  - arch/x86/kernel/sev.c:vc_handle_ioio
```
**Symbols:**

```
ffffffff810a40e0-ffffffff810a41ef: vc_write_mem (STB_LOCAL)
ffffffff81e4ee3c-ffffffff81e4ee58: vc_write_mem.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
enum es_result vc_write_mem(struct es_em_ctxt *ctxt, char *dst, char *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/sev.c (0)
Location: arch/x86/kernel/sev.c:323
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:vc_handle_mmio
  - arch/x86/kernel/sev.c:vc_handle_ioio
```
**Symbols:**

```
ffffffff810bc340-ffffffff810bc44f: vc_write_mem (STB_LOCAL)
ffffffff8205462e-ffffffff8205464a: vc_write_mem.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
enum es_result vc_write_mem(struct es_em_ctxt *ctxt, char *dst, char *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/sev.c (0)
Location: arch/x86/kernel/sev.c:335
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:vc_handle_mmio
  - arch/x86/kernel/sev.c:vc_handle_ioio
```
**Symbols:**

```
ffffffff810bf630-ffffffff810bf73f: vc_write_mem (STB_LOCAL)
ffffffff820d2c1f-ffffffff820d2c3b: vc_write_mem.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
enum es_result vc_write_mem(struct es_em_ctxt *ctxt, char *dst, char *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/sev.c (0)
Location: arch/x86/kernel/sev.c:335
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:vc_handle_mmio
  - arch/x86/kernel/sev.c:vc_handle_ioio
```
**Symbols:**

```
ffffffff810c6980-ffffffff810c6a8f: vc_write_mem (STB_LOCAL)
ffffffff821ada81-ffffffff821ada9d: vc_write_mem.cold (STB_LOCAL)
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
