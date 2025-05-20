# Function: <code>__uprobe_register</code>

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
In kernel/events/uprobes.c (ffffffff81188131)
Location: kernel/events/uprobes.c:834
Inline: True
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
In kernel/events/uprobes.c (ffffffff8119a7d0)
Location: kernel/events/uprobes.c:836
Inline: True
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
In kernel/events/uprobes.c (ffffffff811a9f40)
Location: kernel/events/uprobes.c:837
Inline: True
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
In kernel/events/uprobes.c (ffffffff811b154d)
Location: kernel/events/uprobes.c:845
Inline: True
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
In kernel/events/uprobes.c (ffffffff811c512d)
Location: kernel/events/uprobes.c:845
Inline: True
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
In kernel/events/uprobes.c (ffffffff811e565c)
Location: kernel/events/uprobes.c:843
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __uprobe_register(struct inode *inode, loff_t offset, loff_t ref_ctr_offset, struct uprobe_consumer *uc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/uprobes.c (0)
Location: kernel/events/uprobes.c:1112
Inline: True
Direct callers:
  - kernel/events/uprobes.c:uprobe_register_refctr
  - kernel/events/uprobes.c:uprobe_register
```
**Symbols:**

```
ffffffff811f5f00-ffffffff811f61c4: __uprobe_register (STB_LOCAL)
ffffffff811f7906-ffffffff811f7948: __uprobe_register.cold.41 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __uprobe_register(struct inode *inode, loff_t offset, loff_t ref_ctr_offset, struct uprobe_consumer *uc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/uprobes.c (0)
Location: kernel/events/uprobes.c:1100
Inline: True
Direct callers:
  - kernel/events/uprobes.c:uprobe_register_refctr
  - kernel/events/uprobes.c:uprobe_register
```
**Symbols:**

```
ffffffff8120dc90-ffffffff8120df70: __uprobe_register (STB_LOCAL)
ffffffff8120f70c-ffffffff8120f748: __uprobe_register.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __uprobe_register(struct inode *inode, loff_t offset, loff_t ref_ctr_offset, struct uprobe_consumer *uc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/uprobes.c (0)
Location: kernel/events/uprobes.c:1152
Inline: True
Direct callers:
  - kernel/events/uprobes.c:uprobe_register_refctr
  - kernel/events/uprobes.c:uprobe_register
```
**Symbols:**

```
ffffffff8121b2c0-ffffffff8121b5a0: __uprobe_register (STB_LOCAL)
ffffffff8121cd68-ffffffff8121cda4: __uprobe_register.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __uprobe_register(struct inode *inode, loff_t offset, loff_t ref_ctr_offset, struct uprobe_consumer *uc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81247bf0)
Location: kernel/events/uprobes.c:1142
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_register_refctr
  - kernel/events/uprobes.c:uprobe_register
```
**Symbols:**

```
ffffffff81247bf0-ffffffff81247d58: __uprobe_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __uprobe_register(struct inode *inode, loff_t offset, loff_t ref_ctr_offset, struct uprobe_consumer *uc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff812522c0)
Location: kernel/events/uprobes.c:1142
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_register_refctr
  - kernel/events/uprobes.c:uprobe_register
```
**Symbols:**

```
ffffffff812522c0-ffffffff81252420: __uprobe_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __uprobe_register(struct inode *inode, loff_t offset, loff_t ref_ctr_offset, struct uprobe_consumer *uc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81256220)
Location: kernel/events/uprobes.c:1140
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_register_refctr
  - kernel/events/uprobes.c:uprobe_register
```
**Symbols:**

```
ffffffff81256220-ffffffff81256380: __uprobe_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __uprobe_register(struct inode *inode, loff_t offset, loff_t ref_ctr_offset, struct uprobe_consumer *uc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81291ed0)
Location: kernel/events/uprobes.c:1141
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_register_refctr
  - kernel/events/uprobes.c:uprobe_register
```
**Symbols:**

```
ffffffff81291ed0-ffffffff81292033: __uprobe_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __uprobe_register(struct inode *inode, loff_t offset, loff_t ref_ctr_offset, struct uprobe_consumer *uc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff812e76f0)
Location: kernel/events/uprobes.c:1135
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_register_refctr
  - kernel/events/uprobes.c:uprobe_register
```
**Symbols:**

```
ffffffff812e76f0-ffffffff812e7873: __uprobe_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __uprobe_register(struct inode *inode, loff_t offset, loff_t ref_ctr_offset, struct uprobe_consumer *uc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81351240)
Location: kernel/events/uprobes.c:1138
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_register_refctr
  - kernel/events/uprobes.c:uprobe_register
```
**Symbols:**

```
ffffffff81351240-ffffffff813513c3: __uprobe_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __uprobe_register(struct inode *inode, loff_t offset, loff_t ref_ctr_offset, struct uprobe_consumer *uc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff813824b0)
Location: kernel/events/uprobes.c:1135
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_register_refctr
  - kernel/events/uprobes.c:uprobe_register
```
**Symbols:**

```
ffffffff813824b0-ffffffff81382630: __uprobe_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __uprobe_register(struct inode *inode, loff_t offset, loff_t ref_ctr_offset, struct uprobe_consumer *uc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff813ab890)
Location: kernel/events/uprobes.c:1135
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_register_refctr
  - kernel/events/uprobes.c:uprobe_register
```
**Symbols:**

```
ffffffff813ab890-ffffffff813aba10: __uprobe_register (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int __uprobe_register(struct inode *inode, loff_t offset, loff_t ref_ctr_offset, struct uprobe_consumer *uc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffff8000102a69c0)
Location: kernel/events/uprobes.c:1152
Inline: True
Direct callers:
  - kernel/events/uprobes.c:uprobe_register_refctr
  - kernel/events/uprobes.c:uprobe_register
```
**Symbols:**

```
ffff8000102a69c0-ffff8000102a6ce4: __uprobe_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int __uprobe_register(struct inode *inode, loff_t offset, loff_t ref_ctr_offset, struct uprobe_consumer *uc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (c04d5b00)
Location: kernel/events/uprobes.c:1152
Inline: True
Direct callers:
  - kernel/events/uprobes.c:uprobe_register_refctr
  - kernel/events/uprobes.c:uprobe_register
```
**Symbols:**

```
c04d5b00-c04d5e60: __uprobe_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int __uprobe_register(struct inode *inode, loff_t offset, loff_t ref_ctr_offset, struct uprobe_consumer *uc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (c000000000359b40)
Location: kernel/events/uprobes.c:1152
Inline: True
Direct callers:
  - kernel/events/uprobes.c:uprobe_register_refctr
  - kernel/events/uprobes.c:uprobe_register
```
**Symbols:**

```
c000000000359b40-c000000000359fb8: __uprobe_register (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __uprobe_register(struct inode *inode, loff_t offset, loff_t ref_ctr_offset, struct uprobe_consumer *uc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/uprobes.c (0)
Location: kernel/events/uprobes.c:1152
Inline: True
Direct callers:
  - kernel/events/uprobes.c:uprobe_register_refctr
  - kernel/events/uprobes.c:uprobe_register
```
**Symbols:**

```
ffffffff81213910-ffffffff81213bf0: __uprobe_register (STB_LOCAL)
ffffffff812153b8-ffffffff812153f4: __uprobe_register.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __uprobe_register(struct inode *inode, loff_t offset, loff_t ref_ctr_offset, struct uprobe_consumer *uc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/uprobes.c (0)
Location: kernel/events/uprobes.c:1152
Inline: True
Direct callers:
  - kernel/events/uprobes.c:uprobe_register_refctr
  - kernel/events/uprobes.c:uprobe_register
```
**Symbols:**

```
ffffffff81206680-ffffffff81206960: __uprobe_register (STB_LOCAL)
ffffffff81208118-ffffffff81208154: __uprobe_register.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __uprobe_register(struct inode *inode, loff_t offset, loff_t ref_ctr_offset, struct uprobe_consumer *uc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/uprobes.c (0)
Location: kernel/events/uprobes.c:1152
Inline: True
Direct callers:
  - kernel/events/uprobes.c:uprobe_register_refctr
  - kernel/events/uprobes.c:uprobe_register
```
**Symbols:**

```
ffffffff812116b0-ffffffff81211990: __uprobe_register (STB_LOCAL)
ffffffff81213158-ffffffff81213194: __uprobe_register.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __uprobe_register(struct inode *inode, loff_t offset, loff_t ref_ctr_offset, struct uprobe_consumer *uc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/uprobes.c (0)
Location: kernel/events/uprobes.c:1152
Inline: True
Direct callers:
  - kernel/events/uprobes.c:uprobe_register_refctr
  - kernel/events/uprobes.c:uprobe_register
```
**Symbols:**

```
ffffffff81220600-ffffffff812208d6: __uprobe_register (STB_LOCAL)
ffffffff812220f8-ffffffff81222132: __uprobe_register.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
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
