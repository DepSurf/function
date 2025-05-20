# Function: <code>ei_open</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ei_open(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/error-inject.c (ffffffff814f00f0)
Location: lib/error-inject.c:204
Inline: False
```
**Symbols:**

```
ffffffff814f00f0-ffffffff814f0105: ei_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ei_open(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/error-inject.c (ffffffff81504010)
Location: lib/error-inject.c:204
Inline: False
```
**Symbols:**

```
ffffffff81504010-ffffffff81504025: ei_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ei_open(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/error-inject.c (ffffffff81532180)
Location: lib/error-inject.c:204
Inline: False
```
**Symbols:**

```
ffffffff81532180-ffffffff81532195: ei_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ei_open(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/error-inject.c (ffffffff81552fc0)
Location: lib/error-inject.c:204
Inline: False
```
**Symbols:**

```
ffffffff81552fc0-ffffffff81552fd5: ei_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ei_open(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/error-inject.c (ffffffff815dc450)
Location: lib/error-inject.c:204
Inline: False
```
**Symbols:**

```
ffffffff815dc450-ffffffff815dc465: ei_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ei_open(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/error-inject.c (ffffffff815fa0f0)
Location: lib/error-inject.c:206
Inline: False
```
**Symbols:**

```
ffffffff815fa0f0-ffffffff815fa105: ei_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ei_open(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/error-inject.c (ffffffff815dccd0)
Location: lib/error-inject.c:206
Inline: False
```
**Symbols:**

```
ffffffff815dccd0-ffffffff815dcce5: ei_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ei_open(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/error-inject.c (ffffffff81648630)
Location: lib/error-inject.c:206
Inline: False
```
**Symbols:**

```
ffffffff81648630-ffffffff81648645: ei_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ei_open(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/error-inject.c (ffffffff8175ea40)
Location: lib/error-inject.c:207
Inline: False
```
**Symbols:**

```
ffffffff8175ea40-ffffffff8175ea5d: ei_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int ei_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/error-inject.c (ffffffff8188c380)
Location: lib/error-inject.c:213
Inline: True
```
**Symbols:**

```
ffffffff8188c380-ffffffff8188c3c9: ei_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int ei_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/error-inject.c (ffffffff818ce7f0)
Location: lib/error-inject.c:213
Inline: True
```
**Symbols:**

```
ffffffff818ce7f0-ffffffff818ce839: ei_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int ei_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/error-inject.c (ffffffff819205d0)
Location: lib/error-inject.c:213
Inline: True
```
**Symbols:**

```
ffffffff819205d0-ffffffff81920619: ei_open (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int ei_open(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/error-inject.c (ffff80001065f268)
Location: lib/error-inject.c:204
Inline: False
```
**Symbols:**

```
ffff80001065f268-ffff80001065f28c: ei_open (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ei_open(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/error-inject.c (c000000000811c90)
Location: lib/error-inject.c:204
Inline: False
```
**Symbols:**

```
c000000000811c90-c000000000811cc8: ei_open (STB_LOCAL)
```
</details>
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
int ei_open(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/error-inject.c (ffffffff8154b5a0)
Location: lib/error-inject.c:204
Inline: False
```
**Symbols:**

```
ffffffff8154b5a0-ffffffff8154b5b5: ei_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ei_open(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/error-inject.c (ffffffff8153b880)
Location: lib/error-inject.c:204
Inline: False
```
**Symbols:**

```
ffffffff8153b880-ffffffff8153b895: ei_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ei_open(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/error-inject.c (ffffffff815472e0)
Location: lib/error-inject.c:204
Inline: False
```
**Symbols:**

```
ffffffff815472e0-ffffffff815472f5: ei_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ei_open(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/error-inject.c (ffffffff81561130)
Location: lib/error-inject.c:204
Inline: False
```
**Symbols:**

```
ffffffff81561130-ffffffff81561145: ei_open (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct file *file</code>
</li>
<li>
<b>Param removed. </b>
<code>struct file *filp</code>
</li>
</ul>
</details>
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
