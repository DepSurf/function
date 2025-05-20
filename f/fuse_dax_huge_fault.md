# Function: <code>fuse_dax_huge_fault</code>

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
<summary>In <code>5.11</code>: ✅</summary>

```c
vm_fault_t fuse_dax_huge_fault(struct vm_fault *vmf, enum page_entry_size pe_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dax.c (ffffffff8149c690)
Location: fs/fuse/dax.c:840
Inline: False
```
**Symbols:**

```
ffffffff8149c690-ffffffff8149c6a6: fuse_dax_huge_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
vm_fault_t fuse_dax_huge_fault(struct vm_fault *vmf, enum page_entry_size pe_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dax.c (ffffffff814a26c0)
Location: fs/fuse/dax.c:840
Inline: False
```
**Symbols:**

```
ffffffff814a26c0-ffffffff814a26d6: fuse_dax_huge_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
vm_fault_t fuse_dax_huge_fault(struct vm_fault *vmf, enum page_entry_size pe_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dax.c (ffffffff814fa770)
Location: fs/fuse/dax.c:839
Inline: False
```
**Symbols:**

```
ffffffff814fa770-ffffffff814fa786: fuse_dax_huge_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
vm_fault_t fuse_dax_huge_fault(struct vm_fault *vmf, enum page_entry_size pe_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dax.c (ffffffff8158acd0)
Location: fs/fuse/dax.c:836
Inline: False
```
**Symbols:**

```
ffffffff8158acd0-ffffffff8158acf0: fuse_dax_huge_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
vm_fault_t fuse_dax_huge_fault(struct vm_fault *vmf, enum page_entry_size pe_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dax.c (ffffffff81631440)
Location: fs/fuse/dax.c:836
Inline: False
```
**Symbols:**

```
ffffffff81631440-ffffffff81631460: fuse_dax_huge_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
vm_fault_t fuse_dax_huge_fault(struct vm_fault *vmf, enum page_entry_size pe_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dax.c (ffffffff81669680)
Location: fs/fuse/dax.c:836
Inline: False
```
**Symbols:**

```
ffffffff81669680-ffffffff816696a0: fuse_dax_huge_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
vm_fault_t fuse_dax_huge_fault(struct vm_fault *vmf, unsigned int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dax.c (ffffffff816a3980)
Location: fs/fuse/dax.c:835
Inline: False
```
**Symbols:**

```
ffffffff816a3980-ffffffff816a39a0: fuse_dax_huge_fault (STB_LOCAL)
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int order</code>
</li>
<li>
<b>Param removed. </b>
<code>enum page_entry_size pe_size</code>
</li>
</ul>
</details>
</li>
</ul>
