# Function: <code>nvm_erase_ppa</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int nvm_erase_ppa(struct nvm_dev *dev, struct ppa_addr *ppas, int nr_ppas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff81542e20)
Location: drivers/lightnvm/core.c:285
Inline: False
Direct callers:
  - drivers/lightnvm/sysblk.c:nvm_dev_factory
  - drivers/lightnvm/sysblk.c:nvm_update_sysblock
```
**Symbols:**

```
ffffffff81542e20-ffffffff81542ec7: nvm_erase_ppa (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int nvm_erase_ppa(struct nvm_dev *dev, struct ppa_addr *ppas, int nr_ppas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff81594a90)
Location: drivers/lightnvm/core.c:288
Inline: False
Direct callers:
  - drivers/lightnvm/sysblk.c:nvm_dev_factory
  - drivers/lightnvm/sysblk.c:nvm_update_sysblock
```
**Symbols:**

```
ffffffff81594a90-ffffffff81594b3d: nvm_erase_ppa (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int nvm_erase_ppa(struct nvm_dev *dev, struct ppa_addr *ppas, int nr_ppas, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff815c2730)
Location: drivers/lightnvm/core.c:383
Inline: False
Direct callers:
  - drivers/lightnvm/sysblk.c:nvm_dev_factory
  - drivers/lightnvm/sysblk.c:nvm_update_sysblock
```
**Symbols:**

```
ffffffff815c2730-ffffffff815c27ef: nvm_erase_ppa (STB_GLOBAL)
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
<code>int flags</code>
</li>
</ul>
</details>
</li>
</ul>
