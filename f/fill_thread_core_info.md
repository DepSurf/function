# Function: <code>fill_thread_core_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/binfmt_elf.c (ffffffff81267100)
Location: fs/binfmt_elf.c:1635
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff81269d10)
Location: fs/binfmt_elf.c:1635
Inline: True
```
**Symbols:**

```
ffffffff81267100-ffffffff8126746b: fill_thread_core_info.isra.7 (STB_LOCAL)
ffffffff81269d10-ffffffff81269ff9: fill_thread_core_info.isra.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff8129486d)
Location: fs/binfmt_elf.c:1643
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff812974f7)
Location: fs/binfmt_elf.c:1643
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff812a951d)
Location: fs/binfmt_elf.c:1635
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff812ac037)
Location: fs/binfmt_elf.c:1635
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff812b5e7a)
Location: fs/binfmt_elf.c:1694
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff812b8f07)
Location: fs/binfmt_elf.c:1694
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff812d96ff)
Location: fs/binfmt_elf.c:1708
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff812dc7e0)
Location: fs/binfmt_elf.c:1708
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/binfmt_elf.c (ffffffff81303f60)
Location: fs/binfmt_elf.c:1722
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff81307870)
Location: fs/binfmt_elf.c:1722
Inline: True
```
**Symbols:**

```
ffffffff81303f60-ffffffff81304333: fill_thread_core_info.isra.9 (STB_LOCAL)
ffffffff81307870-ffffffff81307c40: fill_thread_core_info.isra.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/binfmt_elf.c (ffffffff813196b0)
Location: fs/binfmt_elf.c:1722
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff8131d080)
Location: fs/binfmt_elf.c:1722
Inline: True
```
**Symbols:**

```
ffffffff813196b0-ffffffff81319a83: fill_thread_core_info.isra.9 (STB_LOCAL)
ffffffff8131d080-ffffffff8131d450: fill_thread_core_info.isra.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff813423b6)
Location: fs/binfmt_elf.c:1725
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff81345cfc)
Location: fs/binfmt_elf.c:1725
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff8135a7ec)
Location: fs/binfmt_elf.c:1699
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff8135dfff)
Location: fs/binfmt_elf.c:1699
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate ⚠️</summary>

```c
int fill_thread_core_info(struct elf_thread_core_info *t, const struct user_regset_view *view, long int signr, size_t *total);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff8139f6b0)
Location: fs/binfmt_elf.c:1819
Inline: False
```
```
In fs/compat_binfmt_elf.c (ffffffff813a2bb0)
Location: fs/binfmt_elf.c:1819
Inline: False
```
**Symbols:**

```
ffffffff8139f6b0-ffffffff8139f930: fill_thread_core_info (STB_LOCAL)
ffffffff813a2bb0-ffffffff813a2e56: fill_thread_core_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate ⚠️</summary>

```c
int fill_thread_core_info(struct elf_thread_core_info *t, const struct user_regset_view *view, long int signr, size_t *total);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff813b0270)
Location: fs/binfmt_elf.c:1727
Inline: False
```
```
In fs/compat_binfmt_elf.c (ffffffff813b3c30)
Location: fs/binfmt_elf.c:1727
Inline: False
```
**Symbols:**

```
ffffffff813b0270-ffffffff813b0444: fill_thread_core_info (STB_LOCAL)
ffffffff813b3c30-ffffffff813b3e20: fill_thread_core_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate ⚠️</summary>

```c
int fill_thread_core_info(struct elf_thread_core_info *t, const struct user_regset_view *view, long int signr, size_t *total);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff813b73a0)
Location: fs/binfmt_elf.c:1730
Inline: False
```
```
In fs/compat_binfmt_elf.c (ffffffff813baaa0)
Location: fs/binfmt_elf.c:1730
Inline: False
```
**Symbols:**

```
ffffffff813b73a0-ffffffff813b7687: fill_thread_core_info (STB_LOCAL)
ffffffff813baaa0-ffffffff813baded: fill_thread_core_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate ⚠️</summary>

```c
int fill_thread_core_info(struct elf_thread_core_info *t, const struct user_regset_view *view, long int signr, size_t *total);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff81407080)
Location: fs/binfmt_elf.c:1732
Inline: False
```
```
In fs/compat_binfmt_elf.c (ffffffff8140a7a0)
Location: fs/binfmt_elf.c:1732
Inline: False
```
**Symbols:**

```
ffffffff81407080-ffffffff81407367: fill_thread_core_info (STB_LOCAL)
ffffffff8140a7a0-ffffffff8140aaed: fill_thread_core_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate ⚠️</summary>

```c
int fill_thread_core_info(struct elf_thread_core_info *t, const struct user_regset_view *view, long int signr, struct elf_note_info *info);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff8147bbe0)
Location: fs/binfmt_elf.c:1767
Inline: False
Direct callers:
  - fs/binfmt_elf.c:fill_note_info
```
```
In fs/compat_binfmt_elf.c (ffffffff8147f500)
Location: fs/binfmt_elf.c:1767
Inline: False
Direct callers:
  - fs/compat_binfmt_elf.c:fill_note_info
```
**Symbols:**

```
ffffffff8147bbe0-ffffffff8147bf2a: fill_thread_core_info (STB_LOCAL)
ffffffff8147f500-ffffffff8147f8a3: fill_thread_core_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate ⚠️</summary>

```c
int fill_thread_core_info(struct elf_thread_core_info *t, const struct user_regset_view *view, long int signr, struct elf_note_info *info);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff8150e620)
Location: fs/binfmt_elf.c:1762
Inline: False
Direct callers:
  - fs/binfmt_elf.c:fill_note_info
```
```
In fs/compat_binfmt_elf.c (ffffffff81512650)
Location: fs/binfmt_elf.c:1762
Inline: False
Direct callers:
  - fs/compat_binfmt_elf.c:fill_note_info
```
**Symbols:**

```
ffffffff8150e620-ffffffff8150e96a: fill_thread_core_info (STB_LOCAL)
ffffffff81512650-ffffffff815129f3: fill_thread_core_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate ⚠️</summary>

```c
int fill_thread_core_info(struct elf_thread_core_info *t, const struct user_regset_view *view, long int signr, struct elf_note_info *info);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff81545de0)
Location: fs/binfmt_elf.c:1767
Inline: False
Direct callers:
  - fs/binfmt_elf.c:fill_note_info
```
```
In fs/compat_binfmt_elf.c (ffffffff8154a090)
Location: fs/binfmt_elf.c:1767
Inline: False
Direct callers:
  - fs/compat_binfmt_elf.c:fill_note_info
```
**Symbols:**

```
ffffffff81545de0-ffffffff81546129: fill_thread_core_info (STB_LOCAL)
ffffffff8154a090-ffffffff8154a433: fill_thread_core_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate ⚠️</summary>

```c
int fill_thread_core_info(struct elf_thread_core_info *t, const struct user_regset_view *view, long int signr, struct elf_note_info *info);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff8157b2c0)
Location: fs/binfmt_elf.c:1702
Inline: False
Direct callers:
  - fs/binfmt_elf.c:fill_note_info
```
```
In fs/compat_binfmt_elf.c (ffffffff8157f0a0)
Location: fs/binfmt_elf.c:1702
Inline: False
Direct callers:
  - fs/compat_binfmt_elf.c:fill_note_info
```
**Symbols:**

```
ffffffff8157b2c0-ffffffff8157b616: fill_thread_core_info (STB_LOCAL)
ffffffff8157f0a0-ffffffff8157f464: fill_thread_core_info (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffff80001041fe00)
Location: fs/binfmt_elf.c:1699
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffff800010423960)
Location: fs/binfmt_elf.c:1699
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (c05e82f8)
Location: fs/binfmt_elf.c:1699
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (c00000000052ecb8)
Location: fs/binfmt_elf.c:1699
Inline: True
```
```
In fs/compat_binfmt_elf.c (c0000000005328d8)
Location: fs/binfmt_elf.c:1699
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffe0002c0dbe)
Location: fs/binfmt_elf.c:1699
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff81352dcc)
Location: fs/binfmt_elf.c:1699
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff813565df)
Location: fs/binfmt_elf.c:1699
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff81343aac)
Location: fs/binfmt_elf.c:1699
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff8134729f)
Location: fs/binfmt_elf.c:1699
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff8135089c)
Location: fs/binfmt_elf.c:1699
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff813540af)
Location: fs/binfmt_elf.c:1699
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff81363e1c)
Location: fs/binfmt_elf.c:1699
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff81367870)
Location: fs/binfmt_elf.c:1699
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct elf_note_info *info</code>
</li>
<li>
<b>Param removed. </b>
<code>size_t *total</code>
</li>
</ul>
</details>
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
