# Function: <code>gart_oldmem_pfn_is_ram</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int gart_oldmem_pfn_is_ram(long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/aperture_64.c (ffffffff8106e990)
Location: arch/x86/kernel/aperture_64.c:69
Inline: False
```
**Symbols:**

```
ffffffff8106e990-ffffffff8106e9bd: gart_oldmem_pfn_is_ram (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int gart_oldmem_pfn_is_ram(long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/aperture_64.c (ffffffff81071860)
Location: arch/x86/kernel/aperture_64.c:69
Inline: False
```
**Symbols:**

```
ffffffff81071860-ffffffff8107188d: gart_oldmem_pfn_is_ram (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int gart_oldmem_pfn_is_ram(long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/aperture_64.c (ffffffff81077880)
Location: arch/x86/kernel/aperture_64.c:69
Inline: False
```
**Symbols:**

```
ffffffff81077880-ffffffff810778ad: gart_oldmem_pfn_is_ram (STB_LOCAL)
```
</details>
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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool gart_oldmem_pfn_is_ram(struct vmcore_cb *cb, long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/aperture_64.c (ffffffff810a7260)
Location: arch/x86/kernel/aperture_64.c:77
Inline: False
```
**Symbols:**

```
ffffffff810a7260-ffffffff810a729f: gart_oldmem_pfn_is_ram (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool gart_oldmem_pfn_is_ram(struct vmcore_cb *cb, long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/aperture_64.c (ffffffff810c0550)
Location: arch/x86/kernel/aperture_64.c:77
Inline: False
```
**Symbols:**

```
ffffffff810c0550-ffffffff810c058f: gart_oldmem_pfn_is_ram (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool gart_oldmem_pfn_is_ram(struct vmcore_cb *cb, long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/aperture_64.c (ffffffff810c3c30)
Location: arch/x86/kernel/aperture_64.c:77
Inline: False
```
**Symbols:**

```
ffffffff810c3c30-ffffffff810c3c6f: gart_oldmem_pfn_is_ram (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool gart_oldmem_pfn_is_ram(struct vmcore_cb *cb, long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/aperture_64.c (ffffffff810cc070)
Location: arch/x86/kernel/aperture_64.c:77
Inline: False
```
**Symbols:**

```
ffffffff810cc070-ffffffff810cc0af: gart_oldmem_pfn_is_ram (STB_LOCAL)
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
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
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
