# Function: <code>fuse_send_writepage</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void fuse_send_writepage(struct fuse_conn *fc, struct fuse_req *req, loff_t size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81317100)
Location: fs/fuse/file.c:1463
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_flush_writepages
```
**Symbols:**

```
ffffffff81317100-ffffffff813171a0: fuse_send_writepage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void fuse_send_writepage(struct fuse_conn *fc, struct fuse_req *req, loff_t size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8134ba20)
Location: fs/fuse/file.c:1476
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_flush_writepages
```
**Symbols:**

```
ffffffff8134ba20-ffffffff8134bac0: fuse_send_writepage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void fuse_send_writepage(struct fuse_conn *fc, struct fuse_req *req, loff_t size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81361330)
Location: fs/fuse/file.c:1477
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_flush_writepages
```
**Symbols:**

```
ffffffff81361330-ffffffff813613d0: fuse_send_writepage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void fuse_send_writepage(struct fuse_conn *fc, struct fuse_req *req, loff_t size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81375d30)
Location: fs/fuse/file.c:1472
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_flush_writepages
```
**Symbols:**

```
ffffffff81375d30-ffffffff81375dd0: fuse_send_writepage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void fuse_send_writepage(struct fuse_conn *fc, struct fuse_req *req, loff_t size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8139aac0)
Location: fs/fuse/file.c:1480
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_flush_writepages
```
**Symbols:**

```
ffffffff8139aac0-ffffffff8139ab60: fuse_send_writepage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void fuse_send_writepage(struct fuse_conn *fc, struct fuse_req *req, loff_t size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff813c9180)
Location: fs/fuse/file.c:1481
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_flush_writepages
```
**Symbols:**

```
ffffffff813c9180-ffffffff813c9220: fuse_send_writepage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void fuse_send_writepage(struct fuse_conn *fc, struct fuse_req *req, loff_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff813e2c30)
Location: fs/fuse/file.c:1485
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_flush_writepages
```
**Symbols:**

```
ffffffff813e2c30-ffffffff813e2cd8: fuse_send_writepage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void fuse_send_writepage(struct fuse_conn *fc, struct fuse_req *req, loff_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8140eb40)
Location: fs/fuse/file.c:1540
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_flush_writepages
```
**Symbols:**

```
ffffffff8140eb40-ffffffff8140ec34: fuse_send_writepage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void fuse_send_writepage(struct fuse_conn *fc, struct fuse_writepage_args *wpa, loff_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81427a80)
Location: fs/fuse/file.c:1627
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_flush_writepages
```
**Symbols:**

```
ffffffff81427a80-ffffffff81427bca: fuse_send_writepage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void fuse_send_writepage(struct fuse_conn *fc, struct fuse_writepage_args *wpa, loff_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff814783b0)
Location: fs/fuse/file.c:1599
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_flush_writepages
```
**Symbols:**

```
ffffffff814783b0-ffffffff8147850e: fuse_send_writepage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void fuse_send_writepage(struct fuse_mount *fm, struct fuse_writepage_args *wpa, loff_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81492e30)
Location: fs/fuse/file.c:1639
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_flush_writepages
```
**Symbols:**

```
ffffffff81492e30-ffffffff81492f8e: fuse_send_writepage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void fuse_send_writepage(struct fuse_mount *fm, struct fuse_writepage_args *wpa, loff_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81497da0)
Location: fs/fuse/file.c:1641
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_flush_writepages
```
**Symbols:**

```
ffffffff81497da0-ffffffff81497ef4: fuse_send_writepage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void fuse_send_writepage(struct fuse_mount *fm, struct fuse_writepage_args *wpa, loff_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff814ef9b0)
Location: fs/fuse/file.c:1647
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_flush_writepages
```
**Symbols:**

```
ffffffff814ef9b0-ffffffff814efb04: fuse_send_writepage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void fuse_send_writepage(struct fuse_mount *fm, struct fuse_writepage_args *wpa, loff_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8157daa0)
Location: fs/fuse/file.c:1662
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_flush_writepages
```
**Symbols:**

```
ffffffff8157daa0-ffffffff8157dc08: fuse_send_writepage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void fuse_send_writepage(struct fuse_mount *fm, struct fuse_writepage_args *wpa, loff_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81623650)
Location: fs/fuse/file.c:1697
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_flush_writepages
```
**Symbols:**

```
ffffffff81623650-ffffffff816237b8: fuse_send_writepage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void fuse_send_writepage(struct fuse_mount *fm, struct fuse_writepage_args *wpa, loff_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8165ba30)
Location: fs/fuse/file.c:1674
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_flush_writepages
```
**Symbols:**

```
ffffffff8165ba30-ffffffff8165bb98: fuse_send_writepage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void fuse_send_writepage(struct fuse_mount *fm, struct fuse_writepage_args *wpa, loff_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81695710)
Location: fs/fuse/file.c:1694
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_flush_writepages
```
**Symbols:**

```
ffffffff81695710-ffffffff81695878: fuse_send_writepage (STB_LOCAL)
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
void fuse_send_writepage(struct fuse_conn *fc, struct fuse_writepage_args *wpa, loff_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffff80001050c758)
Location: fs/fuse/file.c:1627
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_flush_writepages
```
**Symbols:**

```
ffff80001050c758-ffff80001050c910: fuse_send_writepage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void fuse_send_writepage(struct fuse_conn *fc, struct fuse_writepage_args *wpa, loff_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (c06c7510)
Location: fs/fuse/file.c:1627
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_flush_writepages
```
**Symbols:**

```
c06c7510-c06c7664: fuse_send_writepage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void fuse_send_writepage(struct fuse_conn *fc, struct fuse_writepage_args *wpa, loff_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (c0000000006520e0)
Location: fs/fuse/file.c:1627
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_flush_writepages
```
**Symbols:**

```
c0000000006520e0-c000000000652320: fuse_send_writepage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void fuse_send_writepage(struct fuse_conn *fc, struct fuse_writepage_args *wpa, loff_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffe0003774c4)
Location: fs/fuse/file.c:1627
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_flush_writepages
```
**Symbols:**

```
ffffffe0003774c4-ffffffe00037764c: fuse_send_writepage (STB_LOCAL)
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
void fuse_send_writepage(struct fuse_conn *fc, struct fuse_writepage_args *wpa, loff_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81420060)
Location: fs/fuse/file.c:1627
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_flush_writepages
```
**Symbols:**

```
ffffffff81420060-ffffffff814201aa: fuse_send_writepage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void fuse_send_writepage(struct fuse_conn *fc, struct fuse_writepage_args *wpa, loff_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81410ae0)
Location: fs/fuse/file.c:1627
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_flush_writepages
```
**Symbols:**

```
ffffffff81410ae0-ffffffff81410c2a: fuse_send_writepage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void fuse_send_writepage(struct fuse_conn *fc, struct fuse_writepage_args *wpa, loff_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8141c200)
Location: fs/fuse/file.c:1627
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_flush_writepages
```
**Symbols:**

```
ffffffff8141c200-ffffffff8141c34a: fuse_send_writepage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void fuse_send_writepage(struct fuse_conn *fc, struct fuse_writepage_args *wpa, loff_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81433260)
Location: fs/fuse/file.c:1627
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_flush_writepages
```
**Symbols:**

```
ffffffff81433260-ffffffff814333a7: fuse_send_writepage (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct fuse_writepage_args *wpa</code>
</li>
<li>
<b>Param removed. </b>
<code>struct fuse_req *req</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct fuse_mount *fm</code>
</li>
<li>
<b>Param removed. </b>
<code>struct fuse_conn *fc</code>
</li>
</ul>
</details>
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
