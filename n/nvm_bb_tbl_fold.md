# Function: <code>nvm_bb_tbl_fold</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int nvm_bb_tbl_fold(struct nvm_dev *dev, u8 *blks, int nr_blks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff81594330)
Location: drivers/lightnvm/core.c:436
Inline: False
Direct callers:
  - drivers/lightnvm/sysblk.c:nvm_dev_factory
  - drivers/lightnvm/sysblk.c:nvm_get_all_sysblks
  - drivers/lightnvm/sysblk.c:nvm_get_all_sysblks
```
**Symbols:**

```
ffffffff81594330-ffffffff815943b0: nvm_bb_tbl_fold (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int nvm_bb_tbl_fold(struct nvm_dev *dev, u8 *blks, int nr_blks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff815c1c20)
Location: drivers/lightnvm/core.c:534
Inline: False
Direct callers:
  - drivers/lightnvm/sysblk.c:nvm_dev_factory
  - drivers/lightnvm/sysblk.c:nvm_get_all_sysblks
  - drivers/lightnvm/sysblk.c:nvm_get_all_sysblks
```
**Symbols:**

```
ffffffff815c1c20-ffffffff815c1ca0: nvm_bb_tbl_fold (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int nvm_bb_tbl_fold(struct nvm_dev *dev, u8 *blks, int nr_blks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff815d82e0)
Location: drivers/lightnvm/core.c:850
Inline: True
```
**Symbols:**

```
ffffffff815d82e0-ffffffff815d835d: nvm_bb_tbl_fold (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int nvm_bb_tbl_fold(struct nvm_dev *dev, u8 *blks, int nr_blks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff8163ef50)
Location: drivers/lightnvm/core.c:856
Inline: True
```
**Symbols:**

```
ffffffff8163ef50-ffffffff8163efcd: nvm_bb_tbl_fold (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int nvm_bb_tbl_fold(struct nvm_dev *dev, u8 *blks, int nr_blks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff8167a300)
Location: drivers/lightnvm/core.c:816
Inline: True
```
**Symbols:**

```
ffffffff8167a300-ffffffff8167a383: nvm_bb_tbl_fold (STB_GLOBAL)
```
</details>
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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
</ul>
