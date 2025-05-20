# Function: <code>__wake_up_klogd</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (ffffffff8115f44a)
Location: kernel/printk/printk.c:3472
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_deferred
  - kernel/printk/printk.c:printk_trigger_flush
  - kernel/printk/printk.c:vprintk_emit
Direct callers:
  - kernel/printk/printk.c:vprintk_deferred
  - kernel/printk/printk.c:printk_trigger_flush
  - kernel/printk/printk.c:vprintk_emit
```
**Symbols:**

```
ffffffff8115bce0-ffffffff8115bd4a: __wake_up_klogd.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (ffffffff81192719)
Location: kernel/printk/printk.c:3735
Inline: True
Inline callers:
  - kernel/printk/printk.c:_printk_deferred
  - kernel/printk/printk.c:printk_trigger_flush
  - kernel/printk/printk.c:vprintk_emit
Direct callers:
  - kernel/printk/printk.c:_printk_deferred
  - kernel/printk/printk.c:printk_trigger_flush
  - kernel/printk/printk.c:vprintk_emit
```
**Symbols:**

```
ffffffff8118e730-ffffffff8118e79a: __wake_up_klogd.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (ffffffff811a3fb9)
Location: kernel/printk/printk.c:3776
Inline: True
Inline callers:
  - kernel/printk/printk.c:_printk_deferred
  - kernel/printk/printk.c:printk_trigger_flush
  - kernel/printk/printk.c:vprintk_emit
Direct callers:
  - kernel/printk/printk.c:_printk_deferred
  - kernel/printk/printk.c:printk_trigger_flush
  - kernel/printk/printk.c:vprintk_emit
```
**Symbols:**

```
ffffffff811a0090-ffffffff811a00fa: __wake_up_klogd.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (ffffffff811b3535)
Location: kernel/printk/printk.c:3877
Inline: True
Inline callers:
  - kernel/printk/printk.c:printk_trigger_flush
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
Direct callers:
  - kernel/printk/printk.c:printk_trigger_flush
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
```
**Symbols:**

```
ffffffff811af090-ffffffff811af0fa: __wake_up_klogd.part.0 (STB_LOCAL)
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
