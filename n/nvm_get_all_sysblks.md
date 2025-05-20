# Function: <code>nvm_get_all_sysblks</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int nvm_get_all_sysblks(struct nvm_dev *dev, struct sysblk_scan *s, struct ppa_addr *ppas, nvm_bb_update_fn *fn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/sysblk.c (ffffffff81544540)
Location: drivers/lightnvm/sysblk.c:121
Inline: False
Direct callers:
  - drivers/lightnvm/sysblk.c:nvm_dev_factory
  - drivers/lightnvm/sysblk.c:nvm_get_sysblock
  - drivers/lightnvm/sysblk.c:nvm_update_sysblock
  - drivers/lightnvm/sysblk.c:nvm_init_sysblock
```
**Symbols:**

```
ffffffff81544540-ffffffff81544647: nvm_get_all_sysblks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int nvm_get_all_sysblks(struct nvm_dev *dev, struct sysblk_scan *s, struct ppa_addr *ppas, int get_free);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/sysblk.c (ffffffff81595df0)
Location: drivers/lightnvm/sysblk.c:162
Inline: False
Direct callers:
  - drivers/lightnvm/sysblk.c:nvm_dev_factory
  - drivers/lightnvm/sysblk.c:nvm_init_sysblock
  - drivers/lightnvm/sysblk.c:nvm_update_sysblock
  - drivers/lightnvm/sysblk.c:nvm_get_sysblock
```
**Symbols:**

```
ffffffff81595df0-ffffffff81596077: nvm_get_all_sysblks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int nvm_get_all_sysblks(struct nvm_dev *dev, struct sysblk_scan *s, struct ppa_addr *ppas, int get_free);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/sysblk.c (ffffffff815c3ab0)
Location: drivers/lightnvm/sysblk.c:163
Inline: False
Direct callers:
  - drivers/lightnvm/sysblk.c:nvm_dev_factory
  - drivers/lightnvm/sysblk.c:nvm_init_sysblock
  - drivers/lightnvm/sysblk.c:nvm_update_sysblock
  - drivers/lightnvm/sysblk.c:nvm_get_sysblock
```
**Symbols:**

```
ffffffff815c3ab0-ffffffff815c3d37: nvm_get_all_sysblks (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int get_free</code>
</li>
<li>
<b>Param removed. </b>
<code>nvm_bb_update_fn *fn</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
</ul>
