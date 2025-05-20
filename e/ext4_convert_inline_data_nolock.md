# Function: <code>ext4_convert_inline_data_nolock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ext4_convert_inline_data_nolock(handle_t *handle, struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff812dfcb0)
Location: fs/ext4/inline.c:1158
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_try_to_evict_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data
```
**Symbols:**

```
ffffffff812dfcb0-ffffffff812e00e3: ext4_convert_inline_data_nolock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ext4_convert_inline_data_nolock(handle_t *handle, struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff8130f960)
Location: fs/ext4/inline.c:1158
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_try_to_evict_inline_data
  - fs/ext4/inline.c:ext4_try_add_inline_entry
```
**Symbols:**

```
ffffffff8130f960-ffffffff8130fdb5: ext4_convert_inline_data_nolock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ext4_convert_inline_data_nolock(handle_t *handle, struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff81325780)
Location: fs/ext4/inline.c:1175
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_try_to_evict_inline_data
  - fs/ext4/inline.c:ext4_try_add_inline_entry
```
**Symbols:**

```
ffffffff81325780-ffffffff81325be0: ext4_convert_inline_data_nolock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ext4_convert_inline_data_nolock(handle_t *handle, struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff812f97c0)
Location: fs/ext4/inline.c:1177
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_try_to_evict_inline_data
  - fs/ext4/inline.c:ext4_try_add_inline_entry
```
**Symbols:**

```
ffffffff812f97c0-ffffffff812f9bcb: ext4_convert_inline_data_nolock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ext4_convert_inline_data_nolock(handle_t *handle, struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff8131de00)
Location: fs/ext4/inline.c:1168
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_try_to_evict_inline_data
  - fs/ext4/inline.c:ext4_try_add_inline_entry
```
**Symbols:**

```
ffffffff8131de00-ffffffff8131e20b: ext4_convert_inline_data_nolock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ext4_convert_inline_data_nolock(handle_t *handle, struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff8134bde0)
Location: fs/ext4/inline.c:1171
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_try_add_inline_entry
```
**Symbols:**

```
ffffffff8134bde0-ffffffff8134c206: ext4_convert_inline_data_nolock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ext4_convert_inline_data_nolock(handle_t *handle, struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff81363f20)
Location: fs/ext4/inline.c:1174
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_try_add_inline_entry
```
**Symbols:**

```
ffffffff81363f20-ffffffff8136434a: ext4_convert_inline_data_nolock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ext4_convert_inline_data_nolock(handle_t *handle, struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff8138da60)
Location: fs/ext4/inline.c:1171
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_try_add_inline_entry
```
**Symbols:**

```
ffffffff8138da60-ffffffff8138debc: ext4_convert_inline_data_nolock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ext4_convert_inline_data_nolock(handle_t *handle, struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff813a64c0)
Location: fs/ext4/inline.c:1171
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_try_add_inline_entry
```
**Symbols:**

```
ffffffff813a64c0-ffffffff813a691c: ext4_convert_inline_data_nolock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_convert_inline_data_nolock(handle_t *handle, struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff813f2370)
Location: fs/ext4/inline.c:1171
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_try_add_inline_entry
```
**Symbols:**

```
ffffffff813f2370-ffffffff813f26c4: ext4_convert_inline_data_nolock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_convert_inline_data_nolock(handle_t *handle, struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff81404ac0)
Location: fs/ext4/inline.c:1171
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_try_add_inline_entry
```
**Symbols:**

```
ffffffff81404ac0-ffffffff81404e14: ext4_convert_inline_data_nolock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_convert_inline_data_nolock(handle_t *handle, struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff8140b080)
Location: fs/ext4/inline.c:1177
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_try_add_inline_entry
```
**Symbols:**

```
ffffffff8140b080-ffffffff8140b378: ext4_convert_inline_data_nolock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ext4_convert_inline_data_nolock(handle_t *handle, struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff8145dcf0)
Location: fs/ext4/inline.c:1193
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_try_add_inline_entry
```
**Symbols:**

```
ffffffff8145dcf0-ffffffff8145dff4: ext4_convert_inline_data_nolock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ext4_convert_inline_data_nolock(handle_t *handle, struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff814dba70)
Location: fs/ext4/inline.c:1189
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_try_add_inline_entry
```
**Symbols:**

```
ffffffff814dba70-ffffffff814dbd8f: ext4_convert_inline_data_nolock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ext4_convert_inline_data_nolock(handle_t *handle, struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff815749d0)
Location: fs/ext4/inline.c:1188
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_try_add_inline_entry
```
**Symbols:**

```
ffffffff815749d0-ffffffff81574cf7: ext4_convert_inline_data_nolock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ext4_convert_inline_data_nolock(handle_t *handle, struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff815ac8a0)
Location: fs/ext4/inline.c:1171
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_try_add_inline_entry
```
**Symbols:**

```
ffffffff815ac8a0-ffffffff815acbc9: ext4_convert_inline_data_nolock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ext4_convert_inline_data_nolock(handle_t *handle, struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff815e5630)
Location: fs/ext4/inline.c:1170
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_try_add_inline_entry
```
**Symbols:**

```
ffffffff815e5630-ffffffff815e5968: ext4_convert_inline_data_nolock (STB_LOCAL)
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
int ext4_convert_inline_data_nolock(handle_t *handle, struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffff800010479db0)
Location: fs/ext4/inline.c:1171
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_try_add_inline_entry
```
**Symbols:**

```
ffff800010479db0-ffff80001047a280: ext4_convert_inline_data_nolock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ext4_convert_inline_data_nolock(handle_t *handle, struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (c063b62c)
Location: fs/ext4/inline.c:1171
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_try_add_inline_entry
```
**Symbols:**

```
c063b62c-c063bb10: ext4_convert_inline_data_nolock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ext4_convert_inline_data_nolock(handle_t *handle, struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (c00000000059bf50)
Location: fs/ext4/inline.c:1171
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_try_add_inline_entry
```
**Symbols:**

```
c00000000059bf50-c00000000059c490: ext4_convert_inline_data_nolock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ext4_convert_inline_data_nolock(handle_t *handle, struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffe000304112)
Location: fs/ext4/inline.c:1171
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_try_add_inline_entry
```
**Symbols:**

```
ffffffe000304112-ffffffe000304428: ext4_convert_inline_data_nolock (STB_LOCAL)
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
int ext4_convert_inline_data_nolock(handle_t *handle, struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff8139eaa0)
Location: fs/ext4/inline.c:1171
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_try_add_inline_entry
```
**Symbols:**

```
ffffffff8139eaa0-ffffffff8139eefc: ext4_convert_inline_data_nolock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ext4_convert_inline_data_nolock(handle_t *handle, struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff8138f530)
Location: fs/ext4/inline.c:1171
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_try_add_inline_entry
```
**Symbols:**

```
ffffffff8138f530-ffffffff8138f98c: ext4_convert_inline_data_nolock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ext4_convert_inline_data_nolock(handle_t *handle, struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff8139c300)
Location: fs/ext4/inline.c:1171
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_try_add_inline_entry
```
**Symbols:**

```
ffffffff8139c300-ffffffff8139c75c: ext4_convert_inline_data_nolock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ext4_convert_inline_data_nolock(handle_t *handle, struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff813b0820)
Location: fs/ext4/inline.c:1171
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_try_add_inline_entry
```
**Symbols:**

```
ffffffff813b0820-ffffffff813b0c6f: ext4_convert_inline_data_nolock (STB_LOCAL)
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
