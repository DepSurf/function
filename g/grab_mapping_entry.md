# Function: <code>grab_mapping_entry</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff812879e7)
Location: fs/dax.c:410
Inline: True
Inline callers:
  - fs/dax.c:dax_fault
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *grab_mapping_entry(struct address_space *mapping, long unsigned int index, long unsigned int size_flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8129bda0)
Location: fs/dax.c:312
Inline: False
Direct callers:
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_fault
```
**Symbols:**

```
ffffffff8129bda0-ffffffff8129c1a0: grab_mapping_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *grab_mapping_entry(struct address_space *mapping, long unsigned int index, long unsigned int size_flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff812aabc0)
Location: fs/dax.c:324
Inline: False
Direct callers:
  - fs/dax.c:dax_iomap_fault
  - fs/dax.c:dax_iomap_fault
```
**Symbols:**

```
ffffffff812aabc0-ffffffff812aae52: grab_mapping_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *grab_mapping_entry(struct address_space *mapping, long unsigned int index, long unsigned int size_flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff812ce3f0)
Location: fs/dax.c:327
Inline: False
Direct callers:
  - fs/dax.c:dax_iomap_fault
  - fs/dax.c:dax_iomap_fault
```
**Symbols:**

```
ffffffff812ce3f0-ffffffff812ce685: grab_mapping_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *grab_mapping_entry(struct address_space *mapping, long unsigned int index, long unsigned int size_flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff812f8a00)
Location: fs/dax.c:500
Inline: False
```
**Symbols:**

```
ffffffff812f8a00-ffffffff812f8c8d: grab_mapping_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *grab_mapping_entry(struct xa_state *xas, struct address_space *mapping, long unsigned int size_flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8130cc70)
Location: fs/dax.c:470
Inline: False
```
**Symbols:**

```
ffffffff8130cc70-ffffffff8130cea5: grab_mapping_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *grab_mapping_entry(struct xa_state *xas, struct address_space *mapping, unsigned int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff81335300)
Location: fs/dax.c:475
Inline: False
```
**Symbols:**

```
ffffffff81335300-ffffffff81335530: grab_mapping_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *grab_mapping_entry(struct xa_state *xas, struct address_space *mapping, unsigned int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff81348ef0)
Location: fs/dax.c:476
Inline: False
```
**Symbols:**

```
ffffffff81348ef0-ffffffff8134912d: grab_mapping_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *grab_mapping_entry(struct xa_state *xas, struct address_space *mapping, unsigned int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8138e270)
Location: fs/dax.c:476
Inline: False
Direct callers:
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pte_fault
```
**Symbols:**

```
ffffffff8138e270-ffffffff8138e4ad: grab_mapping_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *grab_mapping_entry(struct xa_state *xas, struct address_space *mapping, unsigned int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8139f9c0)
Location: fs/dax.c:476
Inline: False
Direct callers:
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pte_fault
```
**Symbols:**

```
ffffffff8139f9c0-ffffffff8139fbfd: grab_mapping_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *grab_mapping_entry(struct xa_state *xas, struct address_space *mapping, unsigned int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff813a6fb0)
Location: fs/dax.c:487
Inline: False
Direct callers:
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pte_fault
```
**Symbols:**

```
ffffffff813a6fb0-ffffffff813a71c8: grab_mapping_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *grab_mapping_entry(struct xa_state *xas, struct address_space *mapping, unsigned int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff813f6e70)
Location: fs/dax.c:487
Inline: False
Direct callers:
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pte_fault
```
**Symbols:**

```
ffffffff813f6e70-ffffffff813f708e: grab_mapping_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *grab_mapping_entry(struct xa_state *xas, struct address_space *mapping, unsigned int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff814692c0)
Location: fs/dax.c:487
Inline: False
Direct callers:
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pte_fault
```
**Symbols:**

```
ffffffff814692c0-ffffffff814694be: grab_mapping_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *grab_mapping_entry(struct xa_state *xas, struct address_space *mapping, unsigned int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff814f9d50)
Location: fs/dax.c:587
Inline: False
Direct callers:
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pte_fault
```
**Symbols:**

```
ffffffff814f9d50-ffffffff814f9f4e: grab_mapping_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *grab_mapping_entry(struct xa_state *xas, struct address_space *mapping, unsigned int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff815311d0)
Location: fs/dax.c:587
Inline: False
Direct callers:
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pte_fault
```
**Symbols:**

```
ffffffff815311d0-ffffffff815313c8: grab_mapping_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *grab_mapping_entry(struct xa_state *xas, struct address_space *mapping, unsigned int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff815660b0)
Location: fs/dax.c:573
Inline: False
Direct callers:
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pte_fault
```
**Symbols:**

```
ffffffff815660b0-ffffffff815662a8: grab_mapping_entry (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffff800010409ad4)
Location: fs/dax.c:476
Inline: True
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
void *grab_mapping_entry(struct xa_state *xas, struct address_space *mapping, unsigned int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (c0000000005158c0)
Location: fs/dax.c:476
Inline: False
```
**Symbols:**

```
c0000000005158c0-c000000000515c9c: grab_mapping_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffe0002b3796)
Location: fs/dax.c:476
Inline: True
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
void *grab_mapping_entry(struct xa_state *xas, struct address_space *mapping, unsigned int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff813414d0)
Location: fs/dax.c:476
Inline: False
```
**Symbols:**

```
ffffffff813414d0-ffffffff8134170d: grab_mapping_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *grab_mapping_entry(struct xa_state *xas, struct address_space *mapping, unsigned int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff81331e90)
Location: fs/dax.c:476
Inline: False
```
**Symbols:**

```
ffffffff81331e90-ffffffff813320bb: grab_mapping_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *grab_mapping_entry(struct xa_state *xas, struct address_space *mapping, unsigned int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8133efa0)
Location: fs/dax.c:476
Inline: False
```
**Symbols:**

```
ffffffff8133efa0-ffffffff8133f1dd: grab_mapping_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *grab_mapping_entry(struct xa_state *xas, struct address_space *mapping, unsigned int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff81350a40)
Location: fs/dax.c:476
Inline: False
```
**Symbols:**

```
ffffffff81350a40-ffffffff81350c61: grab_mapping_entry (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct xa_state *xas</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int index</code>
</li>
<li>
<b>Param reordered. </b>
<code>mapping, index, size_flag</code> ➡️ <code>xas, mapping, size_flag</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int order</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int size_flag</code>
</li>
</ul>
</details>
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
