# Function: <code>nvm_write_and_verify</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int nvm_write_and_verify(struct nvm_dev *dev, struct nvm_sb_info *info, struct sysblk_scan *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/sysblk.c (ffffffff81544ac0)
Location: drivers/lightnvm/sysblk.c:270
Inline: False
Direct callers:
  - drivers/lightnvm/sysblk.c:nvm_update_sysblock
  - drivers/lightnvm/sysblk.c:nvm_init_sysblock
```
**Symbols:**

```
ffffffff81544ac0-ffffffff81544d48: nvm_write_and_verify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int nvm_write_and_verify(struct nvm_dev *dev, struct nvm_sb_info *info, struct sysblk_scan *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/sysblk.c (ffffffff815963d0)
Location: drivers/lightnvm/sysblk.c:295
Inline: False
Direct callers:
  - drivers/lightnvm/sysblk.c:nvm_init_sysblock
  - drivers/lightnvm/sysblk.c:nvm_update_sysblock
```
**Symbols:**

```
ffffffff815963d0-ffffffff81596690: nvm_write_and_verify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int nvm_write_and_verify(struct nvm_dev *dev, struct nvm_sb_info *info, struct sysblk_scan *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/sysblk.c (ffffffff815c3f00)
Location: drivers/lightnvm/sysblk.c:279
Inline: False
Direct callers:
  - drivers/lightnvm/sysblk.c:nvm_init_sysblock
  - drivers/lightnvm/sysblk.c:nvm_update_sysblock
```
**Symbols:**

```
ffffffff815c3f00-ffffffff815c41c0: nvm_write_and_verify (STB_LOCAL)
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
