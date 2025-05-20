# Function: <code>nvm_generic_to_addr_mode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void nvm_generic_to_addr_mode(struct nvm_dev *dev, struct nvm_rq *rqd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff81542d00)
Location: drivers/lightnvm/core.c:227
Inline: True
Direct callers:
  - drivers/lightnvm/core.c:nvm_erase_ppa
  - drivers/lightnvm/core.c:nvm_submit_ppa
  - drivers/lightnvm/sysblk.c:nvm_set_bb_tbl
```
**Symbols:**

```
ffffffff81542d00-ffffffff81542e11: nvm_generic_to_addr_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void nvm_generic_to_addr_mode(struct nvm_dev *dev, struct nvm_rq *rqd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff81594990)
Location: drivers/lightnvm/core.c:225
Inline: True
Direct callers:
  - drivers/lightnvm/core.c:__nvm_submit_ppa
  - drivers/lightnvm/core.c:nvm_erase_ppa
  - drivers/lightnvm/sysblk.c:nvm_set_bb_tbl
```
**Symbols:**

```
ffffffff81594990-ffffffff81594a8f: nvm_generic_to_addr_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void nvm_generic_to_addr_mode(struct nvm_dev *dev, struct nvm_rq *rqd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff815c2530)
Location: drivers/lightnvm/core.c:319
Inline: True
Direct callers:
  - drivers/lightnvm/core.c:__nvm_submit_ppa
  - drivers/lightnvm/core.c:nvm_erase_ppa
  - drivers/lightnvm/core.c:nvm_set_bb_tbl
```
**Symbols:**

```
ffffffff815c2530-ffffffff815c263f: nvm_generic_to_addr_mode (STB_GLOBAL)
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
