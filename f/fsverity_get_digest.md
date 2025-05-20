# Function: <code>fsverity_get_digest</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int fsverity_get_digest(struct inode *inode, u8 *digest, enum hash_algo *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/measure.c (ffffffff81473610)
Location: fs/verity/measure.c:73
Inline: False
Direct callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
```
**Symbols:**

```
ffffffff81473610-ffffffff8147374d: fsverity_get_digest (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fsverity_get_digest(struct inode *inode, u8 *digest, enum hash_algo *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/measure.c (ffffffff815055f0)
Location: fs/verity/measure.c:72
Inline: False
Direct callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
```
**Symbols:**

```
ffffffff815055f0-ffffffff81505651: fsverity_get_digest (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fsverity_get_digest(struct inode *inode, u8 *raw_digest, u8 *alg, enum hash_algo *halg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/measure.c (ffffffff8153c800)
Location: fs/verity/measure.c:83
Inline: False
Direct callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
```
**Symbols:**

```
ffffffff8153c800-ffffffff8153c884: fsverity_get_digest (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fsverity_get_digest(struct inode *inode, u8 *raw_digest, u8 *alg, enum hash_algo *halg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/measure.c (ffffffff81571ae0)
Location: fs/verity/measure.c:85
Inline: False
Direct callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
```
**Symbols:**

```
ffffffff81571ae0-ffffffff81571b64: fsverity_get_digest (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u8 *raw_digest</code>
</li>
<li>
<b>Param added. </b>
<code>enum hash_algo *halg</code>
</li>
<li>
<b>Param removed. </b>
<code>u8 *digest</code>
</li>
<li>
<b>Param type changed. </b>
<code>enum hash_algo *alg</code> ➡️ <code>u8 *alg</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
