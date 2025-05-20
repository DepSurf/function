# Function: <code>vc_handle_mmio_twobyte_ops</code>

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
enum es_result vc_handle_mmio_twobyte_ops(struct ghcb *ghcb, struct es_em_ctxt *ctxt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev-es.c (ffffffff810838d0)
Location: arch/x86/kernel/sev-es.c:787
Inline: False
Direct callers:
  - arch/x86/kernel/sev-es.c:vc_handle_mmio
```
**Symbols:**

```
ffffffff810838d0-ffffffff81083b3e: vc_handle_mmio_twobyte_ops (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
enum es_result vc_handle_mmio_twobyte_ops(struct ghcb *ghcb, struct es_em_ctxt *ctxt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff81083e30)
Location: arch/x86/kernel/sev.c:866
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:vc_handle_mmio
```
**Symbols:**

```
ffffffff81083e30-ffffffff8108409f: vc_handle_mmio_twobyte_ops (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
enum es_result vc_handle_mmio_twobyte_ops(struct ghcb *ghcb, struct es_em_ctxt *ctxt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff81092ff0)
Location: arch/x86/kernel/sev.c:862
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:vc_handle_mmio
```
**Symbols:**

```
ffffffff81092ff0-ffffffff8109325f: vc_handle_mmio_twobyte_ops (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
</ul>
