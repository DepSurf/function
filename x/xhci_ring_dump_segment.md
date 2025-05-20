# Function: <code>xhci_ring_dump_segment</code>

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
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-debugfs.c (ffffffff8177578a)
Location: drivers/usb/host/xhci-debugfs.c:193
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_trb_show
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-debugfs.c (ffffffff817b6b01)
Location: drivers/usb/host/xhci-debugfs.c:194
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_trb_show
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-debugfs.c (ffffffff817dd211)
Location: drivers/usb/host/xhci-debugfs.c:194
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_trb_show
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-debugfs.c (0)
Location: drivers/usb/host/xhci-debugfs.c:194
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_trb_show
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-debugfs.c (0)
Location: drivers/usb/host/xhci-debugfs.c:194
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_trb_show
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-debugfs.c (ffffffff81920fed)
Location: drivers/usb/host/xhci-debugfs.c:194
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_trb_show
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-debugfs.c (ffffffff8192859d)
Location: drivers/usb/host/xhci-debugfs.c:195
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_trb_show
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
In drivers/usb/host/xhci-debugfs.c (ffffffff8190bc2d)
Location: drivers/usb/host/xhci-debugfs.c:195
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_trb_show
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void xhci_ring_dump_segment(struct seq_file *s, struct xhci_segment *seg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-debugfs.c (ffffffff819ad0d0)
Location: drivers/usb/host/xhci-debugfs.c:195
Inline: False
Direct callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_trb_show
```
**Symbols:**

```
ffffffff819ad0d0-ffffffff819ad171: xhci_ring_dump_segment (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void xhci_ring_dump_segment(struct seq_file *s, struct xhci_segment *seg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-debugfs.c (ffffffff81b0b690)
Location: drivers/usb/host/xhci-debugfs.c:195
Inline: False
Direct callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_trb_show
```
**Symbols:**

```
ffffffff81b0b690-ffffffff81b0b774: xhci_ring_dump_segment (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void xhci_ring_dump_segment(struct seq_file *s, struct xhci_segment *seg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-debugfs.c (ffffffff81c9b5f0)
Location: drivers/usb/host/xhci-debugfs.c:195
Inline: False
Direct callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_trb_show
```
**Symbols:**

```
ffffffff81c9b5f0-ffffffff81c9b6d4: xhci_ring_dump_segment (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void xhci_ring_dump_segment(struct seq_file *s, struct xhci_segment *seg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-debugfs.c (ffffffff81d029d0)
Location: drivers/usb/host/xhci-debugfs.c:196
Inline: False
Direct callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_trb_show
```
**Symbols:**

```
ffffffff81d029d0-ffffffff81d02ab4: xhci_ring_dump_segment (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void xhci_ring_dump_segment(struct seq_file *s, struct xhci_segment *seg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-debugfs.c (ffffffff81db8500)
Location: drivers/usb/host/xhci-debugfs.c:196
Inline: False
Direct callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_trb_show
```
**Symbols:**

```
ffffffff81db8500-ffffffff81db85eb: xhci_ring_dump_segment (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-debugfs.c (0)
Location: drivers/usb/host/xhci-debugfs.c:194
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_trb_show
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-debugfs.c (0)
Location: drivers/usb/host/xhci-debugfs.c:194
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_trb_show
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-debugfs.c (0)
Location: drivers/usb/host/xhci-debugfs.c:194
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_trb_show
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-debugfs.c (ffffffe0006a2900)
Location: drivers/usb/host/xhci-debugfs.c:194
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_trb_show
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-debugfs.c (0)
Location: drivers/usb/host/xhci-debugfs.c:194
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_trb_show
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-debugfs.c (0)
Location: drivers/usb/host/xhci-debugfs.c:194
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_trb_show
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-debugfs.c (0)
Location: drivers/usb/host/xhci-debugfs.c:194
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_trb_show
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-debugfs.c (0)
Location: drivers/usb/host/xhci-debugfs.c:194
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_trb_show
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
