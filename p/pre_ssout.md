# Function: <code>pre_ssout</code>

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
In kernel/events/uprobes.c (ffffffff8118905c)
Location: kernel/events/uprobes.c:1607
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
In kernel/events/uprobes.c (ffffffff8119b749)
Location: kernel/events/uprobes.c:1613
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
In kernel/events/uprobes.c (ffffffff811ab13d)
Location: kernel/events/uprobes.c:1614
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
In kernel/events/uprobes.c (ffffffff811b26b6)
Location: kernel/events/uprobes.c:1620
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
In kernel/events/uprobes.c (ffffffff811c62cd)
Location: kernel/events/uprobes.c:1620
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
In kernel/events/uprobes.c (ffffffff811e68dd)
Location: kernel/events/uprobes.c:1620
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
In kernel/events/uprobes.c (ffffffff811f7439)
Location: kernel/events/uprobes.c:1890
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
In kernel/events/uprobes.c (ffffffff8120f079)
Location: kernel/events/uprobes.c:1878
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
In kernel/events/uprobes.c (ffffffff8121c7a4)
Location: kernel/events/uprobes.c:1930
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
int pre_ssout(struct uprobe *uprobe, struct pt_regs *regs, long unsigned int bp_vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff812484b0)
Location: kernel/events/uprobes.c:1929
Inline: False
Direct callers:
  - kernel/events/uprobes.c:handle_swbp
```
**Symbols:**

```
ffffffff812484b0-ffffffff812485e2: pre_ssout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pre_ssout(struct uprobe *uprobe, struct pt_regs *regs, long unsigned int bp_vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81252bc0)
Location: kernel/events/uprobes.c:1929
Inline: False
Direct callers:
  - kernel/events/uprobes.c:handle_swbp
```
**Symbols:**

```
ffffffff81252bc0-ffffffff81252cf2: pre_ssout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pre_ssout(struct uprobe *uprobe, struct pt_regs *regs, long unsigned int bp_vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81256d30)
Location: kernel/events/uprobes.c:1927
Inline: False
Direct callers:
  - kernel/events/uprobes.c:handle_swbp
```
**Symbols:**

```
ffffffff81256d30-ffffffff81256f19: pre_ssout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pre_ssout(struct uprobe *uprobe, struct pt_regs *regs, long unsigned int bp_vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81292ac0)
Location: kernel/events/uprobes.c:1928
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
```
**Symbols:**

```
ffffffff81292ac0-ffffffff81292ca9: pre_ssout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pre_ssout(struct uprobe *uprobe, struct pt_regs *regs, long unsigned int bp_vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff812e84e0)
Location: kernel/events/uprobes.c:1923
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
```
**Symbols:**

```
ffffffff812e84e0-ffffffff812e86fa: pre_ssout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pre_ssout(struct uprobe *uprobe, struct pt_regs *regs, long unsigned int bp_vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81352180)
Location: kernel/events/uprobes.c:1927
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
```
**Symbols:**

```
ffffffff81352180-ffffffff81352399: pre_ssout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pre_ssout(struct uprobe *uprobe, struct pt_regs *regs, long unsigned int bp_vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81383390)
Location: kernel/events/uprobes.c:1924
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
```
**Symbols:**

```
ffffffff81383390-ffffffff813835a9: pre_ssout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pre_ssout(struct uprobe *uprobe, struct pt_regs *regs, long unsigned int bp_vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff813ac7c0)
Location: kernel/events/uprobes.c:1924
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
```
**Symbols:**

```
ffffffff813ac7c0-ffffffff813ac9a1: pre_ssout (STB_LOCAL)
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
In kernel/events/uprobes.c (ffff8000102a835c)
Location: kernel/events/uprobes.c:1930
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
In kernel/events/uprobes.c (c04d7318)
Location: kernel/events/uprobes.c:1930
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
In kernel/events/uprobes.c (c00000000035b944)
Location: kernel/events/uprobes.c:1930
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
In kernel/events/uprobes.c (ffffffff81214df4)
Location: kernel/events/uprobes.c:1930
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
In kernel/events/uprobes.c (ffffffff81207b64)
Location: kernel/events/uprobes.c:1930
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
In kernel/events/uprobes.c (ffffffff81212b94)
Location: kernel/events/uprobes.c:1930
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
In kernel/events/uprobes.c (ffffffff81221b14)
Location: kernel/events/uprobes.c:1930
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
