# Function: <code>uprobe_warn</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81187321)
Location: kernel/events/uprobes.c:1459
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_copy_process
  - kernel/events/uprobes.c:uprobe_copy_process
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_notify_resume
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff8119b91b)
Location: kernel/events/uprobes.c:1464
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_copy_process
  - kernel/events/uprobes.c:uprobe_copy_process
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff811ab308)
Location: kernel/events/uprobes.c:1465
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_copy_process
  - kernel/events/uprobes.c:uprobe_copy_process
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff811b27a3)
Location: kernel/events/uprobes.c:1471
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_copy_process
  - kernel/events/uprobes.c:uprobe_copy_process
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff811c63ba)
Location: kernel/events/uprobes.c:1471
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_copy_process
  - kernel/events/uprobes.c:uprobe_copy_process
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/uprobes.c (ffffffff811e6d15)
Location: kernel/events/uprobes.c:1471
Inline: True
Direct callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_copy_process
  - kernel/events/uprobes.c:uprobe_copy_process
```
**Symbols:**

```
ffffffff811e6d15-ffffffff811e6d45: uprobe_warn.isra.24 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/uprobes.c (ffffffff811f7875)
Location: kernel/events/uprobes.c:1741
Inline: True
Direct callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_copy_process
  - kernel/events/uprobes.c:uprobe_copy_process
```
**Symbols:**

```
ffffffff811f7875-ffffffff811f78a5: uprobe_warn.isra.26 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/uprobes.c (ffffffff8120f63b)
Location: kernel/events/uprobes.c:1729
Inline: True
Direct callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:handler_chain
  - kernel/events/uprobes.c:uprobe_copy_process
  - kernel/events/uprobes.c:uprobe_copy_process
```
**Symbols:**

```
ffffffff8120f63b-ffffffff8120f66b: uprobe_warn.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/uprobes.c (ffffffff8121ccd8)
Location: kernel/events/uprobes.c:1781
Inline: True
Direct callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:uprobe_copy_process
  - kernel/events/uprobes.c:uprobe_copy_process
```
**Symbols:**

```
ffffffff8121ccd8-ffffffff8121cd08: uprobe_warn.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/uprobes.c (ffffffff812490b4)
Location: kernel/events/uprobes.c:1780
Inline: True
Direct callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:handle_trampoline
  - kernel/events/uprobes.c:prepare_uretprobe
  - kernel/events/uprobes.c:uprobe_copy_process
  - kernel/events/uprobes.c:uprobe_copy_process
```
**Symbols:**

```
ffffffff812490b4-ffffffff812490e4: uprobe_warn.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81be67ef)
Location: kernel/events/uprobes.c:1780
Inline: True
Direct callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:handle_trampoline
  - kernel/events/uprobes.c:prepare_uretprobe
  - kernel/events/uprobes.c:uprobe_copy_process
  - kernel/events/uprobes.c:uprobe_copy_process
```
**Symbols:**

```
ffffffff81be67ef-ffffffff81be681f: uprobe_warn.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81bd84f0)
Location: kernel/events/uprobes.c:1778
Inline: True
Direct callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:prepare_uretprobe
  - kernel/events/uprobes.c:uprobe_copy_process
  - kernel/events/uprobes.c:uprobe_copy_process
```
**Symbols:**

```
ffffffff81bd84f0-ffffffff81bd8520: uprobe_warn.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81cb9a17)
Location: kernel/events/uprobes.c:1779
Inline: True
Direct callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:prepare_uretprobe
  - kernel/events/uprobes.c:uprobe_copy_process
  - kernel/events/uprobes.c:uprobe_copy_process
```
**Symbols:**

```
ffffffff81cb9a17-ffffffff81cb9a47: uprobe_warn.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81e6b001)
Location: kernel/events/uprobes.c:1774
Inline: True
Direct callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:prepare_uretprobe
  - kernel/events/uprobes.c:uprobe_copy_process
  - kernel/events/uprobes.c:uprobe_copy_process
```
**Symbols:**

```
ffffffff81e6b001-ffffffff81e6b03f: uprobe_warn.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81352fdc)
Location: kernel/events/uprobes.c:1778
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:prepare_uretprobe
  - kernel/events/uprobes.c:uprobe_copy_process
  - kernel/events/uprobes.c:uprobe_copy_process
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
In kernel/events/uprobes.c (ffffffff813841d8)
Location: kernel/events/uprobes.c:1775
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:prepare_uretprobe
  - kernel/events/uprobes.c:uprobe_copy_process
  - kernel/events/uprobes.c:uprobe_copy_process
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
In kernel/events/uprobes.c (ffffffff813ad5e6)
Location: kernel/events/uprobes.c:1775
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:prepare_uretprobe
  - kernel/events/uprobes.c:uprobe_copy_process
  - kernel/events/uprobes.c:uprobe_copy_process
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/uprobes.c (ffff8000102a8aa8)
Location: kernel/events/uprobes.c:1781
Inline: True
Direct callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:handler_chain
  - kernel/events/uprobes.c:uprobe_copy_process
  - kernel/events/uprobes.c:uprobe_copy_process
```
**Symbols:**

```
ffff8000102a8aa8-ffff8000102a8ae8: uprobe_warn.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/uprobes.c (c04d77ec)
Location: kernel/events/uprobes.c:1781
Inline: True
Direct callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:uprobe_copy_process
  - kernel/events/uprobes.c:uprobe_copy_process
```
**Symbols:**

```
c04d77ec-c04d782c: uprobe_warn.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/uprobes.c (c00000000035c088)
Location: kernel/events/uprobes.c:1781
Inline: True
Direct callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:uprobe_copy_process
```
**Symbols:**

```
c00000000035c088-c00000000035c0d4: uprobe_warn.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81215328)
Location: kernel/events/uprobes.c:1781
Inline: True
Direct callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:uprobe_copy_process
  - kernel/events/uprobes.c:uprobe_copy_process
```
**Symbols:**

```
ffffffff81215328-ffffffff81215358: uprobe_warn.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81208088)
Location: kernel/events/uprobes.c:1781
Inline: True
Direct callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:uprobe_copy_process
  - kernel/events/uprobes.c:uprobe_copy_process
```
**Symbols:**

```
ffffffff81208088-ffffffff812080b8: uprobe_warn.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/uprobes.c (ffffffff812130c8)
Location: kernel/events/uprobes.c:1781
Inline: True
Direct callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:uprobe_copy_process
  - kernel/events/uprobes.c:uprobe_copy_process
```
**Symbols:**

```
ffffffff812130c8-ffffffff812130f8: uprobe_warn.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81222068)
Location: kernel/events/uprobes.c:1781
Inline: True
Direct callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:uprobe_copy_process
  - kernel/events/uprobes.c:uprobe_copy_process
```
**Symbols:**

```
ffffffff81222068-ffffffff81222098: uprobe_warn.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
