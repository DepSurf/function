# Function: <code>ext4_da_invalidatepage</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void ext4_da_invalidatepage(struct page *page, unsigned int offset, unsigned int length);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81297260)
Location: fs/ext4/inode.c:2860
Inline: True
```
**Symbols:**

```
ffffffff81297260-ffffffff81297587: ext4_da_invalidatepage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void ext4_da_invalidatepage(struct page *page, unsigned int offset, unsigned int length);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812c4880)
Location: fs/ext4/inode.c:3049
Inline: True
```
**Symbols:**

```
ffffffff812c4880-ffffffff812c4bb1: ext4_da_invalidatepage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void ext4_da_invalidatepage(struct page *page, unsigned int offset, unsigned int length);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812d9f30)
Location: fs/ext4/inode.c:3076
Inline: True
```
**Symbols:**

```
ffffffff812d9f30-ffffffff812da261: ext4_da_invalidatepage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void ext4_da_invalidatepage(struct page *page, unsigned int offset, unsigned int length);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812fde20)
Location: fs/ext4/inode.c:3192
Inline: True
```
**Symbols:**

```
ffffffff812fde20-ffffffff812fe11b: ext4_da_invalidatepage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void ext4_da_invalidatepage(struct page *page, unsigned int offset, unsigned int length);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81322610)
Location: fs/ext4/inode.c:3185
Inline: True
```
**Symbols:**

```
ffffffff81322610-ffffffff8132290e: ext4_da_invalidatepage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void ext4_da_invalidatepage(struct page *page, unsigned int offset, unsigned int length);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81350fc0)
Location: fs/ext4/inode.c:3186
Inline: True
```
**Symbols:**

```
ffffffff81350fc0-ffffffff813512c4: ext4_da_invalidatepage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void ext4_da_invalidatepage(struct page *page, unsigned int offset, unsigned int length);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81368320)
Location: fs/ext4/inode.c:3217
Inline: True
```
**Symbols:**

```
ffffffff81368320-ffffffff8136847b: ext4_da_invalidatepage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void ext4_da_invalidatepage(struct page *page, unsigned int offset, unsigned int length);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813912e0)
Location: fs/ext4/inode.c:3230
Inline: True
```
**Symbols:**

```
ffffffff813912e0-ffffffff8139142f: ext4_da_invalidatepage (STB_LOCAL)
```
</details>
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
</ul>
