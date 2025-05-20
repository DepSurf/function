# Function: <code>__remove_pending</code>

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
void __remove_pending(struct inode *inode, ext4_lblk_t lblk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff81359740)
Location: fs/ext4/extents_status.c:1509
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:ext4_remove_pending
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
```
**Symbols:**

```
ffffffff81359740-ffffffff813597a4: __remove_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __remove_pending(struct inode *inode, ext4_lblk_t lblk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff81382830)
Location: fs/ext4/extents_status.c:1508
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:ext4_remove_pending
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
```
**Symbols:**

```
ffffffff81382830-ffffffff8138289b: __remove_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __remove_pending(struct inode *inode, ext4_lblk_t lblk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff8139ac80)
Location: fs/ext4/extents_status.c:1899
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:ext4_remove_pending
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
```
**Symbols:**

```
ffffffff8139ac80-ffffffff8139aceb: __remove_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __remove_pending(struct inode *inode, ext4_lblk_t lblk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff813e60f0)
Location: fs/ext4/extents_status.c:1899
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:__revise_pending
  - fs/ext4/extents_status.c:__revise_pending
  - fs/ext4/extents_status.c:ext4_remove_pending
```
**Symbols:**

```
ffffffff813e60f0-ffffffff813e615f: __remove_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __remove_pending(struct inode *inode, ext4_lblk_t lblk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff813f8450)
Location: fs/ext4/extents_status.c:1920
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:__revise_pending
  - fs/ext4/extents_status.c:__revise_pending
  - fs/ext4/extents_status.c:ext4_remove_pending
```
**Symbols:**

```
ffffffff813f8450-ffffffff813f84bf: __remove_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __remove_pending(struct inode *inode, ext4_lblk_t lblk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff813fe8d0)
Location: fs/ext4/extents_status.c:1918
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:__revise_pending
  - fs/ext4/extents_status.c:__revise_pending
  - fs/ext4/extents_status.c:ext4_remove_pending
```
**Symbols:**

```
ffffffff813fe8d0-ffffffff813fe93f: __remove_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __remove_pending(struct inode *inode, ext4_lblk_t lblk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/extents_status.c (0)
Location: fs/ext4/extents_status.c:1918
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:__revise_pending
  - fs/ext4/extents_status.c:__revise_pending
  - fs/ext4/extents_status.c:ext4_remove_pending
```
**Symbols:**

```
ffffffff81450c60-ffffffff81450cec: __remove_pending (STB_LOCAL)
ffffffff81cc99b2-ffffffff81cc99d0: __remove_pending.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __remove_pending(struct inode *inode, ext4_lblk_t lblk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/extents_status.c (0)
Location: fs/ext4/extents_status.c:1918
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:__revise_pending
  - fs/ext4/extents_status.c:__revise_pending
  - fs/ext4/extents_status.c:ext4_remove_pending
```
**Symbols:**

```
ffffffff814cdc90-ffffffff814cdd34: __remove_pending (STB_LOCAL)
ffffffff81e7c6c2-ffffffff81e7c6e0: __remove_pending.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void __remove_pending(struct inode *inode, ext4_lblk_t lblk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/extents_status.c (0)
Location: fs/ext4/extents_status.c:1915
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:__revise_pending
  - fs/ext4/extents_status.c:__revise_pending
  - fs/ext4/extents_status.c:ext4_remove_pending
```
**Symbols:**

```
ffffffff81566410-ffffffff815664b4: __remove_pending (STB_LOCAL)
ffffffff8206cd0c-ffffffff8206cd2a: __remove_pending.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void __remove_pending(struct inode *inode, ext4_lblk_t lblk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/extents_status.c (0)
Location: fs/ext4/extents_status.c:1953
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:__revise_pending
  - fs/ext4/extents_status.c:__revise_pending
  - fs/ext4/extents_status.c:ext4_remove_pending
```
**Symbols:**

```
ffffffff8159e0a0-ffffffff8159e144: __remove_pending (STB_LOCAL)
ffffffff820eca94-ffffffff820ecab2: __remove_pending.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void __remove_pending(struct inode *inode, ext4_lblk_t lblk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/extents_status.c (0)
Location: fs/ext4/extents_status.c:1999
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:__revise_pending
  - fs/ext4/extents_status.c:__revise_pending
  - fs/ext4/extents_status.c:__revise_pending
  - fs/ext4/extents_status.c:ext4_remove_pending
```
**Symbols:**

```
ffffffff815d6e20-ffffffff815d6ec4: __remove_pending (STB_LOCAL)
ffffffff821c9cd0-ffffffff821c9cee: __remove_pending.cold (STB_LOCAL)
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
void __remove_pending(struct inode *inode, ext4_lblk_t lblk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffff80001046d698)
Location: fs/ext4/extents_status.c:1899
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:ext4_remove_pending
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
```
**Symbols:**

```
ffff80001046d698-ffff80001046d724: __remove_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __remove_pending(struct inode *inode, ext4_lblk_t lblk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (c062eca0)
Location: fs/ext4/extents_status.c:1899
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:ext4_remove_pending
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
```
**Symbols:**

```
c062eca0-c062ed28: __remove_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __remove_pending(struct inode *inode, ext4_lblk_t lblk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (c00000000058d560)
Location: fs/ext4/extents_status.c:1899
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:ext4_remove_pending
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
```
**Symbols:**

```
c00000000058d560-c00000000058d624: __remove_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __remove_pending(struct inode *inode, ext4_lblk_t lblk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffe0002fa98c)
Location: fs/ext4/extents_status.c:1899
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:ext4_remove_pending
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
```
**Symbols:**

```
ffffffe0002fa98c-ffffffe0002faa00: __remove_pending (STB_LOCAL)
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
void __remove_pending(struct inode *inode, ext4_lblk_t lblk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff81393260)
Location: fs/ext4/extents_status.c:1899
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:ext4_remove_pending
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
```
**Symbols:**

```
ffffffff81393260-ffffffff813932cb: __remove_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __remove_pending(struct inode *inode, ext4_lblk_t lblk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff81383cf0)
Location: fs/ext4/extents_status.c:1899
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:ext4_remove_pending
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
```
**Symbols:**

```
ffffffff81383cf0-ffffffff81383d5b: __remove_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __remove_pending(struct inode *inode, ext4_lblk_t lblk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff81390bc0)
Location: fs/ext4/extents_status.c:1899
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:ext4_remove_pending
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
```
**Symbols:**

```
ffffffff81390bc0-ffffffff81390c2b: __remove_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __remove_pending(struct inode *inode, ext4_lblk_t lblk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff813a4a50)
Location: fs/ext4/extents_status.c:1899
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:ext4_remove_pending
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
```
**Symbols:**

```
ffffffff813a4a50-ffffffff813a4abb: __remove_pending (STB_LOCAL)
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
