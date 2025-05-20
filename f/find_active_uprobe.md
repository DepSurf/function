# Function: <code>find_active_uprobe</code>

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
In kernel/events/uprobes.c (ffffffff81188ce0)
Location: kernel/events/uprobes.c:1713
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
In kernel/events/uprobes.c (ffffffff8119b3b0)
Location: kernel/events/uprobes.c:1724
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
In kernel/events/uprobes.c (ffffffff811aada4)
Location: kernel/events/uprobes.c:1726
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
In kernel/events/uprobes.c (ffffffff811b220b)
Location: kernel/events/uprobes.c:1732
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
In kernel/events/uprobes.c (ffffffff811c5e1b)
Location: kernel/events/uprobes.c:1732
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
In kernel/events/uprobes.c (ffffffff811e639d)
Location: kernel/events/uprobes.c:1732
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
In kernel/events/uprobes.c (ffffffff811f6eed)
Location: kernel/events/uprobes.c:2002
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
In kernel/events/uprobes.c (ffffffff8120ef6d)
Location: kernel/events/uprobes.c:1990
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
In kernel/events/uprobes.c (ffffffff8121c21d)
Location: kernel/events/uprobes.c:2042
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
struct uprobe *find_active_uprobe(long unsigned int bp_vaddr, int *is_swbp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81246fc0)
Location: kernel/events/uprobes.c:2044
Inline: False
Direct callers:
  - kernel/events/uprobes.c:handle_swbp
```
**Symbols:**

```
ffffffff81246fc0-ffffffff8124711e: find_active_uprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct uprobe *find_active_uprobe(long unsigned int bp_vaddr, int *is_swbp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81251600)
Location: kernel/events/uprobes.c:2044
Inline: False
Direct callers:
  - kernel/events/uprobes.c:handle_swbp
```
**Symbols:**

```
ffffffff81251600-ffffffff8125179c: find_active_uprobe (STB_LOCAL)
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
In kernel/events/uprobes.c (ffffffff8125779d)
Location: kernel/events/uprobes.c:2042
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handle_swbp
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct uprobe *find_active_uprobe(long unsigned int bp_vaddr, int *is_swbp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81291030)
Location: kernel/events/uprobes.c:2043
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
```
**Symbols:**

```
ffffffff81291030-ffffffff8129129a: find_active_uprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct uprobe *find_active_uprobe(long unsigned int bp_vaddr, int *is_swbp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff812e6510)
Location: kernel/events/uprobes.c:2038
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
```
**Symbols:**

```
ffffffff812e6510-ffffffff812e685b: find_active_uprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct uprobe *find_active_uprobe(long unsigned int bp_vaddr, int *is_swbp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81350000)
Location: kernel/events/uprobes.c:2043
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
```
**Symbols:**

```
ffffffff81350000-ffffffff8135033f: find_active_uprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct uprobe *find_active_uprobe(long unsigned int bp_vaddr, int *is_swbp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff813811d0)
Location: kernel/events/uprobes.c:2039
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
```
**Symbols:**

```
ffffffff813811d0-ffffffff81381533: find_active_uprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct uprobe *find_active_uprobe(long unsigned int bp_vaddr, int *is_swbp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff813aa580)
Location: kernel/events/uprobes.c:2039
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
```
**Symbols:**

```
ffffffff813aa580-ffffffff813aa8df: find_active_uprobe (STB_LOCAL)
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
In kernel/events/uprobes.c (ffff8000102a80b0)
Location: kernel/events/uprobes.c:2042
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
In kernel/events/uprobes.c (c04d6cc8)
Location: kernel/events/uprobes.c:2042
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
In kernel/events/uprobes.c (c00000000035b2a0)
Location: kernel/events/uprobes.c:2042
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
In kernel/events/uprobes.c (ffffffff8121486d)
Location: kernel/events/uprobes.c:2042
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
In kernel/events/uprobes.c (ffffffff812075dd)
Location: kernel/events/uprobes.c:2042
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
In kernel/events/uprobes.c (ffffffff8121260d)
Location: kernel/events/uprobes.c:2042
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
In kernel/events/uprobes.c (ffffffff8122158d)
Location: kernel/events/uprobes.c:2042
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
