# Function: <code>m_start</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision, Selective Inline ⚠️</summary>

```c
void *m_start(struct seq_file *m, loff_t *pos);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff811058c0)
Location: kernel/module.c:3893
Inline: False
```
```
In kernel/user_namespace.c (ffffffff8111e2f3)
Location: kernel/user_namespace.c:499
Inline: True
Inline callers:
  - kernel/user_namespace.c:uid_m_start
  - kernel/user_namespace.c:gid_m_start
  - kernel/user_namespace.c:projid_m_start
```
```
In fs/namespace.c (ffffffff8122bb00)
Location: fs/namespace.c:1228
Inline: False
```
```
In fs/proc/task_mmu.c (ffffffff81277f30)
Location: fs/proc/task_mmu.c:142
Inline: False
```
**Symbols:**

```
ffffffff811058c0-ffffffff811058eb: m_start (STB_LOCAL)
ffffffff8122bb00-ffffffff8122bb81: m_start (STB_LOCAL)
ffffffff81277f30-ffffffff812780b1: m_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision, Selective Inline ⚠️</summary>

```c
void *m_start(struct seq_file *m, loff_t *pos);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8110d190)
Location: kernel/module.c:4064
Inline: False
```
```
In kernel/user_namespace.c (ffffffff81126223)
Location: kernel/user_namespace.c:499
Inline: True
Inline callers:
  - kernel/user_namespace.c:projid_m_start
  - kernel/user_namespace.c:gid_m_start
  - kernel/user_namespace.c:uid_m_start
```
```
In fs/namespace.c (ffffffff81254270)
Location: fs/namespace.c:1228
Inline: False
```
```
In fs/proc/task_mmu.c (ffffffff812a4290)
Location: fs/proc/task_mmu.c:153
Inline: False
```
**Symbols:**

```
ffffffff8110d190-ffffffff8110d1bb: m_start (STB_LOCAL)
ffffffff81254270-ffffffff812542f1: m_start (STB_LOCAL)
ffffffff812a4290-ffffffff812a4411: m_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision, Selective Inline ⚠️</summary>

```c
void *m_start(struct seq_file *m, loff_t *pos);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81114c00)
Location: kernel/module.c:4085
Inline: False
```
```
In kernel/user_namespace.c (ffffffff8112fc70)
Location: kernel/user_namespace.c:545
Inline: True
Inline callers:
  - kernel/user_namespace.c:projid_m_start
  - kernel/user_namespace.c:gid_m_start
  - kernel/user_namespace.c:uid_m_start
```
```
In fs/namespace.c (ffffffff812675b0)
Location: fs/namespace.c:1302
Inline: False
```
```
In fs/proc/task_mmu.c (ffffffff812b9790)
Location: fs/proc/task_mmu.c:153
Inline: False
```
**Symbols:**

```
ffffffff81114c00-ffffffff81114c2b: m_start (STB_LOCAL)
ffffffff812675b0-ffffffff8126762e: m_start (STB_LOCAL)
ffffffff812b9790-ffffffff812b9913: m_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision, Selective Inline ⚠️</summary>

```c
void *m_start(struct seq_file *m, loff_t *pos);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81115b70)
Location: kernel/module.c:4130
Inline: False
```
```
In kernel/user_namespace.c (ffffffff81131280)
Location: kernel/user_namespace.c:546
Inline: True
Inline callers:
  - kernel/user_namespace.c:projid_m_start
  - kernel/user_namespace.c:gid_m_start
  - kernel/user_namespace.c:uid_m_start
```
```
In fs/namespace.c (ffffffff81274d80)
Location: fs/namespace.c:1244
Inline: False
```
```
In fs/proc/task_mmu.c (ffffffff812c7090)
Location: fs/proc/task_mmu.c:155
Inline: False
```
**Symbols:**

```
ffffffff81115b70-ffffffff81115b9b: m_start (STB_LOCAL)
ffffffff81274d80-ffffffff81274e03: m_start (STB_LOCAL)
ffffffff812c7090-ffffffff812c7208: m_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Selective Inline ⚠️</summary>

```c
void *m_start(struct seq_file *m, loff_t *pos);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81121100)
Location: kernel/module.c:4152
Inline: False
```
```
In kernel/user_namespace.c (ffffffff8113dda0)
Location: kernel/user_namespace.c:652
Inline: True
Inline callers:
  - kernel/user_namespace.c:projid_m_start
  - kernel/user_namespace.c:gid_m_start
  - kernel/user_namespace.c:uid_m_start
```
```
In fs/namespace.c (ffffffff812976b0)
Location: fs/namespace.c:1309
Inline: False
```
```
In fs/proc/task_mmu.c (ffffffff812eac90)
Location: fs/proc/task_mmu.c:152
Inline: False
```
**Symbols:**

```
ffffffff81121100-ffffffff8112112b: m_start (STB_LOCAL)
ffffffff812976b0-ffffffff81297733: m_start (STB_LOCAL)
ffffffff812eac90-ffffffff812eae08: m_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Selective Inline ⚠️</summary>

```c
void *m_start(struct seq_file *m, loff_t *pos);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8112ea20)
Location: kernel/module.c:4189
Inline: False
```
```
In kernel/user_namespace.c (ffffffff8114c73d)
Location: kernel/user_namespace.c:652
Inline: True
Inline callers:
  - kernel/user_namespace.c:projid_m_start
  - kernel/user_namespace.c:gid_m_start
  - kernel/user_namespace.c:uid_m_start
```
```
In fs/namespace.c (ffffffff812bd8a0)
Location: fs/namespace.c:1335
Inline: False
```
```
In fs/proc/task_mmu.c (ffffffff81318840)
Location: fs/proc/task_mmu.c:149
Inline: False
```
**Symbols:**

```
ffffffff8112ea20-ffffffff8112ea4b: m_start (STB_LOCAL)
ffffffff812bd8a0-ffffffff812bd923: m_start (STB_LOCAL)
ffffffff81318840-ffffffff813189c3: m_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Selective Inline ⚠️</summary>

```c
void *m_start(struct seq_file *m, loff_t *pos);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8113a3e0)
Location: kernel/module.c:4227
Inline: False
```
```
In kernel/user_namespace.c (ffffffff8115935d)
Location: kernel/user_namespace.c:652
Inline: True
Inline callers:
  - kernel/user_namespace.c:projid_m_start
  - kernel/user_namespace.c:gid_m_start
  - kernel/user_namespace.c:uid_m_start
```
```
In fs/namespace.c (ffffffff812d2d40)
Location: fs/namespace.c:1247
Inline: False
```
```
In fs/proc/task_mmu.c (ffffffff8132f730)
Location: fs/proc/task_mmu.c:149
Inline: False
```
**Symbols:**

```
ffffffff8113a3e0-ffffffff8113a40b: m_start (STB_LOCAL)
ffffffff812d2d40-ffffffff812d2dc3: m_start (STB_LOCAL)
ffffffff8132f730-ffffffff8132f86b: m_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Selective Inline ⚠️</summary>

```c
void *m_start(struct seq_file *m, loff_t *pos);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81145cd0)
Location: kernel/module.c:4255
Inline: False
```
```
In kernel/user_namespace.c (ffffffff81165a9d)
Location: kernel/user_namespace.c:646
Inline: True
Inline callers:
  - kernel/user_namespace.c:projid_m_start
  - kernel/user_namespace.c:gid_m_start
  - kernel/user_namespace.c:uid_m_start
```
```
In fs/namespace.c (ffffffff812efee0)
Location: fs/namespace.c:1257
Inline: False
```
```
In fs/proc/task_mmu.c (ffffffff81357530)
Location: fs/proc/task_mmu.c:149
Inline: False
```
**Symbols:**

```
ffffffff81145cd0-ffffffff81145cfb: m_start (STB_LOCAL)
ffffffff812efee0-ffffffff812eff63: m_start (STB_LOCAL)
ffffffff81357530-ffffffff81357666: m_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Selective Inline ⚠️</summary>

```c
void *m_start(struct seq_file *m, loff_t *pos);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81151850)
Location: kernel/module.c:4322
Inline: False
```
```
In kernel/user_namespace.c (ffffffff8117195d)
Location: kernel/user_namespace.c:646
Inline: True
Inline callers:
  - kernel/user_namespace.c:projid_m_start
  - kernel/user_namespace.c:gid_m_start
  - kernel/user_namespace.c:uid_m_start
```
```
In fs/namespace.c (ffffffff813019b0)
Location: fs/namespace.c:1257
Inline: False
```
```
In fs/proc/task_mmu.c (ffffffff8136f760)
Location: fs/proc/task_mmu.c:149
Inline: False
```
**Symbols:**

```
ffffffff81151850-ffffffff8115187b: m_start (STB_LOCAL)
ffffffff813019b0-ffffffff81301a33: m_start (STB_LOCAL)
ffffffff8136f760-ffffffff8136f896: m_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Selective Inline ⚠️</summary>

```c
void *m_start(struct seq_file *m, loff_t *pos);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81161c90)
Location: kernel/module.c:4329
Inline: False
```
```
In kernel/user_namespace.c (ffffffff8118377a)
Location: kernel/user_namespace.c:646
Inline: True
Inline callers:
  - kernel/user_namespace.c:projid_m_start
  - kernel/user_namespace.c:gid_m_start
  - kernel/user_namespace.c:uid_m_start
```
```
In fs/namespace.c (ffffffff8133b160)
Location: fs/namespace.c:1291
Inline: False
```
```
In fs/proc/task_mmu.c (ffffffff813b7580)
Location: fs/proc/task_mmu.c:126
Inline: False
```
**Symbols:**

```
ffffffff81161c90-ffffffff81161cbe: m_start (STB_LOCAL)
ffffffff8133b160-ffffffff8133b1fd: m_start (STB_LOCAL)
ffffffff813b7580-ffffffff813b76c7: m_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Selective Inline ⚠️</summary>

```c
void *m_start(struct seq_file *m, loff_t *pos);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8115dda0)
Location: kernel/module.c:4560
Inline: False
```
```
In kernel/user_namespace.c (ffffffff811806aa)
Location: kernel/user_namespace.c:646
Inline: True
Inline callers:
  - kernel/user_namespace.c:projid_m_start
  - kernel/user_namespace.c:gid_m_start
  - kernel/user_namespace.c:uid_m_start
```
```
In fs/namespace.c (ffffffff81346f80)
Location: fs/namespace.c:1294
Inline: False
```
```
In fs/proc/task_mmu.c (ffffffff813c8e70)
Location: fs/proc/task_mmu.c:126
Inline: False
```
**Symbols:**

```
ffffffff8115dda0-ffffffff8115ddce: m_start (STB_LOCAL)
ffffffff81346f80-ffffffff8134701d: m_start (STB_LOCAL)
ffffffff813c8e70-ffffffff813c9008: m_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Selective Inline ⚠️</summary>

```c
void *m_start(struct seq_file *m, loff_t *pos);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8115ee60)
Location: kernel/module.c:4499
Inline: False
```
```
In kernel/user_namespace.c (ffffffff8118170a)
Location: kernel/user_namespace.c:647
Inline: True
Inline callers:
  - kernel/user_namespace.c:projid_m_start
  - kernel/user_namespace.c:gid_m_start
  - kernel/user_namespace.c:uid_m_start
```
```
In fs/namespace.c (ffffffff8134d7d0)
Location: fs/namespace.c:1305
Inline: False
```
```
In fs/proc/task_mmu.c (ffffffff813cff40)
Location: fs/proc/task_mmu.c:126
Inline: False
```
**Symbols:**

```
ffffffff8115ee60-ffffffff8115ee8e: m_start (STB_LOCAL)
ffffffff8134d7d0-ffffffff8134d86d: m_start (STB_LOCAL)
ffffffff813cff40-ffffffff813d00d8: m_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Selective Inline ⚠️</summary>

```c
void *m_start(struct seq_file *m, loff_t *pos);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81183f30)
Location: kernel/module.c:4522
Inline: False
```
```
In kernel/user_namespace.c (ffffffff811a962a)
Location: kernel/user_namespace.c:663
Inline: True
Inline callers:
  - kernel/user_namespace.c:projid_m_start
  - kernel/user_namespace.c:gid_m_start
  - kernel/user_namespace.c:uid_m_start
```
```
In fs/namespace.c (ffffffff8139b7a0)
Location: fs/namespace.c:1314
Inline: False
```
```
In fs/proc/task_mmu.c (ffffffff81421560)
Location: fs/proc/task_mmu.c:126
Inline: False
```
**Symbols:**

```
ffffffff81183f30-ffffffff81183f5e: m_start (STB_LOCAL)
ffffffff8139b7a0-ffffffff8139b83d: m_start (STB_LOCAL)
ffffffff81421560-ffffffff814216f2: m_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Selective Inline ⚠️</summary>

```c
void *m_start(struct seq_file *m, loff_t *pos);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module/procfs.c (ffffffff81192050)
Location: kernel/module/procfs.c:49
Inline: False
```
```
In kernel/user_namespace.c (ffffffff811da9ba)
Location: kernel/user_namespace.c:668
Inline: True
Inline callers:
  - kernel/user_namespace.c:projid_m_start
  - kernel/user_namespace.c:gid_m_start
  - kernel/user_namespace.c:uid_m_start
```
```
In fs/namespace.c (ffffffff8141d1a0)
Location: fs/namespace.c:1355
Inline: False
```
```
In fs/proc/task_mmu.c (ffffffff81498f30)
Location: fs/proc/task_mmu.c:127
Inline: False
```
**Symbols:**

```
ffffffff81192050-ffffffff81192086: m_start (STB_LOCAL)
ffffffff8141d1a0-ffffffff8141d241: m_start (STB_LOCAL)
ffffffff81498f30-ffffffff814990ef: m_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Selective Inline ⚠️</summary>

```c
void *m_start(struct seq_file *m, loff_t *pos);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module/procfs.c (ffffffff811cf780)
Location: kernel/module/procfs.c:49
Inline: False
```
```
In kernel/user_namespace.c (ffffffff8121fffa)
Location: kernel/user_namespace.c:668
Inline: True
Inline callers:
  - kernel/user_namespace.c:projid_m_start
  - kernel/user_namespace.c:gid_m_start
  - kernel/user_namespace.c:uid_m_start
```
```
In fs/namespace.c (ffffffff814a94d0)
Location: fs/namespace.c:1460
Inline: False
```
```
In fs/proc/task_mmu.c (ffffffff8152d280)
Location: fs/proc/task_mmu.c:141
Inline: False
```
**Symbols:**

```
ffffffff811cf780-ffffffff811cf7b6: m_start (STB_LOCAL)
ffffffff814a94d0-ffffffff814a9571: m_start (STB_LOCAL)
ffffffff8152d280-ffffffff8152d47d: m_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Selective Inline ⚠️</summary>

```c
void *m_start(struct seq_file *m, loff_t *pos);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module/procfs.c (ffffffff811e3920)
Location: kernel/module/procfs.c:49
Inline: False
```
```
In kernel/user_namespace.c (ffffffff81236252)
Location: kernel/user_namespace.c:668
Inline: True
Inline callers:
  - kernel/user_namespace.c:projid_m_start
  - kernel/user_namespace.c:gid_m_start
  - kernel/user_namespace.c:uid_m_start
```
```
In fs/namespace.c (ffffffff814de410)
Location: fs/namespace.c:1434
Inline: False
```
```
In fs/proc/task_mmu.c (ffffffff81565350)
Location: fs/proc/task_mmu.c:141
Inline: False
```
**Symbols:**

```
ffffffff811e3920-ffffffff811e3956: m_start (STB_LOCAL)
ffffffff814de410-ffffffff814de4b1: m_start (STB_LOCAL)
ffffffff81565350-ffffffff81565589: m_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Selective Inline ⚠️</summary>

```c
void *m_start(struct seq_file *m, loff_t *pos);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module/procfs.c (ffffffff811f9680)
Location: kernel/module/procfs.c:49
Inline: False
```
```
In kernel/user_namespace.c (ffffffff8124fed2)
Location: kernel/user_namespace.c:671
Inline: True
Inline callers:
  - kernel/user_namespace.c:projid_m_start
  - kernel/user_namespace.c:gid_m_start
  - kernel/user_namespace.c:uid_m_start
```
```
In fs/namespace.c (ffffffff81512560)
Location: fs/namespace.c:1454
Inline: False
```
```
In fs/proc/task_mmu.c (ffffffff8159c150)
Location: fs/proc/task_mmu.c:144
Inline: False
```
**Symbols:**

```
ffffffff811f9680-ffffffff811f96b6: m_start (STB_LOCAL)
ffffffff81512560-ffffffff815125cc: m_start (STB_LOCAL)
ffffffff8159c150-ffffffff8159c390: m_start (STB_LOCAL)
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
void *m_start(struct seq_file *m, loff_t *pos);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffff8000101c0900)
Location: kernel/module.c:4322
Inline: False
```
```
In kernel/user_namespace.c (ffff8000101e56a0)
Location: kernel/user_namespace.c:646
Inline: True
Inline callers:
  - kernel/user_namespace.c:projid_m_start
  - kernel/user_namespace.c:gid_m_start
  - kernel/user_namespace.c:uid_m_start
```
```
In fs/namespace.c (ffff8000103b4090)
Location: fs/namespace.c:1257
Inline: False
```
```
In fs/proc/task_mmu.c (ffff80001043a3e0)
Location: fs/proc/task_mmu.c:149
Inline: False
```
**Symbols:**

```
ffff8000101c0900-ffff8000101c0940: m_start (STB_LOCAL)
ffff8000103b4090-ffff8000103b4138: m_start (STB_LOCAL)
ffff80001043a3e0-ffff80001043a59c: m_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision, Selective Inline ⚠️</summary>

```c
void *m_start(struct seq_file *m, loff_t *pos);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (c0407eb0)
Location: kernel/module.c:4322
Inline: False
```
```
In kernel/user_namespace.c (c0425e5c)
Location: kernel/user_namespace.c:646
Inline: True
Inline callers:
  - kernel/user_namespace.c:projid_m_start
  - kernel/user_namespace.c:gid_m_start
  - kernel/user_namespace.c:uid_m_start
```
```
In fs/namespace.c (c0592f40)
Location: fs/namespace.c:1257
Inline: False
```
```
In fs/proc/task_mmu.c (c06010c4)
Location: fs/proc/task_mmu.c:149
Inline: False
```
**Symbols:**

```
c0407eb0-c0407ee8: m_start (STB_LOCAL)
c0592f40-c0592ffc: m_start (STB_LOCAL)
c06010c4-c0601248: m_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision, Selective Inline ⚠️</summary>

```c
void *m_start(struct seq_file *m, loff_t *pos);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (c0000000002267f0)
Location: kernel/module.c:4322
Inline: False
```
```
In kernel/user_namespace.c (c000000000255a90)
Location: kernel/user_namespace.c:646
Inline: True
Inline callers:
  - kernel/user_namespace.c:projid_m_start
  - kernel/user_namespace.c:gid_m_start
  - kernel/user_namespace.c:uid_m_start
```
```
In fs/namespace.c (c0000000004aff40)
Location: fs/namespace.c:1257
Inline: False
```
```
In fs/proc/task_mmu.c (c00000000054af00)
Location: fs/proc/task_mmu.c:149
Inline: False
```
**Symbols:**

```
c0000000002267f0-c000000000226858: m_start (STB_LOCAL)
c0000000004aff40-c0000000004b0030: m_start (STB_LOCAL)
c00000000054af00-c00000000054b150: m_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision, Selective Inline ⚠️</summary>

```c
void *m_start(struct seq_file *m, loff_t *pos);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffe000142bce)
Location: kernel/module.c:4322
Inline: False
```
```
In kernel/user_namespace.c (ffffffe00015b1b2)
Location: kernel/user_namespace.c:646
Inline: True
Inline callers:
  - kernel/user_namespace.c:projid_m_start
  - kernel/user_namespace.c:gid_m_start
  - kernel/user_namespace.c:uid_m_start
```
```
In fs/namespace.c (ffffffe0002778b2)
Location: fs/namespace.c:1257
Inline: False
```
```
In fs/proc/task_mmu.c (ffffffe0002d20d0)
Location: fs/proc/task_mmu.c:149
Inline: False
```
**Symbols:**

```
ffffffe000142bce-ffffffe000142c10: m_start (STB_LOCAL)
ffffffe0002778b2-ffffffe00027793c: m_start (STB_LOCAL)
ffffffe0002d20d0-ffffffe0002d21ee: m_start (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision, Selective Inline ⚠️</summary>

```c
void *m_start(struct seq_file *m, loff_t *pos);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81149e70)
Location: kernel/module.c:4322
Inline: False
```
```
In kernel/user_namespace.c (ffffffff81169f7d)
Location: kernel/user_namespace.c:646
Inline: True
Inline callers:
  - kernel/user_namespace.c:projid_m_start
  - kernel/user_namespace.c:gid_m_start
  - kernel/user_namespace.c:uid_m_start
```
```
In fs/namespace.c (ffffffff812f9f90)
Location: fs/namespace.c:1257
Inline: False
```
```
In fs/proc/task_mmu.c (ffffffff81367d40)
Location: fs/proc/task_mmu.c:149
Inline: False
```
**Symbols:**

```
ffffffff81149e70-ffffffff81149e9b: m_start (STB_LOCAL)
ffffffff812f9f90-ffffffff812fa013: m_start (STB_LOCAL)
ffffffff81367d40-ffffffff81367e76: m_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Selective Inline ⚠️</summary>

```c
void *m_start(struct seq_file *m, loff_t *pos);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8113d120)
Location: kernel/module.c:4322
Inline: False
```
```
In kernel/user_namespace.c (ffffffff8115d17d)
Location: kernel/user_namespace.c:646
Inline: True
Inline callers:
  - kernel/user_namespace.c:projid_m_start
  - kernel/user_namespace.c:gid_m_start
  - kernel/user_namespace.c:uid_m_start
```
```
In fs/namespace.c (ffffffff812eabb0)
Location: fs/namespace.c:1257
Inline: False
```
```
In fs/proc/task_mmu.c (ffffffff81358bf0)
Location: fs/proc/task_mmu.c:149
Inline: False
```
**Symbols:**

```
ffffffff8113d120-ffffffff8113d14b: m_start (STB_LOCAL)
ffffffff812eabb0-ffffffff812eac33: m_start (STB_LOCAL)
ffffffff81358bf0-ffffffff81358d26: m_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Selective Inline ⚠️</summary>

```c
void *m_start(struct seq_file *m, loff_t *pos);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81147d20)
Location: kernel/module.c:4322
Inline: False
```
```
In kernel/user_namespace.c (ffffffff81167d4d)
Location: kernel/user_namespace.c:646
Inline: True
Inline callers:
  - kernel/user_namespace.c:projid_m_start
  - kernel/user_namespace.c:gid_m_start
  - kernel/user_namespace.c:uid_m_start
```
```
In fs/namespace.c (ffffffff812f7d80)
Location: fs/namespace.c:1257
Inline: False
```
```
In fs/proc/task_mmu.c (ffffffff81365810)
Location: fs/proc/task_mmu.c:149
Inline: False
```
**Symbols:**

```
ffffffff81147d20-ffffffff81147d4b: m_start (STB_LOCAL)
ffffffff812f7d80-ffffffff812f7e03: m_start (STB_LOCAL)
ffffffff81365810-ffffffff81365946: m_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Selective Inline ⚠️</summary>

```c
void *m_start(struct seq_file *m, loff_t *pos);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81154930)
Location: kernel/module.c:4322
Inline: False
```
```
In kernel/user_namespace.c (ffffffff8117542d)
Location: kernel/user_namespace.c:646
Inline: True
Inline callers:
  - kernel/user_namespace.c:projid_m_start
  - kernel/user_namespace.c:gid_m_start
  - kernel/user_namespace.c:uid_m_start
```
```
In fs/namespace.c (ffffffff813094e0)
Location: fs/namespace.c:1257
Inline: False
```
```
In fs/proc/task_mmu.c (ffffffff81378ea0)
Location: fs/proc/task_mmu.c:149
Inline: False
```
**Symbols:**

```
ffffffff81154930-ffffffff8115495b: m_start (STB_LOCAL)
ffffffff813094e0-ffffffff81309563: m_start (STB_LOCAL)
ffffffff81378ea0-ffffffff81378fd6: m_start (STB_LOCAL)
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
