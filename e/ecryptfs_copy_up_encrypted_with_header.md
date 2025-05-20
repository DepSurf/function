# Function: <code>ecryptfs_copy_up_encrypted_with_header</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ecryptfs_copy_up_encrypted_with_header(struct page *page, struct ecryptfs_crypt_stat *crypt_stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/mmap.c (ffffffff81303e30)
Location: fs/ecryptfs/mmap.c:122
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
**Symbols:**

```
ffffffff81303e30-ffffffff81304030: ecryptfs_copy_up_encrypted_with_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ecryptfs_copy_up_encrypted_with_header(struct page *page, struct ecryptfs_crypt_stat *crypt_stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/mmap.c (ffffffff81337e20)
Location: fs/ecryptfs/mmap.c:121
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
```
**Symbols:**

```
ffffffff81337e20-ffffffff81338049: ecryptfs_copy_up_encrypted_with_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ecryptfs_copy_up_encrypted_with_header(struct page *page, struct ecryptfs_crypt_stat *crypt_stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/mmap.c (ffffffff8134dbf0)
Location: fs/ecryptfs/mmap.c:122
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
```
**Symbols:**

```
ffffffff8134dbf0-ffffffff8134de14: ecryptfs_copy_up_encrypted_with_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ecryptfs_copy_up_encrypted_with_header(struct page *page, struct ecryptfs_crypt_stat *crypt_stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/mmap.c (ffffffff813627e0)
Location: fs/ecryptfs/mmap.c:122
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
```
**Symbols:**

```
ffffffff813627e0-ffffffff813629ea: ecryptfs_copy_up_encrypted_with_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ecryptfs_copy_up_encrypted_with_header(struct page *page, struct ecryptfs_crypt_stat *crypt_stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/mmap.c (ffffffff81387460)
Location: fs/ecryptfs/mmap.c:122
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
```
**Symbols:**

```
ffffffff81387460-ffffffff81387646: ecryptfs_copy_up_encrypted_with_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int ecryptfs_copy_up_encrypted_with_header(struct page *page, struct ecryptfs_crypt_stat *crypt_stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/mmap.c (0)
Location: fs/ecryptfs/mmap.c:122
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
```
**Symbols:**

```
ffffffff813b6290-ffffffff813b644e: ecryptfs_copy_up_encrypted_with_header (STB_LOCAL)
ffffffff813b6c08-ffffffff813b6c4f: ecryptfs_copy_up_encrypted_with_header.cold.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int ecryptfs_copy_up_encrypted_with_header(struct page *page, struct ecryptfs_crypt_stat *crypt_stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/mmap.c (0)
Location: fs/ecryptfs/mmap.c:122
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
```
**Symbols:**

```
ffffffff813cf7e0-ffffffff813cf99e: ecryptfs_copy_up_encrypted_with_header (STB_LOCAL)
ffffffff813d0158-ffffffff813d019f: ecryptfs_copy_up_encrypted_with_header.cold.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int ecryptfs_copy_up_encrypted_with_header(struct page *page, struct ecryptfs_crypt_stat *crypt_stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/mmap.c (0)
Location: fs/ecryptfs/mmap.c:108
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
```
**Symbols:**

```
ffffffff813fa3b0-ffffffff813fa58f: ecryptfs_copy_up_encrypted_with_header (STB_LOCAL)
ffffffff813fad4d-ffffffff813fad94: ecryptfs_copy_up_encrypted_with_header.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int ecryptfs_copy_up_encrypted_with_header(struct page *page, struct ecryptfs_crypt_stat *crypt_stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/mmap.c (0)
Location: fs/ecryptfs/mmap.c:108
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
```
**Symbols:**

```
ffffffff81414280-ffffffff8141445f: ecryptfs_copy_up_encrypted_with_header (STB_LOCAL)
ffffffff81414c1d-ffffffff81414c64: ecryptfs_copy_up_encrypted_with_header.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int ecryptfs_copy_up_encrypted_with_header(struct page *page, struct ecryptfs_crypt_stat *crypt_stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/mmap.c (0)
Location: fs/ecryptfs/mmap.c:108
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
```
**Symbols:**

```
ffffffff814625c0-ffffffff8146278f: ecryptfs_copy_up_encrypted_with_header (STB_LOCAL)
ffffffff81462eb8-ffffffff81462eff: ecryptfs_copy_up_encrypted_with_header.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int ecryptfs_copy_up_encrypted_with_header(struct page *page, struct ecryptfs_crypt_stat *crypt_stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/mmap.c (0)
Location: fs/ecryptfs/mmap.c:108
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
```
**Symbols:**

```
ffffffff8147e010-ffffffff8147e1df: ecryptfs_copy_up_encrypted_with_header (STB_LOCAL)
ffffffff81bee3b4-ffffffff81bee3fb: ecryptfs_copy_up_encrypted_with_header.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int ecryptfs_copy_up_encrypted_with_header(struct page *page, struct ecryptfs_crypt_stat *crypt_stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/mmap.c (0)
Location: fs/ecryptfs/mmap.c:109
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
```
**Symbols:**

```
ffffffff81483ae0-ffffffff81483cb9: ecryptfs_copy_up_encrypted_with_header (STB_LOCAL)
ffffffff81be0414-ffffffff81be045b: ecryptfs_copy_up_encrypted_with_header.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ecryptfs_copy_up_encrypted_with_header(struct page *page, struct ecryptfs_crypt_stat *crypt_stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/mmap.c (0)
Location: fs/ecryptfs/mmap.c:109
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
```
**Symbols:**

```
ffffffff814db2a0-ffffffff814db479: ecryptfs_copy_up_encrypted_with_header (STB_LOCAL)
ffffffff81cd0ba2-ffffffff81cd0be9: ecryptfs_copy_up_encrypted_with_header.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ecryptfs_copy_up_encrypted_with_header(struct page *page, struct ecryptfs_crypt_stat *crypt_stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/mmap.c (0)
Location: fs/ecryptfs/mmap.c:109
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_read_folio
```
**Symbols:**

```
ffffffff81568b20-ffffffff81568d29: ecryptfs_copy_up_encrypted_with_header (STB_LOCAL)
ffffffff81e83da7-ffffffff81e83de8: ecryptfs_copy_up_encrypted_with_header.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ecryptfs_copy_up_encrypted_with_header(struct page *page, struct ecryptfs_crypt_stat *crypt_stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/mmap.c (ffffffff8160c450)
Location: fs/ecryptfs/mmap.c:109
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_read_folio
```
**Symbols:**

```
ffffffff8160c450-ffffffff8160c68d: ecryptfs_copy_up_encrypted_with_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ecryptfs_copy_up_encrypted_with_header(struct page *page, struct ecryptfs_crypt_stat *crypt_stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/mmap.c (ffffffff81644340)
Location: fs/ecryptfs/mmap.c:109
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_read_folio
```
**Symbols:**

```
ffffffff81644340-ffffffff8164457d: ecryptfs_copy_up_encrypted_with_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ecryptfs_copy_up_encrypted_with_header(struct page *page, struct ecryptfs_crypt_stat *crypt_stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/mmap.c (ffffffff8167d8e0)
Location: fs/ecryptfs/mmap.c:109
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_read_folio
```
**Symbols:**

```
ffffffff8167d8e0-ffffffff8167daaa: ecryptfs_copy_up_encrypted_with_header (STB_LOCAL)
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
int ecryptfs_copy_up_encrypted_with_header(struct page *page, struct ecryptfs_crypt_stat *crypt_stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/mmap.c (ffff8000104f56e0)
Location: fs/ecryptfs/mmap.c:108
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
```
**Symbols:**

```
ffff8000104f56e0-ffff8000104f58e0: ecryptfs_copy_up_encrypted_with_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ecryptfs_copy_up_encrypted_with_header(struct page *page, struct ecryptfs_crypt_stat *crypt_stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/mmap.c (c06b2f20)
Location: fs/ecryptfs/mmap.c:108
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
```
**Symbols:**

```
c06b2f20-c06b3158: ecryptfs_copy_up_encrypted_with_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ecryptfs_copy_up_encrypted_with_header(struct page *page, struct ecryptfs_crypt_stat *crypt_stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/mmap.c (c000000000636360)
Location: fs/ecryptfs/mmap.c:108
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
```
**Symbols:**

```
c000000000636360-c0000000006365f8: ecryptfs_copy_up_encrypted_with_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ecryptfs_copy_up_encrypted_with_header(struct page *page, struct ecryptfs_crypt_stat *crypt_stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/mmap.c (ffffffe00036471e)
Location: fs/ecryptfs/mmap.c:108
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
```
**Symbols:**

```
ffffffe00036471e-ffffffe0003648d6: ecryptfs_copy_up_encrypted_with_header (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int ecryptfs_copy_up_encrypted_with_header(struct page *page, struct ecryptfs_crypt_stat *crypt_stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/mmap.c (0)
Location: fs/ecryptfs/mmap.c:108
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
```
**Symbols:**

```
ffffffff8140c860-ffffffff8140ca3f: ecryptfs_copy_up_encrypted_with_header (STB_LOCAL)
ffffffff8140d1fd-ffffffff8140d244: ecryptfs_copy_up_encrypted_with_header.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int ecryptfs_copy_up_encrypted_with_header(struct page *page, struct ecryptfs_crypt_stat *crypt_stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/mmap.c (0)
Location: fs/ecryptfs/mmap.c:108
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
```
**Symbols:**

```
ffffffff813fd2e0-ffffffff813fd4bf: ecryptfs_copy_up_encrypted_with_header (STB_LOCAL)
ffffffff813fdc7d-ffffffff813fdcc4: ecryptfs_copy_up_encrypted_with_header.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int ecryptfs_copy_up_encrypted_with_header(struct page *page, struct ecryptfs_crypt_stat *crypt_stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/mmap.c (0)
Location: fs/ecryptfs/mmap.c:108
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
```
**Symbols:**

```
ffffffff81409be0-ffffffff81409dbf: ecryptfs_copy_up_encrypted_with_header (STB_LOCAL)
ffffffff8140a57d-ffffffff8140a5c4: ecryptfs_copy_up_encrypted_with_header.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int ecryptfs_copy_up_encrypted_with_header(struct page *page, struct ecryptfs_crypt_stat *crypt_stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/mmap.c (0)
Location: fs/ecryptfs/mmap.c:108
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
```
**Symbols:**

```
ffffffff8141f8a0-ffffffff8141fa8d: ecryptfs_copy_up_encrypted_with_header (STB_LOCAL)
ffffffff8142028b-ffffffff814202c3: ecryptfs_copy_up_encrypted_with_header.cold (STB_LOCAL)
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
