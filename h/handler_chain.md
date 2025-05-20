# Function: <code>handler_chain</code>

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
In kernel/events/uprobes.c (ffffffff81188f45)
Location: kernel/events/uprobes.c:1742
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
In kernel/events/uprobes.c (ffffffff8119b628)
Location: kernel/events/uprobes.c:1753
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
In kernel/events/uprobes.c (ffffffff811ab01c)
Location: kernel/events/uprobes.c:1755
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
In kernel/events/uprobes.c (ffffffff811b2599)
Location: kernel/events/uprobes.c:1761
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
In kernel/events/uprobes.c (ffffffff811c61af)
Location: kernel/events/uprobes.c:1761
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
In kernel/events/uprobes.c (ffffffff811e6657)
Location: kernel/events/uprobes.c:1761
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
In kernel/events/uprobes.c (ffffffff811f71b6)
Location: kernel/events/uprobes.c:2031
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void handler_chain(struct uprobe *uprobe, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/events/uprobes.c (0)
Location: kernel/events/uprobes.c:2019
Inline: False
Direct callers:
  - kernel/events/uprobes.c:handle_swbp
```
**Symbols:**

```
ffffffff8120eb80-ffffffff8120ef07: handler_chain (STB_LOCAL)
ffffffff8120f7ce-ffffffff8120f818: handler_chain.cold (STB_LOCAL)
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
In kernel/events/uprobes.c (ffffffff8121c329)
Location: kernel/events/uprobes.c:2071
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handle_swbp
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void handler_chain(struct uprobe *uprobe, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81248c30)
Location: kernel/events/uprobes.c:2073
Inline: False
Direct callers:
  - kernel/events/uprobes.c:handle_swbp
```
**Symbols:**

```
ffffffff81248c30-ffffffff81248d39: handler_chain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void handler_chain(struct uprobe *uprobe, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81253340)
Location: kernel/events/uprobes.c:2073
Inline: False
Direct callers:
  - kernel/events/uprobes.c:handle_swbp
```
**Symbols:**

```
ffffffff81253340-ffffffff81253449: handler_chain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void handler_chain(struct uprobe *uprobe, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81257530)
Location: kernel/events/uprobes.c:2071
Inline: False
Direct callers:
  - kernel/events/uprobes.c:handle_swbp
```
**Symbols:**

```
ffffffff81257530-ffffffff8125773c: handler_chain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void handler_chain(struct uprobe *uprobe, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff812932c0)
Location: kernel/events/uprobes.c:2072
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
```
**Symbols:**

```
ffffffff812932c0-ffffffff812934c8: handler_chain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void handler_chain(struct uprobe *uprobe, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff812e8da0)
Location: kernel/events/uprobes.c:2067
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
```
**Symbols:**

```
ffffffff812e8da0-ffffffff812e8f96: handler_chain (STB_LOCAL)
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
In kernel/events/uprobes.c (ffffffff81352d14)
Location: kernel/events/uprobes.c:2072
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
In kernel/events/uprobes.c (ffffffff81383f23)
Location: kernel/events/uprobes.c:2068
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
In kernel/events/uprobes.c (ffffffff813ad353)
Location: kernel/events/uprobes.c:2068
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
<summary>In <code>arm64</code>: ✅</summary>

```c
void handler_chain(struct uprobe *uprobe, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffff8000102a7bb0)
Location: kernel/events/uprobes.c:2071
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
```
**Symbols:**

```
ffff8000102a7bb0-ffff8000102a7f54: handler_chain (STB_LOCAL)
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
In kernel/events/uprobes.c (c04d6d80)
Location: kernel/events/uprobes.c:2071
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
In kernel/events/uprobes.c (c00000000035b3e4)
Location: kernel/events/uprobes.c:2071
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
In kernel/events/uprobes.c (ffffffff81214979)
Location: kernel/events/uprobes.c:2071
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
In kernel/events/uprobes.c (ffffffff812076e9)
Location: kernel/events/uprobes.c:2071
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
In kernel/events/uprobes.c (ffffffff81212719)
Location: kernel/events/uprobes.c:2071
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
In kernel/events/uprobes.c (ffffffff81221699)
Location: kernel/events/uprobes.c:2071
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
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
