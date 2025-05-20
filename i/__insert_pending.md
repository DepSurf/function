# Function: <code>__insert_pending</code>

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
int __insert_pending(struct inode *inode, ext4_lblk_t lblk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff81359850)
Location: fs/ext4/extents_status.c:1460
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:ext4_es_insert_delayed_block
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
```
**Symbols:**

```
ffffffff81359850-ffffffff813598f5: __insert_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __insert_pending(struct inode *inode, ext4_lblk_t lblk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff813828a0)
Location: fs/ext4/extents_status.c:1459
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:ext4_es_insert_delayed_block
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
```
**Symbols:**

```
ffffffff813828a0-ffffffff81382952: __insert_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __insert_pending(struct inode *inode, ext4_lblk_t lblk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff8139ada0)
Location: fs/ext4/extents_status.c:1850
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:ext4_es_insert_delayed_block
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
```
**Symbols:**

```
ffffffff8139ada0-ffffffff8139ae52: __insert_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff813e6160)
Location: fs/ext4/extents_status.c:1850
Inline: True
Direct callers:
  - fs/ext4/extents_status.c:__revise_pending
  - fs/ext4/extents_status.c:__revise_pending
  - fs/ext4/extents_status.c:__revise_pending
  - fs/ext4/extents_status.c:ext4_es_insert_delayed_block
```
**Symbols:**

```
ffffffff813e6160-ffffffff813e61fe: __insert_pending.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff813f84c0)
Location: fs/ext4/extents_status.c:1871
Inline: True
Direct callers:
  - fs/ext4/extents_status.c:__revise_pending
  - fs/ext4/extents_status.c:__revise_pending
  - fs/ext4/extents_status.c:__revise_pending
  - fs/ext4/extents_status.c:ext4_es_insert_delayed_block
```
**Symbols:**

```
ffffffff813f84c0-ffffffff813f855e: __insert_pending.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff813fe940)
Location: fs/ext4/extents_status.c:1869
Inline: True
Direct callers:
  - fs/ext4/extents_status.c:__revise_pending
  - fs/ext4/extents_status.c:__revise_pending
  - fs/ext4/extents_status.c:__revise_pending
  - fs/ext4/extents_status.c:ext4_es_insert_delayed_block
```
**Symbols:**

```
ffffffff813fe940-ffffffff813fe9de: __insert_pending.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/extents_status.c (0)
Location: fs/ext4/extents_status.c:1869
Inline: True
Direct callers:
  - fs/ext4/extents_status.c:__revise_pending
  - fs/ext4/extents_status.c:__revise_pending
  - fs/ext4/extents_status.c:__revise_pending
  - fs/ext4/extents_status.c:ext4_es_insert_delayed_block
```
**Symbols:**

```
ffffffff81450cf0-ffffffff81450da3: __insert_pending.isra.0 (STB_LOCAL)
ffffffff81cc99d0-ffffffff81cc99ee: __insert_pending.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/extents_status.c (0)
Location: fs/ext4/extents_status.c:1869
Inline: True
Direct callers:
  - fs/ext4/extents_status.c:__revise_pending
  - fs/ext4/extents_status.c:__revise_pending
  - fs/ext4/extents_status.c:__revise_pending
  - fs/ext4/extents_status.c:ext4_es_insert_delayed_block
```
**Symbols:**

```
ffffffff814cde60-ffffffff814cdf26: __insert_pending.isra.0 (STB_LOCAL)
ffffffff81e7c6e0-ffffffff81e7c6fe: __insert_pending.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/extents_status.c (0)
Location: fs/ext4/extents_status.c:1866
Inline: True
Direct callers:
  - fs/ext4/extents_status.c:__revise_pending
  - fs/ext4/extents_status.c:__revise_pending
  - fs/ext4/extents_status.c:__revise_pending
  - fs/ext4/extents_status.c:ext4_es_insert_delayed_block
```
**Symbols:**

```
ffffffff81566600-ffffffff815666c6: __insert_pending.isra.0 (STB_LOCAL)
ffffffff8206cd2a-ffffffff8206cd48: __insert_pending.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/extents_status.c (0)
Location: fs/ext4/extents_status.c:1904
Inline: True
Direct callers:
  - fs/ext4/extents_status.c:__revise_pending
  - fs/ext4/extents_status.c:__revise_pending
  - fs/ext4/extents_status.c:__revise_pending
  - fs/ext4/extents_status.c:ext4_es_insert_delayed_block
```
**Symbols:**

```
ffffffff8159e290-ffffffff8159e356: __insert_pending.isra.0 (STB_LOCAL)
ffffffff820ecab2-ffffffff820ecad0: __insert_pending.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int __insert_pending(struct inode *inode, ext4_lblk_t lblk, struct pending_reservation **prealloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/extents_status.c (0)
Location: fs/ext4/extents_status.c:1944
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:__revise_pending
  - fs/ext4/extents_status.c:__revise_pending
  - fs/ext4/extents_status.c:__revise_pending
  - fs/ext4/extents_status.c:__revise_pending
  - fs/ext4/extents_status.c:ext4_es_insert_delayed_block
```
**Symbols:**

```
ffffffff815d8290-ffffffff815d8378: __insert_pending (STB_LOCAL)
ffffffff821c9ec4-ffffffff821c9ee2: __insert_pending.cold (STB_LOCAL)
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
int __insert_pending(struct inode *inode, ext4_lblk_t lblk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffff80001046d818)
Location: fs/ext4/extents_status.c:1850
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:ext4_es_insert_delayed_block
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
```
**Symbols:**

```
ffff80001046d818-ffff80001046d8e0: __insert_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __insert_pending(struct inode *inode, ext4_lblk_t lblk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (c062efac)
Location: fs/ext4/extents_status.c:1850
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:ext4_es_insert_delayed_block
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
```
**Symbols:**

```
c062efac-c062f068: __insert_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __insert_pending(struct inode *inode, ext4_lblk_t lblk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (c00000000058d720)
Location: fs/ext4/extents_status.c:1850
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:ext4_es_insert_delayed_block
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
```
**Symbols:**

```
c00000000058d720-c00000000058d84c: __insert_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __insert_pending(struct inode *inode, ext4_lblk_t lblk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffe0002faabc)
Location: fs/ext4/extents_status.c:1850
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:ext4_es_insert_delayed_block
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
```
**Symbols:**

```
ffffffe0002faabc-ffffffe0002fab70: __insert_pending (STB_LOCAL)
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
int __insert_pending(struct inode *inode, ext4_lblk_t lblk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff81393380)
Location: fs/ext4/extents_status.c:1850
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:ext4_es_insert_delayed_block
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
```
**Symbols:**

```
ffffffff81393380-ffffffff81393432: __insert_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __insert_pending(struct inode *inode, ext4_lblk_t lblk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff81383e10)
Location: fs/ext4/extents_status.c:1850
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:ext4_es_insert_delayed_block
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
```
**Symbols:**

```
ffffffff81383e10-ffffffff81383ec2: __insert_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __insert_pending(struct inode *inode, ext4_lblk_t lblk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff81390ce0)
Location: fs/ext4/extents_status.c:1850
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:ext4_es_insert_delayed_block
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
```
**Symbols:**

```
ffffffff81390ce0-ffffffff81390d92: __insert_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __insert_pending(struct inode *inode, ext4_lblk_t lblk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff813a4b70)
Location: fs/ext4/extents_status.c:1850
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:ext4_es_insert_delayed_block
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
```
**Symbols:**

```
ffffffff813a4b70-ffffffff813a4c22: __insert_pending (STB_LOCAL)
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
