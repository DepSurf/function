# Function: <code>find_uprobe</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct uprobe *find_uprobe(struct inode *inode, loff_t offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81186fa0)
Location: kernel/events/uprobes.c:415
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_unregister
  - kernel/events/uprobes.c:uprobe_apply
  - kernel/events/uprobes.c:uprobe_notify_resume
```
**Symbols:**

```
ffffffff81186fa0-ffffffff81186fe2: find_uprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct uprobe *find_uprobe(struct inode *inode, loff_t offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff811994c0)
Location: kernel/events/uprobes.c:417
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_unregister
  - kernel/events/uprobes.c:uprobe_apply
```
**Symbols:**

```
ffffffff811994c0-ffffffff81199502: find_uprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct uprobe *find_uprobe(struct inode *inode, loff_t offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff811a8eb0)
Location: kernel/events/uprobes.c:418
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_unregister
  - kernel/events/uprobes.c:uprobe_apply
```
**Symbols:**

```
ffffffff811a8eb0-ffffffff811a8ef2: find_uprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct uprobe *find_uprobe(struct inode *inode, loff_t offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff811b06c0)
Location: kernel/events/uprobes.c:426
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_unregister
  - kernel/events/uprobes.c:uprobe_apply
```
**Symbols:**

```
ffffffff811b06c0-ffffffff811b0702: find_uprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct uprobe *find_uprobe(struct inode *inode, loff_t offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff811c41d0)
Location: kernel/events/uprobes.c:426
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_unregister
  - kernel/events/uprobes.c:uprobe_apply
```
**Symbols:**

```
ffffffff811c41d0-ffffffff811c4212: find_uprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct uprobe *find_uprobe(struct inode *inode, loff_t offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff811e4690)
Location: kernel/events/uprobes.c:426
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_unregister
  - kernel/events/uprobes.c:uprobe_apply
```
**Symbols:**

```
ffffffff811e4690-ffffffff811e46d2: find_uprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct uprobe *find_uprobe(struct inode *inode, loff_t offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff811f4cc0)
Location: kernel/events/uprobes.c:624
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_apply
  - kernel/events/uprobes.c:uprobe_unregister
```
**Symbols:**

```
ffffffff811f4cc0-ffffffff811f4d02: find_uprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct uprobe *find_uprobe(struct inode *inode, loff_t offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff8120c9c0)
Location: kernel/events/uprobes.c:612
Inline: False
Direct callers:
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:uprobe_apply
  - kernel/events/uprobes.c:uprobe_unregister
```
**Symbols:**

```
ffffffff8120c9c0-ffffffff8120ca04: find_uprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct uprobe *find_uprobe(struct inode *inode, loff_t offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81219cb0)
Location: kernel/events/uprobes.c:664
Inline: False
Direct callers:
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:uprobe_apply
  - kernel/events/uprobes.c:uprobe_unregister
```
**Symbols:**

```
ffffffff81219cb0-ffffffff81219cf4: find_uprobe (STB_LOCAL)
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
In kernel/events/uprobes.c (ffffffff812470eb)
Location: kernel/events/uprobes.c:658
Inline: True
Inline callers:
  - kernel/events/uprobes.c:find_active_uprobe
  - kernel/events/uprobes.c:uprobe_apply
  - kernel/events/uprobes.c:uprobe_unregister
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
In kernel/events/uprobes.c (ffffffff81251769)
Location: kernel/events/uprobes.c:658
Inline: True
Inline callers:
  - kernel/events/uprobes.c:find_active_uprobe
  - kernel/events/uprobes.c:uprobe_apply
  - kernel/events/uprobes.c:uprobe_unregister
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct uprobe *find_uprobe(struct inode *inode, loff_t offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81254ef0)
Location: kernel/events/uprobes.c:673
Inline: False
Direct callers:
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:uprobe_apply
  - kernel/events/uprobes.c:uprobe_unregister
```
**Symbols:**

```
ffffffff81254ef0-ffffffff81254f8e: find_uprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct uprobe *find_uprobe(struct inode *inode, loff_t offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81290930)
Location: kernel/events/uprobes.c:674
Inline: False
Direct callers:
  - kernel/events/uprobes.c:find_active_uprobe
  - kernel/events/uprobes.c:uprobe_apply
  - kernel/events/uprobes.c:uprobe_unregister
```
**Symbols:**

```
ffffffff81290930-ffffffff812909ce: find_uprobe (STB_LOCAL)
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
In kernel/events/uprobes.c (ffffffff812e66ac)
Location: kernel/events/uprobes.c:668
Inline: True
Inline callers:
  - kernel/events/uprobes.c:find_active_uprobe
  - kernel/events/uprobes.c:uprobe_apply
  - kernel/events/uprobes.c:uprobe_unregister
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
In kernel/events/uprobes.c (ffffffff81350185)
Location: kernel/events/uprobes.c:671
Inline: True
Inline callers:
  - kernel/events/uprobes.c:find_active_uprobe
  - kernel/events/uprobes.c:uprobe_apply
  - kernel/events/uprobes.c:uprobe_unregister
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
In kernel/events/uprobes.c (ffffffff81381355)
Location: kernel/events/uprobes.c:668
Inline: True
Inline callers:
  - kernel/events/uprobes.c:find_active_uprobe
  - kernel/events/uprobes.c:uprobe_apply
  - kernel/events/uprobes.c:uprobe_unregister
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
In kernel/events/uprobes.c (ffffffff813aa705)
Location: kernel/events/uprobes.c:668
Inline: True
Inline callers:
  - kernel/events/uprobes.c:find_active_uprobe
  - kernel/events/uprobes.c:uprobe_apply
  - kernel/events/uprobes.c:uprobe_unregister
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
struct uprobe *find_uprobe(struct inode *inode, loff_t offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffff8000102a4ed0)
Location: kernel/events/uprobes.c:664
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_apply
  - kernel/events/uprobes.c:uprobe_unregister
```
**Symbols:**

```
ffff8000102a4ed0-ffff8000102a4f70: find_uprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct uprobe *find_uprobe(struct inode *inode, loff_t offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (c04d4524)
Location: kernel/events/uprobes.c:664
Inline: False
Direct callers:
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:uprobe_apply
  - kernel/events/uprobes.c:uprobe_unregister
```
**Symbols:**

```
c04d4524-c04d4580: find_uprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct uprobe *find_uprobe(struct inode *inode, loff_t offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (c000000000357a20)
Location: kernel/events/uprobes.c:664
Inline: False
Direct callers:
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:uprobe_apply
  - kernel/events/uprobes.c:uprobe_unregister
```
**Symbols:**

```
c000000000357a20-c000000000357aec: find_uprobe (STB_LOCAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
struct uprobe *find_uprobe(struct inode *inode, loff_t offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81212300)
Location: kernel/events/uprobes.c:664
Inline: False
Direct callers:
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:uprobe_apply
  - kernel/events/uprobes.c:uprobe_unregister
```
**Symbols:**

```
ffffffff81212300-ffffffff81212344: find_uprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct uprobe *find_uprobe(struct inode *inode, loff_t offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81205090)
Location: kernel/events/uprobes.c:664
Inline: False
Direct callers:
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:uprobe_apply
  - kernel/events/uprobes.c:uprobe_unregister
```
**Symbols:**

```
ffffffff81205090-ffffffff812050d4: find_uprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct uprobe *find_uprobe(struct inode *inode, loff_t offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff812100a0)
Location: kernel/events/uprobes.c:664
Inline: False
Direct callers:
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:uprobe_apply
  - kernel/events/uprobes.c:uprobe_unregister
```
**Symbols:**

```
ffffffff812100a0-ffffffff812100e4: find_uprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct uprobe *find_uprobe(struct inode *inode, loff_t offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff8121efc0)
Location: kernel/events/uprobes.c:664
Inline: False
Direct callers:
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:uprobe_apply
  - kernel/events/uprobes.c:uprobe_unregister
```
**Symbols:**

```
ffffffff8121efc0-ffffffff8121f002: find_uprobe (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
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
