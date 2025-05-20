# Function: <code>handle_trampoline</code>

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
In kernel/events/uprobes.c (ffffffff81188e53)
Location: kernel/events/uprobes.c:1800
Inline: True
Inline callers:
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
In kernel/events/uprobes.c (ffffffff8119b521)
Location: kernel/events/uprobes.c:1811
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
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
In kernel/events/uprobes.c (ffffffff811aaf15)
Location: kernel/events/uprobes.c:1813
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
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
In kernel/events/uprobes.c (ffffffff811b234d)
Location: kernel/events/uprobes.c:1819
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
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
In kernel/events/uprobes.c (ffffffff811c5f60)
Location: kernel/events/uprobes.c:1819
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
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
In kernel/events/uprobes.c (ffffffff811e6468)
Location: kernel/events/uprobes.c:1819
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
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
In kernel/events/uprobes.c (ffffffff811f6fb8)
Location: kernel/events/uprobes.c:2089
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
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
In kernel/events/uprobes.c (ffffffff8120f104)
Location: kernel/events/uprobes.c:2077
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handle_swbp
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
In kernel/events/uprobes.c (ffffffff8121c3ec)
Location: kernel/events/uprobes.c:2129
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handle_swbp
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void handle_trampoline(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/events/uprobes.c (0)
Location: kernel/events/uprobes.c:2131
Inline: False
Direct callers:
  - kernel/events/uprobes.c:handle_swbp
```
**Symbols:**

```
ffffffff81248850-ffffffff81248995: handle_trampoline (STB_LOCAL)
ffffffff81249196-ffffffff812491b1: handle_trampoline.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void handle_trampoline(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/events/uprobes.c (0)
Location: kernel/events/uprobes.c:2131
Inline: False
Direct callers:
  - kernel/events/uprobes.c:handle_swbp
```
**Symbols:**

```
ffffffff81252f60-ffffffff812530a5: handle_trampoline (STB_LOCAL)
ffffffff81be68d1-ffffffff81be68ec: handle_trampoline.cold (STB_LOCAL)
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
In kernel/events/uprobes.c (ffffffff8125795f)
Location: kernel/events/uprobes.c:2129
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handle_swbp
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
In kernel/events/uprobes.c (ffffffff812936a5)
Location: kernel/events/uprobes.c:2130
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
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
In kernel/events/uprobes.c (ffffffff812e917f)
Location: kernel/events/uprobes.c:2125
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
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
In kernel/events/uprobes.c (ffffffff81352d94)
Location: kernel/events/uprobes.c:2130
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
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
In kernel/events/uprobes.c (ffffffff81383fa1)
Location: kernel/events/uprobes.c:2126
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
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
In kernel/events/uprobes.c (ffffffff813ad3d1)
Location: kernel/events/uprobes.c:2126
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
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
In kernel/events/uprobes.c (ffff8000102a81bc)
Location: kernel/events/uprobes.c:2129
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
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
In kernel/events/uprobes.c (c04d7074)
Location: kernel/events/uprobes.c:2129
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handle_swbp
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
In kernel/events/uprobes.c (c00000000035b5d0)
Location: kernel/events/uprobes.c:2129
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handle_swbp
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81214a3c)
Location: kernel/events/uprobes.c:2129
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handle_swbp
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
In kernel/events/uprobes.c (ffffffff812077ac)
Location: kernel/events/uprobes.c:2129
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handle_swbp
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
In kernel/events/uprobes.c (ffffffff812127dc)
Location: kernel/events/uprobes.c:2129
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handle_swbp
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
In kernel/events/uprobes.c (ffffffff8122175c)
Location: kernel/events/uprobes.c:2129
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handle_swbp
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
