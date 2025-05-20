# Function: <code>perf_mmap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int perf_mmap(struct file *file, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81181110)
Location: kernel/events/core.c:4740
Inline: False
```
**Symbols:**

```
ffffffff81181110-ffffffff811816a3: perf_mmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int perf_mmap(struct file *file, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81192f00)
Location: kernel/events/core.c:5057
Inline: False
```
**Symbols:**

```
ffffffff81192f00-ffffffff8119349a: perf_mmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int perf_mmap(struct file *file, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811a26e0)
Location: kernel/events/core.c:5154
Inline: False
```
**Symbols:**

```
ffffffff811a26e0-ffffffff811a2c7b: perf_mmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int perf_mmap(struct file *file, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811a9d50)
Location: kernel/events/core.c:5246
Inline: False
```
**Symbols:**

```
ffffffff811a9d50-ffffffff811aa281: perf_mmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int perf_mmap(struct file *file, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811bd640)
Location: kernel/events/core.c:5196
Inline: False
```
**Symbols:**

```
ffffffff811bd640-ffffffff811bdb74: perf_mmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int perf_mmap(struct file *file, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811dd890)
Location: kernel/events/core.c:5553
Inline: False
```
**Symbols:**

```
ffffffff811dd890-ffffffff811dddba: perf_mmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int perf_mmap(struct file *file, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811edc90)
Location: kernel/events/core.c:5562
Inline: False
```
**Symbols:**

```
ffffffff811edc90-ffffffff811ee1c0: perf_mmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int perf_mmap(struct file *file, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (0)
Location: kernel/events/core.c:5608
Inline: False
```
**Symbols:**

```
ffffffff81205700-ffffffff81205bf6: perf_mmap (STB_LOCAL)
ffffffff8120a110-ffffffff8120a145: perf_mmap.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int perf_mmap(struct file *file, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81212a90)
Location: kernel/events/core.c:5704
Inline: False
```
**Symbols:**

```
ffffffff81212a90-ffffffff81212f90: perf_mmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int perf_mmap(struct file *file, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8123eb10)
Location: kernel/events/core.c:5973
Inline: False
```
**Symbols:**

```
ffffffff8123eb10-ffffffff8123f098: perf_mmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int perf_mmap(struct file *file, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81248f00)
Location: kernel/events/core.c:6053
Inline: False
```
**Symbols:**

```
ffffffff81248f00-ffffffff81249492: perf_mmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int perf_mmap(struct file *file, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8124d0d0)
Location: kernel/events/core.c:6137
Inline: False
```
**Symbols:**

```
ffffffff8124d0d0-ffffffff8124d658: perf_mmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int perf_mmap(struct file *file, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81286ce0)
Location: kernel/events/core.c:6253
Inline: False
```
**Symbols:**

```
ffffffff81286ce0-ffffffff81287270: perf_mmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int perf_mmap(struct file *file, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812db5b0)
Location: kernel/events/core.c:6151
Inline: False
```
**Symbols:**

```
ffffffff812db5b0-ffffffff812dbb26: perf_mmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int perf_mmap(struct file *file, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81343880)
Location: kernel/events/core.c:6369
Inline: False
```
**Symbols:**

```
ffffffff81343880-ffffffff81343dea: perf_mmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int perf_mmap(struct file *file, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff813748e0)
Location: kernel/events/core.c:6369
Inline: False
```
**Symbols:**

```
ffffffff813748e0-ffffffff81374e73: perf_mmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int perf_mmap(struct file *file, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8139dc10)
Location: kernel/events/core.c:6442
Inline: False
```
**Symbols:**

```
ffffffff8139dc10-ffffffff8139e1a3: perf_mmap (STB_LOCAL)
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
int perf_mmap(struct file *file, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffff80001029ceb0)
Location: kernel/events/core.c:5704
Inline: False
```
**Symbols:**

```
ffff80001029ceb0-ffff80001029d360: perf_mmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int perf_mmap(struct file *file, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c04cc504)
Location: kernel/events/core.c:5704
Inline: False
```
**Symbols:**

```
c04cc504-c04ccae4: perf_mmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int perf_mmap(struct file *file, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c00000000034d7d0)
Location: kernel/events/core.c:5704
Inline: False
```
**Symbols:**

```
c00000000034d7d0-c00000000034dde8: perf_mmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int perf_mmap(struct file *file, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffe0001cdf44)
Location: kernel/events/core.c:5704
Inline: False
```
**Symbols:**

```
ffffffe0001cdf44-ffffffe0001ce28c: perf_mmap (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int perf_mmap(struct file *file, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120b0e0)
Location: kernel/events/core.c:5704
Inline: False
```
**Symbols:**

```
ffffffff8120b0e0-ffffffff8120b5e0: perf_mmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int perf_mmap(struct file *file, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811fdeb0)
Location: kernel/events/core.c:5704
Inline: False
```
**Symbols:**

```
ffffffff811fdeb0-ffffffff811fe3b0: perf_mmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int perf_mmap(struct file *file, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81208e80)
Location: kernel/events/core.c:5704
Inline: False
```
**Symbols:**

```
ffffffff81208e80-ffffffff81209380: perf_mmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int perf_mmap(struct file *file, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81217c10)
Location: kernel/events/core.c:5704
Inline: False
```
**Symbols:**

```
ffffffff81217c10-ffffffff8121811a: perf_mmap (STB_LOCAL)
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
