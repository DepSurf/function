# Function: <code>fuse_writepage_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/file.c (ffffffff81315830)
Location: fs/fuse/file.c:1435
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_writepages_fill
```
**Symbols:**

```
ffffffff81315830-ffffffff81315887: fuse_writepage_free.isra.22 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/file.c (ffffffff8134a010)
Location: fs/fuse/file.c:1448
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_end
```
**Symbols:**

```
ffffffff8134a010-ffffffff8134a067: fuse_writepage_free.isra.25 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/file.c (ffffffff8135f960)
Location: fs/fuse/file.c:1449
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_end
```
**Symbols:**

```
ffffffff8135f960-ffffffff8135f9b7: fuse_writepage_free.isra.25 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/file.c (ffffffff81374540)
Location: fs/fuse/file.c:1444
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_end
```
**Symbols:**

```
ffffffff81374540-ffffffff81374597: fuse_writepage_free.isra.23 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/file.c (ffffffff81399210)
Location: fs/fuse/file.c:1452
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_end
```
**Symbols:**

```
ffffffff81399210-ffffffff81399267: fuse_writepage_free.isra.24 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/file.c (ffffffff813c7f20)
Location: fs/fuse/file.c:1453
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_end
```
**Symbols:**

```
ffffffff813c7f20-ffffffff813c7f77: fuse_writepage_free.isra.28 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/file.c (ffffffff813e1160)
Location: fs/fuse/file.c:1457
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_send_writepage
```
**Symbols:**

```
ffffffff813e1160-ffffffff813e11b9: fuse_writepage_free.isra.32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/file.c (ffffffff8140cd80)
Location: fs/fuse/file.c:1512
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_send_writepage
  - fs/fuse/file.c:fuse_send_writepage
```
**Symbols:**

```
ffffffff8140cd80-ffffffff8140cdd9: fuse_writepage_free.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void fuse_writepage_free(struct fuse_writepage_args *wpa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81426890)
Location: fs/fuse/file.c:1593
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_send_writepage
  - fs/fuse/file.c:fuse_send_writepage
```
**Symbols:**

```
ffffffff81426890-ffffffff814268fe: fuse_writepage_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void fuse_writepage_free(struct fuse_writepage_args *wpa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff814768e0)
Location: fs/fuse/file.c:1566
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_writepage_add
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_send_writepage
  - fs/fuse/file.c:fuse_send_writepage
```
**Symbols:**

```
ffffffff814768e0-ffffffff8147694e: fuse_writepage_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void fuse_writepage_free(struct fuse_writepage_args *wpa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81491620)
Location: fs/fuse/file.c:1606
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_writepage_add
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_send_writepage
  - fs/fuse/file.c:fuse_send_writepage
```
**Symbols:**

```
ffffffff81491620-ffffffff8149168e: fuse_writepage_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void fuse_writepage_free(struct fuse_writepage_args *wpa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81496820)
Location: fs/fuse/file.c:1608
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_writepage_add
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_send_writepage
  - fs/fuse/file.c:fuse_send_writepage
```
**Symbols:**

```
ffffffff81496820-ffffffff8149688e: fuse_writepage_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void fuse_writepage_free(struct fuse_writepage_args *wpa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff814ee100)
Location: fs/fuse/file.c:1611
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_send_writepage
  - fs/fuse/file.c:fuse_send_writepage
```
**Symbols:**

```
ffffffff814ee100-ffffffff814ee19d: fuse_writepage_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void fuse_writepage_free(struct fuse_writepage_args *wpa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8157d900)
Location: fs/fuse/file.c:1626
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_send_writepage
  - fs/fuse/file.c:fuse_send_writepage
```
**Symbols:**

```
ffffffff8157d900-ffffffff8157d9b3: fuse_writepage_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void fuse_writepage_free(struct fuse_writepage_args *wpa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81623490)
Location: fs/fuse/file.c:1661
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_send_writepage
  - fs/fuse/file.c:fuse_send_writepage
```
**Symbols:**

```
ffffffff81623490-ffffffff81623543: fuse_writepage_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void fuse_writepage_free(struct fuse_writepage_args *wpa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8165b870)
Location: fs/fuse/file.c:1638
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_send_writepage
  - fs/fuse/file.c:fuse_send_writepage
```
**Symbols:**

```
ffffffff8165b870-ffffffff8165b923: fuse_writepage_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void fuse_writepage_free(struct fuse_writepage_args *wpa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81695550)
Location: fs/fuse/file.c:1658
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_send_writepage
  - fs/fuse/file.c:fuse_send_writepage
```
**Symbols:**

```
ffffffff81695550-ffffffff81695603: fuse_writepage_free (STB_LOCAL)
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
void fuse_writepage_free(struct fuse_writepage_args *wpa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffff80001050a4a8)
Location: fs/fuse/file.c:1593
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_send_writepage
  - fs/fuse/file.c:fuse_send_writepage
```
**Symbols:**

```
ffff80001050a4a8-ffff80001050a52c: fuse_writepage_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void fuse_writepage_free(struct fuse_writepage_args *wpa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (c06c6558)
Location: fs/fuse/file.c:1593
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_send_writepage
  - fs/fuse/file.c:fuse_send_writepage
```
**Symbols:**

```
c06c6558-c06c65cc: fuse_writepage_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void fuse_writepage_free(struct fuse_writepage_args *wpa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (c000000000650790)
Location: fs/fuse/file.c:1593
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_send_writepage
  - fs/fuse/file.c:fuse_send_writepage
```
**Symbols:**

```
c000000000650790-c000000000650844: fuse_writepage_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void fuse_writepage_free(struct fuse_writepage_args *wpa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffe000375acc)
Location: fs/fuse/file.c:1593
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_send_writepage
  - fs/fuse/file.c:fuse_send_writepage
```
**Symbols:**

```
ffffffe000375acc-ffffffe000375b54: fuse_writepage_free (STB_LOCAL)
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
void fuse_writepage_free(struct fuse_writepage_args *wpa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8141ee70)
Location: fs/fuse/file.c:1593
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_send_writepage
  - fs/fuse/file.c:fuse_send_writepage
```
**Symbols:**

```
ffffffff8141ee70-ffffffff8141eede: fuse_writepage_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void fuse_writepage_free(struct fuse_writepage_args *wpa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8140f8f0)
Location: fs/fuse/file.c:1593
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_send_writepage
  - fs/fuse/file.c:fuse_send_writepage
```
**Symbols:**

```
ffffffff8140f8f0-ffffffff8140f95e: fuse_writepage_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void fuse_writepage_free(struct fuse_writepage_args *wpa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8141b010)
Location: fs/fuse/file.c:1593
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_send_writepage
  - fs/fuse/file.c:fuse_send_writepage
```
**Symbols:**

```
ffffffff8141b010-ffffffff8141b07e: fuse_writepage_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void fuse_writepage_free(struct fuse_writepage_args *wpa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81432240)
Location: fs/fuse/file.c:1593
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_send_writepage
  - fs/fuse/file.c:fuse_send_writepage
```
**Symbols:**

```
ffffffff81432240-ffffffff814322ae: fuse_writepage_free (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
