# Function: <code>handle_swbp</code>

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
In kernel/events/uprobes.c (ffffffff81188ca5)
Location: kernel/events/uprobes.c:1857
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
In kernel/events/uprobes.c (ffffffff8119b375)
Location: kernel/events/uprobes.c:1868
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
In kernel/events/uprobes.c (ffffffff811aad69)
Location: kernel/events/uprobes.c:1870
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
In kernel/events/uprobes.c (ffffffff811b21d0)
Location: kernel/events/uprobes.c:1876
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
In kernel/events/uprobes.c (ffffffff811c5de0)
Location: kernel/events/uprobes.c:1876
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
In kernel/events/uprobes.c (ffffffff811e6362)
Location: kernel/events/uprobes.c:1876
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
In kernel/events/uprobes.c (ffffffff811f6eb2)
Location: kernel/events/uprobes.c:2146
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
void handle_swbp(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/events/uprobes.c (0)
Location: kernel/events/uprobes.c:2134
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
```
**Symbols:**

```
ffffffff8120ef10-ffffffff8120f477: handle_swbp (STB_LOCAL)
ffffffff8120f818-ffffffff8120f833: handle_swbp.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void handle_swbp(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/events/uprobes.c (0)
Location: kernel/events/uprobes.c:2186
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
```
**Symbols:**

```
ffffffff8121c1c0-ffffffff8121cb30: handle_swbp (STB_LOCAL)
ffffffff8121ce11-ffffffff8121ce63: handle_swbp.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void handle_swbp(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81248d40)
Location: kernel/events/uprobes.c:2188
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
```
**Symbols:**

```
ffffffff81248d40-ffffffff81248ec0: handle_swbp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void handle_swbp(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81253450)
Location: kernel/events/uprobes.c:2188
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
```
**Symbols:**

```
ffffffff81253450-ffffffff812535d0: handle_swbp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void handle_swbp(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/events/uprobes.c (0)
Location: kernel/events/uprobes.c:2186
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
```
**Symbols:**

```
ffffffff81257740-ffffffff81257be5: handle_swbp (STB_LOCAL)
ffffffff81bd8602-ffffffff81bd861d: handle_swbp.cold (STB_LOCAL)
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
In kernel/events/uprobes.c (ffffffff812935b4)
Location: kernel/events/uprobes.c:2187
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
In kernel/events/uprobes.c (ffffffff812e9087)
Location: kernel/events/uprobes.c:2182
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
In kernel/events/uprobes.c (ffffffff81352c4f)
Location: kernel/events/uprobes.c:2187
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
In kernel/events/uprobes.c (ffffffff81383e5f)
Location: kernel/events/uprobes.c:2183
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
In kernel/events/uprobes.c (ffffffff813ad2af)
Location: kernel/events/uprobes.c:2183
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
In kernel/events/uprobes.c (ffff8000102a8080)
Location: kernel/events/uprobes.c:2186
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void handle_swbp(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (c04d6c64)
Location: kernel/events/uprobes.c:2186
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
```
**Symbols:**

```
c04d6c64-c04d75ac: handle_swbp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void handle_swbp(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (c00000000035b230)
Location: kernel/events/uprobes.c:2186
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
```
**Symbols:**

```
c00000000035b230-c00000000035be04: handle_swbp (STB_LOCAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void handle_swbp(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/events/uprobes.c (0)
Location: kernel/events/uprobes.c:2186
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
```
**Symbols:**

```
ffffffff81214810-ffffffff81215180: handle_swbp (STB_LOCAL)
ffffffff81215461-ffffffff812154b3: handle_swbp.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void handle_swbp(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/events/uprobes.c (0)
Location: kernel/events/uprobes.c:2186
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
```
**Symbols:**

```
ffffffff81207580-ffffffff81207ef0: handle_swbp (STB_LOCAL)
ffffffff812081c1-ffffffff81208213: handle_swbp.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void handle_swbp(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/events/uprobes.c (0)
Location: kernel/events/uprobes.c:2186
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
```
**Symbols:**

```
ffffffff812125b0-ffffffff81212f20: handle_swbp (STB_LOCAL)
ffffffff81213201-ffffffff81213253: handle_swbp.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void handle_swbp(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/events/uprobes.c (0)
Location: kernel/events/uprobes.c:2186
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
```
**Symbols:**

```
ffffffff81221530-ffffffff81221e8f: handle_swbp (STB_LOCAL)
ffffffff8122219f-ffffffff812221f1: handle_swbp.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
