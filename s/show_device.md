# Function: <code>show_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int show_device(struct seq_file *m, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/proc.c (ffffffff81441850)
Location: drivers/pci/proc.c:334
Inline: False
```
**Symbols:**

```
ffffffff81441850-ffffffff8144196b: show_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int show_device(struct seq_file *m, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/proc.c (ffffffff8148d760)
Location: drivers/pci/proc.c:337
Inline: False
```
**Symbols:**

```
ffffffff8148d760-ffffffff8148d87d: show_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int show_device(struct seq_file *m, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/proc.c (ffffffff814aef50)
Location: drivers/pci/proc.c:337
Inline: False
```
**Symbols:**

```
ffffffff814aef50-ffffffff814af06d: show_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int show_device(struct seq_file *m, void *v);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/proc.c (ffffffff814b98b0)
Location: drivers/pci/proc.c:350
Inline: True
```
**Symbols:**

```
ffffffff814b98b0-ffffffff814b99cc: show_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int show_device(struct seq_file *m, void *v);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/proc.c (ffffffff814f9c80)
Location: drivers/pci/proc.c:352
Inline: True
```
**Symbols:**

```
ffffffff814f9c80-ffffffff814f9d9c: show_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int show_device(struct seq_file *m, void *v);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/proc.c (ffffffff8152a750)
Location: drivers/pci/proc.c:352
Inline: True
```
**Symbols:**

```
ffffffff8152a750-ffffffff8152a86c: show_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int show_device(struct seq_file *m, void *v);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/proc.c (ffffffff815405d0)
Location: drivers/pci/proc.c:352
Inline: True
```
**Symbols:**

```
ffffffff815405d0-ffffffff815406ec: show_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int show_device(struct seq_file *m, void *v);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/proc.c (ffffffff8156fed0)
Location: drivers/pci/proc.c:353
Inline: True
```
**Symbols:**

```
ffffffff8156fed0-ffffffff8156ffdc: show_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int show_device(struct seq_file *m, void *v);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/proc.c (ffffffff81590f50)
Location: drivers/pci/proc.c:356
Inline: True
```
**Symbols:**

```
ffffffff81590f50-ffffffff815910b3: show_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int show_device(struct seq_file *m, void *v);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/proc.c (ffffffff8163f230)
Location: drivers/pci/proc.c:357
Inline: True
```
**Symbols:**

```
ffffffff8163f230-ffffffff8163f388: show_device.part.0 (STB_LOCAL)
ffffffff8163f390-ffffffff8163f3aa: show_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int show_device(struct seq_file *m, void *v);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/proc.c (ffffffff81665630)
Location: drivers/pci/proc.c:357
Inline: True
```
**Symbols:**

```
ffffffff81665630-ffffffff81665788: show_device.part.0 (STB_LOCAL)
ffffffff81665790-ffffffff816657aa: show_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int show_device(struct seq_file *m, void *v);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/proc.c (ffffffff81647c00)
Location: drivers/pci/proc.c:363
Inline: True
```
**Symbols:**

```
ffffffff81647c00-ffffffff81647d63: show_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int show_device(struct seq_file *m, void *v);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/proc.c (ffffffff816b9560)
Location: drivers/pci/proc.c:364
Inline: True
```
**Symbols:**

```
ffffffff816b9560-ffffffff816b977b: show_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int show_device(struct seq_file *m, void *v);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/proc.c (ffffffff817de040)
Location: drivers/pci/proc.c:362
Inline: True
```
**Symbols:**

```
ffffffff817de040-ffffffff817de290: show_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int show_device(struct seq_file *m, void *v);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/proc.c (ffffffff81900bc0)
Location: drivers/pci/proc.c:367
Inline: True
```
**Symbols:**

```
ffffffff81900bc0-ffffffff81900e10: show_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int show_device(struct seq_file *m, void *v);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/proc.c (ffffffff81944180)
Location: drivers/pci/proc.c:367
Inline: True
```
**Symbols:**

```
ffffffff81944180-ffffffff819443d0: show_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int show_device(struct seq_file *m, void *v);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/proc.c (ffffffff8198d480)
Location: drivers/pci/proc.c:367
Inline: True
```
**Symbols:**

```
ffffffff8198d480-ffffffff8198d6cf: show_device (STB_LOCAL)
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
int show_device(struct seq_file *m, void *v);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/proc.c (ffff8000106f5bd0)
Location: drivers/pci/proc.c:356
Inline: True
```
**Symbols:**

```
ffff8000106f5bd0-ffff8000106f5d54: show_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int show_device(struct seq_file *m, void *v);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/proc.c (c0890ee4)
Location: drivers/pci/proc.c:356
Inline: True
```
**Symbols:**

```
c0890ee4-c089108c: show_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int show_device(struct seq_file *m, void *v);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/proc.c (c000000000874e60)
Location: drivers/pci/proc.c:356
Inline: True
```
**Symbols:**

```
c000000000874e60-c000000000875068: show_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int show_device(struct seq_file *m, void *v);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/proc.c (ffffffe0004c8d4e)
Location: drivers/pci/proc.c:356
Inline: True
```
**Symbols:**

```
ffffffe0004c8d4e-ffffffe0004c8e8a: show_device (STB_LOCAL)
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
int show_device(struct seq_file *m, void *v);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/proc.c (ffffffff81584de0)
Location: drivers/pci/proc.c:356
Inline: True
```
**Symbols:**

```
ffffffff81584de0-ffffffff81584f43: show_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int show_device(struct seq_file *m, void *v);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/proc.c (ffffffff81573bb0)
Location: drivers/pci/proc.c:356
Inline: True
```
**Symbols:**

```
ffffffff81573bb0-ffffffff81573d13: show_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int show_device(struct seq_file *m, void *v);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/proc.c (ffffffff81584ca0)
Location: drivers/pci/proc.c:356
Inline: True
```
**Symbols:**

```
ffffffff81584ca0-ffffffff81584e03: show_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int show_device(struct seq_file *m, void *v);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/proc.c (ffffffff8159f150)
Location: drivers/pci/proc.c:356
Inline: True
```
**Symbols:**

```
ffffffff8159f150-ffffffff8159f2b3: show_device (STB_LOCAL)
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
