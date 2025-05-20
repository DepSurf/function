# Function: <code>vc_handle_mmio</code>

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
enum es_result vc_handle_mmio(struct ghcb *ghcb, struct es_em_ctxt *ctxt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev-es.c (ffffffff81083b40)
Location: arch/x86/kernel/sev-es.c:924
Inline: False
Direct callers:
  - arch/x86/kernel/sev-es.c:vc_handle_exitcode
```
**Symbols:**

```
ffffffff81083b40-ffffffff81083eae: vc_handle_mmio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
enum es_result vc_handle_mmio(struct ghcb *ghcb, struct es_em_ctxt *ctxt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff810840a0)
Location: arch/x86/kernel/sev.c:1003
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:vc_handle_exitcode
```
**Symbols:**

```
ffffffff810840a0-ffffffff81084507: vc_handle_mmio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
enum es_result vc_handle_mmio(struct ghcb *ghcb, struct es_em_ctxt *ctxt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff81093260)
Location: arch/x86/kernel/sev.c:999
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:vc_handle_exitcode
```
**Symbols:**

```
ffffffff81093260-ffffffff810936c7: vc_handle_mmio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
enum es_result vc_handle_mmio(struct ghcb *ghcb, struct es_em_ctxt *ctxt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff810a5560)
Location: arch/x86/kernel/sev.c:1536
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:vc_handle_exitcode
```
**Symbols:**

```
ffffffff810a5560-ffffffff810a592f: vc_handle_mmio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
enum es_result vc_handle_mmio(struct ghcb *ghcb, struct es_em_ctxt *ctxt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/sev.c (0)
Location: arch/x86/kernel/sev.c:1536
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:vc_handle_exitcode
```
**Symbols:**

```
ffffffff810bdd00-ffffffff810be190: vc_handle_mmio (STB_LOCAL)
ffffffff820546aa-ffffffff820546e2: vc_handle_mmio.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
enum es_result vc_handle_mmio(struct ghcb *ghcb, struct es_em_ctxt *ctxt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/sev.c (0)
Location: arch/x86/kernel/sev.c:1493
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:vc_handle_exitcode
```
**Symbols:**

```
ffffffff810c1370-ffffffff810c181b: vc_handle_mmio (STB_LOCAL)
ffffffff820d2ca3-ffffffff820d2cdb: vc_handle_mmio.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
enum es_result vc_handle_mmio(struct ghcb *ghcb, struct es_em_ctxt *ctxt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/sev.c (0)
Location: arch/x86/kernel/sev.c:1522
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:vc_handle_exitcode
```
**Symbols:**

```
ffffffff810c87d0-ffffffff810c8c9d: vc_handle_mmio (STB_LOCAL)
ffffffff821adb05-ffffffff821adb3d: vc_handle_mmio.cold (STB_LOCAL)
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
