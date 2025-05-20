# Function: <code>fuse_dax_page_mkwrite</code>

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
vm_fault_t fuse_dax_page_mkwrite(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dax.c (ffffffff8149c670)
Location: fs/fuse/dax.c:846
Inline: True
```
**Symbols:**

```
ffffffff8149c670-ffffffff8149c687: fuse_dax_page_mkwrite (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
vm_fault_t fuse_dax_page_mkwrite(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dax.c (ffffffff814a26a0)
Location: fs/fuse/dax.c:846
Inline: True
```
**Symbols:**

```
ffffffff814a26a0-ffffffff814a26b7: fuse_dax_page_mkwrite (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
vm_fault_t fuse_dax_page_mkwrite(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dax.c (ffffffff814fa750)
Location: fs/fuse/dax.c:845
Inline: True
```
**Symbols:**

```
ffffffff814fa750-ffffffff814fa767: fuse_dax_page_mkwrite (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
vm_fault_t fuse_dax_page_mkwrite(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dax.c (ffffffff8158aca0)
Location: fs/fuse/dax.c:842
Inline: True
```
**Symbols:**

```
ffffffff8158aca0-ffffffff8158acc1: fuse_dax_page_mkwrite (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
vm_fault_t fuse_dax_page_mkwrite(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dax.c (ffffffff81631400)
Location: fs/fuse/dax.c:842
Inline: True
```
**Symbols:**

```
ffffffff81631400-ffffffff81631421: fuse_dax_page_mkwrite (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
vm_fault_t fuse_dax_page_mkwrite(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dax.c (ffffffff81669640)
Location: fs/fuse/dax.c:842
Inline: True
```
**Symbols:**

```
ffffffff81669640-ffffffff81669661: fuse_dax_page_mkwrite (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
vm_fault_t fuse_dax_page_mkwrite(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dax.c (ffffffff816a3940)
Location: fs/fuse/dax.c:840
Inline: True
```
**Symbols:**

```
ffffffff816a3940-ffffffff816a3961: fuse_dax_page_mkwrite (STB_LOCAL)
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
