# Function: <code>console_emit_next_record</code>

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
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:2676
Inline: True
Direct callers:
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:console_unlock
```
**Symbols:**

```
ffffffff8115ce70-ffffffff8115d178: console_emit_next_record.constprop.0 (STB_LOCAL)
ffffffff81e5c6ef-ffffffff81e5c76e: console_emit_next_record.constprop.0.cold (STB_LOCAL)
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
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:2769
Inline: True
Direct callers:
  - kernel/printk/printk.c:console_flush_all
  - kernel/printk/printk.c:console_flush_all
```
**Symbols:**

```
ffffffff8118f9b0-ffffffff8118fcf9: console_emit_next_record.constprop.0 (STB_LOCAL)
ffffffff82058997-ffffffff82058a0e: console_emit_next_record.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool console_emit_next_record(struct console *con, bool *handover, int cookie);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:2831
Inline: False
Direct callers:
  - kernel/printk/printk.c:console_flush_all
```
**Symbols:**

```
ffffffff811a1490-ffffffff811a165b: console_emit_next_record (STB_LOCAL)
ffffffff820d72a0-ffffffff820d72b4: console_emit_next_record.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool console_emit_next_record(struct console *con, bool *handover, int cookie);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:2857
Inline: False
Direct callers:
  - kernel/printk/printk.c:console_flush_all
```
**Symbols:**

```
ffffffff811b1bb0-ffffffff811b1d7b: console_emit_next_record (STB_LOCAL)
ffffffff821b260a-ffffffff821b261e: console_emit_next_record.cold (STB_LOCAL)
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
