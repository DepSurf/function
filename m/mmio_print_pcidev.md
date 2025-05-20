# Function: <code>mmio_print_pcidev</code>

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
In kernel/trace/trace_mmiotrace.c (ffffffff81158a78)
Location: kernel/trace/trace_mmiotrace.c:62
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_read
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
In kernel/trace/trace_mmiotrace.c (ffffffff8116331e)
Location: kernel/trace/trace_mmiotrace.c:62
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_read
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
In kernel/trace/trace_mmiotrace.c (ffffffff8116e64e)
Location: kernel/trace/trace_mmiotrace.c:62
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_read
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
In kernel/trace/trace_mmiotrace.c (ffffffff8117188e)
Location: kernel/trace/trace_mmiotrace.c:62
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_read
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
In kernel/trace/trace_mmiotrace.c (ffffffff8117ea1e)
Location: kernel/trace/trace_mmiotrace.c:63
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_read
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
In kernel/trace/trace_mmiotrace.c (ffffffff8118db22)
Location: kernel/trace/trace_mmiotrace.c:63
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_read
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
In kernel/trace/trace_mmiotrace.c (ffffffff8119b502)
Location: kernel/trace/trace_mmiotrace.c:63
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_read
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
In kernel/trace/trace_mmiotrace.c (ffffffff811a90c2)
Location: kernel/trace/trace_mmiotrace.c:63
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_read
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
In kernel/trace/trace_mmiotrace.c (ffffffff811b48f2)
Location: kernel/trace/trace_mmiotrace.c:63
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_read
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void mmio_print_pcidev(struct trace_seq *s, const struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_mmiotrace.c (ffffffff811cd060)
Location: kernel/trace/trace_mmiotrace.c:63
Inline: False
Direct callers:
  - kernel/trace/trace_mmiotrace.c:mmio_read
```
**Symbols:**

```
ffffffff811cd060-ffffffff811cd164: mmio_print_pcidev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void mmio_print_pcidev(struct trace_seq *s, const struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_mmiotrace.c (ffffffff811ca550)
Location: kernel/trace/trace_mmiotrace.c:63
Inline: False
Direct callers:
  - kernel/trace/trace_mmiotrace.c:mmio_read
```
**Symbols:**

```
ffffffff811ca550-ffffffff811ca654: mmio_print_pcidev (STB_LOCAL)
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
In kernel/trace/trace_mmiotrace.c (ffffffff811cba8e)
Location: kernel/trace/trace_mmiotrace.c:61
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_read
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_mmiotrace.c (ffffffff811f7f21)
Location: kernel/trace/trace_mmiotrace.c:61
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_read
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_mmiotrace.c (ffffffff81231bcf)
Location: kernel/trace/trace_mmiotrace.c:61
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_read
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
In kernel/trace/trace_mmiotrace.c (ffffffff8127e1df)
Location: kernel/trace/trace_mmiotrace.c:61
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_read
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
In kernel/trace/trace_mmiotrace.c (ffffffff8129ac5f)
Location: kernel/trace/trace_mmiotrace.c:61
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_read
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
In kernel/trace/trace_mmiotrace.c (ffffffff812b62df)
Location: kernel/trace/trace_mmiotrace.c:61
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_read
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
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_mmiotrace.c (ffffffff811acf12)
Location: kernel/trace/trace_mmiotrace.c:63
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_read
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
In kernel/trace/trace_mmiotrace.c (ffffffff8119fda2)
Location: kernel/trace/trace_mmiotrace.c:63
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_read
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
In kernel/trace/trace_mmiotrace.c (ffffffff811aace2)
Location: kernel/trace/trace_mmiotrace.c:63
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_read
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
In kernel/trace/trace_mmiotrace.c (ffffffff811b8b42)
Location: kernel/trace/trace_mmiotrace.c:63
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_read
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
