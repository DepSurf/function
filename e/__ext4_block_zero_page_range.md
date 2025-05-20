# Function: <code>__ext4_block_zero_page_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812991a2)
Location: fs/ext4/inode.c:3404
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_zero_page_range
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812c6392)
Location: fs/ext4/inode.c:3678
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_zero_page_range
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812dbbf2)
Location: fs/ext4/inode.c:3797
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_zero_page_range
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81300481)
Location: fs/ext4/inode.c:3917
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_zero_page_range
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81324ca1)
Location: fs/ext4/inode.c:3966
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_zero_page_range
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81352f01)
Location: fs/ext4/inode.c:3978
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_zero_page_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8136b02e)
Location: fs/ext4/inode.c:4011
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_zero_page_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __ext4_block_zero_page_range(handle_t *handle, struct address_space *mapping, loff_t from, loff_t length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813944f0)
Location: fs/ext4/inode.c:4024
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_block_zero_page_range
```
**Symbols:**

```
ffffffff813944f0-ffffffff81394a23: __ext4_block_zero_page_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __ext4_block_zero_page_range(handle_t *handle, struct address_space *mapping, loff_t from, loff_t length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813ace70)
Location: fs/ext4/inode.c:4001
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_block_zero_page_range
```
**Symbols:**

```
ffffffff813ace70-ffffffff813ad3a3: __ext4_block_zero_page_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __ext4_block_zero_page_range(handle_t *handle, struct address_space *mapping, loff_t from, loff_t length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813f90e0)
Location: fs/ext4/inode.c:3693
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_block_zero_page_range
```
**Symbols:**

```
ffffffff813f90e0-ffffffff813f948e: __ext4_block_zero_page_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __ext4_block_zero_page_range(handle_t *handle, struct address_space *mapping, loff_t from, loff_t length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8140b7b0)
Location: fs/ext4/inode.c:3731
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_block_zero_page_range
```
**Symbols:**

```
ffffffff8140b7b0-ffffffff8140ba90: __ext4_block_zero_page_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __ext4_block_zero_page_range(handle_t *handle, struct address_space *mapping, loff_t from, loff_t length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81411960)
Location: fs/ext4/inode.c:3730
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_block_zero_page_range
```
**Symbols:**

```
ffffffff81411960-ffffffff81411c48: __ext4_block_zero_page_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __ext4_block_zero_page_range(handle_t *handle, struct address_space *mapping, loff_t from, loff_t length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:3653
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_block_zero_page_range
```
**Symbols:**

```
ffffffff81464810-ffffffff81464b05: __ext4_block_zero_page_range (STB_LOCAL)
ffffffff81ccabdb-ffffffff81ccac07: __ext4_block_zero_page_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __ext4_block_zero_page_range(handle_t *handle, struct address_space *mapping, loff_t from, loff_t length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:3718
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_block_zero_page_range
```
**Symbols:**

```
ffffffff814e3e20-ffffffff814e41a6: __ext4_block_zero_page_range (STB_LOCAL)
ffffffff81e7d9d3-ffffffff81e7d9ff: __ext4_block_zero_page_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int __ext4_block_zero_page_range(handle_t *handle, struct address_space *mapping, loff_t from, loff_t length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:3804
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_block_zero_page_range
```
**Symbols:**

```
ffffffff8157d350-ffffffff8157d6bf: __ext4_block_zero_page_range (STB_LOCAL)
ffffffff8206df3d-ffffffff8206df69: __ext4_block_zero_page_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int __ext4_block_zero_page_range(handle_t *handle, struct address_space *mapping, loff_t from, loff_t length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:3589
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_block_zero_page_range
```
**Symbols:**

```
ffffffff815b4700-ffffffff815b49ab: __ext4_block_zero_page_range (STB_LOCAL)
ffffffff820edc2b-ffffffff820edc58: __ext4_block_zero_page_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int __ext4_block_zero_page_range(handle_t *handle, struct address_space *mapping, loff_t from, loff_t length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:3608
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_block_zero_page_range
```
**Symbols:**

```
ffffffff815ed510-ffffffff815ed7ea: __ext4_block_zero_page_range (STB_LOCAL)
ffffffff821cad5a-ffffffff821cadb5: __ext4_block_zero_page_range.cold (STB_LOCAL)
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
int __ext4_block_zero_page_range(handle_t *handle, struct address_space *mapping, loff_t from, loff_t length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffff8000104815f8)
Location: fs/ext4/inode.c:4001
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_block_zero_page_range
```
**Symbols:**

```
ffff8000104815f8-ffff800010481b04: __ext4_block_zero_page_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __ext4_block_zero_page_range(handle_t *handle, struct address_space *mapping, loff_t from, loff_t length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (c0642798)
Location: fs/ext4/inode.c:4001
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_block_zero_page_range
```
**Symbols:**

```
c0642798-c0642cd4: __ext4_block_zero_page_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __ext4_block_zero_page_range(handle_t *handle, struct address_space *mapping, loff_t from, loff_t length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (c0000000005a5cc0)
Location: fs/ext4/inode.c:4001
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_block_zero_page_range
```
**Symbols:**

```
c0000000005a5cc0-c0000000005a6320: __ext4_block_zero_page_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __ext4_block_zero_page_range(handle_t *handle, struct address_space *mapping, loff_t from, loff_t length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffe00030a296)
Location: fs/ext4/inode.c:4001
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_block_zero_page_range
```
**Symbols:**

```
ffffffe00030a296-ffffffe00030a6f2: __ext4_block_zero_page_range (STB_LOCAL)
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
int __ext4_block_zero_page_range(handle_t *handle, struct address_space *mapping, loff_t from, loff_t length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813a5450)
Location: fs/ext4/inode.c:4001
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_block_zero_page_range
```
**Symbols:**

```
ffffffff813a5450-ffffffff813a5983: __ext4_block_zero_page_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __ext4_block_zero_page_range(handle_t *handle, struct address_space *mapping, loff_t from, loff_t length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81395ee0)
Location: fs/ext4/inode.c:4001
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_block_zero_page_range
```
**Symbols:**

```
ffffffff81395ee0-ffffffff81396413: __ext4_block_zero_page_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __ext4_block_zero_page_range(handle_t *handle, struct address_space *mapping, loff_t from, loff_t length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813a2cb0)
Location: fs/ext4/inode.c:4001
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_block_zero_page_range
```
**Symbols:**

```
ffffffff813a2cb0-ffffffff813a31e3: __ext4_block_zero_page_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __ext4_block_zero_page_range(handle_t *handle, struct address_space *mapping, loff_t from, loff_t length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813b7390)
Location: fs/ext4/inode.c:4001
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_block_zero_page_range
```
**Symbols:**

```
ffffffff813b7390-ffffffff813b78d4: __ext4_block_zero_page_range (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
