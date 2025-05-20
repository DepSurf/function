# Function: <code>nvm_scan_block</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int nvm_scan_block(struct nvm_dev *dev, struct ppa_addr *ppa, struct nvm_system_block *sblk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/sysblk.c (ffffffff81544770)
Location: drivers/lightnvm/sysblk.c:153
Inline: False
Direct callers:
  - drivers/lightnvm/sysblk.c:nvm_get_sysblock
  - drivers/lightnvm/sysblk.c:nvm_update_sysblock
```
**Symbols:**

```
ffffffff81544770-ffffffff81544926: nvm_scan_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int nvm_scan_block(struct nvm_dev *dev, struct ppa_addr *ppa, struct nvm_system_block *sblk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/sysblk.c (ffffffff81596080)
Location: drivers/lightnvm/sysblk.c:210
Inline: False
Direct callers:
  - drivers/lightnvm/sysblk.c:nvm_update_sysblock
  - drivers/lightnvm/sysblk.c:nvm_get_sysblock
```
**Symbols:**

```
ffffffff81596080-ffffffff81596232: nvm_scan_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int nvm_scan_block(struct nvm_dev *dev, struct ppa_addr *ppa, struct nvm_system_block *sblk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/sysblk.c (ffffffff815c3d40)
Location: drivers/lightnvm/sysblk.c:212
Inline: False
Direct callers:
  - drivers/lightnvm/sysblk.c:nvm_update_sysblock
  - drivers/lightnvm/sysblk.c:nvm_get_sysblock
```
**Symbols:**

```
ffffffff815c3d40-ffffffff815c3ef2: nvm_scan_block (STB_LOCAL)
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
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
</ul>
