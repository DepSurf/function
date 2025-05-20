# Function: <code>sgx_get_unmapped_area</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
long unsigned int sgx_get_unmapped_area(struct file *file, long unsigned int addr, long unsigned int len, long unsigned int pgoff, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/driver.c (ffffffff81065630)
Location: arch/x86/kernel/cpu/sgx/driver.c:104
Inline: True
```
**Symbols:**

```
ffffffff81065630-ffffffff81065675: sgx_get_unmapped_area (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
long unsigned int sgx_get_unmapped_area(struct file *file, long unsigned int addr, long unsigned int len, long unsigned int pgoff, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/driver.c (ffffffff81065d00)
Location: arch/x86/kernel/cpu/sgx/driver.c:104
Inline: True
```
**Symbols:**

```
ffffffff81065d00-ffffffff81065d45: sgx_get_unmapped_area (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
long unsigned int sgx_get_unmapped_area(struct file *file, long unsigned int addr, long unsigned int len, long unsigned int pgoff, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/driver.c (ffffffff8106fe20)
Location: arch/x86/kernel/cpu/sgx/driver.c:104
Inline: True
```
**Symbols:**

```
ffffffff8106fe20-ffffffff8106fe65: sgx_get_unmapped_area (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
long unsigned int sgx_get_unmapped_area(struct file *file, long unsigned int addr, long unsigned int len, long unsigned int pgoff, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/driver.c (ffffffff8107d700)
Location: arch/x86/kernel/cpu/sgx/driver.c:104
Inline: True
```
**Symbols:**

```
ffffffff8107d700-ffffffff8107d77c: sgx_get_unmapped_area (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
long unsigned int sgx_get_unmapped_area(struct file *file, long unsigned int addr, long unsigned int len, long unsigned int pgoff, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/driver.c (ffffffff8108ec50)
Location: arch/x86/kernel/cpu/sgx/driver.c:104
Inline: True
```
**Symbols:**

```
ffffffff8108ec50-ffffffff8108eccc: sgx_get_unmapped_area (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
long unsigned int sgx_get_unmapped_area(struct file *file, long unsigned int addr, long unsigned int len, long unsigned int pgoff, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/driver.c (ffffffff81091a70)
Location: arch/x86/kernel/cpu/sgx/driver.c:104
Inline: True
```
**Symbols:**

```
ffffffff81091a70-ffffffff81091aec: sgx_get_unmapped_area (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
long unsigned int sgx_get_unmapped_area(struct file *file, long unsigned int addr, long unsigned int len, long unsigned int pgoff, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/driver.c (ffffffff81098e20)
Location: arch/x86/kernel/cpu/sgx/driver.c:104
Inline: True
```
**Symbols:**

```
ffffffff81098e20-ffffffff81098e9c: sgx_get_unmapped_area (STB_LOCAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
