# Function: <code>ecryptfs_encrypt_filename</code>

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
In fs/ecryptfs/crypto.c (ffffffff813070be)
Location: fs/ecryptfs/crypto.c:1501
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_and_encode_filename
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
In fs/ecryptfs/crypto.c (ffffffff8133b2fc)
Location: fs/ecryptfs/crypto.c:1498
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_and_encode_filename
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
In fs/ecryptfs/crypto.c (ffffffff8135108c)
Location: fs/ecryptfs/crypto.c:1498
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_and_encode_filename
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
In fs/ecryptfs/crypto.c (ffffffff81365bbc)
Location: fs/ecryptfs/crypto.c:1498
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_and_encode_filename
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
In fs/ecryptfs/crypto.c (ffffffff8138a878)
Location: fs/ecryptfs/crypto.c:1480
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_and_encode_filename
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
In fs/ecryptfs/crypto.c (ffffffff813b956c)
Location: fs/ecryptfs/crypto.c:1480
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_and_encode_filename
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
In fs/ecryptfs/crypto.c (ffffffff813d2adc)
Location: fs/ecryptfs/crypto.c:1480
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_and_encode_filename
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
In fs/ecryptfs/crypto.c (ffffffff813fd57f)
Location: fs/ecryptfs/crypto.c:1474
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_and_encode_filename
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
In fs/ecryptfs/crypto.c (ffffffff8141745f)
Location: fs/ecryptfs/crypto.c:1476
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_and_encode_filename
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int ecryptfs_encrypt_filename(struct ecryptfs_filename *filename, struct ecryptfs_mount_crypt_stat *mount_crypt_stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:1461
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_and_encode_filename
```
**Symbols:**

```
ffffffff81463880-ffffffff81463960: ecryptfs_encrypt_filename (STB_LOCAL)
ffffffff81465ec2-ffffffff81465f35: ecryptfs_encrypt_filename.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int ecryptfs_encrypt_filename(struct ecryptfs_filename *filename, struct ecryptfs_mount_crypt_stat *mount_crypt_stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:1461
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_and_encode_filename
```
**Symbols:**

```
ffffffff8147f040-ffffffff8147f120: ecryptfs_encrypt_filename (STB_LOCAL)
ffffffff81bee631-ffffffff81bee6a4: ecryptfs_encrypt_filename.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int ecryptfs_encrypt_filename(struct ecryptfs_filename *filename, struct ecryptfs_mount_crypt_stat *mount_crypt_stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:1456
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_and_encode_filename
```
**Symbols:**

```
ffffffff81484ae0-ffffffff81484bc0: ecryptfs_encrypt_filename (STB_LOCAL)
ffffffff81be066a-ffffffff81be06dd: ecryptfs_encrypt_filename.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ecryptfs_encrypt_filename(struct ecryptfs_filename *filename, struct ecryptfs_mount_crypt_stat *mount_crypt_stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:1456
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_and_encode_filename
```
**Symbols:**

```
ffffffff814dc160-ffffffff814dc240: ecryptfs_encrypt_filename (STB_LOCAL)
ffffffff81cd0e07-ffffffff81cd0e7a: ecryptfs_encrypt_filename.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ecryptfs_encrypt_filename(struct ecryptfs_filename *filename, struct ecryptfs_mount_crypt_stat *mount_crypt_stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:1456
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_and_encode_filename
```
**Symbols:**

```
ffffffff8156a050-ffffffff8156a152: ecryptfs_encrypt_filename (STB_LOCAL)
ffffffff81e8404f-ffffffff81e840ba: ecryptfs_encrypt_filename.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ecryptfs_encrypt_filename(struct ecryptfs_filename *filename, struct ecryptfs_mount_crypt_stat *mount_crypt_stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff8160dcd0)
Location: fs/ecryptfs/crypto.c:1456
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_and_encode_filename
```
**Symbols:**

```
ffffffff8160dcd0-ffffffff8160de4b: ecryptfs_encrypt_filename (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ecryptfs_encrypt_filename(struct ecryptfs_filename *filename, struct ecryptfs_mount_crypt_stat *mount_crypt_stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff81645b40)
Location: fs/ecryptfs/crypto.c:1432
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_and_encode_filename
```
**Symbols:**

```
ffffffff81645b40-ffffffff81645cbb: ecryptfs_encrypt_filename (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ecryptfs_encrypt_filename(struct ecryptfs_filename *filename, struct ecryptfs_mount_crypt_stat *mount_crypt_stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff8167f000)
Location: fs/ecryptfs/crypto.c:1432
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_and_encode_filename
```
**Symbols:**

```
ffffffff8167f000-ffffffff8167f17b: ecryptfs_encrypt_filename (STB_LOCAL)
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
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:1476
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_and_encode_filename
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
In fs/ecryptfs/crypto.c (c06b682c)
Location: fs/ecryptfs/crypto.c:1476
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_and_encode_filename
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
In fs/ecryptfs/crypto.c (c00000000063b0d8)
Location: fs/ecryptfs/crypto.c:1476
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_and_encode_filename
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
In fs/ecryptfs/crypto.c (ffffffe0003677a6)
Location: fs/ecryptfs/crypto.c:1476
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_and_encode_filename
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
In fs/ecryptfs/crypto.c (ffffffff8140fa3f)
Location: fs/ecryptfs/crypto.c:1476
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_and_encode_filename
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
In fs/ecryptfs/crypto.c (ffffffff814004bf)
Location: fs/ecryptfs/crypto.c:1476
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_and_encode_filename
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
In fs/ecryptfs/crypto.c (ffffffff8140cdbf)
Location: fs/ecryptfs/crypto.c:1476
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_and_encode_filename
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
In fs/ecryptfs/crypto.c (ffffffff81422a3f)
Location: fs/ecryptfs/crypto.c:1476
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_and_encode_filename
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
