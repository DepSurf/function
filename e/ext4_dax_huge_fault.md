# Function: <code>ext4_dax_huge_fault</code>

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
int ext4_dax_huge_fault(struct vm_fault *vmf, enum page_entry_size pe_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (ffffffff812f1150)
Location: fs/ext4/file.c:275
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_dax_fault
```
**Symbols:**

```
ffffffff812f1150-ffffffff812f1299: ext4_dax_huge_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ext4_dax_huge_fault(struct vm_fault *vmf, enum page_entry_size pe_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (ffffffff81315ca0)
Location: fs/ext4/file.c:280
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_dax_fault
```
**Symbols:**

```
ffffffff81315ca0-ffffffff81315e52: ext4_dax_huge_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
vm_fault_t ext4_dax_huge_fault(struct vm_fault *vmf, enum page_entry_size pe_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (ffffffff813438e0)
Location: fs/ext4/file.c:280
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_dax_fault
```
**Symbols:**

```
ffffffff813438e0-ffffffff81343acf: ext4_dax_huge_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
vm_fault_t ext4_dax_huge_fault(struct vm_fault *vmf, enum page_entry_size pe_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (ffffffff8135ba20)
Location: fs/ext4/file.c:280
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_dax_fault
```
**Symbols:**

```
ffffffff8135ba20-ffffffff8135bc0f: ext4_dax_huge_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
vm_fault_t ext4_dax_huge_fault(struct vm_fault *vmf, enum page_entry_size pe_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (ffffffff81384a00)
Location: fs/ext4/file.c:291
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_dax_fault
```
**Symbols:**

```
ffffffff81384a00-ffffffff81384bf3: ext4_dax_huge_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
vm_fault_t ext4_dax_huge_fault(struct vm_fault *vmf, enum page_entry_size pe_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (ffffffff8139d480)
Location: fs/ext4/file.c:291
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_dax_fault
```
**Symbols:**

```
ffffffff8139d480-ffffffff8139d673: ext4_dax_huge_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
vm_fault_t ext4_dax_huge_fault(struct vm_fault *vmf, enum page_entry_size pe_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (ffffffff813e8b80)
Location: fs/ext4/file.c:663
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_dax_fault
```
**Symbols:**

```
ffffffff813e8b80-ffffffff813e8d76: ext4_dax_huge_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
vm_fault_t ext4_dax_huge_fault(struct vm_fault *vmf, enum page_entry_size pe_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (ffffffff813fc080)
Location: fs/ext4/file.c:668
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_dax_fault
```
**Symbols:**

```
ffffffff813fc080-ffffffff813fc2e8: ext4_dax_huge_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
vm_fault_t ext4_dax_huge_fault(struct vm_fault *vmf, enum page_entry_size pe_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (ffffffff814024c0)
Location: fs/ext4/file.c:684
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_dax_fault
```
**Symbols:**

```
ffffffff814024c0-ffffffff8140272f: ext4_dax_huge_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
vm_fault_t ext4_dax_huge_fault(struct vm_fault *vmf, enum page_entry_size pe_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (ffffffff81454b80)
Location: fs/ext4/file.c:684
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_dax_fault
```
**Symbols:**

```
ffffffff81454b80-ffffffff81454df3: ext4_dax_huge_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
vm_fault_t ext4_dax_huge_fault(struct vm_fault *vmf, enum page_entry_size pe_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (ffffffff814d2330)
Location: fs/ext4/file.c:683
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_dax_fault
```
**Symbols:**

```
ffffffff814d2330-ffffffff814d2615: ext4_dax_huge_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
vm_fault_t ext4_dax_huge_fault(struct vm_fault *vmf, enum page_entry_size pe_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (ffffffff8156ae80)
Location: fs/ext4/file.c:704
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_dax_fault
```
**Symbols:**

```
ffffffff8156ae80-ffffffff8156b168: ext4_dax_huge_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
vm_fault_t ext4_dax_huge_fault(struct vm_fault *vmf, enum page_entry_size pe_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (ffffffff815a2d30)
Location: fs/ext4/file.c:726
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_dax_fault
```
**Symbols:**

```
ffffffff815a2d30-ffffffff815a3021: ext4_dax_huge_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
vm_fault_t ext4_dax_huge_fault(struct vm_fault *vmf, unsigned int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (ffffffff815dba50)
Location: fs/ext4/file.c:702
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_dax_fault
```
**Symbols:**

```
ffffffff815dba50-ffffffff815dbd41: ext4_dax_huge_fault (STB_LOCAL)
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
vm_fault_t ext4_dax_huge_fault(struct vm_fault *vmf, enum page_entry_size pe_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (ffff800010470968)
Location: fs/ext4/file.c:291
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_dax_fault
```
**Symbols:**

```
ffff800010470968-ffff800010470b6c: ext4_dax_huge_fault (STB_LOCAL)
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
vm_fault_t ext4_dax_huge_fault(struct vm_fault *vmf, enum page_entry_size pe_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (c000000000590f00)
Location: fs/ext4/file.c:291
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_dax_fault
```
**Symbols:**

```
c000000000590f00-c0000000005911e4: ext4_dax_huge_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
vm_fault_t ext4_dax_huge_fault(struct vm_fault *vmf, enum page_entry_size pe_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (ffffffe0002fcd56)
Location: fs/ext4/file.c:291
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_dax_fault
```
**Symbols:**

```
ffffffe0002fcd56-ffffffe0002fcf26: ext4_dax_huge_fault (STB_LOCAL)
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
vm_fault_t ext4_dax_huge_fault(struct vm_fault *vmf, enum page_entry_size pe_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (ffffffff81395a60)
Location: fs/ext4/file.c:291
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_dax_fault
```
**Symbols:**

```
ffffffff81395a60-ffffffff81395c53: ext4_dax_huge_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
vm_fault_t ext4_dax_huge_fault(struct vm_fault *vmf, enum page_entry_size pe_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (ffffffff813864f0)
Location: fs/ext4/file.c:291
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_dax_fault
```
**Symbols:**

```
ffffffff813864f0-ffffffff813866e3: ext4_dax_huge_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
vm_fault_t ext4_dax_huge_fault(struct vm_fault *vmf, enum page_entry_size pe_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (ffffffff813933c0)
Location: fs/ext4/file.c:291
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_dax_fault
```
**Symbols:**

```
ffffffff813933c0-ffffffff813935b3: ext4_dax_huge_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
vm_fault_t ext4_dax_huge_fault(struct vm_fault *vmf, enum page_entry_size pe_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (ffffffff813a7450)
Location: fs/ext4/file.c:291
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_dax_fault
```
**Symbols:**

```
ffffffff813a7450-ffffffff813a7643: ext4_dax_huge_fault (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>vm_fault_t</code>
</li>
</ul>
</details>
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
