# Function: <code>uprobe_apply</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int uprobe_apply(struct inode *inode, loff_t offset, struct uprobe_consumer *uc, bool add);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff811882f0)
Location: kernel/events/uprobes.c:917
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
```
**Symbols:**

```
ffffffff811882f0-ffffffff811883a8: uprobe_apply (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int uprobe_apply(struct inode *inode, loff_t offset, struct uprobe_consumer *uc, bool add);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff8119a990)
Location: kernel/events/uprobes.c:919
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
```
**Symbols:**

```
ffffffff8119a990-ffffffff8119aa4b: uprobe_apply (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int uprobe_apply(struct inode *inode, loff_t offset, struct uprobe_consumer *uc, bool add);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff811aa100)
Location: kernel/events/uprobes.c:920
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
```
**Symbols:**

```
ffffffff811aa100-ffffffff811aa1bb: uprobe_apply (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int uprobe_apply(struct inode *inode, loff_t offset, struct uprobe_consumer *uc, bool add);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff811b16e0)
Location: kernel/events/uprobes.c:928
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
```
**Symbols:**

```
ffffffff811b16e0-ffffffff811b178c: uprobe_apply (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int uprobe_apply(struct inode *inode, loff_t offset, struct uprobe_consumer *uc, bool add);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff811c52c0)
Location: kernel/events/uprobes.c:928
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
```
**Symbols:**

```
ffffffff811c52c0-ffffffff811c536c: uprobe_apply (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int uprobe_apply(struct inode *inode, loff_t offset, struct uprobe_consumer *uc, bool add);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff811e5800)
Location: kernel/events/uprobes.c:927
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
```
**Symbols:**

```
ffffffff811e5800-ffffffff811e58aa: uprobe_apply (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int uprobe_apply(struct inode *inode, loff_t offset, struct uprobe_consumer *uc, bool add);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff811f6200)
Location: kernel/events/uprobes.c:1177
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
```
**Symbols:**

```
ffffffff811f6200-ffffffff811f62aa: uprobe_apply (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int uprobe_apply(struct inode *inode, loff_t offset, struct uprobe_consumer *uc, bool add);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/events/uprobes.c (0)
Location: kernel/events/uprobes.c:1165
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
```
**Symbols:**

```
ffffffff8120f748-ffffffff8120f761: uprobe_apply.cold (STB_LOCAL)
ffffffff8120dfa0-ffffffff8120e035: uprobe_apply (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int uprobe_apply(struct inode *inode, loff_t offset, struct uprobe_consumer *uc, bool add);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff8121b5d0)
Location: kernel/events/uprobes.c:1217
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:uprobe_perf_close
```
**Symbols:**

```
ffffffff8121b5d0-ffffffff8121b677: uprobe_apply (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int uprobe_apply(struct inode *inode, loff_t offset, struct uprobe_consumer *uc, bool add);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81247e60)
Location: kernel/events/uprobes.c:1216
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:uprobe_perf_open
  - kernel/trace/trace_uprobe.c:uprobe_perf_close
```
**Symbols:**

```
ffffffff81247e60-ffffffff81247f2d: uprobe_apply (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int uprobe_apply(struct inode *inode, loff_t offset, struct uprobe_consumer *uc, bool add);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81252570)
Location: kernel/events/uprobes.c:1216
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:uprobe_perf_open
  - kernel/trace/trace_uprobe.c:uprobe_perf_close
```
**Symbols:**

```
ffffffff81252570-ffffffff8125263d: uprobe_apply (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int uprobe_apply(struct inode *inode, loff_t offset, struct uprobe_consumer *uc, bool add);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff812563b0)
Location: kernel/events/uprobes.c:1214
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
  - kernel/trace/trace_uprobe.c:uprobe_perf_close
```
**Symbols:**

```
ffffffff812563b0-ffffffff81256454: uprobe_apply (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int uprobe_apply(struct inode *inode, loff_t offset, struct uprobe_consumer *uc, bool add);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81292070)
Location: kernel/events/uprobes.c:1215
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
  - kernel/trace/trace_uprobe.c:uprobe_perf_close
```
**Symbols:**

```
ffffffff81292070-ffffffff81292114: uprobe_apply (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int uprobe_apply(struct inode *inode, loff_t offset, struct uprobe_consumer *uc, bool add);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff812e78d0)
Location: kernel/events/uprobes.c:1210
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
  - kernel/trace/trace_uprobe.c:uprobe_perf_close
```
**Symbols:**

```
ffffffff812e78d0-ffffffff812e79b4: uprobe_apply (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int uprobe_apply(struct inode *inode, loff_t offset, struct uprobe_consumer *uc, bool add);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff813515b0)
Location: kernel/events/uprobes.c:1213
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
  - kernel/trace/trace_uprobe.c:uprobe_perf_close
```
**Symbols:**

```
ffffffff813515b0-ffffffff81351694: uprobe_apply (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int uprobe_apply(struct inode *inode, loff_t offset, struct uprobe_consumer *uc, bool add);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81382820)
Location: kernel/events/uprobes.c:1210
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
  - kernel/trace/trace_uprobe.c:uprobe_perf_close
```
**Symbols:**

```
ffffffff81382820-ffffffff81382904: uprobe_apply (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int uprobe_apply(struct inode *inode, loff_t offset, struct uprobe_consumer *uc, bool add);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff813abbf0)
Location: kernel/events/uprobes.c:1210
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
  - kernel/trace/trace_uprobe.c:uprobe_perf_close
```
**Symbols:**

```
ffffffff813abbf0-ffffffff813abcd4: uprobe_apply (STB_GLOBAL)
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
int uprobe_apply(struct inode *inode, loff_t offset, struct uprobe_consumer *uc, bool add);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffff8000102a6d80)
Location: kernel/events/uprobes.c:1217
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:uprobe_perf_close
```
**Symbols:**

```
ffff8000102a6d80-ffff8000102a6e54: uprobe_apply (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int uprobe_apply(struct inode *inode, loff_t offset, struct uprobe_consumer *uc, bool add);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (c04d5ecc)
Location: kernel/events/uprobes.c:1217
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:uprobe_perf_close
```
**Symbols:**

```
c04d5ecc-c04d5f80: uprobe_apply (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int uprobe_apply(struct inode *inode, loff_t offset, struct uprobe_consumer *uc, bool add);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (c00000000035a000)
Location: kernel/events/uprobes.c:1217
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:uprobe_perf_close
```
**Symbols:**

```
c00000000035a000-c00000000035a0f8: uprobe_apply (STB_GLOBAL)
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
int uprobe_apply(struct inode *inode, loff_t offset, struct uprobe_consumer *uc, bool add);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81213c20)
Location: kernel/events/uprobes.c:1217
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:uprobe_perf_close
```
**Symbols:**

```
ffffffff81213c20-ffffffff81213cc7: uprobe_apply (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int uprobe_apply(struct inode *inode, loff_t offset, struct uprobe_consumer *uc, bool add);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81206990)
Location: kernel/events/uprobes.c:1217
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:uprobe_perf_close
```
**Symbols:**

```
ffffffff81206990-ffffffff81206a37: uprobe_apply (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int uprobe_apply(struct inode *inode, loff_t offset, struct uprobe_consumer *uc, bool add);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff812119c0)
Location: kernel/events/uprobes.c:1217
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:uprobe_perf_close
```
**Symbols:**

```
ffffffff812119c0-ffffffff81211a67: uprobe_apply (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int uprobe_apply(struct inode *inode, loff_t offset, struct uprobe_consumer *uc, bool add);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81220910)
Location: kernel/events/uprobes.c:1217
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:uprobe_perf_close
```
**Symbols:**

```
ffffffff81220910-ffffffff812209b7: uprobe_apply (STB_GLOBAL)
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
