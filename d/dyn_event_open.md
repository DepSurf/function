# Function: <code>dyn_event_open</code>

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
int dyn_event_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_dynevent.c (ffffffff811ba850)
Location: kernel/trace/trace_dynevent.c:169
Inline: False
```
**Symbols:**

```
ffffffff811ba850-ffffffff811ba88d: dyn_event_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int dyn_event_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_dynevent.c (ffffffff811c98f0)
Location: kernel/trace/trace_dynevent.c:169
Inline: False
```
**Symbols:**

```
ffffffff811c98f0-ffffffff811c992f: dyn_event_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int dyn_event_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_dynevent.c (ffffffff811d5610)
Location: kernel/trace/trace_dynevent.c:173
Inline: True
```
**Symbols:**

```
ffffffff811d5610-ffffffff811d565b: dyn_event_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int dyn_event_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_dynevent.c (ffffffff811f1c80)
Location: kernel/trace/trace_dynevent.c:173
Inline: True
```
**Symbols:**

```
ffffffff811f1c80-ffffffff811f1ccd: dyn_event_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int dyn_event_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_dynevent.c (ffffffff811f06b0)
Location: kernel/trace/trace_dynevent.c:173
Inline: True
```
**Symbols:**

```
ffffffff811f06b0-ffffffff811f06fd: dyn_event_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int dyn_event_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_dynevent.c (ffffffff811f1610)
Location: kernel/trace/trace_dynevent.c:184
Inline: True
```
**Symbols:**

```
ffffffff811f1610-ffffffff811f165d: dyn_event_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int dyn_event_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_dynevent.c (ffffffff812227b0)
Location: kernel/trace/trace_dynevent.c:222
Inline: True
```
**Symbols:**

```
ffffffff812227b0-ffffffff812227fd: dyn_event_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int dyn_event_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_dynevent.c (ffffffff812625c0)
Location: kernel/trace/trace_dynevent.c:222
Inline: True
```
**Symbols:**

```
ffffffff812625c0-ffffffff81262615: dyn_event_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int dyn_event_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_dynevent.c (ffffffff812b3dc0)
Location: kernel/trace/trace_dynevent.c:224
Inline: True
```
**Symbols:**

```
ffffffff812b3dc0-ffffffff812b3e15: dyn_event_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int dyn_event_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_dynevent.c (ffffffff812d66d0)
Location: kernel/trace/trace_dynevent.c:224
Inline: True
```
**Symbols:**

```
ffffffff812d66d0-ffffffff812d6719: dyn_event_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int dyn_event_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_dynevent.c (ffffffff812f41e0)
Location: kernel/trace/trace_dynevent.c:224
Inline: True
```
**Symbols:**

```
ffffffff812f41e0-ffffffff812f4229: dyn_event_open (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int dyn_event_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_dynevent.c (ffff800010255898)
Location: kernel/trace/trace_dynevent.c:173
Inline: True
```
**Symbols:**

```
ffff800010255898-ffff8000102558f8: dyn_event_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int dyn_event_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_dynevent.c (c0488a4c)
Location: kernel/trace/trace_dynevent.c:173
Inline: True
```
**Symbols:**

```
c0488a4c-c0488ab0: dyn_event_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int dyn_event_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_dynevent.c (c0000000002f5900)
Location: kernel/trace/trace_dynevent.c:173
Inline: True
```
**Symbols:**

```
c0000000002f5900-c0000000002f5994: dyn_event_open (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int dyn_event_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_dynevent.c (ffffffff811cdc30)
Location: kernel/trace/trace_dynevent.c:173
Inline: True
```
**Symbols:**

```
ffffffff811cdc30-ffffffff811cdc7b: dyn_event_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int dyn_event_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_dynevent.c (ffffffff811c0a00)
Location: kernel/trace/trace_dynevent.c:173
Inline: True
```
**Symbols:**

```
ffffffff811c0a00-ffffffff811c0a4b: dyn_event_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int dyn_event_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_dynevent.c (ffffffff811cba00)
Location: kernel/trace/trace_dynevent.c:173
Inline: True
```
**Symbols:**

```
ffffffff811cba00-ffffffff811cba4b: dyn_event_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int dyn_event_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_dynevent.c (ffffffff811d9c60)
Location: kernel/trace/trace_dynevent.c:173
Inline: True
```
**Symbols:**

```
ffffffff811d9c60-ffffffff811d9cab: dyn_event_open (STB_LOCAL)
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
