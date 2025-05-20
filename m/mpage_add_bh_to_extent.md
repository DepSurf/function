# Function: <code>mpage_add_bh_to_extent</code>

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
In fs/ext4/inode.c (ffffffff81296920)
Location: fs/ext4/inode.c:1971
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_process_page_bufs
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
In fs/ext4/inode.c (ffffffff812c3f60)
Location: fs/ext4/inode.c:2128
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_process_page_bufs
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
In fs/ext4/inode.c (ffffffff812d9610)
Location: fs/ext4/inode.c:2157
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_process_page_bufs
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
In fs/ext4/inode.c (ffffffff812fd52d)
Location: fs/ext4/inode.c:2231
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_process_page_bufs
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
In fs/ext4/inode.c (ffffffff81321d6d)
Location: fs/ext4/inode.c:2239
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_process_page_bufs
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
In fs/ext4/inode.c (ffffffff8134fd9c)
Location: fs/ext4/inode.c:2238
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_process_page_bufs
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
In fs/ext4/inode.c (ffffffff81367f8d)
Location: fs/ext4/inode.c:2268
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_process_page_bufs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8139151d)
Location: fs/ext4/inode.c:2284
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_process_page_bufs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813a9eaf)
Location: fs/ext4/inode.c:2262
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_process_page_bufs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool mpage_add_bh_to_extent(struct mpage_da_data *mpd, ext4_lblk_t lblk, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813f5780)
Location: fs/ext4/inode.c:2112
Inline: False
Direct callers:
  - fs/ext4/inode.c:mpage_process_page_bufs
```
**Symbols:**

```
ffffffff813f5780-ffffffff813f580e: mpage_add_bh_to_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool mpage_add_bh_to_extent(struct mpage_da_data *mpd, ext4_lblk_t lblk, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81407f30)
Location: fs/ext4/inode.c:2132
Inline: False
Direct callers:
  - fs/ext4/inode.c:mpage_process_page_bufs
```
**Symbols:**

```
ffffffff81407f30-ffffffff81407fbe: mpage_add_bh_to_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8140e30c)
Location: fs/ext4/inode.c:2131
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_process_page_bufs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff814614b9)
Location: fs/ext4/inode.c:2110
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_process_page_bufs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff814e0229)
Location: fs/ext4/inode.c:2142
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_process_page_bufs
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:2160
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_process_page_bufs
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff815b12c9)
Location: fs/ext4/inode.c:1895
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_process_page_bufs
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff815ea0f9)
Location: fs/ext4/inode.c:1899
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_process_page_bufs
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
In fs/ext4/inode.c (ffff80001047d8e8)
Location: fs/ext4/inode.c:2262
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_process_page_bufs
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (c0640764)
Location: fs/ext4/inode.c:2262
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_process_page_bufs
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (c0000000005a1390)
Location: fs/ext4/inode.c:2262
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_process_page_bufs
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
In fs/ext4/inode.c (ffffffe000307692)
Location: fs/ext4/inode.c:2262
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_process_page_bufs
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813a248f)
Location: fs/ext4/inode.c:2262
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_process_page_bufs
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81392f1f)
Location: fs/ext4/inode.c:2262
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_process_page_bufs
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8139fcef)
Location: fs/ext4/inode.c:2262
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_process_page_bufs
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813b49cf)
Location: fs/ext4/inode.c:2262
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_process_page_bufs
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
