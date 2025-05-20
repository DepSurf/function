# Function: <code>nvm_setup_sysblk_scan</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void nvm_setup_sysblk_scan(struct nvm_dev *dev, struct sysblk_scan *s, struct ppa_addr *sysblk_ppas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/sysblk.c (ffffffff81544d50)
Location: drivers/lightnvm/sysblk.c:89
Inline: False
Direct callers:
  - drivers/lightnvm/sysblk.c:nvm_dev_factory
  - drivers/lightnvm/sysblk.c:nvm_get_sysblock
  - drivers/lightnvm/sysblk.c:nvm_update_sysblock
  - drivers/lightnvm/sysblk.c:nvm_init_sysblock
```
**Symbols:**

```
ffffffff81544d50-ffffffff81544df4: nvm_setup_sysblk_scan (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void nvm_setup_sysblk_scan(struct nvm_dev *dev, struct sysblk_scan *s, struct ppa_addr *sysblk_ppas);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/sysblk.c (ffffffff81596320)
Location: drivers/lightnvm/sysblk.c:91
Inline: False
Direct callers:
  - drivers/lightnvm/sysblk.c:nvm_dev_factory
  - drivers/lightnvm/sysblk.c:nvm_init_sysblock
  - drivers/lightnvm/sysblk.c:nvm_update_sysblock
  - drivers/lightnvm/sysblk.c:nvm_get_sysblock
```
**Symbols:**

```
ffffffff81596320-ffffffff815963cc: nvm_setup_sysblk_scan (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void nvm_setup_sysblk_scan(struct nvm_dev *dev, struct sysblk_scan *s, struct ppa_addr *sysblk_ppas);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/sysblk.c (ffffffff815c3a00)
Location: drivers/lightnvm/sysblk.c:92
Inline: False
Direct callers:
  - drivers/lightnvm/sysblk.c:nvm_dev_factory
  - drivers/lightnvm/sysblk.c:nvm_init_sysblock
  - drivers/lightnvm/sysblk.c:nvm_update_sysblock
  - drivers/lightnvm/sysblk.c:nvm_get_sysblock
```
**Symbols:**

```
ffffffff815c3a00-ffffffff815c3aac: nvm_setup_sysblk_scan (STB_LOCAL)
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
