# Function: <code>microcode_write</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t microcode_write(struct file *file, const char *buf, size_t len, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8104c9e0)
Location: arch/x86/kernel/cpu/microcode/core.c:312
Inline: False
```
**Symbols:**

```
ffffffff8104c9e0-ffffffff8104caca: microcode_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t microcode_write(struct file *file, const char *buf, size_t len, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8104ca60)
Location: arch/x86/kernel/cpu/microcode/core.c:304
Inline: False
```
**Symbols:**

```
ffffffff8104ca60-ffffffff8104cb4c: microcode_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t microcode_write(struct file *file, const char *buf, size_t len, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8104ef70)
Location: arch/x86/kernel/cpu/microcode/core.c:379
Inline: False
```
**Symbols:**

```
ffffffff8104ef70-ffffffff8104f06a: microcode_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t microcode_write(struct file *file, const char *buf, size_t len, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8104ed60)
Location: arch/x86/kernel/cpu/microcode/core.c:419
Inline: False
```
**Symbols:**

```
ffffffff8104ed60-ffffffff8104ee59: microcode_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t microcode_write(struct file *file, const char *buf, size_t len, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff810526d0)
Location: arch/x86/kernel/cpu/microcode/core.c:433
Inline: False
```
**Symbols:**

```
ffffffff810526d0-ffffffff810527b2: microcode_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
ssize_t microcode_write(struct file *file, const char *buf, size_t len, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (0)
Location: arch/x86/kernel/cpu/microcode/core.c:433
Inline: False
```
**Symbols:**

```
ffffffff810553f0-ffffffff810554bb: microcode_write (STB_LOCAL)
ffffffff81055c5f-ffffffff81055c77: microcode_write.cold.8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
ssize_t microcode_write(struct file *file, const char *buf, size_t len, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (0)
Location: arch/x86/kernel/cpu/microcode/core.c:433
Inline: False
```
**Symbols:**

```
ffffffff81052a90-ffffffff81052b5b: microcode_write (STB_LOCAL)
ffffffff810532ff-ffffffff81053317: microcode_write.cold.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
ssize_t microcode_write(struct file *file, const char *buf, size_t len, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (0)
Location: arch/x86/kernel/cpu/microcode/core.c:430
Inline: False
```
**Symbols:**

```
ffffffff81055c40-ffffffff81055d0b: microcode_write (STB_LOCAL)
ffffffff810564d1-ffffffff810564e9: microcode_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
ssize_t microcode_write(struct file *file, const char *buf, size_t len, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (0)
Location: arch/x86/kernel/cpu/microcode/core.c:430
Inline: False
```
**Symbols:**

```
ffffffff81056580-ffffffff8105664b: microcode_write (STB_LOCAL)
ffffffff81056da0-ffffffff81056db8: microcode_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
ssize_t microcode_write(struct file *file, const char *buf, size_t len, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (0)
Location: arch/x86/kernel/cpu/microcode/core.c:425
Inline: False
```
**Symbols:**

```
ffffffff8105b950-ffffffff8105ba58: microcode_write (STB_LOCAL)
ffffffff8105bfa9-ffffffff8105bfc1: microcode_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
ssize_t microcode_write(struct file *file, const char *buf, size_t len, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (0)
Location: arch/x86/kernel/cpu/microcode/core.c:423
Inline: False
```
**Symbols:**

```
ffffffff8105a3a0-ffffffff8105a4a8: microcode_write (STB_LOCAL)
ffffffff81bd5f1c-ffffffff81bd5f34: microcode_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
ssize_t microcode_write(struct file *file, const char *buf, size_t len, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (0)
Location: arch/x86/kernel/cpu/microcode/core.c:423
Inline: False
```
**Symbols:**

```
ffffffff8105ad40-ffffffff8105ae48: microcode_write (STB_LOCAL)
ffffffff81bc82c8-ffffffff81bc82e0: microcode_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
ssize_t microcode_write(struct file *file, const char *buf, size_t len, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (0)
Location: arch/x86/kernel/cpu/microcode/core.c:423
Inline: False
```
**Symbols:**

```
ffffffff81064280-ffffffff81064388: microcode_write (STB_LOCAL)
ffffffff81c9c143-ffffffff81c9c15b: microcode_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
ssize_t microcode_write(struct file *file, const char *buf, size_t len, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (0)
Location: arch/x86/kernel/cpu/microcode/core.c:430
Inline: False
```
**Symbols:**

```
ffffffff81056100-ffffffff810561cb: microcode_write (STB_LOCAL)
ffffffff81056920-ffffffff81056938: microcode_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
ssize_t microcode_write(struct file *file, const char *buf, size_t len, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (0)
Location: arch/x86/kernel/cpu/microcode/core.c:430
Inline: False
```
**Symbols:**

```
ffffffff81046310-ffffffff810463db: microcode_write (STB_LOCAL)
ffffffff81046b30-ffffffff81046b48: microcode_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
ssize_t microcode_write(struct file *file, const char *buf, size_t len, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (0)
Location: arch/x86/kernel/cpu/microcode/core.c:430
Inline: False
```
**Symbols:**

```
ffffffff81056530-ffffffff810565fb: microcode_write (STB_LOCAL)
ffffffff81056d50-ffffffff81056d68: microcode_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
ssize_t microcode_write(struct file *file, const char *buf, size_t len, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (0)
Location: arch/x86/kernel/cpu/microcode/core.c:430
Inline: False
```
**Symbols:**

```
ffffffff81057a80-ffffffff81057b4b: microcode_write (STB_LOCAL)
ffffffff81058210-ffffffff81058228: microcode_write.cold (STB_LOCAL)
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
