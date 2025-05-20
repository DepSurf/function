# Function: <code>dev_seq_stop</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void dev_seq_stop(struct seq_file *s, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffff815c2510)
Location: drivers/scsi/sg.c:2533
Inline: False
```
**Symbols:**

```
ffffffff815c2510-ffffffff815c2527: dev_seq_stop (STB_LOCAL)
ffffffff81737f20-ffffffff81737f2b: dev_seq_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision ⚠️</summary>

```c
void dev_seq_stop(struct seq_file *s, void *v);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffff8161aca0)
Location: drivers/scsi/sg.c:2534
Inline: False
```
```
In net/core/net-procfs.c (0)
Location: net/core/net-procfs.c:71
Inline: False
```
**Symbols:**

```
ffffffff8161aca0-ffffffff8161acb7: dev_seq_stop (STB_LOCAL)
ffffffff817a41e0-ffffffff817a41eb: dev_seq_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision ⚠️</summary>

```c
void dev_seq_stop(struct seq_file *s, void *v);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffff8164b920)
Location: drivers/scsi/sg.c:2531
Inline: False
```
```
In net/core/net-procfs.c (0)
Location: net/core/net-procfs.c:71
Inline: False
```
**Symbols:**

```
ffffffff8164b920-ffffffff8164b934: dev_seq_stop (STB_LOCAL)
ffffffff817d2c60-ffffffff817d2c6b: dev_seq_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision, Selective Inline ⚠️</summary>

```c
void dev_seq_stop(struct seq_file *s, void *v);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffff816600c0)
Location: drivers/scsi/sg.c:2530
Inline: False
```
```
In net/core/net-procfs.c (ffffffff817f17e0)
Location: net/core/net-procfs.c:71
Inline: True
```
**Symbols:**

```
ffffffff816600c0-ffffffff816600d4: dev_seq_stop (STB_LOCAL)
ffffffff817f17e0-ffffffff817f17eb: dev_seq_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Selective Inline ⚠️</summary>

```c
void dev_seq_stop(struct seq_file *s, void *v);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffff816c96d0)
Location: drivers/scsi/sg.c:2529
Inline: False
```
```
In net/core/net-procfs.c (ffffffff8186cdc0)
Location: net/core/net-procfs.c:72
Inline: True
```
**Symbols:**

```
ffffffff816c96d0-ffffffff816c96e4: dev_seq_stop (STB_LOCAL)
ffffffff8186cdc0-ffffffff8186cdcb: dev_seq_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Selective Inline ⚠️</summary>

```c
void dev_seq_stop(struct seq_file *s, void *v);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffff81706270)
Location: drivers/scsi/sg.c:2479
Inline: False
```
```
In net/core/net-procfs.c (ffffffff818be040)
Location: net/core/net-procfs.c:72
Inline: True
```
**Symbols:**

```
ffffffff81706270-ffffffff81706284: dev_seq_stop (STB_LOCAL)
ffffffff818be040-ffffffff818be04b: dev_seq_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Selective Inline ⚠️</summary>

```c
void dev_seq_stop(struct seq_file *s, void *v);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffff81728660)
Location: drivers/scsi/sg.c:2467
Inline: False
```
```
In net/core/net-procfs.c (ffffffff818e5420)
Location: net/core/net-procfs.c:72
Inline: True
```
**Symbols:**

```
ffffffff81728660-ffffffff81728674: dev_seq_stop (STB_LOCAL)
ffffffff818e5420-ffffffff818e542b: dev_seq_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision ⚠️</summary>

```c
void dev_seq_stop(struct seq_file *s, void *v);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffff81763d90)
Location: drivers/scsi/sg.c:2462
Inline: False
```
```
In net/core/net-procfs.c (ffffffff81934d60)
Location: net/core/net-procfs.c:72
Inline: False
```
**Symbols:**

```
ffffffff81763d90-ffffffff81763da4: dev_seq_stop (STB_LOCAL)
ffffffff81934d60-ffffffff81934d6b: dev_seq_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision ⚠️</summary>

```c
void dev_seq_stop(struct seq_file *s, void *v);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffff81787d80)
Location: drivers/scsi/sg.c:2462
Inline: False
```
```
In net/core/net-procfs.c (ffffffff81967b20)
Location: net/core/net-procfs.c:72
Inline: False
```
**Symbols:**

```
ffffffff81787d80-ffffffff81787d94: dev_seq_stop (STB_LOCAL)
ffffffff81967b20-ffffffff81967b2b: dev_seq_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Selective Inline ⚠️</summary>

```c
void dev_seq_stop(struct seq_file *s, void *v);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffff8184c6e0)
Location: drivers/scsi/sg.c:2490
Inline: False
```
```
In net/core/net-procfs.c (ffffffff81a3b380)
Location: net/core/net-procfs.c:72
Inline: True
```
**Symbols:**

```
ffffffff8184c6e0-ffffffff8184c6f4: dev_seq_stop (STB_LOCAL)
ffffffff81a3b380-ffffffff81a3b38b: dev_seq_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Selective Inline ⚠️</summary>

```c
void dev_seq_stop(struct seq_file *s, void *v);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffff8185cb20)
Location: drivers/scsi/sg.c:2483
Inline: False
```
```
In net/core/net-procfs.c (ffffffff81a3db80)
Location: net/core/net-procfs.c:72
Inline: True
```
**Symbols:**

```
ffffffff8185cb20-ffffffff8185cb34: dev_seq_stop (STB_LOCAL)
ffffffff81a3db80-ffffffff81a3db90: dev_seq_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Selective Inline ⚠️</summary>

```c
void dev_seq_stop(struct seq_file *s, void *v);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffff8183fa10)
Location: drivers/scsi/sg.c:2477
Inline: False
```
```
In net/core/net-procfs.c (ffffffff81a24c50)
Location: net/core/net-procfs.c:69
Inline: True
```
**Symbols:**

```
ffffffff8183fa10-ffffffff8183fa24: dev_seq_stop (STB_LOCAL)
ffffffff81a24c50-ffffffff81a24c60: dev_seq_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Selective Inline ⚠️</summary>

```c
void dev_seq_stop(struct seq_file *s, void *v);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffff818cc3b0)
Location: drivers/scsi/sg.c:2446
Inline: False
```
```
In net/core/net-procfs.c (ffffffff81ad96c0)
Location: net/core/net-procfs.c:69
Inline: True
```
**Symbols:**

```
ffffffff818cc3b0-ffffffff818cc3c4: dev_seq_stop (STB_LOCAL)
ffffffff81ad96c0-ffffffff81ad96d0: dev_seq_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Selective Inline ⚠️</summary>

```c
void dev_seq_stop(struct seq_file *s, void *v);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffff81a19750)
Location: drivers/scsi/sg.c:2482
Inline: False
```
```
In net/core/net-procfs.c (ffffffff81c5a9a0)
Location: net/core/net-procfs.c:71
Inline: True
```
**Symbols:**

```
ffffffff81a19750-ffffffff81a1976a: dev_seq_stop (STB_LOCAL)
ffffffff81c5a9a0-ffffffff81c5a9b4: dev_seq_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Selective Inline ⚠️</summary>

```c
void dev_seq_stop(struct seq_file *s, void *v);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffff81b9a7f0)
Location: drivers/scsi/sg.c:2465
Inline: False
```
```
In net/core/net-procfs.c (ffffffff81e10b50)
Location: net/core/net-procfs.c:71
Inline: True
```
**Symbols:**

```
ffffffff81b9a7f0-ffffffff81b9a80a: dev_seq_stop (STB_LOCAL)
ffffffff81e10b50-ffffffff81e10b64: dev_seq_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Selective Inline ⚠️</summary>

```c
void dev_seq_stop(struct seq_file *s, void *v);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffff81bf0dd0)
Location: drivers/scsi/sg.c:2476
Inline: False
```
```
In net/core/net-procfs.c (ffffffff81e84450)
Location: net/core/net-procfs.c:71
Inline: True
```
**Symbols:**

```
ffffffff81bf0dd0-ffffffff81bf0dea: dev_seq_stop (STB_LOCAL)
ffffffff81e84450-ffffffff81e84464: dev_seq_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Selective Inline ⚠️</summary>

```c
void dev_seq_stop(struct seq_file *s, void *v);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffff81c46690)
Location: drivers/scsi/sg.c:2475
Inline: False
```
```
In net/core/net-procfs.c (ffffffff81f46400)
Location: net/core/net-procfs.c:71
Inline: True
```
**Symbols:**

```
ffffffff81c46690-ffffffff81c466aa: dev_seq_stop (STB_LOCAL)
ffffffff81f46400-ffffffff81f46414: dev_seq_stop (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision, Selective Inline ⚠️</summary>

```c
void dev_seq_stop(struct seq_file *s, void *v);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffff80001098e7d0)
Location: drivers/scsi/sg.c:2462
Inline: False
```
```
In net/core/net-procfs.c (ffff800010c0d6c0)
Location: net/core/net-procfs.c:72
Inline: True
```
**Symbols:**

```
ffff80001098e7d0-ffff80001098e7fc: dev_seq_stop (STB_LOCAL)
ffff800010c0d6c0-ffff800010c0d6d8: dev_seq_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision, Selective Inline ⚠️</summary>

```c
void dev_seq_stop(struct seq_file *s, void *v);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (c0a60c68)
Location: drivers/scsi/sg.c:2462
Inline: False
```
```
In net/core/net-procfs.c (c0d25858)
Location: net/core/net-procfs.c:72
Inline: True
```
**Symbols:**

```
c0a60c68-c0a60c88: dev_seq_stop (STB_LOCAL)
c0d25858-c0d25870: dev_seq_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision ⚠️</summary>

```c
void dev_seq_stop(struct seq_file *s, void *v);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (c000000000a509b0)
Location: drivers/scsi/sg.c:2462
Inline: False
```
```
In net/core/net-procfs.c (c000000000cf8d90)
Location: net/core/net-procfs.c:72
Inline: False
```
**Symbols:**

```
c000000000a509b0-c000000000a509e8: dev_seq_stop (STB_LOCAL)
c000000000cf8d90-c000000000cf8d9c: dev_seq_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision, Selective Inline ⚠️</summary>

```c
void dev_seq_stop(struct seq_file *s, void *v);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffe0005f2d4a)
Location: drivers/scsi/sg.c:2462
Inline: False
```
```
In net/core/net-procfs.c (ffffffe00078a390)
Location: net/core/net-procfs.c:72
Inline: True
```
**Symbols:**

```
ffffffe0005f2d4a-ffffffe0005f2d74: dev_seq_stop (STB_LOCAL)
ffffffe00078a390-ffffffe00078a3aa: dev_seq_stop (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision ⚠️</summary>

```c
void dev_seq_stop(struct seq_file *s, void *v);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffff8173c470)
Location: drivers/scsi/sg.c:2462
Inline: False
```
```
In net/core/net-procfs.c (ffffffff81907af0)
Location: net/core/net-procfs.c:72
Inline: False
```
**Symbols:**

```
ffffffff8173c470-ffffffff8173c484: dev_seq_stop (STB_LOCAL)
ffffffff81907af0-ffffffff81907afb: dev_seq_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision ⚠️</summary>

```c
void dev_seq_stop(struct seq_file *s, void *v);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffff8171e110)
Location: drivers/scsi/sg.c:2462
Inline: False
```
```
In net/core/net-procfs.c (ffffffff818c1900)
Location: net/core/net-procfs.c:72
Inline: False
```
**Symbols:**

```
ffffffff8171e110-ffffffff8171e124: dev_seq_stop (STB_LOCAL)
ffffffff818c1900-ffffffff818c190b: dev_seq_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision ⚠️</summary>

```c
void dev_seq_stop(struct seq_file *s, void *v);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffff8177cc00)
Location: drivers/scsi/sg.c:2462
Inline: False
```
```
In net/core/net-procfs.c (ffffffff81958b20)
Location: net/core/net-procfs.c:72
Inline: False
```
**Symbols:**

```
ffffffff8177cc00-ffffffff8177cc14: dev_seq_stop (STB_LOCAL)
ffffffff81958b20-ffffffff81958b2b: dev_seq_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision ⚠️</summary>

```c
void dev_seq_stop(struct seq_file *s, void *v);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffff81796a30)
Location: drivers/scsi/sg.c:2462
Inline: False
```
```
In net/core/net-procfs.c (ffffffff8197ad60)
Location: net/core/net-procfs.c:72
Inline: False
```
**Symbols:**

```
ffffffff81796a30-ffffffff81796a44: dev_seq_stop (STB_LOCAL)
ffffffff8197ad60-ffffffff8197ad70: dev_seq_stop (STB_LOCAL)
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
