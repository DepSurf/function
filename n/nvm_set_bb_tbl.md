# Function: <code>nvm_set_bb_tbl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int nvm_set_bb_tbl(struct nvm_dev *dev, struct sysblk_scan *s, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/sysblk.c (ffffffff81544930)
Location: drivers/lightnvm/sysblk.c:214
Inline: False
Direct callers:
  - drivers/lightnvm/sysblk.c:nvm_dev_factory
  - drivers/lightnvm/sysblk.c:nvm_init_sysblock
```
**Symbols:**

```
ffffffff81544930-ffffffff815449fb: nvm_set_bb_tbl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int nvm_set_bb_tbl(struct nvm_dev *dev, struct sysblk_scan *s, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/sysblk.c (ffffffff81596240)
Location: drivers/lightnvm/sysblk.c:270
Inline: False
Direct callers:
  - drivers/lightnvm/sysblk.c:nvm_dev_factory
  - drivers/lightnvm/sysblk.c:nvm_init_sysblock
```
**Symbols:**

```
ffffffff81596240-ffffffff8159631a: nvm_set_bb_tbl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int nvm_set_bb_tbl(struct nvm_dev *dev, struct ppa_addr *ppas, int nr_ppas, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff815c2640)
Location: drivers/lightnvm/core.c:198
Inline: False
Direct callers:
  - drivers/lightnvm/sysblk.c:nvm_dev_factory
  - drivers/lightnvm/sysblk.c:nvm_init_sysblock
```
**Symbols:**

```
ffffffff815c2640-ffffffff815c272b: nvm_set_bb_tbl (STB_GLOBAL)
```
</details>
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct ppa_addr *ppas</code>
</li>
<li>
<b>Param added. </b>
<code>int nr_ppas</code>
</li>
<li>
<b>Param removed. </b>
<code>struct sysblk_scan *s</code>
</li>
<li>
<b>Param reordered. </b>
<code>dev, s, type</code> ➡️ <code>dev, ppas, nr_ppas, type</code>
</li>
</ul>
</details>
</li>
</ul>
