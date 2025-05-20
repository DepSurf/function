# Function: <code>vc_read_mem</code>

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
enum es_result vc_read_mem(struct es_em_ctxt *ctxt, char *src, char *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev-es.c (ffffffff81082ec0)
Location: arch/x86/kernel/sev-es.c:344
Inline: False
Direct callers:
  - arch/x86/kernel/sev-es.c:vc_handle_mmio_movs
  - arch/x86/kernel/sev-es.c:vc_handle_ioio
```
**Symbols:**

```
ffffffff81082ec0-ffffffff8108300e: vc_read_mem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
enum es_result vc_read_mem(struct es_em_ctxt *ctxt, char *src, char *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff81083650)
Location: arch/x86/kernel/sev.c:385
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:vc_handle_mmio
  - arch/x86/kernel/sev.c:vc_handle_ioio
```
**Symbols:**

```
ffffffff81083650-ffffffff81083737: vc_read_mem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
enum es_result vc_read_mem(struct es_em_ctxt *ctxt, char *src, char *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/sev.c (0)
Location: arch/x86/kernel/sev.c:372
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:vc_handle_mmio
  - arch/x86/kernel/sev.c:vc_handle_ioio
```
**Symbols:**

```
ffffffff81092790-ffffffff81092890: vc_read_mem (STB_LOCAL)
ffffffff81c9f684-ffffffff81c9f6a0: vc_read_mem.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
enum es_result vc_read_mem(struct es_em_ctxt *ctxt, char *src, char *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/sev.c (0)
Location: arch/x86/kernel/sev.c:402
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:vc_handle_mmio
  - arch/x86/kernel/sev.c:vc_handle_ioio
```
**Symbols:**

```
ffffffff810a3fc0-ffffffff810a40d7: vc_read_mem (STB_LOCAL)
ffffffff81e4ee20-ffffffff81e4ee3c: vc_read_mem.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
enum es_result vc_read_mem(struct es_em_ctxt *ctxt, char *src, char *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/sev.c (0)
Location: arch/x86/kernel/sev.c:402
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:vc_handle_mmio
  - arch/x86/kernel/sev.c:vc_handle_ioio
```
**Symbols:**

```
ffffffff810bc210-ffffffff810bc327: vc_read_mem (STB_LOCAL)
ffffffff82054612-ffffffff8205462e: vc_read_mem.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
enum es_result vc_read_mem(struct es_em_ctxt *ctxt, char *src, char *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/sev.c (0)
Location: arch/x86/kernel/sev.c:414
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:vc_handle_mmio
  - arch/x86/kernel/sev.c:vc_handle_ioio
```
**Symbols:**

```
ffffffff810bf500-ffffffff810bf61b: vc_read_mem (STB_LOCAL)
ffffffff820d2c03-ffffffff820d2c1f: vc_read_mem.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
enum es_result vc_read_mem(struct es_em_ctxt *ctxt, char *src, char *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/sev.c (0)
Location: arch/x86/kernel/sev.c:414
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:vc_handle_mmio
  - arch/x86/kernel/sev.c:vc_handle_ioio
```
**Symbols:**

```
ffffffff810c6850-ffffffff810c696b: vc_read_mem (STB_LOCAL)
ffffffff821ada65-ffffffff821ada81: vc_read_mem.cold (STB_LOCAL)
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
