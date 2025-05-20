# Function: <code>free_pstore_private</code>

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
void free_pstore_private(struct pstore_private *private);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pstore/inode.c (ffffffff8137f6f0)
Location: fs/pstore/inode.c:62
Inline: False
Direct callers:
  - fs/pstore/inode.c:pstore_mkfile
  - fs/pstore/inode.c:pstore_evict_inode
```
**Symbols:**

```
ffffffff8137f6f0-ffffffff8137f72a: free_pstore_private (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void free_pstore_private(struct pstore_private *private);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pstore/inode.c (ffffffff813a4790)
Location: fs/pstore/inode.c:61
Inline: False
Direct callers:
  - fs/pstore/inode.c:pstore_mkfile
  - fs/pstore/inode.c:pstore_evict_inode
```
**Symbols:**

```
ffffffff813a4790-ffffffff813a47ca: free_pstore_private (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void free_pstore_private(struct pstore_private *private);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pstore/inode.c (ffffffff813d3b30)
Location: fs/pstore/inode.c:61
Inline: False
Direct callers:
  - fs/pstore/inode.c:pstore_mkfile
  - fs/pstore/inode.c:pstore_evict_inode
```
**Symbols:**

```
ffffffff813d3b30-ffffffff813d3b69: free_pstore_private (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void free_pstore_private(struct pstore_private *private);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pstore/inode.c (ffffffff813ee210)
Location: fs/pstore/inode.c:61
Inline: False
Direct callers:
  - fs/pstore/inode.c:pstore_mkfile
  - fs/pstore/inode.c:pstore_evict_inode
```
**Symbols:**

```
ffffffff813ee210-ffffffff813ee249: free_pstore_private (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void free_pstore_private(struct pstore_private *private);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pstore/inode.c (ffffffff8141a4b0)
Location: fs/pstore/inode.c:49
Inline: False
Direct callers:
  - fs/pstore/inode.c:pstore_mkfile
  - fs/pstore/inode.c:pstore_evict_inode
```
**Symbols:**

```
ffffffff8141a4b0-ffffffff8141a4ec: free_pstore_private (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void free_pstore_private(struct pstore_private *private);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pstore/inode.c (ffffffff81434320)
Location: fs/pstore/inode.c:49
Inline: False
Direct callers:
  - fs/pstore/inode.c:pstore_mkfile
  - fs/pstore/inode.c:pstore_evict_inode
```
**Symbols:**

```
ffffffff81434320-ffffffff8143435c: free_pstore_private (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/pstore/inode.c (ffffffff81484658)
Location: fs/pstore/inode.c:52
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_mkfile
  - fs/pstore/inode.c:pstore_evict_inode
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/pstore/inode.c (ffffffff814a1ca8)
Location: fs/pstore/inode.c:52
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_mkfile
  - fs/pstore/inode.c:pstore_evict_inode
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/pstore/inode.c (ffffffff814a7dd8)
Location: fs/pstore/inode.c:52
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_mkfile
  - fs/pstore/inode.c:pstore_evict_inode
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/pstore/inode.c (ffffffff815000d6)
Location: fs/pstore/inode.c:52
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_mkfile
  - fs/pstore/inode.c:pstore_evict_inode
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/pstore/inode.c (ffffffff815912aa)
Location: fs/pstore/inode.c:52
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_mkfile
  - fs/pstore/inode.c:pstore_evict_inode
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/pstore/inode.c (ffffffff8163888a)
Location: fs/pstore/inode.c:52
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_mkfile
  - fs/pstore/inode.c:pstore_evict_inode
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/pstore/inode.c (ffffffff81670c8a)
Location: fs/pstore/inode.c:52
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_mkfile
  - fs/pstore/inode.c:pstore_evict_inode
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/pstore/inode.c (ffffffff816acb48)
Location: fs/pstore/inode.c:55
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_mkfile
  - fs/pstore/inode.c:pstore_evict_inode
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
void free_pstore_private(struct pstore_private *private);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pstore/inode.c (ffff800010519f18)
Location: fs/pstore/inode.c:49
Inline: False
Direct callers:
  - fs/pstore/inode.c:pstore_mkfile
  - fs/pstore/inode.c:pstore_evict_inode
```
**Symbols:**

```
ffff800010519f18-ffff800010519f60: free_pstore_private (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void free_pstore_private(struct pstore_private *private);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pstore/inode.c (c06d4530)
Location: fs/pstore/inode.c:49
Inline: False
Direct callers:
  - fs/pstore/inode.c:pstore_mkfile
  - fs/pstore/inode.c:pstore_evict_inode
```
**Symbols:**

```
c06d4530-c06d4574: free_pstore_private (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void free_pstore_private(struct pstore_private *private);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pstore/inode.c (c000000000663780)
Location: fs/pstore/inode.c:49
Inline: False
Direct callers:
  - fs/pstore/inode.c:pstore_mkfile
  - fs/pstore/inode.c:pstore_evict_inode
```
**Symbols:**

```
c000000000663780-c0000000006637ec: free_pstore_private (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void free_pstore_private(struct pstore_private *private);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pstore/inode.c (ffffffe0003831b4)
Location: fs/pstore/inode.c:49
Inline: False
Direct callers:
  - fs/pstore/inode.c:pstore_mkfile
  - fs/pstore/inode.c:pstore_evict_inode
```
**Symbols:**

```
ffffffe0003831b4-ffffffe0003831f8: free_pstore_private (STB_LOCAL)
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
void free_pstore_private(struct pstore_private *private);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pstore/inode.c (ffffffff8142c900)
Location: fs/pstore/inode.c:49
Inline: False
Direct callers:
  - fs/pstore/inode.c:pstore_mkfile
  - fs/pstore/inode.c:pstore_evict_inode
```
**Symbols:**

```
ffffffff8142c900-ffffffff8142c93c: free_pstore_private (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void free_pstore_private(struct pstore_private *private);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pstore/inode.c (ffffffff8141d380)
Location: fs/pstore/inode.c:49
Inline: False
Direct callers:
  - fs/pstore/inode.c:pstore_mkfile
  - fs/pstore/inode.c:pstore_evict_inode
```
**Symbols:**

```
ffffffff8141d380-ffffffff8141d3bc: free_pstore_private (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void free_pstore_private(struct pstore_private *private);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pstore/inode.c (ffffffff81428aa0)
Location: fs/pstore/inode.c:49
Inline: False
Direct callers:
  - fs/pstore/inode.c:pstore_mkfile
  - fs/pstore/inode.c:pstore_evict_inode
```
**Symbols:**

```
ffffffff81428aa0-ffffffff81428adc: free_pstore_private (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void free_pstore_private(struct pstore_private *private);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pstore/inode.c (ffffffff8143f960)
Location: fs/pstore/inode.c:49
Inline: False
Direct callers:
  - fs/pstore/inode.c:pstore_mkfile
  - fs/pstore/inode.c:pstore_evict_inode
```
**Symbols:**

```
ffffffff8143f960-ffffffff8143f99c: free_pstore_private (STB_LOCAL)
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
