# Function: <code>vc_do_mmio</code>

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
enum es_result vc_do_mmio(struct ghcb *ghcb, struct es_em_ctxt *ctxt, unsigned int bytes, bool read);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev-es.c (ffffffff810837d0)
Location: arch/x86/kernel/sev-es.c:755
Inline: False
Direct callers:
  - arch/x86/kernel/sev-es.c:vc_handle_mmio
  - arch/x86/kernel/sev-es.c:vc_handle_mmio
  - arch/x86/kernel/sev-es.c:vc_handle_mmio
  - arch/x86/kernel/sev-es.c:vc_handle_mmio_twobyte_ops
  - arch/x86/kernel/sev-es.c:vc_handle_mmio_twobyte_ops
```
**Symbols:**

```
ffffffff810837d0-ffffffff810838cf: vc_do_mmio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
enum es_result vc_do_mmio(struct ghcb *ghcb, struct es_em_ctxt *ctxt, unsigned int bytes, bool read);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff81083d30)
Location: arch/x86/kernel/sev.c:834
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:vc_handle_mmio
  - arch/x86/kernel/sev.c:vc_handle_mmio
  - arch/x86/kernel/sev.c:vc_handle_mmio
  - arch/x86/kernel/sev.c:vc_handle_mmio_twobyte_ops
  - arch/x86/kernel/sev.c:vc_handle_mmio_twobyte_ops
```
**Symbols:**

```
ffffffff81083d30-ffffffff81083e27: vc_do_mmio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
enum es_result vc_do_mmio(struct ghcb *ghcb, struct es_em_ctxt *ctxt, unsigned int bytes, bool read);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff81092ef0)
Location: arch/x86/kernel/sev.c:830
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:vc_handle_mmio
  - arch/x86/kernel/sev.c:vc_handle_mmio
  - arch/x86/kernel/sev.c:vc_handle_mmio
  - arch/x86/kernel/sev.c:vc_handle_mmio_twobyte_ops
  - arch/x86/kernel/sev.c:vc_handle_mmio_twobyte_ops
```
**Symbols:**

```
ffffffff81092ef0-ffffffff81092fe7: vc_do_mmio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
enum es_result vc_do_mmio(struct ghcb *ghcb, struct es_em_ctxt *ctxt, unsigned int bytes, bool read);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff810a5450)
Location: arch/x86/kernel/sev.c:1437
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:vc_handle_mmio
  - arch/x86/kernel/sev.c:vc_handle_mmio
  - arch/x86/kernel/sev.c:vc_handle_mmio
  - arch/x86/kernel/sev.c:vc_handle_mmio
```
**Symbols:**

```
ffffffff810a5450-ffffffff810a5560: vc_do_mmio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
enum es_result vc_do_mmio(struct ghcb *ghcb, struct es_em_ctxt *ctxt, unsigned int bytes, bool read);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff810bdbe0)
Location: arch/x86/kernel/sev.c:1437
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:vc_handle_mmio
  - arch/x86/kernel/sev.c:vc_handle_mmio
  - arch/x86/kernel/sev.c:vc_handle_mmio
  - arch/x86/kernel/sev.c:vc_handle_mmio
```
**Symbols:**

```
ffffffff810bdbe0-ffffffff810bdcee: vc_do_mmio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
enum es_result vc_do_mmio(struct ghcb *ghcb, struct es_em_ctxt *ctxt, unsigned int bytes, bool read);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff810c1250)
Location: arch/x86/kernel/sev.c:1394
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:vc_handle_mmio
  - arch/x86/kernel/sev.c:vc_handle_mmio
  - arch/x86/kernel/sev.c:vc_handle_mmio
  - arch/x86/kernel/sev.c:vc_handle_mmio
```
**Symbols:**

```
ffffffff810c1250-ffffffff810c135e: vc_do_mmio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
enum es_result vc_do_mmio(struct ghcb *ghcb, struct es_em_ctxt *ctxt, unsigned int bytes, bool read);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff810c86b0)
Location: arch/x86/kernel/sev.c:1423
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:vc_handle_mmio
  - arch/x86/kernel/sev.c:vc_handle_mmio
  - arch/x86/kernel/sev.c:vc_handle_mmio
  - arch/x86/kernel/sev.c:vc_handle_mmio
```
**Symbols:**

```
ffffffff810c86b0-ffffffff810c87be: vc_do_mmio (STB_LOCAL)
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
