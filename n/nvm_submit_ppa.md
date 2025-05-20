# Function: <code>nvm_submit_ppa</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int nvm_submit_ppa(struct nvm_dev *dev, struct ppa_addr *ppa, int nr_ppas, int opcode, int flags, void *buf, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff81542ed0)
Location: drivers/lightnvm/core.c:325
Inline: False
Direct callers:
  - drivers/lightnvm/sysblk.c:nvm_scan_block
  - drivers/lightnvm/sysblk.c:nvm_write_and_verify
  - drivers/lightnvm/sysblk.c:nvm_write_and_verify
```
**Symbols:**

```
ffffffff81542ed0-ffffffff81543073: nvm_submit_ppa (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int nvm_submit_ppa(struct nvm_dev *dev, struct ppa_addr *ppa, int nr_ppas, int opcode, int flags, void *buf, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff81594d00)
Location: drivers/lightnvm/core.c:409
Inline: False
Direct callers:
  - drivers/lightnvm/sysblk.c:nvm_write_and_verify
  - drivers/lightnvm/sysblk.c:nvm_write_and_verify
  - drivers/lightnvm/sysblk.c:nvm_scan_block
```
**Symbols:**

```
ffffffff81594d00-ffffffff81594dc2: nvm_submit_ppa (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int nvm_submit_ppa(struct nvm_dev *dev, struct ppa_addr *ppa, int nr_ppas, int opcode, int flags, void *buf, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff815c29b0)
Location: drivers/lightnvm/core.c:507
Inline: False
Direct callers:
  - drivers/lightnvm/sysblk.c:nvm_write_and_verify
  - drivers/lightnvm/sysblk.c:nvm_write_and_verify
  - drivers/lightnvm/sysblk.c:nvm_scan_block
```
**Symbols:**

```
ffffffff815c29b0-ffffffff815c2a72: nvm_submit_ppa (STB_GLOBAL)
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
