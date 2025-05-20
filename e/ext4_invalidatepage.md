# Function: <code>ext4_invalidatepage</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void ext4_invalidatepage(struct page *page, unsigned int offset, unsigned int length);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81296760)
Location: fs/ext4/inode.c:3020
Inline: True
```
**Symbols:**

```
ffffffff81296760-ffffffff81296816: ext4_invalidatepage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void ext4_invalidatepage(struct page *page, unsigned int offset, unsigned int length);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812c3db0)
Location: fs/ext4/inode.c:3209
Inline: True
```
**Symbols:**

```
ffffffff812c3db0-ffffffff812c3e5b: ext4_invalidatepage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void ext4_invalidatepage(struct page *page, unsigned int offset, unsigned int length);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812d9460)
Location: fs/ext4/inode.c:3236
Inline: True
```
**Symbols:**

```
ffffffff812d9460-ffffffff812d950b: ext4_invalidatepage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void ext4_invalidatepage(struct page *page, unsigned int offset, unsigned int length);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812fd390)
Location: fs/ext4/inode.c:3352
Inline: True
Direct callers:
  - fs/ext4/inode.c:ext4_writepage
```
**Symbols:**

```
ffffffff812fd390-ffffffff812fd429: ext4_invalidatepage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ext4_invalidatepage(struct page *page, unsigned int offset, unsigned int length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81321540)
Location: fs/ext4/inode.c:3345
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_writepage
```
**Symbols:**

```
ffffffff81321540-ffffffff813215dc: ext4_invalidatepage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void ext4_invalidatepage(struct page *page, unsigned int offset, unsigned int length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8134f550)
Location: fs/ext4/inode.c:3346
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_writepage
```
**Symbols:**

```
ffffffff8134f550-ffffffff8134f5f5: ext4_invalidatepage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ext4_invalidatepage(struct page *page, unsigned int offset, unsigned int length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81367730)
Location: fs/ext4/inode.c:3378
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_writepage
```
**Symbols:**

```
ffffffff81367730-ffffffff813677d5: ext4_invalidatepage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void ext4_invalidatepage(struct page *page, unsigned int offset, unsigned int length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:3391
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_writepage
```
**Symbols:**

```
ffffffff81390b20-ffffffff81390bbe: ext4_invalidatepage (STB_LOCAL)
ffffffff8139c6d6-ffffffff8139c6e9: ext4_invalidatepage.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void ext4_invalidatepage(struct page *page, unsigned int offset, unsigned int length);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813a9be0)
Location: fs/ext4/inode.c:3354
Inline: True
Direct callers:
  - fs/ext4/inode.c:ext4_writepage
```
**Symbols:**

```
ffffffff813a9be0-ffffffff813a9c7c: ext4_invalidatepage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ext4_invalidatepage(struct page *page, unsigned int offset, unsigned int length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813f6890)
Location: fs/ext4/inode.c:3244
Inline: False
```
**Symbols:**

```
ffffffff813f6890-ffffffff813f692c: ext4_invalidatepage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ext4_invalidatepage(struct page *page, unsigned int offset, unsigned int length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81409150)
Location: fs/ext4/inode.c:3264
Inline: False
```
**Symbols:**

```
ffffffff81409150-ffffffff814091d9: ext4_invalidatepage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ext4_invalidatepage(struct page *page, unsigned int offset, unsigned int length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8140f120)
Location: fs/ext4/inode.c:3263
Inline: False
```
**Symbols:**

```
ffffffff8140f120-ffffffff8140f1a9: ext4_invalidatepage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ext4_invalidatepage(struct page *page, unsigned int offset, unsigned int length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81462060)
Location: fs/ext4/inode.c:3186
Inline: False
```
**Symbols:**

```
ffffffff81462060-ffffffff814620e6: ext4_invalidatepage (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void ext4_invalidatepage(struct page *page, unsigned int offset, unsigned int length);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffff80001047e830)
Location: fs/ext4/inode.c:3354
Inline: True
Direct callers:
  - fs/ext4/inode.c:ext4_writepage
```
**Symbols:**

```
ffff80001047e830-ffff80001047e914: ext4_invalidatepage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void ext4_invalidatepage(struct page *page, unsigned int offset, unsigned int length);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (c063f404)
Location: fs/ext4/inode.c:3354
Inline: True
Direct callers:
  - fs/ext4/inode.c:ext4_writepage
```
**Symbols:**

```
c063f404-c063f504: ext4_invalidatepage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ext4_invalidatepage(struct page *page, unsigned int offset, unsigned int length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (c0000000005a0d70)
Location: fs/ext4/inode.c:3354
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_writepage
```
**Symbols:**

```
c0000000005a0d70-c0000000005a0e84: ext4_invalidatepage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void ext4_invalidatepage(struct page *page, unsigned int offset, unsigned int length);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffe000307500)
Location: fs/ext4/inode.c:3354
Inline: True
Direct callers:
  - fs/ext4/inode.c:ext4_writepage
```
**Symbols:**

```
ffffffe000307500-ffffffe0003075bc: ext4_invalidatepage (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void ext4_invalidatepage(struct page *page, unsigned int offset, unsigned int length);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813a21c0)
Location: fs/ext4/inode.c:3354
Inline: True
Direct callers:
  - fs/ext4/inode.c:ext4_writepage
```
**Symbols:**

```
ffffffff813a21c0-ffffffff813a225c: ext4_invalidatepage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void ext4_invalidatepage(struct page *page, unsigned int offset, unsigned int length);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81392c50)
Location: fs/ext4/inode.c:3354
Inline: True
Direct callers:
  - fs/ext4/inode.c:ext4_writepage
```
**Symbols:**

```
ffffffff81392c50-ffffffff81392cec: ext4_invalidatepage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void ext4_invalidatepage(struct page *page, unsigned int offset, unsigned int length);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8139fa20)
Location: fs/ext4/inode.c:3354
Inline: True
Direct callers:
  - fs/ext4/inode.c:ext4_writepage
```
**Symbols:**

```
ffffffff8139fa20-ffffffff8139fabc: ext4_invalidatepage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void ext4_invalidatepage(struct page *page, unsigned int offset, unsigned int length);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813b4600)
Location: fs/ext4/inode.c:3354
Inline: True
Direct callers:
  - fs/ext4/inode.c:ext4_writepage
```
**Symbols:**

```
ffffffff813b4600-ffffffff813b46bc: ext4_invalidatepage (STB_LOCAL)
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
