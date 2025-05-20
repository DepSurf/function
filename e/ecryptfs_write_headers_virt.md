# Function: <code>ecryptfs_write_headers_virt</code>

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
In fs/ecryptfs/crypto.c (ffffffff81306545)
Location: fs/ecryptfs/crypto.c:1102
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
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
In fs/ecryptfs/crypto.c (ffffffff8133a8fe)
Location: fs/ecryptfs/crypto.c:1095
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
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
In fs/ecryptfs/crypto.c (ffffffff8135069b)
Location: fs/ecryptfs/crypto.c:1095
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
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
In fs/ecryptfs/crypto.c (ffffffff813651ab)
Location: fs/ecryptfs/crypto.c:1095
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
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
In fs/ecryptfs/crypto.c (ffffffff81389e7b)
Location: fs/ecryptfs/crypto.c:1079
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
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
In fs/ecryptfs/crypto.c (ffffffff813b8cdb)
Location: fs/ecryptfs/crypto.c:1079
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
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
In fs/ecryptfs/crypto.c (ffffffff813d224b)
Location: fs/ecryptfs/crypto.c:1079
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
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
In fs/ecryptfs/crypto.c (ffffffff813fccae)
Location: fs/ecryptfs/crypto.c:1064
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
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
In fs/ecryptfs/crypto.c (ffffffff81416b8e)
Location: fs/ecryptfs/crypto.c:1066
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ecryptfs_write_headers_virt(char *page_virt, size_t max, size_t *size, struct ecryptfs_crypt_stat *crypt_stat, struct dentry *ecryptfs_dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff81463e10)
Location: fs/ecryptfs/crypto.c:1051
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
**Symbols:**

```
ffffffff81463e10-ffffffff81463f2a: ecryptfs_write_headers_virt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ecryptfs_write_headers_virt(char *page_virt, size_t max, size_t *size, struct ecryptfs_crypt_stat *crypt_stat, struct dentry *ecryptfs_dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff8147f5d0)
Location: fs/ecryptfs/crypto.c:1051
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
**Symbols:**

```
ffffffff8147f5d0-ffffffff8147f6ea: ecryptfs_write_headers_virt (STB_LOCAL)
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
In fs/ecryptfs/crypto.c (ffffffff8148626c)
Location: fs/ecryptfs/crypto.c:1046
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
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
In fs/ecryptfs/crypto.c (ffffffff814dd9fc)
Location: fs/ecryptfs/crypto.c:1046
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
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
In fs/ecryptfs/crypto.c (ffffffff8156bab9)
Location: fs/ecryptfs/crypto.c:1046
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
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
In fs/ecryptfs/crypto.c (ffffffff8160fae9)
Location: fs/ecryptfs/crypto.c:1046
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
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
In fs/ecryptfs/crypto.c (ffffffff81647979)
Location: fs/ecryptfs/crypto.c:1022
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
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
In fs/ecryptfs/crypto.c (ffffffff81680e29)
Location: fs/ecryptfs/crypto.c:1022
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
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
In fs/ecryptfs/crypto.c (ffff8000104f8284)
Location: fs/ecryptfs/crypto.c:1066
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
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
In fs/ecryptfs/crypto.c (c06b5acc)
Location: fs/ecryptfs/crypto.c:1066
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
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
In fs/ecryptfs/crypto.c (c00000000063a08c)
Location: fs/ecryptfs/crypto.c:1066
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
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
In fs/ecryptfs/crypto.c (ffffffe000366b86)
Location: fs/ecryptfs/crypto.c:1066
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
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
In fs/ecryptfs/crypto.c (ffffffff8140f16e)
Location: fs/ecryptfs/crypto.c:1066
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
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
In fs/ecryptfs/crypto.c (ffffffff813ffbee)
Location: fs/ecryptfs/crypto.c:1066
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
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
In fs/ecryptfs/crypto.c (ffffffff8140c4ee)
Location: fs/ecryptfs/crypto.c:1066
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
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
In fs/ecryptfs/crypto.c (ffffffff8142216e)
Location: fs/ecryptfs/crypto.c:1066
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
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
