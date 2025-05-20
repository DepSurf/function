# Function: <code>mce_chrdev_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t mce_chrdev_read(struct file *filp, char *ubuf, size_t usize, loff_t *off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81043f30)
Location: arch/x86/kernel/cpu/mcheck/mce.c:1817
Inline: False
```
**Symbols:**

```
ffffffff81043f30-ffffffff8104423c: mce_chrdev_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t mce_chrdev_read(struct file *filp, char *ubuf, size_t usize, loff_t *off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81044070)
Location: arch/x86/kernel/cpu/mcheck/mce.c:1896
Inline: False
```
**Symbols:**

```
ffffffff81044070-ffffffff81044326: mce_chrdev_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t mce_chrdev_read(struct file *filp, char *ubuf, size_t usize, loff_t *off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81045b00)
Location: arch/x86/kernel/cpu/mcheck/mce.c:1959
Inline: False
```
**Symbols:**

```
ffffffff81045b00-ffffffff81045dd2: mce_chrdev_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t mce_chrdev_read(struct file *filp, char *ubuf, size_t usize, loff_t *off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/dev-mcelog.c (ffffffff8104c1f0)
Location: arch/x86/kernel/cpu/mcheck/dev-mcelog.c:230
Inline: False
```
**Symbols:**

```
ffffffff8104c1f0-ffffffff8104c4ff: mce_chrdev_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t mce_chrdev_read(struct file *filp, char *ubuf, size_t usize, loff_t *off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/dev-mcelog.c (ffffffff8104fca0)
Location: arch/x86/kernel/cpu/mcheck/dev-mcelog.c:204
Inline: False
```
**Symbols:**

```
ffffffff8104fca0-ffffffff8104fe25: mce_chrdev_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
ssize_t mce_chrdev_read(struct file *filp, char *ubuf, size_t usize, loff_t *off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/dev-mcelog.c (0)
Location: arch/x86/kernel/cpu/mcheck/dev-mcelog.c:204
Inline: False
```
**Symbols:**

```
ffffffff81052920-ffffffff81052a98: mce_chrdev_read (STB_LOCAL)
ffffffff81052d3d-ffffffff81052d49: mce_chrdev_read.cold.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
ssize_t mce_chrdev_read(struct file *filp, char *ubuf, size_t usize, loff_t *off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: arch/x86/kernel/cpu/mce/dev-mcelog.c:199
Inline: False
```
**Symbols:**

```
ffffffff8104ff80-ffffffff810500f8: mce_chrdev_read (STB_LOCAL)
ffffffff810503ad-ffffffff810503b9: mce_chrdev_read.cold.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
ssize_t mce_chrdev_read(struct file *filp, char *ubuf, size_t usize, loff_t *off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: arch/x86/kernel/cpu/mce/dev-mcelog.c:200
Inline: False
```
**Symbols:**

```
ffffffff81053080-ffffffff810531f8: mce_chrdev_read (STB_LOCAL)
ffffffff810534bd-ffffffff810534c9: mce_chrdev_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
ssize_t mce_chrdev_read(struct file *filp, char *ubuf, size_t usize, loff_t *off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: arch/x86/kernel/cpu/mce/dev-mcelog.c:200
Inline: False
```
**Symbols:**

```
ffffffff81053970-ffffffff81053ae8: mce_chrdev_read (STB_LOCAL)
ffffffff81053dad-ffffffff81053db9: mce_chrdev_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t mce_chrdev_read(struct file *filp, char *ubuf, size_t usize, loff_t *off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff81058850)
Location: arch/x86/kernel/cpu/mce/dev-mcelog.c:201
Inline: False
```
**Symbols:**

```
ffffffff81058850-ffffffff810589bd: mce_chrdev_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t mce_chrdev_read(struct file *filp, char *ubuf, size_t usize, loff_t *off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff81057650)
Location: arch/x86/kernel/cpu/mce/dev-mcelog.c:203
Inline: False
```
**Symbols:**

```
ffffffff81057650-ffffffff810577bd: mce_chrdev_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t mce_chrdev_read(struct file *filp, char *ubuf, size_t usize, loff_t *off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff81057fc0)
Location: arch/x86/kernel/cpu/mce/dev-mcelog.c:203
Inline: False
```
**Symbols:**

```
ffffffff81057fc0-ffffffff8105812d: mce_chrdev_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t mce_chrdev_read(struct file *filp, char *ubuf, size_t usize, loff_t *off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff81060e90)
Location: arch/x86/kernel/cpu/mce/dev-mcelog.c:203
Inline: False
```
**Symbols:**

```
ffffffff81060e90-ffffffff81060ffd: mce_chrdev_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t mce_chrdev_read(struct file *filp, char *ubuf, size_t usize, loff_t *off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff8106d820)
Location: arch/x86/kernel/cpu/mce/dev-mcelog.c:203
Inline: False
```
**Symbols:**

```
ffffffff8106d820-ffffffff8106d997: mce_chrdev_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t mce_chrdev_read(struct file *filp, char *ubuf, size_t usize, loff_t *off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff8107da90)
Location: arch/x86/kernel/cpu/mce/dev-mcelog.c:203
Inline: False
```
**Symbols:**

```
ffffffff8107da90-ffffffff8107dc07: mce_chrdev_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t mce_chrdev_read(struct file *filp, char *ubuf, size_t usize, loff_t *off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff8107fe70)
Location: arch/x86/kernel/cpu/mce/dev-mcelog.c:202
Inline: False
```
**Symbols:**

```
ffffffff8107fe70-ffffffff8107ffe6: mce_chrdev_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t mce_chrdev_read(struct file *filp, char *ubuf, size_t usize, loff_t *off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff81087980)
Location: arch/x86/kernel/cpu/mce/dev-mcelog.c:202
Inline: False
```
**Symbols:**

```
ffffffff81087980-ffffffff81087af6: mce_chrdev_read (STB_LOCAL)
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
ssize_t mce_chrdev_read(struct file *filp, char *ubuf, size_t usize, loff_t *off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: arch/x86/kernel/cpu/mce/dev-mcelog.c:200
Inline: False
```
**Symbols:**

```
ffffffff81053570-ffffffff810536c2: mce_chrdev_read (STB_LOCAL)
ffffffff8105392d-ffffffff81053939: mce_chrdev_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
ssize_t mce_chrdev_read(struct file *filp, char *ubuf, size_t usize, loff_t *off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: arch/x86/kernel/cpu/mce/dev-mcelog.c:200
Inline: False
```
**Symbols:**

```
ffffffff810435c0-ffffffff81043738: mce_chrdev_read (STB_LOCAL)
ffffffff810439fd-ffffffff81043a09: mce_chrdev_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
ssize_t mce_chrdev_read(struct file *filp, char *ubuf, size_t usize, loff_t *off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: arch/x86/kernel/cpu/mce/dev-mcelog.c:200
Inline: False
```
**Symbols:**

```
ffffffff81053920-ffffffff81053a98: mce_chrdev_read (STB_LOCAL)
ffffffff81053d5d-ffffffff81053d69: mce_chrdev_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
ssize_t mce_chrdev_read(struct file *filp, char *ubuf, size_t usize, loff_t *off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: arch/x86/kernel/cpu/mce/dev-mcelog.c:200
Inline: False
```
**Symbols:**

```
ffffffff81054e70-ffffffff81054fe8: mce_chrdev_read (STB_LOCAL)
ffffffff810551dd-ffffffff810551e9: mce_chrdev_read.cold (STB_LOCAL)
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
