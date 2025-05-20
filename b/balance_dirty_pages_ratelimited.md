# Function: <code>balance_dirty_pages_ratelimited</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void balance_dirty_pages_ratelimited(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff8119a420)
Location: mm/page-writeback.c:1820
Inline: False
Direct callers:
  - mm/filemap.c:generic_perform_write
  - mm/memory.c:do_wp_page
  - mm/memory.c:handle_mm_fault
  - fs/buffer.c:cont_write_begin
```
**Symbols:**

```
ffffffff8119a420-ffffffff8119a80d: balance_dirty_pages_ratelimited (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void balance_dirty_pages_ratelimited(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff811aed30)
Location: mm/page-writeback.c:1863
Inline: False
Direct callers:
  - mm/filemap.c:generic_perform_write
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_wp_page
  - fs/buffer.c:cont_write_begin
  - fs/iomap.c:iomap_write_actor
```
**Symbols:**

```
ffffffff811aed30-ffffffff811af11b: balance_dirty_pages_ratelimited (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void balance_dirty_pages_ratelimited(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff811bf3e0)
Location: mm/page-writeback.c:1864
Inline: False
Direct callers:
  - mm/filemap.c:generic_perform_write
  - fs/buffer.c:cont_write_begin
  - fs/iomap.c:iomap_dirty_actor
  - fs/iomap.c:iomap_write_actor
```
**Symbols:**

```
ffffffff811bf3e0-ffffffff811bf7bc: balance_dirty_pages_ratelimited (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void balance_dirty_pages_ratelimited(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff811c71f0)
Location: mm/page-writeback.c:1864
Inline: False
Direct callers:
  - mm/filemap.c:generic_perform_write
  - fs/buffer.c:cont_write_begin
  - fs/iomap.c:iomap_dirty_actor
  - fs/iomap.c:iomap_write_actor
```
**Symbols:**

```
ffffffff811c71f0-ffffffff811c7579: balance_dirty_pages_ratelimited (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void balance_dirty_pages_ratelimited(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff811dc000)
Location: mm/page-writeback.c:1862
Inline: False
Direct callers:
  - mm/filemap.c:generic_perform_write
  - fs/buffer.c:cont_write_begin
  - fs/iomap.c:iomap_dirty_actor
  - fs/iomap.c:iomap_write_actor
```
**Symbols:**

```
ffffffff811dc000-ffffffff811dc394: balance_dirty_pages_ratelimited (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void balance_dirty_pages_ratelimited(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff811fd8f0)
Location: mm/page-writeback.c:1862
Inline: False
Direct callers:
  - mm/filemap.c:generic_perform_write
  - fs/buffer.c:cont_write_begin
  - fs/iomap.c:iomap_dirty_actor
  - fs/iomap.c:iomap_write_actor
```
**Symbols:**

```
ffffffff811fd8f0-ffffffff811fdc94: balance_dirty_pages_ratelimited (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void balance_dirty_pages_ratelimited(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff81210410)
Location: mm/page-writeback.c:1861
Inline: False
Direct callers:
  - mm/filemap.c:generic_perform_write
  - fs/buffer.c:cont_write_begin
  - fs/iomap.c:iomap_dirty_actor
  - fs/iomap.c:iomap_write_actor
```
**Symbols:**

```
ffffffff81210410-ffffffff812107d0: balance_dirty_pages_ratelimited (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void balance_dirty_pages_ratelimited(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff8121fab0)
Location: mm/page-writeback.c:1862
Inline: False
Direct callers:
  - mm/filemap.c:generic_perform_write
  - fs/buffer.c:cont_write_begin
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/iomap/buffered-io.c:iomap_write_actor
```
**Symbols:**

```
ffffffff8121fab0-ffffffff8121fe32: balance_dirty_pages_ratelimited (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void balance_dirty_pages_ratelimited(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff8122d560)
Location: mm/page-writeback.c:1864
Inline: False
Direct callers:
  - mm/filemap.c:generic_perform_write
  - mm/memory.c:fault_dirty_shared_page
  - mm/memory.c:fault_dirty_shared_page
  - fs/buffer.c:cont_write_begin
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/iomap/buffered-io.c:iomap_write_actor
```
**Symbols:**

```
ffffffff8122d560-ffffffff8122d8e2: balance_dirty_pages_ratelimited (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void balance_dirty_pages_ratelimited(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff8125b080)
Location: mm/page-writeback.c:1877
Inline: False
Direct callers:
  - mm/filemap.c:generic_perform_write
  - mm/memory.c:fault_dirty_shared_page
  - mm/memory.c:fault_dirty_shared_page
  - fs/buffer.c:cont_expand_zero
  - fs/iomap/buffered-io.c:iomap_write_actor
```
**Symbols:**

```
ffffffff8125b080-ffffffff8125b3fe: balance_dirty_pages_ratelimited (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void balance_dirty_pages_ratelimited(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff812651b0)
Location: mm/page-writeback.c:1877
Inline: False
Direct callers:
  - mm/filemap.c:generic_perform_write
  - mm/memory.c:fault_dirty_shared_page
  - mm/memory.c:fault_dirty_shared_page
  - fs/buffer.c:cont_expand_zero
  - fs/iomap/buffered-io.c:iomap_write_actor
```
**Symbols:**

```
ffffffff812651b0-ffffffff81265570: balance_dirty_pages_ratelimited (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void balance_dirty_pages_ratelimited(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff812693c0)
Location: mm/page-writeback.c:1877
Inline: False
Direct callers:
  - mm/filemap.c:generic_perform_write
  - mm/memory.c:fault_dirty_shared_page
  - mm/memory.c:fault_dirty_shared_page
  - fs/buffer.c:cont_expand_zero
  - fs/iomap/buffered-io.c:iomap_write_actor
```
**Symbols:**

```
ffffffff812693c0-ffffffff8126977f: balance_dirty_pages_ratelimited (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void balance_dirty_pages_ratelimited(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff812a5e40)
Location: mm/page-writeback.c:1878
Inline: False
Direct callers:
  - mm/filemap.c:generic_perform_write
  - mm/memory.c:fault_dirty_shared_page
  - mm/memory.c:fault_dirty_shared_page
  - fs/buffer.c:cont_expand_zero
  - fs/iomap/buffered-io.c:iomap_file_unshare
  - fs/iomap/buffered-io.c:iomap_file_buffered_write
```
**Symbols:**

```
ffffffff812a5e40-ffffffff812a6207: balance_dirty_pages_ratelimited (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void balance_dirty_pages_ratelimited(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff812feb10)
Location: mm/page-writeback.c:1875
Inline: False
Direct callers:
  - mm/filemap.c:generic_perform_write
  - mm/memory.c:fault_dirty_shared_page
  - mm/memory.c:fault_dirty_shared_page
  - fs/buffer.c:cont_expand_zero
  - fs/iomap/buffered-io.c:iomap_file_unshare
  - fs/iomap/buffered-io.c:iomap_write_iter
```
**Symbols:**

```
ffffffff812feb10-ffffffff812feea4: balance_dirty_pages_ratelimited (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void balance_dirty_pages_ratelimited(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff81369640)
Location: mm/page-writeback.c:2062
Inline: False
Direct callers:
  - mm/filemap.c:generic_perform_write
  - mm/memory.c:fault_dirty_shared_page
  - mm/memory.c:fault_dirty_shared_page
  - fs/buffer.c:cont_expand_zero
  - fs/iomap/buffered-io.c:iomap_file_unshare
```
**Symbols:**

```
ffffffff81369640-ffffffff8136965c: balance_dirty_pages_ratelimited (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void balance_dirty_pages_ratelimited(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff8139b7e0)
Location: mm/page-writeback.c:2062
Inline: False
Direct callers:
  - mm/filemap.c:generic_perform_write
  - mm/memory.c:fault_dirty_shared_page
  - mm/memory.c:fault_dirty_shared_page
  - fs/buffer.c:cont_expand_zero
  - fs/iomap/buffered-io.c:iomap_file_unshare
```
**Symbols:**

```
ffffffff8139b7e0-ffffffff8139b7fc: balance_dirty_pages_ratelimited (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void balance_dirty_pages_ratelimited(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff813c5750)
Location: mm/page-writeback.c:2062
Inline: False
Direct callers:
  - mm/filemap.c:generic_perform_write
  - mm/memory.c:fault_dirty_shared_page
  - mm/memory.c:fault_dirty_shared_page
  - fs/buffer.c:cont_expand_zero
  - fs/iomap/buffered-io.c:iomap_file_unshare
```
**Symbols:**

```
ffffffff813c5750-ffffffff813c576c: balance_dirty_pages_ratelimited (STB_GLOBAL)
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
void balance_dirty_pages_ratelimited(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffff8000102bc3f0)
Location: mm/page-writeback.c:1864
Inline: False
Direct callers:
  - mm/filemap.c:generic_perform_write
  - mm/memory.c:fault_dirty_shared_page
  - mm/memory.c:fault_dirty_shared_page
  - fs/buffer.c:cont_write_begin
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/iomap/buffered-io.c:iomap_write_actor
```
**Symbols:**

```
ffff8000102bc3f0-ffff8000102bc830: balance_dirty_pages_ratelimited (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void balance_dirty_pages_ratelimited(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (c04e89fc)
Location: mm/page-writeback.c:1864
Inline: False
Direct callers:
  - mm/filemap.c:generic_perform_write
  - mm/memory.c:fault_dirty_shared_page
  - mm/memory.c:fault_dirty_shared_page
  - fs/buffer.c:cont_write_begin
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/iomap/buffered-io.c:iomap_write_actor
```
**Symbols:**

```
c04e89fc-c04e8f18: balance_dirty_pages_ratelimited (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void balance_dirty_pages_ratelimited(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (c0000000003747b0)
Location: mm/page-writeback.c:1864
Inline: False
Direct callers:
  - mm/filemap.c:generic_perform_write
  - mm/memory.c:fault_dirty_shared_page
  - mm/memory.c:fault_dirty_shared_page
  - fs/buffer.c:cont_write_begin
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/iomap/buffered-io.c:iomap_write_actor
```
**Symbols:**

```
c0000000003747b0-c000000000374d08: balance_dirty_pages_ratelimited (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void balance_dirty_pages_ratelimited(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffe0001df0e2)
Location: mm/page-writeback.c:1864
Inline: False
Direct callers:
  - mm/filemap.c:generic_perform_write
  - mm/memory.c:fault_dirty_shared_page
  - mm/memory.c:fault_dirty_shared_page
  - fs/buffer.c:cont_write_begin
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/iomap/buffered-io.c:iomap_write_actor
```
**Symbols:**

```
ffffffe0001df0e2-ffffffe0001df472: balance_dirty_pages_ratelimited (STB_GLOBAL)
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
void balance_dirty_pages_ratelimited(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff81225bb0)
Location: mm/page-writeback.c:1864
Inline: False
Direct callers:
  - mm/filemap.c:generic_perform_write
  - mm/memory.c:fault_dirty_shared_page
  - mm/memory.c:fault_dirty_shared_page
  - fs/buffer.c:cont_write_begin
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/iomap/buffered-io.c:iomap_write_actor
```
**Symbols:**

```
ffffffff81225bb0-ffffffff81225f32: balance_dirty_pages_ratelimited (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void balance_dirty_pages_ratelimited(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff81218d50)
Location: mm/page-writeback.c:1864
Inline: False
Direct callers:
  - mm/filemap.c:generic_perform_write
  - mm/memory.c:fault_dirty_shared_page
  - mm/memory.c:fault_dirty_shared_page
  - fs/buffer.c:cont_write_begin
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/iomap/buffered-io.c:iomap_write_actor
```
**Symbols:**

```
ffffffff81218d50-ffffffff812190d2: balance_dirty_pages_ratelimited (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void balance_dirty_pages_ratelimited(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff81223950)
Location: mm/page-writeback.c:1864
Inline: False
Direct callers:
  - mm/filemap.c:generic_perform_write
  - mm/memory.c:fault_dirty_shared_page
  - mm/memory.c:fault_dirty_shared_page
  - fs/buffer.c:cont_write_begin
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/iomap/buffered-io.c:iomap_write_actor
```
**Symbols:**

```
ffffffff81223950-ffffffff81223cd2: balance_dirty_pages_ratelimited (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void balance_dirty_pages_ratelimited(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff81232b50)
Location: mm/page-writeback.c:1864
Inline: False
Direct callers:
  - mm/filemap.c:generic_perform_write
  - mm/memory.c:fault_dirty_shared_page
  - mm/memory.c:fault_dirty_shared_page
  - fs/buffer.c:cont_write_begin
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/iomap/buffered-io.c:iomap_write_actor
```
**Symbols:**

```
ffffffff81232b50-ffffffff81232f7c: balance_dirty_pages_ratelimited (STB_GLOBAL)
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
