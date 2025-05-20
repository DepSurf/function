# Function: <code>dev_mce_log</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int dev_mce_log(struct notifier_block *nb, long unsigned int val, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/dev-mcelog.c (ffffffff8104bf30)
Location: arch/x86/kernel/cpu/mcheck/dev-mcelog.c:52
Inline: False
```
**Symbols:**

```
ffffffff8104bf30-ffffffff8104c08f: dev_mce_log (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int dev_mce_log(struct notifier_block *nb, long unsigned int val, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/dev-mcelog.c (ffffffff8104f970)
Location: arch/x86/kernel/cpu/mcheck/dev-mcelog.c:44
Inline: False
```
**Symbols:**

```
ffffffff8104f970-ffffffff8104fa97: dev_mce_log (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int dev_mce_log(struct notifier_block *nb, long unsigned int val, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/dev-mcelog.c (ffffffff81052680)
Location: arch/x86/kernel/cpu/mcheck/dev-mcelog.c:44
Inline: False
```
**Symbols:**

```
ffffffff81052680-ffffffff810527a7: dev_mce_log (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int dev_mce_log(struct notifier_block *nb, long unsigned int val, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff8104fce0)
Location: arch/x86/kernel/cpu/mce/dev-mcelog.c:39
Inline: False
```
**Symbols:**

```
ffffffff8104fce0-ffffffff8104fe07: dev_mce_log (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int dev_mce_log(struct notifier_block *nb, long unsigned int val, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff81052df0)
Location: arch/x86/kernel/cpu/mce/dev-mcelog.c:40
Inline: False
```
**Symbols:**

```
ffffffff81052df0-ffffffff81052f10: dev_mce_log (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int dev_mce_log(struct notifier_block *nb, long unsigned int val, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff810536e0)
Location: arch/x86/kernel/cpu/mce/dev-mcelog.c:40
Inline: False
```
**Symbols:**

```
ffffffff810536e0-ffffffff81053800: dev_mce_log (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int dev_mce_log(struct notifier_block *nb, long unsigned int val, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff810589c0)
Location: arch/x86/kernel/cpu/mce/dev-mcelog.c:36
Inline: True
```
**Symbols:**

```
ffffffff810589c0-ffffffff81058ac0: dev_mce_log.part.0 (STB_LOCAL)
ffffffff81058ac0-ffffffff81058adc: dev_mce_log (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int dev_mce_log(struct notifier_block *nb, long unsigned int val, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff810577c0)
Location: arch/x86/kernel/cpu/mce/dev-mcelog.c:36
Inline: True
```
**Symbols:**

```
ffffffff810577c0-ffffffff810578c9: dev_mce_log.part.0 (STB_LOCAL)
ffffffff810578d0-ffffffff810578ec: dev_mce_log (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int dev_mce_log(struct notifier_block *nb, long unsigned int val, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff81058130)
Location: arch/x86/kernel/cpu/mce/dev-mcelog.c:36
Inline: True
```
**Symbols:**

```
ffffffff81058130-ffffffff81058242: dev_mce_log (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int dev_mce_log(struct notifier_block *nb, long unsigned int val, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff81061000)
Location: arch/x86/kernel/cpu/mce/dev-mcelog.c:36
Inline: True
```
**Symbols:**

```
ffffffff81061000-ffffffff81061112: dev_mce_log (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int dev_mce_log(struct notifier_block *nb, long unsigned int val, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff8106d9a0)
Location: arch/x86/kernel/cpu/mce/dev-mcelog.c:36
Inline: False
```
**Symbols:**

```
ffffffff8106d9a0-ffffffff8106daca: dev_mce_log (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dev_mce_log(struct notifier_block *nb, long unsigned int val, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff8107dc20)
Location: arch/x86/kernel/cpu/mce/dev-mcelog.c:36
Inline: False
```
**Symbols:**

```
ffffffff8107dc20-ffffffff8107dd4a: dev_mce_log (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dev_mce_log(struct notifier_block *nb, long unsigned int val, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff81080000)
Location: arch/x86/kernel/cpu/mce/dev-mcelog.c:36
Inline: False
```
**Symbols:**

```
ffffffff81080000-ffffffff8108012a: dev_mce_log (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dev_mce_log(struct notifier_block *nb, long unsigned int val, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff81087b10)
Location: arch/x86/kernel/cpu/mce/dev-mcelog.c:36
Inline: False
```
**Symbols:**

```
ffffffff81087b10-ffffffff81087c3a: dev_mce_log (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
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
int dev_mce_log(struct notifier_block *nb, long unsigned int val, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff810533b0)
Location: arch/x86/kernel/cpu/mce/dev-mcelog.c:40
Inline: False
```
**Symbols:**

```
ffffffff810533b0-ffffffff810534d0: dev_mce_log (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int dev_mce_log(struct notifier_block *nb, long unsigned int val, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff81043330)
Location: arch/x86/kernel/cpu/mce/dev-mcelog.c:40
Inline: False
```
**Symbols:**

```
ffffffff81043330-ffffffff81043450: dev_mce_log (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int dev_mce_log(struct notifier_block *nb, long unsigned int val, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff81053690)
Location: arch/x86/kernel/cpu/mce/dev-mcelog.c:40
Inline: False
```
**Symbols:**

```
ffffffff81053690-ffffffff810537b0: dev_mce_log (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int dev_mce_log(struct notifier_block *nb, long unsigned int val, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff81054b50)
Location: arch/x86/kernel/cpu/mce/dev-mcelog.c:40
Inline: False
```
**Symbols:**

```
ffffffff81054b50-ffffffff81054c70: dev_mce_log (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
