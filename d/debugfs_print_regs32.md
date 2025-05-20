# Function: <code>debugfs_print_regs32</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void debugfs_print_regs32(struct seq_file *s, const struct debugfs_reg32 *regs, int nregs, void *base, char *prefix);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff8131ea80)
Location: fs/debugfs/file.c:719
Inline: False
Direct callers:
  - fs/debugfs/file.c:debugfs_show_regset32
```
**Symbols:**

```
ffffffff8131ea80-ffffffff8131eb06: debugfs_print_regs32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void debugfs_print_regs32(struct seq_file *s, const struct debugfs_reg32 *regs, int nregs, void *base, char *prefix);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff81353cf0)
Location: fs/debugfs/file.c:1024
Inline: False
Direct callers:
  - fs/debugfs/file.c:debugfs_show_regset32
```
**Symbols:**

```
ffffffff81353cf0-ffffffff81353d74: debugfs_print_regs32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void debugfs_print_regs32(struct seq_file *s, const struct debugfs_reg32 *regs, int nregs, void *base, char *prefix);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff81369fa0)
Location: fs/debugfs/file.c:1021
Inline: False
Direct callers:
  - fs/debugfs/file.c:debugfs_show_regset32
```
**Symbols:**

```
ffffffff81369fa0-ffffffff8136a024: debugfs_print_regs32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void debugfs_print_regs32(struct seq_file *s, const struct debugfs_reg32 *regs, int nregs, void *base, char *prefix);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff8137e610)
Location: fs/debugfs/file.c:1021
Inline: False
Direct callers:
  - fs/debugfs/file.c:debugfs_show_regset32
```
**Symbols:**

```
ffffffff8137e610-ffffffff8137e695: debugfs_print_regs32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void debugfs_print_regs32(struct seq_file *s, const struct debugfs_reg32 *regs, int nregs, void *base, char *prefix);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff813a3210)
Location: fs/debugfs/file.c:1064
Inline: False
Direct callers:
  - fs/debugfs/file.c:debugfs_show_regset32
```
**Symbols:**

```
ffffffff813a3210-ffffffff813a3295: debugfs_print_regs32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void debugfs_print_regs32(struct seq_file *s, const struct debugfs_reg32 *regs, int nregs, void *base, char *prefix);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff813d25b0)
Location: fs/debugfs/file.c:1079
Inline: False
Direct callers:
  - fs/debugfs/file.c:debugfs_show_regset32
```
**Symbols:**

```
ffffffff813d25b0-ffffffff813d2634: debugfs_print_regs32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void debugfs_print_regs32(struct seq_file *s, const struct debugfs_reg32 *regs, int nregs, void *base, char *prefix);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff813ecca0)
Location: fs/debugfs/file.c:1081
Inline: False
Direct callers:
  - fs/debugfs/file.c:debugfs_show_regset32
```
**Symbols:**

```
ffffffff813ecca0-ffffffff813ecd24: debugfs_print_regs32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void debugfs_print_regs32(struct seq_file *s, const struct debugfs_reg32 *regs, int nregs, void *base, char *prefix);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff81418e00)
Location: fs/debugfs/file.c:1069
Inline: False
Direct callers:
  - fs/debugfs/file.c:debugfs_show_regset32
```
**Symbols:**

```
ffffffff81418e00-ffffffff81418e86: debugfs_print_regs32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void debugfs_print_regs32(struct seq_file *s, const struct debugfs_reg32 *regs, int nregs, void *base, char *prefix);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff81432cc0)
Location: fs/debugfs/file.c:1072
Inline: False
Direct callers:
  - fs/debugfs/file.c:debugfs_show_regset32
```
**Symbols:**

```
ffffffff81432cc0-ffffffff81432d46: debugfs_print_regs32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void debugfs_print_regs32(struct seq_file *s, const struct debugfs_reg32 *regs, int nregs, void *base, char *prefix);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff81482a26)
Location: fs/debugfs/file.c:1045
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_show_regset32
```
**Symbols:**

```
ffffffff814822e0-ffffffff81482362: debugfs_print_regs32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void debugfs_print_regs32(struct seq_file *s, const struct debugfs_reg32 *regs, int nregs, void *base, char *prefix);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff814a00b6)
Location: fs/debugfs/file.c:1032
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_show_regset32
```
**Symbols:**

```
ffffffff8149f980-ffffffff8149fa02: debugfs_print_regs32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void debugfs_print_regs32(struct seq_file *s, const struct debugfs_reg32 *regs, int nregs, void *base, char *prefix);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff814a6186)
Location: fs/debugfs/file.c:1122
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_show_regset32
```
**Symbols:**

```
ffffffff814a5980-ffffffff814a5a02: debugfs_print_regs32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void debugfs_print_regs32(struct seq_file *s, const struct debugfs_reg32 *regs, int nregs, void *base, char *prefix);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff814fe8d6)
Location: fs/debugfs/file.c:1108
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_show_regset32
```
**Symbols:**

```
ffffffff814fdb40-ffffffff814fdbc2: debugfs_print_regs32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void debugfs_print_regs32(struct seq_file *s, const struct debugfs_reg32 *regs, int nregs, void *base, char *prefix);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff8158f616)
Location: fs/debugfs/file.c:1108
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_show_regset32
```
**Symbols:**

```
ffffffff8158e6b0-ffffffff8158e758: debugfs_print_regs32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void debugfs_print_regs32(struct seq_file *s, const struct debugfs_reg32 *regs, int nregs, void *base, char *prefix);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff81636866)
Location: fs/debugfs/file.c:1124
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_regset32_show
```
**Symbols:**

```
ffffffff816356e0-ffffffff81635788: debugfs_print_regs32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void debugfs_print_regs32(struct seq_file *s, const struct debugfs_reg32 *regs, int nregs, void *base, char *prefix);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff8166ec46)
Location: fs/debugfs/file.c:1116
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_regset32_show
```
**Symbols:**

```
ffffffff8166d9f0-ffffffff8166da98: debugfs_print_regs32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void debugfs_print_regs32(struct seq_file *s, const struct debugfs_reg32 *regs, int nregs, void *base, char *prefix);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff816a96b6)
Location: fs/debugfs/file.c:1270
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_regset32_show
```
**Symbols:**

```
ffffffff816a8140-ffffffff816a81e8: debugfs_print_regs32 (STB_GLOBAL)
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
void debugfs_print_regs32(struct seq_file *s, const struct debugfs_reg32 *regs, int nregs, void *base, char *prefix);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffff8000105183e8)
Location: fs/debugfs/file.c:1072
Inline: False
Direct callers:
  - fs/debugfs/file.c:debugfs_show_regset32
```
**Symbols:**

```
ffff8000105183e8-ffff8000105184b0: debugfs_print_regs32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void debugfs_print_regs32(struct seq_file *s, const struct debugfs_reg32 *regs, int nregs, void *base, char *prefix);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (c06d2954)
Location: fs/debugfs/file.c:1072
Inline: False
Direct callers:
  - fs/debugfs/file.c:debugfs_show_regset32
```
**Symbols:**

```
c06d2954-c06d2a00: debugfs_print_regs32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void debugfs_print_regs32(struct seq_file *s, const struct debugfs_reg32 *regs, int nregs, void *base, char *prefix);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (c000000000661400)
Location: fs/debugfs/file.c:1072
Inline: False
Direct callers:
  - fs/debugfs/file.c:debugfs_show_regset32
```
**Symbols:**

```
c000000000661400-c000000000661580: debugfs_print_regs32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void debugfs_print_regs32(struct seq_file *s, const struct debugfs_reg32 *regs, int nregs, void *base, char *prefix);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffe0003818bc)
Location: fs/debugfs/file.c:1072
Inline: False
Direct callers:
  - fs/debugfs/file.c:debugfs_show_regset32
```
**Symbols:**

```
ffffffe0003818bc-ffffffe00038195e: debugfs_print_regs32 (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void debugfs_print_regs32(struct seq_file *s, const struct debugfs_reg32 *regs, int nregs, void *base, char *prefix);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff8142b2a0)
Location: fs/debugfs/file.c:1072
Inline: False
Direct callers:
  - fs/debugfs/file.c:debugfs_show_regset32
```
**Symbols:**

```
ffffffff8142b2a0-ffffffff8142b326: debugfs_print_regs32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void debugfs_print_regs32(struct seq_file *s, const struct debugfs_reg32 *regs, int nregs, void *base, char *prefix);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff8141bd20)
Location: fs/debugfs/file.c:1072
Inline: False
Direct callers:
  - fs/debugfs/file.c:debugfs_show_regset32
```
**Symbols:**

```
ffffffff8141bd20-ffffffff8141bda6: debugfs_print_regs32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void debugfs_print_regs32(struct seq_file *s, const struct debugfs_reg32 *regs, int nregs, void *base, char *prefix);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff81427440)
Location: fs/debugfs/file.c:1072
Inline: False
Direct callers:
  - fs/debugfs/file.c:debugfs_show_regset32
```
**Symbols:**

```
ffffffff81427440-ffffffff814274c6: debugfs_print_regs32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void debugfs_print_regs32(struct seq_file *s, const struct debugfs_reg32 *regs, int nregs, void *base, char *prefix);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff8143e300)
Location: fs/debugfs/file.c:1072
Inline: False
Direct callers:
  - fs/debugfs/file.c:debugfs_show_regset32
```
**Symbols:**

```
ffffffff8143e300-ffffffff8143e386: debugfs_print_regs32 (STB_GLOBAL)
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
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
