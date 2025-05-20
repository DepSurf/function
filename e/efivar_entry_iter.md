# Function: <code>efivar_entry_iter</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int efivar_entry_iter(int (*func)(struct efivar_entry *, void *), struct list_head *head, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff816d1560)
Location: drivers/firmware/efi/vars.c:1074
Inline: False
```
**Symbols:**

```
ffffffff816d1560-ffffffff816d15f0: efivar_entry_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int efivar_entry_iter(int (*func)(struct efivar_entry *, void *), struct list_head *head, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff81734780)
Location: drivers/firmware/efi/vars.c:1065
Inline: False
```
**Symbols:**

```
ffffffff81734780-ffffffff8173480e: efivar_entry_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int efivar_entry_iter(int (*func)(struct efivar_entry *, void *), struct list_head *head, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff81767db0)
Location: drivers/firmware/efi/vars.c:1086
Inline: True
```
**Symbols:**

```
ffffffff81767db0-ffffffff81767e4c: efivar_entry_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int efivar_entry_iter(int (*func)(struct efivar_entry *, void *), struct list_head *head, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff81786690)
Location: drivers/firmware/efi/vars.c:1086
Inline: True
```
**Symbols:**

```
ffffffff81786690-ffffffff8178672c: efivar_entry_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int efivar_entry_iter(int (*func)(struct efivar_entry *, void *), struct list_head *head, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff817fcaf0)
Location: drivers/firmware/efi/vars.c:1086
Inline: True
```
**Symbols:**

```
ffffffff817fcaf0-ffffffff817fcb8e: efivar_entry_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int efivar_entry_iter(int (*func)(struct efivar_entry *, void *), struct list_head *head, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff81846280)
Location: drivers/firmware/efi/vars.c:1086
Inline: True
```
**Symbols:**

```
ffffffff81846280-ffffffff8184631e: efivar_entry_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int efivar_entry_iter(int (*func)(struct efivar_entry *, void *), struct list_head *head, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff818724b0)
Location: drivers/firmware/efi/vars.c:1143
Inline: True
```
**Symbols:**

```
ffffffff818724b0-ffffffff8187254e: efivar_entry_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int efivar_entry_iter(int (*func)(struct efivar_entry *, void *), struct list_head *head, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff818b66d0)
Location: drivers/firmware/efi/vars.c:1130
Inline: True
```
**Symbols:**

```
ffffffff818b66d0-ffffffff818b676f: efivar_entry_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int efivar_entry_iter(int (*func)(struct efivar_entry *, void *), struct list_head *head, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff818e9030)
Location: drivers/firmware/efi/vars.c:1130
Inline: True
```
**Symbols:**

```
ffffffff818e9030-ffffffff818e90cf: efivar_entry_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int efivar_entry_iter(int (*func)(struct efivar_entry *, void *), struct list_head *head, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff819bc4f0)
Location: drivers/firmware/efi/vars.c:1130
Inline: True
```
**Symbols:**

```
ffffffff819bc4f0-ffffffff819bc58f: efivar_entry_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int efivar_entry_iter(int (*func)(struct efivar_entry *, void *), struct list_head *head, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff819be690)
Location: drivers/firmware/efi/vars.c:1122
Inline: True
```
**Symbols:**

```
ffffffff819be690-ffffffff819be72f: efivar_entry_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int efivar_entry_iter(int (*func)(struct efivar_entry *, void *), struct list_head *head, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff819a2cc0)
Location: drivers/firmware/efi/vars.c:1122
Inline: True
```
**Symbols:**

```
ffffffff819a2cc0-ffffffff819a2d5f: efivar_entry_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int efivar_entry_iter(int (*func)(struct efivar_entry *, void *), struct list_head *head, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff81a4fec0)
Location: drivers/firmware/efi/vars.c:1125
Inline: True
```
**Symbols:**

```
ffffffff81a4fec0-ffffffff81a4ff5f: efivar_entry_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int efivar_entry_iter(int (*func)(struct efivar_entry *, void *), struct list_head *head, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff81bbed10)
Location: drivers/firmware/efi/vars.c:1125
Inline: True
```
**Symbols:**

```
ffffffff81bbed10-ffffffff81bbedc8: efivar_entry_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int efivar_entry_iter(int (*func)(struct efivar_entry *, void *), struct list_head *head, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/efivarfs/vars.c (ffffffff8163b8c0)
Location: fs/efivarfs/vars.c:704
Inline: False
Direct callers:
  - fs/efivarfs/super.c:efivarfs_kill_sb
  - fs/efivarfs/super.c:efivarfs_fill_super
```
**Symbols:**

```
ffffffff8163b8c0-ffffffff8163b950: efivar_entry_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int efivar_entry_iter(int (*func)(struct efivar_entry *, void *), struct list_head *head, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/efivarfs/vars.c (ffffffff81673f00)
Location: fs/efivarfs/vars.c:704
Inline: False
Direct callers:
  - fs/efivarfs/super.c:efivarfs_fill_super
```
**Symbols:**

```
ffffffff81673f00-ffffffff81673f90: efivar_entry_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int efivar_entry_iter(int (*func)(struct efivar_entry *, void *), struct list_head *head, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/efivarfs/vars.c (ffffffff816b02c0)
Location: fs/efivarfs/vars.c:708
Inline: False
Direct callers:
  - fs/efivarfs/super.c:efivarfs_kill_sb
```
**Symbols:**

```
ffffffff816b02c0-ffffffff816b0350: efivar_entry_iter (STB_GLOBAL)
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
int efivar_entry_iter(int (*func)(struct efivar_entry *, void *), struct list_head *head, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffff800010b5c718)
Location: drivers/firmware/efi/vars.c:1130
Inline: True
```
**Symbols:**

```
ffff800010b5c718-ffff800010b5c7d4: efivar_entry_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int efivar_entry_iter(int (*func)(struct efivar_entry *, void *), struct list_head *head, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (c0c3cef4)
Location: drivers/firmware/efi/vars.c:1130
Inline: True
```
**Symbols:**

```
c0c3cef4-c0c3cf9c: efivar_entry_iter (STB_GLOBAL)
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
int efivar_entry_iter(int (*func)(struct efivar_entry *, void *), struct list_head *head, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff8188bdb0)
Location: drivers/firmware/efi/vars.c:1130
Inline: True
```
**Symbols:**

```
ffffffff8188bdb0-ffffffff8188be4f: efivar_entry_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int efivar_entry_iter(int (*func)(struct efivar_entry *, void *), struct list_head *head, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff81843730)
Location: drivers/firmware/efi/vars.c:1130
Inline: True
```
**Symbols:**

```
ffffffff81843730-ffffffff818437cf: efivar_entry_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int efivar_entry_iter(int (*func)(struct efivar_entry *, void *), struct list_head *head, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff818dde90)
Location: drivers/firmware/efi/vars.c:1130
Inline: True
```
**Symbols:**

```
ffffffff818dde90-ffffffff818ddf2f: efivar_entry_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int efivar_entry_iter(int (*func)(struct efivar_entry *, void *), struct list_head *head, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff818fa9a0)
Location: drivers/firmware/efi/vars.c:1130
Inline: True
```
**Symbols:**

```
ffffffff818fa9a0-ffffffff818faa3f: efivar_entry_iter (STB_GLOBAL)
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
