# Function: <code>pwm_debugfs_open</code>

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
int pwm_debugfs_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff81642030)
Location: drivers/pwm/core.c:1337
Inline: True
```
**Symbols:**

```
ffffffff81642030-ffffffff81642072: pwm_debugfs_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int pwm_debugfs_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff81624fb0)
Location: drivers/pwm/core.c:1307
Inline: True
```
**Symbols:**

```
ffffffff81624fb0-ffffffff81624ff2: pwm_debugfs_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int pwm_debugfs_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff816947c0)
Location: drivers/pwm/core.c:1235
Inline: True
```
**Symbols:**

```
ffffffff816947c0-ffffffff81694802: pwm_debugfs_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int pwm_debugfs_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff817b5320)
Location: drivers/pwm/core.c:1289
Inline: True
```
**Symbols:**

```
ffffffff817b5320-ffffffff817b536e: pwm_debugfs_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int pwm_debugfs_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff818cf860)
Location: drivers/pwm/core.c:1187
Inline: True
```
**Symbols:**

```
ffffffff818cf860-ffffffff818cf8ae: pwm_debugfs_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int pwm_debugfs_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff81912810)
Location: drivers/pwm/core.c:1130
Inline: True
```
**Symbols:**

```
ffffffff81912810-ffffffff8191285e: pwm_debugfs_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int pwm_debugfs_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff8195a5d0)
Location: drivers/pwm/core.c:1124
Inline: True
```
**Symbols:**

```
ffffffff8195a5d0-ffffffff8195a61e: pwm_debugfs_open (STB_LOCAL)
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
