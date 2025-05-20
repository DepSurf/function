# Function: <code>efivar_entry_delete</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int efivar_entry_delete(struct efivar_entry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff816d1b10)
Location: drivers/firmware/efi/vars.c:597
Inline: False
Direct callers:
  - fs/efivarfs/inode.c:efivarfs_unlink
```
**Symbols:**

```
ffffffff816d1b10-ffffffff816d1c29: efivar_entry_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int efivar_entry_delete(struct efivar_entry *entry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff81734c70)
Location: drivers/firmware/efi/vars.c:587
Inline: True
Direct callers:
  - fs/efivarfs/inode.c:efivarfs_unlink
```
**Symbols:**

```
ffffffff81734c70-ffffffff81734d31: efivar_entry_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int efivar_entry_delete(struct efivar_entry *entry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff81767ca0)
Location: drivers/firmware/efi/vars.c:608
Inline: True
Direct callers:
  - fs/efivarfs/inode.c:efivarfs_unlink
```
**Symbols:**

```
ffffffff81767ca0-ffffffff81767d73: efivar_entry_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int efivar_entry_delete(struct efivar_entry *entry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff81786450)
Location: drivers/firmware/efi/vars.c:608
Inline: True
Direct callers:
  - fs/efivarfs/inode.c:efivarfs_unlink
```
**Symbols:**

```
ffffffff81786450-ffffffff81786521: efivar_entry_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int efivar_entry_delete(struct efivar_entry *entry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff817fc8b0)
Location: drivers/firmware/efi/vars.c:608
Inline: True
Direct callers:
  - fs/efivarfs/inode.c:efivarfs_unlink
```
**Symbols:**

```
ffffffff817fc8b0-ffffffff817fc986: efivar_entry_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int efivar_entry_delete(struct efivar_entry *entry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff81846040)
Location: drivers/firmware/efi/vars.c:608
Inline: True
Direct callers:
  - fs/efivarfs/inode.c:efivarfs_unlink
```
**Symbols:**

```
ffffffff81846040-ffffffff81846116: efivar_entry_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int efivar_entry_delete(struct efivar_entry *entry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff81872380)
Location: drivers/firmware/efi/vars.c:625
Inline: True
Direct callers:
  - fs/efivarfs/inode.c:efivarfs_unlink
```
**Symbols:**

```
ffffffff81872380-ffffffff81872473: efivar_entry_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int efivar_entry_delete(struct efivar_entry *entry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff818b65a0)
Location: drivers/firmware/efi/vars.c:612
Inline: True
Direct callers:
  - fs/efivarfs/inode.c:efivarfs_unlink
```
**Symbols:**

```
ffffffff818b65a0-ffffffff818b6691: efivar_entry_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int efivar_entry_delete(struct efivar_entry *entry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff818e8f00)
Location: drivers/firmware/efi/vars.c:612
Inline: True
Direct callers:
  - fs/efivarfs/inode.c:efivarfs_unlink
```
**Symbols:**

```
ffffffff818e8f00-ffffffff818e8ff1: efivar_entry_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int efivar_entry_delete(struct efivar_entry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff819bc0b0)
Location: drivers/firmware/efi/vars.c:612
Inline: False
Direct callers:
  - fs/efivarfs/inode.c:efivarfs_unlink
```
**Symbols:**

```
ffffffff819bc0b0-ffffffff819bc1a1: efivar_entry_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int efivar_entry_delete(struct efivar_entry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff819be210)
Location: drivers/firmware/efi/vars.c:604
Inline: False
Direct callers:
  - fs/efivarfs/inode.c:efivarfs_unlink
```
**Symbols:**

```
ffffffff819be210-ffffffff819be301: efivar_entry_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int efivar_entry_delete(struct efivar_entry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff819a2770)
Location: drivers/firmware/efi/vars.c:604
Inline: False
Direct callers:
  - fs/efivarfs/inode.c:efivarfs_unlink
```
**Symbols:**

```
ffffffff819a2770-ffffffff819a2861: efivar_entry_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int efivar_entry_delete(struct efivar_entry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff81a4f610)
Location: drivers/firmware/efi/vars.c:604
Inline: False
Direct callers:
  - fs/efivarfs/inode.c:efivarfs_unlink
```
**Symbols:**

```
ffffffff81a4f610-ffffffff81a4f701: efivar_entry_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int efivar_entry_delete(struct efivar_entry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff81bbe400)
Location: drivers/firmware/efi/vars.c:604
Inline: False
Direct callers:
  - fs/efivarfs/inode.c:efivarfs_unlink
```
**Symbols:**

```
ffffffff81bbe400-ffffffff81bbe50f: efivar_entry_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int efivar_entry_delete(struct efivar_entry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/efivarfs/vars.c (ffffffff8163b4d0)
Location: fs/efivarfs/vars.c:519
Inline: False
Direct callers:
  - fs/efivarfs/inode.c:efivarfs_unlink
```
**Symbols:**

```
ffffffff8163b4d0-ffffffff8163b5b2: efivar_entry_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int efivar_entry_delete(struct efivar_entry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/efivarfs/vars.c (ffffffff81673b10)
Location: fs/efivarfs/vars.c:519
Inline: False
Direct callers:
  - fs/efivarfs/inode.c:efivarfs_unlink
```
**Symbols:**

```
ffffffff81673b10-ffffffff81673bf2: efivar_entry_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int efivar_entry_delete(struct efivar_entry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/efivarfs/vars.c (ffffffff816afed0)
Location: fs/efivarfs/vars.c:523
Inline: False
Direct callers:
  - fs/efivarfs/inode.c:efivarfs_unlink
```
**Symbols:**

```
ffffffff816afed0-ffffffff816affb2: efivar_entry_delete (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int efivar_entry_delete(struct efivar_entry *entry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffff800010b5c280)
Location: drivers/firmware/efi/vars.c:612
Inline: True
Direct callers:
  - fs/efivarfs/inode.c:efivarfs_unlink
```
**Symbols:**

```
ffff800010b5c280-ffff800010b5c37c: efivar_entry_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int efivar_entry_delete(struct efivar_entry *entry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (c0c3cdc4)
Location: drivers/firmware/efi/vars.c:612
Inline: True
Direct callers:
  - fs/efivarfs/inode.c:efivarfs_unlink
```
**Symbols:**

```
c0c3cdc4-c0c3ceb0: efivar_entry_delete (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int efivar_entry_delete(struct efivar_entry *entry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff8188bc80)
Location: drivers/firmware/efi/vars.c:612
Inline: True
Direct callers:
  - fs/efivarfs/inode.c:efivarfs_unlink
```
**Symbols:**

```
ffffffff8188bc80-ffffffff8188bd71: efivar_entry_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int efivar_entry_delete(struct efivar_entry *entry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff81843600)
Location: drivers/firmware/efi/vars.c:612
Inline: True
Direct callers:
  - fs/efivarfs/inode.c:efivarfs_unlink
```
**Symbols:**

```
ffffffff81843600-ffffffff818436f1: efivar_entry_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int efivar_entry_delete(struct efivar_entry *entry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff818ddd60)
Location: drivers/firmware/efi/vars.c:612
Inline: True
Direct callers:
  - fs/efivarfs/inode.c:efivarfs_unlink
```
**Symbols:**

```
ffffffff818ddd60-ffffffff818dde51: efivar_entry_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int efivar_entry_delete(struct efivar_entry *entry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff818fa870)
Location: drivers/firmware/efi/vars.c:612
Inline: True
Direct callers:
  - fs/efivarfs/inode.c:efivarfs_unlink
```
**Symbols:**

```
ffffffff818fa870-ffffffff818fa961: efivar_entry_delete (STB_GLOBAL)
```
</details>
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
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
