# Function: <code>dax_entry_mkclean</code>

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
void dax_entry_mkclean(struct address_space *mapping, long unsigned int index, long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8130c310)
Location: fs/dax.c:770
Inline: False
Direct callers:
  - fs/dax.c:dax_writeback_mapping_range
```
**Symbols:**

```
ffffffff8130c310-ffffffff8130c523: dax_entry_mkclean (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void dax_entry_mkclean(struct address_space *mapping, long unsigned int index, long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff81333850)
Location: fs/dax.c:775
Inline: False
Direct callers:
  - fs/dax.c:dax_writeback_mapping_range
```
**Symbols:**

```
ffffffff81333850-ffffffff81333a73: dax_entry_mkclean (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void dax_entry_mkclean(struct address_space *mapping, long unsigned int index, long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff813473f0)
Location: fs/dax.c:776
Inline: False
Direct callers:
  - fs/dax.c:dax_writeback_mapping_range
```
**Symbols:**

```
ffffffff813473f0-ffffffff81347629: dax_entry_mkclean (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void dax_entry_mkclean(struct address_space *mapping, long unsigned int index, long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8138d7f0)
Location: fs/dax.c:776
Inline: False
Direct callers:
  - fs/dax.c:dax_writeback_one
```
**Symbols:**

```
ffffffff8138d7f0-ffffffff8138da46: dax_entry_mkclean (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void dax_entry_mkclean(struct address_space *mapping, long unsigned int index, long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8139f270)
Location: fs/dax.c:792
Inline: False
Direct callers:
  - fs/dax.c:dax_writeback_one
```
**Symbols:**

```
ffffffff8139f270-ffffffff8139f4be: dax_entry_mkclean (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void dax_entry_mkclean(struct address_space *mapping, long unsigned int index, long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff813a5fe0)
Location: fs/dax.c:804
Inline: False
Direct callers:
  - fs/dax.c:dax_writeback_one
```
**Symbols:**

```
ffffffff813a5fe0-ffffffff813a6228: dax_entry_mkclean (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void dax_entry_mkclean(struct address_space *mapping, long unsigned int index, long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff813f5a50)
Location: fs/dax.c:804
Inline: False
Direct callers:
  - fs/dax.c:dax_writeback_one
```
**Symbols:**

```
ffffffff813f5a50-ffffffff813f5c98: dax_entry_mkclean (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void dax_entry_mkclean(struct address_space *mapping, long unsigned int index, long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffff800010407618)
Location: fs/dax.c:776
Inline: False
Direct callers:
  - fs/dax.c:dax_writeback_mapping_range
```
**Symbols:**

```
ffff800010407618-ffff800010407818: dax_entry_mkclean (STB_LOCAL)
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
void dax_entry_mkclean(struct address_space *mapping, long unsigned int index, long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (c000000000512560)
Location: fs/dax.c:776
Inline: False
Direct callers:
  - fs/dax.c:dax_writeback_mapping_range
```
**Symbols:**

```
c000000000512560-c0000000005128b0: dax_entry_mkclean (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void dax_entry_mkclean(struct address_space *mapping, long unsigned int index, long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffe0002b2c9e)
Location: fs/dax.c:776
Inline: False
Direct callers:
  - fs/dax.c:dax_writeback_mapping_range
```
**Symbols:**

```
ffffffe0002b2c9e-ffffffe0002b2e6c: dax_entry_mkclean (STB_LOCAL)
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
void dax_entry_mkclean(struct address_space *mapping, long unsigned int index, long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8133f9d0)
Location: fs/dax.c:776
Inline: False
Direct callers:
  - fs/dax.c:dax_writeback_mapping_range
```
**Symbols:**

```
ffffffff8133f9d0-ffffffff8133fc09: dax_entry_mkclean (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void dax_entry_mkclean(struct address_space *mapping, long unsigned int index, long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff81330690)
Location: fs/dax.c:776
Inline: False
Direct callers:
  - fs/dax.c:dax_writeback_mapping_range
```
**Symbols:**

```
ffffffff81330690-ffffffff8133089a: dax_entry_mkclean (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void dax_entry_mkclean(struct address_space *mapping, long unsigned int index, long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8133d4a0)
Location: fs/dax.c:776
Inline: False
Direct callers:
  - fs/dax.c:dax_writeback_mapping_range
```
**Symbols:**

```
ffffffff8133d4a0-ffffffff8133d6d9: dax_entry_mkclean (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void dax_entry_mkclean(struct address_space *mapping, long unsigned int index, long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff813503e0)
Location: fs/dax.c:776
Inline: False
Direct callers:
  - fs/dax.c:dax_writeback_mapping_range
```
**Symbols:**

```
ffffffff813503e0-ffffffff813505fc: dax_entry_mkclean (STB_LOCAL)
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
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
