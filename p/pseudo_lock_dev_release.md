# Function: <code>pseudo_lock_dev_release</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pseudo_lock_dev_release(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8105c050)
Location: arch/x86/kernel/cpu/resctrl/pseudo_lock.c:1455
Inline: False
```
**Symbols:**

```
ffffffff8105c050-ffffffff8105c0ad: pseudo_lock_dev_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int pseudo_lock_dev_release(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (0)
Location: arch/x86/kernel/cpu/resctrl/pseudo_lock.c:1444
Inline: False
```
**Symbols:**

```
ffffffff8105f560-ffffffff8105f5ac: pseudo_lock_dev_release (STB_LOCAL)
ffffffff81060e45-ffffffff81060e69: pseudo_lock_dev_release.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int pseudo_lock_dev_release(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8105fc80)
Location: arch/x86/kernel/cpu/resctrl/pseudo_lock.c:1444
Inline: False
```
**Symbols:**

```
ffffffff8105fc80-ffffffff8105fcde: pseudo_lock_dev_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pseudo_lock_dev_release(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff810657c0)
Location: arch/x86/kernel/cpu/resctrl/pseudo_lock.c:1444
Inline: False
```
**Symbols:**

```
ffffffff810657c0-ffffffff81065824: pseudo_lock_dev_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pseudo_lock_dev_release(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81063a70)
Location: arch/x86/kernel/cpu/resctrl/pseudo_lock.c:1444
Inline: False
```
**Symbols:**

```
ffffffff81063a70-ffffffff81063ad4: pseudo_lock_dev_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pseudo_lock_dev_release(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81064110)
Location: arch/x86/kernel/cpu/resctrl/pseudo_lock.c:1444
Inline: False
```
**Symbols:**

```
ffffffff81064110-ffffffff81064174: pseudo_lock_dev_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pseudo_lock_dev_release(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8106e100)
Location: arch/x86/kernel/cpu/resctrl/pseudo_lock.c:1450
Inline: False
```
**Symbols:**

```
ffffffff8106e100-ffffffff8106e164: pseudo_lock_dev_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pseudo_lock_dev_release(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8107b930)
Location: arch/x86/kernel/cpu/resctrl/pseudo_lock.c:1450
Inline: False
```
**Symbols:**

```
ffffffff8107b930-ffffffff8107b9a4: pseudo_lock_dev_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pseudo_lock_dev_release(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8108cd20)
Location: arch/x86/kernel/cpu/resctrl/pseudo_lock.c:1456
Inline: False
```
**Symbols:**

```
ffffffff8108cd20-ffffffff8108cd94: pseudo_lock_dev_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int pseudo_lock_dev_release(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8108fe70)
Location: arch/x86/kernel/cpu/resctrl/pseudo_lock.c:1456
Inline: True
```
**Symbols:**

```
ffffffff8108fe70-ffffffff8108fee4: pseudo_lock_dev_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int pseudo_lock_dev_release(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81097200)
Location: arch/x86/kernel/cpu/resctrl/pseudo_lock.c:1470
Inline: True
```
**Symbols:**

```
ffffffff81097200-ffffffff81097274: pseudo_lock_dev_release (STB_LOCAL)
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
int pseudo_lock_dev_release(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8105f800)
Location: arch/x86/kernel/cpu/resctrl/pseudo_lock.c:1444
Inline: False
```
**Symbols:**

```
ffffffff8105f800-ffffffff8105f85e: pseudo_lock_dev_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int pseudo_lock_dev_release(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8104fb30)
Location: arch/x86/kernel/cpu/resctrl/pseudo_lock.c:1444
Inline: False
```
**Symbols:**

```
ffffffff8104fb30-ffffffff8104fb8e: pseudo_lock_dev_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int pseudo_lock_dev_release(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8105fc30)
Location: arch/x86/kernel/cpu/resctrl/pseudo_lock.c:1444
Inline: False
```
**Symbols:**

```
ffffffff8105fc30-ffffffff8105fc8e: pseudo_lock_dev_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int pseudo_lock_dev_release(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81061190)
Location: arch/x86/kernel/cpu/resctrl/pseudo_lock.c:1444
Inline: False
```
**Symbols:**

```
ffffffff81061190-ffffffff810611ee: pseudo_lock_dev_release (STB_LOCAL)
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
