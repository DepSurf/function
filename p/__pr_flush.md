# Function: <code>__pr_flush</code>

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
<summary>In <code>5.19</code>: ✅</summary>

```c
bool __pr_flush(struct console *con, int timeout_ms, bool reset_on_progress);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8115d370)
Location: kernel/printk/printk.c:3366
Inline: False
Direct callers:
  - kernel/printk/printk.c:console_start
  - kernel/printk/printk.c:console_stop
  - kernel/printk/printk.c:console_unblank
  - kernel/printk/printk.c:resume_console
  - kernel/printk/printk.c:suspend_console
```
**Symbols:**

```
ffffffff8115d370-ffffffff8115d510: __pr_flush (STB_LOCAL)
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
In kernel/printk/printk.c (ffffffff81190290)
Location: kernel/printk/printk.c:3622
Inline: True
Direct callers:
  - kernel/printk/printk.c:console_start
  - kernel/printk/printk.c:console_stop
  - kernel/printk/printk.c:console_unblank
  - kernel/printk/printk.c:resume_console
  - kernel/printk/printk.c:suspend_console
```
**Symbols:**

```
ffffffff81190290-ffffffff8119040c: __pr_flush.constprop.0.isra.0 (STB_LOCAL)
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
In kernel/printk/printk.c (ffffffff811a1a80)
Location: kernel/printk/printk.c:3663
Inline: True
Direct callers:
  - kernel/printk/printk.c:console_start
  - kernel/printk/printk.c:console_stop
  - kernel/printk/printk.c:console_unblank
  - kernel/printk/printk.c:resume_console
  - kernel/printk/printk.c:suspend_console
```
**Symbols:**

```
ffffffff811a1a80-ffffffff811a1bfc: __pr_flush.constprop.0.isra.0 (STB_LOCAL)
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
In kernel/printk/printk.c (ffffffff811b2680)
Location: kernel/printk/printk.c:3750
Inline: True
Direct callers:
  - kernel/printk/printk.c:console_start
  - kernel/printk/printk.c:console_stop
  - kernel/printk/printk.c:console_unblank
  - kernel/printk/printk.c:resume_console
  - kernel/printk/printk.c:suspend_console
```
**Symbols:**

```
ffffffff811b2680-ffffffff811b2918: __pr_flush.constprop.0.isra.0 (STB_LOCAL)
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
</ul>
