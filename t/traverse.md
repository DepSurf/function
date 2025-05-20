# Function: <code>traverse</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int traverse(struct seq_file *m, loff_t offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff81230790)
Location: fs/seq_file.c:100
Inline: False
Direct callers:
  - fs/seq_file.c:seq_lseek
  - fs/seq_file.c:seq_read
```
**Symbols:**

```
ffffffff81230790-ffffffff81230974: traverse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int traverse(struct seq_file *m, loff_t offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff81258e20)
Location: fs/seq_file.c:101
Inline: False
Direct callers:
  - fs/seq_file.c:seq_lseek
  - fs/seq_file.c:seq_read
```
**Symbols:**

```
ffffffff81258e20-ffffffff81259004: traverse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int traverse(struct seq_file *m, loff_t offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff8126c2d0)
Location: fs/seq_file.c:101
Inline: False
Direct callers:
  - fs/seq_file.c:seq_lseek
  - fs/seq_file.c:seq_read
```
**Symbols:**

```
ffffffff8126c2d0-ffffffff8126c4b4: traverse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int traverse(struct seq_file *m, loff_t offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff81279a70)
Location: fs/seq_file.c:87
Inline: False
Direct callers:
  - fs/seq_file.c:seq_lseek
  - fs/seq_file.c:seq_read
```
**Symbols:**

```
ffffffff81279a70-ffffffff81279c81: traverse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int traverse(struct seq_file *m, loff_t offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff8129c4a0)
Location: fs/seq_file.c:88
Inline: False
Direct callers:
  - fs/seq_file.c:seq_lseek
  - fs/seq_file.c:seq_read
```
**Symbols:**

```
ffffffff8129c4a0-ffffffff8129c6cf: traverse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int traverse(struct seq_file *m, loff_t offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff812c2a70)
Location: fs/seq_file.c:91
Inline: False
Direct callers:
  - fs/seq_file.c:seq_lseek
  - fs/seq_file.c:seq_read
```
**Symbols:**

```
ffffffff812c2a70-ffffffff812c2c97: traverse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int traverse(struct seq_file *m, loff_t offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff812d8410)
Location: fs/seq_file.c:91
Inline: True
Direct callers:
  - fs/seq_file.c:seq_lseek
  - fs/seq_file.c:seq_read
```
**Symbols:**

```
ffffffff812d8410-ffffffff812d85eb: traverse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int traverse(struct seq_file *m, loff_t offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff812f6910)
Location: fs/seq_file.c:91
Inline: True
Direct callers:
  - fs/seq_file.c:seq_lseek
  - fs/seq_file.c:seq_read
```
**Symbols:**

```
ffffffff812f6910-ffffffff812f6af6: traverse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int traverse(struct seq_file *m, loff_t offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff813084e0)
Location: fs/seq_file.c:91
Inline: True
Direct callers:
  - fs/seq_file.c:seq_lseek
  - fs/seq_file.c:seq_read
```
**Symbols:**

```
ffffffff813084e0-ffffffff813086c6: traverse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/seq_file.c (ffffffff81341c92)
Location: fs/seq_file.c:86
Inline: True
Inline callers:
  - fs/seq_file.c:seq_lseek
  - fs/seq_file.c:seq_read
Direct callers:
  - fs/seq_file.c:seq_lseek
  - fs/seq_file.c:seq_read
```
**Symbols:**

```
ffffffff81341830-ffffffff813419a5: traverse.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/seq_file.c (ffffffff8134e352)
Location: fs/seq_file.c:87
Inline: True
Inline callers:
  - fs/seq_file.c:seq_lseek
  - fs/seq_file.c:seq_read_iter
Direct callers:
  - fs/seq_file.c:seq_lseek
  - fs/seq_file.c:seq_read_iter
```
**Symbols:**

```
ffffffff8134d8a0-ffffffff8134da03: traverse.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/seq_file.c (ffffffff81355432)
Location: fs/seq_file.c:90
Inline: True
Inline callers:
  - fs/seq_file.c:seq_lseek
  - fs/seq_file.c:seq_read_iter
Direct callers:
  - fs/seq_file.c:seq_lseek
  - fs/seq_file.c:seq_read_iter
```
**Symbols:**

```
ffffffff81354c20-ffffffff81354da1: traverse.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/seq_file.c (ffffffff813a3842)
Location: fs/seq_file.c:90
Inline: True
Inline callers:
  - fs/seq_file.c:seq_lseek
  - fs/seq_file.c:seq_read_iter
Direct callers:
  - fs/seq_file.c:seq_lseek
  - fs/seq_file.c:seq_read_iter
```
**Symbols:**

```
ffffffff813a3030-ffffffff813a31b1: traverse.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/seq_file.c (ffffffff81427598)
Location: fs/seq_file.c:90
Inline: True
Inline callers:
  - fs/seq_file.c:seq_lseek
  - fs/seq_file.c:seq_read_iter
Direct callers:
  - fs/seq_file.c:seq_lseek
  - fs/seq_file.c:seq_read_iter
```
**Symbols:**

```
ffffffff81426dc0-ffffffff81426f66: traverse.part.0.constprop.0 (STB_LOCAL)
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
In fs/seq_file.c (ffffffff814b4058)
Location: fs/seq_file.c:90
Inline: True
Inline callers:
  - fs/seq_file.c:seq_lseek
  - fs/seq_file.c:seq_read_iter
Direct callers:
  - fs/seq_file.c:seq_lseek
  - fs/seq_file.c:seq_read_iter
```
**Symbols:**

```
ffffffff814b3870-ffffffff814b3a16: traverse.part.0.constprop.0 (STB_LOCAL)
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
In fs/seq_file.c (ffffffff814e910c)
Location: fs/seq_file.c:90
Inline: True
Inline callers:
  - fs/seq_file.c:seq_lseek
  - fs/seq_file.c:seq_read_iter
Direct callers:
  - fs/seq_file.c:seq_lseek
  - fs/seq_file.c:seq_read_iter
```
**Symbols:**

```
ffffffff814e88f0-ffffffff814e8a96: traverse.part.0.constprop.0 (STB_LOCAL)
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
In fs/seq_file.c (ffffffff8151cfec)
Location: fs/seq_file.c:90
Inline: True
Inline callers:
  - fs/seq_file.c:seq_lseek
  - fs/seq_file.c:seq_read_iter
Direct callers:
  - fs/seq_file.c:seq_lseek
  - fs/seq_file.c:seq_read_iter
```
**Symbols:**

```
ffffffff8151c780-ffffffff8151c926: traverse.part.0.constprop.0 (STB_LOCAL)
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
int traverse(struct seq_file *m, loff_t offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffff8000103bc1e8)
Location: fs/seq_file.c:91
Inline: True
Direct callers:
  - fs/seq_file.c:seq_lseek
  - fs/seq_file.c:seq_read
```
**Symbols:**

```
ffff8000103bc1e8-ffff8000103bc398: traverse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int traverse(struct seq_file *m, loff_t offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (c0599914)
Location: fs/seq_file.c:91
Inline: True
Direct callers:
  - fs/seq_file.c:seq_lseek
  - fs/seq_file.c:seq_read
```
**Symbols:**

```
c0599914-c0599af8: traverse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int traverse(struct seq_file *m, loff_t offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (c0000000004b9870)
Location: fs/seq_file.c:91
Inline: True
Direct callers:
  - fs/seq_file.c:seq_lseek
  - fs/seq_file.c:seq_read
```
**Symbols:**

```
c0000000004b9870-c0000000004b9b2c: traverse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int traverse(struct seq_file *m, loff_t offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffe00027da6c)
Location: fs/seq_file.c:91
Inline: True
Direct callers:
  - fs/seq_file.c:seq_lseek
  - fs/seq_file.c:seq_read
```
**Symbols:**

```
ffffffe00027da6c-ffffffe00027dba4: traverse (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int traverse(struct seq_file *m, loff_t offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff81300ac0)
Location: fs/seq_file.c:91
Inline: True
Direct callers:
  - fs/seq_file.c:seq_lseek
  - fs/seq_file.c:seq_read
```
**Symbols:**

```
ffffffff81300ac0-ffffffff81300ca6: traverse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int traverse(struct seq_file *m, loff_t offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff812f16e0)
Location: fs/seq_file.c:91
Inline: True
Direct callers:
  - fs/seq_file.c:seq_lseek
  - fs/seq_file.c:seq_read
```
**Symbols:**

```
ffffffff812f16e0-ffffffff812f18c6: traverse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int traverse(struct seq_file *m, loff_t offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff812fe8b0)
Location: fs/seq_file.c:91
Inline: True
Direct callers:
  - fs/seq_file.c:seq_lseek
  - fs/seq_file.c:seq_read
```
**Symbols:**

```
ffffffff812fe8b0-ffffffff812fea96: traverse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int traverse(struct seq_file *m, loff_t offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff8130fbf0)
Location: fs/seq_file.c:91
Inline: True
Direct callers:
  - fs/seq_file.c:seq_lseek
  - fs/seq_file.c:seq_read
```
**Symbols:**

```
ffffffff8130fbf0-ffffffff8130fdd6: traverse (STB_LOCAL)
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
