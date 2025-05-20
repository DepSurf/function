# Function: <code>ext4_block_zero_page_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ext4_block_zero_page_range(handle_t *handle, struct address_space *mapping, loff_t from, loff_t length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81299130)
Location: fs/ext4/inode.c:3500
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_zero_partial_blocks
  - fs/ext4/inode.c:ext4_zero_partial_blocks
  - fs/ext4/inode.c:ext4_zero_partial_blocks
  - fs/ext4/inode.c:ext4_truncate
```
**Symbols:**

```
ffffffff81299130-ffffffff812995c5: ext4_block_zero_page_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ext4_block_zero_page_range(handle_t *handle, struct address_space *mapping, loff_t from, loff_t length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812c6320)
Location: fs/ext4/inode.c:3774
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_zero_partial_blocks
  - fs/ext4/inode.c:ext4_zero_partial_blocks
  - fs/ext4/inode.c:ext4_zero_partial_blocks
```
**Symbols:**

```
ffffffff812c6320-ffffffff812c6856: ext4_block_zero_page_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ext4_block_zero_page_range(handle_t *handle, struct address_space *mapping, loff_t from, loff_t length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812dbb80)
Location: fs/ext4/inode.c:3894
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_zero_partial_blocks
  - fs/ext4/inode.c:ext4_zero_partial_blocks
  - fs/ext4/inode.c:ext4_zero_partial_blocks
```
**Symbols:**

```
ffffffff812dbb80-ffffffff812dc0df: ext4_block_zero_page_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ext4_block_zero_page_range(handle_t *handle, struct address_space *mapping, loff_t from, loff_t length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81300420)
Location: fs/ext4/inode.c:4014
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_zero_partial_blocks
  - fs/ext4/inode.c:ext4_zero_partial_blocks
  - fs/ext4/inode.c:ext4_zero_partial_blocks
```
**Symbols:**

```
ffffffff81300420-ffffffff81300924: ext4_block_zero_page_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ext4_block_zero_page_range(handle_t *handle, struct address_space *mapping, loff_t from, loff_t length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81324c40)
Location: fs/ext4/inode.c:4063
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_zero_partial_blocks
  - fs/ext4/inode.c:ext4_zero_partial_blocks
  - fs/ext4/inode.c:ext4_zero_partial_blocks
```
**Symbols:**

```
ffffffff81324c40-ffffffff81325179: ext4_block_zero_page_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ext4_block_zero_page_range(handle_t *handle, struct address_space *mapping, loff_t from, loff_t length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81352e90)
Location: fs/ext4/inode.c:4075
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_zero_partial_blocks
  - fs/ext4/inode.c:ext4_zero_partial_blocks
  - fs/ext4/inode.c:ext4_zero_partial_blocks
```
**Symbols:**

```
ffffffff81352e90-ffffffff813533ef: ext4_block_zero_page_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ext4_block_zero_page_range(handle_t *handle, struct address_space *mapping, loff_t from, loff_t length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8136afc0)
Location: fs/ext4/inode.c:4108
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_zero_partial_blocks
  - fs/ext4/inode.c:ext4_zero_partial_blocks
  - fs/ext4/inode.c:ext4_zero_partial_blocks
```
**Symbols:**

```
ffffffff8136afc0-ffffffff8136b51c: ext4_block_zero_page_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ext4_block_zero_page_range(handle_t *handle, struct address_space *mapping, loff_t from, loff_t length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81394a30)
Location: fs/ext4/inode.c:4120
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_zero_partial_blocks
  - fs/ext4/inode.c:ext4_zero_partial_blocks
  - fs/ext4/inode.c:ext4_zero_partial_blocks
```
**Symbols:**

```
ffffffff81394a30-ffffffff81394a8c: ext4_block_zero_page_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ext4_block_zero_page_range(handle_t *handle, struct address_space *mapping, loff_t from, loff_t length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813ad3b0)
Location: fs/ext4/inode.c:4097
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_zero_partial_blocks
  - fs/ext4/inode.c:ext4_zero_partial_blocks
  - fs/ext4/inode.c:ext4_zero_partial_blocks
```
**Symbols:**

```
ffffffff813ad3b0-ffffffff813ad40c: ext4_block_zero_page_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_block_zero_page_range(handle_t *handle, struct address_space *mapping, loff_t from, loff_t length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813f9490)
Location: fs/ext4/inode.c:3793
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_zero_partial_blocks
  - fs/ext4/inode.c:ext4_zero_partial_blocks
  - fs/ext4/inode.c:ext4_zero_partial_blocks
```
**Symbols:**

```
ffffffff813f9490-ffffffff813f94ec: ext4_block_zero_page_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_block_zero_page_range(handle_t *handle, struct address_space *mapping, loff_t from, loff_t length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8140ba90)
Location: fs/ext4/inode.c:3828
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_zero_partial_blocks
  - fs/ext4/inode.c:ext4_zero_partial_blocks
  - fs/ext4/inode.c:ext4_zero_partial_blocks
```
**Symbols:**

```
ffffffff8140ba90-ffffffff8140baec: ext4_block_zero_page_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_block_zero_page_range(handle_t *handle, struct address_space *mapping, loff_t from, loff_t length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81411c50)
Location: fs/ext4/inode.c:3827
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_zero_partial_blocks
  - fs/ext4/inode.c:ext4_zero_partial_blocks
  - fs/ext4/inode.c:ext4_zero_partial_blocks
```
**Symbols:**

```
ffffffff81411c50-ffffffff81411cab: ext4_block_zero_page_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ext4_block_zero_page_range(handle_t *handle, struct address_space *mapping, loff_t from, loff_t length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81464b10)
Location: fs/ext4/inode.c:3751
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_zero_partial_blocks
  - fs/ext4/inode.c:ext4_zero_partial_blocks
  - fs/ext4/inode.c:ext4_zero_partial_blocks
```
**Symbols:**

```
ffffffff81464b10-ffffffff81464b6b: ext4_block_zero_page_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ext4_block_zero_page_range(handle_t *handle, struct address_space *mapping, loff_t from, loff_t length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff814e41b0)
Location: fs/ext4/inode.c:3816
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_zero_partial_blocks
  - fs/ext4/inode.c:ext4_zero_partial_blocks
  - fs/ext4/inode.c:ext4_zero_partial_blocks
```
**Symbols:**

```
ffffffff814e41b0-ffffffff814e4235: ext4_block_zero_page_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ext4_block_zero_page_range(handle_t *handle, struct address_space *mapping, loff_t from, loff_t length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8157d6d0)
Location: fs/ext4/inode.c:3902
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_zero_partial_blocks
  - fs/ext4/inode.c:ext4_zero_partial_blocks
  - fs/ext4/inode.c:ext4_zero_partial_blocks
```
**Symbols:**

```
ffffffff8157d6d0-ffffffff8157d755: ext4_block_zero_page_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ext4_block_zero_page_range(handle_t *handle, struct address_space *mapping, loff_t from, loff_t length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff815b49c0)
Location: fs/ext4/inode.c:3691
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_zero_partial_blocks
  - fs/ext4/inode.c:ext4_zero_partial_blocks
  - fs/ext4/inode.c:ext4_zero_partial_blocks
```
**Symbols:**

```
ffffffff815b49c0-ffffffff815b4a45: ext4_block_zero_page_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ext4_block_zero_page_range(handle_t *handle, struct address_space *mapping, loff_t from, loff_t length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff815ed800)
Location: fs/ext4/inode.c:3708
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_zero_partial_blocks
  - fs/ext4/inode.c:ext4_zero_partial_blocks
  - fs/ext4/inode.c:ext4_zero_partial_blocks
```
**Symbols:**

```
ffffffff815ed800-ffffffff815ed885: ext4_block_zero_page_range (STB_LOCAL)
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
int ext4_block_zero_page_range(handle_t *handle, struct address_space *mapping, loff_t from, loff_t length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffff800010481b08)
Location: fs/ext4/inode.c:4097
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_zero_partial_blocks
  - fs/ext4/inode.c:ext4_zero_partial_blocks
  - fs/ext4/inode.c:ext4_zero_partial_blocks
```
**Symbols:**

```
ffff800010481b08-ffff800010481bac: ext4_block_zero_page_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ext4_block_zero_page_range(handle_t *handle, struct address_space *mapping, loff_t from, loff_t length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (c0642cd4)
Location: fs/ext4/inode.c:4097
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_zero_partial_blocks
  - fs/ext4/inode.c:ext4_zero_partial_blocks
  - fs/ext4/inode.c:ext4_zero_partial_blocks
```
**Symbols:**

```
c0642cd4-c0642d30: ext4_block_zero_page_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ext4_block_zero_page_range(handle_t *handle, struct address_space *mapping, loff_t from, loff_t length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (c0000000005a6320)
Location: fs/ext4/inode.c:4097
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_zero_partial_blocks
  - fs/ext4/inode.c:ext4_zero_partial_blocks
  - fs/ext4/inode.c:ext4_zero_partial_blocks
```
**Symbols:**

```
c0000000005a6320-c0000000005a63bc: ext4_block_zero_page_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ext4_block_zero_page_range(handle_t *handle, struct address_space *mapping, loff_t from, loff_t length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffe00030a6f2)
Location: fs/ext4/inode.c:4097
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_zero_partial_blocks
  - fs/ext4/inode.c:ext4_zero_partial_blocks
  - fs/ext4/inode.c:ext4_zero_partial_blocks
```
**Symbols:**

```
ffffffe00030a6f2-ffffffe00030a786: ext4_block_zero_page_range (STB_LOCAL)
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
int ext4_block_zero_page_range(handle_t *handle, struct address_space *mapping, loff_t from, loff_t length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813a5990)
Location: fs/ext4/inode.c:4097
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_zero_partial_blocks
  - fs/ext4/inode.c:ext4_zero_partial_blocks
  - fs/ext4/inode.c:ext4_zero_partial_blocks
```
**Symbols:**

```
ffffffff813a5990-ffffffff813a59ec: ext4_block_zero_page_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ext4_block_zero_page_range(handle_t *handle, struct address_space *mapping, loff_t from, loff_t length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81396420)
Location: fs/ext4/inode.c:4097
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_zero_partial_blocks
  - fs/ext4/inode.c:ext4_zero_partial_blocks
  - fs/ext4/inode.c:ext4_zero_partial_blocks
```
**Symbols:**

```
ffffffff81396420-ffffffff8139647c: ext4_block_zero_page_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ext4_block_zero_page_range(handle_t *handle, struct address_space *mapping, loff_t from, loff_t length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813a31f0)
Location: fs/ext4/inode.c:4097
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_zero_partial_blocks
  - fs/ext4/inode.c:ext4_zero_partial_blocks
  - fs/ext4/inode.c:ext4_zero_partial_blocks
```
**Symbols:**

```
ffffffff813a31f0-ffffffff813a324c: ext4_block_zero_page_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ext4_block_zero_page_range(handle_t *handle, struct address_space *mapping, loff_t from, loff_t length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813b78e0)
Location: fs/ext4/inode.c:4097
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_zero_partial_blocks
  - fs/ext4/inode.c:ext4_zero_partial_blocks
  - fs/ext4/inode.c:ext4_zero_partial_blocks
```
**Symbols:**

```
ffffffff813b78e0-ffffffff813b793c: ext4_block_zero_page_range (STB_LOCAL)
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
