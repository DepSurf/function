# Function: <code>ptc_proc_open</code>

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
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ptc_proc_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/uv/tlb_uv.c (ffffffff81095040)
Location: arch/x86/platform/uv/tlb_uv.c:1661
Inline: False
```
**Symbols:**

```
ffffffff81095040-ffffffff8109505a: ptc_proc_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ptc_proc_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/uv/tlb_uv.c (ffffffff8109a3a0)
Location: arch/x86/platform/uv/tlb_uv.c:1661
Inline: False
```
**Symbols:**

```
ffffffff8109a3a0-ffffffff8109a3ba: ptc_proc_open (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ptc_proc_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/uv/tlb_uv.c (ffffffff81096500)
Location: arch/x86/platform/uv/tlb_uv.c:1661
Inline: False
```
**Symbols:**

```
ffffffff81096500-ffffffff8109651a: ptc_proc_open (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
