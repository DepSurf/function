# Function: <code>mtrr_write</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t mtrr_write(struct file *file, const char *buf, size_t len, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/if.c (ffffffff8104af70)
Location: arch/x86/kernel/cpu/mtrr/if.c:94
Inline: False
```
**Symbols:**

```
ffffffff8104af70-ffffffff8104b1d8: mtrr_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t mtrr_write(struct file *file, const char *buf, size_t len, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/if.c (ffffffff8104b0c0)
Location: arch/x86/kernel/cpu/mtrr/if.c:93
Inline: False
```
**Symbols:**

```
ffffffff8104b0c0-ffffffff8104b340: mtrr_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t mtrr_write(struct file *file, const char *buf, size_t len, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/if.c (ffffffff8104d520)
Location: arch/x86/kernel/cpu/mtrr/if.c:93
Inline: False
```
**Symbols:**

```
ffffffff8104d520-ffffffff8104d7a0: mtrr_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t mtrr_write(struct file *file, const char *buf, size_t len, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/if.c (ffffffff8104d580)
Location: arch/x86/kernel/cpu/mtrr/if.c:93
Inline: False
```
**Symbols:**

```
ffffffff8104d580-ffffffff8104d7f0: mtrr_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t mtrr_write(struct file *file, const char *buf, size_t len, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/if.c (ffffffff81050ee0)
Location: arch/x86/kernel/cpu/mtrr/if.c:94
Inline: False
```
**Symbols:**

```
ffffffff81050ee0-ffffffff81051150: mtrr_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
ssize_t mtrr_write(struct file *file, const char *buf, size_t len, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/if.c (0)
Location: arch/x86/kernel/cpu/mtrr/if.c:94
Inline: False
```
**Symbols:**

```
ffffffff81053b90-ffffffff81053da8: mtrr_write (STB_LOCAL)
ffffffff81054492-ffffffff810544aa: mtrr_write.cold.3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
ssize_t mtrr_write(struct file *file, const char *buf, size_t len, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/if.c (0)
Location: arch/x86/kernel/cpu/mtrr/if.c:94
Inline: False
```
**Symbols:**

```
ffffffff81051210-ffffffff81051428: mtrr_write (STB_LOCAL)
ffffffff81051b32-ffffffff81051b4a: mtrr_write.cold.3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
ssize_t mtrr_write(struct file *file, const char *buf, size_t len, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/if.c (0)
Location: arch/x86/kernel/cpu/mtrr/if.c:94
Inline: False
```
**Symbols:**

```
ffffffff81054340-ffffffff81054559: mtrr_write (STB_LOCAL)
ffffffff81054c42-ffffffff81054c5a: mtrr_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
ssize_t mtrr_write(struct file *file, const char *buf, size_t len, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/if.c (0)
Location: arch/x86/kernel/cpu/mtrr/if.c:94
Inline: False
```
**Symbols:**

```
ffffffff81054c20-ffffffff81054e39: mtrr_write (STB_LOCAL)
ffffffff81055522-ffffffff8105553a: mtrr_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
ssize_t mtrr_write(struct file *file, const char *buf, size_t len, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/if.c (0)
Location: arch/x86/kernel/cpu/mtrr/if.c:94
Inline: False
```
**Symbols:**

```
ffffffff81059b80-ffffffff81059d6f: mtrr_write (STB_LOCAL)
ffffffff8105a552-ffffffff8105a56a: mtrr_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
ssize_t mtrr_write(struct file *file, const char *buf, size_t len, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/if.c (0)
Location: arch/x86/kernel/cpu/mtrr/if.c:94
Inline: False
```
**Symbols:**

```
ffffffff810586f0-ffffffff810588df: mtrr_write (STB_LOCAL)
ffffffff81bd5d6b-ffffffff81bd5d83: mtrr_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
ssize_t mtrr_write(struct file *file, const char *buf, size_t len, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/if.c (0)
Location: arch/x86/kernel/cpu/mtrr/if.c:94
Inline: False
```
**Symbols:**

```
ffffffff81059040-ffffffff81059233: mtrr_write (STB_LOCAL)
ffffffff81bc811f-ffffffff81bc8137: mtrr_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
ssize_t mtrr_write(struct file *file, const char *buf, size_t len, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/if.c (0)
Location: arch/x86/kernel/cpu/mtrr/if.c:94
Inline: False
```
**Symbols:**

```
ffffffff81062260-ffffffff81062453: mtrr_write (STB_LOCAL)
ffffffff81c9bf64-ffffffff81c9bf7c: mtrr_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
ssize_t mtrr_write(struct file *file, const char *buf, size_t len, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/if.c (0)
Location: arch/x86/kernel/cpu/mtrr/if.c:94
Inline: False
```
**Symbols:**

```
ffffffff8106ecd0-ffffffff8106eed5: mtrr_write (STB_LOCAL)
ffffffff81e4b39a-ffffffff81e4b3b2: mtrr_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t mtrr_write(struct file *file, const char *buf, size_t len, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/if.c (ffffffff8107ee70)
Location: arch/x86/kernel/cpu/mtrr/if.c:94
Inline: False
```
**Symbols:**

```
ffffffff8107ee70-ffffffff8107f08d: mtrr_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t mtrr_write(struct file *file, const char *buf, size_t len, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/if.c (ffffffff81080ff0)
Location: arch/x86/kernel/cpu/mtrr/if.c:94
Inline: False
```
**Symbols:**

```
ffffffff81080ff0-ffffffff81081212: mtrr_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t mtrr_write(struct file *file, const char *buf, size_t len, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/if.c (ffffffff81088b00)
Location: arch/x86/kernel/cpu/mtrr/if.c:94
Inline: False
```
**Symbols:**

```
ffffffff81088b00-ffffffff81088d22: mtrr_write (STB_LOCAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
ssize_t mtrr_write(struct file *file, const char *buf, size_t len, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/if.c (0)
Location: arch/x86/kernel/cpu/mtrr/if.c:94
Inline: False
```
**Symbols:**

```
ffffffff810547a0-ffffffff810549b9: mtrr_write (STB_LOCAL)
ffffffff810550a2-ffffffff810550ba: mtrr_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
ssize_t mtrr_write(struct file *file, const char *buf, size_t len, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/if.c (0)
Location: arch/x86/kernel/cpu/mtrr/if.c:94
Inline: False
```
**Symbols:**

```
ffffffff81044820-ffffffff81044a39: mtrr_write (STB_LOCAL)
ffffffff81045122-ffffffff8104513a: mtrr_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
ssize_t mtrr_write(struct file *file, const char *buf, size_t len, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/if.c (0)
Location: arch/x86/kernel/cpu/mtrr/if.c:94
Inline: False
```
**Symbols:**

```
ffffffff81054bd0-ffffffff81054de9: mtrr_write (STB_LOCAL)
ffffffff810554d2-ffffffff810554ea: mtrr_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
ssize_t mtrr_write(struct file *file, const char *buf, size_t len, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/if.c (0)
Location: arch/x86/kernel/cpu/mtrr/if.c:94
Inline: False
```
**Symbols:**

```
ffffffff81056050-ffffffff81056269: mtrr_write (STB_LOCAL)
ffffffff81056952-ffffffff8105696a: mtrr_write.cold (STB_LOCAL)
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
