# Function: <code>ecryptfs_calculate_md5</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ecryptfs_calculate_md5(char *dst, struct ecryptfs_crypt_stat *crypt_stat, char *src, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff81304de0)
Location: fs/ecryptfs/crypto.c:87
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv
```
**Symbols:**

```
ffffffff81304de0-ffffffff81304f47: ecryptfs_calculate_md5 (STB_LOCAL)
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
In fs/ecryptfs/crypto.c (ffffffff81339260)
Location: fs/ecryptfs/crypto.c:101
Inline: True
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
```
**Symbols:**

```
ffffffff81339260-ffffffff8133932c: ecryptfs_calculate_md5.isra.15 (STB_LOCAL)
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
In fs/ecryptfs/crypto.c (ffffffff8134f000)
Location: fs/ecryptfs/crypto.c:101
Inline: True
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
```
**Symbols:**

```
ffffffff8134f000-ffffffff8134f0cc: ecryptfs_calculate_md5.isra.17 (STB_LOCAL)
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
In fs/ecryptfs/crypto.c (ffffffff81363ab0)
Location: fs/ecryptfs/crypto.c:101
Inline: True
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
```
**Symbols:**

```
ffffffff81363ab0-ffffffff81363b7c: ecryptfs_calculate_md5.isra.18 (STB_LOCAL)
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
In fs/ecryptfs/crypto.c (ffffffff81388820)
Location: fs/ecryptfs/crypto.c:87
Inline: True
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
```
**Symbols:**

```
ffffffff81388820-ffffffff813888ec: ecryptfs_calculate_md5.isra.18 (STB_LOCAL)
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
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:87
Inline: True
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
```
**Symbols:**

```
ffffffff813b7680-ffffffff813b7738: ecryptfs_calculate_md5.isra.20 (STB_LOCAL)
ffffffff813b9a69-ffffffff813b9a84: ecryptfs_calculate_md5.isra.20.cold.27 (STB_LOCAL)
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
In fs/ecryptfs/crypto.c (ffffffff813d1c17)
Location: fs/ecryptfs/crypto.c:87
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
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
In fs/ecryptfs/crypto.c (ffffffff813fc757)
Location: fs/ecryptfs/crypto.c:73
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
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
In fs/ecryptfs/crypto.c (ffffffff81416637)
Location: fs/ecryptfs/crypto.c:73
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff81464bd5)
Location: fs/ecryptfs/crypto.c:61
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff814803a5)
Location: fs/ecryptfs/crypto.c:61
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
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
In fs/ecryptfs/crypto.c (ffffffff81485bf5)
Location: fs/ecryptfs/crypto.c:61
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
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
In fs/ecryptfs/crypto.c (ffffffff814dd315)
Location: fs/ecryptfs/crypto.c:61
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
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
In fs/ecryptfs/crypto.c (ffffffff8156b367)
Location: fs/ecryptfs/crypto.c:61
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
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
In fs/ecryptfs/crypto.c (ffffffff8160f277)
Location: fs/ecryptfs/crypto.c:61
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
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
In fs/ecryptfs/crypto.c (ffffffff816470fe)
Location: fs/ecryptfs/crypto.c:61
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
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
In fs/ecryptfs/crypto.c (ffffffff816805ae)
Location: fs/ecryptfs/crypto.c:61
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
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
In fs/ecryptfs/crypto.c (ffff8000104f7c78)
Location: fs/ecryptfs/crypto.c:73
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
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
In fs/ecryptfs/crypto.c (c06b5530)
Location: fs/ecryptfs/crypto.c:73
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
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
In fs/ecryptfs/crypto.c (c000000000639508)
Location: fs/ecryptfs/crypto.c:73
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
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
In fs/ecryptfs/crypto.c (ffffffe0003665fa)
Location: fs/ecryptfs/crypto.c:73
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
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
In fs/ecryptfs/crypto.c (ffffffff8140ec17)
Location: fs/ecryptfs/crypto.c:73
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
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
In fs/ecryptfs/crypto.c (ffffffff813ff697)
Location: fs/ecryptfs/crypto.c:73
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
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
In fs/ecryptfs/crypto.c (ffffffff8140bf97)
Location: fs/ecryptfs/crypto.c:73
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
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
In fs/ecryptfs/crypto.c (ffffffff81421c17)
Location: fs/ecryptfs/crypto.c:73
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
